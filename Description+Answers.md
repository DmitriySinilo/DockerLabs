**Опис скриншотів**
**Спочатку запускаємо Riak в Docker.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/1.PNG)
**Зображена стартова сторінка Riak.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/2.PNG)
**Відсилаємо запит на /ping  щоб перевірити що з’єднання працює.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/3.PNG)
**Додаємо у сегмент Persons новий об’єкт персони.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/5.PNG)
**Переглядаємо що у сегменті Persons є новий об’єкт, використовуємо атрибут keys=true щоб переглянути усі id об’єктів.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/6.PNG)
**Відсилаємо PUT запит на зміну даних.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/8.PNG)
**Бачимо зміни відбулися.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/9.PNG)
**Відсилаємо запит на видалення об’єкту.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/10.PNG)
**Об’єкт більше не в колекції.**
![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/11.PNG)
**Контрольні запитанні**
1.	Що таке Riak?
2.	Яку модель використовує Riak?
3.	Як отримати запис із Riak?
4.	Як додати запис в Riak?
5.	Як модифікувати запис в Riak?
6.	Як видалити запис в Riak?
**Відповіді на контрольні запитання**
1. Riak - це розподілене сховище ключів і значень, в якому значенням може бути що завгодно - простий текст, документ в форматі JSON або XML, зображення або відеокліп. Для доступу до сховища надається простий і одноманітний HTTP-інтерфейс. З усіма даними якими працює користувач, Rik їх зберігає.
2. модель даних типу "ключ-значення" забезпечує гнучкість без визначеної схеми роботи
3. За допомогою запиту Get
4. За допомогою запиту Post
5. За допомогою запиту Put
6. За допомогою запиту Delete

![Image1](https://github.com/DmitriySinilo/DockerLabs/blob/lab6/lb6/1.PNG)
