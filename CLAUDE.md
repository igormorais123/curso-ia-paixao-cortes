# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Projeto

Materiais didaticos do curso "O PROTOCOLO: Ativacao do Advogado Aumentado" para Paixao Cortes Advogados (Brasilia-DF). Curso hibrido (presencial 3 cidades + online) sobre IA generativa aplicada a advocacia.

- **Repo GitHub**: `igormorais123/curso-ia-paixao-cortes` (publico)
- **GitHub Pages**: `igormorais123.github.io/curso-ia-paixao-cortes/`
- **Branch unico**: master

## Arquitetura

Nao ha build, testes ou dependencias. Projeto e 100% documentacao e paginas HTML estaticas.

### Materiais principais (raiz)

| Arquivo | Funcao |
|---------|--------|
| `ROTEIRO_CURSO_4H_IA_ADVOCACIA_v4.md` | Roteiro principal v5.0 — 4 Fases + Protocolo Ativo (linguagem juridica) |
| `ROTEIRO_CURSO_4H_HIBRIDO_v4.md` | Roteiro legado v4.1 — substituido pelo v5.0 |
| `pagina_12_cartas_v3.html` | 12 cartas CLEAR (framework de prompts) — servido via GitHub Pages |
| `qrcodes_curso.html` | QR codes com links para recursos — servido via GitHub Pages |
| `index_curso.html` | Central de materiais do curso — servido via GitHub Pages |
| `CHECKLIST_COMPLETO_CURSO.md` | Checklist logistico completo |
| `EMAIL_PRE_CURSO.md` | Template de e-mail para participantes |
| `FOLHA_PROMPTS_QR_CODES.html` | Folha impressa com prompts e QR codes |
| `MANUAL_RAPIDO_IA_ESCRITORIO.html` | Manual rapido pos-curso |

### Diretorios de suporte

- `.memoria/`: contexto ativo, aprendizados e historico entre sessoes
- `AI/converted/`: .docx convertidos para .md (leitura por IA)
- `AI/diagrams/`: diagramas Mermaid dos modulos
- `Apresentações e Palestras 2025+/`: 23 PPTXs de apoio
- `Cartas perfis resistentes/`: baralho didatico legado

### Narrativa do Curso (v5.0)

4 Fases: ABERTURA → INSTRUCAO → BLINDAGEM → PROVA DE FOGO + PROTOCOLO ATIVO.
Igor ministra 3h: Qui 15h-17h (Fases 1-3) + Sex 10h-11h (Fase 4 + encerramento).
Jurimetria: outro instrutor, Sex 11h-12h.

### Antipadrao CRITICO: Linguagem
- NUNCA termos de TI para advogados (Boot, Scanner, Firewall = ERRADO)
- SEMPRE termos juridicos: Abertura, Instrucao, Blindagem, Prova de Fogo
- "thinking mode" → "raciocinio aprofundado" (nome do produto entre parenteses)
- "output" → "resultado" / "resposta da IA"
- "alucinacao" → "erro de citacao"

## Convencoes

- Escrever sempre em portugues (Brasil)
- Nomes de arquivos descritivos em portugues, MAIUSCULAS para documentos principais
- Materiais fonte em `.docx`, exportacoes web em `.html` na raiz
- Commits: Conventional Commits em portugues (`docs:`, `feat:`, `fix:`, `chore:`)
- HTMLs sao self-contained (CSS inline, sem framework externo)
- QR codes usam API externa `api.qrserver.com` — funciona mas depende de terceiro
- Palette do escritorio: vinho `#66142E` + dourado/tech-blue para ativacao

## Deploy

Push para `master` publica automaticamente no GitHub Pages. Propagacao leva 2-5 minutos.

```bash
git add <arquivos> && git commit -m "docs: descricao" && git push origin master
```

## URLs de Referencia Juridica (verificados)

Documentos juridicos exigem precisao absoluta — nomes errados destroem credibilidade.

- CNJ Resolucao 615/2025: `atos.cnj.jus.br/atos/detalhar/6001`
- OAB **Recomendacao** 001/2024 (NAO "Provimento"): `oab.org.br/noticia/62704/...`
- Podcast Direito 4.0: `open.spotify.com/show/5Q0rJimaM6ao4NWoyuMIve`

## Memoria do Projeto

- `.memoria/CONTEXTO_ATIVO.md`: estado atual e proximos passos
- `.memoria/APRENDIZADOS.md`: licoes aprendidas
- Repo Sandman (cross-projeto): `C:\Users\IgorPC\GitHub\Sandman-registro-de-memorias-de-IA-compatilhadas\`
