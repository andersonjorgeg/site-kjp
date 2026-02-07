# 🎨 Agência KJP - Landing Page (JS OOP Refactor)

Uma landing page moderna, **Mobile First** e de alta performance, desenvolvida para agências criativas. O projeto foi refatorado utilizando **Classes JavaScript (ES6)** para garantir um código limpo, modular e fácil de manter.

## 🚀 Funcionalidades

- **📱 Mobile First:** Layout desenvolvido priorizando dispositivos móveis, adaptando-se perfeitamente a telas maiores.
- **🧩 Arquitetura de Componentes:** O site é renderizado dinamicamente via JavaScript, dividido em classes lógicas (Header, Hero, Services, etc.).
- **⚙️ Fácil Configuração:** Todo o conteúdo (textos, imagens, links) está separado da lógica, permitindo edições rápidas sem tocar no HTML.
- **🎨 Design Premium:** Estética "Dark Mode" com efeitos de vidro (*glassmorphism*) e animações suaves.
- **⚡ Zero Dependências de Build:** Funciona diretamente no navegador com Tailwind via CDN.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura base (`<div id="app">`).
- **JavaScript (Vanilla ES6+):** Orientação a Objetos para renderização dos componentes.
- **Tailwind CSS (3.4):** Estilização utilitária rápida.
- **Google Fonts:** Tipografia *Spline Sans*.
- **Material Symbols:** Ícones vetoriais leves.

## 📂 Estrutura do Projeto

O código foi organizado para que você não precise procurar por textos no meio de tags HTML complexas. A estrutura segue este padrão:

1.  **Configuração & Dados:** Constantes no topo do script (`SITE_CONFIG`, `TEAM_DATA`).
2.  **Classes de Componentes:** Cada seção é uma classe independente com um método `.render()`.
3.  **Classe App:** Gerencia a inicialização e injeção no DOM.

## ⚙️ Como Personalizar

### 1. Alterar Textos e Imagens
Abra o arquivo `index.html` em um editor de código (como VS Code). Logo no início da tag `<script>`, você encontrará as constantes de dados.

**Exemplo - Alterar dados da Equipe:**
```javascript
const TEAM_DATA = [
    { 
        name: "Novo Nome", 
        role: "Novo Cargo", 
        img: "URL_DA_FOTO.jpg" 
    },
    // Adicione mais objetos aqui...
];