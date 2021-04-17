# Kapitel 1

Was gibt das folgende Programm aus?

```c++
int methode1(int* p, int i1){
    int i=1;
    for( ; i < i1; i*=2)
        *p += 1;
        printf("%i", *p );
    }
    return i;
}

int methode (){
    int i1 = 8;
    int i2 = 2;
    i1 = methode1(&i2, i1);
    printf("\ni1= %i" , i1);
    printf("\ni2= %i" , i2);
    return 0;
}
```

---

Start mit i1 = 8
Weiter mit i2 = 2
i1 wird in methode1 geschoben:
- aus i2 wird die adresse *p mit dem Wert 2
- für i1 is der Wert 8
Die Schleife beginnt mit 1
- 1+1=2

Dann wird die Schleife neu gestartet und vorher 2 auf 3 addiert = 5




