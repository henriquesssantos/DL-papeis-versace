# 🏛️ DL Papéis & Persianas - Alto Padrão (Versace Landing Page)

Projeto front-end de uma Landing Page comercial de luxo para apresentação de papéis de parede, persianas e cortinas de alto padrão, visualmente inspirada na sofisticação da estética *Versace*.

Este trabalho foi construído como primeiro projeto prático da disciplina de **Programação Web** na 1ª fase do curso de **Análise e Desenvolvimento de Sistemas (ADS)**, aplicando conceitos de marcação semântica HTML5, estilização moderna CSS3, integração de bibliotecas JS externas e Design Responsivo.

---

## 🎯 Objetivo do Projeto

Desenvolver uma vitrine digital de alta conversão para o segmento de arquitetura e decoração de luxo. A página foi pensada para proporcionar navegação fluida em dispositivos móveis e desktops, combinando apelo visual elegante com **Chamadas para Ação (CTA)** diretas integradas à API do WhatsApp e links para mídias sociais.

---

## 🚀 Funcionalidades e Interatividade

- **Carrossel Suave e Contínuo (Infinite Autoplay):** Implementação da biblioteca **Swiper.js** com rolagem automática suave (`speed: 8000`), transições sem pausas bruscas, controle por toque/arrasto (`grabCursor: true`) e paginação interativa.
- **Catálogo de Soluções com Cards Interativos:** Apresentação em cards de "Papéis de Parede", "Persianas" e "Cortinas", com efeitos visuais de elevação ao passar o mouse (`transform: translateY`) e botões de contato dinâmicos.
- **Redes Sociais e API WhatsApp Integradas:** Botões estrategicamente posicionados no cabeçalho, nos cards e no rodapé que acionam links diretos de conversa via WhatsApp com mensagens personalizadas pré-definidas (`wa.me`).
- **Seção de Diferenciais Institucionais:** Exibição em grade estruturada com ícones do **FontAwesome**, destacando a autoridade e os diferenciais técnicos da empresa.

---

## 🛠️ Conceitos Técnicos e Arquitetura Front-end

O projeto explora técnicas modernas de desenvolvimento front-end estático sem depender de frameworks CSS pesados:

*   **HTML5 Semântico:**
    * Uso de tags como `<nav>`, `<section>`, `<footer>` e divisão em blocos modulares.
    * Incorporação de ícones vetorizados através da CDN do **Font Awesome** (`<i class="fab ...">`).
*   **CSS3 Avançado & Resolução de Bugs Nativa:**
    * **Pseudo-elementos (`::after` e `::before`):** O fundo temático "Versace" foi implementado como uma camada fixa (`position: fixed`) esticada em `-50px` nas bordas, junto com uma película de escurecimento (`rgba(0,0,0,0.75)`). Isso corrige **definitivamente o bug visual no Safari / iOS** que distorce fundos fixos em celulares.
    * **Flexbox & Grid Layout:** Alinhamento dinâmico de cards, navegação, ícones de redes sociais e seções institucionais.
    * **Microinterações e Efeitos Visuais:** Uso de `mix-blend-mode: lighten` nas logos, escala gradual de imagens nos cards (`transform: scale(1.1)`) e efeitos de sombra de profundidade (`box-shadow`).
*   **Design Responsivo (Media Queries + Breakpoints Swiper):**
    * Adaptação total para smartphones (`320px`/`600px`), tablets (`640px`/`768px`) e desktops (`1024px+`).
    * Ajuste estrutural completo da Navbar (de cabeçalho centralizado com logo grande para menu enxuto na horizontal em dispositivos móveis).

---

## 💻 Como Executar e Visualizar o Projeto

Por se tratar de um projeto **Front-end estático**, ele não requer a instalação de Node.js, dependências locais ou bancos de dados.

### 1. Visualização via GitHub Pages (Recomendado)
Acesse a demonstração online e interativa diretamente no navegador:
👉 **[Clique aqui para ver o site rodando](https://henriquesssantos.github.io/DL-papeis-versace)** *(Nota: Ative o GitHub Pages na branch do repositório)*

### 2. Execução Local
1. Clone este repositório para a sua máquina:
   ```bash
   git clone [https://github.com/henriquesssantos/DL-papeis-versace.git](https://github.com/henriquesssantos/DL-papeis-versace.git)
