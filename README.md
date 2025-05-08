[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AIsXDBUL)


# Victor Gabriel de Souza Lacerda Belém - Projeto I de Front-end 

Este README documenta os principais recursos de HTML e CSS utilizados no projeto, indicando os arquivos e linhas onde aparecem. O propósito é facilitar a compreensão do código e destacar as principais funcionalidades implementadas.

---

## **Recursos de HTML**

### 1. **Definindo o idioma e metadados básicos**
   - **Arquivo**: `index.html`
   - **Local**: Linha 2–6
   - **Descrição**:
     - Define o idioma da página como `pt-BR`.
     - Inclui metadados como `charset` para suporte UTF-8 e `viewport` para responsividade.

### 2. **Links para fontes e estilos externos**
   - **Arquivo**: `index.html`
   - **Local**: Linha 7–11
   - **Descrição**:
     - Importa a fonte "Poppins" do Google Fonts.
     - Vincula arquivos CSS externos (`mainstyle.css` e `responsive.css`) para estilização.

### 3. **Estrutura do cabeçalho e navegação**
   - **Arquivo**: `index.html`
   - **Local**: Linha 13–25
   - **Descrição**:
     - Criação de uma barra de navegação usando um `<nav>` com links para seções internas e externas.
     - A galeria foi criada como forma de mostrar meu lado pessoal.
     - Os projetos são todos meus como aluno do IFSC.
     - Uso de classes como `header-area` e `main-nav` para estilização.

### 4. **Seções principais**
   - **Arquivo**: `index.html`
   - **Local**: Linha 27–163
   - **Descrição**:
     - Seções organizadas com IDs como `habilidades`, `galeria` e `disciplinas`.
     - Uso de divs e classes como `caixa-habilidade` para estruturar o conteúdo.

### 5. **Carrossel de imagens**
   - **Arquivo**: `index.html`
   - **Local**: Linha 91–151
   - **Descrição**:
     - Carrossel implementado com elementos `<section>` e `<li>`.
     - Navegação entre slides usando links com IDs (`#carousel__slide1`, `#carousel__slide2`, etc.).

### 6. **Rodapé**
   - **Arquivo**: `index.html`
   - **Local**: Linha 165–169
   - **Descrição**:
     - Inclui informações de contato e uma breve descrição do autor.

---

## **Página de projetos**

### 1. **Estrutura básica do documento**
   - **Arquivo**: `index.html`
   - **Local**: Linha 1–12
   - **Descrição**:
     - Uso de `<!DOCTYPE html>` para definir o documento como HTML5.
     - Definição do idioma como `pt-BR` e configuração de metadados (`charset` e `viewport`) para responsividade.
     - Importação da fonte "Poppins" do Google Fonts.

### 2. **Cabeçalho e navegação**
   - **Arquivo**: `index.html`
   - **Local**: Linha 14–27
   - **Descrição**:
     - Uso da tag `<header>` para organizar o cabeçalho.
     - Criação de uma barra de navegação com links para as páginas internas e externas.
     - Exemplo: O logotipo do IFSC é exibido com uma imagem `<img>` e um link `<a>`.

### 3. **Seção de banner principal**
   - **Arquivo**: `index.html`
   - **Local**: Linha 29–44
   - **Descrição**:
     - Uso de `<div>` com classe `main-banner` para criar o banner principal.
     - Estrutura com título `<h6>`, subtítulo `<h2>` e parágrafo `<p>`.
     - Inclusão de uma imagem à direita usando `<img>` com a classe `right-image`.

### 4. **Seção de projetos**
   - **Arquivo**: `index.html`
   - **Local**: Linha 46–111
   - **Descrição**:
     - Uso de `<div>` com a classe `projects` e IDs para organização.
     - Cada projeto é estruturado com:
       - Uma miniatura `<img>` (ex.: Linha 53).
       - Um título `<h4>` e descrição `<p>` (ex.: Linha 56–57).
       - Um botão `<a>` com a classe `main-button` para acessar mais detalhes (ex.: Linha 58).

### 5. **Rodapé**
   - **Arquivo**: `index.html`
   - **Local**: Linha 113–118
   - **Descrição**:
     - Uso da tag `<footer>` para exibir informações de contato e uma descrição breve do autor.

### 6. **Observações**
- Os arquivos como projeto.html, pessoal.html e faculdade.html possuem estruturas similiares, então deixei para comentar uma delas de forma geral.

---
---


## **Recursos de CSS**

### 1. **Reset CSS**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 238–278
   - **Descrição**:
     - Remove margens e paddings padrão de elementos HTML para garantir consistência.

### 2. **Fonte global e design responsivo**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 56–61
   - **Descrição**:
     - Define a fonte global como "Poppins".
     - Inclui propriedades como `overflow-x: hidden` para evitar barras de rolagem horizontais.

### 3. **Estilo do cabeçalho fixo**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 238–278
   - **Descrição**:
     - Aplica bordas arredondadas ao cabeçalho.
     - Estiliza itens do menu de navegação com hover e estado ativo.

### 4. **Banner principal**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 369–403
   - **Descrição**:
     - Estiliza o banner principal com uma imagem de fundo e texto centralizado.
     - Adiciona bordas arredondadas e espaçamento interno consistente.

### 5. **Carrossel de imagens**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 913–1002
   - **Descrição**:
     - Implementação de um carrossel com navegação por scroll e animações suaves.
     - Usa `scroll-snap-align` para centralizar os slides.

### 6. **Botões personalizados**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 130–134
   - **Descrição**:
     - Botões com bordas arredondadas, cores definidas e transições suaves ao passar o mouse.

### 7. **Cartões de informações**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 1200–1250
   - **Descrição**:
     - Cartões com sombras, gradientes e transições de hover.
     - Personalização com diferentes estilos para cada cartão.

---

## **Recursos Avançados**

### 1. **CSS Animations**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 985–1000
   - **Descrição**:
     - Animações para transições suaves no carrossel (`@keyframes`).

### 2. **Grid e flexbox**
   - **Arquivo**: `css/mainstyle.css`
   - **Local**: Linha 786–796, 938
   - **Descrição**:
     - Usa CSS Grid para o layout da galeria e Flexbox para centralizar conteúdo.

---

## **Como executar**

1. Clone o repositório:
   ```bash
   git clone https://github.com/sergio-prolo-class/projeto-1-victorlcrd
   ```
2. Abra o arquivo `index.html` em qualquer navegador para visualizar a página.

---