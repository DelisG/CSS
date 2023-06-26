![](https://res.cloudinary.com/cloudinary-marketing/images/w_1540,h_847/f_auto,q_auto/v1649718594/Web_Assets/blog/working_with_css_22218720ab/working_with_css_22218720ab-jpg?_i=AA)
## O que é o CSS e por que ele existe?

O CSS é uma linguagem de folhas de estilos que é utilizada para definir como os documentos escritos na linguagem de marcação (HTML ou XML) devem ser apresentados em termos de formatação, de layout. Em um cenário ideal, enquanto o HTML é usado para estruturar os conteúdos, o CSS é utilizado para formatá-los. Dessa forma há uma enorme integração entre o HTML e o CSS.

No inicio da Internet, apenas o HTML era utilizado na elaboração das páginas Web, com o tempo e a necessidade de mais alternativas de formatação dessas páginas, foram criadas novas tags e atributos de estilo no HTML para que ele pudesse atender essas necessidades de layout, passando a cumprir tanto a função de estruturação quanto a de apresentação. Porém, isto começou a criar um problema para os Web Designers pois não havia como definir um padrão que se aplicasse a todas as páginas, qualquer alteração tinha que ser aplicada em cada uma delas, tornando o desenvolvimento muito complexo principalmente em grandes portais.
### Principais Benefícios do CSS

- Possibilidade do controle do layout de vários documentos a partir de um único arquivo CSS
- Aplicação de layouts diferentes de acordo com o dispositivo utilizado, possibilitando o layout responsivo
- Possibilidade de manter a mesma formatação em diferentes navegadores
- Aplicação de técnicas mais sofisticadas de desenvolvimento
- Menor consumo de banda e melhor desempenho devido ao reuso do mesmo código de formatação em várias páginas

### Como o CSS é integrado com o HTML?

1. O Atributo Style

Nesse caso, é utilizado o atributo Style dentro da tag Body do HTML. Por exemplo:
```sh
<html>         
    <head>               
        <title>Exemplo HTML CSS</title>          
    </head>         
    <body style="background-color: #00BFFF;">               
        <p>Esta é uma página com fundo azul</p>          
    </body>        
</html>
```

2. A Tag Style

Aqui é utilizada tag CSS style para definição da formatação, não um atributo dentro da tag body.

```sh
<html>         
    <head>               
        <title>Exemplo Linguagem CSS</title>     
        <style type="text/css"> 
            body {background-color: #00BFFF;}
        </style>      
    </head>         
        <p>Este é um exemplo de página com formatação</p>          
    </body>        
</html>
```

3. Externo – Link para o arquivo CSS

Essa é uma das opções mais utilizadas pois permite que as alterações de formatação sejam feitas uma única vez e afetem várias páginas simultaneamente. Nesse modelo o documento HTML inclui um link para um outro documento CSS de onde ele importa as definições de estilo.

###### exemplo.html

```sh
<html>
    <head>
        <title>O que é CSS</title>
        <link rel="stylesheet" type="text/css" href="style.css" />
    </head>
    <body>
        <h1>Esse é um exemplo de documento HTML</h1>
    </body>
</html>
```
###### style.css
```sh
body {
    background-color: #00BFFF;
}
```

## E o que é CSS3?
O CCS3 é simplesmente a versão mais atual do CSS, uma evolução. Entre outras as evoluções, ele incorpora novos elementos para construir animações tanto em 2 como e 3 dimensões. Incorpora também novos mecanismos para um maior controle sobre o estilo com o qual se mostram as características das páginas.
# Glossário de Termos Técnicos em CSS

Aqui está um glossário de termos técnicos comumente utilizados em CSS (Cascading Style Sheets), juntamente com seus significados:

| Termo Técnico     | Significado                                                  |
|-------------------|--------------------------------------------------------------|
| Seletor           | Um seletor é usado para selecionar um elemento HTML para estilização.                                |
| Propriedade       | Uma propriedade define o estilo de um elemento selecionado.                                                 |
| Valor             | Um valor é atribuído a uma propriedade para especificar como ela deve ser estilizada.                        |
| Classe            | Uma classe é um seletor reutilizável que pode ser aplicado a vários elementos HTML.                          |
| ID                | Um ID é um seletor exclusivo para um elemento HTML específico.                                            |
| Pseudo-classe     | Uma pseudo-classe é usada para selecionar elementos com base em um estado ou ação específica.                |
| Pseudo-elemento   | Um pseudo-elemento é usado para estilizar uma parte específica de um elemento.                               |
| Box Model         | O Box Model define o layout de um elemento, incluindo seu conteúdo, preenchimento, bordas e margens.         |
| Margem            | A margem é o espaço em branco ao redor de um elemento CSS.                                                   |
| Preenchimento      | O preenchimento é o espaço entre o conteúdo de um elemento e sua borda.                                       |
| Display           | A propriedade display define como um elemento deve ser exibido no layout da página.                           |
| Float             | A propriedade float é usada para posicionar elementos lado a lado dentro de um contêiner.                   |
| Posicionamento     | O posicionamento define como um elemento é posicionado em relação a seus elementos pai ou irmãos.           |
| Flexbox           | O Flexbox é um modelo de layout que permite criar layouts flexíveis e responsivos.                            |
| Grid              | O Grid é um sistema de layout bidimensional que permite criar layouts complexos e responsivos.               |
| Responsivo        | Um design responsivo é aquele que se adapta a diferentes tamanhos de tela e dispositivos.                     |
| Media Query       | Uma media query é usada para aplicar estilos diferentes com base nas características do dispositivo.          |
| Transição         | A transição é usada para criar animações suaves entre os estados de um elemento.                              |
| Animação          | As animações permitem criar efeitos de movimento em elementos HTML usando keyframes.                           |
| Gradiente         | Um gradiente é uma transição suave entre duas ou mais cores.                                                   |
| Sombras           | As sombras são usadas para adicionar profundidade e efeitos visuais a elementos usando sombras projetadas.   |
| Seletores de Atributo  | Os seletores de atributo são usados para selecionar elementos com base em seus atributos específicos. |
| Unidades de Medida     | As unidades de medida são usadas para definir tamanhos e distâncias em CSS, como px, em, %, rem, etc. |
| Estilos em Cascata     | A cascata é o processo de aplicação de estilos, onde os estilos são herdados e podem ser substituídos. |
| Herança                | A herança permite que os estilos sejam aplicados a elementos filhos com base nos estilos dos elementos pais. |
| Estilos Externos       | Os estilos externos são arquivos separados que contêm as regras de estilo CSS e são vinculados a uma página HTML. |
| Estilos Embutidos      | Os estilos embutidos são definidos diretamente nos elementos HTML usando o atributo "style".          |
| Estilos Inline         | Os estilos inline são definidos diretamente nos elementos HTML usando a propriedade "style" no próprio elemento. |
| Prioridade de Seletor  | A prioridade de seletor determina qual estilo será aplicado quando existem regras de estilo conflitantes. |
| Transparência          | A transparência é a propriedade que permite que um elemento seja parcialmente transparente.              |
| Opacidade              | A opacidade é a propriedade que define o quão opaco ou transparente um elemento é.                      |
| Transformações        | As transformações são usadas para modificar a posição, rotação e escala de um elemento.                 |
| Transições             | As transições são animações que ocorrem entre dois estados de um elemento, com suavidade e controle de tempo. |
| Animações             | As animações são sequências de transições e estilos que criam efeitos de movimento em elementos.       |
| Tipografia             | A tipografia se refere ao estilo e formatação do texto, como fonte, tamanho, espaçamento e estilo do texto. |
| Modelos de Box         | Os modelos de box são as diferentes propriedades que definem o layout de um elemento, como margem, preenchimento e borda. |
| Cores                  | As cores em CSS podem ser definidas por nome, código hexadecimal, RGB ou HSL.                            |
| Gradientes             | Os gradientes são transições suaves entre duas ou mais cores que podem ser aplicados a fundos e elementos. |
| Sombras                | As sombras são efeitos visuais aplicados a elementos, como sombras projetadas ou sombras internas.        |
| Animar SVG             | É possível animar elementos SVG (Scalable Vector Graphics) usando CSS para criar efeitos visuais dinâmicos. |
| Opções de Exibição     | As opções de exibição definem como um elemento é renderizado na página, como block, inline ou none.    |
| Pseudo-classes Avançadas | As pseudo-classes avançadas são seletores que permitem estilizar elementos com base em estados específicos, como :hover, :focus, :active, etc. |

[fonte](https://portalwebdesigner.com/programacao/css/)


