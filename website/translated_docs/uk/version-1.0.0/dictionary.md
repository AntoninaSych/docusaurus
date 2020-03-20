---
id: version-1.0.0-dictionary
title: dictionary
original_id: dictionary
---
## Довідник. Статуси платежу


| значення | статус                                  |
|--------------|------------------------------------------|
| ON-PAYMENT   | платіж здійснюється                       |
| NEW          | Платіж створений, очікується введення реквізитів |
| APPROVED     | платіж успішний                           |
| DECLINED     | платіж відхилений                          |
| REFUNDINPROC | В процесі повернення                     |
| REFUNDED     | повернуто                                |
| EXPIRED      | платіж прострочений                        |
| WAITING-AUTH | Чекає підтвердження авторизації        |
| 3ds          | Вимагає перевірки 3D-Secure              |



## Довідник. коди відповідей

| Код  | Розшифровка                                                                                                                                                  | Расшифровка (ENG)                                                       |
|------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| 1    | ОПЕРАЦІЯ дозволено                                                                                                                                          |                                                                         |
| 50   | Фінансова транзакція не виконана                                                                                                                           | General                                                                 |
| 51   | Карта клієнта прострочена                                                                                                                                     | Expired card                                                            |
| 52   | Перевищено число спроб введення PIN                                                                                                                            | Number of PIN tries exceeded                                            |
| 53   | Чи не вдалося маршрутизировать транзакцію                                                                                                                       | No sharing allowed                                                      |
| 55   | Транзакція має некоректні атрибути або дана операція не дозволена                                                                                      | Invalid transaction                                                     |
| 56   | Запитувана операція не підтримується хостом                                                                                                              | Transaction not supported by institution                                |
| 57   | Карта клієнта має статус 'втрачена' або 'вкрадена'                                                                                                         | Lost or stolen card                                                     |
| 58   | Карта клієнта має неправильний статус                                                                                                                      | Invalid card status                                                     |
| 59   | Карта клієнта має обмежені можливості                                                                                                                 | Restricted status                                                       |
| 60   | Не вдалося знайти вендор із зазначеним номером рахунку                                                                                                                   | Account not found                                                       |
| 61   | Неправильне кількість інформаційних полів для заданого вендора                                                                                              | Wrong customer information for payment                                  |
| 62   | Невірний формат інформаційного поля платежу                                                                                                                 | Customer information format error                                       |
| 63   | Не вдалося знайти prepaid-код                                                                                                                                        | Prepaid Code not found                                                  |
| 64   | Track2 картки клієнта містить невірну інформацію                                                                                                           | Bad track information Track2                                            |
| 69   | Невірний формат повідомлення                                                                                                                                   | Bad message edit                                                        |
| 74   | неможливо авторизувати                                                                                                                                      | Unable to authorize                                                     |
| 75   | Невірний PAN карти                                                                                                                                           | Invalid credit PAN                                                      |
| 76   | На рахунку не вистачає засобів                                                                                                                                 | Insufficient funds                                                      |
| 78   | Сталося дублювання транзакції                                                                                                                            | Duplicate transaction received                                          |
| 82   | Перевищення кількості використань карти клієнта                                                                                                            | Maximum number of times used                                            |
| 85   | Неможливо видати баланс                                                                                                                                     | Balance not allowed                                                     |
| 95   | Перевищення ліміту за сумою                                                                                                                                   | Amount over maximum                                                     |
| 100  | Неможливо провести транзакцію                                                                                                                               | Unable to process                                                       |
| 101  | Неможливо авторизувати - необхідно зателефонувати видавцеві карти                                                                                                | Unable to authorize – call issuer                                       |
| 105  | Даний тип карт не підтримується                                                                                                                            | Card not supported                                                      |
| 200  | Неправильний рахунок клієнта                                                                                                                                    | Invalid account                                                         |
| 201  | неправильний PIN                                                                                                                                             | Incorrect PIN                                                           |
| 205  | Некоректна сума                                                                                                                                           | Invalid advance amount                                                  |
| 209  | Невірний код транзакції                                                                                                                                      | Invalid transaction code                                                |
| 210  | Некоректне значення CAVV                                                                                                                                       | Bad CAVV                                                                |
| 211  | Некоректне значенняCVV2                                                                                                                                       | Bad Cvv2                                                                |
| 212  | Чи не знайдена оригінальна транзакція для сліпа                                                                                                                | Original transaction not found for slip                                 |
| 213  | Сліп приймається повторно                                                                                                                                    | Slip already received                                                   |
| 501  | Транзакція виконана успішно                                                                                                                                 | Approved                                                                |
| 502  | Транзакція виконана успішно на часткову суму                                                                                                              | Partially approved                                                      |
| 503  | Транзакція виконана успішно тільки на суму покупки (для транзакції 118 - Purchase with Cashback)                                                           | Purchase only approved                                                  |
| 510  | Немає номера рахунку в запиті транзакції, є кілька рахунків зазначеного типу, і термінал підтримує вибір рахунки                                            | Should select account number                                            |
| 511  | Необхідно змінити PVV (дозволена тільки транзакція PIN Change)                                                                                              | Should change PVV                                                       |
| 512  | Необхідно підтвердити результати перевірки платежу в системі online-прийому платежів                                                                          | Confirm Payment Precheck                                                |
| 513  | Транзакція запиту списку повідомлень виконана успішно                                                                                                      | Select Bill                                                             |
| 514  | Необхідно підтвердити результати предпроверкі операції                                                                                                      | Customer confirmation requested                                         |
| 515  | Чи не знайдена оригінальна транзакція                                                                                                                           | Original transaction not found                                          |
| 516  | Сліп вже прийнятий                                                                                                                                              | Slip already received                                                   |
| 517  | Помилка у реквізитах платежу                                                                                                                                  | Personal information input error                                        |
| 520  | Неможливо захопити Prepaid-код                                                                                                                             | Prepaid code not found                                                  |
| 521  | Баланс кор. рахунку вичерпаний                                                                                                                                 | Corresponding account exhausted                                         |
| 522  | Перевищено еквайрингової ліміт                                                                                                                                 | Acquirer limit exceeded                                                 |
| 524  | Закінчився термін дії діаміческого PVV                                                                                                                         | Dynamic PVV Expired                                                     |
| 525  | слабкий PIN                                                                                                                                                   | Weak PIN                                                                |
| 540  | Карта втрачена                                                                                                                                               | Lost card                                                               |
| 541  | карта украдена                                                                                                                                               | Stolen card                                                             |
| 549  | Неприпустимий тип платежу для даного вендора                                                                                                                 | Ineligible vendor account                                               |
| 550  | несанкціоноване використання                                                                                                                            | Unauthorized usage                                                      |
| 551  | Закінчився термін дії карти                                                                                                                                    | Expired card                                                            |
| 552  | Невірна карта                                                                                                                                               | Invalid card                                                            |
| 553  | Неправильний PIN-код                                                                                                                                             | Invalid PIN                                                             |
| 554  | Системна помилка                                                                                                                                             | System error                                                            |
| 555  | невідповідна транзакція                                                                                                                                     | Ineligible transaction                                                  |
| 556  | невідповідний рахунок                                                                                                                                            | Ineligible account                                                      |
| 557  | Транзакція не підтримується                                                                                                                                 | Transaction not supported                                               |
| 558  | Карта обмежена (дана операція по картці не вирішена)                                                                                                    | Restricted Card                                                         |
| 559  | Недостатньо коштів на рахунку                                                                                                                                | Insufficient funds                                                      |
| 560  | Перевищено ліміт на число використань карти                                                                                                                  | Uses limit exceeded                                                     |
| 561  | Ліміт на зняття готівки буде перевищено                                                                                                                      | Withdrawal limit would be exceeded                                      |
| 562  | Досягнуто або перевищено ліміт на число невірних спроб правильно ввести PIN                                                                                               | PIN tries limit was reached                                             |
| 563  | Досягнуто ліміт на зняття готівки                                                                                                                           | Withdrawal limit already reached                                        |
| 564  | Досягнуто ліміт на депозит                                                                                                                                   | Credit amount limit                                                     |
| 565  | Немає інформації для надання звіту за рахунком                                                                                                            | No statement information                                                |
| 566  | Надання звіту по рахунку неможливо (заборонено)                                                                                                        | Statement not available                                                 |
| 567  | неприпустима сума                                                                                                                                           | Invalid amount                                                          |
| 568  | Транзакція відкинута зовнішнім хостом                                                                                                                         | External decline                                                        |
| 569  | Неузгоджений запит (дана картка не обслуговується в даному терміналі)                                                                                    | No sharing                                                              |
| 571  | Необхідно звернутися до видавця                                                                                                                             | Contact card issuer                                                     |
| 572  | авторизатор недоступний                                                                                                                                      | Destination not available                                               |
| 573  | Помилка маршрутизації                                                                                                                                        | Routing error                                                           |
| 574  | Помилка формату                                                                                                                                               | Format error                                                            |
| 575  | Транзакція відкинута зовнішнім хостом за спеціальним умові (власник карти підозрюється в шахрайстві)                                                  | External decline special condition                                      |
| 580  | невірний CVV                                                                                                                                                | Bad CVV                                                                 |
| 581  | невірний CVV2                                                                                                                                                | Bad CVV2                                                                |
| 582  | Невірна транзакція (транзакція не дозволена з такими умовами проведення)                                                                                  | Invalid transaction                                                     |
| 583  | Ліміт на число невірних спроб правильно ввести PIN ВЖЕ досягнутий (тобто раніше був досягнутий ліміт на число невірних спроб правильно ввести PIN, після чого був введений вірний PIN)| PIN tries limit was exceeded                                            |
| 584  | Некоректна перевірочного числа 3D Secure Cardholder Authentication Verification Value                                                               | Bad CAVV                                                                |
| 585  | Некоректна криптограми ARQC                                                                                                                          | Bad ARQC                                                                |
| 800  | Помилка формату                                                                                                                                               | Format error                                                            |
| 801  | Чи не знайдена оригінальна транзакція для реверсу                                                                                                               | Original transaction not found                                          |
| 809  | Невірна операція закриття періоду                                                                                                                           | Invalid close transaction                                               |
| 810  | Стався тайм-аут                                                                                                                                           | Transaction timeout                                                     |
| 811  | Системна помилка                                                                                                                                             | System error                                                            |
| 820  | Неправильний ідентифікатор терміналу                                                                                                                         | Invalid terminal identifier                                             |
| 880  | Був посланий останній пакет - прогрузкі успішно завершена                                                                                                     | Download has been received in its entirety                              |
| 881  | Попередній етап прогрузкі був успішно виконаний -чи ще дані                                                                                           | Download received successfully and there is more data for this download |
| 882  | Прогрузкі терміналу зупинена. Необхідно зателефонувати в процесинговий центр                                                                                 | Download aborted (call for service)                                     |
| 897  | Отримано невірна криптограма в транзакції                                                                                                                 | Invalid cryptogram                                                      |
| 898  | Отримано невірний MAC                                                                                                                                        | Invalid MAC                                                             |
| 899  | Помилка синхронізації                                                                                                                                         | Sequence error—resync                                                   |
| 900  | Перевищено число спроб введення PIN. Потрібно захоплення карти                                                                                                    | Pin Tries Limit Exceeded                                                |
| 901  | Карта прострочена, потрібно захоплення карти                                                                                                                    | Expired Card                                                            |
| 909  | Потрібно захоплення карти                                                                                                                                       | External Decline Special Condition                                      |
| 959  | Адміністративна транзакція не підтримується                                                                                                                | Administrative transaction not supported                                |
| 2001 | Необхідна верифікація 3DS                                                                                                                                   | Need 3ds verify                                                         |

## Довідник. Коди системних помилок

| Код  | Розшифровка                               | Розшифровка (ENG)                        |
|------|-------------------------------------------|------------------------------------------|
| -1   | Системна помилка                         |                                          |
| -2   | не переданий параметр merchant_id           | General                                  |
| -3   | Мерчант не знайден                         | Expired card                             |
| -4   | неправильна підпис                     | Number of PIN tries exceeded             |
| -5   | Ліміт на виконання операцій              | No sharing allowed                       |
| -6   | Невірний номер карти                      | Invalid transaction                      |
| -7   | Невірна валюта                           | Transaction not supported by institution |
| -8   | Неверный  order_id                        | Lost or stolen card                      |
| -9   | Операція з таким order_id вже існує | Invalid card status                      |
| -10  | Платіж не найден                         | Restricted status                        |
| -11  | Невірний тип операції                    | Account not found                        |
| -999 | Системна помилка                         | Wrong customer information for payment   |