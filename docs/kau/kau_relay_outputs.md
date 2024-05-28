---
layout: default
title: Релейные выходы
parent: КАУ
nav_order: 5
permalink: /docs/kau/kau_relay_outputs
---

# Релейные выходы КАУ
[КАУ] имеет три дискретных релейных выхода типа «сухой контакт». Выходы запрограммированы для передачи обобщенных сигналов «Неисправность», «Пуск» и «Пожар». Выходы формируют сигнал путем замыкания внешней цепи.

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
      <td style="text-align: left">Замкнут при переходе в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_пуск">состояние ПУСК</a>, разомкнут в любом другом состоянии</td>
    </tr>
    <tr>
      <td id="релейный_выход_гк_пожар" style="text-align: left">ПОЖАР</td>
      <td style="text-align: left">Замкнут при переходе в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_пожар">состояние ПОЖАР</a>, разомкнут в любом другом состоянии</td>
    </tr>
    <tr>
      <td id="релейный_выход_гк_неисправность" style="text-align: left">НЕИСПРАВНОСТЬ</td>
      <td style="text-align: left">Замкнут при пропадании электропитания на основном и резервном вводе и/или при переходе в <a href="/gk_manual/docs/kau/kau_conditions#состояние_кау_неисправность">состояние НЕИСПРАВНОСТЬ</a>, разомкнут в любом другом состоянии</td>
    </tr>
  </tbody>
</table>

[КАУ]: /gk_manual/docs/kau#кау
