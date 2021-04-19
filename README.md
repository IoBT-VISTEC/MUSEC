# MUSEC-MusicPreference-Behaviors-EEG
# Revealing Preference in Popular music Through Familiarity and Brain Response
### [This work](https://doi.org/10.1109/JSEN.2021.3073040) is published in IEEE Sensors Journal 

### For accessing to the full dataset, please send your CV to Dr.Theerawit Wilaiprasitporn (theerawit.w@vistec.ac.th)

## Abstract

**Music preference was reported as a factor, which could elicit innermost music emotion, entailing accurate ground-truth data and music therapy efficiency. This study executes statistical analysis to investigate the distinction of music preference through familiarity scores, response times (response rates), and brain response (EEG). Twenty participants did self-assessment after listening to two types of popular music’s chorus section: music without lyrics (Melody) and music with lyrics (Song). We then conduct a music preference classification using a support vector machine, random forest, and k-nearest neighbors with the familiarity scores, the response rates, and EEG as the feature vectors. The statistical analysis and F1-score of EEG are congruent, which says that the brain’s right side outperformed its left side in classification performance. Finally, these behavioral and brain studies support that preference, familiarity, and response rates can contribute to the music emotion experiment’s design to understand music, emotion, and listener. Not only to the music industry, the biomedical and healthcare industry can also exploit this experiment to collect data from patients to improve the efficiency of healing by music.**

## Data description
The dataset was divided into 2 audio types: Melody and Song.

Each audio contains:
* [EEG and EOG raw data](#eeg_eog_dataset)
* [Behaviors data (Familiarity, Times, and Response Rate) and Preference labels (favoured and non_favoured)](#behaviors_labels_dataset)

## Dataset 
<h3 id="eeg_eog_dataset">EEG and EOG</h3>
<!-- <br>EEG and EOG -->

In the full dataset, you will find the 4 music preference groups such as favoured Melody, favoured Song, non_favoured Melody, non_favoured Song as follows:

```
favoured
└─ favoured_melody (81 files)
    └─ s001_gtec_melody_20_030.csv
    └─ s002_gtec_melody_10_082.csv
    .
    .
    .
    └─ s020_gtec_melody_05_022.csv
    
└─ favoured_song (81 files)
    └─ s001_gtec_song_20_030.csv
    └─ s002_gtec_song_10_082.csv
    .
    .
    .
    └─ s020_gtec_song_05_022.csv
    
---------------------------------------
non_favoured
└─ non_favoured_melody (271 files)
    └─ s001_gtec_melody_01_070.csv
    └─ s001_gtec_melody_02_057.csv
    .
    .
    .
    └─ s020_gtec_melody_22_012.csv
    
└─ non_favoured_song (271 files)
    └─ s001_gtec_song_01_070.csv
    └─ s001_gtec_song_02_057.csv
    .
    .
    .
    └─ s020_gtec_song_22_012.csv


```
Each .csv file contains 64 columns as follows: 
* EEG: 62 channels (Columns 1-62)
* EOG: 2 channels (Columns 63-64)

<br><h3 id="behaviors_labels_dataset">Behaviors and Preference labels</h3>
All behaviors and preference labels were collected in 'behaviors.csv' as follows:


