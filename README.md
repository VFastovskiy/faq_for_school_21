FAQ Школы 21 для новичков и не очень
------------------------------------

Эта статья предназначена для тех, кто находится в школе 21 недавно, и еще не успел наступить на дорожку из граблей.
Так же это будет являться памяткой для студентов-олдфагов, которые что-либо упустили или забыли, но не хотят волновать
токсичный slack вопросами, которые кажутся дурацкими настоящим просветленным гуру.

По вопросам, несостыковкам и ошибкам пишите в slack. Мой ник - swarner.
На все остальное есть ADM.

Содержание
----------

**Вопросы, не связанные с технической стороной**

- [Удаленная сдача проектов в период карантина](#distance)
- [Вопросы о ТИЖах](#tig)
- [Как привести гостя в школу](#guest)
- [Что делать, если заболел](#desease)
- [Что делать, если что-то разлил/испачкал](#water)
- [Что делать, если сломался/не работает Mac](#brokenmac)
- [Забыл разлогиниться и теперь при попытке зайти в учетку выскакивает какая-то ошибка](#relogin_error)
- [Обязательные педагогические встречи](#pedmiteengs)
- [Получение справки от школы](#contract)
- [Пришло сообщение о blackhole](#blackhole)
- [Где получить вещи, купленные за wallets](#wallets)
- [Вопросы по норме кода](#norm)
- [Вопросы об экзамене (C Exam Alone In The Dark - Beginner)](#exam)
- [Как получить лицензию JetBrains (Clion, PyCharm и т.д.)](#get_jetbrains)
- [Пора делать резюме. С чего начать?](#cv)
- [Сайты со счетчиком уровней за проекты](#top_21)
- [Полезные каналы в slack](#slack)

**Вопросы, связанные с технической стороной**
- [Установка Oh-My-Zsh](#zsh)
- [Установка HomeBrew на Mac](#brew)
- [Установка valgrind для поиска утечек](#valgrind)
- [Проверка на утечки в графическом проекте (FDF, Fract'ol и другие)](#gui_leaks)
- [Кончилось место на маке. Как почистить кэш?](#cache)
- [Почему moulinette в fillit поставила -42 за функцию из libft](#error_fillit)
- [Настройка дебаггера в vscode](#vscode)
- [Настройка clion](#clion)
- [Скрипт для цветного norminette](#color_norm)
- [Сборник чекеров на проекты](#checkers)








Вопросы, не связанные с технической стороной
-------------------------------------------------

<a name="distance">Удаленная сдача проектов в период карантина</a>
----------

* Официальные правила сдачи и проверки проектов - [ТУТ](https://21-school.ru/onlineeducation)
* Официальная информация, мануалы по настройке Windows, MacOS и Ubuntu, полезные бонусы для студентов школы и правила школы от ADM - [ТУТ](https://21-school.ru/adm)

<a name="tig">Вопросы о ТИЖах</a>
----------

#### Получил ТИЖ, что делать?
1. Записаться в интре на удобный вам день, кроме субботы и воскресенья.
2. Подойти в назначенный день в ADM в 11:00 и получить задание.
3. Отрабатывать ТИЖ.

#### Мне дали 2/4/8 часовой ТИЖ. Как это?
Администрация раздает ТИЖи в зависимости от тяжести проступков. В итоге вы можете отрабатывать 8 часовой ТИЖ, каждый день приходя в 11:00, выполняя задание по 2 часа в течение 4 дней.

#### Я записался на отработку ТИЖа, но не пришел. Что теперь?
За неявку на отработку администрация автоматически даст вам второй двухчасовой ТИЖ. Остается лишь корить себя за нерасторопность и идти отрабатывать.

#### Я записался на отработку, но теперь хочу перенести на другой день. Как быть?
Нужно писать в канал ADM в slack и просить перенести отработку.


<a name="guest">Как привести гостя в школу</a>
----------------
Переходим по ссылке — [ТУТ](https://docs.google.com/forms/d/e/1FAIpQLSfYMfRIse_kM8r4HjnLKA0ZNG8-XFU1TJvjxQeMFVzQK5yGeg/viewform) и записываем гостя.  
Помните основные правила — гость приходит максимум на час, везде ходит с сопровождающим и носит бейджик.  
Записывать гостя необходимо за день до его прибытия.  
В выходные привести гостя нет возможности, потому что ADM присутствует в школе только по будням.

<a name="desease">Что делать, если заболел</a>
----------------
При болезни лучше сидите дома, чтобы не заражать других студентов. Справки администрации приносить не нужно.  
Однако если вы не успеваете в дедлайны и заболели, пишем в ADM и просим отсрочку дедлайнов по болезни, после приносим им все справки. Естественно, болезнь у вас должна быть серьезнее, чем насморк.

<a name="water">Что делать, если что-то разлил/испачкал</a>
----------------
Пишем в канал в slack #help о случившемся, или подходим к уборщицам и просим убрать беспорядок.

<a name="brokenmac">Что делать, если сломался/не работает mac</a>
----------------
Пишем в канал в slack #boсal о случившемся и пересаживаемся за другой компьютер

<a name="relogin_error">Забыл разлогиниться и теперь при попытке зайти в учетку выскакивает какая-то ошибка</a>
----------------
Все очень просто. Нужно нажать кнопку "Terminate sessions" и все. Однако вероятно при этом у вас сбросятся настройки учетки и придется выставлять их заново, поэтому лучше всего не забывать разлогиниться.  
Иногда после всего этого интра начинает насчитывать вам время бесконечно и неправильно указывает за каким компьютером вы сидите. Решение также тривиально - пишем в #boсal и ждем пока исправят. 

<a name="pedmiteengs">Обязательные педагогические встречи</a>
----------------
#### Что делать, если я не могу прийти (работаю/не успеваю)?
К сожалению, приходить нужно обязательно. При неявке на встречу выдается ТИЖ.

#### У меня уважительная причина для неявки. Кому писать?
Пишем вашу причину в #adm и ждем ответа.

#### Как проверяют присутствие на встрече?
На входе стоит Face ID, который определяет по лицу кто зашел в школу и во сколько.

#### В атриум не влезут ≈999999 человек! Как мы там все уместимся?
В атриуме сидеть не обязательно. Достаточно быть в школе и смотреть трансляцию.

<a name="contract">Получение справки от школы</a>
----------------
Вам нужна справка от школы для армии/вуза/посольства. Нашей справкой об обучении является контракт со школой. При необходимости сканируем и показываем копию договора.

<a name="blackhole">Пришло сообщение о blackhole</a>
----------------
Вы заходите в интру, а вам высвечивается ошибка "blackhole". Это означает, что вы провалили французский дедлайн, где нужно получить 7 уровней за полгода. Но наша школа живет по своим дедлайнам, так что волноваться не о чем. Просто нажимаем "продолжить игру". Но если вы не можете после зайти в интру и/или нажали "покинуть игру", то пишем в #bocal и просим разблокировать учетку.

<a name="wallets">Где получить вещи, купленные за wallets</a>
----------------
Приходим в ADM в рабочее время и просим выдать вашу покупку.

<a name="norm">Вопросы по норме кода</a>
----------------
#### Где найти актуальные правила нормы?
По ссылке - [ТУТ](https://cdn.intra.42.fr/pdf/pdf/1065/norme.en.pdf).
Перевод правил нормы на русский вы можете найти - [ТУТ](https://github.com/burninggoose/42-norme-ru). Перевод оставляет желать лучшего, и вообще — учите английский, он программисту необходим.

#### Можно ли использовать макросы?
Нельзя. Norminette и пиры не пропустят такие вещи как:
>#define SUM(x, y) (x + y)  

К тому же в подобных вещах абсолютно нет нужды. Просто создайте отдельную функцию.

#### Можно ли использовать глобальные или статик переменные?
Статические переменные используются без ограничений, глобальные с учётом обоснования (см. разд. II.1 Правил). Обратите внимание, что в некоторых проектах использование глобальных переменных прямо запрещено.  
Необоснованное использование глобальной переменной: счётчики, переменная использованная в одной функции. Обоснованное использование: ссылка на структуру хранения, например, символьный буфер.

#### Можно ли использовать константы и структуры из библиотек limits.h или bool.h?
Можно. Если сомневаетесь, просто скопируйте исходный код себе в проект.

#### Как правильно оформить комментарий?
В теле функции комментарии не допускаются. Комментарии в стиле С99 - //, запрещены. (см. разд. II.11 Правил).
Правильно оформленный комментарий выглядит так:  
>  /*  
>  ** Текст комментария.  
>  */

<a name="exam">Вопросы об экзамене (C Exam Alone In The Dark - Beginner)</a>
----------------
#### Во сколько и когда бывают экзамены?
По четвергам в 12:00. Если к ближайшей субботе наберутся волонтеры, которые готовы присматривать за экзаменующимися, то будет и в эту субботу в 12:00.

#### Как правильно залогинится на экзамене?
* Приходим и логинимся с помощью учетки экзамена - exam:exam.
* Далее заходим в терминал и пишем kinit [ваш логин] и вводим ваш пароль.
* Ждем команды от экзаменаторов о начале экзамена и после в терминале пишем examshell.
* Экзамен начался!

#### Нужно ли приводить к норме на экзамене?
Нет. На экзамене это не нужно.

#### Я все сделал верно, протестил, а moulinette выдала 0!!!
Значит что-то неверно. Внимательно читайте трассировку от moulinette (её пониманию очень поможет знание команды diff). Так же вероятно вы забыли скомпилировать с флагами -Wall -Werror -Wextra и не увидели скрытой ошибки. Впрочем, moulinette — программный комплекс, и в нём тоже могут быть ошибки. Если считаете, что это именно ваш случай — можете попробовать оспорить в ADM.

#### На экзамене я сделал все до 3 уровня. С какого уровня я смогу начать в следующий раз?
На самом деле если вы сделали 00-03 уровни включительно, потом ушли то по приходу вы можете начать с любого уровня до которого дошли и баллов будет предложено максимум, а не сколько вы набрали. То есть если вы сделали 00-03 уровни допустим, на 16-11-16-16 баллов, потом ушли на следующий раз вы можете начать с 00-04 уровня, и за 04 вам сразу будет предложено на 80(16-16-16-16-16).  
Плюс есть исключение с 5 уровнем, если вы сделали 04 без ошибки и ушли, то в следующий раз вы можете начать с 05 уже за 100 баллов, но если вы сделали 04 с ошибкой, то вы не сможете начать с 05 в следующий раз, если ушли, а снова с 04 за 80 баллов

<a name="get_jetbrains">Как получить лицензию JetBrains (Clion, PyCharm и т.д.)</a>
----------------
1. Зайти на сайт [JetBrains](https://account.jetbrains.com/login) и создать аккаунт.
2. Далее перейти по ссылке [Apply for a free student or teacher license for educational purposes](https://www.jetbrains.com/student?_ga=2.139493115.9198993.1580488158-1606284117.1580488158)
3. Нажать "Apply now".
4. Ввести правильно все свои данные в форме. Email нужно указывать ваш школьный - [ваш ник]@student.21-school.ru.
5. Ждать подтверждения на почте.

<a name="cv">Пора делать резюме. С чего начать?</a>
----------------
* Прочитайте [рекомендации по написанию к резюме](docs/Rekomendatsii_po_napisaniyu_rezyume_Scheglova_L.docx)
* Заходите на сайт [canva.com](https://www.canva.com/) и начинайте создавать резюме :)

<a name="top_21">Сайты со счетчиком уровней за проекты</a>
----------------
* [top-school-21.ru](https://top-school-21.ru/)  
* [https://isthisjazz.website/xpcalc.php](https://isthisjazz.website/xpcalc.php)

<a name="slack">Полезные каналы в slack</a>
----------------
* #21hackers - канал с хакатонами.
* #21lectures - студенты пишут, кого хотят позвать в школу в качестве лектора.
* #club-raspberry - канал кружка робототехники.
* #help - канал для помощи в уборке.
* #talks - обсуждение насущных вопросов школы с директором.
* #datascience - канал дата саентистов.
* #born_to_code - канал по вопросам о проектах и коде.
* #school_life - обзор мероприятий и каналов.
* #java - в основном Java SE.

Вопросы, связанные с технической стороной
-------------------------------------------------

<a name="zsh">Установка Oh-My-Zsh</a>
----------------
Пишем в терминал и запускаем:  
>sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

<a name="brew">Установка HomeBrew на Mac</a>
----------------
Пишем в терминал и запускаем:  
>curl -fsSL https://rawgit.com/kube/42homebrew/master/install.sh | zsh

<a name="valgrind">Установка valgrind для поиска утечек</a>
----------------
Пишем в терминал и запускаем:  
* Если нет HomeBrew:
>curl -fsSL https://rawgit.com/kube/42homebrew/master/install.sh | zsh  
>brew install valgrind

* Если HomeBrew есть:
>brew install valgrind  

Использование:
>valgrind ./[ваш бинарник] [аргументы] --leak-check=full

<a name="gui_leaks">Проверка на утечки в графическом проекте (FDF, Fract'ol и другие)</a>
---------------
Проверить на утечки в проектах графики можно двумя способами.  
Первый:  
1. Запускаем вашу программу
2. В другом терминале пишем:
>leaks [имя вашего бинарника]

Второй:
1. Запускаем Xcode
2. Вверху нажимаем на вкладку Xcode
3. Ищем "Open Developer Tool" и нажимаем на "Instruments"
4. Выбираем "Leaks"
5. Нажимаем на кнопку с красным кругом и выбираем свой бинарник.
6. Если нужны аргументы - пишем их в поле "Arguments".

<a name="cache">Кончилось место на маке. Как почистить кэш?</a>
---------------
* Пишем в терминал и запускаем:   
>curl -fsSL https://raw.githubusercontent.com/daniiomir/faq_for_school_21/master/docs/clear.sh | sh  
* Появляется сообщение:  
>Clean cache? (y/n): 
* Пишем - y.
* Кэш очищен.

Или:
>rm -rfv ~/Library/\*42_cache*

<a name="error_fillit">Почему moulinette в fillit поставила -42 за функцию из libft</a>
---------------
Это происходит, потому что moulinett в проекте fillit неправильно обрабатывает хедеры, которые построены подобным образом:
>#include "../libft/libft.h"  

Необходимо исправить все хедеры в проекте на:
>#include "libft.h"

А также скопировать сам файл libft.h в папку includes в корне проекта.  
И исправить Makefile в том месте, где подключаются хедеры, на:
>-I includes/

На всех остальных проектах нет разницы как подключать хедеры. Данная проблема была замечена только в fillit.

<a name="vscode">Настройка дебаггера в VSCode</a>
---------------
* Установите в VSCode расширение [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)
* Не забудьте почитать Users Manual, там много интересного.

Или:

* Берем и копируем конфигурацию из [этого файла](docs/launch.json)  
* Вставляем все вместо вашего файла launch.json, который лежит в .vscode  
* После у вас появится вверху кнопка "(lldb) Запустить"  
* Теперь вы можете дебажить ваш код :)  

Вы можете поменять переменную ${workspaceFolderBasename} на имя вашего бинарника, если ваш бинарник называется не также как и папка.  
Чтобы запускать программу с аргументами нужно в строчке - "args": [], в скобки вставить ваши аргументы.

<a name="clion">Настройка Clion</a>
---------------
Для корректной работы clion нужен аналог Makefile - CMakeList.txt. К счастью, clion умеет генерировать его автоматически.  
1. Нужно открыть clion и нажать - New CMake Project from sources. 
2. Откроется окно, где нужно будет выбрать папку проекта.
3. Нажимаем окей в следующем окне, где clion предлагает выбрать файлы проекта.
4. Clion готов к работе.

Если вам нужно запустить программу с аргументами:
1. Нажимаем вверху на вкладку Run.
2. Ищем Edit configurations и нажимаем.
3. В поле Program arguments вписываем аргументы.

<a name="color_norm">Скрипт для цветного norminette</a>
---------------
Ссылка на репозиторий, а так же скриншоты - [ТУТ](https://github.com/liftchampion/colorised_Norminette)  
Как установить:
>sh -c "$(curl -s https://bitbucket.org/liftchampion/colorised-norminette/raw/b4272f2c2dac52b1da721ae658815c43f64e5cb2/colorised_norm_install_installer.sh)"

<a name="checkers">Сборник чекеров на проекты</a>
---------------
Чекер для 6 начальных проектов - 
[42FileChecker](https://github.com/jgigault/42FileChecker)  

#### Libft
[libft-unit-test](https://github.com/alelievr/libft-unit-test)  

#### Fillit
[fillit_checker](https://github.com/Millon15/fillit_checker)  

#### Ft_printf
[pft](https://github.com/gavinfielder/pft)  
[printf-unit-test - 3,4 миллиона тестов](https://github.com/alelievr/printf-unit-test)  
[curqui_test](https://github.com/curquiza/curqui_test)  

#### Push_swap
[push_swap cheker](https://github.com/ksnow-be/push_swap_checker) (супер крутой чекер, сделанный студентом школы 21)  

#### Lem-in
[Lem-in-Checker](https://github.com/emilwallner/Lem-in-Checker)  
[lem-in_test](https://github.com/TBouder/lem-in_test)  

#### Filler
[filler_checker](https://github.com/Millon15/filler_checker)  

#### Corewar
[42-Corewar-Checker](https://github.com/Gliperal/42-Corewar-Checker)  
[unit-tests](https://github.com/rizkyario/corewar/tree/unit-tests)  
