ACPO TERAPIA CAPILAR
Um website completo para salão de beleza com sistema de carrinho de compras e agendamento de serviços.

📋 Descrição do Projeto
O ACPO Terapia Capilar é uma aplicação web responsiva que combina catálogo de serviços e produtos de beleza com 
um sistema completo de e-commerce. O site permite aos clientes visualizar serviços disponíveis, comprar produtos 
profissionais e simular o processo de checkout com diferentes métodos de pagamento.

✨ Funcionalidades

🎯 Principais Recursos

Catálogo de Serviços: Apresentação visual dos serviços do salão com preços e descrições
Loja de Produtos: Sistema de e-commerce para produtos de beleza profissionais
Carrinho de Compras: Sistema completo com adição, remoção e alteração de quantidades
Sistema de Pagamento: Simulação de checkout com múltiplas formas de pagamento
Interface Responsiva: Design adaptável para desktop, tablet e mobile
Animações Interativas: Efeitos visuais modernos e transições suaves

🛒 Sistema de E-commerce
Adição de produtos/serviços ao carrinho
Controle de quantidade por item
Cálculo automático de totais
Modal do carrinho com visualização completa
Remoção individual de itens
Contador visual de itens no header

💳 Formas de Pagamento
Cartão de Crédito: Formulário com parcelamento em até 12x
Cartão de Débito: Pagamento à vista
PIX: Com 5% de desconto e QR Code simulado

🏗️ Estrutura do Projeto
acpo-terapia-capilar/
│
├── index.html              # Arquivo principal
├── README.md              # Este arquivo
│
└── Estrutura Interna:
    ├── CSS Integrado       # Estilos completos no <head>
    ├── JavaScript         # Funcionalidades no final do <body>
    └── Conteúdo HTML      # Estrutura semântica

🚀 Como Executar
Pré-requisitos
Navegador web moderno (Chrome, Firefox, Safari, Edge)
Não requer servidor local (arquivo estático)
Instalação e Execução
Clone ou baixe o projeto
bash
   git clone [url-do-repositorio]
   cd acpo-terapia-capilar
Abra o arquivo
Clique duplo em index.html
Ou abra através do navegador (File > Open)
Ou use um servidor local:
bash
     # Python 3
     python -m http.server 8000
     
     # Node.js (http-server)
     npx http-server
     
     # VS Code Live Server
     # Clique direito no arquivo > Open with Live Server
Acesse no navegador
Arquivo local: file:///caminho/para/index.html
Servidor local: http://localhost:8000

🎨 Tecnologias Utilizadas
Frontend
HTML5: Estrutura semântica e acessível
CSS3: Estilos modernos com flexbox e grid
JavaScript ES6+: Funcionalidades interativas
Recursos CSS
CSS Grid e Flexbox para layout responsivo
Gradientes lineares para visual moderno
Animações CSS (keyframes, transitions)
Media queries para responsividade
Backdrop-filter para efeitos de vidro
Funcionalidades JavaScript
Manipulação do DOM
Sistema de eventos
LocalStorage (comentado - alternativa com variáveis)
Formatação de dados (cartão, moeda)
Validação de formulários

📱 Design Responsivo
Breakpoints
Desktop: > 768px (layout completo)
Tablet: 768px - 480px (grid adaptável)
Mobile: < 768px (layout em coluna única)
Adaptações Mobile
Menu de navegação oculto
Grid de produtos em coluna única
Modal do carrinho em tela cheia
Formulários em layout vertical
Botões com toque otimizado

🧩 Componentes Principais
Header/Navegação
Logo com gradiente
Menu de navegação com efeitos hover
Botão do carrinho com contador
Design glassmorphism fixo
Seção Hero
Título principal com call-to-action
Fundo com gradiente e sobreposições
Botões para navegação interna
Design imersivo
Grid de Produtos/Serviços
Cards com hover effects
Badges promocionais
Seletores de quantidade
Botões de ação animados
Modal do Carrinho
Visualização completa dos itens
Controles de quantidade
Sistema de pagamento integrado
Cálculos automáticos de total
Formulários de Pagamento
Validação em tempo real
Formatação automática de dados
Múltiplas formas de pagamento
Feedback visual

🎯 Funcionalidades Específicas
Sistema de Carrinho
javascript
// Adicionar ao carrinho
addToCart(name, price, category, icon, button)

// Alterar quantidade
changeCartQuantity(id, delta)

// Remover item
removeFromCart(id)

// Atualizar interface
updateCartUI()
Formatação de Dados
javascript

// Número do cartão
formatCardNumber(input)

// Data de validade
formatExpiry(input)

// Validação de CVV

// Apenas números, máximo 4 dígitos
Métodos de Pagamento
Seleção visual interativa
Formulários condicionais
Cálculo de desconto PIX
Validação por tipo

📞 Informações de Contato
ACPO Terapia Capilar
Endereço: Rua Waldemar Fianco, 123 - Centro, ES
CEP: 29850-000
WhatsApp: (27) 99694-2124
Email: contato@bellavita.com.br
Horário de Funcionamento
Segunda a Sexta: 9h às 19h
Sábado: 9h às 17h
Domingo: Fechado

🔧 Personalização
Cores do Tema
css
/* Cores principais */
--primary-gradient: linear-gradient(135deg, #667eea 0%, #034510 100%);
--secondary-color: #034510;
--success-color: #2ed573;
--danger-color: #ff4757;
Adicionando Novos Produtos
Copie a estrutura HTML de um card existente
Altere o ícone, nome, preço e descrição
Atualize a função addToCart() com os novos dados
Modificando Formas de Pagamento
Adicione novo método em .payment-methods
Crie formulário correspondente em .payment-forms
Atualize a função selectPaymentMethod()

🚨 Observações Importantes
Limitações Atuais
Sistema de pagamento é apenas simulação
Não há integração com gateway de pagamento real
LocalStorage comentado (use variáveis JavaScript)
Imagens são representadas por emojis
Sugestões para Produção
Integrar com API de pagamento real (PagSeguro, Mercado Pago)
Implementar backend para processamento de pedidos
Adicionar sistema de autenticação de usuários
Implementar envio de emails de confirmação
Adicionar imagens reais dos produtos
Integrar com WhatsApp Business API

📄 Licença
Este projeto foi desenvolvido para uso comercial da ACPO Terapia Capilar. Todos os direitos reservados.

👥 Contribuição
Para sugestões ou melhorias, entre em contato através dos canais oficiais do salão.

Desenvolvido com 💜 para sua beleza

© 2025 ACPO Terapia Capilar - Todos os direitos reservados
