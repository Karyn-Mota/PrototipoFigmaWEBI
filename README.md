# Projeto Final – Implementação de Protótipo do Figma

Este repositório contém o **Projeto Final da disciplina Desenvolvimento Web I**, cuja proposta é implementar, em **HTML e CSS**, um site completo baseado no protótipo criado previamente no **Figma**.

**Curso:** Técnico Integrado em Informática  
**Instituição:** Instituto Federal do Ceará – Campus Maranguape  
**Disciplina:** Desenvolvimento Web I  
**Professor:** Thomaz Maia  
**Dupla:** [Karynne Mota de Abreu](https://github.com/Karyn-Mota) e [Maria Alice Cavalcante de Brito](https://github.com/alicecavalcante)  <br> 
**Período:** 4º semestre  

---

## 🎯 Objetivo do Projeto

Implementar um site fiel ao protótipo desenvolvido no **Figma**, aplicando todos os conceitos estudados na disciplina, como:

- HTML semântico  
- Estruturação de páginas  
- Estilização com CSS  
- Flexbox e responsividade  
- Aplicação da paleta de cores e elementos do design original  

O site deve ser publicado no **GitHub Pages**.

---

## 📌 Instruções Gerais

- O projeto deve ser desenvolvido **apenas com HTML e CSS** (sem JavaScript).  
- Todo o layout deve seguir o design e a paleta definidos no protótipo do Figma.  
- O site deve conter três páginas principais:
  - Página Inicial (index.html)
  - Página de Detalhes (detalhes.html)
  - Página de Contato (contato.html)
- A entrega deve ser feita via link do **GitHub Pages** + repositório com **README.md**.

---

## 🧱 Requisitos de Estrutura

### **1. Cabeçalho e Rodapé**

Todas as três páginas devem conter:

- `<header>` com nome do site e menu de navegação (`<nav>`);  
- `<footer>` com nomes dos autores e ano;  
- Os elementos devem ser **iguais em todas as páginas** (copiados entre os arquivos).

---

## 🏠 2. Página Inicial – `index.html`

A página inicial deve conter:

- Pelo menos **5 itens relacionados ao tema** do site  
  (ex.: produtos, livros, filmes, jogos, personagens, etc.);
- Os itens devem ser exibidos em **cards**, contendo:
  - imagem  
  - título  
  - pequena descrição  

### ✔ Requisitos Técnicos

- Utilizar tags semânticas: `section`, `article`, `figure`;  
- Usar **Flexbox** para organizar e distribuir os cards de forma responsiva;  
- Seguir fielmente a estrutura do protótipo do Figma.

---

## 📄 3. Página de Detalhes – `detalhes.html`

Esta página deve destacar um item dentre os apresentados na página inicial.

### Deve conter:

- Imagem principal  
- Título  
- Descrição detalhada  
- Informações adicionais, como:
  - preço  
  - autor  
  - gênero  
  - tamanho  
  - ou qualquer outra informação relevante ao tema  

### ✔ Requisitos Técnicos

- Organizar as informações com **Flexbox** e **Box Model**;  
- Manter legibilidade, contraste e espaçamento adequados.

---

## ✉️ 4. Página de Contato – `contato.html`

O formulário deve conter:

- Nome — `input type="text"`  
- E-mail — `input type="email"`  
- Assunto — `input type="text"`  
- Mensagem — `<textarea>`  
- Botão de envio — `button type="submit"`

### ✔ Requisitos Técnicos

- Utilizar `<form>` com labels associadas corretamente;  
- Aplicar estilização para torná-lo agradável visualmente;  
- Manter consistência com o restante do design do site.

---

## 🎨 5. Requisitos de Estilo – `style.css`

O estilo deve seguir:

- Baseado na **paleta do Figma**  
- Uso de **classes e IDs** de forma coerente  
- Aplicação do **box model** (margin, padding, border)  
- Posicionamento e alinhamento com:
  - `display: flex`
  - `justify-content`
  - `align-items`
  - `gap`
- Responsividade básica: o site deve se ajustar a diferentes larguras  

---

## 🖼️ 6. Apresentação Final no README.md

O README deve conter:

### ✔ Prints do protótipo do Figma
- Uma captura de cada página:
  - Página inicial  
  - Página de detalhes  
  - Página de contato  

### ✔ Prints do site final em HTML/CSS
- Capturas das páginas desenvolvidas  

### ✔ Comentário comparativo
- Pequena explicação sobre:
  - Semelhanças entre o protótipo e a implementação final  
  - Diferenças e adaptações necessárias  

As imagens devem ser salvas na pasta:

