# Agencia de Viajem
Modelo de Agência e Viajem

🚀 Funcionalidades
🌐 Navegação SPA
Transição suave entre páginas sem recarregamento

Menu responsivo com experiência mobile

Estados ativos nos links de navegação

Scroll automático para o topo nas transições

📱 Design Responsivo
Layout adaptável para desktop, tablet e mobile

Menu hamburguer para dispositivos móveis

Grids flexíveis que se ajustam ao tamanho da tela

Tipografia e espaçamento otimizados

🎨 Seções da Aplicação
Home (6 seções completas)

Hero section com call-to-action

Diferenciais da agência

Destinos em destaque

Experiências exclusivas

Depoimentos de clientes

Newsletter com formulário

Serviços

Cards com serviços premium

Ícones ilustrativos

Efeitos hover interativos

Pacotes

Catálogo de pacotes turísticos

Tags de categorias

Lista de benefícios

Botão de cotação

Destinos

Organização por continentes

Grid de países interativo

Informações regionais

Sobre

História da empresa

Equipe com fotos e descrições

Hero section dedicada

Contato

Formulário completo com validação

Informações de contato

Mapa ilustrativo

Campos para personalização da viagem

🛠️ Tecnologias Utilizadas
HTML5 - Estrutura semântica

CSS3 - Estilização avançada com:

Variáveis CSS (Custom Properties)

Flexbox e Grid Layout

Animações e transições

Media Queries

JavaScript Vanilla - Funcionalidades SPA

Font Awesome - Ícones

Google Fonts - Tipografia

🎯 Características Técnicas
Sistema de Design
Paleta de Cores:

Primária: #0A2463 (Azul marinho)

Secundária: #FF9F1C (Laranja)

Neutras: Tons de areia e branco

Tipografia:

Títulos: Playfair Display (serif)

Texto: Inter (sans-serif)

Componentes Reutilizáveis:

Botões com estados hover

Cards consistentes

Formulários padronizados

Seções com padding consistente

Performance
Código CSS otimizado e minificado inline

Sem dependências externas pesadas

Imagens otimizadas via Unsplash CDN

Carregamento rápido da SPA

Acessibilidade
Navegação por teclado

Contraste de cores adequado

Labels descritivos nos formulários

Alt text em imagens

📁 Estrutura do Projeto
text
odyssea-travel-agency/
│
├── index.html              # Arquivo principal (SPA completa)
│
├── SEÇÕES DA SPA:
│   ├── Home                # Página inicial com 6 subseções
│   ├── Serviços           # Catálogo de serviços
│   ├── Pacotes            # Pacotes turísticos
│   ├── Destinos           # Destinos por região
│   ├── Sobre              # Sobre a empresa
│   └── Contato            # Formulário de contato
│
└── RECURSOS:
    ├── CSS inline         # Todos os estilos no mesmo arquivo
    ├── JavaScript         # Lógica SPA no final do body
    ├── Imagens            | Via Unsplash CDN
    └── Ícones            | Font Awesome CDN
🚀 Como Executar
Clone o repositório:

bash
git clone [seu-repositorio]
Acesse o diretório:

bash
cd odyssea-travel-agency
Execute o arquivo:

Abra o arquivo index.html em qualquer navegador moderno

Ou utilize uma extensão Live Server no VS Code

Para desenvolvimento:

Não é necessário build ou compilação

Todas as dependências são via CDN

Edite diretamente o arquivo HTML

📱 Responsividade
O projeto foi desenvolvido com mobile-first approach e inclui:

Desktop: Layout completo com grids complexos

Tablet: Ajustes em grids e tipografia

Mobile: Menu hamburguer, single column layout

Breakpoint principal: 768px

🔧 Personalização
Modificando Cores
Edite as variáveis CSS na raiz do documento:

css
:root {
    --primary: #0A2463;
    --accent: #FF9F1C;
    /* Adicione suas cores aqui */
}
Adicionando Novas Seções
Crie um novo div com classe page-section hidden

Adicione um ID único

Atualize a navegação no header

Implemente a função showPage() para o novo ID

Substituindo Imagens
As imagens são carregadas via Unsplash CDN. Para substituir:

html
<img src="https://images.unsplash.com/[novo-link]" alt="Descrição">
