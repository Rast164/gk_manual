---
layout: default
title: Ограничение доступа
parent: СПЗ Глобал
nav_order: 3
permalink: /docs/global_system/acms
---

# Ограничение доступа
Ограничение доступа посторонних лиц к компонентам системы построено на базе системы радиочастотной идентификации (RFID), состоящей из считывателей и карт доступа (RFID-меток). Считыватели располагаются на панели управления и индикации ГК и панели управления и индикации ТПУ. Карты доступа выдаются ответственному персоналу.

Без авторизации работа в системе ограничена. Авторизованные пользователи делятся на группы по уровню доступа. Система автоматически распознает пользователя, приложившего карту доступа к считывателю, определяет его имя и уровень доступа.

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center">Функция</th>
      <th style="text-align: center">Без авторизации</th>
      <th style="text-align: center">Оператор</th>
      <th style="text-align: center">Администратор</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td style="text-align: left">Просмотр основных состояний <a href="/gk_manual/docs/gk#гк">ГК</a></td>
      <td style="text-align: center">+</td>
      <td style="text-align: center">+</td>
      <td style="text-align: center">+</td>
    </tr>
    <tr>
      <td style="text-align: left">Выключение звуковой сигнализации <a href="/gk_manual/docs/gk#гк">ГК</a></td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">+</td>
      <td style="text-align: center">+</td>
    </tr>
    <tr>
      <td style="text-align: left">Просмотр основного меню (кроме меню НАСТРОЙКИ и ДОСТУП)</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">+</td>
      <td style="text-align: center">+</td>
    </tr>
    <tr>
      <td style="text-align: left">Доступ к органам управления (клавишам), в том числе сброс пожарной тревоги</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">+</td>
      <td style="text-align: center">+</td>
    </tr>
    <tr>
      <td style="text-align: left">Управление устройствами, сценариями и пожарными зонами</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">+</td>
      <td style="text-align: center">+</td>
    </tr>
    <tr>
      <td style="text-align: left">Просмотр меню НАСТРОЙКИ (управление настройками <a href="/gk_manual/docs/gk#гк">ГК</a>) и ДОСТУП (управление пользователями)</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">+</td>
    </tr>
    <tr>
      <td style="text-align: left">Просмотр меню настроек устройств, сценариев и пожарных зон</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">-</td>
      <td style="text-align: center">+</td>
    </tr>
   </tbody>
</table>

Добавление новых пользователей и запись соответствующих карт доступа в систему осуществляется в меню ДОСТУП. Карты доступа, входящие в комплект поставки ГК и ТПУ, записываюся заводом-изготовителем.
