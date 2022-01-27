# Predicting Heart Disease using Machine Learning

## Can we predict if patient has heart disease or is at the risk of it?

This project aim is to analize which features measured by doctors can be used to predict heart disease of a patient. For this I will be using dataset, containing physical measurements of patients. 

Features:
⋅⋅* age - age in years
⋅⋅* sex - (1 = male; 0 = female)
⋅⋅* cp - chest pain type
⋅⋅* trestbps - resting blood pressure (in mm Hg on admission to the hospital)
⋅⋅* chol - serum cholestoral in mg/dl
⋅⋅* fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
⋅⋅* restecg - resting electrocardiographic results
⋅⋅* thalach - maximum heart rate achieved
⋅⋅* exang - exercise induced angina (1 = yes; 0 = no)
⋅⋅* oldpeak - ST depression induced by exercise relative to rest
⋅⋅* slope - the slope of the peak exercise ST segment
⋅⋅* ca - number of major vessels (0-3) colored by flourosopy
⋅⋅* thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
⋅⋅* target - 1 or 0

I will build several classification models and choose the best-performing once. As a model quality measure, I'm going to look at all the metrics, but try to maximize recall. I think in this case it is important to catch more positive cases, even if it comes at the cost of including false positives. It is better to analyze more patients and tell some of them that their diagnosis is wrong and they are healthy than to have false negatives and miss a patient with a disease. 
For completion of this project I'm going to use data analysis toolds such as Numpy, Pandas, Matplotlib and Seaborn. For model building I will use scikit-learn package.

# Прогнозирование сердечных заболеваний с помощью машинного обучения

## Можем ли мы предсказать, есть ли у пациента заболевание сердца или есть ли риск его возникновения?

Цель этого проекта — проанализировать, какие характеристики, измеряемые врачами, можно использовать для прогнозирования сердечно-сосудистых заболеваний пациента. Для этого я буду использовать набор данных, содержащий физические измерения пациентов.

Показатели в датасете:
⋅⋅* age - возраст в годах
⋅⋅* пол - (1 = мужчина; 0 = женщина)
⋅⋅* cp - тип боли в груди
⋅⋅* trestbps - артериальное давление в покое (в мм рт.ст. при поступлении в стационар)
⋅⋅* chol - холестерин в сыворотке в мг/дл
⋅⋅* fbs - (уровень сахара в крови натощак > 120 мг/дл) (1 = верно; 0 = неверно)
⋅⋅* restecg - результаты электрокардиографии в покое
⋅⋅* thalach - максимальная достигнутая частота сердечных сокращений
⋅⋅* exang - стенокардия, вызванная физической нагрузкой (1 = да; 0 = нет)
⋅⋅* oldpeak - депрессия ST, вызванная физической нагрузкой, по сравнению с состоянием покоя
⋅⋅* slope - наклон пикового сегмента ST нагрузки
⋅⋅* ca - количество крупных сосудов (0-3), окрашенных при флюороскопии
⋅⋅* thal - 3 = нормальный; 6 = фиксированный дефект; 7 = обратимый дефект
⋅⋅* цель - 1 или 0

Я построю несколько моделей классификации и один раз выберу наиболее эффективную. В качестве меры качества модели я рассмотрю все показатели, но постараюсь максимизировать recall. Я думаю, что в этом случае важно выявлять больше положительных случаев, даже если это происходит за счет включения ложноположительных. Лучше клинически исследовать больше пациентов и сказать некоторым из них, что их диагноз неверен и они здоровы, чем иметь ложноотрицательные результаты и пропустить больного с заболеванием. 
Для выполнения этого проекта я использую инструменты анализа данных, такие как Numpy, Pandas, Matplotlib и Seaborn. Для построения модели я буду использовать пакет scikit-learn. 
