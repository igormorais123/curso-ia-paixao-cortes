# Repository Guidelines

## Instrucoes Base (Obrigatorio)
- Escreva sempre em portugues (Brasil).
- Usuario iniciante: decida por conta propria e pergunte somente o essencial.
- Se precisar perguntar algo tecnico, explique o porquê e marque a opcao recomendada.
- Nao ha risco na pasta: pode editar arquivos sem avisos longos.

## Estrutura do Projeto
Repositorio de documentacao e materiais didaticos do curso de IA aplicada a advocacia.
- `.memoria/`: contexto ativo, aprendizados e historico.
- `AI/`: textos extraidos, Markdown convertido, diagramas e notas de skills.
- `Cartas perfis resistentes/`: baralho didatico.
- Raiz `*.docx` e `*.html`: documentos principais, propostas e exportacoes.

## Comandos de Desenvolvimento
Nao ha build ou testes automatizados. Trabalho principal e edicao de documentos.
- `*.docx`: editar no editor de texto/office.
- `AI/converted/**` e `AI/diagrams/**`: editar em Markdown.
- Exportacoes HTML ficam na raiz ao lado do documento fonte.

## Padroes de Escrita e Nomes
- Preferir nomes descritivos em portugues.
- Materiais principais em `.docx`; `.html` somente para versoes exportadas.
- Markdown com titulos claros e paragrafos curtos.

## Testes e Validacao
Sem framework de testes.
- Validar abrindo os documentos e conferindo formatacao.
- Revisar Markdown convertido para garantir titulos e secao completos.

## Commits e Pull Requests
Usar Conventional Commits em portugues: `docs:`, `feat:`, `fix:`, `chore:`.
Exemplos: `docs: Atualizacao IA no Direito (nov/2025 - fev/2026)`.
Se houver PR:
- Resumo das mudancas e motivo.
- Caminhos dos arquivos atualizados (ex.: `ATUALIZACAO_IA_DIREITO_NOV2025_FEV2026.html`).
- Print apenas se a mudanca visual for relevante.

## Seguranca e Privacidade
Evite incluir dados sensiveis que nao estejam aprovados para o curso.
Guarde rascunhos sigilosos fora do repo e traga apenas versoes finais.
