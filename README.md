# Take Dois

**Take Dois** é um site de ranking de séries e filmes desenvolvido para a disciplina de **Padrões Web da UTFPR**.

O projeto apresenta duas listas com nossas produções favoritas, relacionando o entretenimento ao uso de plataformas de streaming como tecnologia presente em atividades de lazer.

## Conteúdo

O site possui dois rankings.

### Top Séries

1. O Mentalista
2. La Casa de Papel
3. Grimm
4. The Vampire Diaries
5. Teen Wolf

### Top Filmes

1. Interestelar
2. O Diabo Veste Prada 2
3. Harry Potter e o Prisioneiro de Azkaban
4. Todo Mundo em Pânico 2
5. Invocação do Mal 2

Cada item apresenta imagem ilustrativa, legenda, justificativa para sua posição no ranking e uma página individual.

## Tecnologias utilizadas

- HTML5
- CSS3
- SVG
- Google Material Icons
- Google Fonts

O projeto não utiliza frameworks.

## Recursos implementados

- elementos semânticos do HTML;
- listas ordenadas para os rankings;
- estados personalizados dos links;
- filtros CSS aplicados às imagens conforme a posição;
- logo desenvolvida em SVG;
- ícones nos links;
- textos alternativos nas imagens;
- figuras com legendas;
- imagens para monitor e celular com `picture` e `source`;
- adaptação para diferentes tamanhos de tela;
- folha de estilos CSS externa.

## Estrutura do projeto

    .
    ├── ranking-julia-ana.html
    ├── ranking-julia-ana.css
    ├── README.md
    ├── imagens/
    │   ├── take-dois.svg
    │   ├── mobile/
    │   └── imagens das séries e filmes
    └── serie-filme/
        └── páginas individuais das séries e filmes

## Executando localmente

No diretório do projeto, execute:

    python3 -m http.server 8000

Depois acesse no navegador:

    http://localhost:8000/ranking-julia-ana.html

## Autoras

- Ana Carolina
- Julia

Projeto acadêmico desenvolvido para a disciplina de **Padrões Web — UTFPR**.
