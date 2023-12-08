<!-- Создаём заголовок с помощью символа "#" -->
# Twitter BootsTrap 
![Bootstrap logo](https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png)
[официальниый сайт](https://getbootstrap.com/) <!--Оформление гиперссылок-->
<!-- Стилизация текста -->
**Twitter Bootstrap** - CSS-фреймворк. Популярный набор компонентов для фронтенд-разработки.
Построен на базе следующих технологий:
* HTML
* CSS
* JavaScript
## Начало работы
Есть несколько вариантов подключения:
* CDN <!-- Элементы списка делаются с помощью табуляции -->
* NPM
### Установка через CDN 
Откройте консоль и выполните следующую команду: npm install bootstrap
### Установка через NPM
Если вы хотите подключить только CSS (без JavaScript плагинов), добавьте в ваши html-файлы следующий код:

Для JavaScript необходимо добавить следующий код:
## Использование
Все возможности по использованию описаны в официальной документации.
<!-- Вставка примеров кода -->
``` html
      <div class="card" style="width:100%;">
        <img src="IMG/intro.jpg" class="card-img-top" height="500px" alt="intro">
        <div class="card-body col-12 position-absolute top-50 start-50 translate-middle ">
          <h5 class="card-title text-center text-white display-5">Клиника RUBIN</h5>
          <p class="card-text text-center text-white fs-2 mb-3">Наше тело все время говорит с нами. Если бы мы только нашли время послушать.</p>
          <button type="button" class="btn btn-success btn-lg d-block  text-white mx-auto ps-3 pe-3">Записаться</button>
        </div>
      </div>
```
```css
.navi {
  max-width: 180px;
}
```
```javascript
// 13. sort - позволяет отсортировать массив по их кодовому значению. Мутирует массив
const arr2 = [2, 55, 10, 4, 1254, -14, 0, 8];
const newArr3 = arr2.sort();
  console.log(newArr3, arr2.sort());

  const arr4 = [2, 55, 10, 4, 1254, -14, 0, 8];
  const newArr4 = arr2.sort((a, b) => {
    console.log(a, b);
    // return (a - b);
    if(a > b) return -1;
    if(a === b) return 0;
    if(a < b) return 1;
  });
  console.log(arr4);
```

