# tf_CFO
Tensorflow implementation of [CFO: Conditional Focused Neural Question Answering with Large-scale Knowledge Bases](https://www.aclweb.org/anthology/P/P16/P16-1076.pdf)

## Requirement
- python >= 3.5
- tensorflow >= 1.4
- pickle
- numpy
- gensim
- nltk
- fuzzywuzzy

## Preprocessing
Goto `data_preprocess` directory and run the scripts (might take some time):

1. fetch dataset
```
sh fetch.sh
```
Update: For those who are blocked, here's the link of BaiduYunPan to download the dataset: [https://pan.baidu.com/s/1RBFQHuQDHuuESu4fGkmeMw](https://pan.baidu.com/s/1RBFQHuQDHuuESu4fGkmeMw) (password: 6mpi)

2. preprocess data
```
sh preprocess.sh
```

## Training
- The QA system consists of 3 components: **entity detection**, **relation network** and **subject network**.
- Goto corresponding directory and refer to README.md to finish training and testing.

## Inference
Goto ``inference`` folder and refer to README.md to get test result.

## Reference
- [https://github.com/castorini/BuboQA](https://github.com/castorini/BuboQA)
- [https://github.com/ZichaoHuang/TransE](https://github.com/ZichaoHuang/TransE)
- [https://github.com/zihangdai/cfo](https://github.com/zihangdai/cfo)


## Download processed data
Processed data are also available, feel free to download: [https://pan.baidu.com/s/1M_674aselMx8LtLagr0AcQ](https://pan.baidu.com/s/1M_674aselMx8LtLagr0AcQ) (password：azen)
