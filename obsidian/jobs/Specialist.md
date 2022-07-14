---
cssclass: wide
alias: специалист
---

# Specialist

> [!warning] Осторожно!
> Так как на начальном этапе мы рассматриваем сферу IT, то у нас немного проблем с набором специалистов. Но если взглянуть чуть вперёд, такие проблемы могут возникнуть. 
> 
> Например специалист Developer в IT и Developer в строительстве это два разных специалиста из двух разных сфер. И чтобы они не пересекались между собой, нужно как-то их «развести». Об этом важно помнить! 


Это сущность, которая описывает требования к самой себе, на основе [[Grade | грейда]] и [[Skill | умений]]. Если говорить проще, то специлист — это набор умений и грейда для определённой профессии или специальности. 

В общем, предполагаются следующие фундаментальные специальности: 

- [[SpecialistDesigner]]
- [[SpecialistDeveloper]]
- [[SpecialistManager]]
- [[SpecialistQA]]

>[!note] Обратите внимание!
>
> В рамках [[MVP]], ведётся работа только с одной фундаментальной специальностью — Developer. 

Каждая фундаментальная специальность, содержит в себе *«подспециальность»*, или профессию.

Например, [[SpecialistDeveloper]] содержит в себе подспециальности: 

- Flutter Developer
- Go Developer
- Java Developer
- JS Developer
- Kotlin Developer
- PHP Developer
- Swift Developer
- [[SpecialistDeveloperTypeScript | TypeScript Developer]]

При этом набор — [[Skill | умение]] / [[Grade | грейд]] для каждой подспециальности свой. Просто потому что, требования к умениям у каждой подспециальности и каждого грейда свои. 