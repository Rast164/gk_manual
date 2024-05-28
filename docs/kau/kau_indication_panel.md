---
layout: default
title: Панель индикации
parent: КАУ
nav_order: 4
permalink: /docs/kau/kau_indication_panel
---

# Панель индикации КАУ
<p align="center">
<img src="../../assets/images/control_panel.png">
</p>

## Световые индикаторы
Световые индикаторы показывают текущие [состояния КАУ]. Расшифровка по направлениям отображается на сенсорном экране [ГК] и/или [ТПУ].

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center" colspan="2">Световой индикатор</th>
      <th style="text-align: center">Режим работы</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="световой_индикатор_кау_пуск" style="text-align: center"><img src="../../assets/icons/light_indicators/li_pusk.png" width="50" height="50"></td>
      <td style="text-align: left">ПУСК</td>
      <td style="text-align: left">Непрерывно светится красным при переходе в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_пуск">состояние ПУСК</a></td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_пожар" style="text-align: center"><img src="../../assets/icons/light_indicators/li_pozhar.png" width="50" height="50"></td>
      <td style="text-align: left">ПОЖАР</td>
      <td style="text-align: left">Непрерывно светится красным при переходе в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_пожар">состояние ПОЖАР</a></td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_внимание" style="text-align: center"><img src="../../assets/icons/light_indicators/li_vnimanie.png" width="50" height="50"></td>
      <td style="text-align: left">ВНИМАНИЕ</td>
      <td style="text-align: left">Непрерывно светится красным при переходе ГК в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_внимание">состояние ВНИМАНИЕ</a></td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_останов_пуска" style="text-align: center"><img src="../../assets/icons/light_indicators/li_ostanov_puska.png" width="50" height="50"></td>
      <td style="text-align: left">ОСТАНОВ ПУСКА</td>
      <td style="text-align: left">Непрерывно светится желтым при ручной приостановке пуска одного или более сценария или устройства системы противопожарной защиты</td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_неисправ" style="text-align: center"><img src="../../assets/icons/light_indicators/li_neispravnost.png" width="50" height="50"></td>
      <td style="text-align: left">НЕИСПРАВ</td>
      <td style="text-align: left">Непрерывно светится желтым при переходе в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_неисправность">состояние НЕИСПРАВНОСТЬ</a></td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_отключение" style="text-align: center"><img src="../../assets/icons/light_indicators/li_otkluchenie.png" width="50" height="50"></td>
      <td style="text-align: left">ОТКЛЮЧЕНИЕ</td>
      <td style="text-align: left">Непрерывно светится желтым при переходе ГК в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_отключение">состояние ОТКЛЮЧЕНИЕ</a></td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_авт_отключена" style="text-align: center"><img src="../../assets/icons/light_indicators/li_avt_otkluchena.png" width="50" height="50"></td>
      <td style="text-align: left">АВТ ОТКЛЮЧЕНА</td>
      <td style="text-align: left">Непрерывно светится желтым при переходе ГК в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_автоматика_отключена">состояние АВТОМАТИКА ОТКЛЮЧЕНА</a></td>
    </tr>
    <tr>
      <td id="световой_индикатор_кау_сист_ошибка" style="text-align: center"><img src="../../assets/icons/light_indicators/li_sist_oshibka.png" width="50" height="50"></td>
      <td style="text-align: left">СИСТ ОШИБКА</td>
      <td style="text-align: left">Непрерывно светится желтым при неисправности <a href="/gk_manual/docs/composite_modules#составные-модули">составных модулей</a> и/или при ошибке <a href="/gk_manual/docs/global_os#global-os">встроенной ОС</a></td>
    </tr>    
    <tr>
      <td id="световой_индикатор_кау_пит_осн" style="text-align: center"><img src="../../assets/icons/light_indicators/li_pit_osn.png" width="50" height="50"></td>
      <td style="text-align: left">ПИТ ОСН</td>
      <td style="text-align: left">Непрерывно светится зеленым при наличии напряжения на основном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на основном входе выше или ниже нормы</td> 
    </tr>
    <tr>
      <td id="световой_индикатор_кау_пит_рез" style="text-align: center"><img src="../../assets/icons/light_indicators/li_pit_rez.png" width="50" height="50"></td>
      <td style="text-align: left">ПИТ РЕЗ</td>
      <td style="text-align: left">Непрерывно светится зеленым при наличии напряжения на резервном входе электропитания. Мигает зеленым с частотой 1 Гц при напряжении питания на резервном входе выше или ниже нормы</td> 
    </tr>
  </tbody>
</table>

[состояния КАУ]: /gk_manual/docs/kau/kau_conditions#состояния-кау
[ГК]: /gk_manual/docs/gk#гк
<a href="/gk_manual/docs/tpu#тпу">ТПУ</a>
