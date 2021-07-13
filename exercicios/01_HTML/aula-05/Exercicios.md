# Exercícios 
## Aula 05

1. Com relação ao trecho de código abaixo responda:
    ~~~HTML
    <!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Estrutura</title>
    </head>
    <body>
        Olá mundo!
    </body>
    </html>
 a) Para que serve a tag `<!DOCTYPE html>`?
 
 >*Apesar da sintaxe parecida, o Doctype não é uma tag do HTML.*
*O Doctype HTML é uma declaração para informar ao navegador qual é a versão do HTML* 
*utilizada no arquivo. Essa declaração vem antes das tags HTML, portanto, geralmente* 
*é apresentada na primeira linha de um código.*
>
>*A partir da nova versão do HTML, o HTML5, a declaração do doctype passou a ser bem* 
*simplificada. Basta declarar como `<!DOCTYPE html>`*

**Fonte:** [Homehost tutoriais](https://www.homehost.com.br/blog/tutoriais/doctype-html/) 

 b) Para que serve as meta tags `<meta>`?
 
>*O elemento HTML `<meta>` define qualquer informação de metadados que não podem ser definidos 
por outros elementos HTML. (`<base>`, `<link>`, `<script>`, `<style>` ou `<title>)`.*
 
 **Fonte:** [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/meta#exemplos)

 c) Qual a importância de usar ad configuração de `charset`?

 >*Este atributo define a codificação de caracteres usada na página. Pode ser substituído 
localmente usando o atributo lang em qualquer elemento. Esse atributo é literalmente 
uma amarra e deve ser um dos MIME names preferidos para uma codificação de caracteres 
como definido pela IANA. Embora o padrão não solicite uma codificação específica, 
os autores são encorajados a usar UTF-8.*

 **Fonte:** [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/meta#exemplos)

 d) Com o conhecimento adquirido até o momento, o que poderia ser melhorando nesse trecho de código?

>*Podemos alterar __lang=pt-br__ para __lang=en-us__, ou outras linguagens dependendo pra que tipo de site estamos criando*
>
>*Também __UTF-8__ por __UTF-16__*

 **Fonte:** [Voices of my mind]()


---

2.Construa um código HTML que exiba o seguinte resultado:
 
> #Alterando _Titulos_ e Parágrafos
> ## Títulos
>  <u>Meus títulos podem ter as seguintes henfáses </u>
> * #A título
> * ##B título
> * ###C título
> * ####D título
> * #####E título
> * ######F título
> Podendo ainda ser _itálico_, <u>sublinhado</u>, **negrito** entre outros
>
> ---
>
> ## Parágrafos
> Meu texto é muito bonito, pois escrevo *italico*, **negrito**, <ins>sublinhado</ins> & <ins>_**sublinhado_Negrito_itálico**_</ins>
>
> Ele também tem quebra de linha
>
> ---
> 
> E tem linha em branco

---

3. Crie código que tenha como resultado uma lista **Não** ordenada para listar os itens
> * FrontEnd
>  * html
>  * css
>  * js 
>  * react 
> * BackEnd 
>  * java
>  * spring-boot 

---

4. Crie um código que tenha como resultado uma lista **ordenada** capaz de listar os intens da seguinte forma:
> 1. FrontEnd
>   1. html
>   2. css
>   3. js 
> 2. react 
> 3. Projeto Final 

---