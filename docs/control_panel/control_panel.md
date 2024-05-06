---
layout: default
title: Панель управления
nav_order: 4
has_children: true
permalink: /docs/control_panel
---

# Панель управления и индикации
<p align="center">
<img src="../assets/images/control_panel.png">
</p>

## Считыватель карт доступа
Считыватель карт доступа является средством ограничения доступа посторонних лиц к прибору. Для работы с прибором сначала необходимо приложить карту доступа к считывателю.

## Световые индикаторы
Обобщенные световые индикаторы показывают текущее состояние ГК. Расшифровка направления отображается на сенсорном экране.

|Индикатор|Режим работы|
|:---|:---|
|<img src="../assets/icons/light_indicators/li_pusk.png" height="40" width="204">|Непрерывно светится красным при переходе ГК в [состояние ПУСК]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_pozhar.png" height="40" width="204">|Непрерывно светится красным при переходе ГК в состояние [состояние ПОЖАР]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_vnimanie.png" height="40" width="204">|Непрерывно светится красным при переходе ГК в [состояние ВНИМАНИЕ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_ostanov_puska.png" height="40" width="204">|Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты|
|<img src="../assets/icons/light_indicators/li_neispravnost.png" height="40" width="204">|Непрерывно светится желтым при переходе ГК в [состояние НЕИСПРАВНОСТЬ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_otkluchenie.png" height="40" width="204">|Непрерывно светится желтым при переходе ГК в [состояние ОТКЛЮЧЕНИЕ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_avt_otkluchena.png" height="40" width="204">|Непрерывно светится желтым при переходе ГК в [состояние АВТОМАТИКА ОТКЛЮЧЕНА]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_sist_oshibka.png" height="40" width="204">|Непрерывно светится желтым при неисправности составных модулей и/или при ошибке в программном обеспечении|
|<img src="../assets/icons/light_indicators/li_zvuk_otkl.png" height="40" width="204">|Непрерывно светится желтым при ручном отключении звуковой сигнализации|
|<img src="../assets/icons/light_indicators/li_pit_osn.png" width="204">|Непрерывно светится зеленым при наличии напряжения на основном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на основном входе выше или ниже нормы|
|<img src="../assets/icons/light_indicators/li_pit_rez.png" width="204">|Непрерывно светится зеленым при наличии напряжения на резервном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на резервном входе выше или ниже нормы|

## Клавиши управления
Доступ к клавишам управления ограничен профилями доступа пользователей. Работа с клавишами осуществляется однократным нажатием. Некоторые клавиши являются контекстными – функционируют только в меню-счетчика событий «ПУСК» при выборе определенного события.
