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

Здесь будет описание того, как читать данную вики.

- **General / [[About | О проекте]]**

	- [[Mission | Миссия]]
	- [[Монетизация]]
	- [[Бизнес процессы]]
	- Киллер фича
	- Roadmap

- **Акторы**

	- [[ActorApplicant | АкторСоискатель]]
	- [[ActorEmployer | АкторРаботодатель]]
	- АкторАдмин
	- АкторЭксперт

- **Материалы**

	- [HR-Tech.figjam](https://www.figma.com/file/SovXmi2VYu2ZlFDutYez58/HR-Tech?node-id=0%3A1)
	- [HR-Tech, Текст Сорокоумова.notion](https://www.notion.so/asorokoumov/HR-Tech-5ca31f5d32ee4a2d862d773b87a6131f)
	- [Business Processes.figjam](https://www.figma.com/file/R5Bnq5O9zagXakYzi5qxPZ/Business-Processes?node-id=0%3A1)

- **Приложения (Applications)**
	- [[HR Applicant App]]
	- [[HR Employer App]]

- **Сущности**
	- Основные
		- [[Applicant]]
		- [[Grade]]
		- [[Organization]]
		- [[Qualification]]
		- [[Skill]]
		- [[Specialist]]
		- [[Vacancy]]
	- Прочие
		- [[ApplicantProfile]]
		- [[InfoСollector]]
		- [[Employer]]
		- [[QualificationTestTask]]

- **Бизнес процессы**
	- [[BP Applicant Job Search | Процесс поиска работы соискателем]]
	- [[BP Employer Job Closing | Процесс закрытия вакансии работодателем]]

- **Не бизнес процессы**
	- **Со стороны Соискателя**
		- Процесс собеседования
	- **Со стороны Работодателя**
		- Процесс создания организации
		- Процесс заполнения карточки организации
		- Процесс создания подразделения
		- Процесс добавления существующего сотрудника в компанию
		---
		- Процесс создания и управления вакансией
		---
		- Процесс собеседования соискателя
		- Процесс найма соискателей

	
	
	
	

- **Не знаю куда**
	- Сравнение ожидаемой зарплаты соискателя с «рыночной стоимостью квалификации»
	- Рекомендация подходящего работодателя
	- Действия: отправить отклик на действующую и подходящую вакансию работодателя
	- Сборщик информации (Аля Typeform) [[Info collector]]
	- Верхняя и нижние границы рекомендаций по различным параметрам вакансии, пример Cian.ru
	- Продумать практики, отделить скиллы от практик
	- Подключение гос услуг
	- Сценарий когда соискатель создаёт себе учетку и уже работает в какой-то компании, которая присутсвует на площадке