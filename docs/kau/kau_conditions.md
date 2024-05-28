---
layout: default
title: Состояния
parent: КАУ
nav_order: 3
permalink: /docs/kau/kau_conditions
---

# Состояния КАУ
В зависимости от поступающих сигналов от устройств и от действий пользователя, [КАУ] может находиться в одном или нескольких состояниях.

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center" >Состояние</th>
      <th style="text-align: center">Условие перехода в состояние</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="состояние_кау_пуск" style="text-align: left">ПУСК</td>
      <td style="text-align: left">При запуске одного или более сценария или <a href="/gk_manual/docs/address_devices#адресные-устройства">АУ</a> системы противопожарной защиты</td>
    </tr>
    <tr>
      <td id="состояние_кау_пожар" style="text-align: left">ПОЖАР</td>
      <td style="text-align: left">При получении данных от <a href="/gk_manual/docs/address_devices/detectors#извещатели">извещателей пожарных</a>, которые при обработке идентифицируются, как сигнал о пожаре</td>
    </tr>
    <tr>
      <td id="состояние_кау_внимание" style="text-align: left">ВНИМАНИЕ</td>
      <td style="text-align: left">При получении данных от <a href="/gk_manual/docs/address_devices/detectors#извещатели">извещателей пожарных</a>, которые при обработке идентифицируются, как сигнал о предварительной пожарной тревоге</td>
    </tr>
    <tr>
      <td id="состояние_кау_неисправность" style="text-align: left">НЕИСПРАВНОСТЬ</td>
      <td style="text-align: left">При обрыве или коротком замыкании <a href="/gk_manual/docs/global_system/communications_lines#адресная-линия-связи">АЛС</a>. При нарушении связи с одним или более подключенным по <a href="/gk_manual/docs/global_system/communications_lines#адресная-линия-связи">АЛС</a> или <a href="/gk_manual/docs/global_system/communications_lines#цифровая-линия-связи">PFM</a> устройством. При неисправности одного или более подключенного по <a href="/gk_manual/docs/global_system/communications_lines#адресная-линия-связи">АЛС</a> или <a href="/gk_manual/docs/global_system/communications_lines#цифровая-линия-связи">PFM</a> устройства. При отсутствии сигналов о срабатывании одного или более <a href="/gk_manual/docs/address_devices#адресные-устройства">АУ</a> системы противопожарной защиты после передачи сигнала об активации таких <a href="/gk_manual/docs/address_devices#адресные-устройства">АУ</a>. При напряжении электропитания ниже или выше нормы или при отсутствии напряжения на основном и/или резервном входе электропитания. При вскрытии крышки корпуса</td>
    </tr>
    <tr>
      <td id="состояние_кау_отключение" style="text-align: left">ОТКЛЮЧЕНИЕ</td>
      <td style="text-align: left">При отключении <a href="/gk_manual/docs/zones#пожарные-зоны">пожарной зоны</a>, <a href="/gk_manual/docs/scenarios#сценарии">сценария</a>, <a href="/gk_manual/docs/composite_modules#составные-модули">составного модуля</a> или <a href="/gk_manual/docs/address_devices#адресные-устройства">АУ</a></td>
    </tr>
    <tr>
      <td id="состояние_кау_автоматика_отключена" style="text-align: left">АВТОМАТИКА ОТКЛЮЧЕНА</td>
      <td style="text-align: left">При отключении автоматики (переводе в ручной режим работы) <a href="/gk_manual/docs/scenarios#сценарии">сценария</a> или <a href="/gk_manual/docs/address_devices#адресные-устройства">АУ</a></td>
    </tr>
    <tr>
      <td id="состояние_кау_тест" style="text-align: left">ТЕСТ</td>
      <td style="text-align: left">При запуске функции тестирования</td>
    </tr>
    <tr>
      <td id="состояние_кау_дежурный" style="text-align: left">ДЕЖУРНЫЙ</td>
      <td style="text-align: left">Нормальное рабочее состояние (отсутствие условий для перехода в другие состояние)</td>
    </tr>
  </tbody>
</table>

Переход в каждое состояние сопровождается включением соответствующих [световых индикаторов] и [релейных выходов].

[КАУ]: /gk_manual/docs/kau#кау
[световых индикаторов]: /gk_manual/docs/kau/kau_control_panel#световые-индикаторы
[релейных выходов]: /gk_manual/docs/kau/kau_relay_outputs#релейные-выходы
