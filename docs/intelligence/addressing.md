---
layout: default
title: Адресация
parent: Основные сведения
nav_order: 3
---

# Адресация
## Адресная система
Система противопожарной защиты (СПЗ) Глобал представляет из себя совокупность приборов (ГК, [КАУ]({% link docs/intelligence/intelligence.md %}#кау) и подключенных к ним по [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи) [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств).

В СПЗ каждый прибор (ГК, [КАУ]({% link docs/intelligence/intelligence.md %}#кау), [составной модуль]({% link docs/intelligence/modules.md %}#составные-модули), [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи) и [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств) имеют свой уникальный идентификатор в системе - адресный номер. Адресный номер присваевается на этапе создания проекта и позволяет определить местоположение (направление) каждого компонента СПЗ.

## Адресный номер ГК и КАУ
Адресный номер ГК и [КАУ]({% link docs/intelligence/intelligence.md %}#кау) имеет вид **x1**, где:
- **x1** - порядковый номер ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау).

## Адресный номер составных модулей
Адресный номер [составных модулей]({% link docs/intelligence/modules.md %}#составные-модули) имеет вид **x1**.**x2**.**0**.**x4**, где:
- **x1** - порядковый номер ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау), в состав которого входит [составной модуль]({% link docs/intelligence/modules.md %}#составные-модули);
- **x2** - порядковый номер [составного модуля]({% link docs/intelligence/modules.md %}#составные-модули);

## Адресный номер входов МДИ и выходов МДО
Адресный номер входов [МДИ]({% link docs/intelligence/modules.md %}#модуль-дискретных-входных-сигналов-с-контролем-цепи) и выходов [МДО]({% link docs/intelligence/modules.md %}#модуль-дискретных-выходных-сигналов-с-контролем-цепи) имеет вид **x1**.**x2**.**0**.**x4**, где:
- **x1** - порядковый номер ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау), в состав которого входит [составной модуль]({% link docs/intelligence/modules.md %}#составные-модули);
- **x2** - порядковый номер [МДИ]({% link docs/intelligence/modules.md %}#модуль-дискретных-входных-сигналов-с-контролем-цепи) или [МДО]({% link docs/intelligence/modules.md %}#модуль-дискретных-выходных-сигналов-с-контролем-цепи);
- **x4** - порядковый номер входа [МДИ]({% link docs/intelligence/modules.md %}#модуль-дискретных-входных-сигналов-с-контролем-цепи) или выхода [МДО]({% link docs/intelligence/modules.md %}#модуль-дискретных-выходных-сигналов-с-контролем-цепи).

## Адресный номер АЛС
Адресный номер [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи) имеет вид **x1**.**x2**.**x3**, где:
- **x1** - порядковый номер ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау), к которому физически подключена [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи);
- **x2** - порядковый номер [МЦП]({% link docs/intelligence/modules.md %}#модуль-центрального-процессора) или [МКА]({% link docs/intelligence/modules.md %}#модуль-кольцевых-адресных-линий-связи), к которому физически подключена [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи);
- **x3** - порядковый номер [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи).

## Адресный номер АУ
В общем случае, адресный номер [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств) имеет вид **x1**.**x2**.**x3**.**x4**, где:
- **x1** - порядковый номер ГК или [КАУ]({% link docs/intelligence/intelligence.md %}#кау);
- **x2** - порядковый номер [МЦП]({% link docs/intelligence/modules.md %}#модуль-центрального-процессора) или [МКА]({% link docs/intelligence/modules.md %}#модуль-кольцевых-адресных-линий-связи), к которому физически подключена [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи), к которой физически подключено [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств);
- **x3** - порядковый номер [АЛС]({% link docs/intelligence/communications_lines.md %}#адресная-линия-связи), к которой физически подключено [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств);
- **x4** - порядковый номер [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств).

Для составных [АУ]({% link docs/intelligence/compatibility.md %}#Список-совместимых-адресных-устройств),занимающих в системе несколько адресов ([АБШС]({% link docs/intelligence/compatibility.md %}#барьер-шлейфов-сигнализации-адресный-абшс-r2), 
