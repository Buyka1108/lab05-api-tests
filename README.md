# Лаборатори №5: API систем тест — Postman ба Newman

## Оюутны мэдээлэл

- Нэр: Буянхишиг
- Оюутны код: B232270114
- Хичээл: F.CSA313 — Программ хангамжийн чанарын баталгаа ба тест

## Ажлын орчин

- Үйлдлийн систем: Windows
- Терминал: PowerShell
- Node.js: v24.14.0
- npm: 11.9.0
- Git: 2.54.0.windows.1
- Newman: 6.2.2

Хувилбар шалгасан командууд болон гаралт:

    PS D:\user\Downloads\lab05> node -v
    v24.14.0

    PS D:\user\Downloads\lab05> npm -v
    11.9.0

    PS D:\user\Downloads\lab05> git --version
    git version 2.54.0.windows.1

    PS D:\user\Downloads\lab05> newman -v
    6.2.2

## Лабораторийн зорилго

Хичээлд бүртгүүлэх REST API дээр тест дизайны таван алхмыг
хэрэгжүүлж, Postman-аар бие даасан тестүүд үүсгэн,
Newman-аар автоматаар ажиллуулж үр дүнг шалгах.

## Тестлэх функц

- Метод: POST
- Endpoint: /registrations
- Серверийн хаяг: http://localhost:3000
- Postman collection variable: baseUrl