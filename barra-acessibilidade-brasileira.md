# Criticas quanto a endorsar “barra de acessibilidade” visível como padrão
Este artigo explica, de forma resumida, o que é a barra de acessibilidade
comum em sites do governo brasileiro, e como o mesmo objetivo final é
conseguido com mais agilidade _e menos burocracia e perda de espaço
visual_ ao seguir padrões como o europeu e americano.

Sua crítica principal é que, ao menos para sites que não são obrigados a
tê-las, **é possível ter um site acessível sem alterar visualmente a
aparência de seu website**, porém a quantidade de premiações para quem segue
o padrão de governo, como esta barra, pode levar a acreditar que a barra
é desproporcionalmente responsável pela acessibilidade e que, por ela
exigir mudanças visuais em uma área de grande destaque, isso pode significar
_assustar_ sites não governamentais de adotar boas práticas desta área.


## O que é a "barra de acessibilidade" do padrão visual do governo brasileiro

Uma das marcas registradas de “site acessível” é uma barra de topo,
que é tida como modelo pelo menos em sites governamentais, e que é
reproduzida em sites como o http://www.brasil.gov.br/.

Ela geralmente possui o seguinte:

- Link de pular para conteúdo principal (sempre tem)
- Link para pular para outras áreas (comum: menu, busca)
- Botão para alterar contraste
- Referências a teclas de atalho "accesskeys" (você usa uma combinação de
teclas para chegar a um local)
- Um link para explicar como usar os outros links

## Supostas vantagens de usar o padrão brasileiro em detrimento do europeu

### Link para pular para conteúdo, e outras áreas importantes

Do ponto de vista de acessibilidade, isto é importante. Porém, **é possível
atingir o mesmo objetivo sem prejudicar a área visual**.

### Exibe, visualmente a todo momento, as teclas de acesso rápido "accesskeys"

Talvez o principal motivo para existência desta barra é permitir que uma
pessoa, que não queira ler o manual de uso de acessibilidade do site antes
de começar a usá-lo, saiba as teclas de acesso rápido.

Isto seria útil, não fosse por um motivo: há anos **há críticas muito pesadas
da utilidade prática de accesskeys há anos**, e com uso de tags ARIA e
determinadas tags HTML5, seu uso ficou ainda mais obsoleto.

Alguns links de referência:

- [Conflitos de accesskeys com navegadores e afins](http://webaim.org/techniques/keyboard/accesskey#browserconflicts)
- [Why Access Keys Are Mostly Useless for Accessibility Purposes](http://www.thesitewizard.com/webdesign/access-keys-are-useless.shtml)
- [Principal motivo para manter accesskey no HTML5 foi por compatibilidade com HTML4 e conteúdo móbile, não melhoria de acessibilidade](http://www.punkchip.com/the-accesskey-attribute/)

### Ela pode ter opção para aumento de constraste

Isto pode ser útil em sites com contraste de texto e cores muito pobre.
Porém o realmente ideal é, **por padrão** o site não precisar de um
botão especial para isto.

### Ela tem opção de aumento de fonte

Ter um botão especial para aumentar a fonte, sendo que é natural para
um usuário acabar descobrindo como aumenta fonte do seu navegador, é
algo meio redundante. Alguns sites, como o do [governo americano](https://www.usa.gov/change-text),
ao clicar na opção de trocar tamanho de fonte, em vez de fazê-lo,
levam a uma página que explica como fazer isso ao usuário final.

### Ela tem um manual de como a acessibilidade do site funciona

A _barra de acessibilidade é tão complexa, que precisa de um manual
para explicá-la_. No [link de explicação do brasil.gov.br](http://www.brasil.gov.br/acessibilidade)
75% do conteúdo principal da página parece mais **ser algo para
parecer que trabalho foi feito**, do que realmente explicar o que
precisa.

A página de manual de acessibilidade destes sites, parece servir
mais ao propósito de educar pessoas que não precisam delas, como
uma forma de conscientização. Por este ponto de vista, para uma
página do governo, é uma questão de decisão da equipe técnica.

É como se, pelo uso desnecessário de links para conteúdo visíveis,
bem como o uso obsoleto de accesskeys que são problemáticas, é
necessário ter uma página de documentação cuja maior parte não
é para documentar a acessibilidade, mas sim dizer leis que
e outros órgãos do governo brasileiro preocupados com isto.
Novamente, isto _faz sentido, apenas, se estamos falando
de páginas do governo_.

## Como é a barra de acessibilidade de outros países de referência?

**Resposta curta**: ela visivelmente não existe. Não é possível saber que está
lá até ela ser necessária.

**Resposta longa**

Diversos países do mundo simplesmente não tem uma barra padrão
de acessibilidade como a brasileira. Como o objetivo real da barra de
acessibilidade é, no fundo, ser acessada por quem usa leitor de tela, e isso é
feito ao pressionar a tecla "Tab", o padrão é unicamente exibir uma ou mais
opções de acessibilidade APENAS quando a tecla Tab é pressionada.

Essa técnica é possível usando apenas CSS e, em alguns casos, JavaScript, e,
normalmente, é usada para no primeiro pressionar de Tab exibir link para
pular para o conteúdo.

Exemplos de "barra de acessibilidade" invisível até ser usada (use tab para
ver os menus):
- https://www.usa.gov
- http://www.government.se
- https://www.canada.ca/en.html
- http://europa.eu

## Prejuízo geral de endorsar, ainda que implicitamente, o padrão brasileiro em sites não governamentais


Leia [Problema de endorsar padrões irrelevantes na melhoria de acessibilidade](problema-de-endorsar-padroes-irrelevantes.md).
