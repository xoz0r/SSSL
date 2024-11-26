## Практическая работа №4. Network Threat Hunting
Выполнил студент группы ББМО-01-23 Бакин Д.И.

![image](https://github.com/user-attachments/assets/418f6221-c46e-4075-b5bd-fca76aa8993c)

![image](https://github.com/user-attachments/assets/a2b7df45-0639-46fd-beca-3513adbf6a2b)

![image](https://github.com/user-attachments/assets/1e940252-b38a-4629-8427-cea58ec13224)

Выбор датасета
![image](https://github.com/user-attachments/assets/a7e63b49-0b55-4d69-93bf-851d4abab48e)

![image](https://github.com/user-attachments/assets/bda33df5-4ba5-492f-93eb-7ed2023934bf)

Добавляем в вайтлист пул сети Skype

![image](https://github.com/user-attachments/assets/59458189-e745-43bf-b3d8-9b41cf328d13)

![image](https://github.com/user-attachments/assets/45877260-4c4e-4d4b-8590-acc3c2f647fd)

Импорт логов

![image](https://github.com/user-attachments/assets/2caeb897-0e9c-491c-9222-74b60a5c5b0c)

![image](https://github.com/user-attachments/assets/8a2babdf-c0bd-41c8-838d-cf631044ef2e)

Смотрим далее

Первый адрес

![image](https://github.com/user-attachments/assets/0a965308-e9b8-4c10-b357-2bdb1657d674)

Выводы о данном адресе:

Очень высокий показатель beacon score.
За последние 24 часа было сделано множество подключений (3 011).
Гистограмма выглядит относительно ровной.
Отсутствует строка хостинга. Необходимо указать полное доменное имя веб-сервера.

Второй адрес

![image](https://github.com/user-attachments/assets/6614a1d9-a27d-4d1e-8787-2ec70cd74b50)

Легитимный домен майкрософт исключаем и остаются 2 адреса

![image](https://github.com/user-attachments/assets/5073acb6-ab8e-4cda-aa6e-334838a4d4a9)

В долгих подключениях:

![image](https://github.com/user-attachments/assets/786f5b56-5432-44f4-bc75-492e4238c15c)

![image](https://github.com/user-attachments/assets/b9930bc2-c834-4bf6-87b8-9035157fc322)

![image](https://github.com/user-attachments/assets/96d62895-e266-4e86-b9f0-481948ce0cda)

![image](https://github.com/user-attachments/assets/a8cdac23-3f6f-431e-a941-16eccdb222b9)

торой IP связан с microsoft

![image](https://github.com/user-attachments/assets/c3c5601d-920b-4434-947f-e5a3b6fc3ba9)

![image](https://github.com/user-attachments/assets/e822a4f6-9b67-43dd-9a7d-e291868e7402)

![image](https://github.com/user-attachments/assets/1f84a3a4-f91b-45ec-9196-b88bc40838d2)

![image](https://github.com/user-attachments/assets/d112bc9a-56f8-47e4-bc37-475fc4fa0553)

![image](https://github.com/user-attachments/assets/3f90b880-4501-431f-b023-8c0e2a69a113)

![image](https://github.com/user-attachments/assets/fb6fb60c-e8a5-4720-a90f-c30d57237daa)

Что можно понять о данном адресе:

Подозрительно выглядит доменное имя skypetm
Очень высокий показатель beacon score.
За последние 24 часа было сделано множество подключений (3 188).
Гистограмма выглядит относительно ровной.

Еще один адрес

![image](https://github.com/user-attachments/assets/95a16214-2247-4a11-be3f-d335bc931d1c)

![image](https://github.com/user-attachments/assets/0f58a898-0241-40a8-a3cc-d0fc0d924d5f)

Легитимный домен майкрософт















