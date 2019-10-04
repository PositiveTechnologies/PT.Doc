|ID|ENG|RUS|
|:--|:--|:--|
|CWE-1|DEPRECATED: Location|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с разработкой и внедрением|
|CWE-2|Environment|Уязвимости, связанные со средой|
|CWE-3|DEPRECATED: Technology-specific Environment Issues|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные со средой конкретной технологии|
|CWE-4|J2EE Environment Issues|Уязвимости, связанные со средой J2EE|
|CWE-5|J2EE Misconfiguration: Data Transmission Without Encryption|Ошибка в конфигурации J2EE: передача данных без шифрования|
|CWE-6|J2EE Misconfiguration: Insufficient Session-ID Length|Ошибка в конфигурации J2EE: недостаточная длина идентификатора сессии|
|CWE-7|J2EE Misconfiguration: Missing Custom Error Page|Ошибка в конфигурации J2EE: отсутствует настроенная страница ошибки|
|CWE-8|J2EE Misconfiguration: Entity Bean Declared Remote|Ошибка в конфигурации J2EE: удаленное объявление компонентов сущности|
|CWE-9|J2EE Misconfiguration: Weak Access Permissions for EJB Methods|Ошибка в конфигурации J2EE: избыточные разрешения для методов EJB|
|CWE-10|DEPRECATED: ASP.NET Environment Issues|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные со средой ASP.NET|
|CWE-11|ASP.NET Misconfiguration: Creating Debug Binary|Ошибка в конфигурации ASP.NET: создание двоичных файлов отладки|
|CWE-12|ASP.NET Misconfiguration: Missing Custom Error Page|Ошибка в конфигурации ASP.NET: отсутствует настроенная страница ошибки|
|CWE-13|ASP.NET Misconfiguration: Password in Configuration File|Ошибка в конфигурации ASP.NET: пароль в файле конфигурации|
|CWE-14|Compiler Removal of Code to Clear Buffers|Отсутствие очистки буфера, связанное с компилятором|
|CWE-15|External Control of System or Configuration Setting|Возможность управления системой или настройками извне|
|CWE-16|Configuration|Уязвимости, связанные с конфигурацией|
|CWE-17|DEPRECATED: Code|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с кодом|
|CWE-18|DEPRECATED: Source Code|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с исходным кодом|
|CWE-19|Data Processing Errors|Ошибки, связанные с обработкой данных|
|CWE-20|Improper Input Validation|Некорректная проверка входных данных|
|CWE-21|Pathname Traversal and Equivalence Errors|Уязвимости, связанные с эквивалентностью и обходом пути|
|CWE-22|Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal')|Некорректные ограничения путей для каталогов (Выход за пределы каталога)|
|CWE-23|Relative Path Traversal|Подмена относительного пути|
|CWE-24|Path Traversal: '../filedir'|Выход за пределы каталога с помощью '../filedir'|
|CWE-25|Path Traversal: '/../filedir'|Выход за пределы каталога с помощью '/../filedir'|
|CWE-26|Path Traversal: '/dir/../filename'|Выход за пределы каталога с помощью '/dir/../filename'|
|CWE-27|Path Traversal: 'dir/../../filename'|Выход за пределы каталога с помощью 'dir/../../filename'|
|CWE-28|Path Traversal: '..\filedir'|Выход за пределы каталога с помощью '..\filedir'|
|CWE-29|Path Traversal: '\..\filename'|Выход за пределы каталога с помощью '\..\filename'|
|CWE-30|Path Traversal: '\dir\..\filename'|Выход за пределы каталога с помощью '\dir\..\filename'|
|CWE-31|Path Traversal: 'dir\..\..\filename'|Выход за пределы каталога с помощью '\dir\..\filename'|
|CWE-32|Path Traversal: '...' (Triple Dot)|Выход за пределы каталога с помощью '...' (трех точек)|
|CWE-33|Path Traversal: '....' (Multiple Dot)|Выход за пределы каталога с помощью '....' (нескольких точек)|
|CWE-34|Path Traversal: '....//'|Выход за пределы каталога с помощью '....//'|
|CWE-35|Path Traversal: '.../...//'|Выход за пределы каталога с помощью '.../...//'|
|CWE-36|Absolute Path Traversal|Подмена абсолютного пути|
|CWE-37|Path Traversal: '/absolute/pathname/here'|Выход за пределы каталога, используя '/здесь/абсолютный/путь'|
|CWE-38|Path Traversal: '\absolute\pathname\here'|Выход за пределы каталога, используя '\здесь\абсолютный\путь'|
|CWE-39|Path Traversal: 'C:dirname'|Подмена пути: 'C:имяпапки'|
|CWE-40|Path Traversal: '\\UNC\share\name\' (Windows UNC Share)|Подмена пути: '\\UNC\общий\ресурс\' (общий ресурс UNC Windows)|
|CWE-41|Improper Resolution of Path Equivalence|Некорректное разрешение эквивалентности пути|
|CWE-42|Path Equivalence: 'filename.' (Trailing Dot)|Эквивалентность пути: 'имяфайла.' (путь заканчивается точкой)|
|CWE-43|Path Equivalence: 'filename....' (Multiple Trailing Dot)|Эквивалентность пути: 'имяфайла....' (путь заканчиается несколькими точками)|
|CWE-44|Path Equivalence: 'file.name' (Internal Dot)|Эквивалентность пути: 'имя.файла' (точка в середине пути)|
|CWE-45|Path Equivalence: 'file...name' (Multiple Internal Dot)|Эквивалентность пути: 'имя…файла' (несколько точек в середине пути)|
|CWE-46|Path Equivalence: 'filename ' (Trailing Space)|Эквивалентность пути: 'filename ' (пробел в конце)|
|CWE-47|Path Equivalence: ' filename' (Leading Space)|Эквивалентность пути: ' filename' (пробел в начале)|
|CWE-48|Path Equivalence: 'file name' (Internal Whitespace)|Эквивалентность пути: 'file name' (пропуск внутри)|
|CWE-49|Path Equivalence: 'filename/' (Trailing Slash)|Эквивалентность пути: 'имяфайла/' (путь заканчивается косой чертой)|
|CWE-50|Path Equivalence: '//multiple/leading/slash'|Эквивалентность пути: '//несколько/косых/черт/в/начале'|
|CWE-51|Path Equivalence: '/multiple//internal/slash'|Эквивалентность пути: '/несколько/косых//черт/в/середине'|
|CWE-52|Path Equivalence: '/multiple/trailing/slash//'|Эквивалентность пути: '/несколько/косых/черт/в/конце//'|
|CWE-53|Path Equivalence: '\multiple\\internal\backslash'|Эквивалентность пути: '\несколько\обратных\\косых\черт\в\середине'|
|CWE-54|Path Equivalence: 'filedir\' (Trailing Backslash)|Эквивалентность пути: 'путькфайлу\' (путь заканчивается обратной косой чертой)|
|CWE-55|Path Equivalence: '/./' (Single Dot Directory)|Эквивалентность пути: '/./' (путь представлен одной точкой)|
|CWE-56|Path Equivalence: 'filedir*' (Wildcard)|Эквивалентность пути: 'путькфайлу*' (групповой символ)|
|CWE-57|Path Equivalence: 'fakedir/../realdir/filename'|Эквивалентность пути: 'ложныйпуть/../реальныйпуть/имяфайла'|
|CWE-58|Path Equivalence: Windows 8.3 Filename|Эквивалентность пути: имя файла Windows в формате 8.3|
|CWE-59|Improper Link Resolution Before File Access ('Link Following')|Некорректное разрешение ссылки перед доступом к файлу ("Переход по ссылке")|
|CWE-60|DEPRECATED: UNIX Path Link Problems|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные со ссылками UNIX|
|CWE-61|UNIX Symbolic Link (Symlink) Following|Уязвимости, связанные с символическими ссылками UNIX|
|CWE-62|UNIX Hard Link|Уязвимости, связанные с жесткими ссылками UNIX|
|CWE-63|DEPRECATED: Windows Path Link Problems|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные со ссылками Windows|
|CWE-64|Windows Shortcut Following (.LNK)|Уязвимости, связанные с ярлыками Windows (.LNK)|
|CWE-65|Windows Hard Link|Уязвимости, связанные с жесткими ссылками Windows|
|CWE-66|Improper Handling of File Names that Identify Virtual Resources|Некорректная обработка имен файлов, определяющих виртуальные ресурсы|
|CWE-67|Improper Handling of Windows Device Names|Некорректная обработка имен устройств Windows|
|CWE-68|DEPRECATED: Windows Virtual File Problems|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с виртуальными файлами Windows|
|CWE-69|Improper Handling of Windows ::DATA Alternate Data Stream|Некорректная обработка альтернативных потоков данных Windows ::DATA|
|CWE-70|DEPRECATED: Mac Virtual File Problems|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с виртуальными файлами в Mac ОС|
|CWE-71|DEPRECATED: Apple '.DS_Store'|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с Apple '.DS_Store'|
|CWE-72|Improper Handling of Apple HFS+ Alternate Data Stream Path|Некорректная обработка путей альтернативных потоков данных Apple HFS+|
|CWE-73|External Control of File Name or Path|Внешнее управление именем или путем файла|
|CWE-74|Improper Neutralization of Special Elements in Output Used by a Downstream Component ('Injection')|Некорректная нейтрализация специальных элементов в выходных данных, отправляемых клиенту (Внедрение)|
|CWE-75|Failure to Sanitize Special Elements into a Different Plane (Special Element Injection)|Некорректная обработка (очистка) специальных элементов управления (Внедрение специальных элементов)|
|CWE-76|Improper Neutralization of Equivalent Special Elements|Некорректная нейтрализация эквивалентов специальных элементов|
|CWE-77|Improper Neutralization of Special Elements used in a Command ('Command Injection')|Некорректная нейтрализация специальных элементов, используемых в командах (Внедрение команд)|
|CWE-78|Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')|Некорректная нейтрализация специальных элементов, используемых в системных командах (Внедрение команд ОС)|
|CWE-79|Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')|Некорректная нейтрализация входных данных при генерировании веб-страниц (Межсайтовое выполнение сценариев)|
|CWE-80|Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS)|Некорректная нейтрализация HTML-тегов, связанных со сценариями, на веб-страницах (Межсайтовое выполнение сценариев)|
|CWE-81|Improper Neutralization of Script in an Error Message Web Page|Некорректная нейтрализация сценариев на веб-страницах сообщений об ошибках|
|CWE-82|Improper Neutralization of Script in Attributes of IMG Tags in a Web Page|Некорректная нейтрализация сценариев в атрибутах тегов IMG на веб-страницах|
|CWE-83|Improper Neutralization of Script in Attributes in a Web Page|Некорректная нейтрализация сценариев в атрибутах на веб-страницах|
|CWE-84|Improper Neutralization of Encoded URI Schemes in a Web Page|Некорректная нейтрализация URI-схем на веб-страницах|
|CWE-85|Doubled Character XSS Manipulations|Межсайтовое выполнение сценариев, связанное с дублированием символов|
|CWE-86|Improper Neutralization of Invalid Characters in Identifiers in Web Pages|Некорректная нейтрализация недопустимых символов в идентификаторах на веб-страницах|
|CWE-87|Improper Neutralization of Alternate XSS Syntax|Межсайтовое выполнение сценариев, связанное с альтернативным синтаксисом сценариев|
|CWE-88|Argument Injection or Modification|Внедрение или изменение аргументов|
|CWE-89|Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection')|Некорректная нейтрализация специальных элементов, используемых в SQL-командах (Внедрение SQL-кода)|
|CWE-90|Improper Neutralization of Special Elements used in an LDAP Query ('LDAP Injection')|Некорректная нейтрализация специальных элементов, используемых в LDAP-запросах (Внедрение LDAP)|
|CWE-91|XML Injection (aka Blind XPath Injection)|Внедрение XML (Внедрение XPath вслепую)|
|CWE-92|DEPRECATED: Improper Sanitization of Custom Special Characters|НЕ РЕКОМЕНДУЕТСЯ: Некорректная очистка пользовательских спецсимволов|
|CWE-93|Improper Neutralization of CRLF Sequences ('CRLF Injection')|Некорректная нейтрализация последовательностей символов CRLF (Внедрение символов CRLF)|
|CWE-94|Improper Control of Generation of Code ('Code Injection')|Некорректное управление генерированием кода (Внедрение кода)|
|CWE-95|Improper Neutralization of Directives in Dynamically Evaluated Code ('Eval Injection')|Некорректная нейтрализация директив в динамически вычисляемом коде (Внедрение eval)|
|CWE-96|Improper Neutralization of Directives in Statically Saved Code ('Static Code Injection')|Некорректная нейтрализация директив в статически хранимом коде (Внедрение статического кода)|
|CWE-97|Improper Neutralization of Server-Side Includes (SSI) Within a Web Page|Некорректная нейтрализация включений на стороне сервера (SSI) на веб-страницах|
|CWE-98|Improper Control of Filename for Include/Require Statement in PHP Program ('PHP Remote File Inclusion')|Уязвимости, связанные с именами файлов для PHP-функций include или require (Удаленное внедрение файлов в PHP)|
|CWE-99|Improper Control of Resource Identifiers ('Resource Injection')|Некорректное управление идентификаторами ресурсов (Внедрение ресурсов)|
|CWE-100|DEPRECATED: Technology-Specific Input Validation Problems|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с проверкой входных данных в различных технологиях|
|CWE-101|DEPRECATED: Struts Validation Problems|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с проверками Struts|
|CWE-102|Struts: Duplicate Validation Forms|Struts: идентичные формы проверки|
|CWE-103|Struts: Incomplete validate() Method Definition|Struts: некорректное определение метода validate()|
|CWE-104|Struts: Form Bean Does Not Extend Validation Class|Struts: beans для форм не расширяет класс проверок|
|CWE-105|Struts: Form Field Without Validator|Struts: поле формы без валидатора|
|CWE-106|Struts: Plug-in Framework not in Use|Struts: не используется фреймворк плагина|
|CWE-107|Struts: Unused Validation Form|Struts: неиспользуемая форма проверки|
|CWE-108|Struts: Unvalidated Action Form|Struts: Action Form без соответствующей формы проверки|
|CWE-109|Struts: Validator Turned Off|Struts: валидатор отключен|
|CWE-110|Struts: Validator Without Form Field|Struts: валидатор без поля формы|
|CWE-111|Direct Use of Unsafe JNI|Использование небезопасного JNI|
|CWE-112|Missing XML Validation|Отсутствие проверки XML|
|CWE-113|Improper Neutralization of CRLF Sequences in HTTP Headers ('HTTP Response Splitting')|Некорректная нейтрализация последовательностей символов CRLF в HTTP-заголовках (Расщепление HTTP-ответов)|
|CWE-114|Process Control|Управление выполнением команд|
|CWE-115|Misinterpretation of Input|Некорректная интерпретация входных данных|
|CWE-116|Improper Encoding or Escaping of Output|Некорректная кодировка или очистка выходных данных|
|CWE-117|Improper Output Neutralization for Logs|Некорректная нейтрализация выходных данных для записи в журналы|
|CWE-118|Incorrect Access of Indexable Resource ('Range Error')|Некорректное ограничение доступа индексируемых ресурсов (Ошибка диапазона)|
|CWE-119|Improper Restriction of Operations within the Bounds of a Memory Buffer|Выполнение операций за пределами буфера памяти|
|CWE-120|Buffer Copy without Checking Size of Input ('Classic Buffer Overflow')|Копирование содержимого буфера без проверки размера входных данных (классическое переполнение буфера)|
|CWE-121|Stack-based Buffer Overflow|Переполнение буфера в стеке|
|CWE-122|Heap-based Buffer Overflow|Переполнение буфера в динамической памяти|
|CWE-123|Write-what-where Condition|Запись произвольных данных в произвольную область|
|CWE-124|Buffer Underwrite ('Buffer Underflow')|Запись данных в область перед началом буфера|
|CWE-125|Out-of-bounds Read|Чтение за пределами буфера|
|CWE-126|Buffer Over-read|Чтение за границей буфера|
|CWE-127|Buffer Under-read|Чтение перед границей буфера|
|CWE-128|Wrap-around Error|Ошибка, связанная с циклическим переносом|
|CWE-129|Improper Validation of Array Index|Некорректная проверка индекса массива|
|CWE-130|Improper Handling of Length Parameter Inconsistency |Некорректная обработка несоответствий параметров длины|
|CWE-131|Incorrect Calculation of Buffer Size|Некорректный расчет размера буфера|
|CWE-132|DEPRECATED (Duplicate): Miscalculated Null Termination|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Некорректный расчет нулевых символов|
|CWE-133|String Errors|Ошибки при работе со строками|
|CWE-134|Use of Externally-Controlled Format String|Использование форматной строки, контролируемой извне|
|CWE-135|Incorrect Calculation of Multi-Byte String Length|Некорректный расчет длины многобайтовых строк|
|CWE-136|Type Errors|Ошибки, связанные с типами данных|
|CWE-137|Representation Errors|Уязвимости, связанные с представлением|
|CWE-138|Improper Neutralization of Special Elements|Некорректная нейтрализация специальных элементов|
|CWE-139|DEPRECATED: General Special Element Problems|НЕ РЕКОМЕНДУЕТСЯ: Общие проблемы, связанные со специальными элементами|
|CWE-140|Improper Neutralization of Delimiters|Некорректная нейтрализация разделителей|
|CWE-141|Improper Neutralization of Parameter/Argument Delimiters|Некорректная нейтрализация разделителей параметров или аргументов|
|CWE-142|Improper Neutralization of Value Delimiters|Некорректная нейтрализация разделителей значений|
|CWE-143|Improper Neutralization of Record Delimiters|Некорректная нейтрализация разделителей записей|
|CWE-144|Improper Neutralization of Line Delimiters|Некорректная нейтрализация разделителей строк|
|CWE-145|Improper Neutralization of Section Delimiters|Некорректная нейтрализация разделителей разделов|
|CWE-146|Improper Neutralization of Expression/Command Delimiters|Некорректная нейтрализация разделителей выражений или команд|
|CWE-147|Improper Neutralization of Input Terminators|Некорректная нейтрализация окончаний входных данных|
|CWE-148|Improper Neutralization of Input Leaders|Некорректная нейтрализация начала входных данных|
|CWE-149|Improper Neutralization of Quoting Syntax|Некорректная нейтрализация кавычек|
|CWE-150|Improper Neutralization of Escape, Meta, or Control Sequences|Некорректная нейтрализация метасимволов или управляющих последовательностей|
|CWE-151|Improper Neutralization of Comment Delimiters|Некорректная нейтрализация символов комментариев|
|CWE-152|Improper Neutralization of Macro Symbols|Некорректная нейтрализация макросимволов|
|CWE-153|Improper Neutralization of Substitution Characters|Некорректная нейтрализация символов подстановки|
|CWE-154|Improper Neutralization of Variable Name Delimiters|Некорректная нейтрализация разделителей имен переменных|
|CWE-155|Improper Neutralization of Wildcards or Matching Symbols|Некорректная нейтрализация групповых символов или символов соответствия|
|CWE-156|Improper Neutralization of Whitespace|Некорректная нейтрализация пропусков (пробелов)|
|CWE-157|Failure to Sanitize Paired Delimiters|Некорректная обработка парных разделителей|
|CWE-158|Improper Neutralization of Null Byte or NUL Character|Некорректная нейтрализация нулевых байтов или символов NUL|
|CWE-159|Failure to Sanitize Special Element|Некорректная обработка специальных элементов|
|CWE-160|Improper Neutralization of Leading Special Elements|Некорректная нейтрализация специальных элементов в начале|
|CWE-161|Improper Neutralization of Multiple Leading Special Elements|Некорректная нейтрализация множественных специальных элементов в начале|
|CWE-162|Improper Neutralization of Trailing Special Elements|Некорректная нейтрализация специальных элементов в конце|
|CWE-163|Improper Neutralization of Multiple Trailing Special Elements|Некорректная нейтрализация множественных специальных элементов в конце|
|CWE-164|Improper Neutralization of Internal Special Elements|Некорректная нейтрализация специальных элементов в середине|
|CWE-165|Improper Neutralization of Multiple Internal Special Elements|Некорректная нейтрализация множественных специальных элементов в середине|
|CWE-166|Improper Handling of Missing Special Element|Некорректная обработка отсутствующих специальных элементов|
|CWE-167|Improper Handling of Additional Special Element|Некорректная обработка дополнительных специальных элементов|
|CWE-168|Improper Handling of Inconsistent Special Elements|Некорректная обработка несоответствий специальных элементов|
|CWE-169|DEPRECATED: Technology-Specific Special Elements|НЕ РЕКОМЕНДУЕТСЯ: Некорректная обработка специальных элементов различных технологий|
|CWE-170|Improper Null Termination|Некорректное использование нулевых символов|
|CWE-171|Cleansing, Canonicalization, and Comparison Errors|Уязвимости, связанные с очисткой, нормализацией и сопоставлением|
|CWE-172|Encoding Error|Ошибка, связанная с кодированием|
|CWE-173|Improper Handling of Alternate Encoding|Некорректная обработка альтернативных кодировок|
|CWE-174|Double Decoding of the Same Data|Повторное декодирование данных|
|CWE-175|Improper Handling of Mixed Encoding|Некорректная обработка смешанных кодировок|
|CWE-176|Improper Handling of Unicode Encoding|Некорректная обработка кодировки Юникод|
|CWE-177|Improper Handling of URL Encoding (Hex Encoding)|Некорректная обработка URL-кодировки (Шестнадцатеричная кодировка)|
|CWE-178|Improper Handling of Case Sensitivity|Некорректная обработка значимости регистра|
|CWE-179|Incorrect Behavior Order: Early Validation|Некорректный порядок действий: преждевременная проверка|
|CWE-180|Incorrect Behavior Order: Validate Before Canonicalize|Некорректный порядок действий: проверка до нормализации|
|CWE-181|Incorrect Behavior Order: Validate Before Filter|Некорректный порядок действий: проверка до фильтрации|
|CWE-182|Collapse of Data into Unsafe Value|Преобразование данных до небезопасных значений|
|CWE-183|Permissive Whitelist|Некорректная настройка белого списка|
|CWE-184|Incomplete Blacklist|Неполный черный список|
|CWE-185|Incorrect Regular Expression|Некорректные регулярные выражения|
|CWE-186|Overly Restrictive Regular Expression|Ограниченные регулярные выражения|
|CWE-187|Partial Comparison|Частичное сопоставление|
|CWE-188|Reliance on Data/Memory Layout|Некорректные предположения о схеме организации данных или памяти|
|CWE-189|Numeric Errors|Ошибки, возникающие при обработке чисел|
|CWE-190|Integer Overflow or Wraparound|Целочисленное переполнение или циклический возврат|
|CWE-191|Integer Underflow (Wrap or Wraparound)|Потеря значимости целых чисел (простой или циклический возврат)|
|CWE-192|Integer Coercion Error|Ошибки преобразования целых чисел|
|CWE-193|Off-by-one Error|Ошибка смещения на единицу|
|CWE-194|Unexpected Sign Extension|Непредусмотренное добавление знака|
|CWE-195|Signed to Unsigned Conversion Error|Ошибка преобразования примитивов со знаком в примитивы без знака|
|CWE-196|Unsigned to Signed Conversion Error|Ошибка преобразования примитивов без знака в примитивы со знаком|
|CWE-197|Numeric Truncation Error|Ошибка числовых усечений|
|CWE-198|Use of Incorrect Byte Ordering|Использование некорректного порядка байтов|
|CWE-199|Information Management Errors|Некорректное управление данными|
|CWE-200|Information Exposure|Разглашение информации|
|CWE-201|Information Exposure Through Sent Data|Разглашение информации в отправляемых данных|
|CWE-202|Exposure of Sensitive Data Through Data Queries|Разглашение конфиденциальных данных, связанное с запросами|
|CWE-203|Information Exposure Through Discrepancy|Разглашение информации, связанное с разницей в поведении или ответах|
|CWE-204|Response Discrepancy Information Exposure|Разглашение информации, связанное с разницей в ответах|
|CWE-205|Information Exposure Through Behavioral Discrepancy|Разглашение информации, связанное с разницей в поведении|
|CWE-206|Information Exposure of Internal State Through Behavioral Inconsistency|Разглашение информации о состоянии системы, связанное с разницей в поведении|
|CWE-207|Information Exposure Through an External Behavioral Inconsistency|Разглашение информации, связанное с отличиями в поведении системы|
|CWE-208|Information Exposure Through Timing Discrepancy|Разглашение информации, связанное с временной разницей при выполнении операций|
|CWE-209|Information Exposure Through an Error Message|Разглашение информации в сообщениях об ошибках|
|CWE-210|Information Exposure Through Self-generated Error Message|Разглашение информации в генерируемых программой сообщениях об ошибках|
|CWE-211|Information Exposure Through Externally-generated Error Message|Разглашение информации в генерируемых внешней программой сообщениях об ошибках|
|CWE-212|Improper Cross-boundary Removal of Sensitive Data|Некорректное удаление конфиденциальных данных|
|CWE-213|Intentional Information Exposure|Преднамеренное разглашение информации|
|CWE-214|Information Exposure Through Process Environment|Разглашение информации через окружение процесса|
|CWE-215|Information Exposure Through Debug Information|Разглашение данных через отладочную информацию|
|CWE-216|Containment Errors (Container Errors)|Ошибки включения данных, связанные с контейнером|
|CWE-217|DEPRECATED: Failure to Protect Stored Data from Modification|НЕ РЕКОМЕНДУЕТСЯ: Возможность изменения хранимых данных|
|CWE-218|DEPRECATED (Duplicate): Failure to provide confidentiality for stored data|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Нарушение конфиденциальности хранимых данных|
|CWE-219|Sensitive Data Under Web Root|Хранение критичных данных в корневом веб-каталоге|
|CWE-220|Sensitive Data Under FTP Root|Хранение критичных данных в корневом FTP-каталоге|
|CWE-221|Information Loss or Omission|Отсутствие регистрации или потеря данных|
|CWE-222|Truncation of Security-relevant Information|Усечение данных, относящихся к безопасности|
|CWE-223|Omission of Security-relevant Information|Отсутствует регистрация или отображение данных, относящихся к безопасности|
|CWE-224|Obscured Security-relevant Information by Alternate Name|Информация, относящаяся к безопасности, скрывается за альтернативными именами|
|CWE-225|DEPRECATED (Duplicate): General Information Management Problems|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Общие проблемы, связанные с управлением данными|
|CWE-226|Sensitive Information Uncleared Before Release|Неполное удаление критичных данных после их использования|
|CWE-227|Improper Fulfillment of API Contract ('API Abuse')|Некорректное выполнение соглашений API (Злоупотребление API)|
|CWE-228|Improper Handling of Syntactically Invalid Structure|Некорректная обработка синтаксически неверных структур|
|CWE-229|Improper Handling of Values|Некорректная обработка значений|
|CWE-230|Improper Handling of Missing Values|Некорректная обработка отсутствующих (пустых) значений|
|CWE-231|Improper Handling of Extra Values|Некорректная обработка дополнительных значений|
|CWE-232|Improper Handling of Undefined Values|Некорректная обработка неопределенных значений|
|CWE-233|Improper Handling of Parameters|Некорректная обработка параметров|
|CWE-234|Failure to Handle Missing Parameter|Уязвимости, связанные с обработкой отсутствующих параметров|
|CWE-235|Improper Handling of Extra Parameters|Некорректная обработка дополнительных параметров|
|CWE-236|Improper Handling of Undefined Parameters|Некорректная обработка неопределенных параметров|
|CWE-237|Improper Handling of Structural Elements|Некорректная обработка структурных элементов|
|CWE-238|Improper Handling of Incomplete Structural Elements|Некорректная обработка неполных структурных элементов|
|CWE-239|Failure to Handle Incomplete Element|Некорректная обработка неполных элементов|
|CWE-240|Improper Handling of Inconsistent Structural Elements|Некорректная обработка несоответствий структурных элементов|
|CWE-241|Improper Handling of Unexpected Data Type|Некорректная обработка непредусмотренных типов данных|
|CWE-242|Use of Inherently Dangerous Function|Использование небезопасных функций|
|CWE-243|Creation of chroot Jail Without Changing Working Directory|Создание среды chroot jail без изменения рабочего каталога|
|CWE-244|Improper Clearing of Heap Memory Before Release ('Heap Inspection')|Некорректная очистка динамической памяти перед ее освобождением (Ревизия динамической памяти)|
|CWE-245|J2EE Bad Practices: Direct Management of Connections|Уязвимости J2EE: управление подключениями напрямую|
|CWE-246|J2EE Bad Practices: Direct Use of Sockets|Уязвимости J2EE: использование сокетов напрямую|
|CWE-247|DEPRECATED (Duplicate): Reliance on DNS Lookups in a Security Decision|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Использование поиска DNS для принятия решений, связанных с безопасностью|
|CWE-248|Uncaught Exception|Необработанное исключение|
|CWE-249|DEPRECATED: Often Misused: Path Manipulation|НЕ РЕКОМЕНДУЕТСЯ: Некорректное использование обработки путей|
|CWE-250|Execution with Unnecessary Privileges|Выполнение операций с избыточными привилегиями|
|CWE-251|Often Misused: String Management|Некорректная работа со строками|
|CWE-252|Unchecked Return Value|Отсутствует проверка возвращаемых значений|
|CWE-253|Incorrect Check of Function Return Value|Некорректная проверка значений, возвращаемых функцией|
|CWE-254|Security Features|Уязвимости в безопасности ПО|
|CWE-255|Credentials Management|Уязвимости, связанные с управлением учетными данными|
|CWE-256|Plaintext Storage of a Password|Хранение пароля в незашифрованном виде|
|CWE-257|Storing Passwords in a Recoverable Format|Небезопасное хранение пароля, допускающее его повторное использование|
|CWE-258|Empty Password in Configuration File|Пустой пароль в файле конфигурации|
|CWE-259|Use of Hard-coded Password|Использование жестко закодированного пароля|
|CWE-260|Password in Configuration File|Пароль содержится в файле конфигурации|
|CWE-261|Weak Cryptography for Passwords|Недостаточно надежное шифрование паролей|
|CWE-262|Not Using Password Aging|Отсутствует срок действия паролей|
|CWE-263|Password Aging with Long Expiration|Срок действия паролей слишком большой|
|CWE-264|Permissions, Privileges, and Access Controls|Уязвимость в управлении доступом, привилегиями и разрешениями|
|CWE-265|Privilege / Sandbox Issues|Уязвимости, связанные с привилегиями или песочницей|
|CWE-266|Incorrect Privilege Assignment|Некорректное назначение привилегий|
|CWE-267|Privilege Defined With Unsafe Actions|Привилегии с возможностью выполнять небезопасные действия|
|CWE-268|Privilege Chaining|Объединение привилегий|
|CWE-269|Improper Privilege Management|Некорректное управление привилегиями|
|CWE-270|Privilege Context Switching Error|Уязвимости, связанные с переключением контекста привилегий|
|CWE-271|Privilege Dropping / Lowering Errors|Ошибки сброса или понижения привилегий|
|CWE-272|Least Privilege Violation|Нарушение принципа минимальных привилегий|
|CWE-273|Improper Check for Dropped Privileges|Некорректная проверка выполнения сброса привилегий|
|CWE-274|Improper Handling of Insufficient Privileges|Некорректная обработка несоответствия привилегий|
|CWE-275|Permission Issues|Уязвимости , связанные с разрешениями|
|CWE-276|Incorrect Default Permissions|Некорректные разрешения, назначаемые по умолчанию|
|CWE-277|Insecure Inherited Permissions|Небезопасное наследование разрешений|
|CWE-278|Insecure Preserved Inherited Permissions|Небезопасные наследуемые разрешения|
|CWE-279|Incorrect Execution-Assigned Permissions|Некорректное назначение разрешений при выполнении|
|CWE-280|Improper Handling of Insufficient Permissions or Privileges |Некорректная обработка неподходящих разрешений или привилегий|
|CWE-281|Improper Preservation of Permissions|Некорректное сохранение разрешений|
|CWE-282|Improper Ownership Management|Некорректное управление правами на владение|
|CWE-283|Unverified Ownership|Некорректная проверка прав на владение|
|CWE-284|Improper Access Control|Некорректное управление доступом|
|CWE-285|Improper Authorization|Некорректная авторизация|
|CWE-286|Incorrect User Management|Некорректное управление пользователями|
|CWE-287|Improper Authentication|Некорректная аутентификация|
|CWE-288|Authentication Bypass Using an Alternate Path or Channel|Обход аутентификации, связанный с альтернативными путями или каналами|
|CWE-289|Authentication Bypass by Alternate Name|Обход аутентификации, связанный с альтернативными именами|
|CWE-290|Authentication Bypass by Spoofing|Обход аутентификации, связанный с подменой данных|
|CWE-291|Reliance on IP Address for Authentication|Использование IP-адреса для аутентификации|
|CWE-292|DEPRECATED (Duplicate): Trusting Self-reported DNS Name|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Использование DNS-имен для аутентификации|
|CWE-293|Using Referer Field for Authentication|Использование поля Referer для аутентификации|
|CWE-294|Authentication Bypass by Capture-replay|Обход аутентификации при помощи перехвата и воспроизведения|
|CWE-295|Improper Certificate Validation|Некорректная проверка сертификатов|
|CWE-296|Improper Following of a Certificate's Chain of Trust|Некорректная проверка цепочки доверия сертификатов|
|CWE-297|Improper Validation of Certificate with Host Mismatch|Некорректная проверка сертификатов с несоответствием узла|
|CWE-298|Improper Validation of Certificate Expiration|Некорректная проверка срока действия сертификата|
|CWE-299|Improper Check for Certificate Revocation|Некорректная проверка статуса сертификата (отозван или нет)|
|CWE-300|Channel Accessible by Non-Endpoint ('Man-in-the-Middle')|Возможность доступа к каналу из точки, не являющейся конечной (Человек посередине)|
|CWE-301|Reflection Attack in an Authentication Protocol|Атака на протокол аутентификации с использованием отражения|
|CWE-302|Authentication Bypass by Assumed-Immutable Data|Обход аутентификации, используя предположительно неизменяемые данные|
|CWE-303|Incorrect Implementation of Authentication Algorithm|Некорректная реализация алгоритма аутентификации|
|CWE-304|Missing Critical Step in Authentication|Пропущен важный шаг аутентификации|
|CWE-305|Authentication Bypass by Primary Weakness|Обход аутентификации с помощью стороннего недостатка|
|CWE-306|Missing Authentication for Critical Function|Отсутствие аутентификации для критически важных функций|
|CWE-307|Improper Restriction of Excessive Authentication Attempts|Некорректное ограничение количества неудачных попыток аутентификации|
|CWE-308|Use of Single-factor Authentication|Использование однофакторной аутентификации|
|CWE-309|Use of Password System for Primary Authentication|Использование системы паролей для первичной аутентификации|
|CWE-310|Cryptographic Issues|Уязвимости, связанные с криптографией|
|CWE-311|Missing Encryption of Sensitive Data|Отсутствует шифрование критичных данных|
|CWE-312|Cleartext Storage of Sensitive Information|Хранение критичных данных в незашифрованном виде|
|CWE-313|Cleartext Storage in a File or on Disk|Хранение критичных данных в незашифрованном виде в файле или на диске|
|CWE-314|Cleartext Storage in the Registry|Хранение критичных данных в незашифрованном виде в реестре|
|CWE-315|Cleartext Storage of Sensitive Information in a Cookie|Хранение критичных данных в незашифрованном виде в куки-файлах|
|CWE-316|Cleartext Storage of Sensitive Information in Memory|Хранение критичных данных в незашифрованном виде в памяти|
|CWE-317|Cleartext Storage of Sensitive Information in GUI|Хранение критичных данных в незашифрованном виде в графическом интерфейсе|
|CWE-318|Cleartext Storage of Sensitive Information in Executable|Хранение критичных данных в незашифрованном виде в исполняемом файле|
|CWE-319|Cleartext Transmission of Sensitive Information|Передача критичных данных в незашифрованном виде|
|CWE-320|Key Management Errors|Уязвимости, связанные с управлением ключами|
|CWE-321|Use of Hard-coded Cryptographic Key|Использование жестко закодированного ключа шифрования|
|CWE-322|Key Exchange without Entity Authentication|Обмен ключами без аутентификации субъекта|
|CWE-323|Reusing a Nonce, Key Pair in Encryption|Повторное использование одноразовых кодов при шифровании|
|CWE-324|Use of a Key Past its Expiration Date|Использование ключа после истечения срока его действия|
|CWE-325|Missing Required Cryptographic Step|Пропущена часть криптографического алгоритма|
|CWE-326|Inadequate Encryption Strength|Недостаточно надежное шифрование|
|CWE-327|Use of a Broken or Risky Cryptographic Algorithm|Использование скомпрометированного или ненадежного криптографического алгоритма|
|CWE-328|Reversible One-Way Hash|Обратимая односторонняя хеш-функция|
|CWE-329|Not Using a Random IV with CBC Mode|Использование непроизвольного вектора инициализации для режима сцепления блоков шифротекста|
|CWE-330|Use of Insufficiently Random Values|Использование недостаточно случайных значений|
|CWE-331|Insufficient Entropy|Недостаточная энтропия|
|CWE-332|Insufficient Entropy in PRNG|Недостаточная энтропия ГПСЧ|
|CWE-333|Improper Handling of Insufficient Entropy in TRNG|Некорректная обработка недостаточной энтропии в генераторе истинно случайных чисел|
|CWE-334|Small Space of Random Values|Недостаточно большой диапазон случайных значений|
|CWE-335|PRNG Seed Error|Уязвимости, связанные с начальным значением ГПСЧ|
|CWE-336|Same Seed in PRNG|Использование одинакового начального значения ГПСЧ|
|CWE-337|Predictable Seed in PRNG|Предсказуемое начальное значение ГПСЧ|
|CWE-338|Use of Cryptographically Weak Pseudo-Random Number Generator (PRNG)|Использование ненадежного ГПСЧ|
|CWE-339|Small Seed Space in PRNG|Недостаточно большой диапазон для начальных значений ГПСЧ|
|CWE-340|Predictability Problems|Уязвимости, связанные с предсказуемостью|
|CWE-341|Predictable from Observable State|Возможность прогнозирования на основе наблюдаемого состояния|
|CWE-342|Predictable Exact Value from Previous Values|Возможность точного прогнозирования значений, исходя из предыдущих значений|
|CWE-343|Predictable Value Range from Previous Values|Возможность спрогнозировать диапазон значений, исходя из предыдущих значений|
|CWE-344|Use of Invariant Value in Dynamically Changing Context|Использование инвариантного значения в динамически меняющемся контексте|
|CWE-345|Insufficient Verification of Data Authenticity|Некорректная проверка достоверности данных|
|CWE-346|Origin Validation Error|Уязвимости, связанные с проверкой источника|
|CWE-347|Improper Verification of Cryptographic Signature|Некорректная проверка криптографической подписи|
|CWE-348|Use of Less Trusted Source|Использование менее надежного источника|
|CWE-349|Acceptance of Extraneous Untrusted Data With Trusted Data|Одобрение сторонних недоверенных данных вместе с доверенными|
|CWE-350|Reliance on Reverse DNS Resolution for a Security-Critical Action|Использование обратного разрешения DNS для принятия решений, связанных с безопасностью|
|CWE-351|Insufficient Type Distinction|Некорректное распознавание типов|
|CWE-352|Cross-Site Request Forgery (CSRF)|Подделка межсайтового запроса|
|CWE-353|Missing Support for Integrity Check|Отсутствует проверка целостности|
|CWE-354|Improper Validation of Integrity Check Value|Некорректная проверка контрольных сумм|
|CWE-355|User Interface Security Issues|Уязвимости в интерфейсе пользователя|
|CWE-356|Product UI does not Warn User of Unsafe Actions|Отсутствие в интерфейсе предупреждений о выполнении небезопасных действий|
|CWE-357|Insufficient UI Warning of Dangerous Operations|Недостаточно очевидное предупреждение об опасных операциях|
|CWE-358|Improperly Implemented Security Check for Standard|Некорректная реализация стандартизированных проверок безопасности|
|CWE-359|Exposure of Private Information ('Privacy Violation')|Разглашение конфиденциальных данных (Нарушение конфиденциальности)|
|CWE-360|Trust of System Event Data|Доверие к данным о системных событиях|
|CWE-361|Time and State|Время и состояние|
|CWE-362|Concurrent Execution using Shared Resource with Improper Synchronization ('Race Condition')|Одновременное использование общих ресурсов при выполнении кода без соответствующей синхронизации (Состояние гонки)|
|CWE-363|Race Condition Enabling Link Following|Состояние гонки, позволяющее осуществить переход по ссылке|
|CWE-364|Signal Handler Race Condition|Состояние гонки, связанное с обработчиком сигналов|
|CWE-365|Race Condition in Switch|Состояние гонки, связанное с оператором выбора|
|CWE-366|Race Condition within a Thread|Состояние гонки в потоке|
|CWE-367|Time-of-check Time-of-use (TOCTOU) Race Condition|Состояние гонки, связанное с временем проверки и временем использования|
|CWE-368|Context Switching Race Condition|Состояние гонки, связанное с переключением контекста|
|CWE-369|Divide By Zero|Деление на ноль|
|CWE-370|Missing Check for Certificate Revocation after Initial Check|Отсутствует проверка отзыва сертификата после первоначальной проверки|
|CWE-371|State Issues|Уязвимости, связанные с состоянием|
|CWE-372|Incomplete Internal State Distinction|Некорректное определение внутреннего состояния|
|CWE-373|DEPRECATED: State Synchronization Error|НЕ РЕКОМЕНДУЕТСЯ: Ошибка синхронизации состояния|
|CWE-374|Passing Mutable Objects to an Untrusted Method|Передача изменяемых объектов недоверенному методу|
|CWE-375|Returning a Mutable Object to an Untrusted Caller|Возврат изменяемого объекта недоверенному вызывающему клиенту|
|CWE-376|Temporary File Issues|Уязвимости, связанные с временными файлами|
|CWE-377|Insecure Temporary File|Уязвимости, связанные с небезопасными временными файлами|
|CWE-378|Creation of Temporary File With Insecure Permissions|Создание временных файлов с небезопасными разрешениями|
|CWE-379|Creation of Temporary File in Directory with Incorrect Permissions|Создание временных файлов в каталоге, имеющем некорректные разрешения|
|CWE-380|Technology-Specific Time and State Issues|Уязвимости, связанные со временем и состоянием в различных технологиях|
|CWE-381|J2EE Time and State Issues|Уязвимости J2EE, связанные со временем и состоянием|
|CWE-382|J2EE Bad Practices: Use of System.exit()|Уязвимости J2EE: использование System.exit()|
|CWE-383|J2EE Bad Practices: Direct Use of Threads|Уязвимости J2EE: прямое использование потоков|
|CWE-384|Session Fixation|Фиксация сессии|
|CWE-385|Covert Timing Channel|Скрытый временной канал|
|CWE-386|Symbolic Name not Mapping to Correct Object|Символическое имя ссылается на некорректный объект|
|CWE-387|Signal Errors|Уязвимости, связанные с обработкой сигналов|
|CWE-388|Error Handling|Уязвимости, связанные с обработкой ошибок|
|CWE-389|Error Conditions, Return Values, Status Codes|Уязвимости, связанные с возвращаемыми значениями, кодами состояния|
|CWE-390|Detection of Error Condition Without Action|Обнаружение ошибки без реагирования на нее|
|CWE-391|Unchecked Error Condition|Игнорирование ошибок|
|CWE-392|Missing Report of Error Condition|Отсутствие отчета об ошибке|
|CWE-393|Return of Wrong Status Code|Возвращение некорректного кода состояния|
|CWE-394|Unexpected Status Code or Return Value|Непредусмотренные коды состояния или возвращаемые значения|
|CWE-395|Use of NullPointerException Catch to Detect NULL Pointer Dereference|Использование NullPointerException для определения разыменования нулевого указателя|
|CWE-396|Declaration of Catch for Generic Exception|Перехват универсальных исключений|
|CWE-397|Declaration of Throws for Generic Exception|Генерирование универсальных исключений|
|CWE-398|Indicator of Poor Code Quality|Плохое качество кода|
|CWE-399|Resource Management Errors|Уязвимости, связанные с управлением ресурсами|
|CWE-400|Uncontrolled Resource Consumption ('Resource Exhaustion')|Неконтролируемое использование ресурсов (Исчерпание ресурсов)|
|CWE-401|Improper Release of Memory Before Removing Last Reference ('Memory Leak')|Некорректное освобождение памяти до удаления последней ссылки (Утечка памяти)|
|CWE-402|Transmission of Private Resources into a New Sphere ('Resource Leak')|Передача ресурсов с ограниченным доступом другому окружению (Утечка ресурсов)|
|CWE-403|Exposure of File Descriptor to Unintended Control Sphere ('File Descriptor Leak')|Доступность файлового дескриптора непредусмотренному процессу ("Утечка файловых дескрипторов")|
|CWE-404|Improper Resource Shutdown or Release|Некорректное освобождение ресурсов|
|CWE-405|Asymmetric Resource Consumption (Amplification)|Асимметричное использование ресурсов (Амплификация)|
|CWE-406|Insufficient Control of Network Message Volume (Network Amplification)|Недостаточный контроль объема сетевых сообщений (Увеличение сетевого трафика)|
|CWE-407|Algorithmic Complexity|Алгоритмическая сложность|
|CWE-408|Incorrect Behavior Order: Early Amplification|Некорректный порядок действий: преждевременное расширение привилегий|
|CWE-409|Improper Handling of Highly Compressed Data (Data Amplification)|Некорректная обработка данных с высокой степенью сжатия (Увеличение объема данных)|
|CWE-410|Insufficient Resource Pool|Недостаточный пул ресурсов|
|CWE-411|Resource Locking Problems|Уязвимости, связанные с блокировкой ресурсов|
|CWE-412|Unrestricted Externally Accessible Lock|Неконтролируемая внешняя блокировка|
|CWE-413|Improper Resource Locking|Некорректная блокировка ресурсов|
|CWE-414|Missing Lock Check|Отсутствует проверка блокировки|
|CWE-415|Double Free|Двойное освобождение|
|CWE-416|Use After Free|Использование после освобождения|
|CWE-417|Channel and Path Errors|Уязвимости, связанные с каналами связи и путями доступа|
|CWE-418|DEPRECATED: Channel Errors|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с каналами связи|
|CWE-419|Unprotected Primary Channel|Незащищенность основного канала|
|CWE-420|Unprotected Alternate Channel|Незащищенность резервного канала|
|CWE-421|Race Condition During Access to Alternate Channel|Состояние гонки при доступе к резервному каналу|
|CWE-422|Unprotected Windows Messaging Channel ('Shatter')|Незащищенный канал сообщений Windows (атака Shatter/Осколок)|
|CWE-423|DEPRECATED (Duplicate): Proxied Trusted Channel|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Использование прокси для доверенного канала|
|CWE-424|Improper Protection of Alternate Path|Недостаточная защита резервного пути|
|CWE-425|Direct Request ('Forced Browsing')|Прямой запрос (Принудительный переход)|
|CWE-426|Untrusted Search Path|Подмена пути исполнения|
|CWE-427|Uncontrolled Search Path Element|Неконтролируемый элемент пути поиска|
|CWE-428|Unquoted Search Path or Element|Отсутствие кавычек вокруг элемента в пути поиска|
|CWE-429|Handler Errors|Уязвимости, связанные с обработчиками|
|CWE-430|Deployment of Wrong Handler|Использование некорректного обработчика|
|CWE-431|Missing Handler|Отсутствует обработчик|
|CWE-432|Dangerous Signal Handler not Disabled During Sensitive Operations|Отсутствие блокировки опасного обработчика сигналов при выполнении критичных операций|
|CWE-433|Unparsed Raw Web Content Delivery|Передача необработанного веб-содержимого|
|CWE-434|Unrestricted Upload of File with Dangerous Type|Отсутствие ограничений на загрузку файлов небезопасного типа|
|CWE-435|Interaction Error|Ошибка взаимодействия|
|CWE-436|Interpretation Conflict|Конфликт интерпретации|
|CWE-437|Incomplete Model of Endpoint Features|Неполная модель функций конечной точки|
|CWE-438|Behavioral Problems|Уязвимости, связанные с непредусмотренным поведением|
|CWE-439|Behavioral Change in New Version or Environment|Изменение поведения в новой версии или ином окружении|
|CWE-440|Expected Behavior Violation|Отклонения от ожидаемого поведения|
|CWE-441|Unintended Proxy or Intermediary ('Confused Deputy')|Непредусмотренный прокси или посредник ("Подмена заместителя")|
|CWE-442|Web Problems|Веб-проблемы|
|CWE-443|DEPRECATED (Duplicate): HTTP response splitting|НЕ РЕКОМЕНДУЕТСЯ (дублирование): Расщепление HTTP-ответов|
|CWE-444|Inconsistent Interpretation of HTTP Requests ('HTTP Request Smuggling')|Некорректная интерпретация HTTP-запросов (Несанкционированные HTTP-запросы)|
|CWE-445|DEPRECATED: User Interface Errors|НЕ РЕКОМЕНДУЕТСЯ: Ошибки, связанные с интерфейсом пользователя|
|CWE-446|UI Discrepancy for Security Feature|Некорректное отображение интерфейсом настроек безопасности|
|CWE-447|Unimplemented or Unsupported Feature in UI|Нереализованная или неподдерживаемая функция в интерфейсе|
|CWE-448|Obsolete Feature in UI|Устаревшая функция в интерфейсе пользователя|
|CWE-449|The UI Performs the Wrong Action|Некорректная работа интерфейса|
|CWE-450|Multiple Interpretations of UI Input|Наличие вариантов интерпретации входных данных интерфейсом|
|CWE-451|User Interface (UI) Misrepresentation of Critical Information|Некорректное представление важной информации интерфейсом пользователя|
|CWE-452|Initialization and Cleanup Errors|Ошибки очистки и инициализации|
|CWE-453|Insecure Default Variable Initialization|Небезопасная инициализация переменной по умолчанию|
|CWE-454|External Initialization of Trusted Variables or Data Stores|Инициализация доверенных переменных или хранилищ данных извне|
|CWE-455|Non-exit on Failed Initialization|Продолжение работы после сбоя инициализации|
|CWE-456|Missing Initialization of a Variable|Отсутствует инициализация переменной|
|CWE-457|Use of Uninitialized Variable|Использование неинициализированной переменной|
|CWE-458|DEPRECATED: Incorrect Initialization|НЕ РЕКОМЕНДУЕТСЯ: Некорректная инициализация|
|CWE-459|Incomplete Cleanup|Неполная очистка|
|CWE-460|Improper Cleanup on Thrown Exception|Некорректная очистка при возникновении исключения|
|CWE-461|Data Structure Issues|Уязвимости, связанные со структурой данных|
|CWE-462|Duplicate Key in Associative List (Alist)|Дублирование ключей в ассоциативном списке (alist)|
|CWE-463|Deletion of Data Structure Sentinel|Имеется возможность удаления сигнальной метки|
|CWE-464|Addition of Data Structure Sentinel|Имеется возможность добавления сигнальной метки|
|CWE-465|Pointer Issues|Уязвимости, связанные с указателями|
|CWE-466|Return of Pointer Value Outside of Expected Range|Возвращение указателя за пределами ожидаемого диапазона|
|CWE-467|Use of sizeof() on a Pointer Type|Использование sizeof() для типа указателя|
|CWE-468|Incorrect Pointer Scaling|Некорректное масштабирование указателей|
|CWE-469|Use of Pointer Subtraction to Determine Size|Вычитание указателей для определения размера|
|CWE-470|Use of Externally-Controlled Input to Select Classes or Code ('Unsafe Reflection')|Использование внешних входных данных для выбора класса или кода ("Небезопасное отражение")|
|CWE-471|Modification of Assumed-Immutable Data (MAID)|Изменение предположительно неизменяемых данных|
|CWE-472|External Control of Assumed-Immutable Web Parameter|Возможность изменения извне предположительно неизменяемых веб-параметров|
|CWE-473|PHP External Variable Modification|Изменение переменных сторонними источниками в PHP|
|CWE-474|Use of Function with Inconsistent Implementations|Использование функции с непоследовательной реализацией|
|CWE-475|Undefined Behavior for Input to API|Неопределенное поведение входных данных API|
|CWE-476|NULL Pointer Dereference|Разыменование нулевого указателя|
|CWE-477|Use of Obsolete Functions|Использование устаревших функций|
|CWE-478|Missing Default Case in Switch Statement|Отсутствие блока default в утверждении switch|
|CWE-479|Signal Handler Use of a Non-reentrant Function|Использование обработчиком сигнала нереентерабельной функции|
|CWE-480|Use of Incorrect Operator|Использование некорректного оператора|
|CWE-481|Assigning instead of Comparing|Назначение вместо сравнения|
|CWE-482|Comparing instead of Assigning|Сравнение вместо назначения|
|CWE-483|Incorrect Block Delimitation|Некорректное разграничение блоков|
|CWE-484|Omitted Break Statement in Switch|Отсутствие в switch утверждения break|
|CWE-485|Insufficient Encapsulation|Некорректная инкапсуляция|
|CWE-486|Comparison of Classes by Name|Сравнение классов по именам|
|CWE-487|Reliance on Package-level Scope|Зависимость от областей видимости уровня пакетов|
|CWE-488|Exposure of Data Element to Wrong Session|Раскрытие (доступность) данных другим сессиям|
|CWE-489|Leftover Debug Code|Присутствует код отладки|
|CWE-490|Mobile Code Issues|Уязвимости в мобильном коде|
|CWE-491|Public cloneable() Method Without Final ('Object Hijack')|Публичный метод cloneable() не объявлен как final ("Перехват объекта")|
|CWE-492|Use of Inner Class Containing Sensitive Data|Использование внутреннего класса, содержащего критичные данные|
|CWE-493|Critical Public Variable Without Final Modifier|Критичная общедоступная переменная без модификатора final|
|CWE-494|Download of Code Without Integrity Check|Загрузка кода без проверки его целостности|
|CWE-495|Private Array-Typed Field Returned From A Public Method|Общедоступный метод возвращает поле, относящееся к закрытому массиву|
|CWE-496|Public Data Assigned to Private Array-Typed Field|Общедоступные данные назначены полю, относящемуся к закрытому массиву|
|CWE-497|Exposure of System Data to an Unauthorized Control Sphere|Разглашение системных данных неавторизованным лицам|
|CWE-498|Cloneable Class Containing Sensitive Information|Клонируемый класс содержит конфиденциальные данные|
|CWE-499|Serializable Class Containing Sensitive Data|Сериализуемый класс содержит конфиденциальные данные|
|CWE-500|Public Static Field Not Marked Final|Публичное (public) статическое (static) поле не помечено как final|
|CWE-501|Trust Boundary Violation|Нарушение границ доверия|
|CWE-502|Deserialization of Untrusted Data|Десериализация недоверенных данных|
|CWE-503|DEPRECATED: Byte/Object Code|НЕ РЕКОМЕНДУЕТСЯ: Байтовый/объектный код|
|CWE-504|DEPRECATED: Motivation/Intent|НЕ РЕКОМЕНДУЕТСЯ: Мотивация/намерение|
|CWE-505|DEPRECATED: Intentionally Introduced Weakness|НЕ РЕКОМЕНДУЕТСЯ: Преднамеренно реализованный недостаток|
|CWE-506|Embedded Malicious Code|Внедренный вредоносный код|
|CWE-507|Trojan Horse|Троянское ПО|
|CWE-508|Non-Replicating Malicious Code|Нераспространяющийся вредоносный код|
|CWE-509|Replicating Malicious Code (Virus or Worm)|Распространяющийся вредоносный код (вирус или червь)|
|CWE-510|Trapdoor|Скрытые средства несанкционированного доступа|
|CWE-511|Logic/Time Bomb|Логическая или временная бомба|
|CWE-512|Spyware|Шпионское ПО|
|CWE-513|DEPRECATED: Intentionally Introduced Nonmalicious Weakness|НЕ РЕКОМЕНДУЕТСЯ: Преднамеренно реализованный неопасный недостаток|
|CWE-514|Covert Channel|Скрытый канал|
|CWE-515|Covert Storage Channel|Скрытый канал хранения данных|
|CWE-516|DEPRECATED (Duplicate): Covert Timing Channel|НЕ РЕКОМЕНДУЕТСЯ (дубликат): Скрытый временной канал|
|CWE-517|DEPRECATED: Other Intentional, Nonmalicious Weakness|НЕ РЕКОМЕНДУЕТСЯ: Прочие преднамеренно реализованные, неопасные недостатки|
|CWE-518|DEPRECATED: Inadvertently Introduced Weakness|НЕ РЕКОМЕНДУЕТСЯ: Непреднамеренно реализованный недостаток|
|CWE-519|.NET Environment Issues|Уязвимости, связанные со средой .NET|
|CWE-520|.NET Misconfiguration: Use of Impersonation|Ошибка в конфигурации .NET: использование олицетворения|
|CWE-521|Weak Password Requirements|Недостаточно надежный пароль|
|CWE-522|Insufficiently Protected Credentials|Недостаточно надежная защита учетных данных|
|CWE-523|Unprotected Transport of Credentials|Незащищенная передача учетных данных|
|CWE-524|Information Exposure Through Caching|Разглашение информации, связанное с кэшированием|
|CWE-525|Information Exposure Through Browser Caching|Разглашение информации, связанное с кэшированием в браузерах|
|CWE-526|Information Exposure Through Environmental Variables|Разглашение информации, связанное с переменными среды|
|CWE-527|Exposure of CVS Repository to an Unauthorized Control Sphere|Возможность непредусмотренного доступа к CVS-репозиторию|
|CWE-528|Exposure of Core Dump File to an Unauthorized Control Sphere|Возможность непредусмотренного доступа к дампу ядра|
|CWE-529|Exposure of Access Control List Files to an Unauthorized Control Sphere|Возможность непредусмотренного доступа к спискам контроля доступа|
|CWE-530|Exposure of Backup File to an Unauthorized Control Sphere|Возможность непредусмотренного доступа к резервным копиям|
|CWE-531|Information Exposure Through Test Code|Разглашение информации, связанное с тестовыми программами|
|CWE-532|Inclusion of Sensitive Information in Log Files|Включение важной информации в файлы журналов|
|CWE-533|DEPRECATED: Information Exposure Through Server Log Files|НЕ РЕКОМЕНДУЕТСЯ: Разглашение информации, связанное с файлами журналов серверов|
|CWE-534|DEPRECATED: Information Exposure Through Debug Log Files|НЕ РЕКОМЕНДУЕТСЯ: Разглашение информации, связанное с файлами журналов отладки|
|CWE-535|Information Exposure Through Shell Error Message|Разглашение информации, связанное с сообщениями об ошибках Shell|
|CWE-536|Information Exposure Through Servlet Runtime Error Message|Разглашение информации, связанное с сообщениями об ошибках сервлетов|
|CWE-537|Information Exposure Through Java Runtime Error Message|Разглашение информации, связанное с сообщениями об ошибках Java|
|CWE-538|File and Directory Information Exposure|Разглашение информации, связанное с файлами и каталогами|
|CWE-539|Information Exposure Through Persistent Cookies|Разглашение информации, связанное с постоянными куки-файлами|
|CWE-540|Information Exposure Through Source Code|Разглашение информации, связанное с исходным кодом|
|CWE-541|Information Exposure Through Include Source Code|Разглашение информации, связанное с исходным кодом включения|
|CWE-542|DEPRECATED: Information Exposure Through Cleanup Log Files|НЕ РЕКОМЕНДУЕТСЯ: Разглашение информации, связанное с файлами журналов очистки|
|CWE-543|Use of Singleton Pattern Without Synchronization in a Multithreaded Context|Использование шаблона "Одиночка" (Singleton) без синхронизации в многопоточном контексте|
|CWE-544|Missing Standardized Error Handling Mechanism|Отсутствует стандартизированный механизм обработки ошибок|
|CWE-545|DEPRECATED: Use of Dynamic Class Loading|НЕ РЕКОМЕНДУЕТСЯ: Использование динамической загрузки классов|
|CWE-546|Suspicious Comment|Уязвимости, связанные с комментариями|
|CWE-547|Use of Hard-coded, Security-relevant Constants|Уязвимости, связанные с жестко закодированными постоянными|
|CWE-548|Information Exposure Through Directory Listing|Разглашение информации, связанное с выводом файлов в каталогах|
|CWE-549|Missing Password Field Masking|Отображение символов пароля при вводе|
|CWE-550|Information Exposure Through Server Error Message|Разглашение информации в сообщении об ошибке сервера|
|CWE-551|Incorrect Behavior Order: Authorization Before Parsing and Canonicalization|Некорректный порядок действий: авторизация до обработки и нормализации|
|CWE-552|Files or Directories Accessible to External Parties|Непредусмотренный доступ к файлам или каталогам|
|CWE-553|Command Shell in Externally Accessible Directory|Командная оболочка в каталоге, доступном извне|
|CWE-554|ASP.NET Misconfiguration: Not Using Input Validation Framework|Ошибка в конфигурации ASP.NET: не используется фреймворк проверки входных данных|
|CWE-555|J2EE Misconfiguration: Plaintext Password in Configuration File|Ошибка в конфигурации J2EE: незашифрованный пароль в файле конфигурации|
|CWE-556|ASP.NET Misconfiguration: Use of Identity Impersonation|Ошибка в конфигурации ASP.NET: использование олицетворения учетных данных|
|CWE-557|Concurrency Issues|Уязвимости, связанные с одновременным использованием ресурсов|
|CWE-558|Use of getlogin() in Multithreaded Application|Использование getlogin() в многопоточном приложении|
|CWE-559|Often Misused: Arguments and Parameters|Некорректное использование аргументов или параметров|
|CWE-560|Use of umask() with chmod-style Argument|Использование umask() с chmod-подобным аргументом|
|CWE-561|Dead Code|Неиспользуемый код|
|CWE-562|Return of Stack Variable Address|Возвращение адреса переменной стека|
|CWE-563|Assignment to Variable without Use ('Unused Variable')|Назначение неиспользуемой переменной|
|CWE-564|SQL Injection: Hibernate|Внедрение SQL-кода с использованием Hibernate|
|CWE-565|Reliance on Cookies without Validation and Integrity Checking|Использование куки-файлов без подтверждения и проверки целостности|
|CWE-566|Authorization Bypass Through User-Controlled SQL Primary Key|Обход авторизации, используя первичный ключ SQL, контролируемый пользователем|
|CWE-567|Unsynchronized Access to Shared Data in a Multithreaded Context|Несинхронизированный доступ к общим данным в многопоточном контексте|
|CWE-568|finalize() Method Without super.finalize()|Метод finalize() не использует super.finalize()|
|CWE-569|Expression Issues|Уязвимости, связанные с некорректно написанными выражениями|
|CWE-570|Expression is Always False|Выражение всегда "ложно"|
|CWE-571|Expression is Always True|Выражение всегда "истинно"|
|CWE-572|Call to Thread run() instead of start()|Вызов метода run() вместо start()|
|CWE-573|Improper Following of Specification by Caller|Некорректное выполнение вызывающим требований спецификации|
|CWE-574|EJB Bad Practices: Use of Synchronization Primitives|Уязвимости EJB: использование примитивов синхронизации|
|CWE-575|EJB Bad Practices: Use of AWT Swing|Уязвимости EJB: использование AWT/Swing|
|CWE-576|EJB Bad Practices: Use of Java I/O|Уязвимости EJB: использование Java I/O|
|CWE-577|EJB Bad Practices: Use of Sockets|Уязвимости EJB: использование сокетов|
|CWE-578|EJB Bad Practices: Use of Class Loader|Уязвимости EJB: использование загрузчика классов|
|CWE-579|J2EE Bad Practices: Non-serializable Object Stored in Session|Уязвимости J2EE: хранение несериализуемых объектов в сессии|
|CWE-580|clone() Method Without super.clone()|Метод clone() не использует super.clone()|
|CWE-581|Object Model Violation: Just One of Equals and Hashcode Defined|Нарушение объектной модели: неодинаковые хеш-коды для одинаковых объектов|
|CWE-582|Array Declared Public, Final, and Static|Объявление public, final и static для массива|
|CWE-583|finalize() Method Declared Public|Открытый доступ к методу finalize()|
|CWE-584|Return Inside Finally Block|Return внутри блока finally|
|CWE-585|Empty Synchronized Block|Пустой синхронизированный блок|
|CWE-586|Explicit Call to Finalize()|Явный вызов метода finalize()|
|CWE-587|Assignment of a Fixed Address to a Pointer|Назначение указателю фиксированного адреса|
|CWE-588|Attempt to Access Child of a Non-structure Pointer|Попытка доступа к дочернему элементу неструктирированного указателя|
|CWE-589|Call to Non-ubiquitous API|Используемый API не является универсальным|
|CWE-590|Free of Memory not on the Heap|Освобождение не выделенной динамической памяти|
|CWE-591|Sensitive Data Storage in Improperly Locked Memory|Хранение важных данных в некорректно заблокированной памяти|
|CWE-592|DEPRECATED: Authentication Bypass Issues|НЕ РЕКОМЕНДУЕТСЯ: Уязвимости, связанные с обходом аутентификации|
|CWE-593|Authentication Bypass: OpenSSL CTX Object Modified after SSL Objects are Created|Обход аутентификации: изменение объекта OpenSSL CTX после создания SSL-объектов|
|CWE-594|J2EE Framework: Saving Unserializable Objects to Disk|Фреймворк J2EE: сохранение несериализуемых объектов на диск|
|CWE-595|Comparison of Object References Instead of Object Contents|Сравнение ссылок на объекты вместо содержимого объектов|
|CWE-596|DEPRECATED: Incorrect Semantic Object Comparison|НЕ РЕКОМЕНДУЕТСЯ: Некорректное сравнение семантических объектов|
|CWE-597|Use of Wrong Operator in String Comparison|Использование некорректного оператора при сравнении строк|
|CWE-598|Information Exposure Through Query Strings in GET Request|Разглашение информации через GET-запросы|
|CWE-599|Missing Validation of OpenSSL Certificate|Отсутствует проверка сертификатов OpenSSL|
|CWE-600|Uncaught Exception in Servlet |Необработанные исключения в сервлете|
|CWE-601|URL Redirection to Untrusted Site ('Open Redirect')|Перенаправление на небезопасный сайт ("Открытое перенаправление")|
|CWE-602|Client-Side Enforcement of Server-Side Security|Обеспечение безопасности сервера на стороне клиента|
|CWE-603|Use of Client-Side Authentication|Использование аутентификации на стороне пользователя|
|CWE-604|Deprecated Entries|Не рекомендуемые к использованию определения|
|CWE-605|Multiple Binds to the Same Port|Множественные привязки к одному порту|
|CWE-606|Unchecked Input for Loop Condition|Отсутствует проверка входных данных для циклических операций|
|CWE-607|Public Static Final Field References Mutable Object|Поле public static final ссылается на изменяемый объект|
|CWE-608|Struts: Non-private Field in ActionForm Class|Struts: общедоступное поле в классе ActionForm|
|CWE-609|Double-Checked Locking|Блокировка с двойной проверкой|
|CWE-610|Externally Controlled Reference to a Resource in Another Sphere|Внешняя ссылка, ведущая на недопустимый ресурс|
|CWE-611|Improper Restriction of XML External Entity Reference ('XXE')|Некорректное ограничение ссылок на внешние сущности XML|
|CWE-612|Information Exposure Through Indexing of Private Data|Разглашение информации, связанное с индексацией конфиденциальных данных|
|CWE-613|Insufficient Session Expiration|Некорректно настроенный срок действия сессий|
|CWE-614|Sensitive Cookie in HTTPS Session Without 'Secure' Attribute|Отсутствие в HTTPS-сессиях атрибута Secure у конфиденциальных куки-файлов|
|CWE-615|Information Exposure Through Comments|Разглашение информации в комментариях|
|CWE-616|Incomplete Identification of Uploaded File Variables (PHP)|Частичная идентификация переменных загружаемых файлов|
|CWE-617|Reachable Assertion|Несанкционированный вызов утверждения|
|CWE-618|Exposed Unsafe ActiveX Method|Доступность небезопасного метода ActiveX|
|CWE-619|Dangling Database Cursor ('Cursor Injection')|Подвисший курсор базы данных (Внедрение курсора)|
|CWE-620|Unverified Password Change|Смена пароля без подтверждения|
|CWE-621|Variable Extraction Error|Ошибка извлечения переменной|
|CWE-622|Improper Validation of Function Hook Arguments|Некорректная проверка аргументов при перехвате функций|
|CWE-623|Unsafe ActiveX Control Marked Safe For Scripting|Небезопасный элемент ActiveX помечен как "безопасный для сценариев"|
|CWE-624|Executable Regular Expression Error|Исполняемые регулярные выражения|
|CWE-625|Permissive Regular Expression|Некорректное ограничение регулярных выражений|
|CWE-626|Null Byte Interaction Error (Poison Null Byte)|Некорректная обработка нулевых байтов (Вредоносные нулевые байты)|
|CWE-627|Dynamic Variable Evaluation|Уязвимости, связанные с динамическими переменными|
|CWE-628|Function Call with Incorrectly Specified Arguments|Вызов функции, используя некорректно заданные аргументы|
|CWE-629|Weaknesses in OWASP Top Ten (2007)|Недостатки из Топ-10 OWASP (2007 г.)|
|CWE-630|DEPRECATED: Weaknesses Examined by SAMATE|НЕ РЕКОМЕНДУЕТСЯ: Недостатки, использовавшиеся в проекте SAMATE|
|CWE-631|DEPRECATED: Resource-specific Weaknesses|НЕ РЕКОМЕНДУЕТСЯ: Недостатки, характерные для определенных ресурсов|
|CWE-632|DEPRECATED: Weaknesses that Affect Files or Directories|НЕ РЕКОМЕНДУЕТСЯ: Недостатки, связанные с файлами или каталогами|
|CWE-633|DEPRECATED: Weaknesses that Affect Memory|НЕ РЕКОМЕНДУЕТСЯ: Недостатки, связанные с памятью|
|CWE-634|DEPRECATED: Weaknesses that Affect System Processes|НЕ РЕКОМЕНДУЕТСЯ: Недостатки, связанные с системными процессами|
|CWE-635|Weaknesses Originally Used by NVD from 2008 to 2016|Недостатки, использовавшиеся в базе данных NVD (с 2008 по 2016 гг.)|
|CWE-636|Not Failing Securely ('Failing Open')|Небезопасное восстановление после сбоя (Сбой с открытием доступа)|
|CWE-637|Unnecessary Complexity in Protection Mechanism (Not Using 'Economy of Mechanism')|Излишняя сложность защитного механизма (Неиспользование "простого механизма")|
|CWE-638|Not Using Complete Mediation|Отсутствие постоянного контроля доступа|
|CWE-639|Authorization Bypass Through User-Controlled Key|Обход авторизации, используя значение ключа пользователя|
|CWE-640|Weak Password Recovery Mechanism for Forgotten Password|Ненадежный механизм восстановления забытого пароля|
|CWE-641|Improper Restriction of Names for Files and Other Resources|Некорректные ограничения для имен фалов и ресурсов|
|CWE-642|External Control of Critical State Data|Возможность доступа к критичной информации о состоянии|
|CWE-643|Improper Neutralization of Data within XPath Expressions ('XPath Injection')|Некорректная нейтрализация данных в выражениях XPath (Внедрение Xpath)|
|CWE-644|Improper Neutralization of HTTP Headers for Scripting Syntax|Некорректная нейтрализация сценариев в HTTP-заголовках|
|CWE-645|Overly Restrictive Account Lockout Mechanism|Излишне ограничивающий механизм блокировки учетных записей|
|CWE-646|Reliance on File Name or Extension of Externally-Supplied File|Проверка загружаемых файлов по имени или расширению|
|CWE-647|Use of Non-Canonical URL Paths for Authorization Decisions|Использование неканонических URL-путей при авторизации|
|CWE-648|Incorrect Use of Privileged APIs|Некорректное использование привилегированных API|
|CWE-649|Reliance on Obfuscation or Encryption of Security-Relevant Inputs without Integrity Checking|Использование обфускации или шифрования критичных данных без проверки целостности|
|CWE-650|Trusting HTTP Permission Methods on the Server Side|Защита сервера на основе разрешений HTTP-методов|
|CWE-651|Information Exposure Through WSDL File|Разглашение информации, связанное с WSDL-файлами|
|CWE-652|Improper Neutralization of Data within XQuery Expressions ('XQuery Injection')|Некорректная нейтрализация данных в выражениях XQuery (Внедрение XQuery)|
|CWE-653|Insufficient Compartmentalization|Некорректная изоляция|
|CWE-654|Reliance on a Single Factor in a Security Decision|Использование однофакторной аутентификации|
|CWE-655|Insufficient Psychological Acceptability|Использование неприемлемого защитного механизма|
|CWE-656|Reliance on Security Through Obscurity|Защитный механизм на основе неизвестности|
|CWE-657|Violation of Secure Design Principles|Нарушение принципов безопасного проектирования|
|CWE-658|Weaknesses in Software Written in C|Недостатки в ПО, написанном на языке C|
|CWE-659|Weaknesses in Software Written in C++|Недостатки в ПО, написанном на C++|
|CWE-660|Weaknesses in Software Written in Java|Недостатки в ПО, написанном на Java|
|CWE-661|Weaknesses in Software Written in PHP|Недостатки в ПО, написанном на PHP|
|CWE-662|Improper Synchronization|Некорректная синхронизация|
|CWE-663|Use of a Non-reentrant Function in a Concurrent Context|Использование нереентерабельной функции в параллельном контексте|
|CWE-664|Improper Control of a Resource Through its Lifetime|Некорректное обращение с ресурсом на протяжении его жизненного цикла|
|CWE-665|Improper Initialization|Некорректная инициализация|
|CWE-666|Operation on Resource in Wrong Phase of Lifetime|Операции с ресурсами, выполняемые на некорректном этапе их жизненного цикла|
|CWE-667|Improper Locking|Некорректная блокировка|
|CWE-668|Exposure of Resource to Wrong Sphere|Возможность несанкционированного доступа к ресурсу|
|CWE-669|Incorrect Resource Transfer Between Spheres|Некорректная передача ресурса между окружениями|
|CWE-670|Always-Incorrect Control Flow Implementation|Некорректная реализация хода выполнения команд|
|CWE-671|Lack of Administrator Control over Security|Недоступность контроля над безопасностью для администратора|
|CWE-672|Operation on a Resource after Expiration or Release|Использование ресурса после окончания срока его действия или освобождения|
|CWE-673|External Influence of Sphere Definition|Возможность изменения области доступа|
|CWE-674|Uncontrolled Recursion|Неконтролируемая рекурсия|
|CWE-675|Duplicate Operations on Resource|Повторные операции с ресурсом|
|CWE-676|Use of Potentially Dangerous Function|Использование потенциально опасной функции|
|CWE-677|Weakness Base Elements|Базовые элементы недостатков|
|CWE-678|Composites|Комбинированные уязвимости|
|CWE-679|DEPRECATED: Chain Elements|НЕ РЕКОМЕНДУЕТСЯ: Элементы цепочки|
|CWE-680|Integer Overflow to Buffer Overflow|Целочисленное переполнение, приводящее к переполнению буфера|
|CWE-681|Incorrect Conversion between Numeric Types|Некорректное преобразование числовых типов|
|CWE-682|Incorrect Calculation|Некорректные расчеты|
|CWE-683|Function Call With Incorrect Order of Arguments|Вызов функции, используя некорректный порядок аргументов|
|CWE-684|Incorrect Provision of Specified Functionality|Некорректное обеспечение заявленных функций|
|CWE-685|Function Call With Incorrect Number of Arguments|Вызов функции, используя некорректное количество аргументов|
|CWE-686|Function Call With Incorrect Argument Type|Вызов функции, используя некорректный тип аргументов|
|CWE-687|Function Call With Incorrectly Specified Argument Value|Вызов функции, используя некорректно заданные значения аргументов|
|CWE-688|Function Call With Incorrect Variable or Reference as Argument|Вызов функции, используя некорректные переменные или ссылки в качестве аргумента|
|CWE-689|Permission Race Condition During Resource Copy|Состояние гонки разрешений при копировании ресурсов|
|CWE-690|Unchecked Return Value to NULL Pointer Dereference|Отсутствие проверки возвращаемого значения, приводящее к разыменованию нулевого указателя|
|CWE-691|Insufficient Control Flow Management|Некорректное управление ходом выполнения команд|
|CWE-692|Incomplete Blacklist to Cross-Site Scripting|Неполный черный список защиты от межсайтового выполнения сценариев|
|CWE-693|Protection Mechanism Failure|Некорректное использование защитных механизмов|
|CWE-694|Use of Multiple Resources with Duplicate Identifier|Одинаковый идентификатор для нескольких ресурсов|
|CWE-695|Use of Low-Level Functionality|Использование низкоуровневой функциональности|
|CWE-696|Incorrect Behavior Order|Некорректный порядок работы|
|CWE-697|Insufficient Comparison|Некорректное сравнение|
|CWE-698|Execution After Redirect (EAR)|Выполнение после перенаправления|
|CWE-699|Development Concepts|Уязвимости, связанные с разработкой ПО|
|CWE-700|Seven Pernicious Kingdoms|Уязвимости, относящиеся к таксономии "7 губительных царств"|
|CWE-701|Weaknesses Introduced During Design|Недостатки, появившиеся на этапе проектирования|
|CWE-702|Weaknesses Introduced During Implementation|Недостатки, появившиеся на этапе реализации|
|CWE-703|Improper Check or Handling of Exceptional Conditions|Некорректная проверка или обработка исключительных ситуаций|
|CWE-704|Incorrect Type Conversion or Cast|Некорректное преобразование или приведение типов|
|CWE-705|Incorrect Control Flow Scoping|Некорректный ход выполнения команд|
|CWE-706|Use of Incorrectly-Resolved Name or Reference|Некорректное разрешение имени или ссылки|
|CWE-707|Improper Enforcement of Message or Data Structure|Некорректное выполнение требований к структуре сообщений или данных|
|CWE-708|Incorrect Ownership Assignment|Некорректное назначение владельца|
|CWE-709|Named Chains|Именованные цепочки|
|CWE-710|Coding Standards Violation|Нарушение стандартов разработки кода|
|CWE-711|Weaknesses in OWASP Top Ten (2004)|Недостатки из Топ-10 OWASP (2004 г.)|
|CWE-712|OWASP Top Ten 2007 Category A1 - Cross Site Scripting (XSS)|Топ-10 OWASP 2007 Категория А1 - Межсайтовое выполнение сценариев|
|CWE-713|OWASP Top Ten 2007 Category A2 - Injection Flaws|Топ-10 OWASP 2007 Категория А2 - Внедрение|
|CWE-714|OWASP Top Ten 2007 Category A3 - Malicious File Execution|Топ-10 OWASP 2007 Категория А3 - Выполнение вредоносных файлов|
|CWE-715|OWASP Top Ten 2007 Category A4 - Insecure Direct Object Reference|Топ-10 OWASP 2007 Категория А4 - Небезопасные прямые ссылки на объекты|
|CWE-716|OWASP Top Ten 2007 Category A5 - Cross Site Request Forgery (CSRF)|Топ-10 OWASP 2007 Категория А5 - Межсайтовая подмена запросов|
|CWE-717|OWASP Top Ten 2007 Category A6 - Information Leakage and Improper Error Handling|Топ-10 OWASP 2007 Категория А6 - Утечка данных и некорректная обработка ошибок|
|CWE-718|OWASP Top Ten 2007 Category A7 - Broken Authentication and Session Management|Топ-10 OWASP 2007 Категория А7 - Недостатки аутентификации и управления сессиями|
|CWE-719|OWASP Top Ten 2007 Category A8 - Insecure Cryptographic Storage|Топ-10 OWASP 2007 Категория А8 - Ненадежная криптографическая защита|
|CWE-720|OWASP Top Ten 2007 Category A9 - Insecure Communications|Топ-10 OWASP 2007 Категория А9 - Небезопасные каналы связи|
|CWE-721|OWASP Top Ten 2007 Category A10 - Failure to Restrict URL Access|Топ-10 OWASP 2007 Категория А10 - Недостаточное ограничение доступа к URL-адресам|
|CWE-722|OWASP Top Ten 2004 Category A1 - Unvalidated Input|Топ-10 OWASP 2004 Категория А1 - Отсутствие проверки входных данных|
|CWE-723|OWASP Top Ten 2004 Category A2 - Broken Access Control|Топ-10 OWASP 2004 Категория А2 - Недостатки контроля доступа|
|CWE-724|OWASP Top Ten 2004 Category A3 - Broken Authentication and Session Management|Топ-10 OWASP 2004 Категория А3 - Недостатки аутентификации и управления сессиями|
|CWE-725|OWASP Top Ten 2004 Category A4 - Cross-Site Scripting (XSS) Flaws|Топ-10 OWASP 2004 Категория А4 - Межсайтовое выполнение сценариев|
|CWE-726|OWASP Top Ten 2004 Category A5 - Buffer Overflows|Топ-10 OWASP 2004 Категория А5 - Переполнение буфера|
|CWE-727|OWASP Top Ten 2004 Category A6 - Injection Flaws|Топ-10 OWASP 2004 Категория А6 - Внедрение|
|CWE-728|OWASP Top Ten 2004 Category A7 - Improper Error Handling|Топ-10 OWASP 2004 Категория А7 - Некорректная обработка ошибок|
|CWE-729|OWASP Top Ten 2004 Category A8 - Insecure Storage|Топ-10 OWASP 2004 Категория А8 - Небезопасное хранение|
|CWE-730|OWASP Top Ten 2004 Category A9 - Denial of Service|Топ-10 OWASP 2004 Категория А9 - Отказ в обслуживании|
|CWE-731|OWASP Top Ten 2004 Category A10 - Insecure Configuration Management|Топ-10 OWASP 2004 Категория А10 - Небезопасные настройки конфигурации|
|CWE-732|Incorrect Permission Assignment for Critical Resource|Некорректные разрешения для критически важных ресурсов|
|CWE-733|Compiler Optimization Removal or Modification of Security-critical Code|Удаление или изменение обеспечивающего безопасность кода при оптимизации компилятором|
|CWE-734|Weaknesses Addressed by the CERT C Secure Coding Standard|Недостатки из стандарта CERT по безопасному программированию на Си|
|CWE-735|CERT C Secure Coding Section 01 - Preprocessor (PRE)|CERT Безопасное программирование на Си, Раздел 01 — Препроцессор (PRE)|
|CWE-736|CERT C Secure Coding Section 02 - Declarations and Initialization (DCL)|CERT Безопасное программирование на Си, Раздел 02 — Объявления и инициализация (DCL)|
|CWE-737|CERT C Secure Coding Section 03 - Expressions (EXP)|CERT Безопасное программирование на Си, Раздел 03 — Выражения (EXP)|
|CWE-738|CERT C Secure Coding Section 04 - Integers (INT)|CERT Безопасное программирование на Си, Раздел 04 — Целые числа (INT)|
|CWE-739|CERT C Secure Coding Section 05 - Floating Point (FLP)|CERT Безопасное программирование на Си, Раздел 05 — Плавающая запятая (FLP)|
|CWE-740|CERT C Secure Coding Section 06 - Arrays (ARR)|CERT Безопасное программирование на Си, Раздел 06 — Массивы (ARR)|
|CWE-741|CERT C Secure Coding Section 07 - Characters and Strings (STR)|CERT Безопасное программирование на Cи, Раздел 07 — Символы и строки (STR)|
|CWE-742|CERT C Secure Coding Section 08 - Memory Management (MEM)|CERT Безопасное программирование на Cи, Раздел 08 — Управление памятью (MEM)|
|CWE-743|CERT C Secure Coding Section 09 - Input Output (FIO)|CERT Безопасное программирование на Си, Раздел 09 — Ввод-вывод (FIO)|
|CWE-744|CERT C Secure Coding Section 10 - Environment (ENV)|CERT Безопасное программирование на Cи, Раздел 10 — Среда (ENV)|
|CWE-745|CERT C Secure Coding Section 11 - Signals (SIG)|CERT Безопасное программирование на Си, Раздел 11 — Сигналы (SIG)|
|CWE-746|CERT C Secure Coding Section 12 - Error Handling (ERR)|CERT Безопасное программирование на Си, Раздел 12 — Обработка ошибок (ERR)|
|CWE-747|CERT C Secure Coding Section 49 - Miscellaneous (MSC)|CERT Безопасное программирование на Си, Раздел 49 — Прочее (MSC)|
|CWE-748|CERT C Secure Coding Section 50 - POSIX (POS)|CERT Безопасное программирование на Си, Раздел 50 — POSIX (POS)|
|CWE-749|Exposed Dangerous Method or Function|Доступны опасные методы или функции|
|CWE-750|Weaknesses in the 2009 CWE/SANS Top 25 Most Dangerous Programming Errors|Недостатки из Топ-25 самых опасных ошибок программирования по версии CWE/SANS 2009 года|
|CWE-751|2009 Top 25 - Insecure Interaction Between Components|Топ-25 — 2009: Небезопасное взаимодействие между компонентами|
|CWE-752|2009 Top 25 - Risky Resource Management|Топ-25 — 2009: Небезопасное управление ресурсами|
|CWE-753|2009 Top 25 - Porous Defenses|Топ-25 — 2009: Ненадежная защита|
|CWE-754|Improper Check for Unusual or Exceptional Conditions|Некорректная проверка наличия нестандартных условий или исключений|
|CWE-755|Improper Handling of Exceptional Conditions|Некорректная обработка исключений|
|CWE-756|Missing Custom Error Page|Отсутствует настроенная страница ошибки|
|CWE-757|Selection of Less-Secure Algorithm During Negotiation ('Algorithm Downgrade')|Выбор менее безопасного алгоритма при согласовании (Понижение надежности алгоритма)|
|CWE-758|Reliance on Undefined, Unspecified, or Implementation-Defined Behavior|Использование неопределенного, незаданного или зависящего от реализации поведения|
|CWE-759|Use of a One-Way Hash without a Salt|Использование односторонней хеш-функции без соли|
|CWE-760|Use of a One-Way Hash with a Predictable Salt|Использование односторонней хеш-функции с предсказуемой солью|
|CWE-761|Free of Pointer not at Start of Buffer|Освобождение указателя, находящегося не в начале буфера|
|CWE-762|Mismatched Memory Management Routines|Нарушение правил работы с памятью|
|CWE-763|Release of Invalid Pointer or Reference|Освобождение недопустимого указателя или ссылки|
|CWE-764|Multiple Locks of a Critical Resource|Частая блокировка критичного ресурса|
|CWE-765|Multiple Unlocks of a Critical Resource|Частая разблокировка критичного ресурса|
|CWE-766|Critical Variable Declared Public|Открытый доступ к критичной переменной|
|CWE-767|Access to Critical Private Variable via Public Method|Доступ к скрытой критичной переменной при помощи общедоступного (открытого) метода|
|CWE-768|Incorrect Short Circuit Evaluation|Некорректные упрощенные вычисления|
|CWE-769|DEPRECATED: File Descriptor Exhaustion|НЕ РЕКОМЕНДУЕТСЯ: Исчерпание файловых дескрипторов|
|CWE-770|Allocation of Resources Without Limits or Throttling|Выделение ресурсов без ограничений или регулировки|
|CWE-771|Missing Reference to Active Allocated Resource|Отсутствие ссылки на активный выделенный ресурс|
|CWE-772|Missing Release of Resource after Effective Lifetime|Удержание ресурса после его использования|
|CWE-773|Missing Reference to Active File Descriptor or Handle|Отсутствие ссылки на активный дескриптор файла|
|CWE-774|Allocation of File Descriptors or Handles Without Limits or Throttling|Выделение файловых дескрипторов без ограничений или регулировки|
|CWE-775|Missing Release of File Descriptor or Handle after Effective Lifetime|Удержание файлового дескриптора после его использования|
|CWE-776|Improper Restriction of Recursive Entity References in DTDs ('XML Entity Expansion')|Некорректное ограничение рекурсивных ссылок на сущности в определении типа документа (Распространение сущности XML)|
|CWE-777|Regular Expression without Anchors|Регулярные выражения без якорей|
|CWE-778|Insufficient Logging|Некорректное журналирование|
|CWE-779|Logging of Excessive Data|Избыточное журналирование|
|CWE-780|Use of RSA Algorithm without OAEP|Использование алгоритма RSA без OAEP|
|CWE-781|Improper Address Validation in IOCTL with METHOD_NEITHER I/O Control Code|Некорректная проверка адресов в IOCTL, использующем METHOD_NEITHER для управления вводом-выводом|
|CWE-782|Exposed IOCTL with Insufficient Access Control|Некорректное ограничение доступа к IOCTL|
|CWE-783|Operator Precedence Logic Error|Уязвимость, связанная с приоритетом операторов|
|CWE-784|Reliance on Cookies without Validation and Integrity Checking in a Security Decision|Защитный механизм на основе куки-файлов без подтверждения и проверки их целостности|
|CWE-785|Use of Path Manipulation Function without Maximum-sized Buffer|Использование некорректного размера буфера для функций обработки путей|
|CWE-786|Access of Memory Location Before Start of Buffer|Доступ к разделу памяти перед началом буфера|
|CWE-787|Out-of-bounds Write|Запись за границами буфера|
|CWE-788|Access of Memory Location After End of Buffer|Доступ к областям памяти за пределами буфера|
|CWE-789|Uncontrolled Memory Allocation|Неконтролируемое выделение памяти|
|CWE-790|Improper Filtering of Special Elements|Некорректная фильтрация специальных элементов|
|CWE-791|Incomplete Filtering of Special Elements|Неполная фильтрация специальных элементов|
|CWE-792|Incomplete Filtering of One or More Instances of Special Elements|Неполная фильтрация одного или нескольких экземпляров специальных элементов|
|CWE-793|Only Filtering One Instance of a Special Element|Фильтрация только одного экземпляра специальных элементов|
|CWE-794|Incomplete Filtering of Multiple Instances of Special Elements|Неполная фильтрация нескольких экземпляров специальных элементов|
|CWE-795|Only Filtering Special Elements at a Specified Location|Фильтрация специальных элементов только в указанных позициях|
|CWE-796|Only Filtering Special Elements Relative to a Marker|Фильтрация специальных элементов на основе маркеров|
|CWE-797|Only Filtering Special Elements at an Absolute Position|Фильтрация специальных элементов на основе расположения|
|CWE-798|Use of Hard-coded Credentials|Использование жестко закодированных учетных данных|
|CWE-799|Improper Control of Interaction Frequency|Некорректное ограничение частоты взаимодействия|
|CWE-800|Weaknesses in the 2010 CWE/SANS Top 25 Most Dangerous Programming Errors|Недостатки из Топ-25 самых опасных ошибок программирования по версии CWE/SANS 2010 года|
|CWE-801|2010 Top 25 - Insecure Interaction Between Components|Топ-25 — 2010: Небезопасное взаимодействие между компонентами|
|CWE-802|2010 Top 25 - Risky Resource Management|Топ-25 — 2010: Небезопасное управление ресурсами|
|CWE-803|2010 Top 25 - Porous Defenses|Топ-25 — 2010: Ненадежная защита|
|CWE-804|Guessable CAPTCHA|Легко решаемая задача CAPTCHA|
|CWE-805|Buffer Access with Incorrect Length Value|Доступ к памяти за пределами буфера|
|CWE-806|Buffer Access Using Size of Source Buffer|Использование размера исходного буфера при обращении к целевому буферу|
|CWE-807|Reliance on Untrusted Inputs in a Security Decision|Использование недоверенных входных данных при обеспечении безопасности|
|CWE-808|2010 Top 25 - Weaknesses On the Cusp|Топ-25 — 2010: Недостатки из списка кандидатов|
|CWE-809|Weaknesses in OWASP Top Ten (2010)|Недостатки из Топ-10 OWASP (2010 г.)|
|CWE-810|OWASP Top Ten 2010 Category A1 - Injection|Топ-10 OWASP — 2010 Категория А1 - Внедрение|
|CWE-811|OWASP Top Ten 2010 Category A2 - Cross-Site Scripting (XSS)|Топ-10 OWASP — 2010 Категория А2 - Межсайтовое выполнение сценариев (XSS)|
|CWE-812|OWASP Top Ten 2010 Category A3 - Broken Authentication and Session Management|Топ-10 OWASP — 2010 Категория А3 - Недостатки аутентификации и управления сессиями|
|CWE-813|OWASP Top Ten 2010 Category A4 - Insecure Direct Object References|Топ-10 OWASP — 2010 Категория А4 - Небезопасные прямые ссылки на объекты|
|CWE-814|OWASP Top Ten 2010 Category A5 - Cross-Site Request Forgery(CSRF)|Топ-10 OWASP — 2010 Категория А5 - Межсайтовая подмена запросов (CSRF)|
|CWE-815|OWASP Top Ten 2010 Category A6 - Security Misconfiguration|Топ-10 OWASP — 2010 Категория А6 - Некорректная настройка параметров безопасности|
|CWE-816|OWASP Top Ten 2010 Category A7 - Insecure Cryptographic Storage|Топ-10 OWASP — 2010 Категория А7 - Ненадежное шифрование хранимых данных|
|CWE-817|OWASP Top Ten 2010 Category A8 - Failure to Restrict URL Access|Топ-10 OWASP — 2010 Категория А8 - Некорректное ограничение URL-доступа|
|CWE-818|OWASP Top Ten 2010 Category A9 - Insufficient Transport Layer Protection|Топ-10 OWASP — 2010 Категория А9 - Недостаточная защита транспортного уровня|
|CWE-819|OWASP Top Ten 2010 Category A10 - Unvalidated Redirects and Forwards|Топ-10 OWASP — 2010 Категория А10 - Непроверенные перенаправления и переадресации|
|CWE-820|Missing Synchronization|Отсутствие синхронизации|
|CWE-821|Incorrect Synchronization|Некорректная синхронизация|
|CWE-822|Untrusted Pointer Dereference|Разыменование непроверенного указателя|
|CWE-823|Use of Out-of-range Pointer Offset|Использование для указателя смещения за пределами назначенного диапазона|
|CWE-824|Access of Uninitialized Pointer|Обращение к неинициализированному указателю|
|CWE-825|Expired Pointer Dereference|Разыменование недействительного указателя|
|CWE-826|Premature Release of Resource During Expected Lifetime|Преждевременное освобождение ресурса|
|CWE-827|Improper Control of Document Type Definition|Некорректные ограничения для определения типа документов (DTD)|
|CWE-828|Signal Handler with Functionality that is not Asynchronous-Safe|Обработчик сигналов нарушает принципы асинхронного использования ресурсов|
|CWE-829|Inclusion of Functionality from Untrusted Control Sphere|Использование функций недоверенных источников|
|CWE-830|Inclusion of Web Functionality from an Untrusted Source|Использование веб-функции из недоверенного источника|
|CWE-831|Signal Handler Function Associated with Multiple Signals|Функция-обработчик сигнала используется для нескольких сигналов|
|CWE-832|Unlock of a Resource that is not Locked|Разблокировка незаблокированного ресурса|
|CWE-833|Deadlock|Взаимоблокировка|
|CWE-834|Excessive Iteration|Излишние итерации|
|CWE-835|Loop with Unreachable Exit Condition ('Infinite Loop')|Бесконечный цикл (Зацикливание)|
|CWE-836|Use of Password Hash Instead of Password for Authentication|Использование хеш-суммы пароля вместо пароля для аутентификации|
|CWE-837|Improper Enforcement of a Single, Unique Action|Некорректная проверка однократности выполнения действия|
|CWE-838|Inappropriate Encoding for Output Context|Некорректная кодировка для выходных данных|
|CWE-839|Numeric Range Comparison Without Minimum Check|Отсутствует проверка на соответствие минимальному значению диапазона|
|CWE-840|Business Logic Errors|Ошибки в бизнес-логике|
|CWE-841|Improper Enforcement of Behavioral Workflow|Некорректный контроль за последовательностью выполняемых действий|
|CWE-842|Placement of User into Incorrect Group|Некорректное включение пользователя в группу|
|CWE-843|Access of Resource Using Incompatible Type ('Type Confusion')|Доступ к ресурсам с использованием несовместимых типов (Смешение типов)|
|CWE-844|Weaknesses Addressed by the CERT Java Secure Coding Standard|Недостатки из стандарта CERT по безопасному программированию на Java|
|CWE-845|CERT Java Secure Coding Section 00 - Input Validation and Data Sanitization (IDS)|CERT Безопасное программирование на Java, Раздел 00 — Проверка и обработка входных данных (IDS)|
|CWE-846|CERT Java Secure Coding Section 01 - Declarations and Initialization (DCL)|CERT Безопасное программирование на Java, Раздел 01 — Объявления и инициализация (DCL)|
|CWE-847|CERT Java Secure Coding Section 02 - Expressions (EXP)|CERT Безопасное программирование на Java, Раздел 02 — Выражения (EXP)|
|CWE-848|CERT Java Secure Coding Section 03 - Numeric Types and Operations (NUM)|CERT Безопасное программирование на Java, Раздел 03 — Числовые типы и операции (NUM)|
|CWE-849|CERT Java Secure Coding Section 04 - Object Orientation (OBJ)|CERT Безопасное программирование на Java, Раздел 04 — Объектная ориентация (OBJ)|
|CWE-850|CERT Java Secure Coding Section 05 - Methods (MET)|CERT Безопасное программирование на Java, Раздел 05 — Методы (MET)|
|CWE-851|CERT Java Secure Coding Section 06 - Exceptional Behavior (ERR)|CERT Безопасное программирование на Java, Раздел 06 — Необычное поведение (ERR)|
|CWE-852|CERT Java Secure Coding Section 07 - Visibility and Atomicity (VNA)|CERT Безопасное программирование на Java, Раздел 07 — Видимость и атомарность (VNA)|
|CWE-853|CERT Java Secure Coding Section 08 - Locking (LCK)|CERT Безопасное программирование на Java, Раздел 08 — Блокировка (LCK)|
|CWE-854|CERT Java Secure Coding Section 09 - Thread APIs (THI)|CERT Безопасное программирование на Java, Раздел 09 — API потоков (THI)|
|CWE-855|CERT Java Secure Coding Section 10 - Thread Pools (TPS)|CERT Безопасное программирование на Java, Раздел 10 — Пулы потоков (TPS)|
|CWE-856|CERT Java Secure Coding Section 11 - Thread-Safety Miscellaneous (TSM)|CERT Безопасное программирование на Java, Раздел 11 — Прочие вопросы по безопасности потоков (TSM)|
|CWE-857|CERT Java Secure Coding Section 12 - Input Output (FIO)|CERT Безопасное программирование на Java, Раздел 12 — Ввод-вывод (FIO)|
|CWE-858|CERT Java Secure Coding Section 13 - Serialization (SER)|CERT Безопасное программирование на Java, Раздел 13 — Сериализация (SER)|
|CWE-859|CERT Java Secure Coding Section 14 - Platform Security (SEC)|CERT Безопасное программирование на Java, Раздел 14 — Безопасность платформы (SEC)|
|CWE-860|CERT Java Secure Coding Section 15 - Runtime Environment (ENV)|CERT Безопасное программирование на Java, Раздел 15 — Среда выполнения (ENV)|
|CWE-861|CERT Java Secure Coding Section 49 - Miscellaneous (MSC)|CERT Безопасное программирование на Java, Раздел 49 — Прочее (MSC)|
|CWE-862|Missing Authorization|Отсутствие авторизации|
|CWE-863|Incorrect Authorization|Некорректная авторизация|
|CWE-864|2011 Top 25 - Insecure Interaction Between Components|Топ-25 — 2011: Небезопасное взаимодействие между компонентами|
|CWE-865|2011 Top 25 - Risky Resource Management|Топ-25 — 2011: Небезопасное управление ресурсами|
|CWE-866|2011 Top 25 - Porous Defenses|Топ-25 — 2011: Ненадежная защита|
|CWE-867|2011 Top 25 - Weaknesses On the Cusp|Топ-25 — 2011: Недостатки из списка кандидатов|
|CWE-868|Weaknesses Addressed by the CERT C++ Secure Coding Standard|Недостатки из стандарта CERT по безопасному программированию на C++|
|CWE-869|CERT C++ Secure Coding Section 01 - Preprocessor (PRE)|CERT Безопасное программирование на C++, Раздел 01 — Препроцессор (PRE)|
|CWE-870|CERT C++ Secure Coding Section 02 - Declarations and Initialization (DCL)|CERT Безопасное программирование на C++, Раздел 02 — Объявления и инициализация (DCL)|
|CWE-871|CERT C++ Secure Coding Section 03 - Expressions (EXP)|CERT Безопасное программирование на C++, Раздел 03 — Выражения (EXP)|
|CWE-872|CERT C++ Secure Coding Section 04 - Integers (INT)|CERT Безопасное программирование на C++, Раздел 04 — Целые числа (INT)|
|CWE-873|CERT C++ Secure Coding Section 05 - Floating Point Arithmetic (FLP)|CERT Безопасное программирование на C++, Раздел 05 — Арифметические операции с плавающей запятой (FLP)|
|CWE-874|CERT C++ Secure Coding Section 06 - Arrays and the STL (ARR)|CERT Безопасное программирование на C++, Раздел 06 — Массивы и стандартная библиотека STL (ARR)|
|CWE-875|CERT C++ Secure Coding Section 07 - Characters and Strings (STR)|CERT Безопасное программирование на C++, Раздел 07 — Символы и строки (STR)|
|CWE-876|CERT C++ Secure Coding Section 08 - Memory Management (MEM)|CERT Безопасное программирование на C++, Раздел 08 — Управление памятью (MEM)|
|CWE-877|CERT C++ Secure Coding Section 09 - Input Output (FIO)|CERT Безопасное программирование на C++, Раздел 09 — Ввод-вывод (FIO)|
|CWE-878|CERT C++ Secure Coding Section 10 - Environment (ENV)|CERT Безопасное программирование на C++, Раздел 10 — Среда (ENV)|
|CWE-879|CERT C++ Secure Coding Section 11 - Signals (SIG)|CERT Безопасное программирование на C++, Раздел 11 — Сигналы (SIG)|
|CWE-880|CERT C++ Secure Coding Section 12 - Exceptions and Error Handling (ERR)|CERT Безопасное программирование на C++, Раздел 12 — Обработка ошибок и исключений (ERR)|
|CWE-881|CERT C++ Secure Coding Section 13 - Object Oriented Programming (OOP)|CERT Безопасное программирование на C++, Раздел 13 — Объектно-ориентированное программирование (OOP)|
|CWE-882|CERT C++ Secure Coding Section 14 - Concurrency (CON)|CERT Безопасное программирование на C++, Раздел 14 — Параллелизм (CON)|
|CWE-883|CERT C++ Secure Coding Section 49 - Miscellaneous (MSC)|CERT Безопасное программирование на C++, Раздел 49 — Прочее (MSC)|
|CWE-884|CWE Cross-section|Сводная таблица CWE|
|CWE-885|SFP Primary Cluster: Risky Values|Модели программных сбоев (первичный кластер): небезопасные значения|
|CWE-886|SFP Primary Cluster: Unused entities|Модели программных сбоев (первичный кластер): неиспользуемые сущности|
|CWE-887|SFP Primary Cluster: API|Модели программных сбоев (первичный кластер): API|
|CWE-888|Software Fault Pattern (SFP) Clusters|Кластеры моделей программных сбоев|
|CWE-889|SFP Primary Cluster: Exception Management|Модели программных сбоев (первичный кластер): управление исключениями|
|CWE-890|SFP Primary Cluster: Memory Access|Модели программных сбоев (первичный кластер): доступ к памяти|
|CWE-891|SFP Primary Cluster: Memory Management|Модели программных сбоев (первичный кластер): управление памятью|
|CWE-892|SFP Primary Cluster: Resource Management|Модели программных сбоев (первичный кластер): управление ресурсами|
|CWE-893|SFP Primary Cluster: Path Resolution|Модели программных сбоев (первичный кластер): разрешение пути|
|CWE-894|SFP Primary Cluster: Synchronization|Модели программных сбоев (первичный кластер): синхронизация|
|CWE-895|SFP Primary Cluster: Information Leak|Модели программных сбоев (первичный кластер): утечка данных|
|CWE-896|SFP Primary Cluster: Tainted Input|Модели программных сбоев (первичный кластер): подмена входных данных|
|CWE-897|SFP Primary Cluster: Entry Points|Модели программных сбоев (первичный кластер): точки входа|
|CWE-898|SFP Primary Cluster: Authentication|Модели программных сбоев (первичный кластер): аутентификация|
|CWE-899|SFP Primary Cluster: Access Control|Модели программных сбоев (первичный кластер): управление доступом|
|CWE-900|Weaknesses in the 2011 CWE/SANS Top 25 Most Dangerous Software Errors|Недостатки из Топ-25 самых опасных ошибок в программном обеспечении по версии CWE/SANS 2011 года|
|CWE-901|SFP Primary Cluster: Privilege|Модели программных сбоев (первичный кластер): привилегии|
|CWE-902|SFP Primary Cluster: Channel|Модели программных сбоев (первичный кластер): каналы|
|CWE-903|SFP Primary Cluster: Cryptography|Модели программных сбоев (первичный кластер): криптография|
|CWE-904|SFP Primary Cluster: Malware|Модели программных сбоев (первичный кластер): вредоносное ПО|
|CWE-905|SFP Primary Cluster: Predictability|Модели программных сбоев (первичный кластер): прогнозируемость|
|CWE-906|SFP Primary Cluster: UI|Модели программных сбоев (первичный кластер): интерфейс пользователя|
|CWE-907|SFP Primary Cluster: Other|Модели программных сбоев (первичный кластер): прочее|
|CWE-908|Use of Uninitialized Resource|Использование неинициализированных ресурсов|
|CWE-909|Missing Initialization of Resource|Отсутствует инициализация ресурса|
|CWE-910|Use of Expired File Descriptor|Использование недействительного файлового дескриптора|
|CWE-911|Improper Update of Reference Count|Некорректное обновление данных счетчика ссылок|
|CWE-912|Hidden Functionality|Скрытые функции|
|CWE-913|Improper Control of Dynamically-Managed Code Resources|Некорректное управление динамически изменяемыми программными ресурсами|
|CWE-914|Improper Control of Dynamically-Identified Variables|Некорректное управление динамически задаваемыми переменными|
|CWE-915|Improperly Controlled Modification of Dynamically-Determined Object Attributes|Некорректный контроль над изменением динамически определяемых атрибутов объектов|
|CWE-916|Use of Password Hash With Insufficient Computational Effort|Создание недостаточно сложных хеш-сумм паролей|
|CWE-917|Improper Neutralization of Special Elements used in an Expression Language Statement ('Expression Language Injection')|Некорректная нейтрализация специальных элементов, используемых в утверждениях языка выражений (Внедрение кода языка выражений)|
|CWE-918|Server-Side Request Forgery (SSRF)|Подделка запроса со стороны сервера|
|CWE-919|Weaknesses in Mobile Applications|Недостатки в мобильных приложениях|
|CWE-920|Improper Restriction of Power Consumption|Некорректное ограничение потребляемой мощности|
|CWE-921|Storage of Sensitive Data in a Mechanism without Access Control|Хранение важных данных без обеспечения контроля доступа|
|CWE-922|Insecure Storage of Sensitive Information|Небезопасное хранение критичных данных|
|CWE-923|Improper Restriction of Communication Channel to Intended Endpoints|Некорректная проверка конечной точки для канала связи|
|CWE-924|Improper Enforcement of Message Integrity During Transmission in a Communication Channel|Некорректная проверка целостности сообщения, полученного по каналу связи|
|CWE-925|Improper Verification of Intent by Broadcast Receiver|Некорректная проверка намерений широковещательным приемником|
|CWE-926|Improper Export of Android Application Components|Некорректный экспорт компонентов Андроид-приложением|
|CWE-927|Use of Implicit Intent for Sensitive Communication|Неявное намерение передавать критичные данные|
|CWE-928|Weaknesses in OWASP Top Ten (2013)|Недостатки из Топ-10 OWASP (2013 г.)|
|CWE-929|OWASP Top Ten 2013 Category A1 - Injection|Топ-10 OWASP — 2013 Категория A1 - Внедрение|
|CWE-930|OWASP Top Ten 2013 Category A2 - Broken Authentication and Session Management|Топ-10 OWASP — 2013 Категория A2 - Недостатки аутентификации и управления сессиями|
|CWE-931|OWASP Top Ten 2013 Category A3 - Cross-Site Scripting (XSS)|Топ-10 OWASP — 2013 Категория A3 - Межсайтовое выполнение сценариев (XSS)|
|CWE-932|OWASP Top Ten 2013 Category A4 - Insecure Direct Object References|Топ-10 OWASP — 2013 Категория A4 - Небезопасные прямые ссылки на объекты|
|CWE-933|OWASP Top Ten 2013 Category A5 - Security Misconfiguration|Топ-10 OWASP — 2013 Категория A5 - Некорректная настройка параметров безопасности|
|CWE-934|OWASP Top Ten 2013 Category A6 - Sensitive Data Exposure|Топ-10 OWASP — 2013 Категория A6 - Разглашение конфиденциальных данных|
|CWE-935|OWASP Top Ten 2013 Category A7 - Missing Function Level Access Control|Топ-10 OWASP — 2013 Категория A7 - Отсутствие контроля доступа на функциональном уровне|
|CWE-936|OWASP Top Ten 2013 Category A8 - Cross-Site Request Forgery (CSRF)|Топ-10 OWASP — 2013 Категория A8 - Межсайтовая подмена запросов (CSRF)|
|CWE-937|OWASP Top Ten 2013 Category A9 - Using Components with Known Vulnerabilities|Топ-10 OWASP — 2013 Категория A9 - Использование компонентов с известными уязвимостями|
|CWE-938|OWASP Top Ten 2013 Category A10 - Unvalidated Redirects and Forwards|Топ-10 OWASP — 2013 Категория A10 - Непроверенные перенаправления и переадресации|
|CWE-939|Improper Authorization in Handler for Custom URL Scheme|Некорректная авторизация в обработчике нестандартных схем URL|
|CWE-940|Improper Verification of Source of a Communication Channel|Некорректная проверка источника для канала связи|
|CWE-941|Incorrectly Specified Destination in a Communication Channel|Некорректное определение адреса назначения для канала связи|
|CWE-942|Overly Permissive Cross-domain Whitelist|Некорректный междоменный белый список|
|CWE-943|Improper Neutralization of Special Elements in Data Query Logic|Некорректная нейтрализация специальных элементов в запросах данных|
|CWE-944|SFP Secondary Cluster: Access Management|Модели программных сбоев (вторичный кластер): управление доступом|
|CWE-945|SFP Secondary Cluster: Insecure Resource Access|Модели программных сбоев (вторичный кластер): небезопасный доступ к ресурсам|
|CWE-946|SFP Secondary Cluster: Insecure Resource Permissions|Модели программных сбоев (вторичный кластер): небезопасные разрешения для ресурсов|
|CWE-947|SFP Secondary Cluster: Authentication Bypass|Модели программных сбоев (вторичный кластер): обход аутентификации|
|CWE-948|SFP Secondary Cluster: Digital Certificate|Модели программных сбоев (вторичный кластер): цифровой сертификат|
|CWE-949|SFP Secondary Cluster: Faulty Endpoint Authentication|Модели программных сбоев (вторичный кластер): некорректная аутентификация конечной точки|
|CWE-950|SFP Secondary Cluster: Hardcoded Sensitive Data|Модели программных сбоев (вторичный кластер): жестко закодированные критичные данные|
|CWE-951|SFP Secondary Cluster: Insecure Authentication Policy|Модели программных сбоев (вторичный кластер): небезопасная политика аутентификации|
|CWE-952|SFP Secondary Cluster: Missing Authentication|Модели программных сбоев (вторичный кластер): отсутствует аутентификация|
|CWE-953|SFP Secondary Cluster: Missing Endpoint Authentication|Модели программных сбоев (вторичный кластер): отсутствует аутентификация конечной точки|
|CWE-954|SFP Secondary Cluster: Multiple Binds to the Same Port|Модели программных сбоев (вторичный кластер): множественные привязки к одному порту|
|CWE-955|SFP Secondary Cluster: Unrestricted Authentication|Модели программных сбоев (вторичный кластер): аутентификация без ограничений|
|CWE-956|SFP Secondary Cluster: Channel Attack|Модели программных сбоев (вторичный кластер): атака по каналам|
|CWE-957|SFP Secondary Cluster: Protocol Error|Модели программных сбоев (вторичный кластер): ошибки в протоколе|
|CWE-958|SFP Secondary Cluster: Broken Cryptography|Модели программных сбоев (вторичный кластер): скомпрометированный криптографический алгоритм|
|CWE-959|SFP Secondary Cluster: Weak Cryptography|Модели программных сбоев (вторичный кластер): ненадежный криптографический алгоритм|
|CWE-960|SFP Secondary Cluster: Ambiguous Exception Type|Модели программных сбоев (вторичный кластер): неоднозначный тип исключения|
|CWE-961|SFP Secondary Cluster: Incorrect Exception Behavior|Модели программных сбоев (вторичный кластер): некорректные действия при исключениях|
|CWE-962|SFP Secondary Cluster: Unchecked Status Condition|Модели программных сбоев (вторичный кластер): отсутствует проверка состояния|
|CWE-963|SFP Secondary Cluster: Exposed Data|Модели программных сбоев (вторичный кластер): разглашение данных|
|CWE-964|SFP Secondary Cluster: Exposure Temporary File|Модели программных сбоев (вторичный кластер): разглашение данных, связанное с временными файлами|
|CWE-965|SFP Secondary Cluster: Insecure Session Management|Модели программных сбоев (вторичный кластер): небезопасное управление сессиями|
|CWE-966|SFP Secondary Cluster: Other Exposures|Модели программных сбоев (вторичный кластер): возможные способы разглашения данных|
|CWE-967|SFP Secondary Cluster: State Disclosure|Модели программных сбоев (вторичный кластер): разглашение данных о состоянии|
|CWE-968|SFP Secondary Cluster: Covert Channel|Модели программных сбоев (вторичный кластер): скрытый канал|
|CWE-969|SFP Secondary Cluster: Faulty Memory Release|Модели программных сбоев (вторичный кластер): некорректное освобождение памяти|
|CWE-970|SFP Secondary Cluster: Faulty Buffer Access|Модели программных сбоев (вторичный кластер): некорректный доступ к буферу|
|CWE-971|SFP Secondary Cluster: Faulty Pointer Use|Модели программных сбоев (вторичный кластер): некорректное использование указателей|
|CWE-972|SFP Secondary Cluster: Faulty String Expansion|Модели программных сбоев (вторичный кластер): некорректное распространение строк|
|CWE-973|SFP Secondary Cluster: Improper NULL Termination|Модели программных сбоев (вторичный кластер): некорректное использование нулевых символов|
|CWE-974|SFP Secondary Cluster: Incorrect Buffer Length Computation|Модели программных сбоев (вторичный кластер): некорректный расчет размера буфера|
|CWE-975|SFP Secondary Cluster: Architecture|Модели программных сбоев (вторичный кластер): архитектура|
|CWE-976|SFP Secondary Cluster: Compiler|Модели программных сбоев (вторичный кластер): компилятор|
|CWE-977|SFP Secondary Cluster: Design|Модели программных сбоев (вторичный кластер): проектирование|
|CWE-978|SFP Secondary Cluster: Implementation|Модели программных сбоев (вторичный кластер): реализация|
|CWE-979|SFP Secondary Cluster: Failed Chroot Jail|Модели программных сбоев (вторичный кластер): неудачная реализация chroot jail|
|CWE-980|SFP Secondary Cluster: Link in Resource Name Resolution|Модели программных сбоев (вторичный кластер): ссылка в разрешении имен ресурсов|
|CWE-981|SFP Secondary Cluster: Path Traversal|Модели программных сбоев (вторичный кластер): подмена пути|
|CWE-982|SFP Secondary Cluster: Failure to Release Resource|Модели программных сбоев (вторичный кластер): некорректное освобождение ресурсов|
|CWE-983|SFP Secondary Cluster: Faulty Resource Use|Модели программных сбоев (вторичный кластер): некорректное использование ресурсов|
|CWE-984|SFP Secondary Cluster: Life Cycle|Модели программных сбоев (вторичный кластер): жизненный цикл|
|CWE-985|SFP Secondary Cluster: Unrestricted Consumption|Модели программных сбоев (вторичный кластер): неконтролируемое использование|
|CWE-986|SFP Secondary Cluster: Missing Lock|Модели программных сбоев (вторичный кластер): отсутствует блокировка|
|CWE-987|SFP Secondary Cluster: Multiple Locks/Unlocks|Модели программных сбоев (вторичный кластер): частые блокировки/разблокировки|
|CWE-988|SFP Secondary Cluster: Race Condition Window|Модели программных сбоев (вторичный кластер): состояние гонки|
|CWE-989|SFP Secondary Cluster: Unrestricted Lock|Модели программных сбоев (вторичный кластер): неконтролируемая блокировка|
|CWE-990|SFP Secondary Cluster: Tainted Input to Command|Модели программных сбоев (вторичный кластер): подмена данных для команды|
|CWE-991|SFP Secondary Cluster: Tainted Input to Environment|Модели программных сбоев (вторичный кластер): подмена данных для среды|
|CWE-992|SFP Secondary Cluster: Faulty Input Transformation|Модели программных сбоев (вторичный кластер): некорректное преобразование входных данных|
|CWE-993|SFP Secondary Cluster: Incorrect Input Handling|Модели программных сбоев (вторичный кластер): некорректная обработка входных данных|
|CWE-994|SFP Secondary Cluster: Tainted Input to Variable|Модели программных сбоев (вторичный кластер): подмена данных для переменной|
|CWE-995|SFP Secondary Cluster: Feature|Модели программных сбоев (вторичный кластер): функциональность|
|CWE-996|SFP Secondary Cluster: Security|Модели программных сбоев (вторичный кластер): безопасность|
|CWE-997|SFP Secondary Cluster: Information Loss|Модели программных сбоев (вторичный кластер): потеря данных|
|CWE-998|SFP Secondary Cluster: Glitch in Computation|Модели программных сбоев (вторичный кластер): сбой при вычислении|
|CWE-999|Weaknesses without Software Fault Patterns|Недостатки без моделей программных сбоев|
|CWE-1000|Research Concepts|Концепции исследования|
|CWE-1001|SFP Secondary Cluster: Use of an Improper API|Модели программных сбоев (вторичный кластер): использование некорректного API|
|CWE-1002|SFP Secondary Cluster: Unexpected Entry Points|Модели программных сбоев (вторичный кластер): непредусмотренные точки входа|
|CWE-1003|Weaknesses for Simplified Mapping of Published Vulnerabilities|Недостатки для упрощенной привязки опубликованных уязвимостей|
|CWE-1004|Sensitive Cookie Without 'HttpOnly' Flag|Отсутствие флага HttpOnly у конфиденциальных куки-файлов|
|CWE-1005|Input Validation and Representation|Отображение и проверка входных данных|
|CWE-1006|Bad Coding Practices|Недостатки программирования|
|CWE-1007|Insufficient Visual Distinction of Homoglyphs Presented to User|Недостаточно очевидные для пользователя визуальные отличия омоглифов|
|CWE-1008|Architectural Concepts|Архитектурные принципы|
|CWE-1009|Audit|Аудит|
|CWE-1010|Authenticate Actors|Аутентификация|
|CWE-1011|Authorize Actors|Авторизация|
|CWE-1012|Cross Cutting|Сквозные уязвимости|
|CWE-1013|Encrypt Data|Шифрование данных|
|CWE-1014|Identify Actors|Управление идентификацией|
|CWE-1015|Limit Access|Ограничение доступа|
|CWE-1016|Limit Exposure|Ограничение количества точек входа|
|CWE-1017|Lock Computer|Блокировка системы|
|CWE-1018|Manage User Sessions|Управление сессиями пользователей|
|CWE-1019|Validate Inputs|Проверка входных данных|
|CWE-1020|Verify Message Integrity|Проверка целостности данных|
|CWE-1021|Improper Restriction of Rendered UI Layers or Frames|Некорректное ограничение отображаемых фреймов или слоев интерфейса|
|CWE-1022|Use of Web Link to Untrusted Target with window.opener Access|Веб-ссылки на недоверенные сайты с использованием window.opener|
|CWE-1023|Incomplete Comparison with Missing Factors|Неполное сравнение, связанное с отсутствующими факторами|
|CWE-1024|Comparison of Incompatible Types|Сравнение несовместимых типов|
|CWE-1025|Comparison Using Wrong Factors|Сравнение некорректных факторов|
|CWE-1026|Weaknesses in OWASP Top Ten (2017)|Недостатки из Топ-10 OWASP (2017 г.)|
|CWE-1027|OWASP Top Ten 2017 Category A1 - Injection|Топ-10 OWASP — 2017 Категория А1 - Внедрение|
|CWE-1028|OWASP Top Ten 2017 Category A2 - Broken Authentication|Топ-10 OWASP — 2017 Категория А2 - Недостатки аутентификации|
|CWE-1029|OWASP Top Ten 2017 Category A3 - Sensitive Data Exposure|Топ-10 OWASP — 2017 Категория А3 - Разглашение конфиденциальных данных|
|CWE-1030|OWASP Top Ten 2017 Category A4 - XML External Entities (XXE)|Топ-10 OWASP — 2017 Категория А4 - Внешние сущности XML (XXE)|
|CWE-1031|OWASP Top Ten 2017 Category A5 - Broken Access Control|Топ-10 OWASP — 2017 Категория А5 - Недостатки контроля доступа|
|CWE-1032|OWASP Top Ten 2017 Category A6 - Security Misconfiguration|Топ-10 OWASP — 2017 Категория А6 - Некорректная настройка параметров безопасности|
|CWE-1033|OWASP Top Ten 2017 Category A7 - Cross-Site Scripting (XSS)|Топ-10 OWASP — 2017 Категория А7 - Межсайтовое выполнение сценариев (XSS)|
|CWE-1034|OWASP Top Ten 2017 Category A8 - Insecure Deserialization|Топ-10 OWASP — 2017 Категория А8 - Небезопасная десериализация|
|CWE-1035|OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities|Топ-10 OWASP — 2017 Категория А9 - Использование компонентов с известными уязвимостями|
|CWE-1036|OWASP Top Ten 2017 Category A10 - Insufficient Logging & Monitoring|Топ-10 OWASP — 2017 Категория А10 - Недостатки журналирования и мониторинга|
|CWE-1037|Processor Optimization Removal or Modification of Security-critical Code|Удаление или изменение обеспечивающего безопасность кода при оптимизации процессором|
|CWE-1038|Insecure Automated Optimizations|Небезопасная автоматическая оптимизация|
|CWE-1039|Automated Recognition Mechanism with Inadequate Detection or Handling of Adversarial Input Perturbations|Некорректная работа автоматизированного механизма распознавания при определении или обработке входных данных, модифицированных злоумышленником|
|CWE-1040|Quality Weaknesses with Indirect Security Impacts|Недостатки качества, оказывающие косвенное влияние на безопасность|
|CWE-1041|Use of Redundant Code|Использование избыточного кода|
|CWE-1042|Static Member Data Element outside of a Singleton Class Element|Статический элемент member, не принадлежащий классу "Одиночка" (Singleton)|
|CWE-1043|Data Element Aggregating an Excessively Large Number of Non-Primitive Elements|Элемент данных со слишком большим количеством элементов, не являющихся примитивами|
|CWE-1044|Architecture with Number of Horizontal Layers Outside of Expected Range|Количество горизонтальных слоев архитектуры не соответствует ожидаемому значению|
|CWE-1045|Parent Class with a Virtual Destructor and a Child Class without a Virtual Destructor|Родительский класс имеет виртуальный деструктор, а дочерний нет|
|CWE-1046|Creation of Immutable Text Using String Concatenation|Создание неизменяемого текста путем объединения строк|
|CWE-1047|Modules with Circular Dependencies|Модули с циклическими зависимостями|
|CWE-1048|Invokable Control Element with Large Number of Outward Calls|Вызываемый элемент управления с большим количеством внешних вызовов|
|CWE-1049|Excessive Data Query Operations in a Large Data Table|Слишком сложная цепочка запроса данных для больших таблиц данных|
|CWE-1050|Excessive Platform Resource Consumption within a Loop|Чрезмерное использование ресурсов платформы в цикле|
|CWE-1051|Initialization with Hard-Coded Network Resource Configuration Data|Инициализация с помощью жестко закодированных данных о конфигурации сетевых ресурсов|
|CWE-1052|Excessive Use of Hard-Coded Literals in Initialization|Чрезмерное использование жестко закодированных литералов для инициализации|
|CWE-1053|Missing Documentation for Design|Отсутствие проектной документации|
|CWE-1054|Invocation of a Control Element at an Unnecessarily Deep Horizontal Layer|Вызов элемента управления из излишне глубокого горизонтального слоя|
|CWE-1055|Multiple Inheritance from Concrete Classes|Множественное наследование из "конкретных" (concrete) классов|
|CWE-1056|Invokable Control Element with Variadic Parameters|Вызываемый элемент управления с переменным числом параметров или аргументов|
|CWE-1057|Data Access Operations Outside of Expected Data Manager Component|Доступ к данным без использования специального компонента управления данными|
|CWE-1058|Invokable Control Element in Multi-Thread Context with non-Final Static Storable or Member Element|Вызываемый элемент управления в многопоточном контексте с non-final статическим элементом storable или member|
|CWE-1059|Incomplete Documentation|Неполная документация|
|CWE-1060|Excessive Number of Inefficient Server-Side Data Accesses|Большое количество недопустимых обращений к данным на стороне сервера|
|CWE-1061|Insufficient Encapsulation|Недостаточная инкапсуляция|
|CWE-1062|Parent Class with References to Child Class|Родительский класс со ссылками на дочерний|
|CWE-1063|Creation of Class Instance within a Static Code Block|Создание экземпляра класса в статическом блоке кода|
|CWE-1064|Invokable Control Element with Signature Containing an Excessive Number of Parameters|Вызываемый элемент управления с подписью, содержащей большое количество параметров|
|CWE-1065|Runtime Resource Management Control Element in a Component Built to Run on Application Servers|Компонент, созданный для работы на сервере, использует элементы управления ресурсами среды исполнения|
|CWE-1066|Missing Serialization Control Element|Отсутствие элемента управления сериализацией|
|CWE-1067|Excessive Execution of Sequential Searches of Data Resource|Чрезмерное использование последовательного поиска данных|
|CWE-1068|Inconsistency Between Implementation and Documented Design|Несоответствие между реализацией и проектной документацией|
|CWE-1069|Empty Exception Block|Пустой блок исключения|
|CWE-1070|Serializable Data Element Containing non-Serializable Item Elements|Сериализуемый элемент данных содержит несериализуемые элементы|
|CWE-1071|Empty Code Block|Пустой блок кода|
|CWE-1072|Data Resource Access without Use of Connection Pooling|Доступ к данным без использования пула подключений|
|CWE-1073|Non-SQL Invokable Control Element with Excessive Number of Data Resource Accesses|Вызываемый не-SQL элемент управления с большим количеством обращений к данным|
|CWE-1074|Class with Excessively Deep Inheritance|Класс со слишком глубоким наследованием|
|CWE-1075|Unconditional Control Flow Transfer outside of Switch Block|Безусловная передача управления за пределами блока переключения|
|CWE-1076|Insufficient Adherence to Expected Conventions|Несоответствие принятым стандартам|
|CWE-1077|Floating Point Comparison with Incorrect Operator|Сравнение значений с плавающей запятой, использующее некорректный оператор|
|CWE-1078|Inappropriate Source Code Style or Formatting|Несоответствие стиля или форматирования исходного кода|
|CWE-1079|Parent Class without Virtual Destructor Method|Родительский класс без метода виртуального деструктора|
|CWE-1080|Source Code File with Excessive Number of Lines of Code|Файл исходного кода содержит слишком большое количество строк|
|CWE-1082|Class Instance Self Destruction Control Element|Самоуничтожение экземпляра класса |
|CWE-1083|Data Access from Outside Expected Data Manager Component|Доступ к данным без использования определенного компонента управления данными|
|CWE-1084|Invokable Control Element with Excessive File or Data Access Operations|Вызываемый элемент управления с большим количеством обращений к файлам или данным|
|CWE-1085|Invokable Control Element with Excessive Volume of Commented-out Code|Вызываемый элемент управления с большим количеством закомментированного кода|
|CWE-1086|Class with Excessive Number of Child Classes|Класс со слишком большим количеством дочерних класов|
|CWE-1087|Class with Virtual Method without a Virtual Destructor|Класс с виртуальным методом без виртуального деструктора|
|CWE-1088|Synchronous Access of Remote Resource without Timeout|Синхронный доступ к удаленному ресурсу без тайм-аута|
|CWE-1089|Large Data Table with Excessive Number of Indices|Большая таблица данных содержит слишком много индексов|
|CWE-1090|Method Containing Access of a Member Element from Another Class|Метод, обращающийся к элементу member из другого класса|
|CWE-1091|Use of Object without Invoking Destructor Method|Использование объекта без последующего вызова деструктора|
|CWE-1092|Use of Same Invokable Control Element in Multiple Architectural Layers|Использование одного вызываемого элемента управления на нескольких архитектурных уровнях|
|CWE-1093|Excessively Complex Data Representation|Слишком сложное представление данных|
|CWE-1094|Excessive Index Range Scan for a Data Resource|Слишком большой диапазон сканирования индексов для источника данных|
|CWE-1095|Loop Condition Value Update within the Loop|Значение условия цикла обновляется внутри цикла|
|CWE-1096|Singleton Class Instance Creation without Proper Locking or Synchronization|Создание экземпляра класса "Одиночка" (Singleton) без соответствующей блокировки или синхронизации|
|CWE-1097|Persistent Storable Data Element without Associated Comparison Control Element|Постоянно хранимый элемент данных без соответствующего элемента управления сравнением|
|CWE-1098|Data Element containing Pointer Item without Proper Copy Control Element|Элемент данных с указателем без элемента управления копированием|
|CWE-1099|Inconsistent Naming Conventions for Identifiers|Непоследовательная система именования идентификаторов|
|CWE-1100|Insufficient Isolation of System-Dependent Functions|Недостаточная изоляция зависящих от системы функций|
|CWE-1101|Reliance on Runtime Component in Generated Code|Использование специального компонента для выполнения генерируемого кода|
|CWE-1102|Reliance on Machine-Dependent Data Representation|Использование машинозависимого представления данных|
|CWE-1103|Use of Platform-Dependent Third Party Components|Использование сторонних платформозависимых компонентов|
|CWE-1104|Use of Unmaintained Third Party Components|Использование сторонних неподдерживаемых компонентов|
|CWE-1105|Insufficient Encapsulation of Machine-Dependent Functionality|Некорректная инкапсуляция машинозависимых функций|
|CWE-1106|Insufficient Use of Symbolic Constants|Некорректное использование символических констант|
|CWE-1107|Insufficient Isolation of Symbolic Constant Definitions|Некорректная изоляция определений символических констант|
|CWE-1108|Excessive Reliance on Global Variables|Чрезмерное использование глобальных переменных|
|CWE-1109|Use of Same Variable for Multiple Purposes|Использование одной переменной для разных целей|
|CWE-1110|Incomplete Design Documentation|Неполная проектная документация|
|CWE-1111|Incomplete I/O Documentation|Неполное описание ввода-вывода данных|
|CWE-1112|Incomplete Documentation of Program Execution|Неполное описание работы программы|
|CWE-1113|Inappropriate Comment Style|Неподходящий стиль комментариев|
|CWE-1114|Inappropriate Whitespace Style|Неподходящий стиль пробелов|
|CWE-1115|Source Code Element without Standard Prologue|Элемент исходного кода без стандартной вводной части|
|CWE-1116|Inaccurate Comments|Неточные комментарии|
|CWE-1117|Callable with Insufficient Behavioral Summary|Недостаточное описание поведения вызываемых функций или методов|
|CWE-1118|Insufficient Documentation of Error Handling Techniques|Недостаточное описание способов обработки ошибок|
|CWE-1119|Excessive Use of Unconditional Branching|Чрезмерное использоавние безусловных переходов|
|CWE-1120|Excessive Code Complexity|Чрезмерная сложность кода|
|CWE-1121|Excessive McCabe Cyclomatic Complexity|Избыточная цикломатическая сложность Маккейба|
|CWE-1122|Excessive Halstead Complexity|Избыточная сложность Холстеда|
|CWE-1123|Excessive Use of Self-Modifying Code|Чрезмерное использование самоизменяющегося кода|
|CWE-1124|Excessively Deep Nesting|Чрезмерная вложенность|
|CWE-1125|Excessive Attack Surface|Большое количество возможных векторов атаки|
|CWE-1126|Declaration of Variable with Unnecessarily Wide Scope|Объявление переменной с необоснованно большой областью использования|
|CWE-1127|Compilation with Insufficient Warnings or Errors|Компиляция без вывода соответствующих предупреждений или ошибок|
|CWE-1128|CISQ Quality Measures (2016)|Критерии качества CISQ (2016)|
|CWE-1129|CISQ Quality Measures - Reliability|Критерии качества CISQ - Надежность|
|CWE-1130|CISQ Quality Measures - Maintainability|Критерии качества CISQ - Удобство сопровождения|
|CWE-1131|CISQ Quality Measures - Security|Критерии качества CISQ - Безопасность|
|CWE-1132|CISQ Quality Measures - Performance|Критерии качества CISQ - Производительность|
|CWE-1133|Weaknesses Addressed by the SEI CERT Oracle Coding Standard for Java|Недостатки из стандарта SEI CERT Oracle по программированию на Java|
|CWE-1134|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 00. Input Validation and Data Sanitization (IDS)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 00. Проверка и обработка входных данных (IDS)|
|CWE-1135|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 01. Declarations and Initialization (DCL)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 01. Объявления и инициализация (DCL)|
|CWE-1136|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 02. Expressions (EXP)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 02. Выражения (EXP)|
|CWE-1137|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 03. Numeric Types and Operations (NUM)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 03. Числовые типы и операции (NUM)|
|CWE-1138|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 04. Characters and Strings (STR)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 04. Символы и строки (STR)|
|CWE-1139|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 05. Object Orientation (OBJ)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 05. Объектная ориентация (OBJ)|
|CWE-1140|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 06. Methods (MET)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 06. Методы (MET)|
|CWE-1141|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 07. Exceptional Behavior (ERR)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 07. Необычное поведение (ERR)|
|CWE-1142|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 08. Visibility and Atomicity (VNA)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 08. Видимость и атомарность (VNA)|
|CWE-1143|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 09. Locking (LCK)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 09. Блокировка (LCK)|
|CWE-1144|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 10. Thread APIs (THI)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 10. API потоков (THI)|
|CWE-1145|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 11. Thread Pools (TPS)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 11. Пулы потоков (TPS)|
|CWE-1146|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 12. Thread-Safety Miscellaneous (TSM)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 12. Прочие вопросы по безопасности потоков (TSM)|
|CWE-1147|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 13. Input Output (FIO)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 13. Ввод-вывод (FIO)|
|CWE-1148|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 14. Serialization (SER)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 14. Сериализация (SER)|
|CWE-1149|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 15. Platform Security (SEC)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 15. Безопасность платформы (SEC)|
|CWE-1150|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 16. Runtime Environment (ENV)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 16. Среда выполнения (ENV)|
|CWE-1151|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 17. Java Native Interface (JNI)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 17. Собственный интерфейс Java (JNI)|
|CWE-1152|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 49. Miscellaneous (MSC)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 49. Прочее (MSC)|
|CWE-1153|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 50. Android (DRD)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 50. Андроид (DRD)|
|CWE-1154|Weaknesses Addressed by the SEI CERT C Coding Standard|Недостатки из стандарта SEI CERT по программированию на Си|
|CWE-1155|SEI CERT C Coding Standard - Guidelines 01. Preprocessor (PRE)|Стандарт SEI CERT по программированию на Си - Рекомендации 01. Препроцессор (PRE)|
|CWE-1156|SEI CERT C Coding Standard - Guidelines 02. Declarations and Initialization (DCL)|Стандарт SEI CERT по программированию на Си - Рекомендации 02. Объявления и инициализация (DCL)|
|CWE-1157|SEI CERT C Coding Standard - Guidelines 03. Expressions (EXP)|Стандарт SEI CERT по программированию на Си - Рекомендации 03. Выражения (EXP)|
|CWE-1158|SEI CERT C Coding Standard - Guidelines 04. Integers (INT)|Стандарт SEI CERT по программированию на Си - Рекомендации 04. Целые числа (INT)|
|CWE-1159|SEI CERT C Coding Standard - Guidelines 05. Floating Point (FLP)|Стандарт SEI CERT по программированию на Си - Рекомендации 05. Плавающая запятая (FLP)|
|CWE-1160|SEI CERT C Coding Standard - Guidelines 06. Arrays (ARR)|Стандарт SEI CERT по программированию на Си - Рекомендации 06. Массивы (ARR)|
|CWE-1161|SEI CERT C Coding Standard - Guidelines 07. Characters and Strings (STR)|Стандарт SEI CERT по программированию на Си - Рекомендации 07. Символы и строки (STR)|
|CWE-1162|SEI CERT C Coding Standard - Guidelines 08. Memory Management (MEM)|Стандарт SEI CERT по программированию на Си - Рекомендации 08. Управление памятью (MEM)|
|CWE-1163|SEI CERT C Coding Standard - Guidelines 09. Input Output (FIO)|Стандарт SEI CERT по программированию на Си - Рекомендации 09. Ввод-вывод (FIO)|
|CWE-1164|Irrelevant Code|Бесполезный код|
|CWE-1165|SEI CERT C Coding Standard - Guidelines 10. Environment (ENV)|Стандарт SEI CERT по программированию на Си - Рекомендации 10. Среда (ENV)|
|CWE-1166|SEI CERT C Coding Standard - Guidelines 11. Signals (SIG)|Стандарт SEI CERT по программированию на Си - Рекомендации 11. Сигналы (SIG)|
|CWE-1167|SEI CERT C Coding Standard - Guidelines 12. Error Handling (ERR)|Стандарт SEI CERT по программированию на Си - Рекомендации 12. Обработка ошибок (ERR)|
|CWE-1168|SEI CERT C Coding Standard - Guidelines 13. Application Programming Interfaces (API)|Стандарт SEI CERT по программированию на Си - Рекомендации 13. Интерфейсы прикладного программирования (API)|
|CWE-1169|SEI CERT C Coding Standard - Guidelines 14. Concurrency (CON)|Стандарт SEI CERT по программированию на Си - Рекомендации 14. Параллелизм (CON)|
|CWE-1170|SEI CERT C Coding Standard - Guidelines 48. Miscellaneous (MSC)|Стандарт SEI CERT по программированию на Си - Рекомендации 48. Прочее (MSC)|
|CWE-1171|SEI CERT C Coding Standard - Guidelines 50. POSIX (POS)|Стандарт SEI CERT по программированию на Си - Рекомендации 50. POSIX (POS)|
|CWE-1172|SEI CERT C Coding Standard - Guidelines 51. Microsoft Windows (WIN)|Стандарт SEI CERT по программированию на Си - Рекомендации 51. Microsoft Windows (WIN)|
|CWE-1173|Improper Use of Validation Framework|Некорректное использование фреймворка проверки входных данных|
|CWE-1174|ASP.NET Misconfiguration: Improper Model Validation|Ошибка в конфигурации ASP.NET: некорректная проверка моделей|
|CWE-1175|SEI CERT Oracle Secure Coding Standard for Java - Guidelines 18. Concurrency (CON)|Стандарт SEI CERT Oracle по безопасному программированию на Java - Рекомендации 18. Параллелизм (CON)|
|CWE-1176|Inefficient CPU Computation|Неэффективное использование ЦП|
|CWE-1177|Use of Prohibited Code|Использование запрещенного кода|
|CWE-1178|Weaknesses Addressed by the SEI CERT Perl Coding Standard|Недостатки из стандарта SEI CERT по программированию на Perl|
|CWE-1179|SEI CERT Perl Coding Standard - Guidelines 01. Input Validation and Data Sanitization (IDS)|Стандарт SEI CERT по программированию на Perl - Рекомендации 01. Проверка и обработка входных данных (IDS)|
|CWE-1180|SEI CERT Perl Coding Standard - Guidelines 02. Declarations and Initialization (DCL)|Стандарт SEI CERT по программированию на Perl - Рекомендации 02. Объявления и инициализация (DCL)|
|CWE-1181|SEI CERT Perl Coding Standard - Guidelines 03. Expressions (EXP)|Стандарт SEI CERT по программированию на Perl - Рекомендации 03. Выражения (EXP)|
|CWE-1182|SEI CERT Perl Coding Standard - Guidelines 04. Integers (INT)|Стандарт SEI CERT по программированию на Perl - Рекомендации 04. Целые числа (INT)|
|CWE-1183|SEI CERT Perl Coding Standard - Guidelines 05. Strings (STR)|Стандарт SEI CERT по программированию на Perl - Рекомендации 05. Строки (STR)|
|CWE-1184|SEI CERT Perl Coding Standard - Guidelines 06. Object-Oriented Programming (OOP)|Стандарт SEI CERT по программированию на Perl - Рекомендации 06. Объектно-ориентированное программирование (OOP)|
|CWE-1185|EI CERT Perl Coding Standard - Guidelines 07. File Input and Output (FIO)|Стандарт SEI CERT по программированию на Perl - Рекомендации 07.  Ввод-вывод (FIO)|
|CWE-1186|SEI CERT Perl Coding Standard - Guidelines 50. Miscellaneous (MSC)|Стандарт SEI CERT по программированию на Perl - Рекомендации 50. Прочее (MSC)|
|CWE-1187|Use of Uninitialized Resource|Использование неинициализированных ресурсов|
|CWE-1188|Insecure Default Initialization of Resource|Инициализация ресурса с небезопасными параметрами по умолчанию|
|CWE-1200|Weaknesses in the 2019 CWE Top 25 Most Dangerous Software Errors|Недостатки из 2019 CWE Топ-25 самых опасных ошибок ПО|
|CWE-2000|Comprehensive CWE Dictionary|Полный список CWE|
