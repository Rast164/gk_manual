---
layout: default
title: Адресные устройства
parent: СПЗ Глобал
nav_order: 3
has_children: true
permalink: /docs/global_system/address_devices
---

# Адресные устройства
## Системные параметры адресных устройств
<table> 
  <thead> 
    <tr> 
      <th style="text-align: center">Параметр</th>
      <th style="text-align: center">Описание</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="краткое_название_устройства" style="text-align: left">Краткое название</td>
      <td style="text-align: left">Наименование устройства в пользовательском интерфейсе ГК и <a href="/gk_manual/docs/global_system/tpu">ТПУ</a></td>
    </tr>
    <tr>
      <td id="обозначение_устройства" style="text-align: left">Обозначение</td>
      <td style="text-align: left">Полное обозначение устройства в пользовательском интерфейсе ГК и <a href="/gk_manual/docs/global_system/tpu">ТПУ</a></td>
    </tr>
    <tr>
      <td id="краткое_обозначение_устройства" style="text-align: left">Краткое обозначение</td>
      <td style="text-align: left">Краткое обозначение устройства. Используется для фильтра устройств в пользовательском интерфейсе ГК и <a href="/gk_manual/docs/global_system/tpu">ТПУ</a></td>
    </tr>
    <tr>
      <td id="количество_адресов" style="text-align: left">Количествово адресов</td>
      <td style="text-align: left">Количество <a href="/gk_manual/docs/global_system#адресный-номер-ау">адресных номеров</a>, которое устройство занимает в <a href="/gk_manual/docs/global_system">СПЗ</a></td>
    </tr>
    <tr>
      <td id="устройство_противопожарной_защиты" style="text-align: left">Устройство противопожарной защиты</td>
      <td style="text-align: left">Относится ли запуск (включение) устройства к активации систем противопожарной защиты по п. 7.1.4 ГОСТ Р 53325 (приводит ли запуск (включение) устройства к переходу ГК или <a href="/gk_manual/docs/global_system/kau">КАУ</a> в <a href="/gk_manual/docs/intelligence/conditions#состояние_пуск">состояние ПУСК</a>)</td>
    </tr>
  </tbody>
</table>

{: .note }
> <details markdown="block"><summary>Перечень систем противопожарной защиты по п. 7.1.4 ГОСТ Р 53325</summary>
  - система управления установками водяного и пенного пожаротушения;
  - система управления установками газового пожаротушения;
  - система управления установками порошкового пожаротушения;
  - система управления установками аэрозольного пожаротушения;
  - система управления средствами оповещения;
  - система управления установками дымо-газоудаления;
  - система формирования сигнала управления инженерным, технологическим оборудованием и иными устройствами, участвующими в обеспечении пожарной безопасности;
  - система комбинированные.

## Режим работы адресных устройств

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center">Положение переключателец</th>
      <th style="text-align: center">Режим работы</th>
      <th style="text-align: center">Описание</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="режим_работы_дежурный" style="text-align: center"><img src="../../assets/icons/operating_mode/om_normal.png" width="150" height="40"></td>
      <td style="text-align: left">ДЕЖУРНЫЙ</td>
      <td style="text-align: left">Устройство работает нормально (штатно)</td>
    </tr>
  </tbody>
</table>
