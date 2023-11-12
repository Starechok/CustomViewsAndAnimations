
### Домашнее задание к занятию «2.1. Custom Views — разработка собственных элементов интерфейса»

<details close><summary> Задача Smart StatsView </summary>
    <br>
    
`StatsView` принимает на вход данные, по которым сама рассчитывает проценты:
```kotlin
findViewById<StatsView>(R.id.stats).data = listOf(
    500F,
    500F,
    500F,
    500F,
)
```
По аналогии с лекцией `SmartStatsView` суммирует все данные и определяет, что каждый элемент — это ровно 25 %: 
![изображение1](https://user-images.githubusercontent.com/93938031/206427669-a70a7fbf-943d-465d-9bd9-b4bf4ac56f9b.png)

</details> 

<details close><summary> Задача Dot </summary>
    <br>

Убрана *"ошибка"* заполняемости круга, согласно изображению :arrow_down:
![изображение2](https://user-images.githubusercontent.com/93938031/206428791-25b0598c-1e66-4689-9609-3fe7aacb44c4.png)
То есть из картинки ***«Как сейчас»*** получаем ***«Как должно быть»***.

</details>

<details close><summary> Задача Not Filled* </summary>
    <br>

При выполнении предыдущих задач, заполняемость графика всегда **100 %**.

За счёт добавления дополнительного цвета с альфа-каналом реализован вариант частичного заполнения:

![изображение3](https://user-images.githubusercontent.com/93938031/206431824-7f8c28e6-fd1c-4dd7-8d91-7556e7ac8788.png)

</details>
