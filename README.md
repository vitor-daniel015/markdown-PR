# Style Guide do Projeto
## Linguagem Typescript
### Variáveis

```
Sempre adicione a tipagem primitiva
```
```
//bad
nome = "Diogo"
nome: any = "Diogo"

//good
nome: string = "sem mundial"
```
---
```
 Evite o uso de ELSE.
```
```
//bad
if (a==b) 
    console.log('iguais')
else 
    console.log('diferentes')

//good
if (a==b) 
    console.log('iguais')
if (a!=b) 
    console.log('diferentes')
```
### Tipagem Variavel
```
 Nunca utilizar var, sempre usar let ou const
```