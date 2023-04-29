# XML

***1. Создать внешний репозиторий c названием XML***

```
github.com -> Repositories -> New -> "XML" -> Create repository
```

***2. Клонировать репозиторий XML на локальный компьютер***

```
Enter to repo XML -> "<>Code" -> SSH -> Copy url -> go to Terminal:

git clone git@github.com:zenDozer/XML.git
```

***3. Внутри локального XML создать файл “new.xml”***

```
cd XML
touch new.xml
```

***4. Добавить файл под гит***

```
git add new.xml
```

***5. Закоммитить файл***

```
git commit - m "Add new.xml file
```

***6. Отправить файл на внешний GitHub репозиторий***

```
git push
```

***7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML***

```
vim new.xml

<?xml version="1.0" encoding="UTF-8"?>
<My_info>
	<fio>Malko Oleksandr</fio>
	<age>42</age>
	<pet>1</pet>
	<salary>750</salary>
</My_info>
```

***8. Отправить изменения на внешний репозиторий***

```
git add .
git commit -m "Update new.xml"
git push
```

***9. Создать файл preferences.xml***
***10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML***

```
vim preferences.xml

<?xml version="1.0" encoding="UTF-8"?>
<preferences>
	<Film>The Social Network</Film>
	<TV_series>Silicon Valley</TV_series>
	<Favorite_food>Borsch</Favorite_food>
	<Favorite_season>Spring</Favorite_season>
	<Country>USA</Country>
</preferences>
```

***11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML***

```
vim sklls.xml

<?xml version="1.0" encoding="UTF-8"?>
<skills>
	<s1>Basic theory</s1>
	<s2>client-server architecture</s2>
	<s3>"HTTP"</s3>
	<s4>JSON/XML</s4>
	<s5>Postman</s5>
	<s6>Charles</s6>
	<s7>Fidler</s7>
	<s8>Dev Tools</s8>
	<s9>VPN</s9>
	<s10>Mobile testing</s10>
	<s11>Android Studio</s11>
	<s12>Terminal</s12>
	<s13>Git</s13>
	<s14>SQL basic</s14>
	<s15>Jmeter</s15>
	<s16>Scrum</s16>
	<s17>Python basic</s17>
</skills>
```

***12. Сделать коммит в одну строку***

```
git add . && git commit -m "Add 2 files"

или командой

git commit -a -m "Add 2 files"

предварительно добавив вновь созданные файлы в трекинг репозитория - git add .
```

***13. Отправить сразу 2 файла на внешний репозиторий***

```
git push
```

***14. На веб интерфейсе создать файл bug_report.xml***

```
Enter to repo XML -> Add file -> Create new file ->  bug_report.xml
```

***15. Сделать Commit changes (сохранить) изменения на веб интерфейсе***

```
Commit changes -> Commit message: "Add bug_report.xml" -> Commit changes
```

***16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML***

```
Select bug_report.xml file -> add changes:

<?xml version="1.0" encoding="UTF-8"?>
<report>
	<ID>LF-001</ID>
	<Summary>The Login button should be blue - not red</Summary>
	<Severity>Minor</Severity>
	<Priority>Low</Priority>
	<Environment>PC, Windows 11, Chrome</Environment>
	<Steps>Open example_site.com, click on sign in button</Steps>
	<ExpectedR>Login button is blue</ExpectedR>
	<ActualR>Login button is red</ActualR>
	<Attachments>Screenshot.jpg</Attachments>
	<ReportedBy>Oleksandr Malko</ReportedBy>
</report>
```

***17. Сделать Commit changes (сохранить) изменения на веб интерфейсе***

```
Commit changes -> Commit message: "Update bug_report.xml" -> Commit changes
```

***18. Синхронизировать внешний и локальный репозиторий XML***

```
Go to Terminal and type:

git pull
```