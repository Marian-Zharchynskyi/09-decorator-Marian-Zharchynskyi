Опис програми
Ця програма демонструє використання паттерну декоратор для ресторанного меню з сезонними пропозиціями. Вона надає можливість ресторанам легко інтегрувати сезонні пропозиції до існуючого меню.

Класи
IMenu: Інтерфейс, який визначає метод Display(), який буде реалізовано класами, що представляють меню.

BasicMenu: Конкретний клас, що реалізує інтерфейс IMenu. Представляє базове меню ресторану.

MenuDecorator: Абстрактний клас, який реалізує інтерфейс IMenu та містить посилання на обгортаний об'єкт IMenu.

SeasonalMenuDecorator: Конкретний декоратор, що реалізує функціонал додавання сезонних пропозицій до меню.

DailySpecialsDecorator: Додатковий конкретний декоратор, який реалізує можливість додавання особливих пропозицій дня до меню.

Діаграму класів програми можна переглянути за посиланням тут.
