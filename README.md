# qa-lesson9-oop

![CI](https://github.com/sys010101/qa-lesson9-oop/actions/workflows/ci.yml/badge.svg)

## Lesson 9 — Câmpuri, Metode, Obiecte și Tipuri ENUM

Homework pentru cursul de QA Automation Engineering (Skillab).  
Demonstrează utilizarea conceptelor OOP: enum, constructori supraîncărcați cu `this()` și metode statice factory.

## Structură

```
src/main/java/com/raducraciun/homework/
├── BrowserType.java        # enum: CHROME, FIREFOX, EDGE
├── BrowserConfig.java      # câmpuri private, 3 constructori, factory method
└── TestConfigRunner.java   # demo: 4 instanțe + afiseazaConfig()
```

## Output

Browser: CHROME, Version: 120, Headless: true

Browser: FIREFOX, Version: 119, Headless: false

Browser: EDGE, Version: latest, Headless: false

Browser: CHROME, Version: latest, Headless: true