<h1>Критерії приймання</h1>

<ul>
<li> Створено репозиторій goit-react-hw-08-phonebook</li>
<li> При здачі домашньої роботи є посилання на вихідні файли та робочі сторінки кожного проекту на GitHub Pages</li>
<li> При запуску коду завдання, в консолі немає помилок та попереджень</li>
<li> Для кожного компонента є окрема папка з файлом компонента React та файлом стилів</li>
<li> Для компонентів описано propTypes</li>
</ul>

<h2>Книга контактів</h2>
  
<p> Додай у програму «Книга контактів» можливість реєстрації, логіна та оновлення користувача, а також роботу з приватною колекцією контактів.</p> 

<h2>Бекенд</h2>

<p> Для цього завдання є готовий бекенд. Ознайомся з <a href="https://connections-api.herokuapp.com/docs/">документацією</a>. Він підтримує всі необхідні операції з колекцією контактів, а також реєстрацію, логін та оновлення користувача за допомогою JWT. Використовуй його замість твого бекенда створеного через сервіс mockapi.io.</p> 

<h2>Маршрутизація</h2>

<p> Додай маршрутизацію з бібліотекою React Router. У програмі має бути кілька сторінок:</p> 

<p> - /register - публічний маршрут реєстрації нового користувача з формою.</p> 
<p> - /login - публічний маршрут логіна існуючого користувача з формою</p> 
<p> - /contacts - приватний маршрут для роботи зі списком контактів користувача</p> 

Додай компонент навігації Navigation з посиланнями для переходу по маршрутах.

<h2>Меню користувача</h2>

Створи компонент UserMenu, що відображає пошту користувача і кнопку виходу з облікового запису. Ось як може виглядати його розмітка.

![image](https://github.com/0trava/-goit-react-hw-08-phonebook/assets/102797527/65736d5a-8cda-4f0f-9c87-2b3c3bf1218a)

<h2>Стилізація</h2>

<p>Це фінальна версія програми, тому попрацюй над оформленням інтерфейсу. Можна використовувати бібліотеку стилізації або компонентів, наприклад Chakra UI або Material UI.</p> 



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h1>JSON Web Token</h1>

<p> Один із механізмів авторизації це JWT (JSON Web Token). Токени надають собою засіб авторизації для кожного запиту від фронтенду до бекенду. Токени створюються на бекенді ґрунтуючись на секретному ключі, який зберігається на сервері, та якихось унікальних для користувача даних, наприклад пошта тощо. Токен у результаті зберігається на фронтенді і використовується за необхідності авторизації будь-якого запиту.

Кожен токен це унікальний зашифрований рядок, який містить три блоки: заголовок (header), набір полів (payload) та сигнатуру. При спробі зловмисником підмінити дані в header або payload, токен стане не валідним, оскільки сигнатура не відповідатиме початковим значенням. А можливість згенерувати нову сигнатуру у зловмисника відсутня, оскільки секретний ключ для зашифрування лежить на сервері.</p>

![image](https://github.com/0trava/-goit-react-hw-08-phonebook/assets/102797527/f307d71e-f068-476c-9f33-817d17547206)
