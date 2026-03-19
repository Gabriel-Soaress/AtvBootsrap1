# Guia Bootstrap baseado no seu index (FitFlex)

Este guia explica os principais conceitos e classes do Bootstrap que aparecem no código.

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

### `.btn-danger`

* Botão com cor de perigo (ações destrutivas)

### `.btn-secondary`

* Botão com estilo secundário

### `.btn-lg`

* Tamanho grande

### `.btn-sm`

* Tamanho pequeno

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

* `mt-3`, `mt-5` → margin-top
* `mb-4`, `mb-5` → margin-bottom
* `py-3`, `py-5` → padding vertical

---

## 7. Utilitários de Texto

### `.text-center`

* Centraliza texto

### `.text-white`

* Cor branca

### `.lead`

* Texto de destaque

### `.fs-1`, `.fs-3`

* Tamanhos de fonte

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

### `.justify-content-between`

* Espaço entre elementos

### `.align-items-center`

* Centraliza horizontalmente

### `.h-100`

* Altura 100%

### `.min-vh-100`

* Altura mínima da tela inteira

---

## 9. Cores e Background

### `.bg-light`

* Fundo claro

### `.bg-primary`, `.bg-success`, `.bg-danger`

* Cores padrão do Bootstrap

### `.text-white`

* Texto branco para contraste

---

## 10. Espaçamento automático

### `.ms-auto`

* Margin start automático
* Empurra elementos para a direita

---

## 11. Sombras

### `.shadow`

* Adiciona sombra ao elemento

---

## 12. JavaScript do Bootstrap

### `bootstrap.bundle.min.js`

* Responsável por:

  * Menu mobile (collapse)
  * Modal
  * Interações

---

# Página de Cadastro

## O que eu usei de novo no Bootstrap nessa página

---

## 13. Formulários (Forms)

### `.form-label`

* Estiliza o label

### `.form-control`

* Inputs e textarea padronizados

### `.form-select`

* Estiliza selects

---

## 14. Modal (Janela Popup)

### `.modal`

* Container principal

### `.fade`

* Animação

### `.modal-dialog`

* Estrutura

### `.modal-dialog-centered`

* Centralização vertical

### `.modal-content`

* Caixa principal

### `.modal-header`, `.modal-body`, `.modal-footer`

* Estrutura interna

### `.modal-title`

* Título

### `.btn-close`

* Botão de fechar

---

## 15. Atributos de Interação

### `data-bs-toggle="modal"`

* Abre o modal

### `data-bs-target="#modalSucesso"`

* Define qual modal abrir

### `data-bs-dismiss="modal"`

* Fecha o modal

---

# Página Dashboard

## O que eu usei de novo no Bootstrap nessa página

---

## 16. Ícones

### Bootstrap Icons

* `bi bi-people-fill`
* `bi bi-person-plus-fill`
* `bi bi-exclamation-triangle-fill`

---

## 17. Cards com utilitários

* Uso de cores (`bg-*`)
* Uso de `text-white`
* Uso de `shadow`
* Uso de flexbox dentro do card

---

# Página Listagem

## O que eu usei de novo no Bootstrap nessa página

---

## 18. Tabelas

### `.table`

* Estrutura base

### `.table-striped`

* Linhas alternadas

### `.table-hover`

* Efeito ao passar o mouse

### `.table-dark`

* Cabeçalho escuro

---

## 19. Integração com Modal

* Botões usando `data-bs-toggle`
* Reutilização de um único modal

---

# Página Contato

## O que eu usei de novo no Bootstrap nessa página

---

* Não houve novos componentes
* Reforço de:
  - Container
  - Grid
  - Navbar

---

## Resumo Final

Com esse projeto, eu utilizei:

* Layout responsivo completo
* Sistema de grid
* Navbar responsiva
* Cards
* Formulários
* Modal (interação)
* Tabelas
* Ícones
* Utilitários (cores, espaçamento, flexbox)

---

## Conclusão

Esse projeto cobre praticamente todo o Bootstrap básico e parte do intermediário, sendo suficiente para desenvolvimento de interfaces modernas e responsivas.