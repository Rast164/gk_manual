---
layout: default
title: Сенсорный экран
parent: Панель управления
nav_order: 1
---

# Сенсорный экран
Сенсорный экран является средством вывода текстовой и символьной информации и основным органом управления ГК. Доступ к сенсорному экрану ограничен <a href="/gk_manual/docs/intelligence/profiles#профили-доступа-пользователей">профилем доступа пользователей</a>.

<p align="center">
<img src="../../assets/images/touch_screen.png">
</p>

## Индикатор состояния
Индикатор состояния сенсорного экрана показывает <a href="/gk_manual/docs/intelligence/conditions#основные-состояния-гк">текущее состояние ГК</a>. 

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center">Индикатор</th>
      <th style="text-align: center">Режим работы</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_pusk.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_пуск">состояние ПУСК</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_pozhar.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_пожар">состояние ПОЖАР</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_vnimanie.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_внимание">состояние ВНИМАНИЕ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_neispravnost.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_неисправность">состояние НЕИСПРАВНОСТЬ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_otkluchenie.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_отключение">состояние ОТКЛЮЧЕНИЕ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_avt_otkluchena.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_автоматика_отключена">состояние АВТОМАТИКА ОТКЛЮЧЕНА</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_test.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_тест">состояние ТЕСТ</a></td>
    </tr>
    <tr>
      <td style="text-align: center"><img src="../../assets/icons/screen_indicator/si_dezhurnyi.png" width="210" height="30"></td>
      <td style="text-align: left">Включается при переходе ГК в <a href="/gk_manual/docs/intelligence/conditions#состояние_дежурный">состояние ДЕЖУРНЫЙ</a></td>
    </tr>
  </tbody>
</table>

{: .note }
> Индикаторы включаются исходя из приоритета ПУСК – ПОЖАР – ВНИМАНИЕ – НЕИСПРАВНОСТЬ – ОТКЛЮЧЕНИЕ – АВТ ОТКЛЮЧЕНА – ДЕЖУРНЫЙ.
>
> Индикатор ТЕСТ включается при ручном запуске функции тестирования

## Дата и время
Показывает системную дату и время. Настройка даты и времени осуществляется в меню НАСТРОЙКИ или при касании экрана в месте отображения даты и времени. 

{: .note }
> ГК выполняет автоматическую синхронизацию даты и времени только при подключении ГК к ПК с установленным программным обеспечением <a href="https://products.rubezh.ru/products/po_global_monitor-3356/" target="_blank">GLOBAL MONITOR</a>. Заводская настройка часов ГК соответствует московскому времени

## Текущий пользователь
Показывает «отображаемое имя» авторизованного пользователя. Если пользователь не авторизован, то поле остается пустым.

## Счетчик журнала
Показывает количество новых событий с момента последнего прочтения журнала.
