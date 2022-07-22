# Severstal-hackaton-march-2022
## As a team member of JEDAI team took 3rd place


## **Задача**

- Проведи исследование имеющихся данных и попробуй спрогнозировать просрочку по контрагенту, предложи, как обогатить модель иными данными;
- На выходе – понятный как для аналитика, так и для бизнес-пользователя Jupyter Notebook с подробным Exploratory Data Analysis (EDA) и воспроизводимым кодом решения, предобработки, моделирования, а также выводами;
- С нас — данные по контрагентам, список показателей для анализа, выборка для обучения модели


Ссылка на сайт хакатона
https://serverchallenge.ru/ 

Ссылка на описание задачи & данные
https://russianhackers.notion.site/4-36f74cb0191d4bb19de1709c9633dd89


## **Структура репозитория**
notebooks - папка для ноутбуков с решениями  
0_data_prepare.ipynb - ноутбук где обрабатываются и объединяются данные и выгружаются в pkl  
auto_eda.ipynb - авто EDA  
2_lama_2.ipynb - Light Auto ML решение  
7_model_tatget_log_exp_metric_another_reg.ipynb - лучшее решение после окончания хакатона (с логарифмированием и регуляризацией параметром reg_lambda (скор: 0.5423 / 0.5391)  
submits - папка для хранения сабмитов (csv-файл + ноутбук в zip-архиве)  
presentations.md - некоторые наиболее интересные скриншоты презентаций топ-7 участников.  
