# Portal Terra

Página de um portal de notícias desenvolvida com **HTML** e **CSS**, criada como
atividade da disciplina de Web do curso de Redes de Computadores do IFC.

O projeto apresenta uma página inicial de portal jornalístico com cabeçalho,
menu de categorias, notícia em destaque, lista de últimas notícias e rodapé. O
layout é construído com **Flexbox** e utiliza a convenção de nomes **BEM** nas
classes CSS.

## Demonstração

Abra o arquivo `index.html` no navegador ou utilize a extensão **Live Server**
do VS Code para visualizar a página com recarregamento automático.

## Estrutura do projeto

```text
.
├── .vscode/                 # Configurações e extensões recomendadas do editor
├── css/
│   ├── reset.css            # Reset dos estilos padrão do navegador
│   └── global.css           # Estilos do portal (Flexbox + BEM)
├── docs/
│   ├── criar-repositorio-base.md    # Guia para criar o template base
│   └── guia-padronizacao-codigo.md  # Guia de padronização do código
├── img/                     # Imagens utilizadas na página
├── index.html               # Página principal do portal
├── .editorconfig            # Regras básicas de formatação
├── .prettierrc.json         # Configuração do Prettier
├── .prettierignore          # Arquivos ignorados pelo Prettier
└── README.md
```

## Layout

A página é organizada em quatro áreas principais:

- **Cabeçalho** — título do portal, slogan e menu horizontal de categorias.
- **Notícia em destaque** — cartão com imagem e texto dispostos lado a lado.
- **Últimas notícias** — cartões em colunas distribuídos com Flexbox.
- **Rodapé** — informações do portal.

O CSS utiliza variáveis (`:root`) para cores, espaçamentos e raios, facilitando
a manutenção e a consistência visual.

## Como executar

1. Clone o repositório:

   ```bash
   git clone <url-do-repositorio>
   cd portal-terra
   ```

2. Abra a pasta no VS Code.

3. Instale as extensões recomendadas (o VS Code sugere ao abrir o projeto).

4. Abra o `index.html` com o **Live Server**: clique com o botão direito no
   arquivo e selecione **Open with Live Server**.

## Padronização do código

O projeto adota EditorConfig e Prettier para manter a formatação consistente:

- indentação de dois espaços;
- largura preferencial de 80 caracteres;
- atributos HTML organizados em linhas separadas;
- quebras de linha no padrão `LF`.

Consulte os documentos em [`docs/`](./docs) para mais detalhes:

- [Guia de padronização do código](./docs/guia-padronizacao-codigo.md)
- [Como criar um repositório-base para HTML e CSS](./docs/criar-repositorio-base.md)

## Tecnologias

- HTML5
- CSS3 (Flexbox e variáveis CSS)
- Convenção de nomenclatura BEM

## Licença

Distribuído sob a licença indicada no arquivo [LICENSE](./LICENSE).
