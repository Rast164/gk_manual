---
layout: default
title: СПЗ Глобал
nav_order: 2
has_children: true
permalink: /docs/global_system
has_toc: false
---

# Система противопожарной защиты Глобал
Адресная система противопожарной защиты (СПЗ) Глобал представляет из себя совокупность ГК, <a href="/gk_manual/docs/global_system/kau">КАУ</a>, <a href="/gk_manual/docs/global_system/tpu">ТПУ</a>, подключенных по <a href="/gk_manual/docs/intelligence/communications_lines#адресная-линия-связи">АЛС</a> <a href="/gk_manual/docs/global_system/address_devices#адресные-устройства">АУ</a> и подключенного посредством <a href="/gk_manual/docs/global_system/address_devices#устройства-ввода-вывода">устройств ввода-вывода</a> внешнего оборудования.

## Адресный номер
Каждый ГК, <a href="/gk_manual/docs/global_system/kau">КАУ</a>, <a href="/gk_manual/docs/global_system/tpu">ТПУ</a>, <a href="/gk_manual/docs/intelligence/modules#составные-модули">составной модуль</a>, <a href="/gk_manual/docs/intelligence/communications_lines#адресная-линия-связи">АЛС</a> и <a href="/gk_manual/docs/global_system/address_devices#адресные-устройства">АУ</a> имеют свой уникальный идентификатор в СПЗ - адресный номер.

{: .note }
> Адресный номер присваевается на этапе <a href="/gk_manual/docs/intelligence#конфигурирование-гк">создания проекта</a> и позволяет определить местоположение (направление) каждого компонента СПЗ.

### Адресный номер ГК, КАУ и ТПУ
Адресный номер ГК, <a href="/gk_manual/docs/global_system/kau">КАУ</a> и <a href="/gk_manual/docs/global_system/tpu">ТПУ</a> имеет вид **x1**, где:
- **x1** - порядковый номер ГК, <a href="/gk_manual/docs/global_system/kau">КАУ</a> или <a href="/gk_manual/docs/global_system/tpu">ТПУ</a>

### Адресный номер составных модулей
Адресный номер <a href="/gk_manual/docs/intelligence/modules#составные-модули">составных модулей</a> имеет вид **x1**.**x2**, где:
- **x1** - порядковый номер ГК или <a href="/gk_manual/docs/global_system/kau">КАУ</a>
- **x2** - порядковый номер <a href="/gk_manual/docs/intelligence/modules#составные-модули">составного модуля</a>

### Адресный номер входов МДИ и выходов МДО
Адресный номер входов <a href="/gk_manual/docs/intelligence/modules#модуль-дискретных-входных-сигналов-с-контролем-цепи">МДИ</a> и выходов <a href="/gk_manual/docs/intelligence/modules#модуль-дискретных-выходных-сигналов-с-контролем-цепи">МДО</a> имеет вид **x1**.**x2**.**x3**, где:
- **x1** - порядковый номер ГК или <a href="/gk_manual/docs/global_system/kau">КАУ</a>
- **x2** - порядковый номер <a href="/gk_manual/docs/intelligence/modules#модуль-дискретных-входных-сигналов-с-контролем-цепи">МДИ</a> или <a href="/gk_manual/docs/intelligence/modules#модуль-дискретных-выходных-сигналов-с-контролем-цепи">МДО</a>
- **x3** - порядковый номер входа <a href="/gk_manual/docs/intelligence/modules#модуль-дискретных-входных-сигналов-с-контролем-цепи">МДИ</a> или выхода <a href="/gk_manual/docs/intelligence/modules#модуль-дискретных-выходных-сигналов-с-контролем-цепи">МДО</a>

### Адресный номер АЛС
Адресный номер <a href="/gk_manual/docs/intelligence/communications_lines#адресная-линия-связи">АЛС</a> имеет вид **x1**.**x2**.**x3**, где:
- **x1** - порядковый номер ГК или <a href="/gk_manual/docs/global_system/kau">КАУ</a>
- **x2** - порядковый номер <a href="/gk_manual/docs/intelligence/modules#модуль-центрального-процессора">МЦП</a> или <a href="/gk_manual/docs/intelligence/modules#модуль-кольцевых-адресных-линий-связи">МКА</a>
- **x3** - порядковый номер <a href="/gk_manual/docs/intelligence/communications_lines#адресная-линия-связи">АЛС</a>

### Адресный номер АУ
Адресный номер <a href="/gk_manual/docs/global_system/address_devices#адресные-устройства">АУ</a> имеет вид **x1**.**x2**.**x3**.**x4**, где:
- **x1** - порядковый номер ГК или <a href="/gk_manual/docs/global_system/kau">КАУ</a>
- **x2** - порядковый номер <a href="/gk_manual/docs/intelligence/modules#модуль-центрального-процессора">МЦП</a> или <a href="/gk_manual/docs/intelligence/modules#модуль-кольцевых-адресных-линий-связи">МКА</a>
- **x3** - порядковый номер <a href="/gk_manual/docs/intelligence/communications_lines#адресная-линия-связи">АЛС</a>
- **x4** - порядковый номер <a href="/gk_manual/docs/global_system/address_devices#адресные-устройства">АУ</a>.

### Многоадресные АУ
Некоторые <a href="/gk_manual/docs/global_system/address_devices#адресные-устройства">АУ</a> занимают в системе несколько адресов

Для <a href="/gk_manual/docs/global_system/address_devices#устройства-ввода-вывода">устройств ввода-вывода</a> (<a href="/gk_manual/docs/global_system/address_devices#барьер-шлейфов-сигнализации-адресный-абшс-r2">АБШС</a>, <a href="/gk_manual/docs/global_system/address_devices#метка-адресная-ам4-r2">АМ4</a>, <a href="/gk_manual/docs/global_system/address_devices#метка-адресная-пожарная-амп4-r2">АМП4</a>, <a href="/gk_manual/docs/global_system/address_devices#модуль-выходов-с-контролем-мвк2-r2">МВК2</a>, <a href="/gk_manual/docs/global_system/address_devices#модуль-выходов-с-контролем-мвк4-r2">МВК4</a>, <a href="/gk_manual/docs/global_system/address_devices#модуль-выходов-с-контролем-мвк8-r2">МВК8</a>, <a href="/gk_manual/docs/global_system/address_devices#модуль-релейный-рм2-r2">РМ2</a>, <a href="/gk_manual/docs/global_system/address_devices#модуль-релейный-рм4-r2">РМ4</a>) последняя цифра **x4** адресного номера соответствует конкретному вводу/выводу устройства.

{: .example }
> <a href="/gk_manual/docs/global_system/address_devices#метка-адресная-пожарная-амп4-r2">АМП4</a> имеет 4 шлейфа сигнализации и занимает в системе 4 адреса. Если в проекте для <a href="/gk_manual/docs/global_system/address_devices#метка-адресная-пожарная-амп4-r2">АМП4</a> задан адрес **1**.**1**.**2**.**029**, то этот адрес соответствует первому шлейву <a href="/gk_manual/docs/global_system/address_devices#метка-адресная-пожарная-амп4-r2">АМП4</a>, адрес **1**.**1**.**2**.**030** соответствует второму шлейфу, **1**.**1**.**2**.**031** - третьему шлейфу и адрес **1**.**1**.**2**.**032** соответствует четвертому шлейфу <a href="/gk_manual/docs/global_system/address_devices#метка-адресная-пожарная-амп4-r2">АМП4</a>

Для <a href="/gk_manual/docs/global_system/address_devices#оповещатель-охранно-пожарный-комбинированный-свето-звуковой-адресный-опоп-124-r2">ОПОП 124</a> последняя цифра **x4** адресного номера соответствует определенному типу сигнализации - световой или звуковой.

{: .example }
> Если в проекте для <a href="/gk_manual/docs/global_system/address_devices#оповещатель-охранно-пожарный-комбинированный-свето-звуковой-адресный-опоп-124-r2">ОПОП 124</a> задан адрес **1**.**1**.**1**.**012**, то этот адрес соответствует световой сигнализации оповещателя, адрес **1**.**1**.**1**.**013** соответствует звуковой сигнализации

Для <a href="/gk_manual/docs/global_system/address_devices#блок-модульного-пожаротушения-бмп-r2">БМП</a> последняя цифра **x4** адресного номера соответствует определенному компоненту.

{: .example }
> Если в проекте для <a href="/gk_manual/docs/global_system/address_devices#блок-модульного-пожаротушения-бмп-r2">БМП</a> задан адрес **1**.**1**.**1**.**207**, то этот адрес соответствует самому <a href="/gk_manual/docs/global_system/address_devices#блок-модульного-пожаротушения-бмп-r2">БМП</a>, адреса **1**.**1**.**1**.**208** и **1**.**1**.**1**.**209** соответствуют датчикам "масса/двери, окна", адрес **1**.**1**.**1**.**210** соответствует выходу на пусковое устройство, адрес **1**.**1**.**1**.**211** - питание <a href="/gk_manual/docs/global_system/address_devices#блок-модульного-пожаротушения-бмп-r2">БМП</a>
