# AndroZooOpen: Collecting large-scale open source android apps for the research community

AndroZooOpen is a growing collection of Open-Source Android Applications collected
from several sources, including Github, Gitlab and Bitbucket.

## Attributes: androzooopen.csv
data\_source, entry, num\_commits, num\_branches, num\_packages, num\_releases, num\_stars, create\_time, update\_time, push\_time, num\_contributors, package\_name, on\_googleplay, on\_androzoo, on\_fdroid, has\_test, has\_kotlin, email\_address, has\_ndk:  Those are what you think they are.

* data\_source: Provided in the format of string, which shows the data source.
* entry: Provided in the format of string, which can uniquely point to an online repository by adding the source domain.
* on\_googleplay: Provided in the format of bool value, either Yes or No, which means the project on the Github was published on Google Play or not.
* on\_androzoo: Provided in the format of bool value, either Yes or No, which means the project has been collected on AndroZoo or not.
* has\_test: Provided in the format of bool value, either Yes or No, which suggests the project provides test or not.
* has\_kotlin: Provided in the format of bool value, either Yes or No,  which shows the project consists of program languge kotlin or not.
* has\_ndk: Provided in the format of bool value, either Yes or No,  which shows the project consists of ndk-build or not.

## Review: Review.zip
Download from Google Play Store if the Android project is published on Google Play.

## Metadata: Metadata.zip
Download from Google Play Store if the Android project is published on Google Play.


## Reference
If you use this dataset, please cite the following paper:
```
@inproceedings{liu2020androzooopen,
  title={Androzooopen: Collecting large-scale open source android apps for the research community},
  author={Liu, Pei and Li, Li and Zhao, Yanjie and Sun, Xiaoyu and Grundy, John},
  booktitle={Proceedings of the 17th International Conference on Mining Software Repositories},
  pages={548--552},
  year={2020}
}
```
