# Mission 3

## Part 0-2

[Link to video (Первоначальный вариант с ошибкой)](https://drive.google.com/file/d/13_5g_zjUmTjmz6N4ui1fMRPeoLIZ1HYZ/view?usp=sharing)
[Исправление](https://drive.google.com/file/d/1nxQdbx7jIua92z7kZts0zMEds6ny2ZT9/view?usp=sharing)

## Part 3

- Запрос 1	 
> Ответ: **select** username **from** users

- Запрос 2	 
> Ответ: **select** "from", count(*) **as** number_of_sent_messages **from** messages **group by** "from"**

- Запрос 3	 
> Ответ: **select** "to" **as** username, count(*) **as** number_of_received_messages **from** messages **group by** "to" **order by** number_of_received_messages desc **limit 1**

- Запрос 4	 
> Ответ: Не получилось сделать
