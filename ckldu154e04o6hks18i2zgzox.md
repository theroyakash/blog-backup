## Machine Learning Issue #02

Welcome to the machine learning issue section of my publications. This section is a weekly, sometimes bi-weekly blog with the most important and interesting stories in the machine learning field. You can follow the blog for free.

## Schedule of new articles
I manage the entire blog all by myself. I intend to post biweekly, but if I'm busy with university or something then I'll delay this delivery by a week.

Welcome to the 2nd issue of machine learning issues. I worked tirelessly throughout the week to find you the best of the best research in machine learning and the field of AI.

If you like the kind of articles I publish and follow my weekly machine learning issues subscribe to my newsletter.

Now let's get started with cool researches for this month.

### Why machine learning algorithms are hard to tune?
Read this [here](https://engraved.ghost.io/why-machine-learning-algorithms-are-hard-to-tune)

In machine learning, linear combinations of losses are all over the place. In fact, they are commonly used as the standard approach, despite that they are a perilous area full of dicey pitfalls. Especially regarding how these linear combinations make your algorithm hard to tune.

[![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1613025383277/qT41p1MVB.png)](https://github.iamroyakash.com/AKDSFramework-docs/)

### Technical Challenges for Training Fair Neural Networks

Read the research [here](https://arxiv.org/pdf/2102.06764v1.pdf)

As machine learning algorithms have been widely deployed across applications, many concerns have been raised over the fairness of their predictions, especially in high-stakes settings (such as facial recognition and medical imaging). To respond to these concerns, the community has proposed and formalized various notions of fairness as well as methods for rectifying unfair behavior. While fairness constraints have been studied extensively for classical models, the effectiveness of methods for imposing fairness on deep neural networks is unclear. In this paper, we observe that these large models overfit fairness objectives, and produce a range of unintended and undesirable consequences. We conduct our experiments on both facial recognition and automated medical diagnosis datasets using state-of-the-art architectures.

### Topological Graph Neural Networks

Read the research paper [here](https://arxiv.org/pdf/2102.07835v1.pdf)

Graph neural networks (GNNs) are a powerful architecture for tackling graph learning tasks, yet have been shown to be oblivious to eminent substructures, such as cycles. We present TOGL, a novel layer that incorporates global topological information of a graph using persistent homology. TOGL can be easily integrated into any type of GNN and is strictly more expressive in terms of the Weisfeiler–Lehman test of isomorphism. Augmenting GNNs with our layer leads to beneficial predictive performance, both on synthetic data sets, which can be trivially classified by humans but not by ordinary GNNs, and on real-world data.

### A new free machine learning book for readers to start from scratch

I am theroyakash, I develop software and machine learning and deep learning models. I am currently in the process of writing a book for understanding fundamental machine learning algorithms from scratch, I assume the reader has no knowledge of machine learning or just trying to start. This book will offer a variety of machine learning algorithms from scratch implementations and the mathematics behind them. The book is in the early stages and will be distributed for free over the internet. You can get early access to this put just filling up this contact form [here](https://www.iamroyakash.com/contact).

### A language learning system that pays attention — more efficiently than ever before

Read about this [here](https://news.mit.edu/2021/language-learning-efficiency-0210)

MIT researchers’ new hardware and software system streamlines state-of-the-art sentence analysis.

### Unsupervised Semantic Segmentation by Contrasting Object Mask Proposals

See the research paper [here](https://arxiv.org/pdf/2102.06191v1.pdf)

Being able to learn dense semantic representations of images without supervision is an important problem in computer vision. However, despite its significance, this problem remains rather unexplored, with a few exceptions that considered unsupervised semantic segmentation on small-scale datasets with a narrow visual domain. In this paper, we make a first attempt to tackle the problem on datasets that have been traditionally utilized for the supervised case. To achieve this, we introduce a novel two-step framework that adopts a predetermined prior in a contrastive optimization objective to learn pixel embeddings. This marks a large deviation from existing works that relied on proxy tasks or end-to-end clustering. Additionally, we argue about the importance of having a prior that contains information about objects, or their parts, and discuss several possibilities to obtain such a prior in an unsupervised manner.

Extensive experimental evaluation shows that the proposed method comes with key advantages over existing works. First, the learned pixel embeddings can be directly clustered in semantic groups using K-Means. Second, the method can serve as an effective unsupervised pre-training for the semantic segmentation task. In particular, when fine-tuning the learned representations using just 1% of labeled examples on PASCAL, we outperform supervised ImageNet pre-training by 7.1% mIoU.

### EasyNMT - Easy to use, state-of-the-art Neural Machine Translation

See the github repo [here](https://github.com/UKPLab/EasyNMT)

This package provides easy-to-use, state-of-the-art machine translation for more than 100+ languages. The highlights of this package are:

- Easy installation and usage: Use state-of-the-art machine translation with 3 lines of code
- Automatic download of pre-trained machine translation models
- Translation between 150+ languages
- Automatic language detection for 170+ languages
- Sentence and document translation
- Multi-GPU and multi-process translation

You can get started with this
```bash
pip install -U easynmt
```

### Physics-informed neural networks with hard constraints for inverse design

Read about the research [here](https://arxiv.org/pdf/2102.04626v1.pdf)

Inverse design arises in a variety of areas in engineering such as acoustic, mechanics, thermal/electronic transport, electromagnetism, and optics. Topology optimization is a major form of inverse design, where we optimize a designed geometry to achieve targeted properties and the geometry is parameterized by a density function. This optimization is challenging because it has a very high dimensionality and is usually constrained by partial differential equations (PDEs) and additional inequalities. Here, we propose a new deep learning method – physics-informed neural networks with hard constraints (hPINNs) – for solving topology optimization. hPINN leverages the recent development of PINNs for solving PDEs, and thus does not rely on any numerical PDE solver. However, all the constraints in PINNs are soft constraints, and hence we impose hard constraints by using the penalty method and the augmented Lagrangian method. We demonstrate the effectiveness of hPINN for a holography problem in optics and a fluid problem of Stokes flow. We achieve the same objective as conventional PDE-constrained optimization methods based on adjoint methods and numerical PDE solvers, but find that the design obtained from hPINN is often simpler and smoother for problems whose solution is not unique. Moreover, the implementation of inverse design with hPINN can be easier than that of conventional methods.

If you like the kind of articles I publish and follow my weekly machine learning issues subscribe to my newsletter.