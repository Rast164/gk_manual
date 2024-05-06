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

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center" colspan="2">Индикатор</th>
      <th style="text-align: center">Режим работы</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_pusk.png" width="50" height="50"></td>
      <td style="text-align: left">ПУСК</td>
      <td style="text-align: left">Непрерывно светится красным при переходе ГК в <a href="/gk_manual/docs/getting_started#основные-состояния-гк">состояние ПУСК</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_pozhar.png" width="50" height="50"></td>
      <td style="text-align: left">ПОЖАР</td>
      <td style="text-align: left">Непрерывно светится красным при переходе ГК в состояние <a href="/gk_manual/docs/getting_started#основные-состояния-гк">состояние ПОЖАР</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_vnimanie.png" width="50" height="50"></td>
      <td style="text-align: left">ВНИМАНИЕ</td>
      <td style="text-align: left">Непрерывно светится красным при переходе ГК в <a href="/gk_manual/docs/getting_started#основные-состояния-гк">состояние ВНИМАНИЕ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_ostanov_puska.png" width="50" height="50"></td>
      <td style="text-align: left">ОСТАНОВ ПУСКА</td>
      <td style="text-align: left">Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты</td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_neispravnost.png" width="50" height="50"></td>
      <td style="text-align: left">НЕИСПРАВ</td>
      <td style="text-align: left">Непрерывно светится желтым при переходе ГК в <a href="/gk_manual/docs/getting_started#основные-состояния-гк">состояние НЕИСПРАВНОСТЬ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_otkluchenie.png" width="50" height="50"></td>
      <td style="text-align: left">ОТКЛЮЧЕНИЕ</td>
      <td style="text-align: left">Непрерывно светится желтым при переходе ГК в <a href="/gk_manual/docs/getting_started#основные-состояния-гк">состояние ОТКЛЮЧЕНИЕ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_avt_otkluchena.png" width="50" height="50"></td>
      <td style="text-align: left">АВТ ОТКЛЮЧЕНА</td>
      <td style="text-align: left">Непрерывно светится желтым при переходе ГК в <a href="/gk_manual/docs/getting_started#основные-состояния-гк">состояние АВТОМАТИКА ОТКЛЮЧЕНА</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_sist_oshibka.png" width="50" height="50"></td>
      <td style="text-align: left">СИСТ ОШИБКА</td>
      <td style="text-align: left">Непрерывно светится желтым при неисправности составных модулей и/или при ошибке в программном обеспечении</td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_zvuk_otkl.png" width="50" height="50"></td>
      <td style="text-align: left">ЗВУК ОТКЛ</td>
      <td style="text-align: left">Непрерывно светится желтым при ручном отключении звуковой сигнализации</td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_pit_osn.png" width="50" height="50"></td>
      <td style="text-align: left">ПИТ ОСН</td>
      <td style="text-align: left">Непрерывно светится зеленым при наличии напряжения на основном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на основном входе выше или ниже нормы</td> 
    </tr>
    <tr>
      <td style="text-align: center"><img src="../assets/icons/light_indicators/li_pit_rez.png" width="50" height="50"></td>
      <td style="text-align: left">ПИТ РЕЗ</td>
      <td style="text-align: left">Непрерывно светится зеленым при наличии напряжения на резервном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на резервном входе выше или ниже нормы</td> 
    </tr>
  </tbody>
</table>

|Иконка|Название|Режим работы|
|:---:|:---|:---|
|<img src="../assets/icons/light_indicators/li_pusk.png" width="50" height="50">|ПУСК|Непрерывно светится красным при переходе ГК в [состояние ПУСК]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_pozhar.png" width="50" height="50">|ПОЖАР|Непрерывно светится красным при переходе ГК в состояние [состояние ПОЖАР]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_vnimanie.png" width="50" height="50">|ВНИМАНИЕ|Непрерывно светится красным при переходе ГК в [состояние ВНИМАНИЕ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_ostanov_puska.png" width="50" height="50">|ОСТАНОВ ПУСКА|Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты|
|<img src="../assets/icons/light_indicators/li_neispravnost.png" width="50" height="50">|НЕИСПРАВ|Непрерывно светится желтым при переходе ГК в [состояние НЕИСПРАВНОСТЬ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_otkluchenie.png" width="50" height="50">|ОТКЛЮЧЕНИЕ|Непрерывно светится желтым при переходе ГК в [состояние ОТКЛЮЧЕНИЕ]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_avt_otkluchena.png" width="50" height="50">|АВТ ОТКЛЮЧЕНА|Непрерывно светится желтым при переходе ГК в [состояние АВТОМАТИКА ОТКЛЮЧЕНА]({% link docs/getting_started/getting_started.md %}#основные-состояния-гк)|
|<img src="../assets/icons/light_indicators/li_sist_oshibka.png" width="50" height="50">|СИСТ ОШИБКА|Непрерывно светится желтым при неисправности составных модулей и/или при ошибке в программном обеспечении|
|<img src="../assets/icons/light_indicators/li_zvuk_otkl.png" width="50" height="50">|ЗВУК ОТКЛ|Непрерывно светится желтым при ручном отключении звуковой сигнализации|
|<img src="../assets/icons/light_indicators/li_pit_osn.png" width="50" height="50">|ПИТ ОСН|Непрерывно светится зеленым при наличии напряжения на основном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на основном входе выше или ниже нормы|
|<img src="../assets/icons/light_indicators/li_pit_rez.png" width="50" height="50">|ПИТ РЕЗ|Непрерывно светится зеленым при наличии напряжения на резервном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на резервном входе выше или ниже нормы|

## Клавиши управления
Доступ к клавишам управления ограничен профилями доступа пользователей. Работа с клавишами осуществляется однократным нажатием. Некоторые клавиши являются контекстными – функционируют только в меню-счетчика событий «ПУСК» при выборе определенного события.

|Иконка|Название|Режим работы|
|:---:|:---|:---|
|<img src="../assets/icons/keys/k_otmenit.png" width="50" height="50">|ОТМЕНИТЬ <br>(задержка пуска)||
|<img src="../assets/icons/keys/k_dobavit.png" width="50" height="50">|ДОБАВИТЬ <br>(задержка пуска)||
|<img src="../assets/icons/keys/k_vyykluchit.png" width="50" height="50">|ВЫКЛЮЧИТЬ||
|<img src="../assets/icons/keys/k_sbros_pozhara.png" width="50" height="50">|СБРОС ПОЖАРА|Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты|
|<img src="../assets/icons/keys/k_vkluchit.png" width="50" height="50">|ВКЛЮЧИТЬ||
|<img src="../assets/icons/keys/k_vyykluchit_zvuk.png" width="50" height="50">|ВЫКЛЮЧИТЬ <br>(звук)|Отключает звуковую сигнализацию до получения ГК нового сообщения о неисправности, пожаре или пуске|
|<img src="../assets/icons/keys/k_vkluchit_zvuk.png" width="50" height="50">|ВКЛЮЧИТЬ <br>(звук)|Включает отключенную звуковую сигнализацию|
