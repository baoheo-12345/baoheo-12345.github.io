---
title: "Exception trong Java"
date: 2025-12-26
draft: false
tags: ["Java"]
---

## Exception là gì?
Exception là lỗi xảy ra khi chương trình đang chạy.

## Try – Catch
```java
try {
    int a = 10 / 0;
} catch (Exception e) {
    System.out.println("Lỗi chia cho 0");
}