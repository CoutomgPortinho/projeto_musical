# 🎵 Sistema Catálogo Musical - Front-end (Sprint 1)

> **Curso:** Técnico em Desenvolvimento de Sistemas — SENAI SP  
> **Unidade Curricular:** Linguagem de Marcação (LIMA)  
> **Semestre:** 2º Semestre de 2026  
> **Tema Base:** Artistas e Músicas (Catálogo de Criadores e Obras)

---

## 📌 Sobre o Projeto

Este projeto tem base na construção da interface **front-end** de um catálogo digital interativo voltado para a organização de artistas e suas músicas. 


---

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estruturação semântica de páginas e formulários web.
- **CSS3:** Estilização com variáveis no `:root`, **Flexbox** e **CSS Grid** para layouts modernos e responsivos.
- **Git & GitHub:** Controle de versão e documentação.
---

## 💻 As 5 Telas do Sistema

O fluxo do sistema é composto por 5 telas interligadas por links navegáveis:

1. **Tela de Login (`login.html`)**
   - Cartão centralizado com o ícone e nome do sistema.
   - Formulário com campos de usuário e senha obrigatórios (`type="password"`).
   - Dica com credenciais de teste para demonstração (`admin` / `123`).

2. **Menu Principal (`index.html`)**
   - Cabeçalho com saudação e botão "Sair" alinhado à direita (redireciona para a tela de login).
   - Grade principal com 3 *cards* interativos: *Cadastro do Criador*, *Cadastro da Obra* e *Listagem/Biblioteca*.

3. **Listagem / Biblioteca (`listagem_musicas.html`)**
   - Barra superior com botões de navegação ("Voltar ao Menu" e "Nova Obra").
   - Barra de filtros contendo busca geral e select duplos (criador e categoria).
   - Tabela exibindo dados cadastrados, miniatura ("Sem capa"), link externo com abertura em nova aba (`target="_blank"`) e botões de ação (Editar e Excluir).

4. **Cadastro de Criadores/Artistas (`cadastro_artista.html`)**
   - Formulário organizado em 2 colunas usando CSS Grid (`method="post"`, `enctype="multipart/form-data"`).
   - Campo obrigatório de texto com indicação `*` e input para upload de imagem (`type="file"` com `accept="image/*"`).
   - Tabela contendo criadores cadastrados e atalho direto para o cadastro de obras.

5. **Cadastro de Obras/Músicas (`cadastro_musica.html`)**
   - Seleção obrigatória (Select) para o criador da obra.
   - Inputs para link externo (`type="url"`), upload de imagem e área de texto (`textarea`) expandida em 2 colunas.
   - Botão de navegação rápida de retorno e listagem de obras cadastradas.

---

## ⚙️ Requisitos Gerais e Boas Práticas

- **Arquivo de Estilo Único:** Toda a estilização está centralizada no arquivo `styles.css`.
- **Design System com Variáveis:** Identidade visual configurada no `:root` do CSS (paleta de cores, tipografia e bordas arredondadas).
- **Responsividade (Mobile First / Media Queries):** Layout totalmente adaptável para telas até 768px (formulários em 1 coluna, filtros empilhados e tabelas com rolagem horizontal).
- **Semântica e Acessibilidade:** Uso de tags semânticas HTML5 e rotulagem correta dos inputs (`<label>`).

---

🎯 *Trabalho acadêmico desenvolvido para fins de aprendizado no curso Técnico em Desenvolvimento de Sistemas — SENAI SP.*
