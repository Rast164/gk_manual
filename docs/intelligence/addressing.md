---
layout: default
title: Адресация
parent: Основные сведения
nav_order: 4
---

# Адресация
Каждое устройство (ГК, [КАУ]({% link docs/intelligence/intelligence.md %}#кау), [составной модуль]({% link docs/intelligence/modules.md %}#составные-модули), [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи) и [адресное устройство]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств)) имеют свой уникальный идентификатор в системе - адресный номер.
Адресный номер имеет вид **x1.x2.x3.x4**, где:
- **x1** - порядковый номер ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау). Максимальное значение соответствует суммарному количеству заложенных в проект ГК и [КАУ]({% link docs/intelligence/intelligence.md %}#кау), но не более 65;
- **x2** - порядковый номер [составного модуля]({% link docs/intelligence/modules.md %}#составные-модули). Максимальное значение соответствует количеству [составных модулей]({% link docs/intelligence/modules.md %}#составные-модули) в [конкретном исполнении]({% link docs/intelligence/intelligence.md %}#исполнения-гк) ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау);
- **x3** - порядковый номер [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи). Максимальное значение зависит от количества МКА в конкретном исполнении ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау);
- **x4** - порядковый номер [адресного устройства]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств)). Максимальное значение соответствует суммарному количеству заложенных в проект [адресных устройств]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств)), но не более 250 на одну [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи).
