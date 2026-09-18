# Tratamentos disponíveis e promissores para a doença de Alzheimer

> Caderno Temático desenvolvido no NotebookLM para o Desafio de Projeto da DIO.

## 1. Contexto

A doença de Alzheimer (DA) é uma doença neurodegenerativa progressiva e a principal causa de demência. Ela afeta memória, linguagem, orientação, comportamento e, com a progressão, a autonomia para realizar atividades cotidianas.

Este projeto utiliza o NotebookLM como uma ferramenta de aprendizagem ativa: as fontes foram reunidas, comparadas e transformadas em materiais de estudo para compreender:

- tratamentos sintomáticos atualmente disponíveis;
- tratamentos que atuam sobre mecanismos relacionados à doença;
- estratégias não farmacológicas e redução de risco;
- terapias ainda experimentais, como terapia gênica e tratamentos dirigidos à proteína tau;
- limites das evidências e cuidados para não confundir promessa científica com tratamento comprovado.

> **Aviso:** este material tem finalidade educacional. Não substitui avaliação médica, diagnóstico, prescrição ou acompanhamento profissional.

## 2. Objetivos de estudo

1. Explicar, em linguagem acessível, as principais alterações associadas à doença de Alzheimer.
2. Diferenciar tratamento sintomático, tratamento modificador da doença, prevenção e cuidados paliativos.
3. Comparar mecanismos de ação, benefícios esperados, limitações e riscos das principais abordagens.
4. Avaliar criticamente notícias sobre medicamentos novos, ensaios clínicos e terapias promissoras.
5. Organizar um conjunto de prompts reutilizáveis para revisão e aprofundamento no NotebookLM.

## 3. Curadoria de fontes

As fontes foram selecionadas por sua relevância científica, institucional ou didática. A prioridade foi dada a documentos oficiais, revisões sistemáticas, registros de ensaios clínicos e artigo científico em PDF.

### Fontes principais utilizadas no NotebookLM

1. **Aprovado medicamento inédito para tratamento da doença de Alzheimer — Anvisa**  
   Fonte oficial sobre a aprovação brasileira do lecanemabe, sua indicação, administração, resultados, critérios de elegibilidade e riscos.
   - [Anvisa — notícia sobre o medicamento](https://www.gov.br/anvisa/pt-br/assuntos/noticias-anvisa/2026/aprovado-medicamento-inedito-para-tratamento-da-doenca-de-alzheimer)
   - [Anvisa — LEQEMBI (lecanemabe): novo registro](https://www.gov.br/anvisa/pt-br/assuntos/medicamentos/novos-medicamentos-e-indicacoes/leqembi-lecanemabe-novo-registro)

2. **Aprova o Protocolo Clínico e Diretrizes Terapêuticas da Doença de Alzheimer — Ministério da Saúde/Conitec**  
   Documento brasileiro de referência para diagnóstico, tratamento medicamentoso e não medicamentoso, acompanhamento e segurança.
   - [Página do PCDT no Ministério da Saúde](https://www.gov.br/saude/pt-br/assuntos/pcdt/d/doenca-de-alzheimer/view)
   - [PCDT da Doença de Alzheimer — Portaria Conjunta SAES/SCTIE nº 27/2025](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt-da-doenca-de-alzheimer/@@display-file/file)

3. **Terapia génica na doença de Alzheimer: uma nova abordagem terapêutica — Acta Farmacêutica Portuguesa, 2021**  
   Artigo anexado ao projeto como `ArtigoAlzheimer.pdf`. Apresenta mecanismos da doença e investiga alvos e estratégias de terapia gênica, incluindo APP, BACE1, neprilisina, ApoE, tau, NGF, BDNF, TREM2, citocinas e autofagia.
   - Arquivo local: `ArtigoAlzheimer.pdf`
   - Texto extraído para consulta no NotebookLM: `ArtigoAlzheimer.md`
   - Observação: o PDF foi fornecido como anexo e não possui, neste repositório, um link público confirmado.

4. **Mediterranean Diet, Ketogenic Diet or MIND Diet for Aging Populations with Cognitive Decline: A Systematic Review**  
   Revisão sistemática sobre padrões alimentares e cognição, com 11 estudos sobre dieta mediterrânea, 7 sobre dieta cetogênica e 1 sobre dieta MIND.
   - [Artigo em acesso aberto — PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9866105/)

5. **Risk reduction of cognitive decline and dementia — WHO Guidelines**  
   Diretriz da Organização Mundial da Saúde sobre atividade física, alimentação, controle de fatores de risco e outras estratégias de redução de risco.
   - [Resumo executivo da OMS](https://cdn.who.int/media/docs/default-source/mental-health/dementia/english_foreward_executive_summary_dementia_guidelines.pdf)

### Fontes complementares consultadas

- [ClinicalTrials.gov — Estudo do BIIB080/MAPTRx, NCT03186989](https://clinicaltrials.gov/study/NCT03186989)
- [ClinicalTrials.gov — Terapia gênica com NGF, NCT00017940](https://clinicaltrials.gov/study/NCT00017940)
- [PubMed — Cannabidiol and Alzheimer's disease](https://pubmed.ncbi.nlm.nih.gov/39029982)
- [PubMed — A randomized clinical trial of low-dose cannabis extract in Alzheimer's disease](https://pubmed.ncbi.nlm.nih.gov/41160460)
- [NEJM — Lecanemab in Early Alzheimer’s Disease](https://www.nejm.org/doi/10.1056/NEJMoa2212948)
- [PubMed — Effects of ketogenic diet on cognitive function of patients with Alzheimer's disease](https://pubmed.ncbi.nlm.nih.gov/38943982)
- [PubMed — Association between Mediterranean diet and dementia and Alzheimer disease](https://pubmed.ncbi.nlm.nih.gov/38519775)

## 4. O que foi produzido no NotebookLM

### 4.1 Infográfico

O infográfico foi criado para apresentar, em tópicos, os seguintes pontos:

- sintomas e impactos funcionais da doença;
- placas beta-amiloides e emaranhados de proteína tau;
- neuroinflamação, estresse oxidativo, excitotoxicidade e alterações de neurotransmissores;
- aspectos ainda não compreendidos;
- tratamentos sintomáticos e seus mecanismos de ação;
- tratamentos promissores para os próximos anos.

### 4.2 Vídeo explicativo

Foi criado um vídeo sobre o lecanemabe, medicamento aprovado pela Anvisa para pacientes adultos com comprometimento cognitivo leve ou demência leve devido à doença de Alzheimer, desde que a patologia amiloide esteja confirmada e sejam atendidos os critérios relacionados ao gene **ApoE ε4**.

O vídeo deve destacar que:

- o lecanemabe é um anticorpo monoclonal dirigido contra agregados de beta-amiloide;
- a administração é intravenosa, em geral a cada duas semanas;
- seu objetivo é retardar o declínio, e não curar ou reverter a doença;
- a indicação depende de seleção clínica e confirmação da patologia amiloide;
- há riscos importantes, especialmente as anormalidades de imagem relacionadas à amiloide, conhecidas como **ARIA**;
- pacientes homozigotos para ApoE ε4 apresentam risco maior e não foram incluídos na indicação brasileira favorável descrita pela Anvisa.

## 5. Miniguia de estudo

### 5.1 Como a doença se manifesta

A doença costuma evoluir de forma gradual. No início, podem aparecer esquecimentos de acontecimentos recentes, dificuldade para encontrar palavras, perda de organização e problemas para realizar tarefas conhecidas. Com a progressão, surgem maior dependência, alterações de comportamento, dificuldades de comunicação, desorientação e perda de autonomia.

### 5.2 O que se sabe sobre as causas

A doença é multifatorial. Os principais elementos estudados incluem:

- **Beta-amiloide:** fragmentos derivados da proteína precursora amiloide podem se acumular e formar oligômeros e placas.
- **Proteína tau:** a tau hiperfosforilada se desprende dos microtúbulos e forma emaranhados dentro dos neurônios.
- **Neuroinflamação:** microglia e astrócitos podem permanecer ativados, liberando mediadores inflamatórios e contribuindo para lesão neuronal.
- **Estresse oxidativo e disfunção mitocondrial:** aumentam a vulnerabilidade e o dano das células nervosas.
- **Alterações de neurotransmissores:** a redução da atividade colinérgica e a desregulação do glutamato contribuem para alterações de memória e aprendizagem.
- **Genética:** mutações em APP, PSEN1 e PSEN2 estão associadas a formas familiares de início precoce. A variante ApoE ε4 aumenta o risco, mas não determina sozinha que a doença ocorrerá.
- **Fatores modificáveis:** saúde cardiovascular, atividade física, tabagismo, diabetes, hipertensão, isolamento social, sono e alimentação podem influenciar o risco cognitivo.

### 5.3 O que ainda não está completamente compreendido

Ainda não existe uma explicação única capaz de esclarecer por que a doença começa, por que progride de maneira diferente entre as pessoas e por que a remoção de placas amiloides nem sempre produz uma recuperação proporcional das funções cognitivas. Também permanecem desafios relacionados ao diagnóstico precoce, à heterogeneidade da doença, à barreira hematoencefálica e à identificação do melhor momento para intervir.

### 5.4 Tratamentos disponíveis e cuidados

| Abordagem | Como atua | Papel principal | Limitações e cuidados |
|---|---|---|---|
| Inibidores da acetilcolinesterase | Aumentam a disponibilidade de acetilcolina | Tratamento sintomático, sobretudo em fases iniciais ou intermediárias | Benefício limitado e possibilidade de efeitos adversos; decisão individualizada |
| Memantina | Modula a ativação dos receptores NMDA e a excitotoxicidade pelo glutamato | Tratamento sintomático, especialmente em doença moderada a grave | Não interrompe a causa da doença; requer acompanhamento clínico |
| Tratamento de sintomas comportamentais | Pode incluir intervenções ambientais, psicossociais e medicamentos selecionados | Reduz sofrimento, agitação, depressão, ansiedade ou alterações do sono | Deve priorizar medidas não farmacológicas e avaliar riscos individualmente |
| Cuidados multiprofissionais | Integra neurologia, geriatria, enfermagem, psicologia, fisioterapia, terapia ocupacional, fonoaudiologia, nutrição e assistência social | Preserva funcionalidade, segurança e qualidade de vida | Requer continuidade e participação do cuidador |
| Lecanemabe | Reduz agregados de beta-amiloide, especialmente protofibrilas | Retarda modestamente o declínio em pacientes selecionados com doença inicial | Não é cura; exige confirmação amiloide, monitoramento por imagem e avaliação de risco de ARIA |

### 5.5 Estratégias não farmacológicas e redução de risco

- atividade física regular adaptada à condição da pessoa;
- alimentação equilibrada, com padrão mediterrâneo como abordagem mais respaldada entre as dietas estudadas;
- controle de hipertensão, diabetes, colesterol e saúde cardiovascular;
- cessação do tabagismo e redução do consumo nocivo de álcool;
- sono adequado, tratamento de depressão e correção de perdas auditivas quando indicado;
- atividades cognitivas, sociais e ocupacionais significativas;
- adaptações do ambiente para reduzir quedas, confusão e acidentes.

A dieta cetogênica é uma linha de investigação, mas não deve ser apresentada como cura ou como substituta do tratamento médico. A evidência clínica ainda é menor e exige atenção a tolerabilidade, estado nutricional, comorbidades e alterações metabólicas.

### 5.6 Tratamentos promissores

O artigo anexado apresenta várias linhas de investigação. Entre elas:

- **Terapia anti-tau:** oligonucleotídeos antissenso, como o BIIB080/MAPTRx, buscam reduzir a expressão ou a propagação patológica da tau.
- **Terapia gênica com neurotrofinas:** NGF e BDNF podem favorecer sobrevivência neuronal e plasticidade, embora os resultados clínicos ainda não comprovem benefício cognitivo consistente.
- **Modulação da microglia:** TREM2, IL-2, IL-4, IL-10 e outros alvos tentam melhorar a resposta imune cerebral, mas os resultados pré-clínicos podem ser dependentes do modelo e do estágio da doença.
- **Depuração de beta-amiloide:** neprilisina, ECE, ApoE e outras estratégias procuram aumentar a remoção ou reduzir a produção de beta-amiloide.
- **Metabolismo lipídico e colesterol:** CYP46A1 e ACAT1/SOAT1 são alvos estudados em modelos experimentais.
- **Autofagia e proteostase:** beclina-1 e p62/SQSTM1 podem influenciar a remoção de proteínas e organelas danificadas.
- **Canabidiol e canabinoides:** há mecanismos pré-clínicos interessantes e estudos clínicos iniciais, mas ainda não há evidência suficiente para tratar o canabidiol como terapia estabelecida para Alzheimer.

A regra de interpretação é simples: resultados em células ou animais indicam plausibilidade, ensaios de fase I avaliam principalmente segurança, fases II e III investigam eficácia clínica, e aprovação regulatória não significa cura.

## 6. Glossário

- **Aβ ou beta-amiloide:** fragmento proteico associado à formação de placas no cérebro.
- **ApoE ε4:** variante genética que aumenta o risco de Alzheimer e também influencia o risco de ARIA com terapias antiamiloide.
- **ARIA:** anormalidades de imagem relacionadas à amiloide; podem envolver edema ou pequenos sangramentos cerebrais.
- **Anticorpo monoclonal:** proteína produzida para reconhecer um alvo específico.
- **Barreira hematoencefálica:** estrutura que limita a passagem de substâncias do sangue para o sistema nervoso central.
- **Biomarcador:** medida que fornece informação sobre uma doença ou processo biológico.
- **CDR-SB:** escala usada para avaliar gravidade e progressão clínica da demência.
- **Ensaio clínico:** estudo realizado em seres humanos para avaliar segurança, eficácia ou outros efeitos de uma intervenção.
- **Lecanemabe:** anticorpo monoclonal antiamiloide aprovado no Brasil para casos iniciais selecionados.
- **Microglia:** células imunes residentes do sistema nervoso central.
- **Neuroinflamação:** resposta inflamatória no tecido nervoso.
- **Neurotrofina:** proteína que apoia crescimento, sobrevivência e plasticidade neuronal.
- **Oligonucleotídeo antissenso:** sequência curta de ácido nucleico desenvolvida para reduzir a produção de uma proteína-alvo.
- **Placa amiloide:** depósito extracelular de agregados de beta-amiloide.
- **Proteína tau:** proteína associada aos microtúbulos; sua hiperfosforilação participa dos emaranhados neurofibrilares.
- **Terapia modificadora da doença:** intervenção que busca alterar a evolução biológica da doença, e não apenas aliviar sintomas.
- **Terapia gênica:** uso de material genético ou de sistemas de entrega para modificar a expressão de genes com finalidade terapêutica.

## 7. Engenharia de prompts e cicatrizes

### Prompt inicial do infográfico

> Descreva brevemente como os sintomas acometem os pacientes, explicando cientificamente quais são as principais causas conhecidas da doença, o que ainda não é compreendido, quais são os principais tratamentos paliativos e seu modo de ação e quais são os tratamentos promissores para os próximos anos. Organize tudo em tópicos bem definidos, em linguagem adulta, porém compreensível para o público leigo.

### Prompts estratégicos recomendados

1. **Síntese com referências**

   > Com base somente nas fontes deste caderno, explique a doença de Alzheimer em cinco blocos: sintomas, mecanismos biológicos, tratamentos disponíveis, tratamentos promissores e limitações das evidências. Para cada afirmação relevante, indique a fonte utilizada.

2. **Comparação de tratamentos**

   > Crie uma tabela comparando donepezila, rivastigmina, galantamina, memantina e lecanemabe. Inclua mecanismo de ação, estágio da doença, objetivo, benefício esperado, principais riscos e nível de evidência. Não apresente nenhum medicamento como cura.

3. **Leitura crítica de notícia**

   > Verifique se a notícia sobre o lecanemabe diferencia aprovação regulatória, eficácia clínica, redução do declínio e cura. Liste todas as condições de elegibilidade e os riscos descritos pela fonte oficial.

4. **Separação entre evidência e hipótese**

   > Separe as afirmações abaixo em quatro categorias: tratamento aprovado, evidência clínica inicial, evidência pré-clínica e hipótese ainda não comprovada. Justifique cada classificação com base nas fontes.

5. **Revisão ativa**

   > Faça dez perguntas progressivas sobre Alzheimer, começando por conceitos básicos e terminando em terapia anti-tau, terapia gênica e ARIA. Depois apresente o gabarito comentado, citando as fontes.

6. **Análise de limitações**

   > Identifique limitações metodológicas das fontes do caderno: tamanho das amostras, duração dos estudos, tipo de desfecho, modelo animal, conflitos de interesse, ausência de grupo-controle e possibilidade de generalização para pacientes reais.

### Cicatrizes e aprendizados

- **Problema:** notícias podem simplificar resultados e usar expressões como “novo remédio contra o Alzheimer”.
  - **Solução:** conferir a fonte regulatória e diferenciar retardar o declínio de interromper ou reverter a doença.

- **Problema:** resultados de modelos animais podem parecer mais conclusivos do que realmente são.
  - **Solução:** registrar o nível de evidência: pré-clínico, fase I, fase II, fase III ou aprovado.

- **Problema:** o texto do artigo anexado descreve várias estratégias de terapia gênica, mas muitas ainda são experimentais.
  - **Solução:** apresentar terapia gênica como perspectiva de pesquisa, sem sugerir disponibilidade clínica.

- **Problema:** o canabidiol aparece em fontes populares como possível tratamento.
  - **Solução:** separar mecanismos pré-clínicos de evidência clínica e informar que ainda são necessários estudos maiores e mais longos.

## 8. Outras ações para enriquecer o NotebookLM

1. **Criar uma linha do tempo** dos tratamentos: inibidores de colinesterase, memantina, anticorpos antiamiloide e terapias anti-tau.
2. **Gerar uma matriz de evidências** com as colunas: intervenção, alvo, estágio da pesquisa, benefício, risco, fonte e nível de confiança.
3. **Pedir uma checagem de contradições** entre o artigo de 2021, o PCDT de 2025 e as páginas regulatórias de 2025/2026.
4. **Criar um roteiro de podcast** de 5 minutos para explicar o tema a familiares e cuidadores.
5. **Gerar um FAQ** com perguntas que pacientes e familiares fariam sobre lecanemabe, ARIA, ApoE ε4 e tratamentos sintomáticos.
6. **Montar um mapa de conceitos** conectando beta-amiloide, tau, microglia, neurotransmissores, memória e tratamentos.
7. **Criar cartões de estudo** com conceito na frente e explicação baseada nas fontes no verso.
8. **Solicitar uma auditoria de linguagem**, removendo promessas exageradas, termos ambíguos e afirmações sem fonte.
9. **Comparar prevenção e tratamento**, evitando afirmar que uma dieta ou exercício substitui medicamentos ou acompanhamento profissional.
10. **Atualizar periodicamente o caderno**, principalmente os registros de ensaios clínicos e as decisões regulatórias.

## 9. Conclusão

A doença de Alzheimer ainda não possui cura. Os tratamentos sintomáticos podem ajudar em determinados estágios, enquanto o lecanemabe representa uma mudança importante por atuar sobre um marcador biológico da doença em pacientes selecionados, mas seu benefício é limitado, exige acompanhamento rigoroso e não interrompe a progressão.

As linhas mais promissoras incluem terapias antiamiloide, anti-tau, modulação da neuroinflamação, neurotrofinas, terapia gênica, autofagia e estratégias metabólicas. A análise crítica das fontes é indispensável para distinguir uma hipótese biologicamente interessante de uma intervenção comprovadamente eficaz.

## 10. Como reproduzir o estudo

1. Criar um novo caderno no NotebookLM.
2. Adicionar o PDF do artigo e as fontes abertas listadas neste README.
3. Executar os prompts da seção **Engenharia de prompts**.
4. Comparar as respostas com as fontes originais.
5. Atualizar o infográfico e o vídeo incorporando referências, limitações e nível de evidência.
6. Publicar o README e os materiais finais no repositório do GitHub.

## Licença e uso

Este repositório foi criado para fins educacionais e de portfólio. As fontes externas pertencem aos seus respectivos autores e instituições. Consulte as licenças e condições de uso de cada publicação antes de redistribuir cópias integrais.
