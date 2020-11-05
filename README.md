# Translation-from-to-Arabic-and-English
This repo contains my work to train and test [**BERT-fused model**](https://github.com/bert-nmt/bert-nmt) in Arabic-English language pairs.

## About BERT-fused model
This model is introduced in [Incorporating BERT into NMT](https://arxiv.org/abs/2002.06823) paper. This paper was published in ICLR conference 2020.
This model makes use of BERT as word embedding for transformer model.
To learn more about BERT, transformer and BERT-fused, please check the papers **in the given order**:

1. [Attention is all you need!](https://arxiv.org/abs/1706.03762)

2. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)

3. [Incorporating BERT into NMT](https://arxiv.org/abs/2002.06823)

You may also check [my report](https://drive.google.com/open?id=1kzgvYoFWDgLwprDhZY1hNolhR1uPhIHf). It includes details about these models and my model description. In other words, this README and details about the models in an organized manner.

Note: my report has some issues in linking to images. I'll remove this note after fixing them.

# Installation
In order to **use these models**, you should:

1. clone [BERT-NMT](https://github.com/bert-nmt/bert-nmt) github repo.

2. 2. Download  [this google drive folder](https://drive.google.com/open?id=1cllkvm5ROrMZXdrVG9XEf6VM2cXG1737)
    - The folder is named as **BERT-NMT** to make it easy to know where to put files.
    - The content of BERT-NMT google drive should be copied as is in the local copy of cloned repo.

3. Update pathes to files of training and generation in corresponding **.sh** files.

4. Check that the configurations of the model are suitable for you.

# Specifications of the machine
Since we need GPUs and they are not easily accessible, I need to illustrate specifications of the machine used in my project. It is built on Google Cloud Platform (GCP):
* 8 VCPUs
* 52GB RAM
* 4 Nvidia Tesla T4 GPUs
* 400GB storage (Boot storage is enough)



# TODO
We will add more details day by day to this README. If you are in a hurry, contact me at [e-mail](mailto:mohamed.fayed.425@gmail.com).

