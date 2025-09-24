# Artist Monitor - Sistema de Monitoramento de Artistas

Sistema de monitoramento em tempo real para produtoras de eventos, focado no acompanhamento de artistas através de múltiplas fontes de dados.

## 🎯 Objetivo

Monitorar 12 artistas específicos através de:
- Notícias e mídia
- Redes sociais
- Google Trends
- Escuta social geral

## 🎨 Artistas Monitorados

1. **Pearl Jam** - Rock Alternativo (EUA)
2. **Ivete Sangalo** - Axé/Pop (Brasil)
3. **Foo Fighters** - Rock (EUA)
4. **The Who** - Rock Clássico (Reino Unido)
5. **Racionais MCs** - Hip Hop (Brasil)
6. **Green Day** - Punk Rock (EUA)
7. **Rolling Stones** - Rock Clássico (Reino Unido)
8. **Roupa Nova** - Pop Rock (Brasil)
9. **Alok** - EDM/House (Brasil)
10. **Backstreet Boys** - Pop (EUA)
11. **Beyoncé** - R&B/Pop (EUA)
12. **Lady Gaga** - Pop/Dance (EUA)

## 🤖 Funcionalidades de IA

### Agentes de Inteligência Artificial
- **Análise de Tendências**: Identificação de padrões e crescimento
- **Detecção de Oportunidades**: Colaborações e eventos potenciais
- **Alertas Inteligentes**: Declínios ou mudanças significativas
- **Insights Estratégicos**: Sugestões baseadas em dados

### Tipos de Insights
- 🔥 **Tendências**: Crescimento em menções e engajamento
- 🎯 **Oportunidades**: Colaborações e eventos estratégicos
- ⚠️ **Alertas**: Declínios ou problemas identificados
- 💡 **Insights**: Padrões e recomendações gerais

## 📊 Métricas Monitoradas

### Por Artista
- **Score Social**: Engajamento geral nas redes sociais
- **Trending Score**: Tendência de crescimento
- **Menções Sociais**: Número total de menções
- **Notícias**: Quantidade de artigos recentes
- **Google Trends**: Popularidade nas buscas
- **Análise de Sentimento**: Positivo, Neutro, Negativo

### Métricas Agregadas
- Total de artistas monitorados
- Menções sociais totais
- Sentimento médio geral
- Notícias totais coletadas

## 🎨 Design System

### Paleta de Cores
- **Primária**: Azul Tecnológico (#0ea5e9)
- **Secundária**: Roxo Inovação (#8b5cf6)
- **Sucesso**: Verde (#10b981)
- **Alerta**: Amarelo (#f59e0b)
- **Erro**: Vermelho (#ef4444)

### Tema
- Tema escuro tecnológico
- Gradientes modernos
- Tipografia otimizada
- Componentes responsivos

## 🚀 Tecnologias

- **Frontend**: React 18 + Vite
- **UI Components**: Radix UI + Tailwind CSS
- **Charts**: Recharts
- **Icons**: Lucide React
- **Styling**: Tailwind CSS + CSS Variables

## 📱 Funcionalidades

### Dashboard Principal
- Visão geral com métricas principais
- Gráficos de tendências temporais
- Painel de insights de IA
- Notícias recentes
- Análise de sentimento

### Página de Artistas
- Cards individuais para cada artista
- Métricas detalhadas por artista
- Status de atividade
- Indicadores visuais de performance

### Analytics Avançado
- Gráficos comparativos
- Rankings de performance
- Análises de sentimento detalhadas
- Métricas históricas

### IA Insights
- Insights gerados automaticamente
- Níveis de confiança
- Sugestões acionáveis
- Priorização inteligente

## 🛠️ Instalação e Uso

```bash
# Instalar dependências
npm install

# Executar em desenvolvimento
npm run dev

# Build para produção
npm run build

# Preview da build
npm run preview
```

## 📁 Estrutura do Projeto

```
src/
├── components/
│   ├── ui/              # Componentes base (Radix UI)
│   ├── ArtistCard.jsx   # Card individual do artista
│   ├── AIInsightsPanel.jsx  # Painel de insights de IA
│   ├── TrendingChart.jsx    # Gráfico de tendências
│   ├── SentimentChart.jsx   # Gráfico de sentimento
│   └── NewsPanel.jsx        # Painel de notícias
├── data/
│   └── artistsData.js   # Dados mockados dos artistas
├── pages/
│   └── Dashboard.jsx    # Página principal
└── App.jsx              # Componente raiz
```

## 🎯 Casos de Uso

### Para Produtoras de Eventos
- Identificar artistas em alta para contratação
- Monitorar sentimento público sobre artistas
- Detectar oportunidades de colaboração
- Acompanhar tendências do mercado musical

### Insights Estratégicos
- Timing ideal para anúncios de eventos
- Artistas com maior potencial de público
- Identificação de nichos em crescimento
- Análise de concorrência

## 🔮 Funcionalidades Futuras

- Integração com APIs reais (Twitter, Instagram, Google Trends)
- Alertas em tempo real
- Relatórios automatizados
- Machine Learning para predições
- Integração com sistemas de CRM
- Dashboard mobile nativo

## 📄 Licença

Projeto desenvolvido para fins de demonstração e uso interno.

---

**Desenvolvido com ❤️ para produtoras de eventos que querem estar sempre um passo à frente no mercado musical.**

