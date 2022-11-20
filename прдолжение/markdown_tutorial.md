# Туториал по языку разметки Markdown

## Загаловки 


## Списки 

gg wp


## Таблицы 

для того что бы добавить таблицу в markdown нужно будет пойти некоторые ухищрения. Воспользуемся разметкой GFM, пример: 
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать: 

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.
Воспользуйтесь тегом table:
```
 <table><tr><td></tr></td><table>
 ```

 ## Изображения 

 Что бы работать с Изображениями в Markdown используйте следующую конструкцию: 
 !["Альтернативныйтекст"](https://ru.wikiquote.org/wiki/Природа#/media/Файл:140-P1020281_-_Flickr_-_Laurie_Nature_Bee.jpg)
    

    
