# IA Generativa em Escritórios de Advocacia_ Uso Global e Guia Prático - Parte 3

Supervisão humana e validação são indispensáveis: Jamais se deve usar cegamente uma saída da IA em um produto final sem revisão. Os modelos podem gerar conteúdo convincente, mas por vezes impreciso ou até inventado. Portanto, encare a IA como assistente e não como autoridade. Grandes escritórios que adotaram essas ferramentas enfatizam que tudo o que a IA produz é checado por advogados antes de ser entregue[46]. Da mesma forma, se a IA redigiu um trecho de petição ou sugeriu um argumento, o advogado deve verificar se está correto juridicamente e adequado ao caso concreto. A IA não substitui a expertise jurídica humana – ela a complementa. Um lembrete comum é que “não há como delegar o julgamento profissional”: o advogado continua responsável pelo produto final, devendo usar senso crítico sobre o que a IA sugere[48]. Em suma, mantenha humano no circuito (human-in-the-loop), especialmente em decisões sensíveis.

Cuidado com “alucinações” e falsos positivos: Os modelos generativos às vezes podem inventar fatos ou referências para parecer convincentes. Houve casos notórios de advogados sancionados por apresentarem jurisprudência inexistente gerada pelo ChatGPT. Para evitar isso, é boa prática exigir que a IA forneça as fontes de suas afirmações e verificar cada uma. Ferramentas especializadas já facilitam isso – por exemplo, o Jus IA inclui referências diretas a documentos na resposta, e possui até uma função específica para verificar se citações existem de fato em qualquer documento dado[42]. Se você usar um modelo genérico que não referencia fontes, redobre a cautela: valide manualmente cada jurisprudência ou artigo de lei citados pelo modelo em sua resposta, antes de confiar neles. Nunca cite em uma peça algo apenas porque a IA disse; confira no texto original (se a IA disser “conforme Súmula 100 do TST”, abra a Súmula 100 e confirme o teor). Adote prompts que instruam a IA a não especular quando não souber e prefira respostas fundamentadas. Em suma, mantenha um pé atrás e não “acredite” na IA sem verificar – por mais confiável que a ferramenta pareça.

Proteja a confidencialidade e os dados sensíveis: Uma consideração crítica ao usar IA é não expor informações confidenciais de clientes ou do escritório em serviços de terceiros sem as devidas salvaguardas. Se você está usando a versão pública do ChatGPT, por exemplo, inserir textos com dados sigilosos (nomes de partes, números de processo, segredos comerciais) pode violar obrigações de confidencialidade, além de potencialmente alimentar os modelos com esses dados. Verifique as políticas de privacidade das ferramentas – algumas, como o ChatGPT Enterprise ou o uso do NotebookLM em ambiente de trabalho Google, garantem que não usam os dados fornecidos para treinar modelos ou que não são vistos por revisores humanos[37]. Se possível, anonimize informações sensíveis antes de colocar no prompt (substitua nomes reais por iniciais, valores exatos por faixas, etc., quando a identidade não for essencial para a tarefa). Considere implementar soluções on-premise ou em nuvem privada para usar IA com dados confidenciais, ou utilize ferramentas que já tenham foco em privacidade (muitas plataformas jurídicas asseguram criptografia ponta-a-ponta e conformidade com LGPD/GDPR[49]). Lembre-se: o sigilo profissional não pode ser comprometido pela comodidade da IA. Muitos escritórios já editaram políticas internas sobre isso, restringindo por exemplo o uso de ferramentas públicas para trabalhos envolvendo informações de clientes. Logo, crie políticas claras de uso de IA no seu escritório e treine a equipe nessas diretrizes.

Esteja atento aos limites de conhecimento da IA:. Portanto, ao solicitar pesquisa jurídica, peça para que ele pesquise na internet informações atuais.  use a IA como pontapé inicial, mas confirme se não surgiram alterações recentes. Por exemplo, se perguntar sobre “jurisprudência atual” em um tema, a IA pode não incluir decisões dos últimos meses/anos. Em 2023 e 2024, já surgiram versões com acesso à internet para atualizações em tempo real, mas ainda assim convém ter prudência. A recomendação é sempre conduzir uma verificação final manual ou em bases atualizadas (como os diários oficiais, sites dos tribunais) para temas onde a atualidade é crítica. Além disso, a IA pode carecer de contexto local ou regional – se treinada principalmente em dados de certo país ou idioma, suas respostas sobre leis de outro país podem ser menos confiáveis. Procure especificar a jurisdição no prompt (“... na legislação trabalhista brasileira” por exemplo) e, se perceber uma incerteza, refine a pergunta ou consulte fontes tradicionais. Em resumo, use a IA como auxiliar, mas não como fonte definitiva, especialmente em questões de direito em evolução.

Mantenha as habilidades humanas afiadas: Uma possível armadilha do uso intenso de IA é a acomodação – confiar tanto no modelo que o advogado deixa de exercitar suas habilidades de pesquisa, redação ou análise crítica. Evite isso utilizando a IA de forma colaborativa: compare as sugestões da IA com o que você pensou, critique o output, use-o para enriquecer seu próprio raciocínio. Lembre-se de que a responsabilidade intelectual e ética do trabalho é sempre do advogado. As soft skills – empatia no atendimento ao cliente, negociação, argumentação oral – continuam insubstituíveis. Use a IA para potencializar sua produtividade, mas não dependa dela para coisas que você mesmo precisa saber fazer. Por exemplo, se a IA lhe deu um resumo de um precedente, leia o precedente na íntegra depois para não perder o feeling jurídico. Se ela gerou uma minuta, revise e tente entender cada argumento inserido. Assim, você aprende com a IA e não apenas delega tudo a ela. Em treinamento interno, incentive advogados juniores a verificar por que a IA indicou certo artigo de lei – isso transforma a interação em aprendizado contínuo, em vez de mera muleta.

Treinamento e governança interna: A incorporação segura de IA requer que toda a equipe esteja alinhada em como e quando usar (ou não usar) essas ferramentas. É uma boa prática promover treinamentos periódicos sobre o funcionamento básico de IA generativa, suas limitações e casos de uso aprovados dentro do escritório. Segundo pesquisa, embora a adoção de IA esteja aumentando, 64% dos profissionais jurídicos afirmaram não ter recebido treinamento específico em IA até 2024, embora esse número venha melhorando (31% já tinham treinamento disponível em 2025, contra 19% no ano anterior)[50]. Fornecer conhecimento aos advogados sobre prompt engineering básico (como escrever perguntas claras e fornecer contexto) pode melhorar bastante os resultados obtidos. Além disso, estabelecer políticas de uso é essencial – por exemplo, definindo quais ferramentas são aprovadas (e em que situações), como lidar com dados sensíveis (conforme mencionado), e quem supervisiona os resultados. Algumas firmas maiores têm comitês de inovação ou grupos de trabalho dedicados a avaliar novas ferramentas de IA, testar e criar diretrizes internas antes de liberar a todos. Mesmo em um pequeno escritório, vale documentar regras simples, como: “usar ChatGPT apenas para tarefas de pesquisa genérica ou rascunhos, nunca colar parecer inteiro do cliente; sempre revisar tudo que a IA produzir; não usar IA para decidir estratégia legal sem validação humana”, etc. Essa governança evita usos indevidos que possam gerar riscos éticos ou resultados de má qualidade. Em suma, encare a IA como mais uma competência profissional a ser desenvolvida – investir em educação e controle hoje permitirá colher os frutos com segurança amanhã.

Seguindo essas melhores práticas, os escritórios podem aproveitar o melhor da IA generativa – celeridade, acesso à informação, automação – minimizando os percalços. A chave é responsabilidade e bom senso: a IA deve servir ao advogado, e não o contrário. Quando bem utilizada, dentro de parâmetros éticos e com verificação, ela se torna uma ferramenta poderosa que eleva o nível do serviço jurídico prestado, ao invés de comprometer sua integridade.

Exemplos de Prompts

…

Fontes e Referências:

Thomson Reuters Institute – 2025 Generative AI in Professional Services Report (Resumo para a área jurídica)[5][19][2]

Thomson Reuters Legal Blog – “Generative AI for legal professionals: Top use cases” (Artigo de 13/05/2025)[4][20][16]

Jusbrasil – Release: “Jusbrasil lança Jus IA para aumentar a confiança no uso de IA no Direito” (05/10/2023)[23][56][30]

Clio – 2025 Legal Trends for Solo and Small Firms (Relatório)[8][31][9]

Everlaw – “Lawyers Are Adopting Generative AI Faster than Other Technologies” (Ediscovery Survey 2024)[57][58]

SiliconANGLE – “PwC partners with Harvey to build AI tools to assist its lawyers” (15/03/2023)[28][46]

Reuters – “OpenAI-backed startup brings chatbot technology to first major law firm” (16/02/2023)[45][12]

Clio Blog – “10 ChatGPT Prompts for Lawyers: Tips & Use-Cases” (2023)[51][53]

Anthropic – “Introducing 100K Context Windows” (2023)[32] (capacidade do Claude)

Outras fontes citadas ao longo do texto nos trechos sinalizados.

[1] [3] [4] [13] [15] [16] [17] [20] [21] [22] [25] [26] [27] [29] [47] [49] [54] [55] Generative AI for legal professionals: Top use cases

https://legal.thomsonreuters.com/blog/generative-ai-for-legal-professionals-top-use-cases-tri/

[2] [5] [6] [7] [10] [11] [14] [19] [50] 2025 GenAI report: Executive summary for legal professionals

https://legal.thomsonreuters.com/blog/genai-report-executive-summary-for-legal-professionals-tri/

[8] [9] [31]  Fresh Insights for Solo and Small Law Firms | Clio

https://www.clio.com/blog/solo-small-law-firms-highlights-2025-legal-trends/

[12] [44] [45] OpenAI-backed startup brings chatbot technology to first major law firm | Reuters

https://www.reuters.com/legal/transactional/openai-backed-startup-brings-chatbot-technology-first-major-law-firm-2023-02-15/

[18] 73% of lawyers plan to use generative AI, report finds | Legal Dive

https://www.legaldive.com/news/generative-ai-legal-use-cases-wolters-kluwer-report/700342/

[23] [24] [30] [38] [39] [40] [41] [42] [43] [56] Jusbrasil lança Jus IA para aumentar a confiança no uso de inteligência artificial no Direito

https://sobre.jusbrasil.com.br/releases/jusbrasil-lanca-jus-ia-para-aumentar-a-confianca-no-uso-de-inteligencia-artificial-no-direito

[28] [46] PwC partners with Harvey to build AI tools to assist its lawyers - SiliconANGLE

https://siliconangle.com/2023/03/15/pwc-partners-harvey-build-ai-tools-assist-lawyers/

[32] How Claude's 100K Contexts Enable Deeper Analysis and Insights ...

https://meetcody.ai/blog/how-claudes-100k-contexts-enable-deeper-analysis-and-insights-for-business/

[33] [34] [35] [36] [37] Top 10 NotebookLM Benefits for Lawyers and Mediators | Lawyers & Mediators International

https://lmipodcast.com/top-10-notebooklm-benefits-for-lawyers-and-mediators/

[48] [51] [52] [53]  10 ChatGPT Prompts for Lawyers: Tips & Use-Cases

https://www.clio.com/blog/chat-gpt-prompts/

[57] [58] Lawyers Are Adopting Generative AI Faster than Other Technologies

https://www.everlaw.com/blog/ai-and-law/lawyers-are-adopting-generative-ai-faster-than-other-technologies/
