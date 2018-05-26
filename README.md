
C# ASP.NET web developer
 
Вопросы:
 
1. Нужно загрузить на сайт через браузер файл размером 10ГБ. Как бы Вы это реализовали?
 
2. Нужно скачать с сайта файл размером 10ГБ. Доступ только для авторизованных клиентов. Клиент может использовать download manager с многопоточной закачкой. Как бы Вы реализовали контроль что файл скачан клиентом целиком?
 
3. На сайте требуется авторизация пользователей, имеется всего несколько страниц, доступных без авторизации. Как бы Вы раскручивали такой сайт чтобы поднять его в результатах поиска Google?
 
4. При оплате сервиса для клиентов из США требуется вычислить сумму налога в зависимости от billing address. Как Вы это будете реализовывать? Опыт, идеи?
 
5. Нужно сгенерить preview видео для отображаения в браузере. Какой минимальный список форматов файлов необходим? Чем и как конвертировать из mp4?
 
6. Как бы Вы имплементировали логирование? Средствами .NET, собственный код с записью в файлы, сторонние библиотеки с записью в БД?
 
7. На главной странице сайта (до авторизации) есть выбор языка. Что предпочтительнее - ComboBox или всплывающее меню со ссылками? Почему?
 
8. Приходилось ли использовать SQL процедуры? Если да, то для чего?

9. How would you make sure related data is consistent between multiple tables?

10. What is a covered query?

11. How would you make sure the consistency and accuracy in case some metadata is in a database and some in regular files. Consider a simple case when a file format and path to a file are stored in a database, and the file itself is in a file system. How would you make sure there is no orphans either in the database nor in the file system?
 
12. Сервер должен запустить консольную утилиту, получить и распарсить вывод в stdout и stderr. Как это сделать? Что делать если утилита крэшнулась? Что делать если крэшнулся сервер, а утилита ещё работает?
 
13. Чему равен result?
object s1 = "abc";
string s2 = "abc";
bool result = s1.Equals(s2);
 
14.
public enum Enum1
{
  Black,
  Red,
  Green,
  Blue,
  Yellow,
  White,
}
 
[Flags]
public enum Enum2
{
  Black = 1,
  Red = 2,
  Green = 4,
  Blue = 8,
  Yellow = 16,
  White = 32,
}
 
Enum2 mux(Enum1 [] e)
{
  // Имплементируйте функцию
}
 
15. Есть текстовый файл в кодировке utf-8. Нужно открыть его как бинарный стрим, прочитать и заполнить массив строк. Приведите решение.
