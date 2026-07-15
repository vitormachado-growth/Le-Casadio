# Le Casadio

Site da Le Casadio — confeitaria artesanal do Kevin Casadio, no Rio de Janeiro.

## O que tem aqui

    index.html          o site inteiro: HTML, CSS e JS num arquivo so
    img/
      selo.jpg          o logo, recortado em circulo (o .jpg original vem num quadrado branco)
      selo-pequeno.png  o mesmo logo em 160px, usado no selo do rodape
      favicon-16/32.png o icone da aba: recortado no disco, sem o "CASADIO"
      apple-touch-icon.png  180px, para quando alguem salva o site na tela do celular
      le-traco-l.png    o "L" da assinatura, isolado — usado na abertura
      le-traco-e.png    o "e" da assinatura, isolado — idem
      fotos/            as seis fotos da vitrine, cortadas em 4:5 e comprimidas
    logo.jpg            o logo original, como o Kevin entregou
    le.png              o "Le" isolado, origem dos dois tracos acima

## Como ver

Abra o `index.html` no navegador. Nao precisa de servidor nem de build.

## Como publicar

Arraste a pasta inteira para o netlify.com/drop — sai no ar em segundos, de graca.
Para um endereco proprio (lecasadio.com.br), registre em registro.br e aponte no Netlify.

## Detalhes que nao sao obvios

- **A abertura** desenha o "Le" com um feixe de luz e o faz pousar dentro do selo.
  O feixe segue um "esqueleto" (o caminho que a caneta percorreria) que esta escrito
  a mao no CSS, nos paths `wA` e `wB`. A letra e revelada por mascara: por isso a
  caligrafia que aparece e a do Kevin, nao um desenho aproximado.

- **A divisao do "L" e do "e"** em dois arquivos existe porque, com um so, a mascara
  do "L" encostava na barriga do "e" e o revelava antes da hora.

- **As cores** saem do logo: caramelo #C67C39, creme #FAEDD8, marrom #8B4C22.
  Todos os pares de texto/fundo foram medidos pela regra de contraste da WCAG.
  Cuidado: caramelo sobre creme da 2.86 e reprova — use o marrom para texto claro.

- **O favicon nao e o logo inteiro.** Em 16px o "CASADIO" vira sujeira e o
  conjunto some num borrao marrom. Os icones da aba sao recortados no disco:
  sacrificam o texto e salvam a letra, que e o que se reconhece.

- **As fotos sao arquivos**, nao estao coladas dentro do HTML. Para trocar, basta
  substituir o arquivo em `img/fotos/` mantendo o nome e a proporcao 4:5.

## Falta

- Quatro respostas do FAQ (antecedencia, entrega, pagamento, restricoes) — hoje o
  site so tem duas perguntas, as que tinham resposta de verdade.
- Uma foto do Kevin na cozinha, para a secao "Sobre".
- Depoimentos de clientes.
- Decidir se entra preco.
