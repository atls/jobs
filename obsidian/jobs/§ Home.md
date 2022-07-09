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
# Jobs

- Соискатель

	- [[объекты работы]]
	- [[проверка тестов]]
	- [[путь соискателя]]
	- [[регистрация соискателя]]
	- [[стаж работы]]

- Работодатель
	- [[работодатель]]

- Вакансия
	- [[вакансия]]