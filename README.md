# 🌍 Movimento Juntos pelo Bem

Plataforma digital de uma ONG voltada a transformar vidas por meio da educação, alimentação e capacitação profissional.  
Este repositório contém o site institucional construído com **HTML5, CSS3 e JavaScript**.

---

## 🚀 Estrutura do Projeto

├── index.html → Página inicial (sobre e contato)
├── projetos.html → Projetos sociais e voluntariado
├── cadastro.html → Formulário de cadastro de doadores e voluntários
├── css/
│ └── styles.css → Design system responsivo e acessível
├── js/
│ └── script.js → Interações e validação de formulários
├── assets/
│ └── logo.png
├── img/
│ └── imagens diversas

## 🧱 Tecnologias Utilizadas

- **HTML5** → Estrutura semântica e acessível  
- **CSS3 (Grid + Flexbox)** → Layout responsivo e moderno  
- **JavaScript (puro)** → Manipulação de DOM, validação e SPA básica  
- **Git + GitHub** → Controle de versão com GitFlow e versionamento semântico


## Guia de Testes de Acessibilidade (WCAG 2.1 Nível AA)

Instruções resumidas para validar as funcionalidades acessíveis implementadas no site.

1) Navegação por teclado
   - Abra a página em um navegador (Chrome/Edge/Firefox).
   - Use Tab / Shift+Tab para navegar entre links, botões e campos de formulário.
   - Pressione Enter ou Espaço para ativar botões (ex.: "Modo Escuro", "Alto Contraste").
   - No menu "Projetos": pressione Tab até o botão "Projetos" e pressione Enter ou ArrowDown para abrir. Use ArrowUp / ArrowDown para navegar entre itens; pressione Esc para fechar.

2) Teste de leitores de tela
   - Windows: instale e use NVDA (https://www.nvaccess.org/).
   - Mac: use VoiceOver (Cmd+F5).
   - Verifique se:
     * O botão "Projetos" anuncia seu estado (expandido/colapsado).
     * As imagens possuem atributos alt descritivos.
     * Mensagens de status (toasts) e mudanças de tema são anunciadas (área com aria-live).

3) Contraste de cores
   - Use a extensão WAVE (WebAIM) ou axe DevTools.
   - Verifique especificamente: links, botões, textos pequenos e itens do submenu.

4) Modo Escuro e Alto Contraste
   - Use os botões no cabeçalho: "Modo Escuro" e "Alto Contraste".
   - O estado é persistido entre recarregamentos (localStorage).
   - O ativador é acessível via teclado e anunciado por leitores de tela.

5) Verificação automatizada
   - Ferramentas recomendadas:
     * WAVE Extension
     * axe DevTools
     * Lighthouse (Chrome DevTools)

Observação:
- O submenu "Projetos" abre ao passar o mouse (hover) e também responde ao teclado. Ele fecha automaticamente quando o foco sai do menu ou ao pressionar Esc.
- Para quaisquer ajustes visuais adicionais (cores, tamanhos, etc.), consulte o arquivo styles.css.


