# Практическая работа №1

---

## *Делимся проектом с миром*

---

### **Список** **ненумерованный**

- пункт номер один
- пункт номер два
- пункт номер три

---

### **Список** **нумерованный**

1. пункт номер один
2. пункт номер два
3. пункт номер три

---

### Пример кода

```
mkdir <Builddir>
cd <Builddir>
cmake "-DTOOLCHAIN_PREFIX=<PathToArmGccCompiler>" -G "MinGW Makefiles" <PathToProject>
mingw32-make GPSLogger.bin
```

---