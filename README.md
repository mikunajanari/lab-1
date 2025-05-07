# lab-1
Ознайомлення з TypeScript

## 1. Типізація змінних
  Оголосимо змінні з типами  string, number, boolean, array, object. Створимо функцію, яка приймає як аргумент об'єкт із полями name (тип string) та age (тип number).

  ![image](https://github.com/user-attachments/assets/f40e3b35-1733-48b4-90da-ea13b63543ff)

  ### .JS
  Код успішно трансформовано в коректний JavaScript. Типи зникають після компіляції (типізація лише для етапу розробки). use strict - забезпечує суворий режим (безпечніший синтаксис JS).

  ![image](https://github.com/user-attachments/assets/cde86371-d350-44af-8d03-07fb97b460e2)

  ### .D.TS
  Описує інтерфейс програми, які змінні і функції доступні та які в них типи. Генерація .d.ts файлу підтверджує правильну типізацію і дозволяє легко повторно використовувати ці типи.
  
  ![image](https://github.com/user-attachments/assets/0b534c31-6bee-42c4-add7-69172d9ed1f3)

  ### Logs
  Демонструє практичне застосування написаної функції.

  ![image](https://github.com/user-attachments/assets/6f04ef36-b4f9-425e-bbb1-edc0e9453791)

  ### Errors
  У вкладці Errors пусто. Зробимо помилку навмисно - присвоїмо змінній age рядок "30".
  
  ![image](https://github.com/user-attachments/assets/a891fdcc-c3a5-4aa6-93d2-c368127942cd)

## 2. Інтерфейси
  Оголосимо інтерфейс Person з полями name, age, address. Реалізуємо функцію printPerson, яка приймає об'єкт типу Person та виводить його дані у консоль.

  ![image](https://github.com/user-attachments/assets/67b0f00d-7f2f-4181-a0ce-19c6808ca880)

  ### .JS
  JavaScript не підтримує статичну типізацію, тому можемо створювати об'єкти без визначення типів, і JavaScript самостійно визначатиме типи на основі значень.
  
  ![image](https://github.com/user-attachments/assets/fe3b5d72-df8d-48a1-84f9-989de0b41daf)

  ### .D.TS
  
  ![image](https://github.com/user-attachments/assets/b77d27ee-87d4-4e63-ad16-edf7e4dba14c)

  ### Logs
  З вказаною адресою:
  
  ![image](https://github.com/user-attachments/assets/ec36ed4a-7d80-4f55-be4a-e333c10078d0)

  Без вказаної адреси:
  
  ![image](https://github.com/user-attachments/assets/90ebc9ea-6f42-41cf-aa89-4ae71ffcaea8)

  
  ### Errors
  У вкладці Errors пусто. Зробимо помилку навмисно - створимо об'єкт user без властивості age.
  
  ![image](https://github.com/user-attachments/assets/48afc60b-2b79-4dbd-937d-78b27a374c05)

## 3. Композитні типи
  Оголосимо об'єднаний тип та реалізуємо функцію, яка виводить повідомлення відповідно до значення Status.

  ![image](https://github.com/user-attachments/assets/fab42fad-08ed-4f89-9833-8bbba151fd49)

  ### .JS
  У .JS файлі не видно типу Status, бо типи існують лише під час розробки в TypeScript і не входять до зібраного коду.
  
  ![image](https://github.com/user-attachments/assets/b87ce315-93f8-4eaf-8ee0-3a7b4021143c)

  ### .D.TS
  
  ![image](https://github.com/user-attachments/assets/af42f3d5-ca1f-49dc-80c1-d34aea85d6e8)

  ### Logs
  
  ![image](https://github.com/user-attachments/assets/e2e41643-dc5e-4dff-b646-26f3a843ce5c)
  
  ### Errors
  У вкладці Errors пусто. Зробимо помилку навмисно - передамо значення, відсутнє у типі Status.

  ![image](https://github.com/user-attachments/assets/c0498926-d828-4678-81f6-da6653dab763)

## 4. Дженерики
  Реалізуємо функцію, яка повертає передане їй значення. Виконаємо її для типів number, string та boolean.
  

  ### .JS
  

  ### .D.TS
  

  ### Logs
  
  
  ### Errors


