<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>Сайт начинающего верстальщика сайтов Шогина Романа</h1>
    </header>
    <main>
        <img class="avatar" src="https://sun9-66.userapi.com/impg/W8wzVsw7O7zggwtgnczE3EAHGnCpRPW9wQW-rw/3Omd_oHDBPM.jpg?size=344x414&quality=96&proxy=1&sign=8c7a72dabb93dd9d1bc1ea4a1914bdea&type=album" width="80" height="80" alt="Аватарка">
        <nav class="blog-navigation">
            <h2>Записи о студенте</h2>
            <ul>
                <li>Електронный адрес студента:
                <li><a href="roman.shogin2015@yandex.ru">roman.shogin2015@yandex.ru</a></li>
                <li>Университет, где я учусь:</li>
                <li><a href="https://nvsu.ru/">Нижневартовский государственный университет</a></li>
            </ul>
            <ul>
                <li><a href="https://nvsu.ru/sveden/">О НВГУ</a></li>
            </ul>
            <li>Моя группа: 3802, 3я подгруппа</li>
        </nav>
        <nav class="blog-navigation2">
            <ul>
                <h2>Моя будущая профессия</h2>
                <li>Инженер-программист.</li>
                <h2>Мои хобби:</h2>
                <li>Вышивание алмазной мозаикой</li>
                <li>Собирание паззлов от 3к деталей</li>
                <li>Оригами</li>
            </ul>
        </nav>
        <section>
            <p></p>
        </section>
    </main>
    <footer>
        <h2>Таблицы</h2>
        <table>
            <caption>Первая таблица из задания 2</caption>
            <tr>
                <td colspan="5"> </td>
            </tr>
            <tr>
                <td rowspan="3"></td>
                <td></td>
                <td rowspan="3"></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td rowspan="3"></td>
                <td rowspan="3"></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
        <table>
            <caption>Вторая таблица из задания 2</caption>
            <tr>
                <td colspan="8" class="aquamarine"> </td>
            </tr>
            <tr>
                <td rowspan="6" class="bone"> </td>
                <td colspan="6" class="aquamarine"> </td>
                <td rowspan="6" class="bone"> </td>
            </tr>
            <tr>
                <td rowspan="4" class="bone"> </td>
                <td colspan="4" class="aquamarine"> </td>
                <td rowspan="4" class="bone"> </td>
            </tr>
            <tr>
                <td rowspan="2" class="bone"> </td>
                <td class="red"> </td>
                <td class="blue"> </td>
                <td rowspan="2" class="bone"> </td>
            </tr>
            <tr>
                <td class="lime"> </td>
                <td class="yellow"> </td>
            </tr>
            <tr>
                <td colspan="4" class="aquamarine"> </td>
            </tr>
            <tr>
                <td colspan="6" class="aquamarine"> </td>
            </tr>
            <tr>
                <td colspan="8" class="aquamarine"> </td>
            </tr>
        </table>
        <h2>Формы</h2>
        <h2>ЗАО Птицефабрика №1</h2>
        <form align:center>
            <label for="fam-field">Фамилия</label>
            <input type="text" name="fam" id="fam-field"><br>
            <label for="name-field">Инициалы</label>
            <input type="text" name="name" id="name-field"><br>
            <label for="password-field">Пароль</label>
            <input type="password" name="password" id="password-field"><br>
            <label for="adress-field">Адрес получателя</label>
            <input type="text" name="adress" id="adress-field" size="30"><br>
            <label for="count-field">Количество</label>
            <input type="text" name="count" id="count-field" size="10"><br>
            <label for="type">Тип</label>
            <select name="type">
                <option value=Куриные>Куриные</option>
            </select>
            <select name="type">
                <option value=Отборные>Отборные</option>
            </select><br>
            <label for="post-field">Доставка</label>
            <input type="radio" name="post" id="post-field" checked>Почтой
            <input type="radio" name="post" id="elec-field">Электронно
            <input type="radio" name="post" id="courier-field">Курьером <br>
            <label for="check-field">Требуется накладная</label>
            <input type="checkbox" name="check" id="check-field"><br>
            <label for="comment">Дополнительная информация:</label>
            <textarea id="comment" rows=5 cols=100></textarea><br>
            <input type="submit" value="Заказать"> <input type="reset" value="Отменить"><br>
        </form>
        <h2 align:center>Пример формы регистрации</h2>
        <form align:center>
            <label for="login-field">Логин</label><br>
            <input type="text" name="login" id="login-field"><br>
            <label for="password-field">Пароль</label><br>
            <input type="password" name="password" id="password-field"><br>
            <label for="adress-field">URL-адрес сайта</label><br>
            <input type="text" name="adress" id="adress-field" value="https://"><br>
            <label for="name-field">Название сайта</label><br>
            <input type="text" name="name" id="name-field"><br>
            <label for="comment">Описание сайта:</label><br>
            <textarea id="comment" rows=5 cols=100></textarea><br>
            <label for="theme">Тема</label><br>
            <select name="type">
                <option value=light>Светлая</option>
                <option value=dark>Темная</option>
            </select><br>
            <label for="file-field">Баннер 88х31</label><br>
            <input type="file" name="file" id="file-field"><br>
            <input type="reset" value="Очистить"><input type="submit" value="Отправить"><br>
        </form>
    </footer>
</body>

</html>
