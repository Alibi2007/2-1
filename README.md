<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Форма регистрации</title>
</head>
<body>
    <h1>Регистрационная форма</h1>
    <form action="#" method="post">
        <fieldset>
            <legend>Личная информация</legend>
            <label for="name">Имя:Жанибек хан</label>
            <input type="text" id="name" name="name" required>
            <br><br>
            <label for="">email</label>
            <input type="email" id="email" name="email" required>
            <br><br>
            <label for="password">Пароль:</label>
            <input type="password" id="password" name="password" required>
            <br><br>
            <label for="comments">Комментарий:Жони</label>
            
<textarea id="comments" name="comments" rows="4" cols="30"></textarea>
        </fieldset>
        <br>
        <fieldset>
            <legend>выбор страны</legend>
            <label for="country">Страна:</label>
            <select id="country" name="country">
                <option value="Россия">Россия</option>
                <option value="США">США</option>
                <option value="Канада">Канада</option>
            </select>
        </fieldset>
        <br>
        <button type="submit">Отправить</button>
        <button type="reset">Сбросить</button>
    </form>

</body>
</html>
