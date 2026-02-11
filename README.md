👁️ Queridômetro Divos Babilônicos
Sistema interativo de votação inspirado no reality show Big Brother Brasil, desenvolvido para a gestão de interações semanais entre participantes. O projeto utiliza persistência de dados local e autenticação simulada.

🚀 Funcionalidades
Sistema de Login Individual: Acesso restrito para os 19 participantes cadastrados (Senha padrão: 123).

Votação Semanal Controlada: Implementação de trava de segurança que permite apenas um emoji por pessoa por ciclo de votação, impedindo também o autovoto.

Painel Visual Dinâmico: Os participantes recebem destaques visuais automáticos baseados nos votos recebidos:

Favorito (Dourado): Maior número de corações.

Alvo (Azul): Maior número de alvos.

Odiado (Vermelho): Maior acúmulo de cobras e vômitos.

Área Administrativa (Kiara Only): Painel exclusivo para o usuário Kiara, permitindo visualização de estatísticas completas e reset do mês.

Tratamento de Imagens Robusto: Sistema de carregamento de fotos que normaliza nomes (remove acentos) e testa múltiplas extensões (.jpg, .png, .jpeg).

🛠️ Tecnologias Utilizadas
O projeto foi construído seguindo os princípios de desenvolvimento Front-end aprendidos no curso de ADS:

HTML5: Estruturação semântica do confessionário e cards.

CSS3: Design responsivo, animações de hover e estilização de badges de status.

JavaScript (ES6+): Lógica de negócios, manipulação do DOM e gestão de estado da aplicação.

LocalStorage: Persistência de dados no navegador do usuário.

GitHub Pages: Hospedagem e deploy contínuo da aplicação.

📂 Estrutura de Pastas
Bash
/
├── index.html         # Arquivo principal (HTML+CSS+JS)
└── fotos/             # Diretório contendo as fotos dos participantes
    ├── kiara.jpg
    ├── siqueira.jpg
    └── joao.jpg       # Nomes normalizados sem caracteres especiais
🔧 Como Executar o Projeto
Clone este repositório ou baixe o arquivo index.html.

Certifique-se de que a pasta fotos contém as imagens com nomes correspondentes aos participantes (em letras minúsculas).

Abra o arquivo index.html em qualquer navegador moderno.

Para testar as funções de administrador, realize o login selecionando o usuário Kiara.
