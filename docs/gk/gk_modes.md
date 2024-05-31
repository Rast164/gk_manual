---
layout: default
title: Режимы работы
parent: ГК
nav_order: 2
permalink: /docs/gk/gk_modes
---

# Режимы работы ГК
Для удобства использования [ГК] предусмотрены три режима его работы. 

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center" >Режим работы</th>
      <th style="text-align: center">Описание</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="режим_гк_технологический" style="text-align: left">ТЕХНОЛОГИЧЕСКИЙ</td>
      <td style="text-align: left">Режим предназначен для <a href="/gk_manual/docs/global_system#конфигурирование">конфигурирования</a>, <a href="/gk_manual/docs/global_system/address_number#адресный-номер-гк,-кау-и-тпу">адресации</a> и проверки общей работоспособности <a href="/gk_manual/docs/global_system#спз-глобал">системы</a>. В этом режиме <a href="/gk_manual/docs/gk#гк">ГК</a> не обрабатывает сигналы с <a href="/gk_manual/docs/address_devices#адресные-устройства">АУ</a> и не выполняет функции управления системами пожаротушения, дымоудаления, газоудаления, оповещения и иными инженерными и технологическими системами</td>
    </tr>
    <tr>
      <td id="режим_гк_отладка" style="text-align: left">ОТЛАДКА</td>
      <td style="text-align: left">Режим используется для настройки и тестирования <a href="/gk_manual/docs/global_system#спз-глобал">системы</a>. В этом режиме <a href="/gk_manual/docs/gk#гк">ГК</a> функционирует нормально, но не реагирует (звуковая сигнализация не включается, на экране не появляются события) на поступающие сигналы о неисправностях, пожарных тревогах и пусках. Журнал регистрирует все события</td>
    </tr>
    <tr>
      <td id="режим_гк_работа" style="text-align: left">РАБОТА</td>
      <td style="text-align: left">Основной режим работы <a href="/gk_manual/docs/gk#гк">ГК</a>. В этом режиме <a href="/gk_manual/docs/gk#гк">ГК</a> выполняет все функции</td>
    </tr>    
  </tbody>
</table>

Переход в ТЕХНОЛОГИЧЕСКИЙ режим работы производится при [конфигурировании системы]. Переход в режим ОТЛАДКА производится в меню <a href="/gk_manual/docs/global_os/main_menu/settings"><img src="../../assets/icons/menus/m_nastroyki.png" width="14" height="14"> НАСТРОЙКИ</a>.

[КАУ]: /gk_manual/docs/kau#кау
[конфигурировании системы]: /gk_manual/docs/global_system#конфигурирование
