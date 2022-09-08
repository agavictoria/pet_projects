# Мои проекты
В этом репозитории размещены проекты, сделанные в процессе обучения на курсе "Аналитик данных" от Karpov.Courses.
Основные библиотеки, используемые в проектах:
  - Pandas
  - Numpy
  - Seaborn
  - Matplotlib
  - Statsmodels
  - Scipy
  - PandaHouse

Общая информация о каждом проекте представлена в таблице ниже.

| № | Название        | Описание |
|:-:|:---------------:| -------------|
| 1 | [A/A-тестирование мобильного приложения](https://github.com/agavictoria/pet_projects/blob/main/aa-test.ipynb) | Проведена  проверка системы сплитования по метрике качества FPR. Система сплитования была сломана. Найдена и устранена её причина: отбор пользователей в группу 0 и использующих версию v2.8.0. У них очень маленькая конверсия в покупку по сравнению с группой 1 той же версии.|
|2| [A/B-тестирование приложения доставки для курьеров](https://github.com/agavictoria/pet_projects/blob/main/ab-test_pizza.ipynb)| Проверена эффективность нового алгоритма, позволяющая  курьерам запланировать свои последние заказы перед окончанием рабочего дня так, чтобы их маршрут доставки совпадал с маршрутом до дома. Сформулирована нулевая и альтернативная гипотезы, проведена проверка данных на нормальность, рассчитано стандартное отклонение. По результатам t-теста отклонили нулевую гипотезу. Новая фича статистически достоверно снизила время доставки на 13%, поэтому раскатываем новый алгоритм на всех пользователей.|
|3|[Поиск аномалий в данных](https://github.com/agavictoria/pet_projects/blob/main/bicycle_rent.ipynb)| Предоставлены данные компании, которая занимается арендой велосипедов в Лондоне. Изучена динамика числа аренд, наличие связи с погодными условиями и выходными, а также найдено несколько аномалий на графике. Несколько резких скачков количества аренд на графике были связаны с забастовками работников лондонского метрополитена. Приостановка работы метро привела к транспортному коллапсу, чтобы добраться до работы люди арендовали наши велосипеды. |
|4| Первый крупный проект e-commerce (вышлю по запросу) | Провела эксплораторный анализ данных для определения понятия "покупка". Определила количество пользователей, которые совершили покупку только один раз. По каждому товару определила, в какой день недели товар чаще всего покупается. Подсчитала, сколько заказов в месяц в среднем не доставляется по разным причинам. Оценила, сколько у каждого из пользователей в среднем покупок в неделю (по месяцам). Провела когортный анализ пользователей. Построила тепловую диаграмму и выявила когорту с самым высоким retention на третий месяц. Построила RFM-сегментацию пользователей для качественной оценки аудитории. Дала название каждому сегменту, визуализировала результат работы. По каждому из вопросов были сделаны краткие выводы, которые оценивают общее состояние бизнеса в контексте поведения клиентов. Даны рекомендации для уменьшения оттока клиентов.|
|5| [Финальный проект edTech](https://github.com/agavictoria/pet_projects/blob/main/final_project_EdTech.ipynb)| Провела эксплораторный анализ входных данных эксперимента. Провела A/B-тестирование новой механики оплаты услуг на сайте. По итогам bootstrap-анализа средний чек статистически достоверно увеличился более чем на 30%, методом хи-квадрат статистически достоверного влияния на конверсию выявлено не было. Даны рекомендации по технической и продуктовой части эксперимента. Новую механику можно раскатывать на всех пользователей. Написан SQL-запрос, дающий информацию о количестве очень усердных студентов за определённый месяц. В одном SQL-запросе выведены метрики по группам пользователей: ARPU, ARPAU, CR в покупку, CR-активного пользователя в покупку, CR пользователя из активности по математике. Реализованы две функции. Первая автоматически подгружает информацию из дополнительно файла и на основании дополнительных параметров пересчитывает метрики. Вторая - строит графики по получаемым метрикам. |
