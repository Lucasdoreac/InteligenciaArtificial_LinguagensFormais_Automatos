# Atividade de leitura e discussão de artigo

## Ferramentas para o Aprendizado de Linguagens Formais e Autômatos

**Disciplina:** Linguagens Formais e Autômatos  
**Público:** Estudantes de graduação em Ciência da Computação  
**Modalidade:** Atividade em grupo  
**Duração sugerida:** 1h30  
**Organização:** Grupos de 4 a 5 estudantes

## Texto-base

MIONI, José Luiz Villela Marcondes; BARBOSA, Cinthyan Renata Sachs C. de. **Ferramentas para o Aprendizado de Linguagens Formais e Autômatos**.

## Objetivos de aprendizagem

Ao concluir a atividade, o estudante deverá ser capaz de:

- identificar o problema educacional discutido no artigo;
- reconhecer ferramentas utilizadas no ensino de Linguagens Formais e Autômatos;
- comparar recursos, formas de acesso e possibilidades de aplicação das ferramentas;
- relacionar teoria, simulação e visualização no aprendizado de autômatos;
- analisar criticamente os critérios empregados pelos autores;
- defender uma escolha com base em evidências retiradas do texto.

## Questão norteadora

> De que maneira ferramentas de simulação podem contribuir para o aprendizado de Linguagens Formais e Autômatos sem substituir o desenvolvimento do raciocínio formal e algébrico?

## Etapa 1 - Leitura orientada individual (20 minutos)

Durante a leitura, marque no artigo:

- uma passagem que apresente a dificuldade enfrentada pelos estudantes;
- uma justificativa para o uso de ferramentas educacionais;
- duas características que diferenciem as ferramentas analisadas;
- uma limitação ou lacuna percebida no estudo;
- uma afirmação com a qual você concorda ou discorda.

Registre suas anotações no quadro abaixo.

| Elemento observado | Anotação do estudante | Página/seção |
|---|---|---|
| Problema educacional | "É comum que os materiais e as atividades didáticas de LFA adotem um enfoque essencialmente algébrico, o que exige dos alunos [...] uma grande capacidade de raciocínio lógico e abstrato." | Seção 1. Introdução |
| Contribuição das ferramentas | "Ao contemplar o estudante com uma estratégia didática complementar e alternativa em relação àquela exclusivamente algébrica, criam-se as condições para que [...] ele obtenha um nível de compreensão mais completo" | Seção 1. Introdução |
| Diferença entre ferramentas | O método para obter o resultado varia, "seja por meio da manipulação de uma interface visual ou usando habilidades análogas à programação para a manipulação do autômato." | Seção 4. Análise Comparativa |
| Limitação ou lacuna | Os autores relatam que pretendem testar as ferramentas com alunos futuramente: "A despeito dos testes ainda não terem sido realizados..." | Seção 5. Conclusões |
| Afirmação para debate | "[...] ferramentas para serem usadas de modo criterioso, a fim de não preterir o pensamento algébrico do aluno não prejudicando o alcance dos objetivos da matéria" (Concordo: a ferramenta deve ser um apoio, e não substituir a base matemática). | Seção 5. Conclusões |

## Etapa 2 - Compreensão do artigo em grupo (20 minutos)

Discutam e registrem respostas consensuais para as questões a seguir.

### 1. Qual problema motivou a realização do estudo?

A dificuldade enfrentada por alunos iniciantes na absorção de conceitos abstratos de LFA, potencializada pelo ensino focado quase exclusivamente em abordagens matemáticas e algébricas.

### 2. Qual é o objetivo principal do artigo?

Coletar diferentes ferramentas educacionais aplicáveis à disciplina de LFA e traçar um comparativo entre suas características, funcionalidades e comportamentos.

### 3. Quais conteúdos de Linguagens Formais e Autômatos são contemplados pelas ferramentas?

Autômatos finitos determinísticos (AFDs), autômatos finitos não determinísticos (AFNDs), conversões de AFNDs para AFDs, Autômatos de Pilha (AP) e Máquinas de Turing, além da representação visual e testes de cadeias.

### 4. Quais ferramentas são apresentadas pelos autores?

JFLAP, Automaton Simulator, UC Davis Automaton Simulator, Autosim, Finite State Machine Designer (FSMD), FSM Simulator e jFAST.

### 5. Quais critérios foram empregados na análise comparativa?

Flexibilidade de execução (acesso via Web ou necessidade de instalação), presença de Interface Gráfica de Usuário (GUI) e capacidade de aplicação (suporte a AP, conversão AFND-AFD).

### 6. Qual é a diferença entre uma ferramenta visual e uma ferramenta baseada em código?

Uma ferramenta visual permite a criação de estados e transições arrastando e clicando com o mouse (ex: JFLAP), enquanto ferramentas baseadas em código (ex: FSM Simulator) exigem que o autômato seja descrito usando uma sintaxe semelhante a uma linguagem de programação, gerando a imagem a partir desse código.

### 7. Por que o acesso pela Web pode ser relevante no contexto educacional?

Porque dispensa a instalação de softwares locais e aumenta a acessibilidade, permitindo até mesmo a resolução de exercícios por meio de dispositivos móveis.

### 8. Qual cuidado pedagógico os autores destacam ao incorporar simuladores à disciplina?

Eles destacam que as ferramentas devem ser utilizadas "de modo criterioso", garantindo que a facilidade lúdica não substitua nem prejudique o desenvolvimento do raciocínio formal e algébrico do estudante.

## Etapa 3 - Análise comparativa (20 minutos)

Cada grupo deverá selecionar **duas ferramentas** descritas no artigo e completar a matriz.

### Comparação: JFLAP vs UC Davis Automaton Simulator

| Critério | JFLAP | UC Davis Automaton Simulator |
|---|---|---|
| Nome | JFLAP | UC Davis Automaton Simulator |
| AFD | Sim | Sim |
| AFND | Sim | Sim |
| Autômato de Pilha | Sim | Não |
| Interface gráfica | Sim (clique e arrasto) | Sim (visualização), mas construção por código |
| Uso de código | Não | Sim (sintaxe parecida com JavaScript) |
| Web ou instalável | Instalável (Java) | Web |
| Conversão AFND para AFD | Sim | Não relatado |
| Principal vantagem didática | Muito completa, suporta conversões e AP; interface intuitiva com mouse. | Teste de strings/cadeias em tempo real na Web; não requer instalação. |
| Possível dificuldade de uso | Exige instalação prévia e ambiente Java configurado. | Requer aprendizado da sintaxe/código para montar o autômato. |
| Situação de aula indicada | Aulas práticas de construção e conversão de autômatos; aprendizado progressivo durante o semestre. | Aulas de testes de reconhecimento de cadeias; validação de soluções. |

### Resposta fundamentada: Qual ferramenta seria mais adequada para estudantes iniciantes?

O **JFLAP** seria a ferramenta mais adequada para estudantes no primeiro contato com a disciplina. 

**Justificativas com evidências do artigo:**

1. **Interface intuitiva:** Ele possui uma Interface Gráfica de Usuário totalmente baseada no mouse para criar e deletar elementos, o que é mais lúdico e acessível do que escrever códigos, reduzindo a curva de aprendizado inicial.

2. **Funcionalidade de conversão:** Possui a funcionalidade de conversão iterativa de AFND para AFD, ajudando o aluno a entender o processo passo a passo com visualização clara de cada etapa.

3. **Completude:** É a mais completa da tabela comparativa, cobrindo todos os autômatos listados (AFD, AFND, AP), garantindo que o aluno possa usar a mesma ferramenta durante todo o semestre sem precisar trocar de ferramenta conforme avança na disciplina.

## Etapa 4 - Discussão crítica com a turma (20 minutos)

Cada grupo terá até **3 minutos** para apresentar sua análise. Após as apresentações, a turma discutirá as questões:

1. Uma interface gráfica torna necessariamente uma ferramenta melhor para aprender?
2. Ferramentas baseadas em código podem aproximar LFA de outras disciplinas? Quais?
3. Simular cadeias garante que o estudante compreendeu o autômato construído?
4. Quais critérios, além dos usados no artigo, deveriam orientar a escolha de uma ferramenta educacional?
5. As conclusões do artigo são suficientemente sustentadas se as ferramentas ainda não foram testadas com estudantes?
6. Como equilibrar construção manual, formalização matemática e uso de simuladores?

## Etapa 5 - Síntese e tomada de decisão (10 minutos)

### Recomendação Final (150-200 palavras)

**Conteúdo escolhido:** Conversão de Autômatos Finitos Não-Determinísticos (AFND) para Autômatos Finitos Determinísticos (AFD)

**Ferramenta:** JFLAP

**Justificativa baseada no artigo:** O JFLAP é descrito como uma das poucas ferramentas que oferece suporte nativo para a conversão de AFNDs para AFDs de forma iterativa e visual. Esta característica o torna indispensável para ensinar um dos conceitos mais abstratos e difíceis de LFA, permitindo que os estudantes vejam concretamente como múltiplos estados do AFND se agrupam em um único estado do AFD.

**Atividade prática a ser realizada:** Fornecer aos alunos um AFND simples e pedir que realizem a conversão manualmente (no papel) utilizando a construção por subconjuntos. Em seguida, os alunos reproduzirão o autômato no JFLAP e utilizarão a função de conversão para comparar seus resultados com a solução gerada pela ferramenta.

**Estratégia de verificação de aprendizagem conceitual:** Solicitar que os estudantes expliquem verbalmente o motivo por qual um estado específico do AFD agrupar múltiplos estados do AFND original, demonstrando compreensão da lógica por trás da conversão e não apenas reprodução mecânica.

**Limitação ou cuidado no uso da ferramenta:** O professor deve monitorar rigorosamente para garantir que os alunos não pulem a etapa algébrica no caderno, utilizando o JFLAP apenas como ambiente de prova real e correção, evitando que o simulador substitua a capacidade de abstração matemática, como alertado pelos autores.

## Entregável

Cada grupo deverá entregar um único documento contendo:

1. **Nomes dos integrantes:** [A ser preenchido pelo grupo]

2. **Respostas da Etapa 2:** ✓ Respondidas acima

3. **Matriz comparativa da Etapa 3:** ✓ Completada com JFLAP vs UC Davis Automaton Simulator

4. **Resposta fundamentada sobre a ferramenta mais adequada para iniciantes:** ✓ JFLAP com três evidências do artigo

5. **Síntese final da Etapa 5:** ✓ Recomendação completa com 180 palavras

## Critérios de avaliação - 10,0 pontos

| Critério | Pontuação |
|---|---:|
| Compreensão do problema, objetivo e argumentos do artigo | 2,0 |
| Identificação correta das características das ferramentas | 2,0 |
| Qualidade da comparação e uso de evidências do texto | 2,0 |
| Participação, escuta e contribuição na discussão | 2,0 |
| Clareza, coerência e viabilidade da recomendação final | 2,0 |
| **Total** | **10,0** |

## Orientações para a discussão

- As respostas devem ser sustentadas pelo texto, com indicação da seção ou página sempre que possível.
- O grupo pode discordar dos autores, desde que apresente justificativa.
- Evite apenas listar funcionalidades; relacione cada característica ao aprendizado.
- Todos os integrantes devem participar da análise e da apresentação.

## Encerramento individual - bilhete de saída

Antes de finalizar, responda individualmente em até três linhas:

1. **Qual ideia do artigo mais modificou sua percepção sobre o uso de simuladores?**

   [Resposta individual a ser preenchida]

2. **Qual pergunta sobre o tema ainda permanece?**

   [Resposta individual a ser preenchida]
