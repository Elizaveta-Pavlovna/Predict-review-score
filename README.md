# Predict-review-score
The work is devoted to predicting the evaluation of reviews about tutors in Russia.

For analysis, we collected a dataset by parsing a site with a database of tutors: https://spb.repetitors.info/repetitor/ (it is an example for Spb)
The repository contains python code with parsing, files with data, python code with analisys data and report about work.

## The best model

ComplementNB provided the best results:

1. precision = 0.85
2. recall = 0.72
3. f1-score = 0.76

An example of the finished model work:

Prediction mark: 5 - "Рекомендую! Ирина Владимировна-очень грамотный педагог. Доступно и понятно объясняет материал. Дочери очень нравится."

Prediction mark: 4 - "Занимались до конца учебы. Сдал сын не очень хорошо но в этом нет вины Артура Валерьевича. Я считаю что в этом вина ребенка что он расслабился. У них хорошо шли занятия хороший был контакт. Хорошо что по этому предмету сын с молодым человеком занимался легко ему было из-за этого. Сдал сын ЕГЭ на 40 баллов."

Prediction mark: 3 - "Занятия прошли без особых эмоций ожидал большего. Объяснения были сухи и скучны. Хотелось бы от репетитора больше заинтересованности."

Prediction mark: 2 - "Не рекомендую данного человека называющего себя репетитором для подготовки подростков к ОГЭ и ЕГЭ. К сожалению довольно длительно ( в течение почти года) занимались но к счастью сложившиеся обстоятельства нас развели . И после тестирования с настоящим педагогом русского языка узнали о потерянном времени и немалых деньгах. Очень жаль что нет договора об услугах которые продает данный человек. Не рекомендую даже предостерегаю!"
