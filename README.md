# Carta de Amor Interativa

Este é um projeto simples de site, criado com **HTML**, **CSS** e **JavaScript**, que simula uma carta de amor com animações interativas. O projeto foi desenvolvido para treinar habilidades de layout, animação CSS e manipulação de eventos no navegador.

## Descrição

O site apresenta uma **carta de amor** que é exibida de forma interativa quando o usuário clica sobre um envelope. O conteúdo é acompanhado por animações de rotação e transição, criando uma experiência imersiva.

### Funcionalidades:
- **Cabeçalho Fixo:** O título "AAAAAAAAAAA" é exibido em um cabeçalho fixo no topo da página, sempre visível enquanto o usuário navega.
- **Animação de Envelope e Carta:** O envelope tem tampas que rotacionam quando a carta é "aberta". O conteúdo da carta se desloca para cima enquanto a animação é executada.
- **Texto Personalizado:** O texto da carta contém uma mensagem de amor, com formatação para destacar trechos importantes.
- **Interatividade:** Ao clicar na carta, a animação é acionada, e os elementos de transformação são aplicados.

## Tecnologias Utilizadas

- **HTML:** Estrutura básica do site, com a marcação de todos os elementos.
- **CSS:** Estilos que definem o layout do site, o design do cabeçalho, e animações de transformação e transição da carta.
- **JavaScript:** A função `alternarClasse` permite alternar o estado da animação ao clicar no envelope.

## Como Executar o Projeto

1. **Clone o repositório ou baixe os arquivos:**
   - Clone com o comando:
     ```bash
     git clone [https://seu-repositorio.com](https://github.com/zeus123-e/envelope-animation.git)
     ```
   - Ou baixe os arquivos diretamente.

2. **Abra o arquivo `index.html` no seu navegador:**
   - Basta abrir o arquivo diretamente em um navegador de sua escolha. Não há necessidade de servidor, pois o projeto é estático.

## Estrutura de Arquivos

- **`index.html`**: O arquivo principal, contendo a estrutura HTML do site.
- **`style.css`**: Contém os estilos principais do site, incluindo o design do cabeçalho e as animações.
- **`script.js`** (se aplicável): Código JavaScript para gerenciar a interatividade, como a animação do envelope.

## Como Funciona

- O **cabeçalho fixo** é renderizado no topo da página, utilizando `position: fixed` no CSS.
- O conteúdo interativo da carta (a `wrapper`) é composto por elementos com animações de rotação que acontecem ao clicar, usando transições CSS.
- O texto da carta é centralizado e estilizado com `font-size`, `color` e outros estilos visuais para garantir legibilidade.

## Objetivo do Projeto

Este projeto tem o objetivo de praticar as seguintes habilidades:
- Trabalhar com **animações e transições** em CSS para criar uma experiência visualmente interessante.
- Utilizar **JavaScript** para manipular interações do usuário, como o clique que alterna classes e ativa animações.
- Criar um layout simples, mas responsivo, com **flexbox** para centralizar o conteúdo na tela.

## Licença

Este projeto é de código aberto e pode ser usado para fins educacionais ou como base para outros projetos. Não há restrições de uso, mas recomenda-se citar o autor em casos de redistribuição.

