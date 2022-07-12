---
cssclass: dashboard, max
---

# Homepage

- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- 🔖 Tagged:  Favorite 
 `$=dv.list(dv.pages('#Favorite').sort(f=>f.file.name,"desc").limit(10).file.link)`
 - 🏁 Tagged:  Finishup 
 `$=dv.list(dv.pages('#Finishup').sort(f=>f.file.name,"desc").limit(10).file.link)`
- 〽️ Stats
	-  File Count: `$=dv.pages().length`
	%% -  Personal recipes: `$=dv.pages('"Family/Recipes"').length`%%

# HR Project

- General / About

	- Миссия
	- Монетизация
	- Бизнес процессы
	- Киллер фича

- Акторы

	- Кандидат
	- Рекрутёр

- Материалы

	- [HR-Tech.figjam](https://www.figma.com/file/SovXmi2VYu2ZlFDutYez58/HR-Tech?node-id=0%3A1)
	- [HR-Tech, Текст Сорокоумова.notion](https://www.notion.so/asorokoumov/HR-Tech-5ca31f5d32ee4a2d862d773b87a6131f)

- Приложения (Applications)

- Сущности