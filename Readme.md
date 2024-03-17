Рекомендация тарифов

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — её уже сделали.

Необходимо построить модель с максимально большим значением accuracy. Нужно довести долю правильных ответов по крайней мере до 0.75. Затем надо проверьте accuracy на тестовой выборке.

Описание данных

Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно: сalls — количество звонков, minutes — суммарная длительность звонков в минутах, messages — количество sms-сообщений, mb_used — израсходованный интернет-трафик в Мб, is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).