Этот репозиторий будет склонирован для каждого студента и доступен по адресу
`https://www.kgeorgiy.info/git-students/year2019/<USER>/java-advanced`.
Имя пользователя и пароль будут высланы на почту `номер@niuitmo.ru`.

Для сдачи домашних заданий
 * Клонируйте ваш личный репозиторий
    * `git clone https://www.kgeorgiy.info/git-students/year2019/<USER>/java-advanced`
    * У личных репозиториев __нет__ web-интерфейса, используйте инструменты командной строки.
 * Добавьте ссылку на исходный репозиторий
    * `git remote add source https://www.kgeorgiy.info/git/geo/java-advanced-2021-solutions`
    * По мере появления новых домашних заданий в исходном репозитории будут появляться заготовки решений
      забирайте из через `git pull source master`.
 * Переименуйте пакет `info.kgeorgiy.ja.antonov`, заменив
   `__last_name__` на вашу фамилию.
    * В остальном сохраняйте текущую структуру каталогов и имена файлов.
    * Если структура репозитория не соответсвует исходной, преподаватель не будет проверять решение.
 * Добавляйте только исходные файлы решений
 * Вы можете редактировать `.gitignore` как вам удобно
 * Отправьте решение на проверку
    * Проверьте, что все исходники компилируеются (в том числе, тех ДЗ, которые вы не сдаёте)
    * Проверьте, что тесты сдаваемого ДЗ проходят
    * Закоммитьте все изменения в `master`
    * Запушите все изменения
    * Запросите проверку решения, заполнив форму
 * После проверки преподаватель либо укажет найденные недостатки в `NOTES.md`,
   либо укажет их в виде комментариев в исходном коде, пометив их как `:NOTE:`