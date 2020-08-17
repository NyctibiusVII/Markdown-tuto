# Markdown-tuto
Tutorial auto explicativo sobre como usar as funcionalidades do MarkDown.
Famoso README.md



* ## Header
``` 
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
# h1
## h2
### h3
#### h4
##### h5
###### h6



* ## Ênfase
**Italico1* *

_ _Italico2_ _


** **Negrito1** **

__ __Negrito2__ __


~~ ~~Traçado~~ ~~



* ## Lista ordenada
``` 
1. Item
2. Item
3. Item

e

1. Item
1. Item
1. Item
```
1. Item
2. Item
3. Item

e

1. Item
1. Item
1. Item



* ## Lista não ordenada

``` 
- Item

e 

* Item
```
- Item

e

* Item



* ## Link
``` [nome do link](endereço_do_link.com) ```

[github](https://github.com/Armax7/Markdown-tuto)



* ## Citação
``` >Que a força esteja com vc ``` 
>Que a força esteja com vc



* ## Tasklists
Com x = checkBox preencida e com espaço = marcação vazia
``` 
- [x] Item 1
- [ ] Item 2
``` 
- [x] Item 1
- [ ] Item 2



* ## Código
```
      ```
      function(){
        var tuto = "tudo dentro deste(```é formatado como um código```)";
        console.log(tuto);
        //meio redundante, não?
      }
      ```
```
```
  function(){
    var tuto = "tudo dentro deste(```é formatado como um código```)";
    console.log(tuto);
    //meio redundante, não? kk
  }
```



* ## Tabela
```
Desenhe a tabela desta forma modificando apenas os itens dentro dos blocos
| topoA | topoB | topoC | topoD |
|-------|-------|-------|-------|
| Item1 | Item1 | Item1 | Item1 |
| Item2 | Item2 | Item2 | Item2 |
| Item3 | Item3 | Item3 | Item3 |
| Item4 | Item4 | Item4 | Item4 |
```
| topoA | topoB | topoC | topoD |
|-------|-------|-------|-------|
| Item1 | Item1 | Item1 | Item1 |
| Item2 | Item2 | Item2 | Item2 |
| Item3 | Item3 | Item3 | Item3 |
| Item4 | Item4 | Item4 | Item4 |



* ## Img e Gif
![](caminho até a imagem ou gif), funciona com links externos.
```
Caminho
![](imgegif/Octocat.png)
![](imgegif/e0db8690895407d039b94f75b6244035.gif)

Links externos
![](https://blogs.swarthmore.edu/its/wp-content/uploads/2018/09/Octocat.png)
![](https://i.pinimg.com/originals/e0/db/86/e0db8690895407d039b94f75b6244035.gif)

Gerenciar tamanho
<img src="link ou caminho" width="400px">
<img src="link ou caminho" width="400px">
```
<p align="center">
<img src="https://blogs.swarthmore.edu/its/wp-content/uploads/2018/09/Octocat.png" width="400px">
<img src="https://i.pinimg.com/originals/e0/db/86/e0db8690895407d039b94f75b6244035.gif" width="400px">
</p>

>DICA: use o html ao seu favor
