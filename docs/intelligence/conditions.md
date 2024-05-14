---
layout: default
title: Состояния ГК
parent: Основные сведения
nav_order: 6
permalink: /docs/intelligence/conditions
---

# Основные состояния ГК
В зависимости от поступающих сигналов от устройств и от действий пользователя, ГК может находиться в одном или нескольких состояниях.

Переход в каждое состояние сопровождается включением соответствующих световых индикаторов, релейных выходов, индикатора состояния сенсорного экрана и счетчика событий.

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center" >Состояние</th>
      <th style="text-align: center">Условие перехода в состояние</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="состояние_пуск" style="text-align: left">ПУСК</td>
      <td style="text-align: left">При запуске одного или более сценария или <a href="/gk_manual/docs/intelligence/compatibility.html#Список-совместимых-адресных-устройств">АУ</a> системы противопожарной защиты</td>
    </tr>
    <tr>
      <td id="состояние_пожар" style="text-align: left">ПОЖАР</td>
      <td style="text-align: left">При получении данных от <a href="/gk_manual/docs/intelligence/compatibility.html#извещатели">извещателей пожарных</a>, которые при обработке идентифицируются, как сигнал о пожаре</td>
    </tr>
    <tr>
      <td id="состояние_внимание" style="text-align: left">ВНИМАНИЕ</td>
      <td style="text-align: left">При получении данных от <a href="/gk_manual/docs/intelligence/compatibility.html#извещатели">извещателей пожарных</a>, которые при обработке идентифицируются, как сигнал о предварительной пожарной тревоге</td>
    </tr>
    <tr>
      <td id="состояние_неисправность" style="text-align: left">НЕИСПРАВНОСТЬ</td>
      <td style="text-align: left">При обрыве или коротком замыкании <a href="/gk_manual/docs/intelligence/communications_lines.html#адресная-линия-связи">АЛС</a>. При нарушении связи с одним или более подключенным по <a href="/gk_manual/docs/intelligence/communications_lines.html#адресная-линия-связи">АЛС</a> или <a href="/gk_manual/docs/intelligence/communications_lines.html#цифровая-линия-связи">PFM</a> устройством. При неисправности одного или более подключенного по <a href="/gk_manual/docs/intelligence/communications_lines.html#адресная-линия-связи">АЛС</a> или <a href="/gk_manual/docs/intelligence/communications_lines.html#цифровая-линия-связи">PFM</a> устройства. При отсутствии сигналов о срабатывании одного или более <a href="/gk_manual/docs/intelligence/compatibility.html#Список-совместимых-адресных-устройств">АУ</a> системы противопожарной защиты после передачи сигнала об активации таких <a href="/gk_manual/docs/intelligence/compatibility.html#Список-совместимых-адресных-устройств">АУ</a>. При напряжении электропитания ниже или выше нормы или при отсутствии напряжения на основном и/или резервном входе электропитания. При вскрытии крышки корпуса</td>
    </tr>
    <tr>
      <td id="состояние_отключение" style="text-align: left">ОТКЛЮЧЕНИЕ</td>
      <td style="text-align: left">При отключении сценария, пожарной зоны, <a href="/gk_manual/docs/intelligence/modules.html#составные-модули">составного модуля</a> или <a href="/gk_manual/docs/intelligence/compatibility.html#Список-совместимых-адресных-устройств">АУ</a></td>
    </tr>
    <tr>
      <td id="состояние_автоматика_отключена" style="text-align: left">АВТОМАТИКА ОТКЛЮЧЕНА</td>
      <td style="text-align: left">При отключении автоматики (переводе в ручной режим работы) сценария или <a href="/gk_manual/docs/intelligence/compatibility.html#Список-совместимых-адресных-устройств">АУ</a></td>
    </tr>
    <tr>
      <td id="состояние_тест" style="text-align: left">ТЕСТ</td>
      <td style="text-align: left">При запуске функции тестирования</td>
    </tr>
    <tr>
      <td id="состояние_дежурный" style="text-align: left">ДЕЖУРНЫЙ</td>
      <td style="text-align: left">Нормальное рабочее состояние (при отсутствии условия для перехода в другие состояние)</td>
    </tr>
  </tbody>
</table>
