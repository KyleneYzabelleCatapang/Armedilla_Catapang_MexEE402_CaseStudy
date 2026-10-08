# Armedilla_Catapang_MexEE402_CaseStudy

# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Armedilla, Christian Joseph | 22-02038 | MEXE-4103 |
| Catapang, Kylene Yzabelle M. | 22-02838 | MEXE-4103 |

## Notebook links

| Chapter | Member 1 | Member 2 |
|---|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/1MNmKyD7SpZt2QyHzHCENnszcwsmM3De7?usp=sharing) | [link](https://colab.research.google.com/drive/1_B9wLwjPpk6uGSJa5EUPkj092zaQyj_a?usp=sharing) |
| Ch4 | [link](https://colab.research.google.com/drive/1G0n47oP41dCyBRH-HQF2HuJPFqbYVduB?usp=sharing) | [link](https://colab.research.google.com/drive/1NYu2nvromXxidFULInNbhk3ul4GycThm?usp=sharing) |
| Ch5 | [link](https://colab.research.google.com/drive/1mL2-ZzgPkjNT76v2NQ1X3ZvYA20iLku6?usp=sharing) | [link](https://colab.research.google.com/drive/1eQiloAONIT1xFOOQgHzYxi3Qw2jfHdyp?usp=sharing) |
| Ch6 | [link](https://colab.research.google.com/drive/1YlaT8pjDOgLvTCjxNS28uf5GDpkjAuIT?usp=sharing) | [link](https://colab.research.google.com/drive/1PJ23nrrlR8d6OppxGF-EuvD9riMjh8lu?usp=sharing) |
| Ch7 | [link](https://colab.research.google.com/drive/1KDHVs3HNpQCOX9KWq0ERBQzFd1x0cel7?usp=sharing) | [link](https://colab.research.google.com/drive/1lF35LCe26hq0uGL_lm9WaRbXCnhXZUT_?usp=sharing) |
| Ch8 | [link](https://colab.research.google.com/drive/1r9rqCpJkln5E0wFyV1QtCbk36SctJhim?usp=sharing) | [link](https://colab.research.google.com/drive/1ysVB5A4QdksXo1G0ProbouS0uskg-RNW?usp=sharing) |
| Ch9 | [link](https://colab.research.google.com/drive/1bffFPNb5XINXSxpKsP_JoDa6PcdvudqI?usp=sharing) | [link](https://colab.research.google.com/drive/1gRtgKHAuyDvDRvtkMa-ODPX0eg0C5iTV?usp=sharing) |

## What we learned

One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught
you and what surprised you. Not what the library does, but what you understood.

**CHAPTER 1-3**

Chapters 1–3 taught me that data must first be cleaned, organized, loaded, and understood before it can be properly analyzed. I learned how to identify data types, explore a dataset, and handle missing values, duplicates, irrelevant features, and noisy data to improve data quality. What surprised me was how much the preparation and cleaning of data can affect the accuracy and reliability of the results.

**CHAPTER 4**

Chapters 1–4 taught me how to clean, load, explore, and transform data so it can be used properly for analysis and machine learning. I learned how to handle missing and unnecessary data and create useful features through binning, interaction, polynomial features, and categorical encoding. What surprised me was that transforming existing data into new features can reveal patterns that are not easily seen in the original data.

**CHAPTER 5**

Chapter 5 taught me how to clean, explore, transform, and scale data so it can be properly used for analysis and machine learning. I learned that scaling and normalization put different features on a fair and comparable range, preventing larger values from having more influence. What surprised me was how changing the scale of the data can affect how fairly a model treats different features.

**CHAPTER 6**

Chapter 6 taught me how to identify and handle outliers, which are data points that are significantly different from most of the data. I learned that methods like Z-score and IQR can detect outliers, while capping, flooring, log transformation, or removal can be used to manage them. What surprised me was that an extreme value can affect the results and lead to misleading conclusions if it is not handled properly.

**CHAPTER 7**

Chapter 7 taught me how to identify the most relevant features by understanding their relationship with the target variable through correlation and different feature selection methods. I learned that removing less useful features can simplify the data and improve the model’s focus. What surprised me was that different methods, such as filter, wrapper, and embedded methods, can select different features based on their importance to the model.

**CHAPTER 8**

Chapter 8 taught me how to organize different preprocessing steps into one pipeline so the data can be cleaned and prepared in a consistent order. I learned that combining steps like handling missing values and scaling makes the preprocessing process more efficient and easier to reuse. What surprised me was that the same pipeline can be applied to new data, helping avoid inconsistent preprocessing and human errors.

**CHAPTER 9**

Chapter 9 taught me how to apply different preprocessing techniques together to prepare real-world data for analysis. I learned that data often needs several steps, such as cleaning missing values, transforming, reducing, discretizing, and encoding, before it becomes useful. What surprised me was that preprocessing is an iterative process because the data may still need to be checked and adjusted after each step.



**CHAPTER 1-3**

This chapter taught me that data needs to be checked and cleaned before it can be properly used for analysis. I learned that missing, incorrect, or unnecessary information can affect the results. What surprised me was that even a large dataset can still have hidden problems, so I realized that the quality of the data is just as important as the way we analyze it.

**CHAPTER 4**

This chapter taught me that feature engineering can make raw data more useful by creating new information from existing data. I learned that techniques like binning, interaction features, polynomial features, and encoding can help reveal patterns and make data easier for machine learning models to understand. What surprised me was that simply combining or transforming existing data, such as temperature and lemonade sales, can provide new insights that are not obvious from the original data.

**CHAPTER 5**

This chapter taught me that scaling and normalization help make different features easier to compare by putting them on a similar range. I understood that features with larger values can affect a model more, so adjusting their scale can make the results fairer. What surprised me was that scaling is not always necessary because its importance depends on the type of data and the algorithm being used.

**CHAPTER 6**

This chapter taught me that outliers are unusual values that can affect the accuracy of data analysis and lead to misleading results. I learned that they can be detected using methods like Z-score and IQR and handled by removing, limiting, or transforming the values. What surprised me was that one unusual value, such as 100 when most values are around 10–22, can have a noticeable effect on how the data is understood.

**CHAPTER 7**

This chapter taught me that feature selection helps choose the most useful information from a dataset while removing features that may not contribute much to the prediction. I learned that correlation can show how variables are related, while filter, wrapper, and embedded methods can help identify important features. What surprised me was that having more features does not always mean better results because unnecessary information can make a model less effective.

**CHAPTER 8**

This chapter taught me that a preprocessing pipeline organizes different data preparation steps into one process, making the data cleaner and ready for machine learning. I understood that steps like filling missing values and scaling features can be done in a consistent order instead of manually doing each one. What surprised me was that the same pipeline can be reused on new data, helping keep the preprocessing consistent and reducing errors.

**CHAPTER 9**

This chapter taught me that real-world data needs several preprocessing steps before it can be properly used for analysis or machine learning. I understood that missing values, unnecessary features, and different types of data need to be handled carefully, and that preprocessing may need to be repeated or adjusted. What surprised me was how much the Titanic data could change after cleaning, transforming, and organizing it, making patterns like survival differences by gender and passenger class easier to understand.

## Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

## Note on AI tools

Say whether you used an AI tool, and what for. This is not a penalty.
Hiding it is.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
