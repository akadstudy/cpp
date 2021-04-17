# Ausdrücke und Anweisungen

## Kapitel 3

Welchen Wert liefert 100/3? Beachten Sie, dass beide Operanden vom Typ int sind!

33

Weil der Datentyp für beide Zahlen int ist, wird auch das Ergebnis int.

---

Sind **k+=1** und **k++** gleichwertig?

k+=1 ist die **Abkürzung** für k = k + 1

k++ ist eine **Abkürzung** für eine Iteration um den Wert 1

Ja in diesem Fall sind sie gleichwertig!

---

Weisen Sie an Hand des obigen Syntaxdiagrammes nach, dass -(3+8)*23 + anzahl*4 ein korrekter (arithmetischer) Ausdruck ist!

---

Eine boolesche Variable weiter soll auf true gesetzt werden, wenn die char-Variable c ein Zeichen 'J' oder 'j' enthält, anderenfalls soll sie false werden. Sie brauchen dazu nur eine Anweisung.

&& und
|| oder
!= nicht

apfel != kartoffel
apfel || kartoffel
apfel && kartoffel

```cpp
weiter = ( (c == 'j' ) || ( c == 'J') );
```