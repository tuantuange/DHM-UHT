# DHM-UHT
This is the code of paper [Unsupervised Meta-Learning via Dynamic Head and Heterogeneous Task Construction for Few-Shot Classification](https://arxiv.org/abs/2410.02267)

This is a minimalist and high readability version of the DHM-UHT ( removing all details that affect readability such as verbose, checkpoint, etc.). These files include the necessary steps for unsupervised meta-learning and stability analysis of model training.

Please ensure all datasets are organized in the format: dataset/class/image

```
python omniglot_main.py --algo=MAML --clustering=DBSCAN

python miniimagenet_main.py --algo=MAML --clustering=DBSCAN

python domainnet_main.py --algo=ANIL --clustering=DBSCAN
```

Optional parameters are MAML/ANIL, DBSCAN/Kmeans


The full code, data, and tutorials will be released in on month after the paper is accepted. Thank you for your understanding.
