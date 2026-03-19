# Guia Bootstrap baseado no seu index (FitFlex)

Este guia explica os principais conceitos e classes do Bootstrap que aparecem no  código.

---

## 1. Container

### `.container` e `.container-fluid`

* São classes de **layout**
* Servem para **centralizar e organizar o conteúdo na tela**

**Diferença:**

* `.container` → largura fixa com margens automáticas
* `.container-fluid` → ocupa 100% da largura da tela

---

## 2. Grid System (Sistema de Grade)

O Bootstrap usa um sistema de 12 colunas.

### `.row`

* Cria uma **linha horizontal**
* Usada para agrupar colunas

### `.col-md-4`, `.col-sm-6`

* São **classes de dimensionamento de colunas**
* Dividem o espaço em partes

Exemplo:

* `.col-md-4` → ocupa 4 de 12 colunas em telas médias
* `.col-sm-6` → ocupa 6 de 12 colunas em telas pequenas

---

## 3. Navbar (Barra de Navegação)

### `.navbar`

* Componente principal de navegação

### `.navbar-expand-lg`

* Define quando o menu expande
* `lg` = telas grandes

### `.navbar-brand`

* Representa o logo ou nome da marca

### `.navbar-nav`

* Container dos itens de navegação

### `.nav-item`

* Cada item da lista

### `.nav-link`

* Link clicável do menu

### `.navbar-toggler`

* Botão que aparece no mobile

### `.collapse` + `.navbar-collapse`

* Controlam o menu escondido no mobile

---

## 4. Botões

### `.btn`

* Classe base de botão

### `.btn-primary`

* Define cor e estilo principal

### `.btn-lg`

* Tamanho grande

---

## 5. Cards

### `.card`

* Componente de cartão

### `.card-body`

* Área de conteúdo

### `.card-title`

* Título do card

### `.card-text`

* Texto do card

### `.card-img-top`

* Imagem no topo

---

## 6. Utilitários de Espaçamento

### Margens e paddings

* `mt-3` → margin-top
* `mb-5` → margin-bottom
* `py-5` → padding vertical

---

## 7. Utilitários de Texto

### `.text-center`

* Centraliza texto

### `.text-white`

* Cor branca

### `.lead`

* Texto de destaque

### `.fs-3`

* Tamanho da fonte

### `.fw-bold`

* Negrito

---

## 8. Flexbox (Layout Flexível)

### `.d-flex`

* Ativa flexbox

### `.flex-column`

* Organiza em coluna

### `.justify-content-center`

* Centraliza verticalmente

### `.align-items-center`

* Centraliza horizontalmente

### `.h-100`

* Altura 100%

---

## 9. Cores e Background

### `.bg-light`

* Fundo claro

---

## 10. Espaçamento automático

### `.ms-auto`

* Margin start automático
* Empurra elementos para a direita

---

## 11. JavaScript do Bootstrap

### `bootstrap.bundle.min.js`

* Responsável por:

  * Menu mobile (collapse)
  * Interações

---

## Resumo geral

Você usou 3 pilares do Bootstrap:

1. Layout (container, grid)
2. Componentes (navbar, card, botão)
3. Utilitários (espaçamento, texto, flex)

---

Se quiser evoluir, próximos passos:

* Forms (formulários)
* Modals (popups)
* Alerts
* Tables

---

#  Página de Cadastro

 Elementos novos que aparecem na página de cadastro.

---

## 12. Formulários (Forms)

O Bootstrap possui um conjunto de classes específicas para formulários.

### `.form-label`

* Define o estilo do rótulo (label)
* Mantém espaçamento e tipografia padrão

### `.form-control`

* Usado em inputs e textarea
* Aplica:

  * largura total
  * padding
  * bordas padronizadas

### `.form-select`

* Estiliza elementos `<select>`
* Mantém padrão visual consistente com inputs

---

## 13. Modal (Janela Popup)

Componente interativo do Bootstrap que depende de JavaScript.

### `.modal`

* Container principal do modal

### `.fade`

* Adiciona animação de transição

### `.modal-dialog`

* Define estrutura e posicionamento

### `.modal-dialog-centered`

* Centraliza verticalmente na tela

### `.modal-content`

* Caixa principal do conteúdo

### `.modal-header`

* Cabeçalho do modal

### `.modal-body`

* Conteúdo principal

### `.modal-footer`

* Área de ações (botões)

### `.modal-title`

* Estilo do título

### `.btn-close`

* Botão padrão de fechar

---

## 14. Atributos de Interação (Data Attributes)

Bootstrap usa atributos HTML para ativar comportamentos.

### `data-bs-toggle="modal"`

* Indica que o elemento ativa um modal

### `data-bs-target="#modalSucesso"`

* Define qual modal será aberto

### `data-bs-dismiss="modal"`

* Fecha o modal ao clicar

---

## 15. Botões adicionais

### `.btn-secondary`

* Variante de botão com cor secundária

---

## Resumo do Cadastro

Novos conceitos aprendidos aqui:

1. Formulários padronizados
2. Modal (popup interativo)
3. Data attributes para interações

---

Agora juntando com o outro arquivo, você já cobre praticamente:

* Layout completo
* Navegação
* Componentes visuais
* Interações básicas

Isso já é nível de projeto acadêmico bem sólido.
