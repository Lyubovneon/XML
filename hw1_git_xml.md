### 👉 *START part 2* 💙💛
### *XML*
***
### *21. Создать внешний репозиторий c названием XML.*
- **github.com --> section Repositories --> click on the NEW button --> write XML in the Repository name field --> mark as Public --> click on the Create repository button**
*** 
### *22. Клонировать репозиторий XML на локальный компьютер.*
- **git clone** git@github.com:Lyubovneon/XML.git
***
### *23. Внутри локального XML создать файл “new.xml”.*
- **cd XML**
- **touch new.xml**
- **ls -la**  -  to see XML content 
***
### *24. Добавить файл под гит*.
- **add new.xml**
***
### *25. Закоммитить файл.*
- **git commit -m** "add new.xml"
***
### *26. Отправить файл на внешний GitHub репозиторий.*
- **git push**
***
### *27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.*
- **vim new.xml**
- **insert**

<person_name>Lyubov</person_name>

<person_surname>Nekroyenko</person_surname>

<age>30</age>

<pets>2</pets>

<salary>3000</salary>

- **Esc:wq**
- **cat new.xml**  - to see the new.xml content in gitbash
***
### *28. Отправить изменения на внешний репозиторий.*
- **git add .**
- **git commit -m** "modify new.xml"
- **git push**
***
### *29. Создать файл preferences.xml*
- **touch preferences.xml**
- **ls -la**  -  to see XML content 
***
### *30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.*
- **vim preferences.xml**
- **insert**

<note>

	<movie>The Bodyguard</movie>
	
	<serial> Friends</serial>
	
	<food>Apples</food>
	
	<season>Spring</season>
	
	<country>USA</country>
	
</note>
- **Esc:wq**
- **cat preferences.xml**  - to see the preferences.xml content in gitbash
***
### *31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML*
- **touch skills.xml**
- **ls -la**  -  to see XML content 
- **vim skills.xml**
- **insert**
- 
<skills>

	<1>Bug Tracker JIRA, Mantis</1>
	
	<2>Test Tracker TestLink </2>
	
        <3>Test documentations Test Plan, Test case, Test Suite, Check list, Bug report</3>
        
	<4>Testing Methods, Types of Testing, Software Test Design Techniques, SDLS(System Development Life Cycle), STLC</4>
	
	<5>Agile methodology SCRUM, KANBAN</5>
	
	<6>Client-Server Architecture Basics</6>
	
	<7>SQL DML, DDL</7>
	
	<8>HTTP methods</8>
	
	<9>Response STATUS codes</9>
	
	<10>API REST, SOAP</10>
	
	<11>POSTMAN</11>
	
	<12>Devtools Chrome</12>
	
	<13>GITHUB, GITBASH</13>
	
	<14>JSON, XML basic, structure </14>
	
	<15>Google Sheets</15>
	
	<16>Visual Studio code basics</16>
	
	<17>Mobile testing</17>
	
	<18>SNAGIT, Lightshot, Bandicam</18>
	
	<19>html, css, JavaScript basics</19>
	
	<20>Taking, uploading and reading Logs </20>
	
</skills>
- **Esc:wq**
- **cat skills.xml**  - to see the skills.xml content in gitbash

***
### *32. Сделать коммит в одну строку.*
- **git add .** 
- **git commit -m** "add preferences.xml skills.xml"
***
### *33. Отправить сразу 2 файла на внешний репозиторий.*
- **git push**
***
### *34. На веб интерфейсе создать файл bug_report.xml.*
- **github.com --> drop down menu --> Your Repositories --> click on the XML Repository --> click on add file dropbox --> Create new file --> write bug_report.xml in the name field **

***
### *35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*
- **--> write the title in the Commite new file field --> click on the Commit new file button**

***
### *36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.*
- **click on the dropbox--> edit this file -->**

<bug_report ID="110920221">

 <Title>Fields are shown without required identification</Title>
            
<Invironment>Microsoft EdgeVersion 105.0.1343.27 (64-bit) OS Windows OS Version 10x64</Invironment>

<STR1>Open the http://itcareer.pythonanywhere.com</STR1>

<STR2>Pay attention to the browser tab</STR2>

<AR>Fields are shown without required identification</AR>

<ER>Required fields are shown marked *(asterisk)</ER>

<Severity>major</Severity>

<Priority>high</Priority>

<Attachment1>link_video</Attachment1>

<Attachment2>link_screenshort</Attachment2>

</bug_report>

***
### *37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*
- **--> write the title in the Commite changes field --> click on the Commit changes button**

***
### *38. Синхронизировать внешний и локальный репозиторий XML*
- **git pull**

###  *F I N I S H_part 2* 👈











