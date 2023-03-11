esse é um dos codigos

esse codigo é usado APENAS se voce for usar as Funçoes "for" ou "while".

o codigo pula o que vc n quer no loop

Exemplo:
```
var haha:Array<Int> = [1, 2, 3, 4, 5];

for(number in haha)
{
    if(number % 2 == 0)
        continue;
    
    trace(number);
}
```

Agora Vamos Ver o Resultado

Resultado:
```
1
3
5
```

ele só deu trace nos numeros que sao impar
