HTML 
HYPERTEXT MARKUP lANGUAGE

Hiper Texto?
Markup
  -tags
  -atributos
  Linguagem
  -maneira de escrever
  href = atributo

  CSS
    -estilos para HTML 
    -Cascading Style Sheets
      -folha de estilo em cascata
      
  Declaração    
    - seletor
    - propriedade e valor

    Conceito
      - cascata
      - especificade
      - Box Model {
        tudo são caixas
        caixas possuem propriedade
      }
      - display block vs inline

JS
  Function
  1. Criação 
    function nomeDaFunção() {
      console.log('código dentro da função)
    }      

  2. Execução
    nomeDaFunção()  

  Parâmetros
    function soma(a, b) {
      console.log(a + b)
    }  
    soma(34, 45)
    soma(40, 78)

  Retorno
    function soma(a, b) {
      return a + b
    }  
    const multiplica = soma(2, 2) * 4
    console.log(multiplica)

    Math.random() // gera número de 0 - 1
    Math.floor() // arredonda para baixo
    Math.ceil() // arredonda para cima

  DOM - Document Object Model
   window
   window.alert('alerta')
   document
   document.write("texto")
   manipular elementos
   document.documentElement.style.background = "black"