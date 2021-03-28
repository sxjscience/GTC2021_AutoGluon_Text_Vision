# GTC2021 Presentation "S31667: Automatically Build Machine Learning Models for Vision and Text with AutoGluon" 

Presenter: [Xingjian Shi](https://sxjscience.github.io/), [Zhi Zhang]( https://zhreshold.github.io), (Amazon Web Services)

## Content

- [AutoGluon Text: Quick Start](autogluon_text_demo1.ipynb)
- [AutoGluon Text: Multimodal Table with Text](autogluon_text_demo2.ipynb)
- [AutoGluon: Combining BERT/Transformers and Classical Tabular Models](autogluon_text_demo3.ipynb)
- [AutoGluon Vision 101](autogluon-vision.ipynb)

## Instruction about Configuring the SageMaker Instance

For the text demo (the first three notebooks), we use will create a [SageMaker notebook instance](https://docs.aws.amazon.com/sagemaker/latest/dg/nbi.html) with `ml.p3.2xlarge` instance type. For the last notebook about vision, 
we will create an instance with `ml.p3.8xlarge` instance type.

To run the notebook, you will need to create the instance and use the `conda_python3` kernel. 
You may try to install the dependencies via the following commands. 

```
bash
conda activate python3
python3 -m pip install autogluon
python3 -m pip install mxnet-cu102==1.7.0
python3 -m pip install openpyxl
```
