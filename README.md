# MIST-SMMD:A Spatio-Temporal Information Extraction Method Based on Multimodal Social Media Data
### [Preprint](https://www.preprints.org/) | [Paper](https://www.mdpi.com/journal/ijgi)
<br/>

>A spatio-temporal information extraction method based on multimodal social media data: A case study on urban inundation  
>[Yilong Wu](https://github.com/uyoin), [Rongyu Zhang](https://github.com/hz157), [Yingjie Chen](https://github.com/FalleNSakura2002), [Zhenfei Cui](http://www.cad.zju.edu.cn/home/bao/), [Xinyi Liu](http://www.cad.zju.edu.cn/home/xzhou/), [Jiayi Zhang](http://www.cad.zju.edu.cn/home/bao/), [Yong Wu](http://geo.fjnu.edu.cn/3e/21/c4964a81441/page.htm)<sup>*</sup>  
> Nodata  

Discussions about the paper are welcomed in the [discussion panel](https://github.com/discussions).

![Data](doc/images/20230320110202.gif)

## Colab demo
Want to run MIST-SMMD with custom image pairs without configuring your own GPU environment? Try the Colab demo:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YUyLpwX7LgOK9FaraktSvX4nd2851qe2?usp=sharing)

## Installation
**Conda:**
```bash
conda env create -f environment.yaml
conda activate mist
```
**Pip:**
``` bash
pip install -r requirements.txt
```
**Use Tsinghua University Mirrors:**
``` bash
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```
**The spacy language pack needs to be installed manually:**
``` bash
python -m spacy download zh_core_web_trf
```

### Config File
Changeable configurations are in the config/config.py file, just modify the parameters in [config/config.py](src/config/config.py)
