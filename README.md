# Socialness Norms
**Data** and **scripts** associated with the publication *Quantifying Social Semantics: An Inclusive Definition of Socialness and Ratings for 8,388 English Words* by Diveica, Pexman, & Binney available at: https://doi.org/10.3758/s13428-022-01810-x 

**A description of all files is provided below:** 

1. 1_Data_Cleaning : applies a set of exclusion criteria to the raw data and generates a *clean* dataset of ratings for inclusion in the main analyses;
2. 2_Descriptives : this script computes summary statistics to characterize the participant sample, the item-wise socialness ratings and the reliability and validity of the socialness measure;
3. 3_Analyses : this script runs correlations and regression models and generates all the analysis tables and figures reported in the associated manuscript;
4. Data:
  - Ratings_sum.stat.csv : item-wise summary statistics for the socialness ratings (M, SD, median, min, max, N)
  - Raw:
    - All_data.csv : all raw data, inlcuding metadata, demographics, ratings
    - All_ratings_only.csv: all raw ratings 
    - Control_words_pilot_ratings.csv : mean pilot socialness ratings for the 30 control words
    - Presentation_order_all.csv : the order in which items were presented to each participant
    - QID_to_word.csv : the word associated with each question ID
  - Preprocessed:
    - Data_clean_all_words.csv : all clean data (i.e., the data remaining after participant exclusion criteria were applied), inlcuding metadata, demographics, ratings
    - Ratings_clean_all_words.csv : all clean ratings (i.e., the ratings remaining after participant exclusion criteria were applied)
    - Ratings_FINAL.csv :  all *final* clean ratings (i.e., the ratings remaining after participant and word exclusion criteria were applied)
  - Other: openly-avaliable datasets used in the reported analyses:
    - Binder_SocialEmotion.csv : 1. Binder JR, Conant LL, Humphries CJ, Fernandino L, Simons SB, Aguilar M, Desai RH. 2016 Toward a brain-based componential semantic representation. Cogn. Neuropsychol. 33, 130–174. (doi:10.1080/02643294.2016.1147426)
    - Brysbaert & Biemiller 2017 test-based AoA measures.csv : 1. Brysbaert M, Biemiller A. 2017 Test-based age-of-acquisition norms for 44 thousand English word meanings. Behav. Res. Methods 49, 1520–1523. (doi:10.3758/s13428-016-0811-4)
    - Brysbaert2013_Concreteness.csv :  1. Brysbaert M, Warriner AB, Kuperman V. 2014 Concreteness ratings for 40 thousand generally known English word lemmas. Behav. Res. Methods 46, 904–911. (doi:10.3758/s13428-013-0403-5)
    - cortese2004_imageability.csv : Cortese MJ, McCarty DP, Schock J. 2015 A mega recognition memory study of 2897 disyllabic words. Q. J. Exp. Psychol. 68, 1489–1501. (doi:10.1080/17470218.2014.945096)
    - ELP_Items.csv : Balota DA et al. 2007 The english lexicon project. Behav. Res. Methods 39, 445–459. (doi:10.3758/BF03193014)
    - Hoffman_2013_Semantic_diversity.csv : 1. Mandera P, Keuleers E, Brysbaert M. 2020 Recognition times for 62 thousand English words: Data from the English Crowdsourcing Project. Behav. Res. Methods 52, 741–760. (doi:10.3758/s13428-019-01272-8)
    - Kuperman_2012_AoA.csv: Mandera P, Keuleers E, Brysbaert M. 2020 Recognition times for 62 thousand English words: Data from the English Crowdsourcing Project. Behav. Res. Methods 52, 741–760. (doi:10.3758/s13428-019-01272-8)
    - Mandera_2020_EnglishCrowdsourcingProject.csv : Mandera P, Keuleers E, Brysbaert M. 2020 Recognition times for 62 thousand English words: Data from the English Crowdsourcing Project. Behav. Res. Methods 52, 741–760. (doi:10.3758/s13428-019-01272-8)
    - Pexman_2019_BOI.csv : Pexman PM, Muraki E, Sidhu DM, Siakaluk PD, Yap MJ. 2019 Quantifying sensorimotor experience: Body–object interaction ratings for more than 9,000 English words. Behav. Res. Methods 51, 453–466. (doi:10.3758/s13428-018-1171-z)
    - Schock_2012_Imageability.csv : Schock J, Cortese MJ, Khanna MM. 2012 Imageability estimates for 3,000 disyllabic words. Behav. Res. Methods 44, 374–379. (doi:10.3758/s13428-011-0162-0)
    - SER_Juhasz2013.csv : Juhasz BJ, Yap MJ. 2012 Sensory experience ratings for over 5,000 mono- and disyllabic words. Behav. Res. Methods 2012 451 45, 160–168. (doi:10.3758/S13428-012-0242-9)
    - SUBTLEX-US frequency list with PoS and Zipf information.csv : Brysbaert M, New B, Keuleers E. 2012 Adding part-of-speech information to the SUBTLEX-US word frequencies. Behav. Res. Methods 2012 444 44, 991–997. (doi:10.3758/S13428-012-0190-4)
    - Troche_2014_Social.csv : Troche J, Crutch SJ, Reilly J. 2017 Defining a conceptual topography of word concreteness: Clustering properties of emotion, sensation, and magnitude among 750 english words. Front. Psychol. 8, 1787. (doi:10.3389/fpsyg.2017.01787)
    - Warriner 2013 Emotion ratings.csv : Warriner AB, Kuperman V, Brysbaert M. 2013 Norms of valence, arousal, and dominance for 13,915 English lemmas. Behav. Res. Methods 45, 1191–1207. (doi:10.3758/s13428-012-0314-x)

5. Pilot
  - Pilot_data_processing : script to explore the data collected in the pilot study
  - Socialness_mean_ratings.png : figure illustrating the mean and SD of the pilot ratings for 60 words
  - Data:
    - Pilot_ratings_summary.csv : item-wise summary statistics for the pilot socialness ratings
    - PILOT_Socialness_mean_ratings.csv : mean pilot socialness ratings
    - Ratings_rationale.csv : verbal explanations provided by participants when asked to explain the reasoning behind their chosen rating for the respective word
    - Instructions_explanations.csv : verbal explanations of the task instructions provided by the participants 
    - Raw :
      -  Raw_Version1 : raw data for the group of participants who read version 1 of the instructions
      -  Raw_Version2 : raw data for the group of participants who read version 2 of the instructions
      -  Word_to_ID.csv :  the word associated with each question ID
      -  README : brief description of the pilot study
