# Converte Numero para Casas 2 Decimais


#### Algumas operações geram muitas casas decimais:


Ex: 
```
2.6 + 1.3 = 3.9000000000000004
```

Esse resultado ao ser passado pra funcao, vai retornar 3.90, como esperado.

```
    function roundToTwo(num) {
        return +(Math.round(num + "e+2") + "e-2");
    }

```

