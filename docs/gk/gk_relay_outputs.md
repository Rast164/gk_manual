---
layout: default
title: Релейные выходы
parent: ГК
nav_order: 5
permalink: /docs/gk/gk_relay_outputs
---

# Релейные выходы ГК
ГК имеет три дискретных релейных выхода типа «сухой контакт». Выходы запрограммированы для передачи обобщенных сигналов «Неисправность», «Пуск» и «Пожар». Выходы формируют сигнал путем замыкания внешней цепи.

<table> 
  <thead> 
    <tr> 
      <th style="text-align: center" >Релейный выход</th>
      <th style="text-align: center">Описание</th>
    </tr>
  </thead> 
  <tbody>
    <tr>
      <td id="релейный_выход_гк_пуск" style="text-align: left">ПУСК</td>
      <td style="text-align: left">Замкнут при нахождении ГК в <a href="/gk_manual/docs/gk/gk_conditions#состояние_гк_пуск">состоянии ПУСК</a>, разомкнут в любом другом состоянии</td>
    </tr>
    <tr>
      <td id="релейный_выход_гк_пожар" style="text-align: left">ПОЖАР</td>
      <td style="text-align: left">Замкнут при нахождении ГК в <a href="/gk_manual/docs/gk/gk_conditions#состояние_гк_пожар">состоянии ПОЖАР</a>, разомкнут в любом другом состоянии</td>
    </tr>
    <tr>
      <td id="релейный_выход_гк_неисправность" style="text-align: left">НЕИСПРАВНОСТЬ</td>
      <td style="text-align: left">Замкнут при пропадании электропитания на основном и резервном вводе и при нахождении ГК в <a href="/gk_manual/docs/gk/gk_conditions#состояние_гк_неисправность">состоянии НЕИСПРАВНОСТЬ</a>, разомкнут в любом другом состоянии</td>
    </tr>
  </tbody>
</table>
