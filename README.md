
# Machine Learning
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Мой+первая+нейроная+машина)](https://git.io/typing-svg)
Не бойтесь это не Скайнет

 [](https://github.com/Yerazamat/eee/blob/main/maxresdefault.jpg) 
## Сделано с помощу 

- pandas
- sklearn


## Примеры

```python
def occupation_format(data):
    if data == -1:
        return data
    elif "university" in data:
        return 1
    elif "work" in data:
        return 2 
```


В этом примере мы меняем значения "университет" и "работа" на цифры 1 и 2.




## Данные пользователей которые были использованы:

1. Текущее занятие пользователя (школа, университет, работа). 
1. Форма обучения.
1. Год начала работы.
1. Год окончания работы.
1. Статус обучения.


## Ссылка на датасет
https://github.com/Yerazamat/eee/blob/main/train.csv




## Удалённые данные



```python
df = df.drop('id', axis = 1)
df = df.drop('bdate', axis = 1)
df = df.drop('followers_count', axis = 1)
df = df.drop('langs', axis = 1)
df = df.drop('city', axis = 1)
df = df.drop('last_seen', axis = 1)
df = df.drop('occupation_name', axis = 1)
df = df.drop('career_start', axis = 1)
df = df.drop('career_end', axis = 1)
df = df.dropуба('graduation', axis = 1)
```
Не подходящие или не нужные данные надо убрать да бы не мешались в будущем .
