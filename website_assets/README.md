# Site Institucional Cultiagro

## Visão Geral
Site institucional responsivo para empresa de importação e exportação de grãos e alimentos, desenvolvido com design profissional e identidade visual da Cultiagro.

## Características do Projeto

### 🎨 Design
- **Paleta de cores**: Baseada no logo Cultiagro - marrom (#8B5E3C), verde (#4A7C3F) e tons terrosos
- **Logo**: Logo oficial da Cultiagro integrado ao cabeçalho
- **Tipografia**: Inter (Google Fonts) - moderna e profissional
- **Layout**: Moderno, limpo e organizado
- **Imagens**: Alta qualidade relacionadas ao agronegócio brasileiro

### 📱 Responsividade
- **Desktop**: Layout completo com grid de 3 colunas
- **Tablet**: Adaptação para 2 colunas e ajustes de espaçamento
- **Mobile**: Layout em coluna única com menu hambúrguer

### 🚀 Funcionalidades
- Menu de navegação responsivo com scroll suave
- Filtros interativos na página de produtos
- Formulário de contato funcional
- Animações e transições suaves
- Otimização SEO básica

## Estrutura do Site

### 📄 Páginas Incluídas
1. **index.html** - Página inicial com banner, serviços e apresentação
2. **produtos.html** - Catálogo de produtos com filtros e especificações
3. **sobre.html** - História da empresa, timeline e equipe

### 📁 Estrutura de Arquivos
```
website_assets/
├── index.html              # Página inicial
├── produtos.html           # Página de produtos
├── sobre.html             # Página sobre a empresa
├── README.md              # Esta documentação
├── test_results.md        # Resultados dos testes
└── images/                # Pasta de imagens
    ├── cultiagro_logo.png # Logo oficial da Cultiagro
    ├── colheita_soja.jpg
    ├── ciclo_soja.jpg
    ├── producao_graos.jpg
    ├── campo_vegetal.jpg
    ├── milho_campo_verde.jpg
    ├── milho_colheita.jpg
    ├── safra_graos.jpg
    ├── planejamento_colheita.jpeg
    ├── navio_graos.jpg
    ├── transporte_graos.jpg
    ├── navios_poroes.jpeg
    ├── exportacao_conteineres.jpg
    ├── exportacao_alimentos.jpg
    ├── exportacao_alimentos_brasil.jpg
    ├── logistica_agronegocio.webp
    └── logistica_agronegocio_desafios.webp
```

## Como Usar

### 🌐 Visualização Local
1. Extraia todos os arquivos em uma pasta
2. Abra o arquivo `index.html` em um navegador web
3. Navegue pelas páginas usando o menu superior

### 🚀 Hospedagem
Para colocar o site online:
1. Faça upload de todos os arquivos para seu servidor web
2. Configure o domínio para apontar para a pasta do site
3. Certifique-se de que o arquivo `index.html` está na raiz

### ✉️ Configuração do Formulário
O formulário de contato está configurado para abrir o cliente de email padrão. Para integração com servidor:
1. Substitua a função `handleSubmit()` no JavaScript
2. Configure um endpoint para processar os dados do formulário
3. Adicione validação server-side conforme necessário

## Conteúdo Personalizado

### 🏢 Informações da Empresa
- **Nome**: Cultiagro
- **Slogan**: "Conectando grãos e alimentos ao mercado global"
- **Foco**: Importação e exportação de grãos e alimentos
- **Mercados**: +50 países atendidos
- **Experiência**: 25 anos no mercado
- **Email**: comercial@cultiagro.com.br

### 📦 Produtos Destacados
1. **Soja em Grão** - Principal produto de exportação
2. **Milho em Grão** - Versátil para indústria e ração
3. **Trigo** - Para panificação e indústria alimentícia
4. **Farelo de Soja** - Rico em proteínas para nutrição animal
5. **Óleo de Soja** - Refinado para consumo e indústria
6. **Grãos Orgânicos** - Linha premium certificada

### 🌍 Mercados de Atuação
- América do Norte
- América Latina  
- Europa
- Ásia
- África
- Oceania

## Tecnologias Utilizadas

### 💻 Frontend
- **HTML5**: Estrutura semântica moderna
- **CSS3**: Flexbox, Grid, animações e responsividade
- **JavaScript**: Interatividade e funcionalidades dinâmicas
- **Font Awesome**: Ícones profissionais
- **Google Fonts**: Tipografia Inter

### 🔧 Recursos Técnicos
- CSS Grid e Flexbox para layouts responsivos
- Media queries para diferentes breakpoints
- Smooth scrolling e animações CSS
- Otimização de imagens e performance
- Meta tags para SEO básico

## Customização

### 🎨 Alterando Cores
As cores estão definidas em variáveis CSS no início de cada arquivo:
```css
:root{
  --bg:#FAF7F2;           /* Fundo principal */
  --earth-1:#8B5E3C;      /* Marrom do logo Cultiagro */
  --earth-2:#A68A6A;      /* Marrom claro da espiga */
  --green-1:#4A7C3F;      /* Verde do logo Cultiagro */
  --green-2:#6FA66F;      /* Verde médio */
  --accent:#D9C7A6;       /* Tons terrosos claros */
  --muted:#6B6B6B;        /* Texto secundário */
}
```

### 📝 Alterando Conteúdo
- **Textos**: Edite diretamente no HTML
- **Imagens**: Substitua os arquivos na pasta `images/`
- **Logo**: Substitua `cultiagro_logo.png` mantendo o mesmo nome
- **Informações de contato**: Atualize na seção de contato
- **Redes sociais**: Adicione os links corretos no rodapé

### 📱 Ajustando Responsividade
Os breakpoints estão definidos nas media queries:
- **Desktop**: Acima de 1024px
- **Tablet**: 768px - 1024px  
- **Mobile**: Abaixo de 768px

## Suporte e Manutenção

### 🔍 Testes Realizados
- ✅ Responsividade em diferentes dispositivos
- ✅ Compatibilidade com navegadores modernos
- ✅ Velocidade de carregamento otimizada
- ✅ Acessibilidade básica implementada
- ✅ SEO on-page configurado
- ✅ Identidade visual Cultiagro aplicada

### 📈 Melhorias Futuras Sugeridas
1. **Backend**: Integração com sistema de gestão
2. **CMS**: Painel administrativo para edição de conteúdo
3. **Analytics**: Google Analytics para métricas
4. **Chat**: Sistema de chat online
5. **Blog**: Seção de notícias do agronegócio
6. **Multilíngua**: Versões em inglês e espanhol

## Contato para Suporte
Para dúvidas sobre implementação ou customizações, consulte a documentação técnica ou entre em contato com o desenvolvedor.

---

**Desenvolvido com foco na excelência e sustentabilidade do agronegócio brasileiro** 🌱

