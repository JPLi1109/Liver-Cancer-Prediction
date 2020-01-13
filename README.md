# Disease-Prediction
The epidemiological questionnaire used in paper "Investigating Critical Risk Factors of Liver Cancers with Deep Neural Networks". 
The crude incidence of liver cancer ranks top five among all cancers in China, and the death rate ranks the top two. Identifying critical risk factors of liver cancer helps people adjust their lifestyles to reduce cancer risk. Launched in 2012, Early Diagnosis and Treatment of Urban Cancer project has been carried out in major cities of China, which collected a broad range of epidemiological risk factors including definite, probable and possible causes of cancer. We retrieved data from 2014 to the present and obtained 184 liver cancer cases among 55 thousand peoples. We explore 84 risk factors and implement liver cancer prediction model with machine learning algorithms, where deep neural network achieves the best performance using non-clinical information (mean AUC=0.718). We analyze model parameters to investigate critical risk factors that contribute the most to prediction. Using 50% top-ranking risk factors to train a model, the performance shows no significant difference from that using all risk factors. Using top 10% risk factors induces a sensitivity drop and a lower false positive rate. These phenomena prove that the identified risk factors are critical in liver cancer prediction. This work is a reference in public health research, and provides a scientific lifestyle guideline for individuals to prevent liver cancer based on machine learning technology.
