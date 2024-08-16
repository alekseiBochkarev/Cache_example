# Cache_example

Пример кода и заголовков:

HTML (index.html):
```HTML
<!DOCTYPE html>
<html>
<head>
    <title>Кэш Браузера Пример</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Привет, мир!</h1>
    <img src="image.png" alt="Example Image">
</body>
</html>
```
CSS (styles.css):
```CSS
body {
    font-family: Arial, sans-serif;
}

h1 {
    color: blue;
}
```
Заголовки HTTP:
```
HTTP/1.1 200 OK
Cache-Control: max-age=3600
ETag: "abcdef12345"
```

Объяснение заголовков:

Cache-Control: max-age=3600 указывает браузеру, что ресурс может храниться в кэше в течение одного часа (3600 секунд).
ETag: "abcdef12345" — это уникальный идентификатор версии ресурса. При следующем запросе браузер может отправить этот ETag на сервер, чтобы проверить, изменилась ли версия ресурса.
