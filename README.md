# Style Guide do Projeto
## Linguagem TypeScript
### Variaveis
```
 Sempre adicione a tipagem
```

```
 //Ruim
 nome = "Corinthians";
 nome: any = "Corinthians";

 //Bom
nome: String= 'Tri Mundial';

```
---
```
    Evite o uso de ELSE.
```
```
    //ruim
        if (a==b)
            console.log('iguais')
        else 
            console.log('diferentes')
    
    //bom
        if (a===b)
            console.log('iguais')
        if (a!=b)
            console.log('diferentes')
```
### Tipagem Variavel
```
    Nunca utilizar var, sempre let ou const
```