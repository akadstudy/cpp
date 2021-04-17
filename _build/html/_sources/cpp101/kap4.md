# Strukturierte Anweisungen

## Kapitel 4

**Switch** ohne default Was passiert bei einer **switch**-Anweisung ohne **default**-Fall, wenn keiner der Normalfälle zutrifft?

Es passiert nichts. Es ist aber *best practice* einen default-Anweisung zu schreiben.

---

Die while-Schleife und die for-Schleife sind kopfgesteuert. Beide haben einen Anfangstest. Sie lassen sich ineinander umformen. Formen Sie die folgende for-Schleife in eine while-Schleife um.

```cpp
for ( int i=10; i>0; i-- ) 
    cout << i*i << ' ';

// Ausgabe: 
100 81 64 49 36 25 16 9 4 1
```


```cpp
int i = 10;

while  i > 0)
{
    cout << i * i << ' ';
 i--;
}
```

---

Zwei einfache Anweisungen werden durch ein Semikolon getrennt. Ist diese Aussage richtig?

Aussage ist falsch.
Semikolon gehört zur ersten Anweisung.