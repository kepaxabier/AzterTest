At the moment there is an improved version called MultiAzterTest

MultiAzterTest is on githup as https://github.com/kepaxabier/MultiAzterTest

You can test the online version of MultiAzterTest at the address http://ixa2.si.ehu.eus/aztertest

Aztertest calculates multiple metrics and indicators of the texts' content and analyzing those results to determine the complexity level of those texts.

If you want to install Aztertest locally, you have to install the following modules:

This version use NLPCube parser:
pip3 install nlpcube

pip3 install numpy

pip3 install nltk

pip3 install argparse

pip3 install tensorflow

pip3 install tensorflow_hub

pip3 install pandas

pip3 install sklearn

pip3 install wordfreq


# AzterTest
AzterTest: Open Source Linguistic and Stylistic Analysis Tool

## How to use

```
python3 main.py -f <FILENAME>
```
Or:
```
python3 main.py --files <FILENAME>
```

For example:
```
python3 main.py --files /home/user/texts/*.txt
```
