# Триксы в WinPlex

[**Список триксов**](./tricks/README.md)

## Что такое Трикс?

Трикс — это что-то вроде фокуса, некая странность в игре... Когда происходит
явление, которого никак не должно было произойти по логически правильным законам
внутриигровой физики. Сюда не входят визуальные глюки и ошибки (например,
остатками взрывов на заднем фоне), которые нельзя как-то использовать в процессе
игры.

## Почему существуют триксы?

> Любая программа содержит хотя бы одну ошибку.

Все дело в том, что игру (и любое другое программное обеспечение) разрабатывают
совершенно обычные люди. Поскольку человеку свойственно ошибаться, в программу
могут вкрасться ошибки, даже если она работает и не падает. Например, это может
быть неправильный подсчет инфотронов, неправильное распространение взрывов и
т.п. Чаще всего триксы возникают из-за того, что при написании программы бывают
ситуации, когда невозможно предусмотреть все варианты поведения. (Пойдете ли вы
налево или направо — это одно. А вот КОГДА вы туда пойдете — неизвестно.) Везде
солому не подстелешь.

## Ну и зачем нужны эти триксы?

Триксы могут помочь выйти из безвыходных ситуаций. Например, вы проходите
уровень сложным и долгим способом, который придумал автор уровня. Вы должны этот
способ разгадать. Однако часто это бывает очень трудно и мучительно. Вот тут-то
Вы вдруг вспомнили о триксах и увидели, что в этом самом сложном уровне можно
использовать какой-нибудь трикс так, чтобы в корне изменить в легкую сторону
авторскую идею прохождения этого уровня. Автор уровня обламывается, а Вы
сохраняете себе нервы и терпение.

Есть также вариант, когда уровни строятся специально с расчётом на то, что
пройти их можно только с использованием определённых триксов.

## Демо

В данном репозитории прилагается коллекция [tricks.dat][] и демки для всех
уровней, которые Вы можете просмотреть, изучить более детально, понять и
попытаться повторить.

**Примечание**: Просмотр демок возможен только в версии Winplex 1.0.0.8.
Большинство триксов были открыты и проверены именно в этой версии. Для более
ранних версий игры нет информации.

Для просмотра демок необходимо:

- поместите файл [tricks.dat][] в папку игры "Levels";
- поместите файлы из папки "[solution][solution-dir]" в папку с таким же именем
  в директории игры;
- запустите игру, выберите коллекцию "tricks.dat";
- выберите нужный уровень в списке уровней и нажмите \<D>; либо начните играть
  нужный уровень, вызовите меню \<Esc> и выберите "Демо";

**Примечание**: Чтобы сделать все уровни доступными для запуска, откройте любой
уровень, нажмите клавишу \<~>, введите `FA`, нажмите \<Enter>. Команда `FA`
открывает любые уровни для просмотра и игры, но деактивирует сохранение
прогресса. Не забывайте перезагружать игру после использования этой команды.


[tricks.dat]: ../../levels/
[solution-dir]: ../../solution/
