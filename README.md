# Roadmap Fullstack Java Júnior

Dashboard interativo de um roadmap de 17 meses, saindo do bootcamp Santander/DIO
rumo a uma vaga real de dev fullstack Java júnior.

## Por que isso existe

Antes esse roadmap vivia como um artifact dentro de uma conversa específica no
Claude — pra marcar o que já tinha sido estudado, era preciso voltar exatamente
àquele chat. Isso quebrava o hábito de acompanhamento. Agora é uma página
estática hospedada no GitHub Pages, com progresso salvo no navegador, e um
board no GitHub Projects como camada complementar de organização.

## Estrutura

```
.
├── index.html                     # o dashboard em si
└── .github/workflows/pages.yml    # publica o index.html no GitHub Pages a cada push
```

Não há build step nem framework: os dados do roadmap (os 17 meses e os
diferenciais de mercado) ficam embutidos no próprio `index.html`, dentro do
bloco `<script>`, nas constantes `roadmapData` e `diferenciaisData`. Editar o
conteúdo é abrir o array, mudar o texto, commitar.

## Como o progresso funciona

- Cada checkbox marcado é salvo em `localStorage`, no navegador — não depende
  mais do Claude.ai nem de nenhum chat específico.
- O indicador **"você está aqui"** não é mais calculado pela data do
  calendário. Ele é sempre o primeiro mês com algum item pendente. Se a rotina
  mudar (como já mudou uma vez), o roadmap não fica "desalinhado" — ele
  acompanha o progresso real, não o relógio.
- Um contador de sequência (🔥) soma dias seguidos com pelo menos um item
  marcado.
- Os itens que fazem parte do currículo oficial do bootcamp Santander/DIO já
  entram marcados como concluídos (ele foi finalizado dentro do prazo, em
  23/08/2026). Itens fora do currículo oficial do bootcamp continuam em
  aberto, mesmo nos meses 1 e 2.
- Os rótulos de período (ex: "~ Set/2026") são só uma referência de ritmo, não
  um prazo travado — o `~` na frente é proposital.

## Colocar no ar (primeira vez)

1. Crie um repositório novo no GitHub (público ou privado — em repositório
   privado, o GitHub Pages exige um plano pago).
2. Suba estes arquivos para a branch `main`.
3. Em **Settings → Pages**, em "Build and deployment", escolha
   **Source: GitHub Actions**.
4. Dê um push. O workflow em `.github/workflows/pages.yml` builda e publica
   sozinho. A URL fica em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## GitHub Projects (organização de tarefas — opcional, manual por enquanto)

Board sugerido, criado em **Projects → New project → Board**:

- Colunas: `Backlog`, `Em andamento`, `Concluído`.
- Um card por item de mês (ou um card por mês inteiro, se preferir menos
  granularidade).

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
