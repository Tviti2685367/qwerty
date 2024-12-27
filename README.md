# Репозиторій Qwerty 📚

Ласкаво просимо до репозиторію Qwerty! 🎉 Цей проект розроблений для того, щоб допомогти вам з ознайомленням мого педагогічного додатка. Нижче ви знайдете всю необхідну інформацію, щоб почати.

## Зміст 📑
ButtonClickCounter відповідає за обробку натискань кнопок у грі, а також за підрахунок правильних відповідей гравця. Ось основні функції та компоненти коду:
#Підрахунок правильних відповідей:
Код зберігає кількість правильних відповідей у статичній змінній correctCount, яка завантажується з PlayerPrefs при запуску скрипту. Це дозволяє зберігати прогрес між сесіями гри.
1.Завантаження сцен:
2.Метод LoadMenu скидає лічильник правильних відповідей до нуля і завантажує сцену меню.
3.Метод OnButtonClick перевіряє, чи натиснута правильна кнопка, і якщо так, збільшує лічильник правильних відповідей. У разі неправильного натискання, також виконується перехід до наступної сцени.
4.Отримання правильної кнопки:
Метод GetCorrectButton визначає, яка кнопка є правильною для кожної сцени на основі її назви.
5.Затримка перед переходом до наступної сцени:
Використовується корутина LoadNextSceneWithDelay, яка затримує перехід до наступної сцени на 1 секунду після натискання кнопки.
6.Відображення результатів:
Метод ShowResult викликається, коли гра закінчується, щоб показати підсумковий рахунок, а потім переходить до фінальної сцени.
## Вступ 🌟
Qwerty – це проект, який росповість вам деталі моєї роботи . Він має на меті проінформувати вас щодо створення мною педагогічного програмного засобу для 7 класу по предмету фізика.

## Функції ✨
- Функція 1
- Функція 2
- Функція 3

## Встановлення 🛠

    ```

## Використання 🚀
Щоб використовувати Qwerty.
actinst.exe - інсталятор педагогічного додатка.
```sh
[команда використання]
