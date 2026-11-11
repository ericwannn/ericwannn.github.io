---
layout: post
title: "CUDA kick-start"
date: 2018-04-11 00:00:00 +0800
categories: ["Programming"]
tags: ["programming", "CUDA", "parallel programming"]
---

- How CUDA works

CUDA accelerates computations following a *single instruction multiple thread* (SIMT) parallelism pattern.

CUDA GPU has multiple cores (threads) containing one ALU and one FPU (which are not important here). A streaming Multiprocessor (SM) has multiple cores.

By saying SIMT, CUDA breaks down a computation (one instruction) into several

- CUDA API & C extension
