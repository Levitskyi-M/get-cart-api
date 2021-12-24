# GET Cart API for OpenCart 2.3 / 3.0 and ocStore 2.3 / 3.0

Модуль позволяет создать ссылку, при открытии которой товар с указанным product_id добавится в корзину.

Это может оказаться полезным в маркетинге, e-mail рассылках, или например, если вы хотите добавлять товар в корзину сайта с Турбо-страниц Яндекса.

Пример ссылки для добавления товара id = 1 в корзину

```
https://example.com/index.php?route=product/product/addtocart&product_id=1
```

Пример ссылки для добавления в корзину 5 единиц товара с id = 1

```
https://example.com/index.php?route=product/product/addtocart&product_id=1&quantity=5
```

Если у товара будут обязательные к заполнению опции - вместо добавления в корзину откроется страница товара.

## Установка

1. Скачайте дистрибутив модуля `get-cart-api.ocmod.zip` из раздела `Releases`
2. Откройте в раздел `Модули / Расширения -> Установка расширений` (`Extensions -> Installer`) в настройках вашего магазина
3. Загрузите архив
4. Перейдите в раздел `Модули / Расширения -> Модификаторы` (`Extensions -> Modifications`) и нажмите кнопку `Обновить` (`Refresh`) - голубая кнопка в верхнем правом углу

Должна появиться модификация `GET Cart API`.

Если возникли проблемы — опишите вашу ситуацию, создав задачу: https://github.com/Levitskyi-M/get-cart-api/issues
