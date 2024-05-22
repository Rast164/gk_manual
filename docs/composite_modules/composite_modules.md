---
layout: default
title: Составные модули
nav_order: 5
has_children: false
permalink: /docs/composite_modules
has_toc: false
---

# Составные модули
Составные модули размещаются на DIN-рейке внутри корпуса <a href="/gk_manual/docs/gk#гк">ГК</a> и <a href="/gk_manual/docs/kau#кау">КАУ</a>. Связь между модулями осуществляется по [ВШС]({% link docs/intelligence/communications_lines.md %}#внутренняя-шина-связи).

## Модуль центрального процессора
<p align="center">
<img src="../../assets/images/mcp.png">
</p>
МЦП обеспечивает основной функционал <a href="/gk_manual/docs/gk#гк">ГК</a> и <a href="/gk_manual/docs/kau#кау">КАУ</a> Для защиты от системной ошибки, приводящей к неисправности <a href="/gk_manual/docs/gk#гк">ГК</a> и <a href="/gk_manual/docs/kau#кау">КАУ</a>, вызванной полным или частичным отказом МЦП, предусмотрена возможность его резервирования путем добавления дополнительного модуля МЦП в состав <a href="/gk_manual/docs/gk#гк">ГК</a> и <a href="/gk_manual/docs/kau#кау">КАУ</a>

<a href="/gk_manual/docs/gk#гк">ГК</a> и <a href="/gk_manual/docs/kau#кау">КАУ</a> в своем составе имеют один или два МЦП.

## Модуль кольцевых адресных линий связи
<p align="center">
<img src="../../assets/images/mka.png">
</p>
МКА предназначен для увеличения количества подключаемых к <a href="/gk_manual/docs/gk#гк">ГК</a> и <a href="/gk_manual/docs/kau#кау">КАУ</a> <a href="/gk_manual/docs/intelligence/communications_lines#адресная-линия-связи">АЛС</a>, что позволяет увеличить количество подключенных <a href="/gk_manual/docs/global_system/address_devices#адресные-устройства">АУ</a>.

## Модуль дискретных входных сигналов с контролем цепи
<p align="center">
<img src="../../assets/images/mdi.png">
</p>
МДИ предназначен для приема дискретных электрических сигналов. МДИ осуществляет автоматический контроль исправности [ВхЛС]({% link docs/intelligence/communications_lines.md %}#входная-дискретная-линия-связи) на обрыв и короткое замыкание.

## Модуль дискретных выходных сигналов с контролем цепи

<p align="center">
<img src="../../assets/images/mdo.png">
</p>
МДО предназначен для передачи дискретных электрических сигналов. МДО осуществляет автоматический контроль исправности [ВыхЛС]({% link docs/intelligence/communications_lines.md %}#выходная-дискретная-линия-связи) на обрыв и короткое замыкание.
