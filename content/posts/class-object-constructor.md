---
title: "Class, Object và Constructor trong Java"
date: 2025-12-26
draft: false
tags: ["Java"]
---

## Class là gì?
Class là bản thiết kế cho đối tượng.

## Object là gì?
Object là thể hiện cụ thể của class.

## Constructor là gì?
Constructor dùng để khởi tạo object.

## Ví dụ
```java
class Student {
    String name;

    Student(String name) {
        this.name = name;
    }
}

public class Main {
    public static void main(String[] args) {
        Student s = new Student("Bao");
        System.out.println(s.name);
    }
}