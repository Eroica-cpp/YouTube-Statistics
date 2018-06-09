YouTube Statistics and Rankings
====
youtubestat.py is a Python module to download YouTube statistics and rankings from [https://www.kedoo.com/youtube/](https://www.kedoo.com/youtube/).

Requirements
----
* Python >= 2.7
* beautifulsoup >= 4.6.0
* bs4 >= 0.0.1
* selenium >= 3.12.0
* Firefox >= 60.0.1
* geckodriver >= 0.20.1

Usage
----
Try `youtubestat.py --help` for all available options.

An example to retrieve top 20 YouTube channels whose category is news and language is English:
```
$ youtubestat.py --category news --topN 20 --language English
```

Citation
----
If this work is useful for your research, please cite our [paper](https://library.nextrans.org/) or [code](https://github.com/Eroica-cpp/YouTube-Statistics):
```
@article{lin2015modeling,
  title={Modeling the impacts of inclement weather on freeway traffic speed: exploratory study with social media data},
  author={Lin, Lei and Ni, Ming and He, Qing and Gao, Jing and Sadek, Adel W},
  journal={Transportation Research Record: Journal of the Transportation Research Board},
  number={2482},
  pages={82--89},
  year={2015},
  publisher={Transportation Research Board of the National Academies}
}
```

License
----
youtubestat.py is licensed under [FreeBSD](https://opensource.org/licenses/BSD-2-Clause).
