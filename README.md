# 🍅 Fokus - Timer Pomodoro Inteligente com Gerenciador de Tarefas

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![LocalStorage](https://img.shields.io/badge/LocalStorage-Enabled-2ea44f?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

## 📋 Sobre o Projeto

Fokus é um aplicativo web completo de produtividade que combina a técnica Pomodoro com um gerenciador de tarefas integrado. Desenvolvido com foco em performance, responsividade e experiência do usuário, o projeto demonstra habilidades avançadas em desenvolvimento front-end.

**🎯 Objetivo:** Maximizar a produtividade através da combinação de ciclos de trabalho cronometrados e gestão organizada de tarefas.

### 🚀 **Destaques Técnicos (Para Recrutadores)**

- **Arquitetura sem frameworks:** Implementação vanilla com organização modular
- **Design System consistente:** Variáveis CSS, componentes reutilizáveis
- **Persistência de dados:** LocalStorage para salvar tarefas entre sessões
- **Responsividade mobile-first:** Layout adaptável para todos os dispositivos
- **Performance otimizada:** Código minificado, assets otimizados
- **Acessibilidade:** HTML semântico, contraste adequado, navegação por teclado
- **SEO friendly:** Meta tags, estrutura hierárquica, conteúdo indexável

## ✨ Funcionalidades

### 🎯 Sistema Pomodoro
- **Foco (25min):** Período de concentração máxima
- **Descanso Curto (5min):** Pausas rápidas para recuperação
- **Descanso Longo (15min):** Intervalos maiores após ciclos completos

### 📝 Gerenciador de Tarefas
- **Adição de tarefas:** Formulário dinâmico com validação
- **Edição em tempo real:** Modificação de tarefas com prompt nativo
- **Marcação de conclusão:** Integração automática com o timer Pomodoro
- **Filtros inteligentes:**
  - Remover tarefas concluídas
  - Remover todas as tarefas
- **Persistência:** Dados salvos automaticamente no LocalStorage
- **Seleção ativa:** Destaque visual da tarefa em progresso

### 🎵 Recursos Interativos
- **Contador regressivo visual** com feedback em tempo real
- **Sistema de música ambiente** para imersão
- **Efeitos sonoros** para transições (play, pause, notificação)
- **Interface com estados visuais** (ativo, pausado, em andamento)
- **Background dinâmico** que muda conforme o modo selecionado
- **Eventos customizados** para integração entre componentes

### 📱 Responsividade
- Layout otimizado para mobile (320px+)
- Design adaptativo para tablets e desktops
- Componentes que se reorganizam inteligentemente
- Fontes e espaçamentos escaláveis

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade | Destaque |
|------------|------------|----------|
| **HTML5** | Estrutura semântica | Tags semânticas, meta tags SEO |
| **CSS3** | Estilização avançada | Variáveis CSS, Flexbox, Media Queries |
| **JavaScript ES6+** | Lógica da aplicação | DOM Manipulation, Event Listeners, Audio API |
| **LocalStorage API** | Persistência de dados | Armazenamento local de tarefas |
| **Google Fonts** | Tipografia | Fontes Montserrat, Unbounded e Prata |
| **CSS Reset** | Consistência cross-browser | Normalização de estilos padrão |

## 🎨 Design System

### Paleta de Cores
```css
--color-primary: #123456;      /* Azul principal */
--azul-royal: #144480;         /* Azul real para elementos ativos */
--lils: #B872FF;               /* Lilás para elementos interativos */
--color-secondary: #FFF;       /* Branco para textos */
```

### Gradientes Contextuais
- **Modo Foco:** Roxo → Azul escuro
- **Descanso Curto:** Verde → Azul escuro
- **Descanso Longo:** Azul claro → Azul escuro

## 🚀 Como Executar o Projeto

### Opção 1: Visualização Online
- **GitHub Pages:** [Link para deploy] *(adicione quando fizer deploy)*
- **Live Server:** Disponível via extensão do VS Code

### Opção 2: Execução Local
```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/fokus-pomodoro.git

# 2. Acesse a pasta do projeto
cd fokus-pomodoro

# 3. Execute com um servidor local
# Usando Python (qualquer versão)
python -m http.server 8000

# Ou usando Node.js com http-server
npx http-server

# 4. Acesse no navegador
http://localhost:8000
```

## 🔄 Fluxo de Trabalho Integrado

### 1. **Configuração Inicial**
```javascript
// Adicione tarefas
- Clique no botão "+ Adicionar Tarefa"
- Digite a descrição da tarefa
- Confirme com Enter ou clique fora

// Selecione uma tarefa ativa
- Clique em uma tarefa para selecioná-la
- A tarefa ativa aparece destacada
```

### 2. **Ciclo Pomodoro com Tarefas**
```javascript
// Inicie o timer
- Selecione o modo (Foco/Descanso)
- Clique em "Começar"
- O timer inicia a contagem regressiva

// Conclusão automática
- Ao final do timer Foco, a tarefa ativa é marcada como concluída
- Receba notificação visual e sonora
```

### 3. **Gerenciamento Avançado**
```javascript
// Edição de tarefas
- Clique no ícone de lápis
- Digite a nova descrição
- Atualização automática no LocalStorage

// Limpeza de lista
- "Remover Concluídas": Remove apenas tarefas finalizadas
- "Remover Todas": Limpa toda a lista
```

## 📱 Compatibilidade

| Navegador | Status | Observações |
|-----------|--------|-------------|
| Chrome 90+ | ✅ Ótimo | Totalmente compatível |
| Firefox 88+ | ✅ Ótimo | Funcionalidades completas |
| Safari 14+ | ✅ Bom | Suporte a ES6+ e LocalStorage |
| Edge 90+ | ✅ Ótimo | Baseado em Chromium |
| Mobile Safari | ✅ Bom | Responsivo e touch-friendly |

## 🔍 SEO e Acessibilidade

### Meta Tags Implementadas
```html
<meta charset="UTF-8"> <!-- Codificação correta -->
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Mobile-first -->
<title>Fokus</title> <!-- Título conciso e relevante -->
```

### Boas Práticas Implementadas
- **HTML semântico** com tags adequadas (main, section, header, footer)
- **Alt text** em todas as imagens
- **Hierarquia de cabeçalhos** (h1, h2, h3)
- **Contraste de cores** WCAG AA compliant
- **Navegação por teclado** totalmente funcional
- **ARIA labels** para elementos interativos

## 📈 Performance

### Otimizações Implementadas
- **CSS reset** para consistência entre navegadores
- **Fontes externas** carregadas assincronamente
- **Imagens otimizadas** com compressão adequada
- **JavaScript não-bloqueante** (defer attribute)
- **Áudios pré-carregados** para resposta imediata
- **LocalStorage eficiente** com atualizações seletivas

## 🎯 Casos de Uso

### 💼 Para Profissionais
- **Desenvolvedores:** Gerenciar tasks de sprints com foco cronometrado
- **Designers:** Organizar etapas criativas com pausas programadas
- **Estudantes:** Planejar sessões de estudo com metas específicas
- **Escritores:** Dividir capítulos em blocos de escrita focada

### 🔄 Técnica Pomodoro Aprimorada
1. **Adicione tarefas** à lista
2. **Selecione uma tarefa** para trabalhar
3. **Defina o timer** para 25min (modo Foco)
4. **Trabalhe na tarefa selecionada** até o timer tocar
5. **Tarefa é marcada como concluída** automaticamente
6. **Faça uma pausa curta** (5min)
7. **A cada 4 pomodoros**, faça uma pausa longa (15min)

## 👩‍💻 Habilidades Demonstradas

### Hard Skills
- **DOM Manipulation Avançada:** Criação dinâmica de elementos
- **CSS Architecture:** Organização escalável de estilos
- **JavaScript Modules:** Separação de responsabilidades
- **Event Handling Complexo:** Sistema completo de interações
- **Audio Web API:** Controle de mídia nativo
- **LocalStorage API:** Persistência de dados no cliente
- **Responsive Design:** Adaptação a múltiplos dispositivos
- **Eventos Customizados:** Comunicação entre componentes

### Soft Skills
- **Solução de problemas complexos:** Integração timer-tarefas
- **Atenção a detalhes:** Micro-interações e transições
- **UX/UI thinking:** Experiência fluida e intuitiva
- **Documentação completa:** README estruturado e informativo
- **Gestão de estado:** Controle de dados da aplicação

## 👤 Autor

**Daniella Dantas**  
*Desenvolvedora Front-end*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniella-dantas)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dani-dantas)

## 📄 Licença

Este projeto é fictício e sem fins comerciais. As imagens foram geradas por IA no Adobe Firefly.

```
Copyright © 2024 Daniella Dantas

Permissão é concedida para visualizar e utilizar este projeto para fins de
aprendizado, portfólio e avaliação técnica. Proibida a redistribuição comercial.
```

---

<div align="center">

### ⭐ Se você gostou deste projeto, considere dar uma estrela no repositório!

**"Produtividade inteligente: tarefas organizadas, foco cronometrado."** 🍅

</div>
