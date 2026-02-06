# Curso: IA na Advocacia — Roteiro v3.3
## Paixao Cortes Advogados | 6 horas (3h + 3h)

> **Filosofia**: Nao convencer, converter. Nao ensinar sobre IA, fazer experimentar IA.

> **Perfil do escritorio**: Contencioso de massa, defesa empresarial. Clientes de grande porte (bancos, companhias aereas). Alto volume, demandas repetitivas. Foco em escala e padronizacao.

> **v3.3**: Melhorias pos-simulacao de ouvintes — exercicio de escala, criacao de prompt proprio, opcao de casos, dados de impacto, bloco de implementacao, exercicio de comunicacao, buddy system pos-curso.

---

## Os 7 Mandamentos

1. **Espanto primeiro** — Demonstracao WOW antes de qualquer slide
2. **Verificacao muscular** — Participante descobre o erro, nao ouve sobre ele
3. **Identidade ampliada** — "Voce com superpoderes", nunca "nao sera substituido"
4. **Pratica e conteudo** — 67% mao na massa, 33% instrucao
5. **Corte radical** — Se pode ser curso separado, nao entra
6. **Presente, nao futuro** — Mostrar 2026, nao prometer 2030
7. **Compromisso > Certificado** — Sair com promessa, nao com PDF

---

## Metricas v3.3

| Metrica | v3.1 | v3.2 | v3.3 |
|---------|------|------|------|
| Instrucao | 100 min (33%) | 95 min (32%) | 85 min (28%) |
| Pratica | 200 min (67%) | 205 min (68%) | 215 min (72%) |
| Slides | 20 | 18 | 19 (+1 dados impacto) |
| Cartas | 12 (defesa empresarial) | 12 + Card Onde Clicar | 12 + Card + Manual Rapido |
| Casos ficticios | 3 (contencioso de massa) | 3 + caso backup | 3 com opcao de escolha |
| Materiais novos | — | 6 de apoio | 8 (+ Manual + Buddy System) |
| Exercicios | 7 | 7 (reformulados) | 9 (+criacao CLEAR, +comunicacao) |

---

# PRE-CURSO (48h antes)

## OBRIGATORIO: E-mail Pre-Curso

Enviar 48h antes com:
- [ ] Instrucoes para criar conta ChatGPT (link + tutorial 30s)
- [ ] Instrucoes para criar conta Claude (link + tutorial 30s)
- [ ] Instrucoes para criar conta Perplexity (link + tutorial 30s)
- [ ] Aviso: "Traga notebook ou celular carregado"
- [ ] Pedir ao escritorio: numero real de acoes pendentes no acervo

**Template completo**: Ver arquivo `EMAIL_PRE_CURSO.md`

---

# DIA 1 — SEXTA-FEIRA (3 horas)

## COLCHAO DE ENTRADA (5 min)
**Horario: 0:00 - 0:05**

Sala preparada. Musica ambiente baixa (opcional). Cartas CLEAR ja nos lugares. Card "Onde Clicar" em cada assento. Projetor ligado com tela de espera escura.

**Objetivo**: Absorver atrasos de ate 5 minutos sem comprometer a abertura.

**Regra**: A abertura silenciosa so comeca quando 80%+ da sala estiver presente E a porta for fechada.

---

## BLOCO 1: ESPANTO (45 min)
**Horario: 0:05 - 0:50**
**"O momento em que tudo muda"**

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-5 | Abertura silenciosa | Sala escura. Projetor mostrando Claude com Extended Thinking. Sem falar, digitar prompt de contestacao bancaria. Zero fala. **VIDEO BACKUP PRONTO caso IA falhe ao vivo.** |
| 5-8 | Primeira frase | "90 segundos. Uma contestacao estruturada. Voces tem [NUMERO REAL] acoes na fila. Facam a conta." |
| 8-10 | Contexto + Dados de impacto | "Isso e o presente." 1 slide com 3 dados: **Thomson Reuters 2025**: advogados com IA economizam 4h/semana. **Stanford HAI**: 17-33% de erro mesmo com RAG; busca web + raciocinio reduzem, mas nao eliminam. **47% dos escritorios "Mais Admirados" do Brasil** ja usam IA generativa. |
| 10-13 | **Micro-CLEAR** | 1 slide: "3 regras pra IA funcionar: 1) DIGA QUEM VOCE E, 2) DIGA O QUE QUER, 3) DE CONTEXTO ESPECIFICO. Nao cole 8 paginas — resuma em 5 linhas." |
| 13-15 | Prompt pronto na tela | Projetar o PROMPT PRONTO para copiar (ver abaixo). "Copiem isso. Mudem os dados para um caso de voces." |
| 15-35 | **EXERCICIO 1** | Cada um abre ChatGPT/Claude (usando Card Onde Clicar), personaliza o prompt pronto, recebe analise de teses e riscos. Instrutor circula priorizando quem tem dificuldade. |
| 35-43 | Compartilhamento com post-its | Cada um escreve em post-it: 1 SURPRESA e 1 DECEPCAO. Colar no quadro. Instrutor le os mais relevantes. |
| 43-45 | Ponte | "Viram que algumas respostas citaram jurisprudencia? Vamos descobrir agora se isso e real." |

### PROMPT PRONTO PARA EXERCICIO 1 (projetar na tela)

```
Sou advogado de escritorio que defende banco em acao trabalhista.
O ex-funcionario pede: [horas extras / dano moral / equiparacao].
Fatos: [descreva em 3-5 linhas o que o reclamante alega].

Quais sao as melhores teses de defesa para este caso?
Liste cada tese com fundamentacao legal.
NAO cite jurisprudencia especifica — foque nas teses e argumentos.
```

**NOTA SOBRE A DEMO**: O prompt da demo WOW deve instruir "NAO cite jurisprudencia especifica — foque em estrutura e teses de defesa". Isso evita que a IA invente numeros de processo na primeira impressao. Ter video pre-gravado como backup.

**Slides: 3** (prompt pronto, micro-CLEAR, pergunta de compartilhamento)

**Material na mesa de cada participante**:
- 1x Card "Onde Clicar" (impresso)
- Post-its (2 cores)
- Caneta

---

## BLOCO 2: PESQUISA INTELIGENTE COM IA (50 min)
**Horario: 0:50 - 1:40**
**"O momento em que voce aprende a pesquisar de verdade"**

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-3 | Setup | "Agora vamos fazer algo que muda tudo: pesquisar jurisprudencia com IA. Funciona, mas tem metodo." |
| 3-5 | Orientacao pratica | "Olhem o Card Onde Clicar. ChatGPT: ativem Deep Research. Perplexity: ja busca sozinho. Claude: pedir para buscar na web." |
| 5-20 | **EXERCICIO 2** | Pesquisar jurisprudencia real. Tema: "horas extras de gerente bancario — TST". DOIS caminhos simultaneos: metade da sala usa ChatGPT com Deep Research, outra metade usa Perplexity. **Aviso**: "Deep Research demora 2-5 min. E NORMAL. Enquanto espera, abra o Perplexity e faca a mesma pesquisa la." |
| 20-32 | **EXERCICIO 3** | Clicar em cada link retornado pela IA. Verificar quais existem. Anotar % de acerto. **Fazer em duplas para reduzir carga no Wi-Fi.** |
| 32-37 | Momento de clareza | "Quando a IA busca na internet e cita com link, funciona. Quando inventa de cabeca, falha. A diferenca e o metodo." |
| 37-42 | Framework + Frase pronta | **"Busca → Link → Thinking → Checagem"**. Projetar a FRASE DE AUTOCHECAGEM para copiar (ver abaixo). |
| 42-47 | Regulacao + Caso real | CNJ 615/2025, OAB Recomendacao 001/2024. Caso Samsung (2023): engenheiros colaram codigo proprietario no ChatGPT, empresa baniu ferramenta. Dados: 206 casos documentados de alucinacoes em tribunais. |
| 47-50 | 3 Perguntas Essenciais | "Posso usar sem declarar?" / "Quanto custa?" / "E se o cliente descobrir?" — respostas rapidas. |

### Protocolo de Pesquisa Juridica com IA (4 passos)

1. **BUSCAR NA INTERNET** — Sempre ativar busca web. ChatGPT: Deep Research. Claude: pedir para buscar. Perplexity: nativo.
2. **EXIGIR LINK** — Toda citacao DEVE vir com link direto para o tribunal. Sem link = nao existe.
3. **USAR THINKING MODE** — Sempre ativar raciocinio estendido. Reduz alucinacoes drasticamente.
4. **PEDIR AUTOCHECAGEM** — Usar a frase pronta (ver abaixo).

### FRASE DE AUTOCHECAGEM (projetar na tela e incluir nas cartas)

```
Agora revise todas as citacoes acima. Confirme que cada link funciona
e cada numero de processo esta correto. Se tiver duvida sobre algum,
sinalize com [VERIFICAR].
```

### 3 PERGUNTAS ESSENCIAIS (respostas rapidas)

**"Posso usar IA sem declarar ao juiz?"**
> CNJ 615/2025: obrigatorio quando o juizo exigir. Na pratica: use, revise, seja transparente quando perguntado.

**"Quanto custa?"**
> ChatGPT Plus: US$ 20/mes. Claude Pro: US$ 20/mes. Perplexity Pro: US$ 20/mes. Invista R$ 100/mes, economize 20h/mes.

**"E se o cliente descobrir que usei IA?"**
> Voce usa Google, calculadora, modelos. IA e mais uma ferramenta. O que importa e a QUALIDADE do trabalho e a VERIFICACAO humana.

**Slides: 3** (protocolo de pesquisa, regulacao/caso real, 3 perguntas)

---

## INTERVALO (15 min)
**Horario: 1:40 - 1:55**

**TAREFA**: "Ate amanha, usem IA em algo real do escritorio. Qualquer coisa. Tragam a experiencia."

**Intervalo de 15 minutos** (nao 10). Necessario para fluxo real de banheiro + cafe + retorno.

---

## BLOCO 3: FERRAMENTAS + CLEAR COMPLETO (50 min)
**Horario: 1:55 - 2:45**
**"O momento em que voce monta seu arsenal"**

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-8 | Mapa essencial | **2 essenciais + 1 bonus** (ver tabela abaixo). Mencao rapida de NotebookLM e Gemini em 1 frase. |
| 8-12 | Framework CLEAR completo | Demonstrar CADA letra com exemplo real de contestacao bancaria. Projetar antes/depois: prompt vago vs prompt CLEAR. |
| 12-32 | **EXERCICIO 4 (FLUXO COMBINADO)** | Passo 1 (8 min): ChatGPT com Deep Research para pesquisar jurisprudencia. Passo 2 (12 min): Colar resultado no Claude com prompt CLEAR e pedir contestacao. **Ferramentas em CADEIA.** |
| 32-37 | **EXERCICIO 4B (CRIE SEU CLEAR)** | "Agora VOCE escreva um prompt CLEAR para a tarefa que voce MAIS faz no escritorio." 5 minutos. Depois: 2-3 voluntarios leem em voz alta. Instrutor ajusta ao vivo. **Consolida o framework pela pratica.** |
| 37-42 | As 12 Cartas — preview | Mostrar 2 cartas como exemplo de CLEAR aplicado. **NAO entregar o baralho todo agora.** "Amanha voces recebem o baralho completo." |
| 42-45 | Consolidacao | "Protocolo de Pesquisa, CLEAR, fluxo combinado. Amanha: caso completo." |

### Mapa de Ferramentas Essenciais (simplificado)

| Ferramenta | Forca | Usar para |
|------------|-------|-----------|
| **ChatGPT** (ESSENCIAL) | Deep Research com fontes, versatilidade | Pesquisa jurisprudencial com links, rascunhos em massa, brainstorm de teses |
| **Claude** (ESSENCIAL) | Analise profunda, Extended Thinking, textos longos | Pareceres, contestacoes complexas, analise de contratos, revisao de pecas |
| **Perplexity** (BONUS) | Pesquisa com fontes nativas, links automaticos | Verificacao rapida, jurisprudencia com citacao, atualizacao legislativa |

**Mencao em 1 frase**: "NotebookLM serve para estudar processos volumosos. Gemini para transcrever audiencias. Explorem depois — os links estao na folha de recursos."

### EXERCICIO 4 REFORMULADO: Fluxo Combinado (23 min)

**Passo 1 (8 min)**: Abrir ChatGPT com Deep Research. Pesquisar: "Jurisprudencia TST sobre [tema do caso de cada um] — decisoes favoraveis a defesa, com link para tribunal."

**Passo 2 (15 min)**: Copiar o resultado da pesquisa. Abrir Claude. Colar junto com prompt CLEAR:
```
CONTEXTO: Sou advogado de escritorio que defende grande banco em
contencioso trabalhista de massa. Pesquisei a jurisprudencia abaixo.
[COLAR RESULTADO DA PESQUISA]

LIMITE: Use APENAS a jurisprudencia que eu forneci acima.
Nao invente citacoes adicionais. Estrutura replicavel.

EXEMPLO: Estrutura: 1) Qualificacao, 2) Sintese da inicial,
3) Preliminares, 4) Impugnacao ponto a ponto, 5) Merito com
jurisprudencia pesquisada, 6) Pedidos.

AUDIENCIA: Juiz do trabalho de vara de Brasilia.

ROLE: Advogado empresarial experiente em contencioso bancario de massa.

FATOS DO CASO: [inserir pedidos da inicial e fatos a impugnar]
```

**Por que isso e melhor que o antigo Exercicio 4**: Em vez de fazer a mesma coisa em 2 ferramentas e comparar (repetitivo), o advogado aprende a usar ferramentas em CADEIA — pesquisa numa, produz na outra. Isso e o uso REAL no dia a dia.

**Slides: 4** (mapa essencial, CLEAR completo com antes/depois, fluxo combinado, preview cartas)

---

## EXERCICIO RELAMPAGO: COMUNICACAO (5 min)
**Horario: 2:45 - 2:50**

**O que fazer**: "O banco ligou. Quer saber AGORA o resultado da audiencia de hoje. Usem IA para redigir e-mail executivo em 3 paragrafos. Tempo: 5 minutos. Go."

**Prompt sugerido na tela**:
```
Sou advogado de escritorio que defende banco em acao trabalhista.
Resultado da audiencia de hoje: [procedente em parte / acordo / adiada].
Redija e-mail executivo para o diretor juridico do banco.
Maximo 3 paragrafos. Tom formal-corporativo. Direto ao ponto.
Incluir: resultado, impacto financeiro, proximo passo.
```

**Por que funciona**: E rapido, pratico e imediatamente aplicavel. Todo advogado precisa comunicar resultado ao cliente. Encerra o Dia 1 com "gostinho de quero mais".

---

## FAQ + BUFFER DIA 1 (10 min)
**Horario: 2:50 - 3:00**

Perguntas restantes + encerramento do dia.

---

# DIA 2 — SABADO (3 horas)

## BLOCO 4: AQUECIMENTO + DOMINIO (75 min)
**Horario: 0:00 - 1:15**
**"O momento em que voce assume o controle"**

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-5 | Aquecimento rapido (post-its) | Cada um escreve: "Tentei: ___" e "Resultado: ___". Colar no quadro. Instrutor le os 3-4 mais relevantes. |
| 5-10 | Entrega do material | Entregar baralho completo das 12 cartas + folha de recursos com QR codes. "Isso e o arsenal de voces pra levar." |
| 10-12 | Formacao de duplas | Instrutor forma duplas ESTRATEGICAMENTE: 1 avancado + 1 iniciante. Nao deixar formacao livre. |
| 12-15 | Escolha do caso | Cada dupla ESCOLHE o caso: **Caso 1** (bancario/contestacao), **Caso 2** (aereo/equiparacao) ou **Caso 1R** (bancario/recurso — versao recursal do Caso 1, banco foi condenado). Imprimir os 3. |
| 15-62 | **EXERCICIO 5** | Fluxo completo com caso escolhido. Duplas. **47 minutos**. |
| 62-70 | **EXERCICIO 5B: ESCALA** | "Voce fez 1 contestacao. Como replica para 50? Identifique: o que e FIXO (estrutura, teses, jurisprudencia) e o que MUDA (fatos, pedidos, valores). Crie o TEMPLATE REPLICAVEL." 8 minutos. |
| 70-75 | Debrief | "Onde a IA ajudou mais? Onde ela atrapalhou?" Post-its. |

### EXERCICIO 5: Fluxo Completo de Defesa (47 min)

**Opcao de caso** (dupla escolhe o mais relevante):
- **Caso 1**: Horas extras de gerente bancario → Contestacao
- **Caso 2**: Equiparacao salarial de comissarios → Defesa da aerea
- **Caso 1R** (NOVO): Mesmo caso 1, mas banco FOI CONDENADO → Recurso Ordinario

**Etapas:**
1. **Pesquisa** (17 min): Aplicar Protocolo de Pesquisa completo. Deep Research ou Perplexity. **"Deep Research demora 3-5 min. Usem Perplexity em paralelo."**
2. **Minuta** (18 min): CLEAR completo + fluxo combinado. Pesquisa do passo 1 alimenta o Claude.
3. **Verificacao** (12 min): Checar links, autochecagem com frase pronta, revisar estrutura.

**Instrutor circula como consultor, priorizando duplas com dificuldade. Nao palestra.**

### EXERCICIO 5B: PENSANDO EM ESCALA (8 min)

**Pergunta**: "Voce acabou de fazer 1 contestacao em 47 minutos. O banco tem 450 iguais. Como escala?"

**Tarefa**: Cada dupla identifica em sua contestacao:
- O que e **FIXO** (estrutura, teses padrao, jurisprudencia consolidada, preliminares)
- O que **MUDA** (nome do reclamante, pedidos especificos, fatos, valores)
- Reescrever o prompt CLEAR substituindo dados especificos por **[VARIAVEIS]**

**Resultado**: Template replicavel. Advogado so preenche as variaveis e roda para cada caso.

**Slides: 3** (fluxo visual, opcoes de caso, template de escala)

---

## INTERVALO DIA 2 (15 min)
**Horario: 1:15 - 1:30**

---

## BLOCO 5: HORIZONTES (10 min)
**Horario: 1:30 - 1:40**
**"O que existe alem"**

> **Movido para ANTES de Seguranca** — Seguranca e mais pratico/interativo e mantem energia melhor no horario de cansaco.

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-7 | Mencoes rapidas | Jurimetria para contencioso de massa, padroes decisorios por vara/juiz, Visual Law, automacao de fluxos, IA agentica — "cursos inteiros, nao cabe aqui" |
| 7-10 | Recursos | "Na folha de recursos que voces receberam tem QR codes para AB2L, podcast, curso FGV. Escaneiem depois." NAO projetar QR codes na tela. |

**Slides: 1** (horizontes em topicos)

### Recursos Concretos (na folha impressa, nao no slide)

- **Ecossistema**: [AB2L](https://ab2l.org.br) — Associacao Brasileira de Lawtechs e Legaltechs
- **Podcast**: [Direito Digital](https://open.spotify.com/show/7mWbaobExP8NXp1wRGSsD3) — Episodios sobre direito e tecnologia
- **Curso gratuito**: [Regulacao da IA - FGV](https://educacao-executiva.fgv.br/cursos/online/curta-media-duracao-online/regulacao-da-inteligencia-artificial) — Online, gratuito

---

## BLOCO 6: SEGURANCA REAL (35 min)
**Horario: 1:40 - 2:15**
**"O momento em que voce protege a si e aos clientes"**

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-8 | Casos reais documentados | 1) Caso Samsung 2023: engenheiros colaram codigo proprietario, empresa baniu ChatGPT. 2) Caso Mata vs Avianca 2023: advogado citou 6 casos inventados, sancionado. 3) Dados: 206 alucinacoes documentadas em tribunais, 66 sancoes a advogados. |
| 8-18 | 5 Regras COM EXEMPLOS PRATICOS | Protocolo inegociavel — cada regra com exemplo concreto (ver abaixo) |
| 18-35 | **EXERCICIO 6** | Anonimizacao real: pegar caso do escritorio, anonimizar dados sensiveis, enviar para IA. **Caso backup impresso disponivel para quem nao tiver caso no celular.** |

### Protocolo de Seguranca (5 Regras com Exemplos Concretos)

**1. Anonimizar SEMPRE**
> Regra: Nomes ficticios, dados bancarios mascarados, valores aproximados.
> Exemplo pratico:
> - "Banco do Brasil S.A." → "Banco XYZ"
> - "Joao Silva, CPF 012.345.678-90" → "Empregado A"
> - "Processo 0001234-56.2025.5.10.0001" → "Processo XXXXX"
> - CNPJ, numero de agencia, valores exatos → remover ou aproximar

**2. Verificar TODA citacao**
> Regra: Nenhuma jurisprudencia sem link verificavel.
> Exemplo pratico: Clicar no link. Nao apenas ler — CLICAR. Se o link nao abrir a decisao citada, DESCARTAR.

**3. Revisar TUDO**
> Regra: Output de IA e rascunho, nao produto final.
> Exemplo pratico: Em contencioso de massa, revisar amostra de 5 contestacoes antes de replicar para 200. Um erro multiplicado por 200 = desastre.

**4. Registrar uso**
> Regra: Transparencia com tribunal quando exigido.
> Modelo de nota de rodape:
> ```
> Peca elaborada com auxilio de ferramenta de IA generativa,
> com revisao integral pelo advogado subscritor, nos termos
> da Resolucao CNJ 615/2025.
> ```

**5. Humano decide**
> Regra: IA sugere, advogado assina.
> Exemplo pratico: IA pode sugerir acordo de R$ 25.000. Mas so o advogado sabe que aquele juiz condena em R$ 60.000 nessa vara. Contexto humano > output de IA.

### CASO BACKUP PARA ANONIMIZACAO

Para participantes sem caso no celular, usar versao com dados completos do Caso 3 (Assedio Moral) para exercicio de anonimizacao:

```
DADOS ORIGINAIS (NAO enviar para IA):
- Reclamante: Ana Cristina Lopes, CPF 987.654.321-00
- Reclamada: Banco Nacional S.A., CNPJ 00.000.000/0001-91
- Processo: 0004567-89.2025.5.10.0012
- Gerente acusado: Paulo Mendes
- Valor pedido: R$ 100.000,00

VERSAO ANONIMIZADA (enviar para IA):
- Reclamante: Empregada A, analista de credito
- Reclamada: Instituicao financeira de grande porte
- Gerente regional: Gestor B
- Valor pedido: aproximadamente R$ 100 mil
```

**Slides: 3** (casos documentados, protocolo com exemplos, checklist)

---

## BLOCO 7: COMPROMISSO + IMPLEMENTACAO (30 min)
**Horario: 2:15 - 2:45**
**"O momento em que voce decide quem sera — e o escritorio decide como muda"**

| Min | Atividade | Detalhe |
|-----|-----------|---------|
| 0-5 | Reflexao | Olhos fechados. "Pensem naquelas [NUMERO REAL] contestacoes na fila. Onde a IA entra na segunda-feira?" |
| 5-12 | **EXERCICIO 7: Compromisso individual** | Escrever em papel: "Na segunda-feira, vou usar IA para _____." ESPECIFICO. |
| 12-15 | Compartilhamento | 3-4 voluntarios. Celebrar a coragem. |
| 15-25 | **EXERCICIO 8: Plano de Implementacao (coletivo)** | Exercicio do escritorio todo junto. Responder 3 perguntas no quadro (ver abaixo). |
| 25-28 | Buddy system | Parear cada participante inseguro com um avancado. "Nas proximas 2 semanas, o buddy ajuda nas primeiras tentativas." |
| 28-30 | Encerramento | "Voces descobriram uma versao mais poderosa de voces." Certificado. Foto. |

### EXERCICIO 8: Plano de Implementacao do Escritorio (10 min)

**Dinamica coletiva** — todo o escritorio responde junto, no quadro:

1. **"Quem e o CAMPEAO DE IA do escritorio?"**
   > A pessoa que vai liderar a adocao, tirar duvidas, manter o padrao. Geralmente o mais entusiasmado (ex: Thiago, Camila).

2. **"Qual o PRIMEIRO PROCESSO a automatizar com IA?"**
   > O mais repetitivo, o que consome mais horas, o que tem mais volume. Geralmente: contestacao padrao de horas extras.

3. **"Como MEDIR resultado em 30 dias?"**
   > Sugestao: tempo medio de producao de contestacao ANTES vs DEPOIS. Numero de pecas produzidas por semana. Qualidade (taxa de revisao necessaria).

**Resultado**: Escritorio sai com PLANO, nao apenas boas intencoes individuais.

### BUDDY SYSTEM POS-CURSO

Formar duplas de acompanhamento:
- Participante **inseguro/cauteloso** + participante **avancado/entusiasta**
- Objetivo: nas primeiras 2 semanas, o buddy ajuda nas primeiras tentativas reais
- Canal: WhatsApp direto entre os dois
- Sem obrigacao formal — so apoio entre colegas

**Slides: 2** (compromisso individual, plano de implementacao)

---

## BUFFER DIA 2 (15 min)
**Horario: 2:45 - 3:00**

---

# AS 12 CARTAS (Mantidas da v3.1)

> As 12 cartas CLEAR permanecem identicas a v3.1 (defesa empresarial).
> Unica mudanca: adicionar a FRASE DE AUTOCHECAGEM em cada carta que envolva pesquisa jurisprudencial (Cartas 1, 2, 3, 7, 8).

## Categoria: ELABORACAO DE PECAS (4 cartas)

### Carta 1: Contestacao Trabalhista em Massa
```
CONTEXTO: Sou advogado de escritorio que defende grande banco em
contencioso trabalhista de massa. Preciso de contestacao para
reclamacao trabalhista que pede [horas extras / equiparacao / dano moral].
Volume: temos 300+ acoes similares.

LIMITE: Nao cite jurisprudencia especifica sem buscar na internet
com link. Foque em teses de defesa consolidadas. Estrutura replicavel.

EXEMPLO: Estrutura desejada: 1) Qualificacao da reclamada,
2) Sintese da inicial, 3) Preliminares, 4) Impugnacao ponto a ponto,
5) Merito (teses de defesa), 6) Pedidos, 7) Documentos.

AUDIENCIA: Juiz do trabalho de vara de Brasilia.

ROLE: Advogado empresarial experiente em contencioso bancario de massa,
linguagem tecnica, objetiva, sem excesso.

FATOS DO CASO: [inserir pedidos da inicial e fatos a impugnar]

AUTOCHECAGEM: Ao final, revise todas as citacoes. Confirme links
e numeros de processo. Sinalize duvidas com [VERIFICAR].
```

### Carta 2: Recurso Ordinario (Defesa)
```
CONTEXTO: Sou advogado da reclamada (banco/empresa de grande porte).
Fomos condenados em primeira instancia. Preciso recorrer dos pedidos
de [horas extras / equiparacao / dano moral].

LIMITE: Nao cite acordaos sem buscar na internet com link verificavel.
Para jurisprudencia: use Perplexity ou ChatGPT com Deep Research,
sempre com link para tribunal. Foque nos fundamentos para reforma.

EXEMPLO: Estrutura: 1) Tempestividade e preparo, 2) Sintese da
sentenca, 3) Razoes de reforma por pedido condenatorio,
4) Pedido de provimento total ou parcial.

AUDIENCIA: Desembargadores do TRT.

ROLE: Advogado recursal de contencioso empresarial, tecnico e preciso.

PONTOS A ATACAR: [inserir fundamentos da sentenca condenatoria]

AUTOCHECAGEM: Ao final, revise todas as citacoes. Confirme links
e numeros de processo. Sinalize duvidas com [VERIFICAR].
```

### Carta 3: Defesa em Acao Civil Publica
```
CONTEXTO: Empresa cliente (banco/aerea) e re em acao civil publica
do MPT sobre [pratica trabalhista]. Risco de condenacao em obrigacao
de fazer + dano moral coletivo.

LIMITE: Nao cite jurisprudencia sem busca na internet com link.
Foque em demonstrar regularidade das praticas empresariais.

EXEMPLO: Estrutura: 1) Preliminares (legitimidade, interesse),
2) Impugnacao dos fatos, 3) Regularidade demonstrada com documentos,
4) Ausencia de dano coletivo, 5) Pedidos.

AUDIENCIA: Juiz da vara do trabalho.

ROLE: Advogado empresarial senior em defesa de litigios coletivos.

FATOS: [inserir resumo da ACP e praticas questionadas]
```

### Carta 4: Acordo em Massa — Proposta Padronizada
```
CONTEXTO: Escritorio defende banco/empresa com 500+ acoes trabalhistas
similares. Diretoria autorizou faixa de acordo. Preciso de proposta
padronizada por faixa de pedido.

LIMITE: Valores genericos (faixas). Linguagem que minimize admissao
de responsabilidade. Clausula de quitacao ampla.

EXEMPLO: Formato: 1) Contextualizacao (sem admissao de culpa),
2) Proposta por faixa de valor, 3) Forma de pagamento,
4) Clausula de quitacao, 5) Prazo de aceite.

AUDIENCIA: Juiz do trabalho e advogado do reclamante.

ROLE: Advogado negociador de contencioso de massa.

PARAMETROS: [inserir faixas de valor autorizadas e perfil das acoes]
```

## Categoria: ANALISE E REVISAO (4 cartas)

### Carta 5: Analise de Risco para Empresa
```
CONTEXTO: Cliente corporativo (banco/aerea) quer avaliar risco de
[pratica trabalhista ou politica interna]. Preciso mapear exposicao.

LIMITE: Nao afirme certeza sobre decisoes judiciais. Apresente
cenarios com probabilidade. Considere volume de acoes similares.

EXEMPLO: Formato: 1) Pratica analisada, 2) Riscos por cenario
(condenacao total/parcial/improcedencia) com probabilidade,
3) Exposicao financeira estimada (unitaria e total do acervo),
4) Recomendacoes, 5) Alternativas de mitigacao.

AUDIENCIA: Diretor juridico e RH da empresa, sem formacao juridica.

ROLE: Consultor trabalhista preventivo de grandes empresas.

SITUACAO: [inserir pratica e numero estimado de empregados afetados]
```

### Carta 6: Revisao de Peca de Defesa
```
CONTEXTO: Advogado junior do escritorio redigiu esta [contestacao/recurso]
para caso de contencioso bancario. Preciso revisar antes de protocolar.

LIMITE: Nao reescreva tudo. Aponte problemas especificos com
sugestoes de correcao. Foco em: teses fracas, fundamentos faltantes,
oportunidades de defesa nao exploradas.

EXEMPLO: Formato: 1) Pontos fortes, 2) Teses de defesa ausentes,
3) Problemas de fundamentacao, 4) Oportunidades perdidas,
5) Sugestoes linha a linha.

AUDIENCIA: Advogado junior, para aprendizado e melhoria.

ROLE: Revisor senior de contencioso empresarial, exigente mas
construtivo.

PECA: [colar peca de defesa]
```

### Carta 7: Parecer para Cliente Corporativo
```
CONTEXTO: Banco/empresa cliente pergunta se pode [pratica trabalhista:
alterar jornada, terceirizar setor, implementar banco de horas, etc.].
Preciso de parecer com analise de risco.

LIMITE: Seja honesto sobre incertezas. Nao prometa resultados.
Considere jurisprudencia do TST e TRT da regiao.
Para citar jurisprudencia, buscar na internet com link.

EXEMPLO: Formato: 1) Consulta, 2) Fundamentacao legal,
3) Jurisprudencia relevante (com links), 4) Analise do caso,
5) Riscos quantificados, 6) Conclusao e recomendacao.

AUDIENCIA: Diretor juridico de grande empresa.

ROLE: Parecerista trabalhista empresarial, claro e objetivo.

CONSULTA: [inserir pergunta do cliente corporativo]

AUTOCHECAGEM: Ao final, revise todas as citacoes. Confirme links
e numeros de processo. Sinalize duvidas com [VERIFICAR].
```

### Carta 8: Estrategia de Contencioso de Massa
```
CONTEXTO: Empresa cliente enfrenta onda de [tipo de acao] — 50 novas
acoes por mes com pedidos similares. Preciso definir estrategia global.

LIMITE: Nao sugira taticas antieticas. Considere custo-beneficio em
escala. Avaliar: defender tudo vs acordar por faixa.

EXEMPLO: Formato: 1) Diagnostico do acervo, 2) Perfil das acoes
(pedidos recorrentes, valores medios), 3) Teses de defesa padronizadas,
4) Politica de acordo por faixa, 5) KPIs de acompanhamento.

AUDIENCIA: Socios do escritorio e diretor juridico do cliente.

ROLE: Advogado estrategista de contencioso de massa.

DADOS: [inserir perfil das acoes e resultados recentes]
```

## Categoria: COMUNICACAO (2 cartas)

### Carta 9: Relatorio Mensal para Cliente Corporativo
```
CONTEXTO: Preciso enviar relatorio mensal do contencioso ao banco/empresa
cliente. [X] acoes ativas, [Y] encerradas no mes, [Z] novas.

LIMITE: Maximo 2 paginas. Dados consolidados. Linguagem executiva.
Foque em numeros, tendencias e recomendacoes.

EXEMPLO: Formato: 1) Dashboard (acoes ativas/encerradas/novas),
2) Resultados do mes (ganhos/perdas/acordos), 3) Exposicao financeira,
4) Tendencias observadas, 5) Acoes recomendadas, 6) Proximos passos.

AUDIENCIA: Diretor juridico de banco, sem tempo, quer numeros.

ROLE: Advogado gestor de contencioso que reporta com clareza.

DADOS: [inserir numeros do mes]
```

### Carta 10: E-mail Profissional para Cliente Corporativo
```
CONTEXTO: Preciso enviar e-mail para [destinatario no banco/empresa]
sobre [resultado de audiencia / decisao / necessidade de documentos].

LIMITE: Tom formal-corporativo. Maximo 3 paragrafos. Direto ao ponto.
Sem juridiques desnecessario.

EXEMPLO: Estrutura: saudacao, resultado/informacao principal em 1 frase,
detalhamento breve, acao necessaria do cliente, despedida.

AUDIENCIA: [gestor juridico / RH / diretor] de grande empresa.

ROLE: Advogado que se comunica com clareza e eficiencia corporativa.

PONTOS A INCLUIR: [listar]
```

## Categoria: PRODUTIVIDADE (2 cartas)

### Carta 11: Resumo de Processo em Lote
```
CONTEXTO: Assumi lote de [X] processos trabalhistas contra banco/empresa.
Preciso entender rapidamente cada um para definir estrategia.

LIMITE: Foque em: partes, pedidos principais, fase processual,
risco (alto/medio/baixo), acao recomendada.

EXEMPLO: Formato tabular: 1) N processo, 2) Reclamante e pedidos,
3) Fase, 4) Risco, 5) Valor estimado, 6) Proximo prazo,
7) Recomendacao (defender/acordar/recorrer).

AUDIENCIA: Eu mesmo e equipe, para gestao do acervo.

ROLE: Assistente juridico de contencioso de massa, eficiente.

DOCUMENTOS: [colar iniciais ou resumo de cada processo]
```

### Carta 12: Checklist de Audiencia de Defesa
```
CONTEXTO: Tenho audiencia [instrucao/julgamento] em processo trabalhista
contra banco/empresa. Reclamante pede [pedidos].

LIMITE: Seja pratico. Foque no que posso esquecer. Considere que
e contencioso de massa — padronizar para replicar.

EXEMPLO: Formato: 1) Documentos para levar (guias GFIP, controle
de jornada, holerites), 2) Perguntas para testemunha da empresa,
3) Contraditas possiveis, 4) Pontos para destacar em defesa,
5) Objecoes provaveis do reclamante, 6) Parametros de acordo.

AUDIENCIA: Eu mesmo, como lembrete padronizado.

ROLE: Advogado experiente em audiencias trabalhistas de defesa.

DETALHES DO CASO: [inserir]
```

---

# CASOS FICTICIOS PARA EXERCICIOS (Mantidos da v3.1)

## CASO 1: Horas Extras de Gerente Bancario (Exercicio 5)

**Partes:**
- Reclamante: Roberto Almeida Costa, 38 anos, ex-gerente de agencia
- Reclamada: Banco Nacional S.A. (grande banco de varejo, 800+ agencias)

**Cenario do escritorio:** O Banco Nacional enfrenta 450+ acoes similares de ex-gerentes pedindo horas extras. Este e um caso-tipo que definira a estrategia para todo o acervo.

**Fatos alegados pelo reclamante:**
Roberto trabalhou como gerente de agencia de 10/03/2020 a 15/12/2025. Salario: R$ 12.500,00 + gratificacao de funcao de R$ 4.200,00. Alega que, apesar do cargo de confianca, nao tinha autonomia real: seguia metas impostas pela regional, nao podia contratar nem demitir, horario era controlado por sistema biometrico, trabalhava das 7h30 as 20h incluindo sabados.

**Documentos do reclamante:**
- Prints de e-mails da regional as 6h e 21h cobrando metas
- Relatorio de ponto biometrico mostrando entradas/saidas
- WhatsApp com superior cobrando abertura da agencia aos sabados
- Holerites mostrando gratificacao de funcao

**Teses de defesa a desenvolver:**
1. Cargo de confianca bancario (art. 224, §2, CLT) — gratificacao > 1/3 do salario
2. Autonomia real: gerente tinha procuracao, assinava contratos, gerenciava equipe de 12 pessoas
3. Ponto biometrico era exigencia de seguranca (resolucao BACEN), nao controle de jornada
4. E-mails da regional nao significam trabalho efetivo fora do horario
5. Prescricao quinquenal

**Questoes para analise com IA:**
1. A gratificacao de R$ 4.200 (33,6% do salario) configura o requisito legal?
2. Como impugnar os registros de ponto biometrico como prova de jornada?
3. Qual a jurisprudencia atual do TST sobre gerente de agencia bancaria? (USAR PROTOCOLO DE PESQUISA)
4. Qual o risco financeiro por acao e para o acervo total (450 acoes)?
5. Vale defender ou propor acordo? Qual faixa?

---

## CASO 1R: Recurso Ordinario — Banco Condenado (Exercicio 5 - opcao recursal)

**Contexto**: MESMO caso do Caso 1, mas o juiz CONDENOU o banco. Agora voce precisa recorrer.

**Sentenca (resumo)**:
O juiz da 12a Vara do Trabalho de Brasilia julgou PROCEDENTE EM PARTE a reclamacao, condenando o Banco Nacional a pagar:
- Horas extras (7a e 8a hora) + reflexos: R$ 185.000,00 estimados
- Adicional noturno sobre horas apos 22h: R$ 12.000,00
- FGTS + multa de 40% sobre diferenças
- Indeferiu dano moral e sabados (considerou jornada ate 18h30 nos sabados nao comprovada)

**Fundamentos da sentenca para atacar**:
1. Juiz entendeu que ponto biometrico COMPROVA jornada (gerente registrava entrada e saida)
2. Juiz considerou que gratificacao de R$ 4.200 (33,6%) e insuficiente pois "a norma exige 1/3 e o valor e marginalmente superior"
3. Juiz desconsiderou procuracao e gestao de equipe como prova de autonomia
4. Juiz usou Sumula 102 do TST de forma que voce considera equivocada

**Tarefa no Exercicio 5**: Pesquisar jurisprudencia do TST favoravel a reforma + gerar razoes de recurso ordinario com CLEAR.

---

## CASO 2: Equiparacao Salarial de Comissarios (Exercicio 5 - opcao aerea)

**Partes:**
- Reclamante: Patricia Mendes Rocha, 29 anos, comissaria de bordo
- Reclamada: Voo Brasil S.A. (companhia aerea, 3.000+ tripulantes)

**Cenario do escritorio:** A Voo Brasil enfrenta 180 acoes de comissarios pedindo equiparacao salarial com colegas de outra base. Vitoria dos reclamantes geraria efeito cascata de R$ 45 milhoes.

**Fatos alegados pela reclamante:**
Patricia trabalha na base de Brasilia desde 2021. Salario: R$ 4.800,00. Alega que comissarios da base de Sao Paulo, contratados na mesma epoca e com mesma funcao, recebem R$ 7.200,00. Diz que faz as mesmas rotas, mesma carga horaria e mesmas atribuicoes. Aponta como paradigma: Lucas Ferreira da Silva, base SP, contratado em 2020.

**Documentos da reclamante:**
- Holerites proprios e do paradigma (obtidos em grupo de WhatsApp)
- Descricao de cargo identica (mesmo codigo no RH)
- Escalas de voo mostrando mesmas rotas

**Teses de defesa a desenvolver:**
1. Bases diferentes = estabelecimentos diferentes (art. 461, CLT — reforma trabalhista)
2. Plano de cargos e salarios registrado (diferenciacao por base e legitima)
3. Paradigma com tempo de servico superior (diferenca > 4 anos na funcao)
4. Custo de vida diferente entre bases justifica diferenca
5. Impugnar holerites obtidos irregularmente

---

## CASO 3: Assedio Moral — Defesa do Banco (Exercicio alternativo + backup anonimizacao)

**Partes:**
- Reclamante: Ana Cristina Lopes, 41 anos, ex-analista de credito
- Reclamada: Banco Nacional S.A.

**Cenario do escritorio:** Acoes de assedio moral representam 25% do acervo do banco (600+ acoes). Condenacoes medias de R$ 15.000-50.000.

**Fatos alegados pela reclamante:**
Ana trabalhou de 2019 a 2025 como analista de credito. Alega que o gerente regional Paulo Mendes a assediava moralmente: cobrancas excessivas por e-mail com copia para toda a equipe, exposicao de metas individuais em ranking publico, ameacas de demissao em reuniao, isolamento apos retorno de licenca maternidade (2023). Pede: dano moral de R$ 100.000 + rescisao indireta + verbas rescisorias.

**Teses de defesa a desenvolver:**
1. Cobranca de metas e exercicio regular do poder diretivo
2. Rankings de produtividade sao pratica de mercado
3. E-mails em copia sao comunicacao institucional normal
4. Ausencia de nexo causal entre trabalho e quadro psiquiatrico
5. Empresa tem canal de denuncia e compliance — reclamante nunca registrou queixa

---

# CHECKLIST DO INSTRUTOR (v3.3)

## 1 Semana Antes
- [ ] Confirmar numero real de acoes pendentes do escritorio (para usar na abertura)
- [ ] Enviar e-mail pre-curso (template em EMAIL_PRE_CURSO.md)
- [ ] Confirmar criacoes de conta (responder e-mail = confirmacao)
- [ ] Testar Wi-Fi do local COM CARGA (12 dispositivos simultaneos)
- [ ] Se Wi-Fi fraco: providenciar roteador 4G extra
- [ ] Discutir formato (sexta+sabado vs 2 sabados) com o escritorio

## 1 Dia Antes
- [ ] Gravar video backup da demo WOW (contestacao bancaria em 90s, SEM citacao de jurisprudencia)
- [ ] Testar ChatGPT (Deep Research), Claude (Extended Thinking), Perplexity no celular e notebook
- [ ] Imprimir por participante: 1x Card Onde Clicar, 12 cartas CLEAR, 1x Folha de Recursos, folha de compromisso
- [ ] Imprimir os 3 casos ficticios + Caso 1R (opcao recursal) + Caso 3 backup anonimizacao
- [ ] Comprar post-its (2 cores) + canetas
- [ ] Preparar 2 notebooks reserva ja logados em ChatGPT e Claude
- [ ] Preparar Manual Rapido de IA (PDF) para envio pos-curso

## Montagem da Sala (40 min antes)
- [ ] Projetor testado
- [ ] Em cada lugar: Card Onde Clicar + post-its + caneta
- [ ] Notebooks reserva carregando
- [ ] Video backup acessivel (pen drive + nuvem)
- [ ] Testar tomadas para carregadores
- [ ] Musica ambiente (opcional, para colchao de entrada)
- [ ] Quadro branco limpo (para exercicios coletivos e post-its)

## Durante o Curso
- [ ] ZERO mencoes a "substituicao" ou "medo"
- [ ] Enfatizar: "IA serve para jurisprudencia SIM — com metodo"
- [ ] Celebrar erros como aprendizado ("esse erro e o que protege voces")
- [ ] Circular durante exercicios — PRIORIZAR quem tem dificuldade
- [ ] Observar niveis para formar duplas estrategicas no Dia 2
- [ ] Dar tempo para reflexoes (nao apressar)
- [ ] Anotar duvidas para FAQ futuro
- [ ] Sempre demonstrar thinking mode quando usar IA
- [ ] No Exercicio 8: facilitar discussao coletiva (campeao, primeiro processo, metricas)
- [ ] No buddy system: sugerir duplas com base no que observou durante o curso

## Depois do Curso (mesmo dia)
- [ ] Enviar por e-mail: Manual Rapido de IA (PDF), cartas PDF, casos, todos os materiais
- [ ] Confirmar buddies formados e canal de comunicacao entre eles

## Depois do Curso (1 semana)
- [ ] Follow-up em 7 dias: "Como foi o compromisso? Buddy system funcionou?"
- [ ] Coletar feedback estruturado (formulario)
- [ ] Verificar com campeao de IA: adocao esta acontecendo?

## Depois do Curso (30 dias)
- [ ] Reuniao de 30 min com o escritorio: metricas de impacto
- [ ] Compilar resultados para v4
- [ ] Oferecer modulo avancado (2h) para quem quiser ir alem

---

# TIMING FINAL v3.3

## DIA 1 — SEXTA (3h = 180 min)

| Bloco | Inicio | Fim | Duracao | Novidade v3.3 |
|-------|--------|-----|---------|---------------|
| Colchao de entrada | 0:00 | 0:05 | 5 min | |
| 1. Espanto + Micro-CLEAR | 0:05 | 0:50 | 45 min | +Slide dados de impacto |
| 2. Pesquisa Inteligente | 0:50 | 1:40 | 50 min | |
| Intervalo | 1:40 | 1:55 | 15 min | |
| 3. Ferramentas + CLEAR | 1:55 | 2:40 | 45 min | +Exerc.4B (Crie seu CLEAR) |
| Exercicio Comunicacao | 2:40 | 2:45 | 5 min | NOVO — e-mail relampago |
| FAQ + Buffer | 2:45 | 3:00 | 15 min | |
| **Total** | | | **180 min** | |

## DIA 2 — SABADO (3h = 180 min)

| Bloco | Inicio | Fim | Duracao | Novidade v3.3 |
|-------|--------|-----|---------|---------------|
| 4. Dominio | 0:00 | 1:15 | 75 min | +Opcao caso, +Exerc.5B Escala |
| Intervalo | 1:15 | 1:30 | 15 min | |
| 5. Horizontes | 1:30 | 1:40 | 10 min | |
| 6. Seguranca | 1:40 | 2:15 | 35 min | |
| 7. Compromisso + Implementacao | 2:15 | 2:45 | 30 min | +Exerc.8 coletivo, +Buddy |
| Buffer | 2:45 | 3:00 | 15 min | |
| **Total** | | | **180 min** | |

---

# MUDANCAS v3.2 → v3.3 (Resumo)

| Item | v3.2 | v3.3 |
|------|------|------|
| Dados de impacto | Nao existia | Slide com 3 dados fundamentados (Thomson Reuters, Stanford, 47% escritorios) |
| Exercicio 4B | Nao existia | "Crie SEU prompt CLEAR" — 5 min de pratica de criacao |
| Exercicio Comunicacao | Nao existia | E-mail relampago para cliente — 5 min |
| Exercicio 5 casos | Apenas Caso 1 | Opcao: Caso 1 (contestacao) OU Caso 2 (aereo) OU Caso 1R (recurso) |
| Caso 1R | Nao existia | Versao recursal do Caso 1 (banco condenado) |
| Exercicio 5B Escala | Nao existia | "Como replica para 50?" — template replicavel com variaveis |
| Exercicio 8 | Nao existia | Plano de implementacao coletivo (campeao, 1o processo, metricas) |
| Buddy system | Nao existia | Dupla de acompanhamento pos-curso (2 semanas) |
| Manual Rapido | Nao existia | PDF consolidado pos-curso para entregar por e-mail |
| Modulo avancado | Nao existia | Oferta de 2h opcional (GPTs, Projects, biblioteca) |
| Follow-up 30 dias | Nao previsto | Reuniao de metricas de impacto |
| Total exercicios | 7 | 9 (+4B comunicacao, +5B escala, +8 implementacao) |

---

# EVOLUCAO COMPLETA DO ROTEIRO

| Versao | Data | Foco | Exercicios | Pratica |
|--------|------|------|-----------|---------|
| v1 | Jan/2026 | Generico, muito slide | 2 | 20 min (11%) |
| v2 | Jan/2026 | Pratico, menos slide | 5 | 190 min (63%) |
| v3 | Fev/2026 | CLEAR, casos ficticios | 7 | 200 min (67%) |
| v3.1 | Fev/2026 | Defesa empresarial 100% | 7 | 200 min (67%) |
| v3.2 | Fev/2026 | Pos-simulacao palestrante | 7 | 205 min (68%) |
| **v3.3** | **Fev/2026** | **Pos-simulacao ouvintes** | **9** | **215 min (72%)** |

---

*Roteiro v3.3 — Pos-simulacao completa (palestrante + ouvintes) — 2026-02-06*
*36 problemas identificados e corrigidos ao longo de 3 rodadas*
*9 exercicios, 72% pratica, 12 cartas CLEAR, 4 casos ficticios*
*Materiais: Card Onde Clicar, E-mail Pre-Curso, Folha de Recursos, Manual Rapido (PDF)*
