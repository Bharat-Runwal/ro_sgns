# Introduction

This repository implements [ACL 2017 Riemannian optimization for skip-gram negative sampling (Fonarev, Hrinchuk et al.)](https://arxiv.org/pdf/1704.08059.pdf).
```
@inproceedings{fonarev2017ro_sgns,
  title={Riemannian Optimization for Skip-Gram Negative Sampling},
  author={Alexander Fonarev and Oleksii Hrinchuk and Gleb Gusev and Pavel Serdyukov and Ivan Oseledets},
  booktitle={ACL},
  year={2017}
}
```

# Prerequisits

- [numpy](http://www.numpy.org)
- [scipy](https://www.scipy.org)
- [pandas](https://pandas.pydata.org)
- [gensim](https://radimrehurek.com/gensim/)
- [nltk](https://www.nltk.org)
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

```
pip install numpy scipy pandas gensim nltk bs4 
```

# Usage

- Download [enwik9](http://mattmahoney.net/dc/enwik9.zip) dataset and preprocess raw data with Perl script [main_.pl](main_.pl). 
- Run IPython notebook [enwik_experiments.ipynb](enwik_experiments.ipynb).

# Algorithm


<div>
<figure>
<img src="/img/ro.png" width="40%" hspace="7%">
  <figcaption><b>Figure 1.</b> Geometric interpretation of one step of Riemannian optimization.</figcaption>
</figure>
<figure>
<img src="/img/algorithm.png" width="40%">
</figure>
</div>

<div>
<img src="http://placekitten.com/200/150">
<p>This is the first picture. Maecenas id feugiat augue, a egestas eros. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
</div>
<div class="fixed">
<img src="http://placekitten.com/200/150">
<p>This is the second picture, though it has fixed height.</p>
</div>

