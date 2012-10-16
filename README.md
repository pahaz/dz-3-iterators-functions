# Циклы и функции

Необходимо создать коллекцию событий и функции выборки и сортировки из этой коллекции.

  * Создать коллекцию событий из нескольких (20+) случайных элементов "Событие"
    * Текстовые поля случайны
    * Поля типа дата разбросаны в интервале -месяц +месяц от текущей
    * GPS координаты и прочие числовые и перечисляемые поля произвольны
  * Создать несколько функций воброки и сортировки элементов из коллекции, которые можно "смешивать" между собой
    * Выбрать прошедшие события
    * Выбрать события с моим участием (если у вас есть такое поле)
    * Выбрать предстоящие события
    * Выбрать события события, которые произойдут через столько-то времени
    * Функция сортировки элементов коллекции по времнеи убывание/возрастания
    * Функция сортировки по рейтингу события (если у вас есть такое поле)
    * ...
  * Фактически вам необходимо создать функции сортировки и выборки по всем перечисляемым и числовым полям
  * В итоге вы должы уметь получать такие комбинации
  "Выбрать все предстоящие события с моим участием отсортированные по рейтигу"
  или "Выбрать все события, которые произойдут на этой неделе, отсортированые по рейтингу"
  или "Выбрать ближайшее (по времени) событие без моего участия"
  и другие связанные с вашими полями
  * Старайтесь не делать копипаст функций, подмайте как их можно агрегировать (Factory pattern?)
  * Необходимо выводить результаты выборки в консоль браузера `console.log()`
  [Как открыть консоль](http://webmasters.stackexchange.com/questions/8525/how-to-open-the-javascript-console-in-different-browsers)
