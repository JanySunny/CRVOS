# CRVOS: Clue Refining Network for Video Object Segmentation

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/crvos-clue-refining-network-for-video-object/visual-object-tracking-on-davis-2016)](https://paperswithcode.com/sota/visual-object-tracking-on-davis-2016?p=crvos-clue-refining-network-for-video-object)

#### Suhwan Cho, MyeongAh Cho, Tae-young Chung, Heansung Lee, Sangyoun Lee

arXiv paper: [[pdf]](https://arxiv.org/pdf/2002.03651.pdf)
___


## How to run
1. Download [DAVIS 2017](https://davischallenge.org/davis2017/code.html) and [pre-trained model](https://drive.google.com/open?id=1ypjAb_cacM1zPILUFdXY1R-fRPWfXEzi).

2. Modify "local_config.py".

3. Check fps of CRVOS.
```
python test.py --fps
```

4. Save the outputs of CRVOS.
```
python test.py --save
```

## How to evaluate
Official evaluation code can only deal with DAVIS 2017. 

If you want to evaluate the model on both DAVIS 2016 and DAVIS 2017, use my code.

[[Official evaluation code]](https://github.com/davisvideochallenge/davis2017-evaluation)

[[My evaluation code]](https://github.com/suhwan-cho/davis-evaluation)


## Citation
```
@article{cho2020crvos,
  title={CRVOS: Clue Refining Network for Video Object Segmentation},
  author={Cho, Suhwan and Cho, MyeongAh and Chung, Tae-young and Lee, Heansung and Lee, Sangyoun},
  journal={arXiv preprint arXiv:2002.03651},
  year={2020}
}
```

## Acknowledgements
This code is built on [joakimjohnander/agame-vos](https://github.com/joakimjohnander/agame-vos). We appreciate the authors sharing the code.
