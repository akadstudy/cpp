# Zusammengesetzte Datentypen

## Kapitel 5

Was ist an folgendem Programmstück falsch?

```cpp
int quadrate[10];

for ( int i=0; i<=10; i++ )

quadrate[i] = i*i;
```
Weshalb ist es gefährlich, auf das Array mit einem Index zuzugreifen, der außerhalb der Array-Grenzen liegt?

---

Warum lehnt der Compiler die Übersetzung folgender Zeile ab?

```cpp
cout << parteien[rot + gelb];
```