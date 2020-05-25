+++
author = "RG"
title = "Case classes ate my RAM"
date = "2018-04-07"
description = "Case class is a most widely used way to model your data. But when the data is huge, you can amazingly discover that only a tiny 10% of your precious RAM used for the data itself. But where is other 90%?"
tags = ["memory", "performance","scala"]
+++

Case class is a most widely used way to model your data. But when the data is huge, you can amazingly discover that only a tiny 10% of your precious RAM used for the data itself. But where is other 90%?

During this talk, you will have a deep dive to the JVM internals learning about case class layout, Scala collections true memory overhead and ways to decrease it. We'll introduce a scala-packed, the project helped Findify to solve a real-life case of reducing memory usage by an order of magnitude by extending Scala collections with transparent Shapeless-based case class <-> Array[Byte] packing.

Presented at SCALAR 2018, Scala.io 2017, Scala User Group Voronezh 2018

[Link](https://scalar-conf.com/2018/) | [Video](https://youtu.be/cJ4OE742bbE) | [Slides](/slides/scala_ate_my_ram) | [Slides rus](/slides/scala_ate_my_ram)
{{< youtube cJ4OE742bbE >}}