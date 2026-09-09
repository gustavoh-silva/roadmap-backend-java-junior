# Roadmap Java Backend → Júnior

> **Posicionamento:** trilha Backend-first (80–90% Backend, 10–20% Frontend como trilha secundária que nunca bloqueia os Gates de Backend).

Dashboard estático em `index.html` (sem build, GitHub Pages), orientado a **Gates de competência**: G0 Fundamentos → G1 Backend Foundation → **G2 Gate de Estágio** → G3 Backend Júnior → G4 Avançado, mais **F1 Frontend Complementar** (opcional).

## Por que isso existe

Antes esse roadmap vivia como um artifact dentro de uma conversa específica no
Claude — pra marcar o que já tinha sido estudado, era preciso voltar exatamente
àquele chat. Isso quebrava o hábito de acompanhamento. Agora é uma página
estática hospedada no GitHub Pages, com progresso salvo no navegador.

## Estrutura

```
.
├── index.html                     # o dashboard em si
└── .github/workflows/Pages.yml    # publica o index.html no GitHub Pages a cada push
```

Não há build step nem framework: os dados ficam embutidos no próprio `index.html`,
dentro do bloco `<script>`, nas constantes `GATES` (G0–G4), `FRONT` (F1), `CAND`
(candidatura) e `DIF` (diferenciais). Editar o conteúdo é abrir o array, mudar
o texto, commitar. Visual segue o tema **Nocturne Gallery** (dark-only, Inter
ss03, Action Sky `#2997ff`, tiles alternados, busca `⌘K` que filtra critérios);
pills de prioridade usam os accents: `CORE` vermelho, `COMP` amarelo, `AVANC`
azul, `FRONT` verde.

## V3 — o que mudou desde a V2

- **Projetos com nome e continuidade**, em vez de "projeto obrigatório" genérico:
  `BiblioTrack` (G0, console) → `TaskFlow` (G1, API) → `TaskFlow — versão
  profissional` (G2, +JWT/Docker) → `TaskFlow em produção` (G3, deploy) →
  `Capstone` (G4, um conceito avançado com profundidade real).
- **Maven** (G0) e **Flyway** (G1) entraram como critérios explícitos —
  ambos citados em vagas reais e ausentes da V2.
- **G3 ganhou "Documentação profissional da API e do projeto"** como CORE
  (antes só aparecia implicitamente).
- **"O que você precisa conseguir explicar"** por Gate: 3 perguntas que
  transformam entrevista em validação de competência, não checklist de
  decorar.
- **Card "IA como ferramenta, não substituto"**: o que pode acelerar
  (boilerplate, explicar erro, docs) vs. o que precisa continuar sendo seu
  (explicar o próprio código, justificar decisão, debugar sem colar tudo
  numa IA).
- **Nota de indicador**: números como "20 exercícios" ou "500+ linhas"
  aparecem explicitamente como indicador de prática, não prova sozinha.
- Versões conferidas em set/2026: Spring Boot 4.1 sobre Spring Framework 7,
  Java 17+ mínimo — o que já estava no roadmap segue correto.

## Como o progresso funciona

- Cada checkbox é salvo em `localStorage` (`roadmap-progress`), mais
  `roadmap-diferenciais`, `roadmap-streak`, `roadmap-evidencias`,
  `roadmap-candidatura`, `roadmap-vagas`, `roadmap-practice` e as flags
  `roadmap-v2-migrated` / `roadmap-v3-migrated`.
- **Migração automática em cadeia V1→V2→V3:** na primeira carga, o progresso
  antigo (`mX-item-Y`, `mX-project`, seed do bootcamp) é mapeado para os IDs
  da V2 (`gX-…`, `f1-…`); em seguida a V3 reindexa os critérios que mudaram
  de posição por causa de Maven/Flyway/Documentação, sem herdar valor de
  item antigo pro slot novo. Itens do bootcamp entram marcados com o selo
  **"conheço → praticar"**; projetos V1 viram evidência `APLICADO` (o 🟢
  exige `COMPROVADO` + link). Nada é apagado.
- **Gates com 3 estados:** 🔴 Não pronto / 🟡 Pronto para avançar / 🟢 Gate
  concluído (thresholds: G0 80, G1 80+projeto, G2 90+projeto, G3 85+prod,
  G4 80, F1 70). Projeto só conta com nível `COMPROVADO` + link
  (commit/PR/API/deploy) — checkbox sozinho não é prova.
- **Dashboard separado:** Backend Core, G2 Estágio e Frontend têm barras
  próprias (Frontend nunca mascara o Backend). **"Você está aqui"** =
  primeira competência CORE pendente (competência > calendário).
- Um contador de sequência (🔥) soma dias seguidos com pelo menos um item
  marcado.
- Os itens do bootcamp Santander/DIO (concluído em 23/08/2026) entram
  marcados como concluídos + selo "praticar".
- Os rótulos de período (ex: "~ Set/2026") são só referência de ritmo.

## Colocar no ar

1. Em **Settings → Pages**, em "Build and deployment", confirme que
   **Source** está em **GitHub Actions**.
2. O workflow em `.github/workflows/Pages.yml` builda e publica sozinho a
   cada push na `main`. A URL fica em
   `https://gustavoh-silva.github.io/roadmap-backend-java-junior/`.

## GitHub Projects (organização de tarefas — opcional, manual por enquanto)

Board sugerido, criado em **Projects → New project → Board**:

- Colunas: `Backlog`, `Em andamento`, `Concluído`.
- Um card por critério ou por Gate, conforme a granularidade que fizer sentido.

Hoje o board **não está sincronizado automaticamente** com o `index.html` —
são duas fontes complementares: o board organiza *o que* fazer e em que
ordem, o dashboard marca *o que já foi feito* e mantém a sequência (streak).
Uma sincronização automática (uma Action lendo o Projects via API e
regravando o progresso) é um upgrade razoável, mas só vale a pena montar
depois de usar o sistema por um tempo e confirmar que o fluxo funciona no
dia a dia.

## Próximos ajustes de conteúdo sugeridos (não bloqueiam o uso)

- Conferir se os itens citados como "novidade 2026" (ex: Spring Boot 4 / Java
  25 como padrão de mercado) ainda refletem a realidade quando você chegar
  neles.
- Revisar a seção de diferenciais de mercado periodicamente — esse tipo de
  conteúdo envelhece rápido.
