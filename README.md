# Ficha da Isa 🏋️

Site pessoal da minha rotina de treinos (Musculação + Muay Thai + Corrida + Bike + Vôlei).

## O que tem
- **Hoje** — o treino do dia, checklist das atividades, hidratação (12 copos de 250 ml) e cardápio do dia.
- **Semana** — os 7 dias com checklist e mapa de calor de constância das últimas 16 semanas.
- **Treinos** — Full Body A, Pernas e Full Body B com animação de cada exercício, link para vídeo, dicas de execução, registro de carga/repetições por série, cronômetro de descanso automático (2–3 min compostos, 60–90 s isoladores) com som e vibração, e aviso de **"Suba a carga"** quando bater o topo da faixa.
- **Evolução** — índice de evolução (constância 40% + força 30% + composição 30%), IMC, % de gordura (método da Marinha), proteína diária, gasto calórico, gráfico de peso e tabela de ganho de força.
- **Receitas** — 44 receitas locais; o site sorteia café, almoço, lanche e jantar diferentes a cada dia, com lista de compras e favoritos. A aba também busca receitas da internet pela API pública TheMealDB quando há conexão.
- **Diário alimentar** — pesquisa alimentos na base pública Open Food Facts, registra a quantidade consumida e soma calorias e proteínas do dia. Com idade preenchida no perfil, compara o consumo com uma estimativa de gasto diário.
- Funciona offline e pode ser **instalado no celular** (PWA) quando publicado no GitHub Pages.
- Tema claro/escuro, backup/restauração dos dados em JSON.

## Como publicar no GitHub Pages
1. Crie um repositório (ex.: `ficha-treino`) e envie **todos** os arquivos desta pasta mantendo a estrutura.
2. No repositório: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `root` → Save**.
3. Em 1–2 minutos o site fica em `https://SEU-USUARIO.github.io/ficha-treino/`.
4. No celular, abra o link e use **"Adicionar à tela inicial"** para virar app.

## Como editar
Tudo que é conteúdo (rotina, exercícios, séries, receitas, meta de peso) está em `js/dados.js`.
Os registros (checklist, cargas, pesos) ficam salvos no navegador de cada aparelho — use **Evolução → Baixar backup** para levar de um aparelho para outro.

## Créditos
Imagens dos exercícios: [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (domínio público / Unlicense).
Valores nutricionais e de composição corporal são estimativas e não substituem nutricionista ou educador físico.

As buscas online dependem de conexão e dos serviços TheMealDB e Open Food Facts; as receitas locais continuam disponíveis offline.
