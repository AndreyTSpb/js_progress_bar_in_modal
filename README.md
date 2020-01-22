# js_progress_bar_in_modal
JS. Progress bar in a modal window. js with bootstrap 4

Прогрес бар в модалке. 
Возможное использование для индикации загрузки данных при асинхронном запросе.

>Для работы требуется: 
>1) bootstrap-4
>2) jquery
> показать и скрыть модалку через jquery 
```js 
$('#'+ id_modal).modal('show'); 
```

Запуск осуществляется функцией viewModal(id_modal, length),
которая принимает два параметра: 
  id_modal - идентификатор модалки 
  и length - начало отсчета и стартовая длинна прогресс-бара
  
  
 В данном примере повешен слушатель на кнопку с идентификатором str-progres
 ```js
 document.getElementById('str-progres').addEventListener('click',()=>viewModal('mod_prog', 50));
 ```
