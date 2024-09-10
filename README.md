# Revolutionising biotechnology: A cutting-edge digital approach for rapid C-phycocyanin detection in _Spirulina platensis_

In our study, we evaluate the performance of three artificial intelligence (AI) models—Support Vector Machines (SVM), eXtreme Gradient Boosting (XGBoost), and Convolutional Neural Networks (CNN)—in predicting the CPC (C-phycocyanin) concentrations from _Spirulina platensis_ (_S.platensis_) biomass and extracted CPC images. We investigate the variation of input parameters under different image-capturing devices, and lighting conditions to simulate based on real-world scenarios. Results signify that SVM model exhibits R2 values of (0.9304 - 0.9867) and (0.9967 - 0.9981) when using _S.platensis_ biomass and extracted CPC images, respectively. XGBoost model demonstrates higher R2 values of (0.9899 - 0.9968) and (0.9996 - 0.9999) for _S.platensis_ biomass and extracted CPC images, respectively. CNN model managed to achieve R2 values of (0.9769 - 0.9986) and (0.9969 - 0.9991) for _S.platensis_ biomass and extracted CPC images, respectively. To shed light on this, our work suggests the feasibility and efficiency of AI-driven methods for CPC concentration prediction.

**Keywords**: _Spirulina platensis_; C-phycocyanin; Colour feature; Machine learning (ML); Deep learning (DL)

# Folder and files description

**AI_models_Final** => Contains the model configuration of SVM regressor, XGBoost regressor, and CNN

**Combined_All_Batch_Days_Camera** => Contains the combined data for all batches (3) and days (2, 4, 6, 8, 10, & 12) when using digital camera capturing device under various type of variables (colour models such as RGB, HSL, & CMYK), and lightning conditions (covered [not exposed to light]/ light disturbed [non_covered])

**Combined_All_Batch_Days_Smartphone** => Contains the combined data for all batches (3) and days (2, 4, 6, 8, 10, & 12) when using smartphone capturing device under various type of colour variables (colour models such as RGB, HSL, & CMYK), and lightning conditions (covered [not exposed to light]/ light disturbed [non_covered])

**Data_Abs_Day_Colour_index_Normalised** => Contains the combined data for all batches (3) and days (2, 4, 6, 8, 10, & 12) when using various image capturing devices (digital camera/ smartphone), type of colour variables (colour models such as RGB, HSL, & CMYK) with additonal 'Day' (period),  'Abs' (absorbance), and lightning conditions (covered [not exposed to light]/ light disturbed [non_covered])

**Data_Colour_index_Normalised** => Contains the combined data for all batches (3) and days (2, 4, 6, 8, 10, & 12) when using various image capturing devices (digital camera/ smartphone), type of colour variables (colour models such as RGB, HSL, & CMYK), and lightning conditions (covered [not exposed to light]/ light disturbed [non_covered])

**Data_Day_Colour_index_Normalised** => Contains the combined data for all batches (3) and days (2, 4, 6, 8, 10, & 12) when using various image capturing devices (digital camera/ smartphone), type of colour variables (colour models such as RGB, HSL, & CMYK) with additonal 'Day' (period), and lightning conditions (covered [not exposed to light]/ light disturbed [non_covered])

**Exp_3_Overall_Microalgae_Tabulated_results.xlsx** => Contains all the results tabulated in excel format

# _Spirulina platensis_ biomass & extracted CPC image dataset
The google drive [https://drive.google.com/drive/folders/1dXDUHCD9nTJaF0CFyxqUkHKZH8Ko1XjF?usp=drive_link] contains the cropped image dataset of _Spirulina platensis_ biomass & extracted CPC grown under BG-11 medium in the period of 12 days. Subsequently, each day will contain a subfolder of both image capturing devices such as smartphone [Model => Iphone_13_Pro_Max] and digital camera [Model => Nikon_Z50]. Each image capturing device will contain a subfolder of covered [images taken without any light disturbances] and light_disturbed [images taken under light disturbed condition]. The experiment is conducted for 3 batches. The image dataset is publicly available for academic and research purposes.

# Referencing and citation
If you find the prediction and analysis of C-phycocyanin (CPC) concentration as well as the image dataset useful in your research, please consider citing: Based on the DOI: 
