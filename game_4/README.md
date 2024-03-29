# Исследование определяющих закономерностей успешность игры 


## Заказчик: интернет-магазин «Стримчик»

## Данные

Входные данные: из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Столбцы обозначают следующее:

    Name — название игры
    Platform — платформа
    Year_of_Release — год выпуска
    Genre — жанр игры
    NA_sales — продажи в Северной Америке (миллионы проданных копий)
    EU_sales — продажи в Европе (миллионы проданных копий)
    JP_sales — продажи в Японии (миллионы проданных копий)
    Other_sales — продажи в других странах (миллионы проданных копий)
    Critic_Score — оценка критиков (максимум 100)
    User_Score — оценка пользователей (максимум 10)
    Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.



## Цель: выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.


## План работы: 

1. Изучаем входные данные. 
2. Устранение пропусков в данных
3. Анализ данных
4. Составляем портрет пользователя каждого региона
5. Проверка гипотез
6. Выводы


## Используемые библиотеки
*pandas*, *matplotlib*, *numpy*, *seaborn*, *scipy*, *math*
