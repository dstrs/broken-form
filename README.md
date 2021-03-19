- [ ] Починить ФИО
- [ ] Починить Email
- [ ] Починить Телефон
- [ ] Обработать состояние загрузки
- [ ] Поднять HTTP сервер и сохранять данные с формы в файл
  - [ ] Отправлять данные в телеграм
- [ ] Переписать клиент на Plain JS


## Http сервер

Использовать библиотеку `fastify`, повесить POST обработчик по адресу `/form` 

- Getting started https://www.fastify.io/docs/latest/Getting-Started/
- пример как прочитать запрос клиента https://www.fastify.io/docs/latest/Request/

## Клиент

```
browser-sync start --server .  --files .
```