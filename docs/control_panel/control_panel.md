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
|<img src="../assets/icons/light_indicators/li_pusk.png">|Непрерывно светится красным при переходе ГК в [состояние ПУСК]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_pozhar.png">|Непрерывно светится красным при переходе ГК в состояние [состояние ПОЖАР]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_vnimanie.png">|Непрерывно светится красным при переходе ГК в [состояние ВНИМАНИЕ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_ostanov_puska.png">|Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты|
|<img src="../assets/icons/light_indicators/li_neispravnost.png">|Непрерывно светится желтым при переходе ГК в [состояние НЕИСПРАВНОСТЬ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_otkluchenie.png">|Непрерывно светится желтым при переходе ГК в [состояние ОТКЛЮЧЕНИЕ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_avt_otkluchena.png">|Непрерывно светится желтым при переходе ГК в [состояние АВТОМАТИКА ОТКЛЮЧЕНА]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_sist_oshibka.png">|Непрерывно светится желтым при неисправности составных модулей и/или при ошибке в программном обеспечении|
|<img src="../assets/icons/light_indicators/li_zvuk_otkl.png">|Непрерывно светится желтым при ручном отключении звуковой сигнализации|
|<img src="../assets/icons/light_indicators/li_pit_osn.png">|Непрерывно светится зеленым при наличии напряжения на основном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на основном входе выше или ниже нормы|
|<img src="../assets/icons/light_indicators/li_pit_rez.png">|Непрерывно светится зеленым при наличии напряжения на резервном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на резервном входе выше или ниже нормы|

## Клавиши управления
Доступ к клавишам управления ограничен профилями доступа пользователей. Работа с клавишами осуществляется однократным нажатием. Некоторые клавиши являются контекстными – функционируют только в меню-счетчика событий «ПУСК» при выборе определенного события.

|Клавиша|Режим работы|
|:---|:---|
|<img src="../assets/icons/keys/k_otmenit.png">||
|<img src="../assets/icons/keys/k_dobavit.png">||
|<img src="../assets/icons/keys/k_vyykluchit.png">||
|<img src="../assets/icons/keys/k_sbros_pozhara.png">|Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты|
|<img src="../assets/icons/keys/k_vkluchit.png">||
|<img src="../assets/icons/keys/k_vyykluchit_zvuk.png">|Отключает звуковую сигнализацию ГК до получения нового сигнала о неисправности, пожаре или пуске|
|<img src="../assets/icons/keys/k_vkluchit_zvuk.png" height="80">|Включает ранее отключенную звуковую сигнализацию|
