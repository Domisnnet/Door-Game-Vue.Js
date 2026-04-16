![GitHub repo size](https://img.shields.io/github/repo-size/Domisnnet/Door-Game-Vue.Js?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/Domisnnet/Door-Game-Vue.Js?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Domisnnet/Door-Game-Vue.Js?style=for-the-badge)

<h2 id="sobre-o-projeto">1. 🚪 Monty Hall: O Jogo das Portas Reativo 🎁</h2>

![Status do Deploy](https://img.shields.io/badge/Status-Online-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-Vue.js%20%7C%20CSS-4FC08D)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/jogo-monty-hall/blob/main/LICENSE)

![Preview do Jogo das Portas](src/assets/iMac-24-1120x630.png)

Bem-vindo ao **Jogo das Portas**! Esta aplicação, desenvolvida com **Vue.js**, é uma implementação interativa do famoso paradoxo matemático de Monty Hall. O usuário pode configurar dinamicamente o número de portas e esconder um presente atrás de uma delas. O desafio é testar a sua sorte e lógica enquanto uma trilha sonora imersiva acompanha a jogatina.

---

## 📚 Tabela de Conteúdo

| 🚪 O Projeto | 🛠️ Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Repositório](https://img.shields.io/badge/6%20-%20Repo-009688)](#codigo-fonte) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Acessar](https://img.shields.io/badge/3%20-%20Acessar-FF9800)](#como-acessar) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Funções](https://img.shields.io/badge/4%20-%20Funções-9C27B0)](#funcionalidades) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙️ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Framework** | ![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D) | Reatividade e gerenciamento de estado dos componentes. |
| **Estilo** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Gradientes dinâmicos e animações de transição (`transition-group`). |
| **Multimídia** | ![Audio](https://img.shields.io/badge/Audio-HTML5-orange?style=flat-square) | Manipulação de áudio ambiente via referências do Vue. |

---

<h2 id="como-acessar">3. 🚀 Como Acessar</h2>

Teste sua sorte e escolha a porta premiada agora mesmo:

<div align="left">
  <a href="https://github.com/Domisnnet/Door-Game-Vue.Js" target="_blank">
    <img alt="Botão Acessar" src="src/assets/img/botão.webp" height="70" width="70" />
  </a>
</div>

---

<h2 id="funcionalidades">4. 🧩 Funcionalidades Principais</h2>

O jogo oferece uma experiência customizável e fluida:

| Funcionalidade | Descrição |
| :--- | :--- |
| 🛠️ **Setup Dinâmico** | Defina a quantidade de portas e a porta premiada antes de começar. |
| 🎵 **Música Ambiente** | Trilha sonora em loop que inicia automaticamente com o jogo. |
| ✨ **Transições Suaves** | Animações de entrada e saída das portas usando `door-fade`. |
| 🔄 **Reset Total** | Reinicie a partida e limpe o estado do jogo com um único clique. |
| 📱 **Responsividade** | Layout adaptável para dispositivos móveis e desktops. |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

Este projeto foca em reatividade e manipulação do DOM virtual:

### 📐 Gerenciamento de Estado
Uso do `v-model.number` para garantir a integridade dos dados de entrada e `v-bind` dinâmico para injetar as propriedades (`props`) no componente `Door`.

### 🔄 Manipulação de Áudio via Refs
Utilização de `this.$refs.bgMusic` para controlar o volume e o estado da música (play/pause) sincronizado com as ações do usuário dentro do ciclo de vida do componente.

---

<h2 id="codigo-fonte">6. 📂 Repositório</h2>

Explore a arquitetura de componentes deste projeto Vue:

[![Repositório](https://img.shields.io/badge/Repositório-Domisnnet%2FDoor--Game--Vue.Js-1DB954?style=for-the-badge&logo=github)](https://github.com/Domisnnet/Door-Game-Vue.Js)

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

Siga os passos abaixo para adicionar novas mecânicas ao jogo:

| Fase | Ação | Link / Comando |
| :---: | :--- | :--- |
| **01** | **Fork** | [![Fork](https://img.shields.io/badge/-Fazer%20Fork-blue?style=flat-square&logo=github)](https://github.com/Domisnnet/Door-Game-Vue.Js/fork) |
| **02** | **Branch** | `git checkout -b feature/NovosSons` |
| **03** | **Commit** | `git commit -m 'feat: sons de abertura de porta'` |
| **04** | **Push** | `git push origin feature/NovosSons` |
| **05** | **PR** | [![Abrir PR](https://img.shields.io/badge/-Abrir%20PR-green?style=flat-square&logo=git)](https://github.com/Domisnnet/Door-Game-Vue.Js/compare) |


---

<h2 id="faq">8. 🧠 Perguntas Frequentes</h2>

<details>
<summary><strong>Por que a música não toca sozinha ❓</strong></summary>
<p>🔊 <strong>Resposta:</strong> A maioria dos navegadores modernos bloqueia o autoplay de áudio sem interação prévia. Por isso, a música inicia no método <code>validateAndStart</code>, após o primeiro clique do usuário.</p>
</details>

<details>
<summary><strong>Como o jogo sabe onde está o presente ❓</strong></summary>
<p>🎁 <strong>Resposta:</strong> Cada componente <code>Door</code> recebe uma prop <code>hasGift</code> que é uma comparação booleana entre o índice atual e o valor de <code>selectedPort</code>.</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

Analise os componentes e a lógica central do App:

![Repositório](https://img.shields.io/badge/Código%20Fonte-Acessar-795548?style=for-the-badge&logo=github)](https://github.com/Domisnnet/Door-Game-Vue.Js/tree/main)

---

<h2 id="créditos">10. 📝 Créditos & Reconhecimentos</h2>

O Jogo das Portas une matemática e tecnologia front-end:

| Atribuição | Responsável / Recurso | Descrição |
| :--- | :--- | :--- |
| **Dev Front-end** | **DomisDev** | Desenvolvimento da lógica reativa e integração de áudio. |
| **Paradoxo** | **Monty Hall** | Inspiração teórica baseada no problema de probabilidade. |
| **UI Design** | **Google Fonts** | Uso da fonte "Montserrat" para uma interface moderna. |
| **Apoio Técnico** | **Google Gemini** | Padronização King-Domfy e refinamento documental. |

---

<h2 id="licenca">11. 📄 Licença</h2>

Este projeto está licenciado sob a [![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/Door-Game-Vue.Js/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨‍💻 Perfil do GitHub</h2>

<a href="https://github.com/Domisnnet"> 
  <img src="src/assets/DomisDev.png" width="120" alt="Acessar perfil GitHub"> 
</a>