🎓 FATEC MasterClass - Plataforma de Aprovação

Uma "Enciclopédia de Bolso" interativa e moderna focada na aprovação de estudantes no vestibular da FATEC (Centro Paula Souza).

📖 Sobre o Projeto

O FATEC MasterClass é uma aplicação web desenvolvida para simular um ambiente de aprendizado (LMS) robusto. O objetivo foi criar uma ferramenta que não apenas lista tópicos, mas ensina através de uma interface rica, cobrindo as principais matérias do edital com profundidade teórica e recursos de estudo ativo.

O diferencial técnico deste projeto é sua arquitetura "Zero-Build Single File". Ele roda React e Tailwind diretamente no navegador via CDN, permitindo que a aplicação inteira seja contida em um único arquivo index.html, facilitando o deploy e a portabilidade.

✨ Funcionalidades

🧠 Estudo Ativo

Flashcards Interativos: Sistema de memorização com cartões que "viram" (flip effect) para fixação de fórmulas e conceitos.

Simulado Inteligente: Quiz com feedback imediato e explicações detalhadas baseadas nas "pegadinhas" da banca FATEC.

📚 Conteúdo Profundo

Apostila Digital: Conteúdo extenso cobrindo Português (Foco no Modernismo), Matemática, Física, Química, Biologia, História e Geografia.

Didática Visual: Boxes de fórmulas, alertas de "Pegadinhas da Banca" e exemplos práticos coloridos.

📝 Laboratório de Redação

Guia estrutural passo a passo para a dissertação argumentativa.

Lista de conectivos e critérios de avaliação oficiais.

💻 Interface (UI/UX)

Dashboard Gamificado: Barra de progresso e atalhos rápidos.

Responsividade Total: Menu lateral adaptável (Mobile/Desktop) e layout fluido.

Dark/Light Mode: Componentes estilizados com Tailwind para leitura agradável.

🛠️ Tecnologias Utilizadas

React (v18): Renderizado via Babel Standalone.

Tailwind CSS: Para estilização utilitária e responsiva.

Lucide React: Biblioteca de ícones moderna e leve.

HTML5 & ES6+: Estrutura semântica e JavaScript moderno.

🚀 Como Rodar o Projeto

Este projeto foi desenhado para ser extremamente simples de executar. Não é necessário instalar Node.js ou rodar npm install.

Opção 1: Rodar Localmente

Clone este repositório ou baixe o arquivo index.html.

Dê um duplo clique no arquivo index.html.

Pronto! A aplicação rodará no seu navegador padrão.

Opção 2: Hospedagem (Netlify/Vercel)

Arraste o arquivo index.html (ou a pasta contendo ele) para o Netlify Drop.

O site estará online em segundos.

📸 Screenshots

(Você pode adicionar prints do seu projeto aqui depois)

🧩 Estrutura do Código

O código segue o padrão Single File Component adaptado para HTML:

// Exemplo da estrutura interna
const subjects = { ... } // Banco de dados do conteúdo (JSON Like)
const SidebarItem = ({ ... }) => ... // Componentes UI reutilizáveis
const FATECMasterClass = () => { ... } // Componente Principal e Roteamento


👨‍💻 Autor

Desenvolvido com foco em Performance e Experiência do Usuário.

Este projeto é uma iniciativa educacional e não possui vínculo oficial com o Centro Paula Souza.
