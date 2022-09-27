# Performance analysis of transformer-based architectures and their ensembles to detect trait-based cyberbullying

# Multi-Class Text Classification with Transformers

## Prerequisites
- Python 3
- CPU or NVIDIA GPU + CUDA CuDNN



### Getting started


- Install PyTorch and other dependencies.

  please run the command `pip install -r requirements.txt`.

### Training and Evaluation
- Go to the `Scripts` directory:
```bash
cd Scripts
```

- Train stand-alone model (BERT-base-uncased) with GPU support:
```bash
python train.py
```
- Train stand-alone model (BERT-base-uncased) with CPU only:
```bash
python train.py --device CPU
```
- Train stand-alone model with Twitter-parsed dataset:
```bash
python train.py --dataset Twitter
```
Information regarding other training parameters can be found at `Scripts/common.py` file.

Fine-tuned models will be saved at `../Models/` folder.\
Evaluation output files will be saved at `../Output/` folder.\
Figures will be saved at `../Figures/` folder.


### Citation
If you use this code for your research, please cite our [paper](https://link.springer.com/article/10.1007/s13278-022-00934-4).
```
@article{Ahmed2022PerformanceAO,
  title={Performance analysis of transformer-based architectures and their ensembles to detect trait-based cyberbullying},
  author={Tasnim Ahmed and Shahriar Ivan and Mohsinul Kabir and Hasan Mahmud and Kamrul Hasan},
  journal={Social Network Analysis and Mining},
  year={2022},
  volume={12},
  pages={1-17}
}

```

 

 
