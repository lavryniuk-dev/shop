# shop
Конфигурация симулирует простой магазин товаров (1С:Предприятие 8.3, учебная версия 8.3.8.1933)

Доступны следующие справочники:
- Валюты (В справочнике имеются 3 предопределенные валюты USD, EUR, а также UAH)
- Номенклатура
- Контрагенты
- Договоры
- Сотрудники
- Склады

Доступны следующие документы:
- Поступление товаров (На форме списка документа динамично отображаются товары из документа)
- Реализация товаров (На форме списка документа динамично отображаются остатки товаров)
- Оплата поставщику (На форме списка документа динамично отображаются задолженности перед контрагентами, на форме документа реализовано авто заполнение оплаты задолженности по кнопке заполнить)
- Списание товаров (На форме списка документа динамично отображаются списанные товары из документа)

Доступны следующие регистры сведений:
- Курсы валют (Подтягиваются курсы валют (для USD, а также EUR) при помощи регламентного задания или по кнопке заполнить на форме списка регистра)
- Учетная политика (Хранит метод списания себестоимости в пределах года)

Доступны следующие регистры накоплений:
- Остатки товаров (Отображает остатки товаров, реализовано списание себестоимости по методам FIFO и LIFO, а также на форме списка реализована возможность отбора по номенклатуре)
- Взаиморасчеты (Отображает задолженности перед контрагентами)
- Продажи (Отображает продажи)

Доступны следующие отчеты:
- Остатки (Отображает остатки товаров на дату и цену товара в выбранной валюте)
- Продажи (Отображает продажи товаров по заданной валюте)
- Себестоимость (Отображает себестоимость товаров, а также маржу и цену по заданной валюте)
