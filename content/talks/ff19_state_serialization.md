+++
author = "RG"
title = "Extending flink state serialization"
date = "2019-10-09"
description = "Operations with Flink state are a common source of performance issues for a typical stateful stream processing application. One tiny mistake can easily make your job to spend most of a precious CPU time in serialization and inflate a checkpoint size to the sky. In this talk we’ll focus on a Flink serialization framework and common problems happening around it"
tags = ["flink", "performance","data processing", "scala"]
+++

Operations with Flink state are a common source of performance issues for a typical stateful stream processing application. One tiny mistake can easily make your job to spend most of a precious CPU time in serialization and inflate a checkpoint size to the sky. In this talk we’ll focus on a Flink serialization framework and common problems happening around it:

* Is Kryo fallback is really that expensive from the CPU and state size perspective?
* How to plug your own or existing serializers into the Flink (like protobuf).
* Using Scala sealed traits without Kryo fallback.
* Using custom integer variable-length encoding and delta encoding for primitive arrays to further reduce the state size.

Presented at Flink Forward Europe 2019

[Link](https://europe-2019.flink-forward.org/conference-program#extending-flink-state-serialization-for-better-performance-and-smaller-checkpoint-size) | [Video](https://www.youtube.com/watch?v=7M5or85WMNs&list=PLDX4T_cnKjD207Aa8b5CsZjc7Z_KRezGz&index=37) | [Slides](/slides/ff19_state_serialization.pdf)
{{< youtube 7M5or85WMNs >}}