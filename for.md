a funcao for é uma das mais uteis

Exemplo como usar a Funcao:
```
var nomes:Array<String> = ["pedro", "lucas", "emo?", "pico", "lol"];

for(n in nomes)
{
trace("Nomes das Pessoas: " + n);
}
```

Resultado:
```
Nomes das Pessoas: pedro
Nomes das Pessoas: lucas
Nomes das Pessoas: emo?
Nomes das Pessoas: pico
Nomes das Pessoas: lol
```

Agora n vamos usar essa Funcao:
```
var nomes:Array<String> = ["pedro", "lucas", "emo?", "pico", "lol"];

trace("Nomes das Pessoas: " + nomes[0]);
trace("Nomes das Pessoas: " + nomes[1]);
trace("Nomes das Pessoas: " + nomes[2]);
trace("Nomes das Pessoas: " + nomes[3]);
trace("Nomes das Pessoas: " + nomes[4]);
```

Vai Ser O Mesmo Resultado mas O Codigo vai ser mais simples usando a Funcao For