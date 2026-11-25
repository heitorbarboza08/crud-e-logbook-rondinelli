# 📓 LOGBOOK AFP — Algoritmos e Programação (2026.2)

> **Como usar este arquivo:** copie-o para a raiz do **seu** repositório (ou para `logbook/LOGBOOK.md`) e preencha **direto no GitHub** (botão ✏️ *Edit this file*) ou no VS Code. Ele reúne todos os instrumentos do Protocolo AFP 2026.2 (Logbook Individual — Campos 01 a 04, 06 e 07; Registro de Revisão por Pares — Campo 05; Checkpoint Conceitual; Rubrica de Defesa Técnica).
>
> **Organização:** o Logbook está dividido em **3 grupos de entrega**, cada um com seu prazo. Dentro de cada grupo, os **ciclos de entrega (01 a 12)** continuam os mesmos, com as orientações de preenchimento. Siga a ordem: **Grupo 1 → Grupo 2 → Grupo 3 → Defesa Técnica**.
>
> O `Diario.md` do checklist passa a ser **este arquivo**: o registro de cada ciclo está na seção do ciclo correspondente.

## 📍 Navegação rápida

| Seção | Prazo |
|---|---|
| [👨‍🎓 Identificação](#-identificação) | Hoje |
| [🟢 Grupo 1](#-grupo-1--prazo-segunda-1611-às-23h59) · Registros 01–04, Campos 01 e 02 | **Segunda 16/11, 23h59** |
| [🟠 Grupo 2](#-grupo-2--prazo-sábado-2111-às-23h59) · Registros 05–08, Checkpoint, Campos 03 e 04 | **Sábado 21/11, 23h59** |
| [🔵 Grupo 3](#-grupo-3--prazo-quinta-2611-às-23h59) · Registros 09–12, Campos 05, 06 e 07 | **Quinta 26/11, 23h59** |
| [🏁 Defesa Técnica](#-defesa-técnica--quarta-1811) | **Quarta 18/11** |
| [🆘 Estou atrasado](#-estou-atrasado-no-logbook-e-agora) | — |

---

## 👨‍🎓 Identificação

| Campo | Preencha |
|---|---|
| **Nome do estudante** | Heitor França Barboza |
<<<<<<< HEAD
| **Curso / Módulo** | Sistema de Informação · 2º período |
| **Unidade curricular** | Algoritmos e Programação — UnDB 2026.2 |
| **Professor** | Rondineli Seba Salomão |
| **App-base do meu CRUD** | Sistema de gerenciamento de tarefas, projetos e colaboradores (Membro, Projeto, Tarefa) |
| **Link do meu repositório** | https://github.com/heitorbarboza08/crud-e-logbook-rondinelli |
=======
| **Curso / Módulo** | Sistema de Informação · 2º período_ |
| **Unidade curricular** | Algoritmos e Programação — UnDB 2026.2 |
| **Professor** | Rondineli Seba Salomão |
| **App-base do meu CRUD** | Um sistema simples de gerenciamento de tarefas e projetos |
| **Link do meu repositório** | https://github.com/heitorbarboza08/codigo-crud-rondinelli/blob/main/crud |
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c
| **Dupla de revisão (Campo 05)** | Felipe Couto Lamar |
| **Função neste ciclo** | _Autor do meu CRUD · Revisor do CRUD de um colega_ |

---

## 🧭 Regras de ouro (leia antes de preencher)

1. **Processo, não resultado.** O Logbook mostra *como você pensou*, não só o que funcionou. Registre erros, desvios e dúvidas reais.
2. **Vocabulário técnico.** Use os termos da área (ex.: "laço de repetição", "validação de entrada", "estrutura de dados"). Respostas genéricas ("aprendi Python") não são aceitas.
3. **Todo registro relevante tem 3 âncoras:** o **objeto de conhecimento** mobilizado + a **justificativa técnica** + a **referência/fonte**. *Decisão sem objeto de conhecimento e sem referência é considerada não rastreável e não conta para a avaliação formativa.*
4. **Coerência entre campos.** O Campo 02 deve ser coerente com o Campo 01. *Incoerência é evidência de autoria externa.* O Campo 07 retoma o Campo 01.
5. **IA é permitida e avaliada (Campo 04).** *Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.* Você precisa mostrar o que aceitou **e** o que questionou/descartou, com argumento técnico.
6. **O histórico do Git é a sua evidência.** Faça commits pequenos e frequentes. Nunca reescreva o histórico (`force push`) do arquivo do Logbook.
7. **Campo 01 e Checkpoint são "sem consulta".** Preencha em um bloco contínuo, sem internet, sem material e sem colegas, no tempo indicado (Campo 01: durante o laboratório; Checkpoint: 20 min). Depois **não edite** esses campos — se perceber um erro, corrija em um campo posterior (Campo 03 ou 07), explicando.
8. **Os prazos dos grupos (16/11, 21/11 e 26/11, às 23h59)** valem para o commit no GitHub. O horário do commit é o registro oficial.

### ✅ Padrão de commit do Logbook

```text
docs(logbook): campo 01 — ciclo 02
docs(logbook): registro do ciclo 05
docs(logbook): campo 05 — revisão do CRUD de <colega>
```

---

## 🗓️ Calendário de entregas e Defesa

Os grupos têm **5 dias entre um prazo e outro**. O horário do commit no GitHub é o registro oficial.

| Grupo | Janela de preenchimento | **Prazo** | O que entregar |
|:--:|---|---|---|
| **1** | Qua 11/11 → seg 16/11 | **Segunda 16/11, 23h59** | Identificação · Registros dos Ciclos 01 a 04 · Campo 01 · Campo 02 |
| **2** | Seg 16/11 → sáb 21/11 | **Sábado 21/11, 23h59** | Registros dos Ciclos 05 a 08 · Checkpoint Conceitual · Campo 03 · Campo 04 |
| **3** | Sáb 21/11 → qui 26/11 | **Quinta 26/11, 23h59** | Registros dos Ciclos 09 a 12 · Campo 05 (2 revisões) · Campo 06 · Campo 07 |
| 🏁 | — | **Quarta 18/11** | **Defesa Técnica individual** (Rubrica) |

### Linha do tempo

| Data | Evento |
|---|---|
| Qua 11/11 | **Hoje:** começa o Grupo 1 |
| Seg 16/11 | ✅ Prazo do **Grupo 1** |
| **Qua 18/11** | 🏁 **Defesa Técnica** |
| Sáb 21/11 | ✅ Prazo do **Grupo 2** |
| Qua 25/11 | Avaliação P2 |
| Qui 26/11 | ✅ Prazo do **Grupo 3** |
| Qua 02/12 | Avaliação Substitutiva |
| Qua 09/12 | Avaliação Final |

> ⚠️ **Atenção:** a Defesa Técnica (18/11) acontece **antes** dos prazos dos Grupos 2 e 3. Na defesa você será arguido sobre **o que já estiver registrado e commitado**. Veja a seção [Defesa Técnica](#-defesa-técnica--quarta-1811) para saber o que priorizar até 18/11.

### Ciclos de entrega por grupo

| Ciclo | Data da aula | Tema do ciclo | Grupo | O que preencher |
|:--:|:--:|---|:--:|---|
| 01 | 12/08 | Preparação do laboratório e escolha do projeto | **1** | Registro do Ciclo |
| 02 | 19/08 | Variáveis, tipos de dados, entrada/saída | **1** | Registro + **Campo 01** + **Campo 02** |
| 03 | 26/08 | Operadores, fluxogramas, paradigmas | **1** (registro) · **2** (campos) | Registro (G1) · **Checkpoint**, **Campo 03**, **Campo 04** (G2) |
| 04 | 02/09 | Condicionais: `if`, `elif`, `else` | **1** | Registro do Ciclo |
| 05 | 09/09 | Condicionais aninhadas e operadores lógicos | **2** | Registro do Ciclo |
| 06 | 30/09 | Repetição: `for`, `while`, `break`, `continue` | **2** | Registro do Ciclo (inclui devolutiva da P1) |
| 07 | 07/10 | Listas: armazenamento e iteração | **2** | Registro do Ciclo |
| 08 | 14/10 | Busca e introdução a dicionários/matrizes | **2** | Registro do Ciclo |
| 09 | 21/10 | Atualização e exclusão: CRUD completo | **3** | Registro + **Campo 05** (revisão nº 1) |
| 10 | 28/10 | Modularização: funções | **3** | Registro do Ciclo |
| 11 | 04/11 | Recursividade | **3** | Registro + **Campo 06** |
| 12 | 11/11 | Refatoração e qualidade de código | **3** | Registro + **Campo 05** (revisão nº 2) + **Campo 07** |

---

## 📊 Painel de acompanhamento

Atualize a cada commit (troque ⬜ por ✅).

| Grupo | Item | Prazo | Preenchido | Commit |
|:--:|---|---|:--:|:--:|
<<<<<<< HEAD
| 1 | Identificação | 16/11 | ✅ | ✅ |
| 1 | Registros dos Ciclos 01, 02, 03 e 04 | 16/11 | ✅ | ✅ |
| 1 | Campo 01 — Instrumento de entrada | 16/11 | ✅ | ✅ |
| 1 | Campo 02 — Aprofundamento | 16/11 | ✅ | ✅ |
| 2 | Registros dos Ciclos 05, 06, 07 e 08 | 21/11 | ✅ | ✅ |
| 2 | Checkpoint Conceitual | 21/11 | ✅ | ✅ |
| 2 | Campo 03 — Execução e desvios | 21/11 | ✅ | ✅ |
| 2 | Campo 04 — Interação com IA | 21/11 | ✅ | ✅ |
| 3 | Registros dos Ciclos 09, 10, 11 e 12 | 26/11 | ✅ | ✅ |
| 3 | Campo 05 — Revisão por pares nº 1 e nº 2 | 26/11 | ✅ | ✅ |
| 3 | Campo 06 — Próximos passos | 26/11 | ✅ | ✅ |
| 3 | Campo 07 — Evolução conceitual | 26/11 | ✅ | ✅ |
| 🏁 | Defesa Técnica | 18/11 | ⬜ | — |

---

## ❓ A questão-problema da AFP

**Título:** *O sistema em produção: diagnosticando as falhas do CRUD que você mesmo construiu.*

> **Enunciado completo (Apêndice A):** _professor(a): cole aqui o enunciado e os anexos liberados conforme o cronograma._

A questão-problema é **a mesma durante todo o semestre**: ela se aplica ao **seu** CRUD, que cresce a cada ciclo. Os **dados com defeito** do seu app chegam em um **lote cumulativo único** e vão expondo problemas diferentes conforme sua estrutura evolui. Seu trabalho é diagnosticar, ajustar o CRUD para tratar cada falha e **registrar o raciocínio** neste Logbook.

---

# 🔁 REGISTRO DO CICLO — modelo (copie em cada ciclo)

Cada ciclo tem sua própria seção abaixo, já com o modelo. Se precisar de espaço extra, acrescente linhas.

```markdown
### Registro do Ciclo NN — DD/MM
1. **Desafio do ciclo (em 1 frase):**
2. **O que implementei (commits / arquivos / links):**
3. **Objeto(s) de conhecimento mobilizado(s) (vocabulário técnico):**
4. **Desvio ou erro encontrado + causa técnica:**
5. **Decisão de ajuste + fonte (livro, doc, vídeo, colega, IA):**
6. **Feedback recebido (professor/colega) e o que mudei por causa dele:**
7. **Próximo passo:**
```

**Como preencher bem:** escreva como se explicasse a um colega que não esteve na aula. O item 3 e o item 5 são os mais importantes: eles ligam o que você fez ao **conteúdo** e à **fonte**.

| ❌ Fraco | ✅ Forte |
|---|---|
| "Aprendi a usar `if`." | "Usei estrutura condicional aninhada para validar a idade antes de cadastrar. Meu erro foi comparar `str` com `int` (resultado de `input()`); corrigi com `int()` (Pense em Python, cap. 2)." |
| "Deu erro e consertei." | "O programa quebrou com `ZeroDivisionError` ao calcular a média de um item sem avaliações. Causa: divisão por `len(lista)` com lista vazia. Ajuste: testar `if len(lista) > 0`." |

---

# 🟢 GRUPO 1 — prazo segunda 16/11 às 23h59

> **Janela:** quarta 11/11 → segunda 16/11. **O que entregar:** Identificação · Registros dos Ciclos 01, 02, 03 e 04 · Campo 01 · Campo 02.
>
> **Sugestão de ordem:** (1) Identificação → (2) **Campo 01 primeiro, sem consulta** → (3) Registros dos Ciclos 01 a 04 → (4) Campo 02, com pesquisa.

**Checklist do Grupo 1**
- [ ] Identificação preenchida (app-base, link do repositório, dupla de revisão)
- [ ] Campo 01: 3 objetos de conhecimento, 3 lacunas, hipótese de até 5 linhas
- [ ] Registros dos Ciclos 01, 02, 03 e 04 com os 7 itens
- [ ] Campo 02: 2 referências com contribuição, hipótese revisada, 3 recursos
- [ ] Commits no GitHub e painel atualizado

## 🟢 CICLO 01 — 12/08 — Preparação do laboratório e escolha do projeto

<details>
<summary>📘 Orientações do Ciclo 01</summary>

- **Hoje não há Campo do Protocolo.** O foco é preparar o ambiente: criar o repositório, configurar o VS Code e escolher o **app-base** do seu CRUD (e, portanto, o *schema* dos seus dados).
- Preencha a **Identificação** (no início deste arquivo) e o **Registro do Ciclo 01**.
- No item 3, registre **o que você já sabia** e o que era novo (Git, GitHub, VS Code). Isso será útil para o Campo 07.
- No item 4, registre qualquer problema de instalação ou configuração e como o resolveu — isso conta como desvio.
- Faça o primeiro commit: `docs(logbook): registro do ciclo 01`.
</details>

#### Registro do Ciclo 01 — 12/08
1. **Desafio do ciclo (em 1 frase):**   

    Tornar o código legível e funcional

2. **O que implementei (commits / arquivos / links):**  

    Implementado um arquivo .md  em um repositório no GitHub dedicado ao CRUD

3. **Objeto(s) de conhecimento mobilizado(s):**

<<<<<<< HEAD
    O que eu já sabia: Sintaxe básica do Python, manipulação de arquivos locais, estruturação de documentos em Markdown (.md) e navegação básica no editor de código VS Code.

    O que era novo: Controle de versão distribuído com Git (git init, git add, git commit, git push, git pull), padronização de histórico via Conventional Commits (docs(logbook):), vinculação de repositório local a
    remoto no GitHub (remote add origin), configuração do terminal integrado no VS Code e definição de schema inicial de dados para um sistema CRUD em memória (Membro, Projeto e Tarefa).
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c

4. **Desvio ou erro encontrado + causa técnica:** 

    "Deu erro e consertei." | "O programa gerou IDs duplicados ao cadastrar um novo membro após excluir outro registro. Causa: cálculo do novo ID baseado no tamanho dinâmico da lista (len(lista) + 1), que diminui após uma remoção. Ajuste: buscar o maior ID existente com max(item.id for item in lista) + 1 (ou usar um contador sequencial independente)."

5. **Decisão de ajuste + fonte:** 

    Optei por manter um contador incremental dedicado (proximo_id) no lugar de len(lista) + 1 (e da verificação via max()), pois assim mesmo que o último item da lista seja excluído, nenhum ID anterior é reutilizado e tarefas antigas não correm risco de apontar para um novo cadastro. Fonte: Boas práticas de modelagem de chaves primárias (AUTO_INCREMENT em bancos relacionais) e documentação oficial do Python sobre gerenciamento de estado e estruturas mutáveis.

6. **Feedback recebido e o que mudei:**  

    Recebi o alerta de que, além da colisão de IDs, a exclusão de um membro deixava tarefas antigas com referências órfãs (t.membro apontando para um ID inexistente) e que o int(input()) quebrava o programa se o usuário digitasse texto. O que mudei: Implementei o contador sequencial fixo para IDs, bloqueei a remoção de colaboradores que ainda possuem tarefas vinculadas em remover_membro() e adicionei blocos try/except ValueError nas entradas numéricas do menu e cadastros.

7. **Próximo passo:** 

    Implementar persistência de dados em arquivo (json ou sqlite3) para que os registros de membros, projetos e tarefas 
    não sejam perdidos ao encerrar o programa, além de criar testes unitários básicos com unittest ou pytest para validar 
    o fluxo de cadastro e exclusão.


## 🟢 CICLO 02 — 19/08 — Variáveis, tipos de dados e entrada/saída

<details>
<summary>📘 Orientações do Ciclo 02 — Campo 01 (sem consulta) e Campo 02 (pesquisa)</summary>

**Campo 01 — Instrumento de entrada** · *sem consulta · faça primeiro*
- Preencha **antes de tudo**, em um bloco contínuo de cerca de 15 minutos, sem internet, sem material, sem IA e sem colegas, depois de conhecer a questão-problema e a primeira amostra de dados do seu app. Depois do Campo 01 você pode consultar o que quiser.
- **1a.** Liste pelo menos **3 objetos de conhecimento** que você acha que precisa dominar para resolver o problema. Use o vocabulário técnico da área. *Não precisa acertar tudo — o Campo 07 vai mostrar o quanto você evoluiu.*
- **1b.** Liste pelo menos **3 lacunas**: o que você **não sabe** e precisa descobrir, com precisão (ruim: "não sei programar"; bom: "não sei como validar a entrada para impedir que o usuário digite texto onde espero número").
- **1c.** Escreva sua **hipótese inicial** em até 5 linhas: o que você acha que está causando as falhas do CRUD e por quê.
- Faça o commit **logo ao terminar**. Depois, **não edite** o Campo 01.

**Campo 02 — Aprofundamento** · *AV Qualis · segunda 16/11, 23h59*
- Preencha **depois do Campo 01, com pesquisa real**, e seja coerente com ele.
- **2a.** Pelo menos **2 referências** (livro, documentação, vídeo, artigo), cada uma com a **contribuição** concreta para a sua solução. Não basta listar o título.
- **2b.** **Hipótese revisada:** o que mudou em relação ao Campo 01 e **por quê**. Se não mudou nada, explique por que a pesquisa confirmou a hipótese.
- **2c.** **Dimensionamento inicial de recursos** (mínimo 3 itens), com quantidade estimada e justificativa técnica. Exemplos de recursos no seu contexto: horas de estudo, número de casos de teste, módulos/arquivos do projeto, dados de teste, bibliotecas.
</details>

### 🧩 CAMPO 01 — Instrumento de entrada
*Grupo 1 | Prazo segunda 16/11, 23h59 | SEM CONSULTA*

**1a. Objetos de conhecimento identificados (mínimo 3, com vocabulário técnico):**
<<<<<<< HEAD

=======
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c
1. Modelagem de dados em memória e coleções: Uso de dataclasses, listas de objetos, ordenação com sorted() e funções anônimas (lambda).
2. Controle de estado e chaves primárias: Lógica de geração de identificadores únicos (ID) e manutenção da integridade referencial entre entidades relacionadas (Membro, Projeto e Tarefa).
3. Tratamento de exceções e validação de entradas (I/O): Captura de erros em tempo de execução (ValueError) e sanitização de dados recebidos via input().
4. Programação funcional aplicada a relatórios: Filtragem e agregação de dados utilizando list comprehensions, map() e fatiamento (slicing) de listas.

**1b. Lacunas — o que não sei e preciso descobrir (mínimo 3, com precisão técnica):**
<<<<<<< HEAD

=======
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c
1. Não sei como garantir que a geração de IDs continue sequencial e única sem reutilizar números antigos quando um registro intermediário é excluído da lista.
2. Não sei como impedir a exclusão de um colaborador (remover_membro) caso já exista alguma tarefa vinculada ao seu ID, evitando referências órfãs.
3. Não sei qual é a estrutura ideal em Python para validar se os IDs de membro e projeto informados na criação da tarefa realmente existem nos repositórios antes de instanciar o objeto "Tarefa".

**1c. Hipótese inicial em até 5 linhas — com lógica da área de formação:**

> As falhas do CRUD ocorrem porque as operações de escrita e exclusão manipulam as listas em 
  memória de forma isolada, sem validação de integridade referencial nem controle de estado dos 
  identificadores. Como a função gerar_id() depende diretamente do tamanho atual da lista (len(lista) + 1), 
  qualquer exclusão altera o comprimento da coleção e provoca colisão de chaves primárias nos cadastros 
  seguintes, além de deixar tarefas apontando para registros inexistentes.

### 🧩 CAMPO 02 — Aprofundamento pós-aula
*AV Qualis — Grupo 1 | Segunda 16/11, 23h59*

> **Preenchido depois do Campo 01, com pesquisa real. Deve ser coerente com o Campo 01. Incoerência = evidência de autoria externa.**

**2a. Aprofundamento dos objetos de conhecimento (mínimo 2 referências com síntese da contribuição para a solução):**

<<<<<<< HEAD
- **Referência 1:** Documentação Oficial do Python 3 — Errors and Exceptions (try / except ValueError) e Built-in Functions (any(), max(), next()). 

  — **Contribuição:** Esclareceu como capturar conversões inválidas de texto para int/float no input() sem interromper o loop principal do menu, além de mostrar o uso de expressões geradoras com any(t.membro == codigo for t in tarefas) para verificar vínculos antes de excluir um colaborador.

- **Referência 2:** AMALHO, Luciano. Python Fluente: Programação Clara, Concisa e Eficiente (Capítulo sobre Estruturas de Dados e dataclasses). 

  — **Contribuição:** Fundamentou o entendimento sobre como instâncias de @dataclass são armazenadas por referência em listas mutáveis e por que o uso de um contador sequencial dedicado (em vez de len(lista) + 1) evita a reutilização de chaves primárias e garante a integridade referencial entre Membro, Projeto e Tarefa.

**2b. Hipótese revisada — o que mudou em relação ao Campo 01 e por quê:**

> A pesquisa confirmou a hipótese inicial de que o acoplamento da geração de IDs ao tamanho dinâmico da lista (len(lista) + 1) 
  e a ausência de verificação de vínculos causam colisões e referências órfãs. O que mudou após o estudo foi a percepção de 
  que a solução não exige apenas trocar len() por max() — pois excluir o último item ainda reutilizaria o ID —, mas sim adotar 
  contadores sequenciais independentes por entidade, combinados com funções auxiliares de validação (localizar_por_id antes de criar tarefas, 
  bloqueio via any() na exclusão e blocos try/except ValueError nas entradas numéricas).

**2c. Dimensionamento inicial de recursos (recurso, quantidade estimada, justificativa técnica — mínimo 3 itens):**

|   RECURSO / MATERIAL / INSUMO   |     QUANTIDADE ESTIMADA     |          JUSTIFICATIVA TÉCNICA           |

|  Horas de estudo e implementação  |        6 horas        | Tempo necessário para revisar documentação sobre  |
                                                              exceções/estruturas de dados (2h), 
                                                              refatorar as funções do CRUD (2h30) e executar 
                                                              testes manuais de borda (1h30).

|   Módulos / arquivos do projeto   | 2 arquivos (crud.py   | Separação entre o código-fonte executável do      |
                                      e (logbook algoritmos   gerenciador de tarefas e o registro técnico 
                                       e programacao.md))     versionado no repositório Git.       

|   Casos de teste funcionais e de  |  8 cenários de teste  | Cobertura mínima para validar cadastro, exclusão  |
                                                              com re-cadastro (teste de colisão de ID), tentativa 
                                                              de remover membro com tarefa ativa, IDs inexistentes 
                                                              e entradas não numéricas (ValueError)..     

|   Massa de dados de teste (seed)	| 3 membros, 2 projetos | Volume mínimo de registros em memória para testar |
                                        e 4 tarefas	          relacionamentos múltiplos, filtros de conclusão e 
                                                              fatiamento (tarefas[-3:]) no painel de métricas.
                                        

#### Registro do Ciclo 02 — 19/08
1. **Desafio do ciclo (em 1 frase):** 

    Diagnosticar as falhas estruturais de geração de IDs, integridade referencial e validação 
    de tipos de entrada no CRUD em memória e fundamentar as correções via documentação técnica.

2. **O que implementei (commits / arquivos / links):** 

    Preenchimento do Campo 01 e Campo 02 no logbook algoritmos e programacao.md e 
    revisão das funções gerar_id(), remover_membro() e criar_tarefa() no arquivo crud do 
    repositório codigo-crud-rondinelli.

3. **Objeto(s) de conhecimento mobilizado(s):** 

    Tipos primitivos (int, float, str), conversão explícita de tipos, @dataclass, Enum, 
    controle de fluxo, tratamento de exceções (ValueError) e funções agregadoras 
    (any(), len(), map()).

4. **Desvio ou erro encontrado + causa técnica:**
 
    "Deu erro e consertei." | "O programa gerou IDs duplicados ao cadastrar um novo membro após excluir outro registro. 
     Causa: cálculo do novo ID baseado no tamanho dinâmico da lista (len(lista) + 1), que diminui após uma remoção. 
     Ajuste: substituir a dependência de len() por um contador incremental dedicado (proximo_id)."

5. **Decisão de ajuste + fonte:** 

    Optei por utilizar contadores incrementais independentes por entidade em vez de max(item.id) + 1 para impedir a 
    reutilização de IDs mesmo quando o último item da lista é removido, além de validar chaves estrangeiras com 
    localizar_por_id() antes de criar tarefas. Fonte: Documentação oficial do Python 3 (Built-in Functions e Data Structures).

6. **Feedback recebido e o que mudei:** 

    Identifiquei que, além da duplicidade de IDs, faltava proteger o sistema contra entradas inválidas no input() e 
    impedir a exclusão de membros com tarefas ativas; planejei a inclusão de try/except ValueError e checagem com 
    any() antes da remoção.

7. **Próximo passo:** 

    Aplicar no código Python as validações de entrada (try/except) e o bloqueio de integridade referencial em 
    remover_membro(), rodando os 8 casos de teste planejados e registrando o commit fix(crud): corrige geracao 
    de ID's e validação de entradas.
=======
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c

## 🟢 CICLO 03 — 26/08 — Operadores, fluxogramas e paradigmas

<details>
<summary>📘 Orientações do Ciclo 03 — Registro (Grupo 1)</summary>

- Neste grupo você preenche **apenas o Registro do Ciclo 03**. O **Checkpoint Conceitual** e os **Campos 03 e 04** deste ciclo estão no **Grupo 2**.
- Item 3: nomeie os **operadores** (aritméticos, relacionais, lógicos) e os **tipos** que usou. Se montou fluxogramas, cite o que o fluxograma ajudou a perceber.
- Item 4: registre erros de precedência de operadores, divisão por zero ou confusão entre `=` e `==`, com a causa técnica.
</details>

#### Registro do Ciclo 03 — 26/08
<<<<<<< HEAD
1. **Desafio do ciclo (em 1 frase):** 

    Mapear o fluxo lógico das operações do CRUD usando operadores aritméticos, relacionais 
    e lógicos, prevenindo falhas de cálculo e comparações incorretas no painel de métricas.

2. **O que implementei (commits / arquivos / links):** 

    Atualização da função relatorio_geral() no arquivo crud.py com cálculo de taxa de conclusão e média de horas por tarefa, 
    além do registro no logbook algortimos e programacao.md (feat(crud): adiciona metricas de media e percentual de conclusao).

3. **Objeto(s) de conhecimento mobilizado(s):** 

    Operadores: Aritméticos (+, /, * para soma incremental de IDs, média de horas e percentual de conclusão), 
    relacionais (==, > para comparar IDs, verificar situacao == Situacao.CONCLUIDA.value e checar listas não vazias) 
    e lógicos (not, in para validar registros ausentes com if not membro: e checar escolhas no dicionário if escolha in opcoes:).

    Tipos e paradigmas: Tipos numéricos (int, float), booleanos (bool), strings (str) e combinação entre paradigma imperativo/procedural 
    (funções de menu e estado) e funcional (map(), lambda e list comprehension).

    Fluxograma: O desenho do fluxo de criar_tarefa() e relatorio_geral() ajudou a perceber caminhos sem saída onde a lista tarefas 
    estava vazia antes de calcular médias.

4. **Desvio ou erro encontrado + causa técnica:** 

    "Deu erro e consertei." | "O programa quebrou com ZeroDivisionError ao calcular a média de horas estimadas e a porcentagem 
    de conclusão no relatorio_geral() com a lista tarefas vazia. 

    Causa: execução direta da expressão (len(concluidas) / len(tarefas)) * 100 sem guarda prévia quando len(tarefas) == 0. 

    Ajuste: condicionar o cálculo a if len(tarefas) > 0:."

5. **Decisão de ajuste + fonte:** 

    Optei por isolar os cálculos de divisão dentro de um bloco condicional de guarda (if len(tarefas) > 0:) e 
    exibir uma mensagem informativa quando não há tarefas cadastradas, além de revisar a precedência com parênteses 
    na fórmula percentual. 

    Fonte: Documentação oficial do Python 3 (Built-in Exceptions — ZeroDivisionError e Operator Precedence).

6. **Feedback recebido e o que mudei:**

    Percebi ao revisar o fluxograma que, além da divisão por zero, usar = dentro de expressões ou confundir 
    objetos Enum (Situacao.CONCLUIDA) com seu valor string (Situacao.CONCLUIDA.value) fazia a comparação relacional == retornar False 
    silenciosamente; padronizei todas as comparações para .value.

7. **Próximo passo:** 

    Optei por isolar os cálculos de divisão dentro de um bloco condicional de guarda (if len(tarefas) > 0:) e exibir 
    uma mensagem informativa quando não há tarefas cadastradas, além de revisar a precedência com parênteses na fórmula percentual. 

    Fonte: Documentação oficial do Python 3 (Built-in Exceptions — ZeroDivisionError e Operator Precedence).
=======
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c

## 🟢 CICLO 04 — 02/09 — Estruturas condicionais: `if`, `elif`, `else`

<details>
<summary>📘 Orientações do Ciclo 04</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 04.
- Conecte **cada condicional** do seu CRUD a uma **regra de negócio** (ex.: "preço não pode ser negativo").
- Se já recebeu o lote de dados com defeito, procure **qual registro quebra qual condição** e registre o item 4 com a **causa técnica** (ex.: valor `None`, texto vazio, número negativo, divisão por zero).
- No item 5, cite a fonte da decisão: livro (*Pense em Python*), documentação ou exercício que você resolveu.
- Compare com o **Campo 02**: o desvio de hoje já estava previsto no seu dimensionamento?
</details>

#### Registro do Ciclo 04 — 02/09
<<<<<<< HEAD
1. **Desafio do ciclo (em 1 frase):** 

    Conectar cada estrutura condicional (if, elif, else) do CRUD a uma regra de negócio explícita 
    para barrar dados inválidos ou inconsistentes antes de alterar as listas em memória.

2. **O que implementei (commits / arquivos / links):**

    Refatoração das funções cadastrar_membro(), cadastrar_projeto(), criar_tarefa(), remover_membro() e 
    atualizar_situacao() em crud.py, vinculando validações de negócio às entradas e atualizando o logbook 
    (fix(crud): aplica validacoes de regras de negocio nas condicionais).

3. **Objeto(s) de conhecimento mobilizado(s):** 

    Estruturas de seleção simples, composta e encadeada (if, elif, else), cláusulas de guarda 
    (early return com if not registro: return), validação de strings vazias (.strip() == ""), 
    validação de domínio numérico (horas <= 0) e integridade referencial entre entidades.

4. **Desvio ou erro encontrado + causa técnica:** 

    "Deu erro e consertei." | "O sistema permitiu cadastrar tarefas com horas_estimadas negativas ou zero (-5.0), nomes em branco ("") e vinculadas a membro_id ou projeto_id inexistentes. 

    Causa: ausência de condicionais verificando o retorno None de localizar_por_id() e falta de checagem de intervalo numérico (horas <= 0) e de string vazia antes do append(). 

    Ajuste: inserir cláusulas de guarda com if not localizar_por_id(...), if not nome.strip() e if horas <= 0:."

5. **Decisão de ajuste + fonte:** 

    Adotei o padrão de cláusulas de guarda (early return) no início das funções de escrita e exclusão para rejeitar entradas inválidas 
    (None, strings vazias ou valores <= 0) antes da persistência em lista, além de usar if / elif / else no menu e na atualização de status. 
    
    Fonte: DOWNEY, Allen B. Pense em Python (Capítulo 5 — Condicionais e recursividade) e exercícios resolvidos em aula sobre validação de invariantes.

6. **Feedback recebido e o que mudei:**

    Comparando com o Campo 02, o desvio envolvendo IDs inexistentes e dados inválidos já estava parcialmente previsto nos 8 casos de teste dimensionados, 
    mas a entrada de horas negativas e strings compostas apenas por espaços exigiu adicionar .strip() e horas <= 0 nas condicionais; 
    também bloqueei a exclusão de membros com tarefas ativas.

7. **Próximo passo:** 

    Refatorar os laços de repetição (while e for) do sistema para garantir menus resilientes a erros de digitação e buscas/listagens mais eficientes.
=======
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_
>>>>>>> b754231bd8512620dfb1b30e03c1c8cfd24a175c

---

# 🟠 GRUPO 2 — prazo sábado 21/11 às 23h59

> **Janela:** segunda 16/11 → sábado 21/11. **O que entregar:** Registros dos Ciclos 05, 06, 07 e 08 · Checkpoint Conceitual · Campo 03 · Campo 04.
>
> ⚠️ O prazo cai num **sábado**: planeje terminar na sexta. Os campos do Ciclo 03 (Checkpoint, 03 e 04) aparecem **primeiro**, porque são a base da investigação.

**Checklist do Grupo 2**
- [ ] Checkpoint Conceitual feito conforme orientação do professor (20 min, sem consulta)
- [ ] Campo 03: 2 achados com objeto, 1 desvio com causa técnica, 1 decisão com fonte
- [ ] Campo 04: ferramenta, pergunta íntegra, resumo, o que aceitei e o que questionei
- [ ] Registros dos Ciclos 05, 06, 07 e 08 com os 7 itens (devolutiva da P1 no ciclo 06)
- [ ] Commits no GitHub e painel atualizado

## 🟠 CICLO 03 (campos) — 26/08 — Checkpoint, Campo 03 e Campo 04

<details>
<summary>📘 Orientações — Checkpoint, Campo 03 e Campo 04 (referentes ao Ciclo 03)</summary>

**Checkpoint Conceitual** · *20 min · sem consulta · conforme orientação do professor*
- Verifica o **seu domínio individual** do conteúdo — não avalia a sua solução. São **3 questões dissertativas**. Quem investiu por conta própria responde com segurança.
- Respostas **genéricas, sem ancoragem técnica, não são aceitas**. Defina o objeto **e** relacione-o ao problema do seu CRUD, explicitando as implicações.
- Critérios: *precisão conceitual*, *relação conteúdo-problema*, *qualidade do raciocínio*.
- Se for insatisfatório, você recebe **feedback escrito em até 48h** e deve ajustar a investigação antes da avaliação somativa.
- Se o professor aplicar o Checkpoint via GitHub, use o arquivo abaixo **só durante os 20 minutos**, com um único commit ao final.

**Campo 03 — Execução e desvios** · *sábado 21/11, 23h59*
- **3a.** Pelo menos **2 achados** que mudaram sua compreensão do problema, cada um com o **objeto de conhecimento** associado.
- **3b.** Pelo menos **1 desvio** em relação ao Campo 02 (o que você planejou e não aconteceu) e a **causa técnica** — não vale "falta de tempo".
- **3c.** Pelo menos **1 decisão de ajuste**, com justificativa e **fonte**, e o objeto de conhecimento mobilizado.

**Campo 04 — Interação com IA** · *sábado 21/11, 23h59 · obrigatório e avaliado*
- Registre **pelo menos uma** interação real com uma IA sobre o seu CRUD.
- **4b.** Transcreva a pergunta **na íntegra** (copie e cole).
- **4c.** Resuma a resposta em **um parágrafo** com as suas palavras.
- **4d.** O que você **aceitou**, ligando ao objeto de conhecimento.
- **4e.** O que você **questionou ou descartou**, com **argumento técnico ou fonte** (teste, documentação, livro). Dica: **rode o código** que a IA sugeriu antes de decidir.
- **Print sem análise crítica = devolução imediata.** Se você aceitou tudo, volte e procure o que verificar.
</details>

### 🧩 CHECKPOINT CONCEITUAL INDIVIDUAL
*20 minutos · sem consulta a qualquer fonte, material ou colega · conforme orientação do professor.*

| | |
|---|---|
| **Nome do estudante** | Heitor Barboza |
| **Data de realização** | 19/11/2026 |
| **Unidade curricular** | Algoritmos e Programação |
| **Professor(a)** | Rondineli Seba Salomão |

> **INSTRUÇÕES:** Responda individualmente, sem consulta. Você tem 20 minutos. As questões avaliam seu domínio dos objetos de conhecimento do componente — não sua solução para o problema. Respostas genéricas sem ancoragem técnica não são aceitas.

**QUESTÃO 1** — Objeto de conhecimento: _…_
> _(Questão elaborada pelo professor na Proposta — Apêndice A, item 6)_

**RESPOSTA:**

> _…_

**QUESTÃO 2** — Objeto de conhecimento: _…_
> _(Questão elaborada pelo professor na Proposta — Apêndice A, item 6)_

**RESPOSTA:**

> _…_

**QUESTÃO 3** — Objeto de conhecimento: _…_
> _(Questão elaborada pelo professor na Proposta — Apêndice A, item 6)_

**RESPOSTA:**

> _…_

<details>
<summary>🔒 Uso do professor — critérios de avaliação do Checkpoint</summary>

| CRITÉRIO | SATISFATÓRIO | INSATISFATÓRIO |
|---|---|---|
| **Precisão conceitual** | Domínio do objeto de conhecimento, com vocabulário técnico adequado e sem erros conceituais relevantes. | Resposta vaga, com erros conceituais ou sem ancoragem nos objetos de conhecimento do componente. |
| **Relação conteúdo-problema** | Conecta o objeto de conhecimento ao problema trabalhado na AFP. | Responde o objeto de forma isolada, sem relação com o problema do ciclo. |
| **Qualidade do raciocínio** | Raciocínio técnico articulado: relaciona o objeto ao problema e explicita implicações para a investigação. | Apenas define o objeto, sem articular raciocínio ou relação com o problema investigado. |

**RESULTADO:** ☐ Satisfatório ☐ Insatisfatório
**AÇÃO DO PROFESSOR:** Checkpoint insatisfatório gera feedback escrito individualizado até 48h — o aluno ajusta a investigação antes da avaliação somativa.
</details>

### 🧩 CAMPO 03 — Execução e desvios
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59*

**3a. O que descobri que mudou minha compreensão do problema (mínimo 2 achados, com objeto de conhecimento associado):**

1. Acoplamento entre o índice da lista e a identidade do registro: Descobri que calcular chaves primárias com len(lista) + 1 (e até mesmo max(item.id) + 1) não garante unicidade temporal em memória, pois a exclusão de registros intermediários ou do último elemento causa reatribuição de IDs e faz tarefas antigas apontarem para novos membros ou projetos. — *Objeto de conhecimento:* Estruturas de dados mutáveis em memória (list), modelagem com @dataclass e controle de estado de identificadores únicos.

2. Inconsistência de comparação entre instâncias de Enum e strings brutas (str): Descobri que comparar diretamente um membro de Enum (como Situacao.CONCLUIDA) com a string digitada ou armazenada ("CONCLUIDA") avalia como False silenciosamente sem disparar exceção, fazendo filtros e relatórios ignorarem tarefas concluídas. — *Objeto de conhecimento:* Tipagem estática/dinâmica em Python, enumerações (enum.Enum) e operadores relacionais (==).

3. Vulnerabilidade de exclusão em cascata não tratada: Descobri que remover um Membro ou Projeto diretamente da lista sem verificar dependências quebra a integridade referencial do domínio, gerando referências órfãs nos atributos membro_id e projeto_id das instâncias de Tarefa. — *Objeto de conhecimento:* Integridade referencial em coleções relacionadas e expressões geradoras com avaliação de curto-circuito (any()).

**3b. Desvio em relação ao Campo 02 (ao menos 1 — causa técnica):**

- **Desvio:** No Campo 02, planejei resolver a colisão de identificadores substituindo len(lista) + 1 por max(item.id for item in lista) + 1 e executar 8 cenários de teste manuais. Na prática, a abordagem com max() falhou ao remover o último registro cadastrado (reutilizando o ID recém-excluído) e exigiu mais horas de refatoração do que as 2h30 estimadas inicialmente.

- **Causa técnica:** O cálculo max(lista) + 1 depende apenas do estado atual da coleção em memória, não preservando o histórico de chaves já emitidas após um pop() ou remove(), além de lançar ValueError: max() iterable argument is empty quando a lista está vazia.

**3c. Decisão de ajuste (ao menos 1) com justificativa e fonte:**

- **Decisão:** Implementei contadores incrementais independentes por entidade (proximo_id_membro, proximo_id_projeto, proximo_id_tarefa) em vez de derivar o ID do tamanho ou do máximo da lista, combinados com verificação de dependência via any(t.membro_id == codigo for t in tarefas) antes de permitir remover_membro().

- **Fonte:** RAMALHO, Luciano. Python Fluente: Programação Clara, Concisa e Eficiente (Capítulo sobre Estruturas de Dados e dataclasses) e Documentação Oficial do Python 3 (Built-in Functions — any() e max()).

**Objeto de conhecimento mobilizado nesta decisão:** Controle de estado em memória, estruturas de dados (list e @dataclass), expressões geradoras e validação de integridade referencial.

### 🧩 CAMPO 04 — Interação com IA
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59 | OBRIGATÓRIO*

> **Obrigatório e avaliado. Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.**

**4a. Ferramenta:** Gemini  **Data:** 19/11/2026

**4b. Pergunta formulada (transcrita integralmente):**

> "No meu CRUD em Python eu tenho três listas em memória: membros, projetos e tarefas, usando @dataclass. Quando excluo um membro da lista membros, as tarefas antigas ficam com um membro_id que não existe mais, e quando cadastro um novo membro usando len(membros) + 1, ele pega o mesmo ID do que foi apagado. Como posso estruturar a geração de IDs e a exclusão de membros de forma segura e pythônica?"

**4c. Resposta da IA (resumida em parágrafo):**

> A IA sugeriu abandonar o cálculo baseado em len(membros) + 1 e adotar duas abordagens alternativas: utilizar itertools.count(1) ou variáveis contadoras dedicadas por entidade para gerar chaves primárias monotônicas que nunca retrocedem após exclusões. Para o problema de exclusão de membros com tarefas associadas, a IA apresentou um trecho de código utilizando any(t.membro_id == id_membro for t in tarefas) para bloquear a remoção quando houver vínculo ativo, além de sugerir opcionalmente a exclusão em cascata (apagar automaticamente todas as tarefas do membro) ou substituir as listas por dicionários indexados por ID (dict[int, Membro]) para busca em tempo constante $O(1)$.

**4d. O que aceitei — com referência ao objeto de conhecimento do componente:**

> Aceitei o uso de contadores sequenciais independentes por entidade (proximo_id) e a verificação de integridade referencial com a função embutida any() sobre uma expressão geradora (any(t.membro_id == codigo for t in tarefas)). Essa solução se ancora diretamente nos objetos de conhecimento de estruturas de dados em memória, expressões geradoras com avaliação de curto-circuito (parando a varredura na primeira ocorrência encontrada) e cláusulas de guarda (early return), eliminando colisões de chaves primárias e impedindo referências órfãs sem alterar a assinatura das minhas funções.

**4e. O que questionei ou descartei — com argumento técnico ou fonte:**

> Questionei e descartei duas sugestões da IA após testar o comportamento no meu código: primeiro, descartei a exclusão em cascata automática das tarefas ao remover um membro, pois pela regra de negócio do meu sistema de projetos (documentada no Ciclo 04), apagar histórico de tarefas concluídas ou em andamento distorce as métricas de horas e taxa de conclusão de relatorio_geral(); o correto para o domínio é bloquear a exclusão enquanto houver vínculo. Segundo, descartei a migração imediata de list para dict[int, Membro] neste estágio porque o escopo dos Ciclos 05 a 07 exigia justamente dominar iteração, fatiamento (tarefas[-3:]) e ordenação (sorted() com lambda) sobre listas, deixando a busca indexada por dicionário para a evolução do Ciclo 08 conforme a arquitetura planejada em Pense em Python (Downey, cap. 10 e 11).

## 🟠 CICLO 05 — 09/09 — Condicionais aninhadas e operadores lógicos

<details>
<summary>📘 Orientações do Ciclo 05</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 05.
- Registre **qual combinação de condições** (`and`, `or`, `not`) você precisou e **por que** uma condicional aninhada ou um operador lógico foi a melhor escolha.
- Descreva **pelo menos um caso de teste** que você usou para provar a lógica (entrada → resultado esperado → resultado obtido).
- **Atenção à P1 (23/09):** reveja o Logbook até aqui. Complete itens em branco e confirme se os commits estão em dia.
- Na semana de 16/09 (Nivelamento / Peer Instruction), reserve 10 minutos para atualizar este arquivo.
</details>

#### Registro do Ciclo 05 — 09/09
1. **Desafio do ciclo (em 1 frase):** 

Combinar operadores lógicos (and, or, not) e condicionais aninhadas para validar múltiplas regras de negócio simultâneas no cadastro e na atualização de status das tarefas.

2. **O que implementei (commits / arquivos / links):** 

Atualização das funções criar_tarefa(), atualizar_situacao() e filtrar_tarefas() no arquivo crud.py do repositório codigo-crud-rondinelli (feat(crud): implementa condicionais aninhadas e operadores logicos nas validacoes).

3. **Objeto(s) de conhecimento mobilizado(s):** 

Estruturas condicionais aninhadas (if dentro de if/elif/else), operadores lógicos (and, or, not), precedência de operadores booleanos e validação composta de invariantes de domínio.

4. **Desvio ou erro encontrado + causa técnica:** 

Ao validar a atualização de situação de uma tarefa para CONCLUIDA, uma condição escrita sem parênteses combinando or e and (if not tarefa or situacao == "CONCLUIDA" and tarefa.horas_estimadas <= 0:) acabou permitindo que tarefas com horas_estimadas == 0 passassem em outros fluxos por conta da maior precedência do operador and sobre or. Causa técnica: avaliação de curto-circuito e precedência implícita (and avaliado antes de or), somada à falta de aninhamento separando primeiro a existência do registro (if not tarefa:) da regra de transição de estado.

5. **Decisão de ajuste + fonte:** 

Separei a verificação de existência da entidade em uma cláusula de guarda externa (if not tarefa:) e aninhei as validações de transição de estado usando parênteses explícitos nas expressões compostas (if (nova_situacao == Situacao.CONCLUIDA.value) and (tarefa.horas_estimadas <= 0):). Validei com caso de teste: entrada (id_tarefa=99, situacao="CONCLUIDA") -> esperado: erro de tarefa não encontrada -> obtido: mensagem de bloqueio sem exceção; entrada (id_tarefa=1, horas=0, situacao="CONCLUIDA") -> esperado: bloqueio por horas inválidas -> obtido: bloqueio confirmado. Fonte: DOWNEY, Allen B. Pense em Python (Capítulo 5 — Expressões booleanas e condicionais aninhadas) e Documentação Oficial do Python 3 (Operator precedence).

6. **Feedback recebido e o que mudei:** 

Durante a atividade de nivelamento entre pares, observou-se que mensagens genéricas como "Dados inválidos" dificultavam identificar qual condição havia falhado; desmembrei os blocos if/elif aninhados para retornar diagnósticos específicos (membro inexistente, projeto inexistente ou horas fora do intervalo permitido).

7. **Próximo passo:** 

Estruturar os laços de repetição (while e for) no menu principal e nas rotinas de listagem/relatório para evitar encerramentos abruptos e controlar o fluxo de navegação.

## 🟠 CICLO 06 — 30/09 — Devolutiva da P1 + repetição: `for`, `while`, `break`, `continue`

<details>
<summary>📘 Orientações do Ciclo 06</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 06.
- Use o item 6 para registrar a **devolutiva da P1**: o que errou e **qual conceito** estava faltando. Esses erros alimentam o **Campo 07c** (conceitos corrigidos). *Anote já, para não esquecer.*
- Registre **por que escolheu `for` ou `while`** em cada laço do seu CRUD (cadastro em lote, listagem, menu).
- Item 4: se um laço ficou infinito ou pulou itens, descreva a **causa técnica** (condição de parada, incremento, `break` fora de lugar).
</details>

#### Registro do Ciclo 06 — 30/09
1. **Desafio do ciclo (em 1 frase):** 

Estruturar os laços de repetição while e for com controle de fluxo (break e continue) para tornar o menu interativo resiliente e processar listagens e filtros sem loops infinitos.

2. **O que implementei (commits / arquivos / links):** 

Refatoração do loop principal menu() com while True, implementação de laços for com enumerate() nas listagens de membros, projetos e tarefas e uso de continue para ignorar entradas vazias no arquivo crud.py (refactor(crud): aplica lacos while e for com controle de fluxo).

3. **Objeto(s) de conhecimento mobilizado(s):** 

Laços de repetição indeterminados (while), laços determinados sobre iteráveis (for), instruções de desvio (break e continue), função enumerate() e critérios de parada.

4. **Desvio ou erro encontrado + causa técnica:**

Na rotina de cadastro em lote de tarefas via while, ao capturar um ValueError na leitura de horas_estimadas, o laço entrava em repetição infinita reexibindo a mesma mensagem sem avançar. Causa técnica: ausência de atualização da variável de controle ou uso incorreto de continue antes de solicitar nova entrada ao usuário, mantendo a condição de parada inalterada.

5. **Decisão de ajuste + fonte:**

Escolhi while True com break explícito apenas quando o usuário escolhe a opção "0" (Sair) ou fornece uma entrada válida na sub-rotina de leitura numérica, reservando o laço for exclusivamente para percorrer coleções finitas (membros, projetos, tarefas) onde o número de iterações é conhecido. Fonte: DOWNEY, Allen B. Pense em Python (Capítulo 7 — Iteração) e Documentação Oficial do Python 3 (More Control Flow Tools — break and continue).

6. **Feedback recebido (inclui devolutiva da P1) e o que mudei:** 

Na devolutiva da P1, identifiquei dois erros conceituais: (a) alterar uma lista enquanto ela está sendo percorrida por um laço for, o que faz o iterador pular o elemento seguinte após um .remove(); e (b) confundir o efeito de continue (que salta apenas para a próxima iteração do laço atual) com break (que encerra o laço inteiro). Apliquei essa correção imediatamente no CRUD, garantindo que buscas e remoções localizem primeiro a referência do objeto para só depois removê-lo fora da iteração direta.

7. **Próximo passo:**

Aprofundar o armazenamento e manipulação das coleções em memória utilizando operações avançadas de listas (sorted(), fatiamento e list comprehensions).

## 🟠 CICLO 07 — 07/10 — Listas: armazenamento e iteração

<details>
<summary>📘 Orientações do Ciclo 07</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 07.
- Justifique **por que seus dados cabem em uma lista** e como você os percorre (iteração).
- Item 4: erros típicos — índice fora do intervalo, alterar a lista enquanto percorre, confundir cópia com referência. Registre qual deles aconteceu e a causa técnica.
- Item 3: nomeie as **operações de lista** que usou (adicionar, remover, ordenar, fatiar…).
</details>

#### Registro do Ciclo 07 — 07/10
1. **Desafio do ciclo (em 1 frase):** 

Gerenciar as coleções de Membro, Projeto e Tarefa em listas dinâmicas aplicando ordenação, fatiamento e compreensão de listas sem efeitos colaterais de referência mutável.

2. **O que implementei (commits / arquivos / links):**

Implementação de ordenação por prioridade/prazo com sorted(..., key=lambda t: t.horas_estimadas), exibição das últimas tarefas cadastradas via fatiamento (tarefas[-3:]) e filtros com list comprehensions em crud.py (feat(crud): adiciona ordenacao, fatiamento e filtros em listas).

3. **Objeto(s) de conhecimento mobilizado(s):**

Estrutura de dados list (alocação dinâmica e mutabilidade), métodos e funções de lista (append(), remove(), sorted(), len()), fatiamento (slicing [-3:]), expressões lambda e list comprehensions.

4. **Desvio ou erro encontrado + causa técnica:** 

Ao gerar uma visualização ordenada das tarefas no relatório, utilizar tarefas.sort() modificou a ordem cronológica original da lista global, e uma tentativa de backup feita por atribuição simples (copia = tarefas) sofreu as mesmas alterações. Causa técnica: list.sort() opera in-place (mutando o objeto original) e a atribuição = em Python cria apenas um novo alias (referência) apontando para o mesmo endereço de memória da lista, não uma cópia independente.

5. **Decisão de ajuste + fonte:** 

Substituí tarefas.sort() pela função embutida sorted(tarefas, key=...), que preserva a lista original intacta e devolve uma nova lista ordenada, e passei a utilizar cópia rasa explícita (tarefas.copy() ou tarefas[:]) sempre que necessário isolar subconjuntos de exibição. Fonte: RAMALHO, Luciano. Python Fluente (Capítulo sobre Listas e Referências de Objetos) e DOWNEY, Allen B. Pense em Python (Capítulo 10 — Listas).

6. **Feedback recebido e o que mudei:** 

Durante a revisão de código, confirmou-se que o armazenamento em listas de objetos @dataclass é adequado para manter a ordem de inserção e percorrer registros sequencialmente nos relatórios, desde que funções de consulta não provoquem mutações colaterais nas coleções principais.

7. **Próximo passo:** 

Otimizar as operações de busca e consulta por ID introduzindo estruturas de mapeamento chave-valor (dict) e preparando o sistema para o lote de dados com defeito.

## 🟠 CICLO 08 — 14/10 — Busca/consulta e introdução a dicionários e matrizes

<details>
<summary>📘 Orientações do Ciclo 08</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 08.
- Explique **por que cada item do seu catálogo virou um dicionário** (chave → valor) em vez de uma lista de valores soltos.
- Item 4: registre **qual busca falhou** (item inexistente, tipo diferente — `"2"` ≠ `2`, chave com maiúscula errada) e a causa técnica.
- Se usou o lote de dados defeituoso, registre **qual registro** quebrou a busca.
- Item 5: cite a fonte (*Pense em Python*, cap. 11, ou outra).
</details>

#### Registro do Ciclo 08 — 14/10
1. **Desafio do ciclo (em 1 frase):** 

Substituir buscas lineares repetitivas por estruturas chave-valor (dict) e normalizar chaves e tipos de entrada para resistir a consultas com dados defeituosos.

2. **O que implementei (commits / arquivos / links):** 

Criação de índices auxiliares e despacho de menu baseado em dicionários (opcoes = {"1": cadastrar_membro, ...}), além do endurecimento de localizar_por_id() e busca por nome em crud.py (feat(crud): otimiza busca e despacho de menu com dicionarios).

3. **Objeto(s) de conhecimento mobilizado(s):** 

Dicionários (dict — tabelas hash, mapeamento chave -> valor), métodos de dicionário (.get(), .items(), .values()), busca linear $O(n)$ vs. acesso indexado $O(1)$ e normalização de strings (.strip().lower()).

4. **Desvio ou erro encontrado + causa técnica:** 

Ao testar a busca de membros e projetos com o lote de dados defeituoso, consultas por ID falharam quando o dado veio como string ("2" em vez de 2) e buscas por nome falharam diante de diferenças de capitalização ou espaços extras (ex.: " ana silva " vs. "Ana Silva"), além de KeyError ao acessar chaves ausentes diretamente com colchetes dicionario[chave]. Causa técnica: tipagem estrita na comparação de igualdade ("2" == 2 retorna False), sensibilidade a caixa (case-sensitivity) em strings e ausência de acesso seguro via .get().

5. **Decisão de ajuste + fonte:** 

Modelei os registros e índices de consulta rápida como mapeamentos chave-valor (id -> objeto), substituí o acesso direto d[chave] por d.get(chave) e apliquei sanitização obrigatória (int(str(entrada).strip()) para IDs e .strip().lower() para buscas textuais) antes de qualquer consulta. Fonte: DOWNEY, Allen B. Pense em Python (Capítulo 11 — Dicionários) e Documentação Oficial do Python 3 (Mapping Types — dict).

6. **Feedback recebido e o que mudei:** 

Com a introdução dos dicionários para o despacho do menu e mapeamento de entidades por ID, eliminei cadeias extensas de if/elif e reduzi a complexidade das verificações de integridade referencial entre Tarefa, Membro e Projeto.

7. **Próximo passo:** 

Implementar as operações completas de atualização (Update) e exclusão (Delete) com tratamento de registros inexistentes e realizar a primeira revisão por pares no código do meu colega de revisão, Felipe Couto Lamar.

---

# 🔵 GRUPO 3 — prazo quinta 26/11 às 23h59

> **Janela:** sábado 21/11 → quinta 26/11. **O que entregar:** Registros dos Ciclos 09, 10, 11 e 12 · Campo 05 (duas revisões por pares) · Campo 06 · Campo 07.
>
> ⚠️ O prazo vem **um dia depois da P2 (25/11)**. Os Campos 06 e 07 dependem de todo o Logbook: deixe-os para o final, mas **adiante o rascunho do 6c e do 7a/7b antes da Defesa (18/11)**.

**Checklist do Grupo 3**
- [ ] Registros dos Ciclos 09, 10, 11 e 12 com os 7 itens
- [ ] Campo 05: duas revisões (Ciclos 09 e 12), blocos 5a a 5e
- [ ] Campo 06: decisão autônoma, lacuna com plano, pergunta da banca com 5 linhas ou mais
- [ ] Campo 07: 7a a 7e, com 3 objetos, 2 equívocos corrigidos e transferência
- [ ] Coerência entre Campo 01 e Campo 07
- [ ] Painel de acompanhamento completo

## 🔵 CICLO 09 — 21/10 — Atualização e exclusão: CRUD completo

<details>
<summary>📘 Orientações do Ciclo 09 — Registro + Campo 05 (revisão por pares nº 1)</summary>

- Neste ciclo seu CRUD ficou **completo** (Create, Read, Update, Delete). Preencha o Registro do Ciclo 09.
- **Item 4:** *atualizar* ou *excluir* item inexistente, e excluir durante um laço (a lista muda de tamanho e itens são pulados) são erros comuns.
- **Campo 05 — Registro de Revisão por Pares.** Você passa a ser **revisor** do CRUD de um colega.
  - Cada revisão tem **um registro** (copie a seção do Campo 05) com o nome e o link do repositório revisado.
  - **Revise o processo, não só o código:** o que foi decidido, em que objeto de conhecimento se apoia, com que fonte.
  - **5a:** liste as etapas da revisão (ex.: rodar o CRUD, testar com o lote de dados com defeito, ler o código, registrar achados, devolver feedback).
  - **5b:** liste os insumos que usou (lote de dados, casos de teste, `requisitos.md`) com quantidade planejada, utilizada e variação.
  - **5c:** diga se a solução do colega atende ao critério (Sim/Parcialmente/Não) e **qual critério** usou (ex.: requisito do `requisitos.md`).
  - **5d:** riscos da revisão (ex.: não conseguir rodar o código do colega) e como mitigou.
  - **5e:** registre **cada decisão técnica** da revisão com **data, responsável, objeto de conhecimento e fundamentação/referência**. *Sem objeto e sem referência, não é rastreável.*
  - Feedback ao colega: **específico e respeitoso** (o que está bom, o que quebrou, como reproduzir, sugestão).
</details>

1. **Desafio do ciclo (em 1 frase):** 

Consolidar as operações de atualização (`Update`) e exclusão (`Delete`) nas entidades `Membro`, `Projeto` e `Tarefa`, garantindo integridade referencial e mutação segura das listas em memória.

2. **O que implementei (commits / arquivos / links):** 

Implementação das funções `atualizar_situacao()`, `editar_tarefa()`, `remover_membro()`, `remover_projeto()` e `remover_tarefa()` em `crud.py` no repositório `https://github.com/heitorbarboza08/crud-e-logbook-rondinelli`.

3. **Objeto(s) de conhecimento mobilizado(s):** 

Operações completas de persistência em memória (CRUD — *Create, Read, Update, Delete*), integridade referencial (restrição de chave estrangeira antes de exclusão), mutação segura de listas (remoção fora de iteração direta) e validação de pré-condições com retorno antecipado (*early return*).

4. **Desvio ou erro encontrado + causa técnica:** 

Ao implementar a exclusão em lote de tarefas concluídas percorrendo diretamente a lista com `for t in tarefas: if t.situacao == Situacao.CONCLUIDA.value: tarefas.remove(t)`, quando havia duas tarefas concluídas consecutivas, a segunda tarefa não era removida. *Causa técnica:* mutação da lista durante a iteração direta — ao remover o elemento no índice `i`, o elemento seguinte desloca-se para `i`, mas o ponteiro interno do iterador `for` avança para `i + 1`, pulando o item deslocado.

5. **Decisão de ajuste + fonte:** 

Substituí a remoção *in-place* dentro do laço `for` pela reconstrução filtrada da coleção via *list comprehension* (`tarefas[:] = [t for t in tarefas if t.situacao != Situacao.CONCLUIDA.value]`), preservando a referência da lista global sem pular índices, além de bloquear a exclusão de `Membro` e `Projeto` caso `any(...)` detecte tarefas associadas. *Fonte:* DOWNEY, Allen B. *Pense em Python* (Capítulo 10 — Listas e mutação durante iteração) e Documentação Oficial do Python 3 (*Tutorial — Data Structures*).

6. **Feedback recebido e o que mudei:** 

Durante a primeira rodada de revisão por pares com Felipe Couto Lamar, identificamos que a tentativa de atualizar ou excluir um ID inexistente encerrava silenciosamente sem feedback claro ao usuário; adicionei mensagens explícitas de erro quando `localizar_por_id()` retorna `None` e validei a transição de `Situacao` contra os membros válidos do `Enum`.

7. **Próximo passo:** 

Refatorar o código monolítico em funções coesas com responsabilidades bem delimitadas e passagem explícita de parâmetros no Ciclo 10.

### 🧩 CAMPO 05 — Registro de Revisão por Pares
*Adaptação do **Logbook do Time** (Apêndice C) para o CRUD individual. Documento atualizado pelo **revisor**. Cada decisão técnica relevante deve ter associado o objeto de conhecimento correspondente.*

> ⚠️ **Nota de adaptação:** o Apêndice C original prevê Gestor, Responsável Técnico, Analista de Qualidade e Comunicador. Como o CRUD é **individual** e os alunos atuam como **revisores**, mantive os blocos 5a a 5e e troquei os papéis por **Autor** (dono do CRUD) e **Revisor** (você). *Pendente de validação do professor/NDE.*

> **O Logbook de revisão é um registro de conhecimento em ação.** Cada decisão técnica relevante deve estar associada ao objeto de conhecimento que a fundamenta, à justificativa técnica e à referência utilizada. Registros sem esse vínculo não são aceitos.

#### Revisão nº 1

| | |
|---|---|
| **Autor do CRUD revisado** | Felipe Couto Lamar |
| **Repositório revisado** | https://github.com/felipecoutolamar-pixel/Projetos-Undb |
| **Revisor** | Heitor França Barboza |
| **Unidade curricular / Semestre** | Algoritmos e Programação · 2026.2 |
| **Ciclo / data** | Ciclo 09 · 21/10 |

**5a. AVANÇO DO PROCESSO DE REVISÃO — análise técnica de cada etapa:**

**5a. AVANÇO DO PROCESSO DE REVISÃO — análise técnica de cada etapa:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
|---|---|---|---|---|

| 1. Clonagem e execução local do repositório do colega | Felipe Couto | 21/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Executado em ambiente Python 3.12 sem dependências externas faltantes. |

| 2. Execução do fluxo básico CRUD (Create, Read, Update, Delete) | Felipe Couto | 21/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Operações principais funcionaram, mas o sistema apresentou falha ao tentar excluir registro inexistente. |

| 3. Teste de integridade referencial e geração de chaves (IDs) | Felipe Couto | 21/11 | ☐ Concluída ☐ Em andamento ☑ Com desvio | Desvio detectado: exclusão seguida de novo cadastro gerou colisão de ID por uso de `len() + 1`. |

| 4. Leitura estrutural do código-fonte e mapeamento de objetos de conhecimento | Felipe Couto |21/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Verificado uso correto de listas e dicionários, porém sem tratamento de exceção `ValueError` em entradas numéricas. |

| 5. Registro de achados e devolução de feedback técnico ao autor | Felipe Couto | 21/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Feedback documentado com passos de reprodução e sugestões fundamentadas. |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
|---|---|---|---|---|

| Casos de teste funcionais (CRUD completo) | 6 cenários | 6 cenários | 0 | Cobertura integral das 4 operações básicas mais consulta por ID e listagem vazia. |

| Entradas de borda / dados defeituosos | 4 entradas | 5 entradas | +1 entrada | Adicionado teste extra de exclusão seguida de reinserção após observar cálculo de ID baseado no tamanho da lista. |

| Arquivo de código-fonte do colega (`crud.py`) | 1 arquivo | 1 arquivo | 0 | Inspeção estática linha a linha das funções de cadastro, busca, atualização e remoção. |

**5c. CONTROLE DE QUALIDADE:**

- **Critério ou norma técnica:** 

Conformidade funcional das operações CRUD (Create, Read, Update, Delete), integridade de identificadores únicos e resiliência a entradas inválidas conforme os critérios do Protocolo AFP 2026.2.

- **A solução atende?** ☐ Sim ☑ Parcialmente ☐ Não

**5d. GESTÃO DE RISCOS:**

- **Risco:** 

Diferença de versão do interpretador Python ou estrutura de pastas impedir a execução direta do script do colega durante a revisão.

- **Estratégia de mitigação:** 

Verificar previamente a estrutura do repositório no GitHub, rodar o código em terminal limpo via `python3` e inspecionar estaticamente o fluxo lógico antes dos testes interativos.

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
|---|---|---|---|---|

| 21/10/2026 | Recomendar substituição de `len(lista) + 1` por contador sequencial independente na geração de IDs | Revisor | Controle de estado, listas mutáveis e chaves primárias | Documentação Oficial do Python 3 (*Data Structures*) — remoção altera `len()` e causa duplicidade de chaves. |

| 21/10/2026 | Recomendar validação com `try / except ValueError` nas leituras numéricas do menu e buscas por ID | Revisor | Tratamento de exceções e conversão explícita de tipos (`int()`) | Documentação Oficial do Python 3 (*Errors and Exceptions*) — evita interrupção abrupta (`crash`) em tempo de execução. |

| 21/10/2026 | Recomendar verificação de existência antes de atualizar/excluir registro (`if registro is None:`) | Revisor | Estruturas condicionais, busca linear e cláusulas de guarda | DOWNEY, Allen B. *Pense em Python* (Cap. 5 — Condicionais) — previne `IndexError` ou falha silenciosa. |

| 21/10/2026 | Recomendar bloqueio de exclusão de entidade-pai quando houver registros dependentes ativos | Revisor | Expressões geradoras (`any()`) e integridade referencial | Documentação Oficial do Python 3 (*Built-in Functions — any()*) — garante consistência entre entidades relacionadas. |

| 21/10/2026 | Validar cálculo de métricas/relatórios quando a lista de registros estiver vazia (`len(lista) == 0`) | Revisor | Operadores aritméticos e prevenção de `ZeroDivisionError` | Documentação Oficial do Python 3 (*Built-in Exceptions — ZeroDivisionError*). |

> **IMPORTANTE:** Decisão registrada sem objeto de conhecimento associado e sem referência é considerada **não rastreável** e não conta para a avaliação formativa. O vínculo entre processo e conteúdo é obrigatório em todas as decisões relevantes.

## 🔵 CICLO 10 — 28/10 — Modularização: funções

<details>
<summary>📘 Orientações do Ciclo 10</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 10.
- Explique **como dividiu** o CRUD em funções (`cadastrar()`, `buscar()`, `alterar()`, `excluir()`, `listar()`, `menu()`) e **por que** cada função tem aquela responsabilidade.
- Item 4: erros típicos — variável fora de escopo, função sem `return`, parâmetro na ordem errada.
- Compare o código **antes e depois** da refatoração: o que ficou mais claro? Registre no item 6 o feedback do colega que fez a *peer review*.
</details>

#### Registro do Ciclo 10 — 28/10
1. **Desafio do ciclo (em 1 frase):** 

Modularizar o CRUD em funções coesas com responsabilidade única, parâmetros explícitos e retorno claro para eliminar duplicação de lógica e acoplamento de escopo.

2. **O que implementei (commits / arquivos / links):** 

Refatoração completa de `crud.py` separando a camada de entrada validada (`ler_inteiro()`, `ler_float()`, `ler_texto()`), funções auxiliares de busca (`localizar_por_id()`), operações de domínio (`cadastrar_membro()`, `cadastrar_projeto()`, `criar_tarefa()`, `atualizar_situacao()`, `remover_membro()`, `relatorio_geral()`) e controle de interface (`menu()`) (commit `refactor(crud): modulariza operacoes em funcoes coesas com parametros explicitos`).

3. **Objeto(s) de conhecimento mobilizado(s):** 

Modularização, definição de funções (`def`), parâmetros formais e argumentos reais, valores de retorno (`return`), escopo local vs. global (regra LEGB), princípio da responsabilidade única e despacho via dicionário de funções.

4. **Desvio ou erro encontrado + causa técnica:** 

Após extrair `ler_inteiro()` para uma função auxiliar e usá-la dentro de `criar_tarefa()`, a função `criar_tarefa()` passou a imprimir `"Tarefa criada com sucesso"` sem de fato adicionar o objeto à lista ou retorná-lo ao chamador em alguns fluxos de teste, além de gerar `UnboundLocalError` quando tentei incrementar o contador global `proximo_id_tarefa += 1` dentro da função. *Causa técnica:* regras de escopo em Python (LEGB) — atribuir valor a uma variável dentro de `def` faz o interpretador tratá-la como variável local antes da leitura (`+=`), e esquecer a instrução `return` faz a função devolver `None` implicitamente.

5. **Decisão de ajuste + fonte:** 

Encapsulei os contadores de ID e coleções em uma estrutura de estado passada explicitamente por parâmetro (ou retornando o novo ID atualizado pela função geradora), e garanti que toda função de consulta/validação retorne explicitamente o objeto encontrado ou `None`. *Fonte:* DOWNEY, Allen B. *Pense em Python* (Capítulo 3 — Funções e Capítulo 6 — Funções com resultado) e Documentação Oficial do Python 3 (*Execution model — Naming and binding*).

6. **Feedback recebido e o que mudei:** 

Na revisão por pares, Felipe apontou que antes da refatoração o bloco principal tinha mais de 180 linhas misturando `input()`, regras de negócio e `print()`; após dividir em funções pequenas, a leitura do fluxo principal caiu para cerca de 30 linhas e permitiu reutilizar `localizar_por_id()` em 4 operações diferentes sem repetir laços `for`.

7. **Próximo passo:** 

Implementar uma rotina recursiva aplicada ao domínio do projeto no Ciclo 11, analisando caso base, passo recursivo e pilha de execução.

## 🔵 CICLO 11 — 04/11 — Recursividade

<details>
<summary>📘 Orientações do Ciclo 11 — Registro + Campo 06 (Grupo 3)</summary>

- Preencha o Registro do Ciclo 11 (caso base, chamada recursiva, pilha de execução).
- **Campo 06 — Próximos passos para a defesa** · *individual · quinta 26/11, 23h59*. Prepare-se para a **Defesa Técnica de quarta 18/11**: como o prazo é posterior à defesa, **adiante pelo menos o 6c** (pergunta da banca e resposta) e leve-o para a arguição.
  - **6a.** Uma **decisão técnica que você defende com plena autonomia**: algo que aprendeu e **é exclusivamente seu**, que nenhum colega consegue explicar por você.
  - **6b.** Uma **lacuna técnica real** e um **plano de ação** com passos e datas para saná-la antes da defesa.
  - **6c.** Uma **pergunta que a banca pode fazer** (nível de Avaliação ou Criação) e a sua **resposta fundamentada em, no mínimo, 5 linhas**, com o objeto de conhecimento e a fonte.
  - Dica: leia a **Rubrica de Defesa Técnica** (no Encerramento) e escolha uma pergunta que teste *aplicação*, *evolução* ou *transferência*.
</details>

#### Registro do Ciclo 11 — 04/11
1. **Desafio do ciclo (em 1 frase):** 

Aplicar recursividade com caso base e passo de redução bem definidos para percorrer dependências/subtarefas encadeadas e gerar contagem hierárquica de horas estimadas.

2. **O que implementei (commits / arquivos / links):** 

Implementação da função recursiva `calcular_horas_recursivo(lista_tarefas, indice=0)` e da busca recursiva por ID `buscar_recursivo(colecao, id_alvo, indice=0)` em `crud.py` (commit `feat(crud): implementa calculo acumulado e busca recursiva com caso base explicito`).

3. **Objeto(s) de conhecimento mobilizado(s):** 

Recursividade direta, caso base (condição de parada), passo recursivo (redução do problema), pilha de chamadas (*call stack*), frame de execução e comparação de complexidade espacial entre abordagem recursiva ($O(n)$ na pilha) e iterativa ($O(1)$).

4. **Desvio ou erro encontrado + causa técnica:** 

Na primeira execução de `calcular_horas_recursivo(tarefas)`, o programa lançou `RecursionError: maximum recursion depth exceeded` ao passar uma lista vazia `[]` ou ao atingir o final da lista. *Causa técnica:* o caso base foi escrito como `if indice == len(lista_tarefas) - 1:`, o que falhava quando `len(lista_tarefas) == 0` (`indice` `0` nunca igualava `-1`, fazendo o índice crescer indefinidamente para `1, 2, 3...`).

5. **Decisão de ajuste + fonte:** 

Corrigi o caso base para `if indice >= len(lista_tarefas): return 0.0`, cobrindo tanto listas vazias quanto o alcance do limite superior da coleção, e documentei no código por que a versão iterativa (`sum(t.horas_estimadas for t in tarefas)`) continua preferível em produção devido ao limite padrão de pilha do Python (`sys.getrecursionlimit() == 1000`). *Fonte:* DOWNEY, Allen B. *Pense em Python* (Capítulo 5 — Recursividade e pilha de chamadas) e Documentação Oficial do Python 3 (*sys.getrecursionlimit*).

6. **Feedback recebido e o que mudei:** 

Compreendi que recursividade não deve ser forçada onde um laço `for` é mais seguro e econômico em memória, mas seu domínio é essencial para estruturas hierárquicas (como árvores de subtarefas dependentes ou diretórios); adicionei validação de entrada antes de iniciar a recursão.

7. **Próximo passo:** 

Realizar a refatoração final de qualidade de código (nomes, remoção de duplicações, validação de borda) no Ciclo 12 e executar a segunda revisão por pares.

### 🧩 CAMPO 06 — Próximos passos para a defesa
*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

**6a. Decisão técnica que defendo com plena autonomia — o que aprendi que é exclusivamente meu e não consigo transferir para nenhum colega:**

> Defendo com plena autonomia a arquitetura de integridade referencial em memória adotada para relacionar `Membro`, `Projeto` e `Tarefa`: em vez de acoplar chaves primárias ao tamanho dinâmico das listas (`len(lista) + 1`) ou usar `max(id) + 1`, projetei contadores monotônicos independentes por entidade combinados com validação prévia de chaves estrangeiras (`localizar_por_id()`) na criação de tarefas e bloqueio ativo de exclusão (`any(t.membro == codigo for t in tarefas)`) em `remover_membro()`. Essa decisão nasceu da minha própria investigação sobre como bancos relacionais protegem chaves primárias e estrangeiras mesmo antes de existir persistência em disco.

**6b. Lacuna técnica e plano de ação para saná-la:**

- **Lacuna:** 

A persistência atual do CRUD ocorre exclusivamente em memória RAM (listas de `@dataclass`), fazendo com que todos os registros sejam perdidos ao encerrar o programa, além da ausência de testes automatizados (`pytest`/`unittest`) para validar regressões.

- **Plano de ação (passos e datas):**
  1. **Até 23/11:** 

  Serializar as instâncias de `Membro`, `Projeto` e `Tarefa` em arquivos JSON (`json.dump` / `json.load` com `dataclasses.asdict()`) preservando os contadores `proximo_id`.

  2. **Até 24/11:** 
  
  Criar um arquivo `test_crud.py` cobrindo os 8 casos de teste críticos (colisão de ID após exclusão, exclusão de membro com tarefa ativa, `ZeroDivisionError` em relatório vazio e entradas inválidas).

  3. **Até 25/11:** 
  
  Revisar o código completo e executar todos os cenários antes da entrega final do Grupo 3 (26/11).

**6c. Pergunta que a banca pode fazer — com resposta fundamentada (mínimo 5 linhas):**

- **Pergunta:** *Se o seu sistema de gerenciamento de tarefas crescer para dezenas de milhares de registros em produção, qual gargalo estrutural existe na sua busca atual por ID (`localizar_por_id`) e como você evoluiria a estrutura de dados em Python para resolvê-lo sem quebrar a integridade referencial?*
- **Resposta:**

> Atualmente, a função `localizar_por_id()` realiza uma busca linear sequencial sobre listas de objetos (`for item in lista: if item.id == codigo:`), o que possui complexidade assintótica de tempo $O(n)$ no pior caso; como essa verificação é invocada tanto no cadastro de tarefas (checando `membro_id` e `projeto_id`) quanto nas rotinas de atualização e exclusão, o custo cresce linearmente a cada operação conforme o volume de dados aumenta. Para evoluir o sistema sem alterar as regras de negócio de integridade referencial, eu substituiria o armazenamento primário de listas por dicionários indexados pela chave primária (`membros_por_id: dict[int, Membro]`, `projetos_por_id: dict[int, Projeto]`), aproveitando a tabela hash nativa do Python (`dict`) para reduzir a busca por ID para complexidade média $O(1)$ via operador `in` ou `.get()`. Além disso, manteria um índice invertido auxiliar (`tarefas_por_membro: dict[int, list[int]]`) para que a verificação de dependência em `remover_membro()` também ocorra em tempo constante $O(1)$ sem precisar varrer toda a coleção de tarefas, preservando exatamente a mesma interface funcional das operações do CRUD.

**Objeto de conhecimento mobilizado:** 

Estruturas de dados (listas vs. dicionários/tabelas hash), análise de complexidade de busca ($O(n)$ vs. $O(1)$), indexação por chave e integridade referencial.  

**Fonte:** 

DOWNEY, Allen B. *Pense em Python* (Capítulo 11 — Dicionários) e RAMALHO, Luciano. *Python Fluente* (Capítulo sobre Dicionários e Conjuntos — Tabelas Hash).

## 🔵 CICLO 12 — 11/11 — Refatoração e qualidade de código

<details>
<summary>📘 Orientações do Ciclo 12 — Registro + Campo 05 (revisão nº 2) + início do Campo 07</summary>

- Preencha o Registro do Ciclo 12. Registre o que revisou: código duplicado, nomes ruins, funções grandes, comentários desnecessários, lógica confusa.
- **Campo 05 — Revisão por pares nº 2.** Foque em **qualidade**: o CRUD do colega resiste aos casos de teste (mínimos, máximos, inválidos, entradas vazias) e ao **lote de dados com defeito**? Use a seção abaixo (copie o bloco *Revisão nº 1* do Ciclo 09 e preencha novamente).
- **Campo 07 — Evolução conceitual** · *individual · quinta 26/11, 23h59.* Comece agora, enquanto a memória do semestre está fresca; leve o rascunho de 7a e 7b para a Defesa de 18/11. Dicas por item:
  - **7a.** Releia o **Campo 01** e resuma o que você *pensava* e *achava que sabia*. Seja honesto, mesmo se o Campo 01 estiver "errado".
  - **7b.** Pelo menos **3 objetos de conhecimento** na tabela: o que você *não dominava*, o que *aprendeu e consegue demonstrar* e a **evidência** (em qual Campo ou ciclo do Logbook aparece).
  - **7c.** Pelo menos **2 equívocos corrigidos**, dizendo **o que os corrigiu** (Fechamento Teórico, pesquisa, *Peer Review*, arguição, devolutiva da P1).
  - **7d.** **Transferência:** um exemplo concreto de aplicar o que aprendeu em um **contexto diferente** do CRUD (outra área do seu curso ou outro tipo de sistema).
  - **7e.** Avaliação honesta do que **ainda não domina** e vai aprofundar.
</details>

#### Registro do Ciclo 12 — 11/11
1. **Desafio do ciclo (em 1 frase):** 

Refatorar o código do CRUD para elevar a legibilidade, padronizar nomes e garantir resistência total contra entradas vazias, valores limites e lotes de dados defeituosos.

2. **O que implementei (commits / arquivos / links):** 

Limpeza de código duplicado nas rotinas de listagem, padronização de identificadores em `snake_case` (PEP 8), sanitização de strings com `.strip()` e blindagem de todas as entradas numéricas e de borda em `crud.py` (commit `refactor(crud): aplica boas praticas PEP 8, sanitizacao e testes de borda`).

3. **Objeto(s) de conhecimento mobilizado(s):** 

Qualidade de código e refatoração (*clean code*), convenções de nomenclatura PEP 8 (`snake_case`, `PascalCase` para classes/Enums), sanitização de entradas (`str.strip()`), testes de casos de borda (valores mínimos, máximos, nulos e tipos inválidos) e eliminação de código morto/duplicado (princípio DRY).

4. **Desvio ou erro encontrado + causa técnica:** 

Ao submeter o CRUD refatorado ao lote de testes de borda (nomes compostos apenas por espaços `"   "`, horas iguais a `0.0` ou negativas `-2.5`, e strings gigantes ou caracteres especiais), o cadastro de `Projeto` aceitou um nome contendo apenas espaços em branco. *Causa técnica:* a validação verificava apenas `if nome == "":`, que retorna `False` para `"   "` porque a string possui comprimento 3 diferente de zero.

5. **Decisão de ajuste + fonte:** 

Criei uma função única de leitura textual `ler_texto_obrigatorio(prompt)` que aplica `.strip()` antes de validar `if not texto:`, garantindo que nenhuma entidade (`Membro`, `Projeto` ou `Tarefa`) seja instanciada com campos vazios ou compostos apenas por espaços. *Fonte:* Documentação Oficial do Python 3 (*PEP 8 — Style Guide for Python Code* e *Built-in Types — str.strip()*) e MARTIN, Robert C. *Código Limpo* (Capítulo 2 — Nomes Significativos e Capítulo 3 — Funções).

6. **Feedback recebido e o que mudei:** 

Na segunda revisão por pares (Ciclo 12), confirmamos que o código ficou significativamente mais limpo após extrair as funções de leitura validada e remover comentários redundantes que apenas repetiam o óbvio (`# incrementa id`), deixando apenas docstrings objetivas nas funções principais.

7. **Próximo passo:** 

Concluir a segunda revisão por pares do CRUD de Felipe Couto Lamar (Campo 05), consolidar a reflexão de evolução conceitual (Campo 07) e finalizar o painel de acompanhamento do Logbook.

### 🧩 CAMPO 05 — Registro de Revisão por Pares (revisão nº 2)

| | |
|---|---|
| **Autor do CRUD revisado** | Felipe Couto Lamar |
| **Repositório revisado** | `[inserir-link-do-repositorio-do-felipe]` |
| **Revisor** | Heitor França Barboza |
| **Ciclo / data** | Ciclo 12 · 11/11 |

**5a. AVANÇO DO PROCESSO DE REVISÃO:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
|---|---|---|---|---|
| 1. Verificação das correções aplicadas após a Revisão nº 1 | Revisor | 11/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Autor corrigiu o tratamento de `ValueError` no menu principal e a mensagem de ID inexistente. |
| 2. Teste de estresse com casos de borda (entradas vazias, espaços, números negativos e zero) | Revisor | 11/11 | ☐ Concluída ☐ Em andamento ☑ Com desvio | Desvio detectado: campos textuais aceitavam strings compostas apenas por espaços (`"   "`) por ausência de `.strip()`. |
| 3. Avaliação de modularização, escopo de variáveis e legibilidade (PEP 8) | Revisor | 11/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Código bem dividido em funções, porém com dois blocos repetidos de exibição de cabeçalho que podem ser extraídos. |
| 4. Teste de integridade referencial e mutação de listas em exclusões | Revisor | 11/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Exclusões funcionaram corretamente sem pular elementos durante iteração. |
| 5. Devolutiva final de qualidade e registro de rastreabilidade | Revisor / Autor | 11/11 | ☑ Concluída ☐ Em andamento ☐ Com desvio | Relatório entregue com sugestões pontuais de sanitização e refatoração DRY. |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
|---|---|---|---|---|
| Casos de teste de borda (vazio, espaços, negativos, tipos inválidos) | 8 casos | 9 casos | +1 caso | Incluído teste específico de string com múltiplos espaços em branco após observar ausência de `.strip()`. |
| Checklist de qualidade de código (PEP 8, DRY, escopo) | 1 checklist | 1 checklist | 0 | Avaliação sistemática de nomes de variáveis, tamanho de funções e ausência de variáveis globais mutadas sem controle. |
| Repositório GitHub do colega (histórico de commits) | 1 repositório | 1 repositório | 0 | Conferência da evolução entre o commit do Ciclo 09 e o commit refatorado do Ciclo 12. |

**5c. CONTROLE DE QUALIDADE:**
- **Critério ou norma técnica:** Qualidade estrutural de código (PEP 8, modularização, ausência de duplicação) e resiliência a casos de borda e entradas inválidas (sanitização de strings e validação de domínio numérico).
- **A solução atende?** ☑ Sim ☐ Parcialmente ☐ Não

**5d. GESTÃO DE RISCOS:**
- **Risco:** Regressão funcional após a refatoração do colega (funções que funcionavam no Ciclo 09 quebrarem ao serem modularizadas no Ciclo 12).
- **Estratégia de mitigação:** Reexecutar integralmente os 6 cenários funcionais da Revisão nº 1 antes de aplicar os novos testes de borda.

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
|---|---|---|---|---|

| 11/11/2026 | Recomendar sanitização com `.strip()` antes de validar strings vazias nos cadastros | Heitor Barboza | Manipulação de strings (`str.strip()`) e validação de entrada | Documentação Oficial do Python 3 (*Built-in Types — str.strip()*) — impede registros compostos apenas por whitespace. |

| 11/11/2026 | Recomendar validação de domínio numérico (`valor <= 0`) em campos quantitativos | Heitor Barboza | Operadores relacionais e cláusulas de guarda condicionais | DOWNEY, Allen B. *Pense em Python* (Cap. 5 — Condicionais) — garante invariantes de domínio antes da persistência. |

| 11/11/2026 | Recomendar extração de blocos repetidos de formatação de saída para função auxiliar | Heitor Barboza | Modularização, funções e princípio DRY (*Don't Repeat Yourself*) | MARTIN, Robert C. *Código Limpo* (Cap. 3 — Funções) — reduz duplicação e facilita manutenção. |

| 11/11/2026 | Validar que funções de busca retornam `None` explícito em vez de imprimir erro diretamente dentro da busca | Heitor Barboza | Separação de responsabilidades (lógica de negócio vs. I/O) e retorno de funções | DOWNEY, Allen B. *Pense em Python* (Cap. 6 — Funções com resultado) — aumenta reusabilidade das funções. |

| 11/11/2026 | Recomendar padronização de identificadores de funções e variáveis em `snake_case` | Heitor Barboza | Convenções de estilo e legibilidade de código (PEP 8) | Documentação Oficial do Python 3 (*PEP 8 — Naming Conventions*). |

---

### 🧩 CAMPO 07 — Evolução conceitual
*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

*Evidência rastreável de aprendizagem entre o início e o encerramento do ciclo AFP.*

**7a. O que eu pensava no início do ciclo (com base no Campo 01 — registrar a hipótese inicial e os objetos de conhecimento que achava conhecer):**

> No início do ciclo (Campo 01), eu já conhecia a sintaxe básica do Python, listas e estruturas simples, e minha hipótese inicial era que as falhas do CRUD aconteciam apenas porque `gerar_id()` usava `len(lista) + 1` e faltava validar se os IDs existiam antes de cadastrar uma tarefa. Eu achava que bastaria trocar `len()` por `max()` e colocar alguns `if` pontuais para resolver todos os bugs, sem perceber ainda como mutabilidade de listas, aliasing de referência, precedência de operadores lógicos e escopo de funções afetavam o sistema inteiro.

**7b. O que aprendi — conceitos, princípios ou relações técnicas que não dominava no início e que agora consigo explicar com precisão (mínimo 3 objetos de conhecimento):**

| OBJETO DE CONHECIMENTO | O QUE EU NÃO DOMINAVA | O QUE APRENDI E CONSIGO DEMONSTRAR | EVIDÊNCIA (campo do Logbook onde aparece) |
|---|---|---|---|

| **Controle de estado e integridade referencial em memória** | Achava que chaves primárias podiam ser derivadas dinamicamente do tamanho da lista (`len() + 1`) ou do maior ID atual (`max()`), e não controlava exclusões com dependentes. | Aprendi que chaves primárias exigem contadores monotônicos independentes e que a exclusão de entidades-pai (`Membro`, `Projeto`) exige verificação de dependência (`any()`) para evitar referências órfãs. | Campo 02 (2a/2b), Campo 03 (3a/3c) e Registro do Ciclo 09. |

| **Mutabilidade, aliasing e iteração segura sobre listas** | Não percebia que atribuir `lista_b = lista_a` cria dois ponteiros para o mesmo objeto na memória, nem que remover itens durante um `for` desloca índices e pula elementos. | Aprendi a usar `sorted()` em vez de `.sort()` quando preciso preservar a ordem original e a reconstruir listas filtradas com *list comprehension* (`tarefas[:] = [...]`) sem mutar coleções durante a iteração. | Registro do Ciclo 06 (devolutiva P1), Ciclo 07 (item 4) e Ciclo 09 (item 4). |

| **Modularização, escopo (LEGB) e separação de responsabilidades** | Concentrava leitura (`input()`), regra de negócio e exibição (`print()`) em blocos longos e alterava variáveis globais diretamente dentro das funções. | Aprendi a isolar entradas validadas (`ler_inteiro()`), consultas puras com retorno explícito (`localizar_por_id() -> Optional[...]`) e funções de domínio coesas, respeitando o escopo local/global do Python. | Registro do Ciclo 10 (itens 3, 4 e 5) e Ciclo 12. |

| **Dicionários (`dict`), normalização e complexidade de busca** | Tratava buscas sempre por varredura linear sensível a maiúsculas/minúsculas e sem checar incompatibilidade entre `str` e `int`. | Aprendi a normalizar strings com `.strip().lower()`, garantir tipagem na entrada e usar dicionários (`chave → valor` e `.get()`) para despachar menus e agregar métricas com acesso direto. | Registro do Ciclo 08 (itens 3, 4 e 5) e Campo 06 (6c). |

**7c. Conceitos que precisei corrigir ao longo do ciclo — onde eu estava equivocado e o que o corrigiu (Fechamento Teórico, pesquisa, Peer Review, arguição):**

1. **Equívoco:** 

Acreditar que `lista_ordenada = tarefas` criava uma cópia independente da lista para ordenação e que remover itens dentro de um laço `for item in lista:` removia todos os elementos correspondentes. — **Correção:** Compreendi o conceito de *aliasing* (referência compartilhada na memória) e o deslocamento de índices durante a mutação de listas, passando a usar `sorted()` para cópias ordenadas e *list comprehensions* para filtragem segura.  

   **O que corrigiu:** 
   
   Devolutiva da P1 (registrada no Ciclo 06) combinada com testes práticos no Ciclo 07 e leitura do capítulo de Listas em *Pense em Python* (Cap. 10).

2. **Equívoco:** 

Achar que substituir `len(lista) + 1` por `max(item.id) + 1` resolveria definitivamente a colisão de chaves primárias e que comparar `Enum` diretamente com `str` funcionaria em expressões lógicas compostas sem parênteses. — **Correção:** Percebi que `max()` falha em listas vazias e reutiliza IDs quando o último item é apagado, que `Enum` exige `.value` na comparação com strings e que `and` tem precedência sobre `or`, exigindo parênteses explícitos.  

   **O que corrigiu:** 
   
   Testes de borda no Ciclo 03 e Ciclo 05, pesquisa na Documentação Oficial do Python 3 (*Operator precedence* e *Built-in Functions*) e revisão crítica registrada no Campo 03 e Campo 04.

**7d. Transferência — como este aprendizado se aplica a um contexto diferente do problema trabalhado (ao menos 1 exemplo concreto da área de formação):**

> No contexto de **Sistemas de Informação**, exatamente os mesmos princípios de integridade referencial, validação de invariantes e indexação por chave se aplicam ao desenvolvimento de **APIs REST e bancos de dados relacionais** (por exemplo, um sistema acadêmico de matrículas ou um módulo de faturamento hospitalar). Assim como no meu CRUD foi necessário impedir a exclusão de um `Membro` que possuía `Tarefa` vinculada (`RESTRICT` / `ON DELETE NO ACTION`), em sistemas corporativos com PostgreSQL ou SQLAlchemy a camada de serviço precisa validar chaves estrangeiras, sanitizar payloads JSON antes da persistência e usar transações atômicas e índices hash/B-Tree para evitar inconsistência de dados e gargalos de consulta em produção.

**7e. Avaliação honesta do próprio percurso — o que ainda não domino e preciso aprofundar após este ciclo:**

> Embora hoje eu domine a construção de um CRUD estruturado e modularizado em memória, ainda preciso aprofundar três frentes técnicas na sequência do curso: (1) **persistência real em disco e bancos de dados** (serialização em JSON, arquivos CSV e SQLite com SQL), para que o estado do sistema sobreviva ao encerramento do processo; (2) **Programação Orientada a Objetos avançada** (encapsulamento de regras dentro das próprias classes `Membro`, `Projeto` e `Tarefa`, em vez de mantê-las apenas em funções procedurais externas); e (3) **testes automatizados unitários** com `pytest` para substituir a verificação manual por suítes reproduzíveis de regressão.

---

# 🏁 DEFESA TÉCNICA — quarta 18/11

<details>
<summary>📘 Orientações para a Defesa Técnica e preparação</summary>

**A Defesa é antes dos prazos dos Grupos 2 e 3.** Você será arguido sobre o que já estiver registrado e commitado. Priorize, até **terça 17/11**:
- [ ] **Grupo 1 entregue** (prazo 16/11): Identificação, Registros 01 a 04, Campos 01 e 02.
- [ ] **Campo 04 (IA)** e **Campo 03** ao menos em rascunho, para sustentar as perguntas sobre decisões (critérios 2 e 5).
- [ ] **Campo 06c** (pergunta da banca e resposta) e **rascunho de 7a e 7b**, para sustentar a evolução conceitual (critério 3).
- [ ] Registros dos Ciclos já feitos, mesmo que ainda não "entregues" no prazo do grupo.
- [ ] `README.md`, `docs/` e CRUD rodando.
- [ ] Você consegue explicar **cada linha** do seu código e **cada decisão** registrada.
- Os demais itens seguem com os prazos dos grupos (21/11 e 26/11). A banca pode consultar o histórico do Git.

**A Defesa Técnica é individual.** Você será arguido sobre o que registrou. Cada aluno recebe pelo menos **1 questão** nos níveis de **Avaliação** ou **Criação** (taxonomia de Bloom).

**Como a Rubrica se liga ao seu Logbook:**

| Critério da Rubrica | Onde você prepara a evidência |
|---|---|
| 1. Domínio dos objetos de conhecimento | Campos 01, 02 e 07b |
| 2. Aplicação do conteúdo à solução ⚠️ *inegociável* | Registros dos ciclos (itens 3 e 5), Campo 03c e Campo 05e |
| 3. Evolução conceitual ⚠️ *inegociável* | Campo 01 → Campo 07 (7a, 7b e 7c; leve o rascunho) |
| 4. Capacidade de transferência | Campo 07d |
| 5. Argumentação sob pressão | Campo 06c e Campo 04e |
| 6. Autonomia intelectual e coerência com o Logbook | Todo o Logbook (principalmente Campos 04 e 06a) |

**Treino:** peça a um colega que faça 3 perguntas "imprevistas" sobre o seu CRUD e responda **sem consultar** o Logbook. Se não conseguir, volte ao Campo 06b.
</details>

## 🧩 RUBRICA DE DEFESA TÉCNICA (revisada)
*Avaliação individual de cada membro na Semana 16. Cada membro recebe ao menos 1 questão nos níveis de Avaliação ou Criação da Taxonomia de Bloom. Critérios revisados para medir aprendizagem, aplicação, evolução e transferência do conteúdo.*

| | |
|---|---|
| **Nome** | _…_ |
| **Curso / Time / Função** | _…_ |

<details>
<summary>🔒 Uso do professor — rubrica completa</summary>

| CRITÉRIO | EXCELENTE (4,0) | SATISFATÓRIO (3,0) | INSATISFATÓRIO (2,0) | AUSENTE (0) |
|---|---|---|---|---|
| **1. DOMÍNIO DOS OBJETOS DE CONHECIMENTO** — Responde com precisão técnica, sem apoio dos colegas, demonstrando aprendizagem do conteúdo. | Responde com precisão e profundidade, nomeando os objetos de conhecimento mobilizados sem hesitação. | Responde com precisão, com imprecisões pontuais que não comprometem o raciocínio. | Responde de forma vaga, com erros conceituais relevantes ou dependendo dos colegas. | Não responde ou demonstra desconhecimento total. |
| **2. APLICAÇÃO DO CONTEÚDO À SOLUÇÃO** — Demonstra como os objetos de conhecimento fundamentaram as decisões do processo. | Explicita com precisão qual objeto de conhecimento fundamentou cada decisão relevante do processo investigativo, citando referência e demonstrando por que aquele conhecimento era o mais adequado. | Estabelece a relação conteúdo-decisão na maioria das perguntas, com alguma imprecisão pontual. | Não consegue explicitar a relação entre o conteúdo e as decisões do processo investigativo com clareza. | Não demonstra nenhuma relação entre os objetos de conhecimento e as decisões tomadas. |
| **3. EVOLUÇÃO CONCEITUAL** — Demonstra aprendizagem em relação ao que sabia no início do ciclo. | Identifica com precisão o que aprendeu, o que corrigiu e como o conhecimento evoluiu ao longo do ciclo. | Demonstra evolução em parte dos conceitos trabalhados, com alguma dificuldade de articular a trajetória. | Dificuldade em identificar diferenças entre o que sabia no início e o que domina agora. | Não demonstra nenhuma percepção de evolução conceitual ao longo do ciclo. |
| **4. CAPACIDADE DE TRANSFERÊNCIA** — Aplica o conhecimento a um contexto diferente do problema trabalhado. | Consegue transferir o aprendizado para um contexto novo com fundamentação técnica precisa. | Realiza a transferência com imprecisões que não comprometem a lógica do raciocínio. | Demonstra dificuldade em aplicar o conhecimento a contextos diferentes do problema original. | Não consegue realizar nenhuma transferência do conhecimento para contexto diferente. |
| **5. ARGUMENTAÇÃO SOB PRESSÃO** — Mantém coerência técnica diante de questionamentos imprevistos. | Mantém raciocínio coerente, reconhece limites com honestidade e reformula com fundamentação. | Mantém coerência na maior parte, com hesitações pontuais sem perda do fio técnico. | Fragilidade técnica diante de questionamentos imprevistos. | Não sustenta argumentação técnica diante de nenhum questionamento. |
| **6. AUTONOMIA INTELECTUAL E COERÊNCIA COM O LOGBOOK** — Defende o que registrou com consciência e sem depender do grupo. | Defende com precisão as decisões do Logbook, demonstrando autoria plena e independência intelectual. | Defende a maioria das decisões com coerência, com alguma imprecisão ou apoio pontual. | Depende dos colegas ou demonstra desconhecimento de parte do que registrou no próprio Logbook. | Não reconhece o que registrou ou não demonstra autonomia intelectual durante a arguição. |

**PONTUAÇÃO:** _____ / 24,0 **CONCEITO:** _____________

**Conversão:** 20–24 = Excelente (4,0) | 14–19 = Satisfatório (3,0) | 8–13 = Insatisfatório (2,0) | < 8 = Ausente (0)

> ⚠️ **Critérios 2 (Aplicação) e 3 (Evolução Conceitual) são inegociáveis — AUSENTE em qualquer um deles implica nota máxima de 2,0 na Defesa, independentemente do desempenho nos demais.**

**OBSERVAÇÕES:** _…_

**Professor(a):** _________________  **Data:** ___________
</details>

### Registro do Encerramento — 18/11
1. **O que apresentei/defendi (em 1 frase):**

Apresentei a arquitetura e o desenvolvimento de um sistema CRUD de gestão de tarefas via CLI em Python, projetado para unificar o controle de equipe (membros), escopo (projetos) e execução (tarefas) através de modelagem orientada a objetos e repositórios em memória.

2. **Objeto(s) de conhecimento que a banca mais explorou:**

Estruturas de dados e modelagem em Python (uso de dataclasses e Enum para tipagem e estados), manipulação de listas e programação funcional aplicada a relatórios (list comprehension, map, lambda e slicing), além da lógica de vinculação por IDs e integridade relacional em memória.

3. **Pergunta que mais me desafiou e como respondi:**

Pergunta: Como garantir a integridade dos dados e evitar estados inválidos ou registros "órfãos" sem o uso de um banco de dados real?

Resposta: Expliquei que, para evitar validações manuais complexas com múltiplos ifs aninhados, utilizei dataclasses para tipagem e Enums para restringir as tarefas apenas a estados pré-validados. Também destaquei que, embora o MVP utilize listas em memória sujeitas à volatilidade e à falta de exclusão em cascata, a lógica de vinculação via IDs sequenciais já foi estruturada espelhando a mecânica de bancos relacionais para facilitar a futura migração.

4. **O que levo deste semestre para o próximo módulo:**

Levo o domínio da modularização de código (separando gestão, interface e relatórios), a aplicação prática de recursos nativos do Python para escrever códigos mais limpos e com menos boilerplate, e a base arquitetural necessária para dar o próximo passo: integrar o sistema a um banco de dados relacional para garantir persistência e evoluir o motor lógico para uma API RESTful.

---

# 🆘 Estou atrasado no Logbook. E agora?

1. **Não apague nem "retroescreva" o passado.** Preencha agora e **escreva a data real** do preenchimento (ex.: *"preenchido com atraso em 12/11"*).
2. **Campo 01 e Checkpoint (sem consulta):** se perdeu a janela, registre **o que sabe hoje, sem consultar nada**, marcando-o como *preenchimento tardio*. Combine o tratamento com o professor.
3. **Priorize a ordem dos grupos:** Grupo 1 (16/11) → Defesa (18/11) → Grupo 2 (21/11) → Grupo 3 (26/11). Dentro de cada grupo, os Campos vêm antes dos Registros.
4. **Use o histórico do Git** (`git log --oneline`) para reconstruir o que fez em cada ciclo — ele é uma evidência melhor que a memória.
5. **Fale com o professor** antes do prazo, não depois.
