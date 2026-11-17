# Protocolo de Fontes da Análise Rasika da Līlā

**Arquivo:** `metodo/protocolo-de-fontes.md`  
**Versão:** 1.0 — Proposta para aprovação  
**Escopo:** Identificação, organização, consulta, avaliação e rastreabilidade das fontes  
**Aplicação:** Todas as obras, capítulos, blocos e núcleos investigados

---

## 1. Finalidade

Este protocolo estabelece as regras para utilização das fontes na Análise Rasika da Līlā.

Sua finalidade é assegurar que toda investigação esteja fundamentada em materiais identificáveis, que as afirmações possam ser rastreadas até suas fontes e que sejam preservadas as distinções entre:

- texto original;
- tradução;
- comentário tradicional;
- referência gramatical ou lexicográfica;
- fundamentação teológica;
- estudo acadêmico;
- interpretação do próprio investigador;
- contemplação rasika.

O protocolo também estabelece procedimentos para lidar com variantes textuais, divergências entre traduções, fontes incompletas, atribuições incertas e interpretações que não puderam ser confirmadas documentalmente.

Não se pretende utilizar fontes apenas para acumular referências. Cada consulta deve responder a uma necessidade concreta da investigação.

## 2. Princípios fundamentais

### 2.1. Rastreabilidade

Toda afirmação que dependa de uma fonte externa deve permitir identificar:

1. qual é a fonte;
2. onde se encontra a informação;
3. qual passagem sustenta a afirmação;
4. se a fonte foi consultada diretamente ou conhecida por intermédio de outra publicação;
5. qual é o grau de segurança da atribuição.

Uma referência bibliográfica sem localização suficiente não é considerada rastreabilidade completa.

### 2.2. Fidelidade à fonte

A fonte deve ser apresentada de acordo com o que efetivamente contém.

Não se deve:

- atribuir a uma fonte uma afirmação que ela não faz;
- ampliar uma passagem para além de seu contexto;
- transformar uma interpretação do comentarista em significado literal do texto;
- combinar passagens distintas como se constituíssem uma única afirmação;
- omitir divergências que alterem significativamente a interpretação.

### 2.3. Hierarquia funcional

As fontes possuem funções diferentes. Uma obra pode ser autoridade para determinada questão e não ser a fonte apropriada para outra.

O texto original é a referência primária para estabelecer o que o autor escreveu. Uma gramática pode esclarecer uma construção sintática. Um comentário tradicional pode oferecer uma interpretação específica. Uma obra teológica pode fundamentar um conceito doutrinário.

Não se deve substituir uma fonte pela outra quando suas funções são distintas.

### 2.4. Separação entre evidência e interpretação

O conteúdo de uma fonte e a interpretação produzida a partir dele devem permanecer distinguíveis.

Quando uma fonte oferece uma interpretação, é necessário registrar se:

- ela afirma explicitamente determinado significado;
- ela sugere uma leitura sem afirmá-la diretamente;
- ela fornece um fundamento doutrinário utilizado pelo investigador;
- ela apenas oferece uma analogia ou paralelo interpretativo.

### 2.5. Transparência sobre limitações

Quando uma fonte não puder ser consultada diretamente, quando faltar uma página ou quando uma referência estiver incompleta, isso deve ser registrado.

Não se deve preencher silenciosamente uma lacuna documental com conhecimento presumido.

---

## 3. Organização das fontes

As fontes serão centralizadas no diretório `fontes/`, organizadas por obra e por função.

Estrutura de referência:

```text
fontes/
├── catalogo-de-fontes.md
├── govinda-lilamrta/
│   ├── textos-originais/
│   ├── traducoes/
│   ├── comentarios/
│   └── referencias-complementares/
├── krsna-bhavanamrta/
│   ├── textos-originais/
│   ├── traducoes/
│   ├── comentarios/
│   └── referencias-complementares/
└── referencias-gerais/
    ├── dicionarios/
    ├── gramatica-sanscrita/
    └── obras-teologicas/
```

As fontes são organizadas por obra, e não por capítulo, porque uma mesma edição, tradução ou comentário poderá ser utilizado em diferentes capítulos.

Os materiais específicos de cada investigação devem ser referenciados nos dossiês dos núcleos e nos registros correspondentes.

Os arquivos originais não devem ser alterados para facilitar a análise. Transcrições, anotações, correções editoriais e traduções de trabalho devem permanecer em arquivos separados.

## 4. Identificação das fontes

### 4.1. Identificadores estáveis

Cada fonte deve receber um identificador único e estável, registrado no `catalogo-de-fontes.md`.

Padrão recomendado:

`SIGLA-CLASSE-NÚMERO`

Exemplos:

| Identificador | Significado |
|---|---|
| `GL-ORIG-001` | Texto original do Govinda-līlāmṛta |
| `GL-TRAD-001` | Tradução do Govinda-līlāmṛta |
| `GL-COM-001` | Comentário do Govinda-līlāmṛta |
| `KB-ORIG-001` | Texto original do Kṛṣṇa-bhāvanāmṛta |
| `KB-TRAD-001` | Tradução do Kṛṣṇa-bhāvanāmṛta |
| `KB-COM-001` | Comentário do Kṛṣṇa-bhāvanāmṛta |
| `REF-GRAM-001` | Referência gramatical |
| `REF-LEX-001` | Referência lexicográfica |
| `REF-TEO-001` | Referência teológica |

A numeração é sequencial dentro da respectiva classe e obra.

Um identificador não deve ser reutilizado, mesmo quando uma fonte deixa de ser utilizada.

### 4.2. Dados mínimos do catálogo

Cada registro deve conter, sempre que disponíveis:

- identificador;
- título original;
- título alternativo ou traduzido;
- autor;
- comentarista, tradutor ou editor;
- edição;
- editora;
- local de publicação;
- ano;
- volume;
- idioma;
- tipo de fonte;
- localização do arquivo;
- origem do material;
- endereço eletrônico, DOI ou outro identificador persistente, quando houver;
- estado de consulta;
- observações sobre integridade ou limitações.

Quando algum dado não estiver disponível, registrar `não identificado` ou `não informado`, em vez de inventá-lo.

### 4.3. Distinção entre obra e edição

A identificação de uma obra não é suficiente para identificar a fonte efetivamente utilizada.

É necessário distinguir:

- obra original;
- edição consultada;
- reprodução digital;
- transcrição de trabalho;
- tradução;
- edição crítica;
- comentário associado.

Duas edições da mesma obra podem apresentar diferenças relevantes. Cada edição efetivamente consultada deve possuir registro próprio quando necessário para a rastreabilidade.

---

## 5. Classes de fontes e suas funções

### 5.1. Textos originais

São as fontes primárias para a investigação do texto.

No caso de obras em sânscrito, devem ser preservados:

- texto original;
- divisão dos versos;
- numeração;
- sandhi;
- diacríticos;
- variantes editoriais;
- informações sobre a edição utilizada.

A transcrição utilizada na análise deve ser confrontada com a edição de referência.

Quando houver divergência entre edições, ela deve ser registrada, sem correção silenciosa do texto original.

### 5.2. Traduções

As traduções auxiliam a compreensão, mas não substituem a investigação do original.

Devem ser registradas com:

- identificação do tradutor;
- edição;
- idioma;
- localização da passagem;
- eventuais notas do tradutor;
- divergências relevantes em relação ao original ou a outras traduções.

Quando duas traduções apresentarem diferenças significativas, a análise deverá examinar se a divergência decorre de:

- interpretação gramatical;
- escolha lexical;
- variante textual;
- opção estilística;
- interpretação contextual;
- pressuposto doutrinário.

A tradução adotada deve ser justificada quando a escolha afetar a compreensão do verso.

### 5.3. Comentários tradicionais

Os comentários tradicionais constituem fontes fundamentais para investigar a recepção e a interpretação da obra dentro da tradição.

Devem ser registrados:

- autor ou comentarista;
- título do comentário;
- obra comentada;
- edição;
- localização exata da passagem;
- texto original do comentário, quando disponível;
- tradução utilizada;
- relação entre a explicação do comentarista e a interpretação em investigação.

É obrigatório distinguir o que o comentarista afirma explicitamente daquilo que o investigador infere a partir de sua explicação.

**Regra de atribuição:** não atribuir uma interpretação a um ācārya apenas porque ela parece compatível com sua teologia, seu estilo ou seus ensinamentos conhecidos. A atribuição exige uma passagem identificável. Se a passagem não foi localizada, a interpretação deve ser marcada como atribuição não verificada ou apresentada sem atribuição pessoal.

### 5.4. Dicionários e referências lexicográficas

São utilizados para esclarecer:

- significado lexical;
- amplitude semântica;
- formas gramaticais;
- usos contextuais;
- sentidos técnicos;
- relações etimológicas, quando pertinentes.

Uma definição de dicionário não determina automaticamente o sentido de uma palavra em um verso.

A escolha lexical deve considerar a construção gramatical, o contexto poético e o uso da palavra na obra e na tradição.

### 5.5. Gramáticas e estudos linguísticos

São utilizados para esclarecer:

- morfologia;
- sintaxe;
- composição nominal;
- particípios;
- formas verbais;
- construções absolutas;
- relações de caso;
- ambiguidade sintática;
- recursos linguísticos relevantes para a interpretação.

Quando uma interpretação depender de uma análise gramatical específica, a referência utilizada deve ser registrada.

### 5.6. Obras teológicas

São utilizadas para fundamentar conceitos e distinções doutrinárias.

A consulta deve considerar:

- contexto da afirmação;
- terminologia utilizada;
- relação com outras passagens da obra;
- posição do autor na tradição;
- distinção entre exposição doutrinária e aplicação contemplativa.

Uma obra teológica pode fundamentar a compreensão de um conceito sem necessariamente comentar o verso investigado.

### 5.7. Estudos acadêmicos e referências complementares

Podem contribuir para:

- história textual;
- crítica editorial;
- contexto histórico;
- análise literária;
- filologia;
- transmissão manuscrita;
- comparação de interpretações.

Devem ser identificados como estudos acadêmicos ou referências complementares, sem receber automaticamente o mesmo estatuto de um texto primário ou de um comentário tradicional.

Sua utilização deve considerar a metodologia, o escopo e os limites do estudo.

---

## 6. Hierarquia funcional e resolução de conflitos

Não existe uma hierarquia única capaz de resolver todas as divergências entre fontes.

A avaliação deve considerar a natureza da questão.

| Questão | Fonte prioritária |
|---|---|
| O que o autor escreveu? | Texto original e edição identificada |
| Qual é a construção gramatical? | Texto original, gramáticas e estudos linguísticos |
| Qual é o sentido lexical possível? | Dicionários e usos contextuais |
| Como o verso foi traduzido? | Traduções identificadas, confrontadas com o original |
| Como um comentarista interpreta a passagem? | Comentário tradicional diretamente consultado |
| Qual é o fundamento de um conceito teológico? | Obras teológicas pertinentes |
| Qual é o desenvolvimento de uma interpretação na tradição? | Conjunto de fontes tradicionais documentadas |
| Qual é a sugestão poética ou contemplativa? | Texto, contexto, composição e fundamentos pertinentes |

Quando duas fontes divergirem, não se deve escolher automaticamente a mais conveniente para a interpretação desejada.

O procedimento será:

1. identificar precisamente a divergência;
2. determinar a natureza da questão;
3. verificar se as fontes tratam do mesmo problema;
4. examinar a edição e o contexto de cada passagem;
5. avaliar os fundamentos apresentados;
6. registrar a conclusão ou preservar a divergência como questão aberta.

Uma divergência não resolvida deve permanecer visível no dossiê do núcleo.

---

## 7. Procedimento de consulta

Toda consulta relevante deve seguir uma sequência de trabalho.

### 7.1. Identificar a necessidade

Antes de consultar uma fonte, registrar qual questão está sendo investigada.

Exemplos:

- esclarecer a função de um particípio;
- determinar a relação sintática entre duas expressões;
- verificar uma variante textual;
- confirmar uma interpretação tradicional;
- fundamentar o uso de determinado conceito de rasa.

### 7.2. Identificar a fonte adequada

Selecionar a fonte conforme sua função.

Não utilizar uma fonte teológica para resolver isoladamente uma questão gramatical, nem uma definição lexicográfica para estabelecer uma interpretação confidencial.

### 7.3. Consultar a passagem

Registrar a localização exata:

- obra;
- capítulo;
- verso;
- seção;
- página;
- volume;
- número de nota;
- outro identificador pertinente.

A localização deve permitir que outra pessoa encontre a passagem.

### 7.4. Registrar o conteúdo relevante

Preservar:

- trecho original, quando necessário;
- tradução;
- explicação;
- contexto;
- observações do investigador.

Quando uma passagem for resumida, o resumo deve permanecer fiel ao conteúdo da fonte.

### 7.5. Avaliar sua contribuição

Registrar o que a fonte efetivamente esclarece e o que permanece sem resposta.

Não atribuir à fonte conclusões que foram produzidas pelo próprio investigador.

### 7.6. Incorporar à investigação

A informação deverá ser incorporada ao dossiê do núcleo, à síntese integrada ou ao comentário, conforme sua relevância.

A consulta não deve ficar isolada do processo interpretativo.

---

## 8. Registro das referências nos dossiês

Toda fonte utilizada para sustentar uma conclusão relevante deve aparecer no registro do núcleo correspondente.

Formato recomendado:

| Campo | Conteúdo |
|---|---|
| ID da fonte | Identificador do catálogo |
| Localização | Capítulo, verso, página ou seção |
| Questão investigada | Problema que motivou a consulta |
| Conteúdo relevante | Passagem ou síntese fiel |
| Contribuição | O que a fonte esclarece |
| Limitações | O que a fonte não permite concluir |
| Tipo de utilização | Direta, indireta ou contextual |
| Estado de verificação | Confirmada, parcial ou não verificada |

A mesma fonte poderá ser utilizada em diferentes núcleos. Não é necessário duplicar seu cadastro no catálogo; cada dossiê deverá registrar sua própria localização e contribuição.

---

## 9. Estados de verificação das fontes

Cada referência relevante deve receber um estado.

### 9.1. Verificada diretamente

A fonte foi consultada e a passagem correspondente foi localizada.

É o estado preferencial para afirmações textuais e atribuições específicas.

### 9.2. Verificada parcialmente

A fonte foi consultada, mas a passagem ou o contexto necessário não pôde ser examinado integralmente.

A limitação deve ser explicitada.

### 9.3. Conhecida indiretamente

A informação foi encontrada em outra publicação que cita ou resume a fonte original.

Deve-se identificar a fonte intermediária e evitar apresentar a afirmação como resultado de consulta direta.

### 9.4. Não verificada

A referência foi mencionada, mas não foi possível confirmar seu conteúdo ou localização.

Não pode sustentar uma atribuição específica como fato estabelecido.

### 9.5. Inadequada ou descartada

A fonte foi examinada e considerada inadequada para a questão investigada, ou sua informação foi descartada por problemas identificados.

O motivo deve ser registrado quando a fonte já tiver influenciado a investigação.

---

## 10. Citações e atribuições

### 10.1. Citação direta

Utilizar quando a formulação original for relevante para a investigação.

Deve conter:

- identificação da fonte;
- localização precisa;
- texto citado;
- indicação de tradução, quando aplicável.

Uma tradução própria deve ser identificada como tal.

### 10.2. Paráfrase

Quando a ideia for apresentada com palavras do investigador, deve-se preservar o sentido da fonte e indicar sua localização.

A paráfrase não pode ampliar silenciosamente o alcance da afirmação.

### 10.3. Tradução de trabalho

Quando o investigador traduzir uma passagem para fins de análise, deve registrar:

- texto original;
- tradução proposta;
- decisões lexicais relevantes;
- ambiguidades;
- alternativas consideradas.

A tradução de trabalho não deve ser confundida com uma tradução publicada.

### 10.4. Atribuição a autores e ācāryas

Uma afirmação só poderá ser apresentada como posição de determinado autor quando houver evidência documental suficiente.

Se a informação for conhecida apenas por fonte secundária, a mediação deve ser indicada.

Se a atribuição não puder ser verificada, utilizar formulações que não atribuam indevidamente a afirmação ao autor.

---

## 11. Variantes textuais e divergências editoriais

Quando forem identificadas variantes entre edições, transcrições ou testemunhos textuais, registrar:

1. forma adotada;
2. forma alternativa;
3. fonte de cada leitura;
4. natureza da divergência;
5. impacto gramatical;
6. impacto semântico;
7. impacto na interpretação;
8. decisão provisória ou final.

Não se deve alterar a transcrição original para fazê-la coincidir com uma tradução ou interpretação.

Quando não houver elementos suficientes para decidir, manter a variante como questão aberta.

Uma variante sem impacto interpretativo relevante pode ser registrada sem exigir reabertura de toda a investigação.

---

## 12. Fontes digitais, arquivos e materiais incompletos

Materiais digitais devem ser identificados com o máximo de precisão possível.

Registrar, quando disponíveis:

- endereço de origem;
- data de acesso;
- identificação da edição;
- responsável pela digitalização;
- indicação de páginas ausentes;
- qualidade da reprodução;
- eventuais problemas de OCR;
- integridade do arquivo.

Uma transcrição obtida por OCR não deve ser tratada automaticamente como texto confiável. Passagens decisivas devem ser confrontadas com a imagem da página ou com uma edição verificável.

Quando um PDF estiver incompleto, ilegível ou sem identificação editorial, isso deve ser registrado.

Não se deve inferir o conteúdo de páginas não consultadas.

---

## 13. Fontes não localizadas e lacunas documentais

Quando uma referência for mencionada, mas não puder ser localizada, o procedimento será:

1. registrar a referência tal como foi recebida;
2. identificar a informação que se pretendia confirmar;
3. registrar as tentativas de localização;
4. procurar fontes intermediárias, se necessário;
5. distinguir a informação conhecida daquilo que permanece sem confirmação;
6. manter a questão aberta.

A ausência de confirmação não autoriza afirmar que a fonte não existe.

Também não autoriza preencher a lacuna com uma citação presumida ou uma atribuição baseada apenas em familiaridade doutrinária.

---

## 14. Fontes novas durante a investigação

A descoberta de uma nova fonte pode exigir a revisão de uma conclusão anterior.

Nesse caso:

- registrar a nova fonte no catálogo;
- identificar os núcleos e conclusões potencialmente afetados;
- avaliar se a fonte acrescenta, confirma, limita ou contradiz a interpretação;
- revisar somente os pontos afetados;
- preservar os resultados que não dependem da nova evidência;
- atualizar os registros de continuidade e validação, quando necessário.

A nova fonte não deve ser incorporada automaticamente apenas por ser mais recente ou mais extensa. Sua pertinência e confiabilidade devem ser avaliadas.

---

## 15. Proibição de fabricação ou normalização de evidências

É proibido:

- inventar referências bibliográficas;
- inventar páginas, capítulos ou versos;
- reconstruir citações como se tivessem sido consultadas;
- apresentar uma tradução própria como tradução publicada;
- atribuir a um autor uma interpretação sem evidência;
- omitir que uma informação foi obtida indiretamente;
- corrigir silenciosamente uma fonte;
- transformar uma hipótese em citação ou conclusão documentada.

Quando houver incerteza, ela deve ser explicitada.

A precisão documental tem prioridade sobre a aparência de completude.

---

## 16. Relação entre fontes e níveis interpretativos

A utilização das fontes deve respeitar os cinco níveis de fundamentação definidos pelo Método de Análise Rasika da Līlā.

| Nível | Papel das fontes |
|---|---|
| Significado textual | Texto original, edição e referências linguísticas |
| Sugestão contextual ou poética | Texto, composição, contexto e estudos pertinentes |
| Fundamentação doutrinária | Obras teológicas e fontes tradicionais |
| Comentário tradicional documentado | Comentários consultados diretamente ou por mediação explicitada |
| Contemplação rasika | Integração dos fundamentos anteriores, com identificação das inferências contemplativas |

A contemplação rasika não precisa ser reduzida a uma citação externa. Entretanto, deve permanecer coerente com o texto, com a tradição e com os fundamentos estabelecidos.

Quando uma contemplação for uma inferência própria, ela deve ser reconhecida como tal.

---

## 17. Responsabilidade e rastreabilidade do processo

O assistente deve:

- identificar quando uma afirmação exige consulta a uma fonte;
- distinguir conhecimento geral de informação documentalmente verificada;
- não simular consulta;
- registrar limitações de acesso;
- indicar a localização das passagens consultadas;
- preservar divergências relevantes;
- evitar atribuições não comprovadas;
- informar quando uma conclusão depende de inferência própria.

O usuário deve poder revisar a relação entre uma conclusão e as fontes que a sustentam.

Uma referência não deve ser considerada validada apenas porque aparece em uma resposta anterior do assistente.

---

## 18. Relação com os demais documentos

| Documento | Responsabilidade |
|---|---|
| `AGENTS.md` | Regras operacionais e governança do repositório |
| `metodo-analise-rasika-v5.md` | Princípios e operações da investigação |
| `criterios-de-validacao.md` | Avaliação da qualidade e maturidade dos resultados |
| `orientacao-de-trabalho-v5.md` | Execução do fluxo de investigação; proposta em elaboração |
| `protocolo-de-continuidade.md` | Preservação do estado e retomada do trabalho |
| `catalogo-de-fontes.md` | Cadastro central das fontes |
| Modelos de `modelos/` | Estrutura dos registros e artefatos |

Este protocolo define como as fontes devem ser utilizadas. O catálogo registra quais fontes estão disponíveis. Os dossiês registram como cada fonte contribuiu para uma investigação específica.

Essas funções não devem ser duplicadas.

---

## 19. Condição de aprovação deste documento

Esta proposta estará pronta para aprovação quando:

- as classes de fontes estiverem suficientemente definidas;
- os identificadores forem compatíveis com a estrutura do repositório;
- a hierarquia funcional estiver clara;
- os estados de verificação forem aplicáveis;
- as regras de atribuição e citação forem suficientemente rigorosas;
- o tratamento de variantes e divergências estiver definido;
- os modelos de núcleo e validação permitirem registrar as fontes sem duplicação;
- o protocolo puder ser aplicado tanto a obras em sânscrito quanto a comentários, traduções e referências teológicas.

**Estado atual:** proposta para revisão e aprovação. Não constitui ainda norma definitiva do repositório.
