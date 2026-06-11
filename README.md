
### 📁 Projeto 3: wikiwave

# 🌊 WikiWave - Buscador de Artigos Temáticos

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E) ![CSS Grid](https://img.shields.io/badge/CSS%20Grid-1572B6)

## 📖 Sobre o projeto

WikiWave é uma interface de busca de artigos inspirada em enciclopédias online. O usuário digita um termo e a aplicação simula a busca (usando um dataset local) e exibe resultados em cards organizados com CSS Grid. O projeto foi criado para praticar consumo de dados (mock) e design moderno.

## 🧰 Tecnologias utilizadas

- **HTML5** – estrutura
- **CSS3** – Grid Layout, transições, variáveis
- **JavaScript** – manipulação de array, filtros, renderização dinâmica

## 🔍 Funcionalidades

- Campo de busca com autocomplete parcial
- Resultados exibidos em grid responsivo (3 colunas no desktop, 1 no mobile)
- Cada artigo tem título, resumo e tag
- Sem dependências externas (vanilla JS)

## 🚀 Como testar

```bash
git clone https://github.com/johnnymartins/wikiwave.git
cd wikiwave
```
# Abra o index.html

Ou acesse o [demo ao vivo](https://wikiwavesite.vercel.app/)

📚 O que aprendi

   - Como estruturar um filtro dinâmico com filter() e map()
   - Uso de `localStorage` para salvar últimos termos buscados
   - CSS Grid avançado para responsividade
   - Debounce em campo de busca (para não executar a cada tecla)

🔜 Próximos passos

   - Substituir o dataset local por uma API real (ex: Wikipedia ou NewsAPI)
   - Adicionar paginação nos resultados
   - Criar página de detalhes do artigo

Feedbacks são muito bem-vindos! Abra uma issue ou me mande uma mensagem.
