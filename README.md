# Gyperpress
система управління гіперпрессом на основі ESP32
Поступило замовлення на виготовлення системи управління гіперпресом, це той прес, який виготовляє цеглу по особливому рецепту без спікання. 
Конкретно цей прес - ротаційний, в ньому є ротор з трьома отвориами, через які одночасно насипається суміш, відбувається пресування і виштовхування на конвеєрну стрічку.
Прес має 5 індукційних датчиків, які контролюють робочі органи, датчик тиску для контролю процесу пресування.
Управління гідравлікою відбувається через електроклапани, їх у пресу 7 шт. 
Контролер відслідковує положення датчиків і посилає команди на електроклапани.
Керування конролером здійснюється через конопки і перемикач. 
Реалізовано режим "ручний" і "автоматичний".
В ручному режимі контролер не реагує на положення датчиків, але запобігає конфліктним ситуаціям.
В автоматичному режимі працює по циклу, доки не натиснути кнопку "Стоп", або якщо виникне конфліктна ситуація.

Проект тільки розпочато, але будуть доповнення по мірі розвитку.
