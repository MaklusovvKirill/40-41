# 40-41


ПАРАГРАФ 40

Зачем нужны операционные системы? Можно ли обойтись без них? Операционные системы (ОС) необходимы для управления аппаратными ресурсами компьютера и обеспечения взаимодействия между пользователем и устройствами. Они предоставляют интерфейс для запуска приложений и управления файлами. Без ОС работать с компьютером было бы крайне сложно, так как не было бы стандартного способа взаимодействия с аппаратурой.

Что такое операционная система? Операционная система — это набор программного обеспечения, который управляет аппаратными ресурсами компьютера и предоставляет услуги для выполнения программ. Она обеспечивает интерфейс между пользователем и аппаратным обеспечением.

Какие задачи выполняет ОС? Основные задачи ОС включают управление процессами, управление памятью, управление файловой системой, управление устройствами ввода-вывода, обеспечение безопасности и управление пользователями.

Чем отличаются многозадачные ОС от однозадачных? Многозадачные ОС могут выполнять несколько задач одновременно, переключаясь между ними, в то время как однозадачные ОС могут выполнять только одну задачу в любой момент времени.

Как обеспечивается многозадачность на компьютерах с одним процессором? Многозадачность на компьютерах с одним процессором достигается с помощью технологии переключения контекста, при которой процессор быстро переключается между задачами, создавая иллюзию одновременного выполнения.

Что такое пакетный режим работы? Пакетный режим работы — это способ обработки данных, при котором задачи собираются в пакеты и обрабатываются группами, а не по одной.

Что такое многопользовательский режим? Многопользовательский режим позволяет нескольким пользователям одновременно работать с одной и той же системой, обеспечивая каждому из них отдельную среду и доступ к ресурсам.

Перечислите составные части ОС. Основные составные части ОС включают ядро, системные библиотеки, системные утилиты и пользовательский интерфейс.

Что такое начальный загрузчик? Начальный загрузчик — это программа, которая загружает операционную систему в память при включении компьютера.

Что такое драйвер? Драйвер — это специальная программа, которая позволяет операционной системе взаимодействовать с аппаратным устройством.

Какие программы относятся к утилитам? Утилиты — это программы, которые выполняют вспомогательные функции, такие как управление файлами, резервное копирование, антивирусная защита и т.д.

Какими достоинствами и недостатками обладает система Linux? Достоинства: открытый исходный код, высокая безопасность, стабильность, большое сообщество. Недостатки: сложность для новичков, несовместимость с некоторыми программами и играми.

Как ОС обменивается данными с внешними устройствами? В чём достоинства такой схемы? ОС использует драйверы для обмена данными с внешними устройствами. Достоинства включают абстракцию аппаратного обеспечения и возможность использования стандартных интерфейсов.

Что происходит, когда ОС обнаруживает новое устройство? ОС идентифицирует устройство, загружает соответствующий драйвер и настраивает его для работы.

Что такое файловая система? Зачем она нужна? Файловая система — это способ организации и хранения данных на носителе. Она необходима для управления файлами и каталогами, а также для обеспечения доступа к данным.

Какие задачи решает файловая система? Файловая система решает задачи хранения, организации, поиска, доступа и защиты данных.

Что такое кластер? Кластер — это минимальная единица хранения данных в файловой системе, которая может содержать один или несколько файлов.

Почему невыгодно хранить мелкие файлы в файловой системе с большим размером кластера? При большом размере кластера может возникнуть неэффективное использование пространства, так как мелкие файлы занимают целый кластер, что приводит к потере места.

Что улучшается при увеличении размера кластера? Увеличение размера кластера может улучшить производительность при работе с большими файлами, так как уменьшает количество операций ввода-вывода.

Какие файловые системы используются в ОС Linux, Windows и Mac OS? В Linux часто используются ext4, XFS, Btrfs; в Windows — NTFS, FAT32; в Mac OS — APFS, HFS+.

Почему файловая система FAT32 считается устаревшей? FAT32 имеет ограничения по размеру файлов (до 4 ГБ) и не поддерживает современные функции безопасности и управления правами.

Что такое одноуровневая и многоуровневая файловые системы? Одноуровневая файловая система имеет простую структуру, где все файлы находятся в одном каталоге. Многоуровневая файловая система организует файлы в иерархическую структуру каталогов.

Что такое корневой каталог? Корневой каталог — это верхний уровень иерархии файловой системы, от которого начинаются все другие каталоги и файлы.

В чём различие файловых систем в ОС Linux и Windows? Файловые системы в Linux (например, ext4) поддерживают более сложные функции, такие как права доступа и символические ссылки, в то время как Windows (например, NTFS) имеет свои особенности, такие как поддержка больших файлов и шифрования.

Где расположены каталоги пользователей в ОС Linux? В Linux каталоги пользователей обычно расположены в каталоге /home, где каждый пользователь имеет свой подкаталог.

Какие символы используются как разделители при записи адреса файла в ОС Linux и Windows? В Linux используется символ /, а в Windows — символ \.

Что такое сетевая файловая система? Сетевая файловая система — это файловая система, которая позволяет пользователям и приложениям получать доступ к файлам по сети, как если бы они находились на локальном диске.





ПАРАГРАФ 41



Что такое машинный код? Машинный код — это низкоуровневый код, который состоит из двоичных инструкций, понятных процессору. Он непосредственно управляет аппаратными ресурсами и выполняется без промежуточной обработки.

Зачем нужны системы программирования? Можно ли обходиться без них? Системы программирования необходимы для упрощения процесса разработки программного обеспечения, предоставляя инструменты для написания, тестирования и отладки кода. Без них разработка была бы сложной и трудоемкой, так как программистам пришлось бы работать напрямую с машинным кодом.

Что такое язык ассемблера? Почему он называется машинно-ориентированным? Язык ассемблера — это низкоуровневый язык программирования, который использует мнемоники для представления машинных инструкций. Он называется машинно-ориентированным, потому что его команды соответствуют конкретной архитектуре процессора и напрямую взаимодействуют с аппаратным обеспечением.

Что такое язык программирования высокого уровня? Язык программирования высокого уровня — это язык, который абстрагирует детали аппаратного обеспечения и предоставляет более удобный и понятный синтаксис для разработки программ. Примеры включают Python, Java и C++.

Как можно разделить языки программирования по области применения? Языки программирования можно разделить на:

Общего назначения (например, C, Python)
Специального назначения (например, SQL для работы с базами данных, HTML для разметки веб-страниц)
Системные языки (например, C для разработки операционных систем)
Языки для встраиваемых систем (например, C для микроконтроллеров)
Зачем нужен транслятор? Транслятор необходим для преобразования кода, написанного на языке программирования, в машинный код или другой промежуточный формат, который может быть выполнен компьютером.

Какие два типа трансляторов вы знаете? В чём их достоинства и недостатки?

Компиляторы: преобразуют весь исходный код в машинный код перед выполнением. Достоинства: высокая производительность, оптимизация кода. Недостатки: длительное время компиляции.
Интерпретаторы: выполняют код построчно, переводя его в машинный код во время выполнения. Достоинства: простота отладки, возможность интерактивного выполнения. Недостатки: меньшая производительность по сравнению с компиляторами.
Какие программы входят в системы программирования? В системы программирования входят компиляторы, интерпретаторы, отладчики, профилировщики, текстовые редакторы, компоновщики и другие инструменты для разработки.

Зачем нужен компоновщик? Компоновщик (линкер) необходим для объединения объектных файлов, созданных компилятором, в единый исполняемый файл, а также для разрешения ссылок на внешние библиотеки и функции.

Что такое отладчик? Перечислите возможности отладчиков. Отладчик — это инструмент, который помогает разработчикам находить и исправлять ошибки в коде. Возможности отладчиков включают:

Установка точек останова
Пошаговое выполнение кода
Просмотр значений переменных
Анализ стека вызовов
Изменение значений переменных во время выполнения
Что такое профилировщик? Зачем он нужен? Профилировщик — это инструмент, который анализирует производительность программы, собирая данные о времени выполнения функций и использовании ресурсов. Он нужен для оптимизации кода и выявления узких мест в производительности.

Что такое интегрированная среда разработки? Интегрированная среда разработки (IDE) — это программное обеспечение, которое объединяет все необходимые инструменты для разработки программного обеспечения в одном интерфейсе. Она обычно включает редактор кода, компилятор, отладчик и другие инструменты, что упрощает процесс разработки.

