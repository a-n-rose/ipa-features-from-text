# ipa-features-from-text
"Translates" English text/words to IPA (can be modified to work with other langauges). Categorizes IPA letters by their IPA features. Saves features of words to machine/deep learning friendly file: one column per feature, and True if the word has this feature, False if not. 

### IPA: International Phonetic Alphabet
The chart can be found and downloaded here https://www.internationalphoneticassociation.org/content/full-ipa-chart
It is an alphabet used by many linguists to categorize sounds of languages.

### Name Data as an example 
These scripts use data from a names database to serve as an example. However, the tools here could be applied to other words as well. 

To use these tools with the names list: 

1) download the latest name database from the Social Security Administration https://catalog.data.gov/dataset/baby-names-from-social-security-card-applications-national-level-data

2) unzip the files in a *new* directory with the scripts provided here. 

3) run the "nametxt2csv.py" 

4) run the "namelist_IPAprep_basic.py"

