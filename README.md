# BioFilt-IMDB-CACD

BioFilt-IMDB-CACD contains filtered versions of sample lists from the [IMDB-WIKI](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/) and [CACD](http://bcsiriuschen.github.io/CARC/) age and gender estimation datasets. The datasets are filtered by the method from our paper [*Unsupervised Facial Biometric Data Filtering for Age and Gender Estimation*](http://www.insticc.org/Primoris/Resources/PaperPdf.ashx?idPaper=72572). The paper shows strong indications of label noise reduction and the experimental section demonstrates reduction of age estimation MAE by up to **2 years on both real and apparent age estimation** tasks. If you find this resources usefull, please cite our paper:
```
@inproceedings{bevsenic2019unsupervised,
  title={Unsupervised Facial Biometric Data Filtering for Age and Gender Estimation},
  author={Be{\v{s}}eni{\'c}, Kre{\v{s}}imir and Ahlberg, J{\"o}rgen and Pand{\v{z}}i{\'c}, Igor},
  booktitle={International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications},
  volume={5},
  pages={209--217},
  year={2019},
  organization={SciTePress}
}

```

[**IMDB-F**](https://github.com/kbesenic/BioFilt-IMDB-CACD/blob/master/IMDB-F.txt) contains filtered list of samples from IMDB part of the [IMDB-WIKI](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/) dataset (note that the WIKI part of the dataset was not used in our work). From 460,723 samples in the original dataset, we used 452,261 samples in our paper and retained only 216,610 samples after the filtering step (**53% sample count reduction**).

[**CACD-F**](https://github.com/kbesenic/BioFilt-IMDB-CACD/blob/master/CACD-F.txt) contains filtered list of samples from the [CACD](http://bcsiriuschen.github.io/CARC/) dataset. From 163,446 samples from the original dataset, we used 150,383 samples in our paper and retained only 130,571 samples after the filtering step (**20% sample count reduction**).

Age statistics for the unfiltered and filtered versions of the IMDB and CACD datasets:
![filtering_stats](https://github.com/kbesenic/BioFilt-IMDB-CACD/blob/master/filtering_stats.png) 

# The B3FD Dataset (2022)
The data presented on this page was further refined and used to create a new derived dataset for age estimation - the B3FD dataset. It contains 375,592 facial image samples with corresponding age labels. Both images and labels are available for download. For more info please visit the dataset page at:
[https://github.com/kbesenic/B3FD](https://github.com/kbesenic/B3FD)
