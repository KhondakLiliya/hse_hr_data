[Файлик гугл-шит](https://docs.google.com/spreadsheets/d/1yzMOUtRVrSZLrxQUcl1OZlIyO4oC6up86WvnjGyt3yk/edit?usp=sharing)

**Проблемы датасета:**  

 * Не у каждого пассажира имеются данные в столбцах "Age" и "Cabin";  
 * Разные форматы значений в столбцах  
     "Age" (*например, 0.83 и 28.5*),  
     "Ticket" (*например, A/5. 2151 и 347082*),  
     "Fare" (*например, 08.05 и 8.4583*). 

**Причины возникновения проблем:**  

В момент сбора информации:
  * какие-то данные были неизвестны изначально и/или просто не внесены в список (*например, возраст или каюта*);  
  * данные могли собираться разными людьми, поэтому форматы значений разные;  
Разный формат значений можно также объяснить переносом в цифровой формат файла и возможно это происходило несколько раз, пока данный датасет не дошел до нас (*Титаник же затонул аж в 1912 году*).  

**Пути решений проблем:**  

 * Недостающую информацию востановить путем обращения к первоисточнику;   
 * Форматы значений также уточнить в первоисточнике;  
 * Наиболее простое и доступное решение, привести форматы к единому виду, в соответствии с имееющейся информацией.


> Шансы на выживание для Леонардо Ди Каприо - Мужчина в крошечной каюте 3 класса: **13,54%**
>  
> Шансы на выживание для Кейт Уинслет - Женщина в комфортабельной каюте 1 класса: **96,81%**

> Число выживших пассажиров женского пола: **233**
