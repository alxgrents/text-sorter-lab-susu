### Лабораторная работа по предмету "Введение в сервис-ориентированные архитектуры"
### 2. Приложение на основе сокетов

[Ссылка на развёрнутую часть 1](https://lab-susu-grentsav-text-sorter.herokuapp.com/)

#### Цель: 

на языке высокого уровня (Java, C#, Python и др. – на выбор обучающегося) реализовать два сетевых клиент-серверных приложения:

1. «Сортировщик слов». Клиентская программа предоставляет пользователю интерфейс ввода текстового блока, отправляет его серверу, получает и отображает пользователю все слова, представленные в тексте в алфавитном порядке без повторений. Соответственно, серверная часть приложения принимает текстовый блок, разбивает его на слова, формирует перечень использованных слов в алфавитном порядке и возвращает клиенту информацию в виде списка слов (каждое слово – с новой строки).

2. «Доска объявлений». Если клиент передает команду «LIST», то ему выводятся все объявления (текстовые строки), добавленные пользователями на доску объявлений через «;». Если клиент передает другую текстовую строку S, она сохраняется во внешнем файле (или базе данных) и пользователю возвращается подтверждение формата: Message added: “S”. Если клиент вводит пустую строку, то соединение разрывается.


