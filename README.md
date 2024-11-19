# Git

<p align="center">
  <img src="screenshots/01.png" alt=""/>
</p> Вказуємо ім'я та пошту для подальшої роботи <br> <br>

<p align="center">
  <img src="screenshots/02.png" alt=""/>
</p> Налаштовуємо main як гілку за замовчуванням <br> <br>

<p align="center">
  <img src="screenshots/03.png" alt=""/>
</p> Також налаштовуємо обробку кінців рядків (в нашому випадку для Windows) <br> <br>

<p align="center">
  <img src="screenshots/04.png" alt=""/>
</p> Створюємо каталог work та файл hello.html в ньому <br> <br>

<p align="center">
  <img src="screenshots/05.png" alt=""/>
</p> Вміст файлу hello.html - "Hello, World!" <br> <br>

<p align="center">
  <img src="screenshots/06.png" alt=""/>
</p> Тепер створюємо репозиторій Гіт із цього каталогу <br> <br>

<p align="center">
  <img src="screenshots/07.png" alt=""/>
</p> Додамо файл hello.html до нашого репозиторію <br> <br>

<p align="center">
  <img src="screenshots/08.png" alt=""/>
</p> Перевіримо поточний статус репозиторію <br> <br>

<p align="center">
  <img src="screenshots/09.png" alt=""/>
</p> Трохи змінимо файл hello.html - додамо html-тег "h1" <br> <br>

<p align="center">
  <img src="screenshots/10.png" alt=""/>
</p> Знову перевіримо статус репозиторію - як ми бачимо файл було змінено, але ці зміни ще не зафіксовано в репозиторії <br> <br>

<p align="center">
  <img src="screenshots/11.png" alt=""/>
</p> Тепер ще раз додамо файл hello.html до репозиторію та перевіримо статус <br> <br>

<p align="center">
  <img src="screenshots/12.png" alt=""/>
</p> За допомогою команди commit відкриємо редактор <br> <br>

<p align="center">
  <img src="screenshots/13.png" alt=""/>
</p> Після збереження файлу, виходу з редактора та ще одної перевірки статуса ми побачимо наступне: <br> <br>

<p align="center">
  <img src="screenshots/14.png" alt=""/>
</p> Додамо до файлу hello.html теги "html" та "body" <br> <br>

<p align="center">
  <img src="screenshots/15.png" alt=""/>
</p> Збережемо зміни в файлі командою add <br> <br>

<p align="center">
  <img src="screenshots/16.png" alt=""/>
</p> Додамо до файлу hello.html також тег "head" <br> <br>

<p align="center">
  <img src="screenshots/17.png" alt=""/>
</p> Перевіримо поточний статус <br> <br>

<p align="center">
  <img src="screenshots/18.png" alt=""/>
</p> Зафіксуємо зміни та перевіримо статус <br> <br>

<p align="center">
  <img src="screenshots/19.png" alt=""/>
</p> Додамо зміни до робочої області командою git add . та знову перевіримо статус <br> <br>

<p align="center">
  <img src="screenshots/20.png" alt=""/>
</p> Зафіксуємо останні зміни <br> <br>

<p align="center">
  <img src="screenshots/21.png" alt=""/>
</p> Отримуємо список внесених змін з командою git log --oneline (я обрав саме такий формат виводу історії, далі буде використовуватись саме він) <br> <br>

<p align="center">
  <img src="screenshots/22.png" alt=""/>
</p> Найбільш підходящий формат виводу змін на думку автора гайду <br> <br>

<p align="center">
  <img src="screenshots/23.png" alt=""/>
</p> Переглянемо хеш одного з чекаутів <br> <br>

<p align="center">
  <img src="screenshots/24.png" alt=""/>
</p> Повертаємось назад до основної гілки main та перевіряємо вміст файлу hello.html <br> <br>

<p align="center">
  <img src="screenshots/25.png" alt=""/>
</p> Додаємо тег "v1" до нинішньої версії сторінки <br> <br>

<p align="center">
  <img src="screenshots/26.png" alt=""/>
</p> Перевіримо версію v1 та файл hello.html - як бачимо, файл в цій версії містить html теги "html" та "body", але ще не містить "head" <br> <br>

<p align="center">
  <img src="screenshots/27.png" alt=""/>
</p> Позначимо цю версію тегом "v1-beta" <br> <br>

<p align="center">
  <img src="screenshots/28.png" alt=""/>
</p> Подивимось різницю між цими двома версіями за допомогою checkout <br> <br>

<p align="center">
  <img src="screenshots/29.png" alt=""/>
</p> Також можна подивитись доступні теги за допомогою команди tag <br> <br>

<p align="center">
  <img src="screenshots/30.png" alt=""/>
</p> І за допомогою команди log <br> <br>

<p align="center">
  <img src="screenshots/31.png" alt=""/>
</p> Перемикаємось назад на головну гілку main <br> <br>

<p align="center">
  <img src="screenshots/32.png" alt=""/>
</p> Додамо непотрібний коментар до нашого файлу hello.html <br> <br>

<p align="center">
  <img src="screenshots/33.png" alt=""/>
</p> Перевіримо статус директорії - файл було змінено, але ці зміни ще не зафіксовано <br> <br>

<p align="center">
  <img src="screenshots/34.png" alt=""/>
</p> Перевіримо версію файлу hello.html в самому репозиторії - немає ні змін в файлі, ні непотрібного коментаря <br> <br>

<p align="center">
  <img src="screenshots/35.png" alt=""/>
</p> Додамо ще раз непотрібний коментар до файлу hello.html <br> <br>

<p align="center">
  <img src="screenshots/36.png" alt=""/>
</p> Зафіксуємо зміни в файлі та переглянемо статус <br> <br>

<p align="center">
  <img src="screenshots/37.png" alt=""/>
</p> За допомогою команди reset HEAD очищаємо проміжну область від змін, які ми щойно внесли. <br> <br>

<p align="center">
  <img src="screenshots/38.png" alt=""/>
</p> Перевіряємо версію файлу hello.html і знову прибираємо непотрібні нам зміни в директорії <br> <br>

<p align="center">
  <img src="screenshots/39.png" alt=""/>
</p> І ще раз додамо непотрібний коментар до файлу hello.html <br> <br>

<p align="center">
  <img src="screenshots/40.png" alt=""/>
</p> Збережемо зміни в файлі командою add та додамо комміт з назвою "Oops, we didn't want this commit" <br> <br>

<p align="center">
  <img src="screenshots/41.png" alt=""/>
</p> Аби відмінити комміт, прописуємо команду revert HEAD і заходимо в редактор, де залишаємо все без змін <br> <br>

<p align="center">
  <img src="screenshots/42.png" alt=""/>
</p> Перевіряємо лог, який показує небажані скасування та фіксації в нашому репозиторії. <br> <br>

<p align="center">
  <img src="screenshots/43.png" alt=""/>
</p> Позначимо останній комміт тегом "oops", щоб ми могли знайти його після видалення комміту(ів) <br> <br>

<p align="center">
  <img src="screenshots/44.png" alt=""/>
</p> За допомогою параметру "--hard" змушуємо робочий каталог відображати нову "голову" гілки <br> <br>

<p align="center">
  <img src="screenshots/45.png" alt=""/>
</p> За допомогою команди "log --all" можна переглядати абсолютно всі комміти репозиторію, навіть ті, які були прибрані з головної гілки main <br> <br>

<p align="center">
  <img src="screenshots/46.png" alt=""/>
</p> Аби видалити помічені тегом комміти і сам тег, використовуємо "tag -d" <br> <br>

<p align="center">
  <img src="screenshots/47.png" alt=""/>
</p> Додамо авторський коментар до файлу hello.html <br> <br>

<p align="center">
  <img src="screenshots/48.png" alt=""/>
</p> Зафіксуємо зміни, додамо комміт "Added copyright statement" та перевіримо лог <br> <br>

<p align="center">
  <img src="screenshots/49.png" alt=""/>
</p> Також додамо до авторського коментаря в файлі hello.html пошту <br> <br>

<p align="center">
  <img src="screenshots/50.png" alt=""/>
</p> Знову зафіксуємо зміни та додамо комміт "Added copyright statement with email" <br> <br>

<p align="center">
  <img src="screenshots/51.png" alt=""/>
</p> Перевіримо лог - новий комміт «автор/електронна пошта» замінив оригінальний комміт «автор». <br> <br>

<p align="center">
  <img src="screenshots/52.png" alt=""/>
</p> Створимо нову гілку з назвою "style" та одразу перевіримо її статус <br> <br>

<p align="center">
  <img src="screenshots/53.png" alt=""/>
</p> Створимо простенький css файл під назвою style.css <br> <br>

<p align="center">
  <img src="screenshots/54.png" alt=""/>
</p> Зафіксуємо зміни та додамо комміт "Added css stylesheet" <br> <br>

<p align="center">
  <img src="screenshots/55.png" alt=""/>
</p> Підключимо css до файлу hello.html <br> <br>

<p align="center">
  <img src="screenshots/56.png" alt=""/>
</p> Знову зафіксуємо зміни та додамо комміт "Included stylesheet into hello.html" <br> <br>

<p align="center">
  <img src="screenshots/57.png" alt=""/>
</p> Перевіримо всі логи - тепер наш проект має дві гілки: main та style <br> <br>

<p align="center">
  <img src="screenshots/58.png" alt=""/>
</p> Повернемося назад до основної гілки і перевіримо вміст файлу hello.html - немає жодних слідів файлу style.css, бо ми не можемо побачити його з головної гілки <br> <br>

<p align="center">
  <img src="screenshots/59.png" alt=""/>
</p> Аби в цьому переконатись повернемось назад до гілки style та знову перевіримо вміст файлу hello.html - зміни, пов'язані з css-файлом, присутні <br> <br>

<p align="center">
  <img src="screenshots/60.png" alt=""/>
</p> Подивимось на лог змін файлів hello.html та style.css <br> <br>

<p align="center">
  <img src="screenshots/61.png" alt=""/>
</p> Розглянемо зміни у файлі hello.html у комміті з тегом "v1" <br> <br>

<p align="center">
  <img src="screenshots/62.png" alt=""/>
</p> Перейменуємо файл hello.html на index.html командою mv та перевіримо статус <br> <br>

<p align="center">
  <img src="screenshots/63.png" alt=""/>
</p> Зафіксуємо зміни в усій гілці та знову переглянемо статус <br> <br>

<p align="center">
  <img src="screenshots/64.png" alt=""/>
</p> Створимо окрему папку для файлу style.css, зафіксуємо його переміщення туди та перевіримо статус <br> <br>

<p align="center">
  <img src="screenshots/65.png" alt=""/>
</p> Додамо комміт "Renamed hello.html; moved style.css" та переглянемо обидві версії історії файлу css/style.css - звичайну і до його переміщення за допомогою параметру "--follow" <br> <br>

<p align="center">
  <img src="screenshots/66.png" alt=""/>
</p> Повернемось назад до головної гілки main, створимо файл README за допомогою команди touch та заповнимо його потрібним вмістом, зафіксуємо зміни та додамо комміт "Added README" <br> <br>

<p align="center">
  <img src="screenshots/67.png" alt=""/>
</p> Такий вигляд має файл README <br> <br>

<p align="center">
  <img src="screenshots/68.png" alt=""/>
</p> Переглянемо вміст всіх гілок командою "log --all --graph", де параметр "--all" гарантує, що ми бачимо всі гілки, а параметр "--graph" додає просте дерево комітів, представлене основними рядками тексту <br> <br>

<p align="center">
  <img src="screenshots/69.png" alt=""/>
</p> Повертаємось до гілки style, де об'єднаємо її з гілкою main командою "merge" та перевіримо графіки фіксації <br> <br>

<p align="center">
  <img src="screenshots/70.png" alt=""/>
</p> Повертаємось до головної гілки main та змінюємо файл hello.html - додаємо заголовок та абзац <br> <br>

<p align="center">
  <img src="screenshots/71.png" alt=""/>
</p> Фіксуємо зміни та додаємо комміт "Added meta title" <br> <br>

<p align="center">
  <img src="screenshots/72.png" alt=""/>
</p> Переглядаємо вміст всіх гілок <br> <br>

<p align="center">
  <img src="screenshots/73.png" alt=""/>
</p> Змінимо гілку на style,  об'єднаємо останні зміни в ній з гілкою main та перевіримо статус <br> <br>

<p align="center">
  <img src="screenshots/74.png" alt=""/>
</p> При відкритті файлу hello.html можимо бачити, що секція між кутовими дужками представляє конфлікт <br> <br>

<p align="center">
  <img src="screenshots/75.png" alt=""/>
</p> Аби це виправити, перервемо злиття та повернемося назад до стану до злиття за допомогою команди "merge --abort" <br> <br>

<p align="center">
  <img src="screenshots/76.png" alt=""/>
</p> Змінимо вигляд файлу hello.html до такого вигляду: <br> <br>

<p align="center">
  <img src="screenshots/77.png" alt=""/>
</p> Зафіксуємо зміни, додамо комміт "Resolved merge conflict", перевіримо статус та вміст всіх гілок <br> <br>

<p align="center">
  <img src="screenshots/78.png" alt=""/>
</p> Тепер знову попрацюємо з гілкою style - перевіримо її вміст та скинемо її до комміту "Renamed hello.html; moved style.css", який відбувся 2 коміти тому, для цього використовуємо команду "reset --hard HEAD~2" <br> <br>

<p align="center">
  <img src="screenshots/79.png" alt=""/>
</p> Знову перевіряємо вміст гілки style <br> <br>

<p align="center">
  <img src="screenshots/80.png" alt=""/>
</p> Тепер спробуємо замість об'єдання гілок перемістити зміни до гілки style - використовуємо команду "rebase" та перевіряємо статус <br> <br>

<p align="center">
  <img src="screenshots/81.png" alt=""/>
</p> Знову маємо конфлікт, але цього разу в файлі hello.html, оскільки цей файл ще не перейменовано в гілці main, тому він все ще має стару назву. <br> <br>

<p align="center">
  <img src="screenshots/82.png" alt=""/>
</p> Змінюємо файл hello.html до наступного вигляду: <br> <br>

<p align="center">
  <img src="screenshots/83.png" alt=""/>
</p> Фіксуємо зміни, залишаємо в редакторі все без змін, перевіряємо статус та вміст всіх гілок <br> <br>

<p align="center">
  <img src="screenshots/84.png" alt=""/>
</p> Повертаємось до гілки main та пробуємо об'єднати її з гілкою style <br> <br>

<p align="center">
  <img src="screenshots/85.png" alt=""/>
</p> Перевіряємо вміст всіх гілок - тепер гілки main та style ідентичні <br> <br>

<p align="center">
  <img src="screenshots/86.png" alt=""/>
</p> Виходимо до головної папки репозиторію repositories, де міститься папка work з усіма файлами <br> <br>

<p align="center">
  <img src="screenshots/87.png" alt=""/>
</p> Створюємо клон work, назвавши його home <br> <br>

<p align="center">
  <img src="screenshots/88.png" alt=""/>
</p> Подивимось вміст клонованого репозиторію - можна побачити файли README, index.html та css з оригінального репозиторію <br> <br>

<p align="center">
  <img src="screenshots/89.png" alt=""/>
</p> Переглянемо вміст історії клонованого репозиторію - все збігається з оригіналом <br> <br>

<p align="center">
  <img src="screenshots/90.png" alt=""/>
</p> Переглянемо інформацію про назву оригінального репозиторію командами "remote" та "remote show origin" <br> <br>

<p align="center">
  <img src="screenshots/91.png" alt=""/>
</p> Переглянемо які гілки є в клонованому репозиторії - бачимо тільки основну main, але оскільки команда "branch" за замовчуванням показує лише локальні гілки, то командою "branch -a" подивимось усі гілки <br> <br>

<p align="center">
  <img src="screenshots/92.png" alt=""/>
</p> Змінюємо файл README наступним чином: <br> <br>

<p align="center">
  <img src="screenshots/93.png" alt=""/>
</p> Повертаємось назад до оригінального репозиторію work, фіксуємо зміни файлу README та додаємо комміт "Changed README in original repo" <br> <br>

<p align="center">
  <img src="screenshots/94.png" alt=""/>
</p> Повернемось до клонованого репозиторію home, де пропишемо команду "fetch", яка отримуватиме нові комміти з віддаленого репозиторію, але не об’єднуватиме їх у локальні гілки, також преевіримо вміст всіх гілок  <br> <br>

<p align="center">
  <img src="screenshots/95.png" alt=""/>
</p> Перевіримо вміст файлу README - нічого не змінилось <br> <br>

<p align="center">
  <img src="screenshots/96.png" alt=""/>
</p> Об'єднаємо отримані зміни в локальну гілку main <br> <br>

<p align="center">
  <img src="screenshots/97.png" alt=""/>
</p> Знову перевіримо вміст файлу README - тепер бачимо зміни <br> <br>

<p align="center">
  <img src="screenshots/98.png" alt=""/>
</p> Команда "pull" виконує ті ж самі функції, що й попередні дві команди: "fetch" та "merge" <br> <br>

<p align="center">
  <img src="screenshots/99.png" alt=""/>
</p> Додаємо до цього репозиторію гілку style з оригінального командою "branch --track style origin/style" та переглядаємо всі гілки - style тепер присутня <br> <br>

<p align="center">
  <img src="screenshots/100.png" alt=""/>
</p> Знову виходимо до головної папки репозиторію repositories і створимо "голе" сховище - те, що немає робочого каталогу за допомогою команди "clone --bare work work.git" і переглянемо його вміст <br> <br>

<p align="center">
  <img src="screenshots/101.png" alt=""/>
</p> Додамо репозиторій work.git до нашого оригінального репозиторію work <br> <br>

<p align="center">
  <img src="screenshots/102.png" alt=""/>
</p> Змінимо файл README наступним чином: <br> <br>

<p align="center">
  <img src="screenshots/103.png" alt=""/>
</p> Повертаємось до основної гілки main, фіксуємо зміни файлу README, додаємо комміт "Added shared comment to readme" та відправляємо ці зміни до спільного репозиторію work.git <br> <br>

<p align="center">
  <img src="screenshots/104.png" alt=""/>
</p> Повертаємось до клонованого репозиторію home, де отримуємо зміни зі спільного середовища work.git командами "remote add shared ../work.git", "branch --track shared main" та "pull shared main", після чого переглядаємо вміст файлу README <br> <br>

<p align="center">
  <img src="screenshots/105.png" alt=""/>
</p> Для того, аби розмістити Git-репозиторій на GitHub, можна використовувати команду "git daemon --verbose --export-all --base-path=." і посилання на папку з репозиторіями. Після цього перейти в інший термінал в ту саму папку і виконати команди "clone git://localhost/work.git network_work", "cd network_work" та "ls", після чого можна буде побачити копію проєкту <br> 

