YouTube Statistics and Rankings
====
youtubestat.py is a Python module to download YouTube statistics and rankings from [https://www.kedoo.com/youtube/](https://www.kedoo.com/youtube/).

Requirements
----
* [Python](https://www.python.org/download/releases/2.7.2/) >= 2.7
* [beautifulsoup](https://www.crummy.com/software/BeautifulSoup/?#Download) >= 4.6.0
* [selenium](https://www.seleniumhq.org/) >= 3.12.0
* [Firefox](https://www.mozilla.org/en-US/firefox/new/) >= 60.0.1
* [geckodriver](https://github.com/mozilla/geckodriver/releases) >= 0.20.1

Usage
----
Try `youtubestat.py --help` for all available options.

An example to retrieve top 20 YouTube channels whose category is news and language is English:
```
$ youtubestat.py --category news --topN 20 --lang en --fmt md
```
| # | Channel | Country | Monthly Views | Subscribers |
|----:|----:|----:|----:|----:|
| 1 | [Inside Edition](https://www.youtube.com/channel/UC9k-yiEpRHMNVOnOi_aQK8w) | United States | 395025524 | 3129845 |
| 2 | [CNN](https://www.youtube.com/channel/UCupvZG-5ko_eiXAupbDfxWw) | N/A | 155319328 | 3794747 |
| 3 | [ABC News](https://www.youtube.com/channel/UCBi2mrWuNuyYy4gbM6fU18Q) | United States | 144872445 | 3850158 |
| 4 | [Barcroft TV](https://www.youtube.com/channel/UCfwx98Wty7LhdlkxL5PZyLA) | N/A | 129030102 | 4627820 |
| 5 | [MSNBC](https://www.youtube.com/channel/UCaXkIU1QidjPwiAYu6GcHjg) | N/A | 74032667 | 963021 |
| 6 | [Fox News](https://www.youtube.com/channel/UCXIJgqnII2ZOINSWNOGFThA) | United States | 60536948 | 1242054 |
| 7 | [Crime Watch Daily](https://www.youtube.com/channel/UC69uYUqvx-vw4luuX7aHNLQ) | N/A | 53485050 | 877800 |
| 8 | [BBC News](https://www.youtube.com/channel/UC16niRr50-MSBwiO3YDb3RA) | United Kingdom | 45344148 | 2619048 |
| 9 | [The Young Turks](https://www.youtube.com/channel/UC1yBKRuGpC1tSM73A0ZjYjQ) | United States | 45159957 | 3899180 |
| 10 | [Guardian News](https://www.youtube.com/channel/UCIRYBXDze5krPDzAEOxFGVA) | United Kingdom | 42598679 | 136110 |
| 11 | [RT](https://www.youtube.com/channel/UCpwvZwUam-URkxB7g4USKpg) | N/A | 40166881 | 2632872 |
| 12 | [TODAY](https://www.youtube.com/channel/UChDKyKQ59fYz3JO2fl0Z6sg) | N/A | 40073086 | 758845 |
| 13 | [The Royal Family Channel](https://www.youtube.com/channel/UCCvgLV2Ixb8KCemj-UtXZ-g) | N/A | 38726120 | 314798 |
| 14 | [USA TODAY](https://www.youtube.com/channel/UCP6HGa63sBC7-KHtkme-p-g) | N/A | 38444609 | 634366 |
| 15 | [VICE News](https://www.youtube.com/channel/UCZaT_X_mc0BI-djXOlfhqWQ) | United States | 36201734 | 3048964 |
| 16 | [TomoNews US](https://www.youtube.com/channel/UCt-WqkTyKK1_70U4bb4k4lQ) | N/A | 34828513 | 2230927 |
| 17 | [CBS News](https://www.youtube.com/channel/UC8p1vwvWtl6T73JiExfWs1g) | N/A | 34513896 | 752014 |
| 18 | [DramaAlert](https://www.youtube.com/channel/UC11PvrGPzo6Y7Zc6-e9cAKg) | United States | 34501164 | 3888026 |
| 19 | [CBS This Morning](https://www.youtube.com/channel/UC-SJ6nODDmufqBzPBwCvYvQ) | N/A | 34236213 | 390538 |
| 20 | [Vox](https://www.youtube.com/channel/UCLXo7UDZvByw2ixzpQCufnA) | N/A | 32228568 | 4166051 |

Citation
----
If this work is useful for your research, please cite our [paper](https://library.nextrans.org/) or [code](https://github.com/Eroica-cpp/YouTube-Statistics):
```
@misc{
    TBD
}
```

License
----
* Source code is licensed under [FreeBSD](https://opensource.org/licenses/BSD-2-Clause).
* Other content are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
