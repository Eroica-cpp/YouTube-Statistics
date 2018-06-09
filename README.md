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
$ youtubestat.py --category news --topN 20 --lang en
```
| Channel | Country | Monthly Views | Subscribers |
|:----:|:----:|:----:|:----:|
| [Inside Edition](https://www.youtube.com/channel/UC9k-yiEpRHMNVOnOi_aQK8w) | United States | [2] | 3129845 |
| [CNN](https://www.youtube.com/channel/UCupvZG-5ko_eiXAupbDfxWw) | N/A | [2] | 3794747 |
| [ABC News](https://www.youtube.com/channel/UCBi2mrWuNuyYy4gbM6fU18Q) | United States | [2] | 3850158 |
| [Barcroft TV](https://www.youtube.com/channel/UCfwx98Wty7LhdlkxL5PZyLA) | N/A | [2] | 4627820 |
| [MSNBC](https://www.youtube.com/channel/UCaXkIU1QidjPwiAYu6GcHjg) | N/A | [2] | 963021 |
| [Fox News](https://www.youtube.com/channel/UCXIJgqnII2ZOINSWNOGFThA) | United States | [2] | 1242054 |
| [Crime Watch Daily](https://www.youtube.com/channel/UC69uYUqvx-vw4luuX7aHNLQ) | N/A | [2] | 877800 |
| [BBC News](https://www.youtube.com/channel/UC16niRr50-MSBwiO3YDb3RA) | United Kingdom | [2] | 2619048 |
| [The Young Turks](https://www.youtube.com/channel/UC1yBKRuGpC1tSM73A0ZjYjQ) | United States | [2] | 3899180 |
| [Guardian News](https://www.youtube.com/channel/UCIRYBXDze5krPDzAEOxFGVA) | United Kingdom | [2] | 136110 |
| [RT](https://www.youtube.com/channel/UCpwvZwUam-URkxB7g4USKpg) | N/A | [2] | 2632872 |
| [TODAY](https://www.youtube.com/channel/UChDKyKQ59fYz3JO2fl0Z6sg) | N/A | [2] | 758845 |
| [The Royal Family Channel](https://www.youtube.com/channel/UCCvgLV2Ixb8KCemj-UtXZ-g) | N/A | [2] | 314798 |
| [USA TODAY](https://www.youtube.com/channel/UCP6HGa63sBC7-KHtkme-p-g) | N/A | [2] | 634366 |
| [VICE News](https://www.youtube.com/channel/UCZaT_X_mc0BI-djXOlfhqWQ) | United States | [2] | 3048964 |
| [TomoNews US](https://www.youtube.com/channel/UCt-WqkTyKK1_70U4bb4k4lQ) | N/A | [2] | 2230927 |
| [CBS News](https://www.youtube.com/channel/UC8p1vwvWtl6T73JiExfWs1g) | N/A | [2] | 752014 |
| [DramaAlert](https://www.youtube.com/channel/UC11PvrGPzo6Y7Zc6-e9cAKg) | United States | [2] | 3888026 |
| [CBS This Morning](https://www.youtube.com/channel/UC-SJ6nODDmufqBzPBwCvYvQ) | N/A | [2] | 390538 |
| [Vox](https://www.youtube.com/channel/UCLXo7UDZvByw2ixzpQCufnA) | N/A | [2] | 4166051 |

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
