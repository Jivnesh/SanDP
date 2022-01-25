Official code for the paper ["Systematic Investigation of Strategies Tailored for Low-Resource Settings for Sanskrit Dependency Parsing"]().
If you use this code please cite our paper.

## Requirements

* Python 3.7 
* Pytorch 1.1.0 
* Cuda 9.0 
* Gensim 3.8.1

We assume that you have installed conda beforehand. 

```
conda install pytorch==1.1.0 torchvision==0.3.0 cudatoolkit=9.0 -c pytorch
pip install gensim==3.8.1
```
## Data
* Pretrained FastText embeddings for STBC/VST can be obtained from [here](https://drive.google.com/drive/folders/1SwdEqikTq-N2vOL7QSUX2vqi3faZE7bq?usp=sharing). Make sure that `.txt` file is placed at `data/`
* The main results are reported on the systems trained by combining train and dev splits. 



## How to train model
To run proposed system: (1) Pretraining (2) Integration, then simply run bash script `run_STBC.sh` or `run_VST.sh` for the respective dataset.

```bash
bash run_STBC.sh

```


## Citation

If you use our tool, we'd appreciate if you cite the following paper:

<!-- ```
@misc{sandhan2021little,
      title={Systematic Investigation of Strategies Tailored for Low-Resource Settings for Sanskrit Dependency Parsing}, 
      author={Jivnesh Sandhan and Laxmidhar Behera and Pawan Goyal},
      year={2022},
      eprint={-},
      archivePrefix={TALLIP},
      primaryClass={cs.CL}
}
``` -->

## Acknowledgements
Much of the base code is from ["DCST Implementation"](https://github.com/rotmanguy/DCST)
