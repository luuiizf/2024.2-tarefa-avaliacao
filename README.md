# 2024.2 Avaliação do 1o período de Sistemas Operacionais

## Informações gerais
- **Objetivo do repositório**: Avaliação do 1o bimestre da Disciplina de sistemas operacionais do curso de TADS do IFRN-CNAT
- **Público alvo**: alunos da disciplina de SO (Sistemas Operacionais) do curso de TADS (Superior em Tecnologia em Análise e Desenvolvimento de Sistemas) no CNAT-IFRN (Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte - Campus Natal-Central).
- disciplina: **SO** Sistemas Operacionais
- professor: [Leonardo A. Minora](https://github.com/leonardo-minora)
- aluno: Luiz Fernando Gama Nery (20232014040019)

## Avaliação
- **Lembre de fazer o fork deste repositório**
- As questões foram construídas com o auxílio do [copilot](https://copilot.microsoft.com/)

# Questão 1. Introdução a sistemas operacionais

Considere as funções e objetivos principais de um sistema operacional conforme discutido no texto. Explique como um sistema operacional gerencia os recursos de hardware e software de um computador para garantir eficiência e segurança. Em sua resposta, aborde os seguintes pontos:

- Gerenciamento de processos
- Gerenciamento de memória
- Gerenciamento de dispositivos de entrada e saída
- Gerenciamento de arquivos

**Dica**: Pense em exemplos práticos de como o sistema operacional realiza essas tarefas no dia a dia de um usuário.

**Copilot informa**: Essa questão incentiva os alunos a explorarem os conceitos fundamentais e a aplicarem o conhecimento teórico em situações práticas. Se precisar de mais alguma coisa, estou aqui para ajudar!

# Questão 2. Estrutura de sistemas operacionais

## Texto informativo
### Estrutura de Sistemas Operacionais: Custo de Desenvolvimento e Segurança da Informação

A estrutura de um sistema operacional (SO) é fundamental para determinar tanto o custo de desenvolvimento e manutenção quanto a segurança da informação. Existem várias arquiteturas de SO, como monolítica, microkernel e em camadas, cada uma com suas próprias implicações em termos de custo e segurança.

#### Custo de Desenvolvimento e Manutenção

1. **Arquitetura Monolítica**:
   - **Desenvolvimento**: Geralmente, mais rápida de desenvolver inicialmente, pois todos os componentes do SO são integrados em um único bloco de código.
   - **Manutenção**: Pode ser mais complexa e cara, pois qualquer alteração em um componente pode afetar todo o sistema, exigindo testes extensivos e cuidadosos.

2. **Arquitetura Microkernel**:
   - **Desenvolvimento**: Pode ser mais demorada e cara inicialmente, pois envolve a criação de um núcleo mínimo e a implementação de serviços adicionais como processos separados.
   - **Manutenção**: Mais fácil e menos custosa, já que os componentes são isolados. Atualizações e correções podem ser feitas em módulos específicos sem impactar o núcleo do sistema.

3. **Arquitetura em Camadas**:
   - **Desenvolvimento**: Moderadamente complexa, pois cada camada deve ser bem definida e interagir corretamente com as outras.
   - **Manutenção**: Relativamente fácil, pois problemas podem ser isolados e corrigidos em camadas específicas sem afetar o restante do sistema.

#### Segurança da Informação

1. **Arquitetura Monolítica**:
   - **Segurança**: Pode ser mais vulnerável, pois uma falha em qualquer parte do sistema pode comprometer todo o SO. A integração de todos os componentes em um único bloco de código pode dificultar a implementação de medidas de segurança robustas.

2. **Arquitetura Microkernel**:
   - **Segurança**: Geralmente mais segura, pois isola os serviços em processos separados. Isso limita o impacto de uma falha ou ataque a um único componente, protegendo o núcleo do sistema e outros serviços.

3. **Arquitetura em Camadas**:
   - **Segurança**: Oferece um bom equilíbrio, pois cada camada pode implementar suas próprias medidas de segurança. No entanto, a comunicação entre camadas deve ser cuidadosamente gerenciada para evitar vulnerabilidades.

### Conclusão

A escolha da arquitetura de um sistema operacional tem um impacto significativo tanto no custo de desenvolvimento e manutenção quanto na segurança da informação. Arquiteturas monolíticas podem ser mais rápidas e baratas de desenvolver inicialmente, mas podem acarretar custos de manutenção mais altos e maiores riscos de segurança. Por outro lado, arquiteturas microkernel e em camadas podem exigir um investimento inicial maior, mas oferecem vantagens em termos de manutenção e segurança.

## Questão
Com base no texto sobre a estrutura de sistemas operacionais, analise como as diferentes arquiteturas (monolítica, microkernel e camadas) impactam o custo com a equipe de desenvolvimento e a segurança do sistema operacional. Em sua resposta, considere os seguintes pontos:
- Complexidade de implementação e manutenção
- Necessidade de especialização da equipe
- Potenciais vulnerabilidades de segurança
- Facilidade de atualização e correção de falhas

**Dica:** Utilize exemplos de sistemas operacionais reais que adotam essas arquiteturas para ilustrar sua análise.

**Copilot informa**: Essa questão incentiva os alunos a considerarem tanto os aspectos econômicos quanto os de segurança ao avaliar diferentes arquiteturas de sistemas operacionais.

# Questão 3. Introdução à Segurança de Sistemas Operacionais

## Texto informativo

A segurança de um sistema operacional é um aspecto crucial que visa proteger os recursos do sistema contra acessos não autorizados, ataques maliciosos e falhas. Um sistema operacional seguro deve garantir a integridade, confidencialidade e disponibilidade dos dados e serviços. Para alcançar esses objetivos, várias técnicas e mecanismos são implementados, incluindo:

1. **Controle de Acesso**: Define quem pode acessar o sistema e quais recursos podem ser utilizados. Isso é feito através de autenticação (verificação de identidade) e autorização (permissão de acesso).

2. **Criptografia**: Utilizada para proteger dados em trânsito e em repouso, garantindo que apenas usuários autorizados possam acessar informações sensíveis.

3. **Auditoria e Monitoramento**: Registra atividades do sistema para detectar e responder a comportamentos suspeitos ou anômalos.

4. **Isolamento de Processos**: Garante que os processos sejam executados em ambientes isolados, evitando que um processo comprometa a segurança de outro.

5. **Atualizações e Patches**: Manter o sistema operacional atualizado é essencial para corrigir vulnerabilidades conhecidas e proteger contra novas ameaças.


## Questão

Considerando os mecanismos de segurança discutidos, analise como a implementação de controles de acesso e criptografia pode impactar a performance e a usabilidade de um sistema operacional. Em sua resposta, aborde os seguintes pontos:
- Benefícios e desafios de cada mecanismo
- Impacto na experiência do usuário
- Exemplos de situações onde esses mecanismos são críticos

**Dica:** Pense em como esses mecanismos são aplicados em sistemas operacionais que você utiliza no dia a dia, como Windows, Linux ou macOS.

**Copilot informa**: Essa questão incentiva os alunos a refletirem sobre o equilíbrio entre segurança, performance e usabilidade, aplicando conceitos teóricos a contextos práticos.


# Questão 4. Custo de Processamento versus Algoritmo Ótimo de Escalonamento

## Texto informativo

O escalonamento de processos é uma função crítica de um sistema operacional, responsável por determinar a ordem em que os processos são executados pelo processador. O objetivo é maximizar a eficiência do sistema, garantindo que os recursos sejam utilizados de maneira justa e eficaz. No entanto, encontrar o algoritmo de escalonamento ótimo envolve um equilíbrio delicado entre o custo de processamento e a eficiência do escalonamento.

### Custo de Processamento

O custo de processamento refere-se ao tempo e aos recursos necessários para executar um algoritmo de escalonamento. Algoritmos mais complexos podem oferecer melhores resultados em termos de tempo de resposta e utilização do processador, mas também podem exigir mais recursos computacionais para tomar decisões de escalonamento. Isso pode incluir tempo de CPU, memória e outras operações de sistema.

### Algoritmo Ótimo de Escalonamento

Um algoritmo ótimo de escalonamento é aquele que maximiza a eficiência do sistema operacional, minimizando o tempo de espera dos processos, o tempo de resposta e o tempo de retorno. Alguns dos algoritmos de escalonamento mais comuns incluem:

- **First-Come, First-Served (FCFS)**: Simples e fácil de implementar, mas pode levar a longos tempos de espera para processos curtos.
- **Shortest Job Next (SJN)**: Minimiza o tempo médio de espera, mas pode ser difícil de implementar devido à necessidade de prever o tempo de execução dos processos.
- **Round Robin (RR)**: Oferece uma abordagem justa, atribuindo fatias de tempo iguais a todos os processos, mas pode resultar em maior sobrecarga de contexto.
- **Priority Scheduling**: Processos com maior prioridade são executados primeiro, mas pode levar à inanição de processos de baixa prioridade.

## Questão

Considerando os conceitos de custo de processamento e algoritmo ótimo de escalonamento, analise como diferentes algoritmos de escalonamento podem impactar a performance de um sistema operacional em termos de tempo de resposta, tempo de espera e utilização do processador. Em sua resposta, aborde os seguintes pontos:
- Vantagens e desvantagens de pelo menos dois algoritmos de escalonamento
- Impacto do custo de processamento na escolha do algoritmo
- Exemplos de situações onde um algoritmo pode ser preferível a outro

**Dica:** Pense em como esses algoritmos são aplicados em diferentes cenários, como sistemas de tempo real, servidores web e sistemas operacionais de uso geral.

**Copilot informa**: Essa questão incentiva os alunos a refletirem sobre a complexidade e os trade-offs envolvidos na escolha de um algoritmo de escalonamento, aplicando conceitos teóricos a contextos práticos.

# Questão 5. Aplicativo em python vs aplicativos em c

## Questão

Explique o caminho que as instruções seguem desde um aplicativo escrito em Python e um aplicativo escrito em linguagem C até serem executadas pelo hardware. Em sua resposta, considere os seguintes pontos:
- O papel do interpretador no caso do Python
- O processo de compilação no caso do C
- A interação entre o kernel do sistema operacional e os drivers de dispositivo
- A tradução final das instruções para o formato binário (0 e 1) executado pelo hardware

**Dica:** Compare e contraste os dois processos, destacando as principais diferenças e semelhanças na forma como as instruções são processadas e executadas.

**Copilot informa**: Essa questão incentiva os alunos a refletirem sobre os diferentes caminhos que as instruções seguem em linguagens interpretadas e compiladas, aplicando conceitos teóricos a contextos práticos.

---

## RESPOSTAS DAS QUESTÔES ABAIXO:

## Questão 1: Gerenciamento de recursos por um SO

O sistema operacional (SO) é responsável por gerenciar os recursos de hardware e software, garantindo **eficiência** e **segurança**. Vamos analisar suas principais funções:

### **Gerenciamento de Processos**
- **Função**: Controla a criação, execução e finalização de processos. Coordena a CPU para que múltiplos processos sejam executados sem conflitos.
- **Exemplo Prático**: No Windows, o Gerenciador de Tarefas permite ao usuário monitorar e encerrar processos em execução, alocando recursos adequadamente.

### **Gerenciamento de Memória**
- **Função**: Garante que cada processo tenha acesso à memória necessária sem interferir em outros processos. Realiza a alocação dinâmica e o uso de memória virtual.
- **Exemplo Prático**: Em sistemas Linux, a memória swap é usada quando a RAM está cheia, permitindo a execução de programas mesmo em condições de pouca memória.

### **Gerenciamento de Dispositivos de Entrada e Saída**
- **Função**: Coordena a comunicação entre hardware (teclados, impressoras, etc.) e software, garantindo que dispositivos diferentes possam ser usados simultaneamente.
- **Exemplo Prático**: O Windows fornece drivers para que dispositivos como impressoras sejam reconhecidos e utilizados sem intervenção manual.

### **Gerenciamento de Arquivos**
- **Função**: Organiza, armazena e protege dados no sistema de arquivos, além de fornecer acesso controlado a eles.
- **Exemplo Prático**: O macOS utiliza o sistema de arquivos APFS para operações rápidas e confiáveis, com suporte a criptografia nativa.

---

## Questão 2: Arquitetura de SOs

### **Impactos das Arquiteturas de Sistemas Operacionais**

#### **Arquitetura Monolítica**
- **Complexidade**: Fácil de implementar inicialmente, pois todos os componentes estão integrados.
- **Manutenção**: Difícil e cara, devido à necessidade de testes extensivos ao alterar qualquer componente.
- **Necessidade de Especialização**: Menor, já que os desenvolvedores precisam compreender um único bloco de código.
- **Segurança**: Vulnerável, pois uma falha em um componente pode comprometer todo o sistema.
- **Exemplo**: O Linux utiliza uma arquitetura monolítica.

#### **Arquitetura Microkernel**
- **Complexidade**: Alta durante a implementação inicial, já que os serviços precisam ser projetados de forma isolada.
- **Manutenção**: Mais fácil, pois os módulos são independentes e podem ser atualizados sem afetar o núcleo.
- **Necessidade de Especialização**: Maior, pois cada módulo exige um nível específico de conhecimento.
- **Segurança**: Elevada, devido ao isolamento de serviços.
- **Exemplo**: O Minix utiliza a arquitetura microkernel.

#### **Arquitetura em Camadas**
- **Complexidade**: Moderada, exige boa definição de interfaces entre camadas.
- **Manutenção**: Simplificada, já que as falhas podem ser corrigidas em camadas específicas.
- **Necessidade de Especialização**: Equilibrada, pois cada camada pode ser tratada de forma independente.
- **Segurança**: Balanceada, desde que a comunicação entre camadas seja segura.
- **Exemplo**: O Windows NT usa uma abordagem em camadas.

---

## Questão 3: Introdução à Segurança de Sistemas Operacionais

### **Impacto de Controles de Acesso e Criptografia**

#### **Controles de Acesso**
- **Benefícios**: Garante que apenas usuários autorizados acessem recursos, protegendo o sistema contra acessos não autorizados.
- **Desafios**: Implementações complexas podem dificultar a usabilidade, como exigir autenticação multifator frequente.
- **Impacto na Experiência do Usuário**: Pode ser percebido como inconveniente, mas é essencial para evitar violações de segurança.
- **Exemplo**: O Windows utiliza políticas de grupo (Group Policies) para definir permissões em redes corporativas.

#### **Criptografia**
- **Benefícios**: Protege dados em trânsito (TLS) e em repouso (BitLocker, no Windows), garantindo confidencialidade.
- **Desafios**: Requer processamento adicional, podendo impactar a performance do sistema.
- **Impacto na Experiência do Usuário**: O impacto é minimizado por hardware moderno, mas pode ser perceptível em sistemas mais antigos.
- **Exemplo**: O macOS usa o FileVault para criptografar o disco do usuário, protegendo dados contra acessos indevidos.

### **Aplicações Críticas**
- **Controles de Acesso**: Em servidores de banco de dados, como MySQL, onde múltiplos usuários acessam informações sensíveis.
- **Criptografia**: Em serviços de armazenamento na nuvem, como o Google Drive, para garantir a privacidade dos arquivos dos usuários.

---

## Questão 4: Análise de algoritmos de escalonamento

O escalonamento de processos é uma função central nos sistemas operacionais, com diferentes algoritmos aplicados de acordo com o cenário e os requisitos de performance. Aqui, analisaremos **Shortest Job Next (SJN)** e **Priority Scheduling**.

### 1. Shortest Job Next (SJN)

#### Descrição
- O SJN é um algoritmo não preemptivo que escolhe para execução o processo com o menor tempo estimado de execução.
- Baseado na premissa de minimizar o tempo médio de espera dos processos na fila de prontos.

#### Vantagens
- Minimiza o tempo médio de espera dos processos, pois os processos curtos são executados rapidamente.
- Reduz o número de processos na fila, promovendo eficiência.

#### Desvantagens
- Requer conhecimento prévio ou estimativa precisa do tempo de execução dos processos, o que nem sempre é viável.
- Pode levar à inanição de processos mais longos, que permanecem indefinidamente na fila se houver um fluxo contínuo de processos curtos.

#### Impacto do custo de processamento
- O custo de processamento no SJN está relacionado à necessidade de prever ou calcular o tempo de execução dos processos. Essa tarefa adiciona sobrecarga computacional, especialmente em sistemas com alta variabilidade de processos.

#### Exemplo de aplicação
- É adequado para sistemas em que os tempos de execução dos processos são conhecidos e previsíveis, como sistemas batch.
- **Exemplo**: processamento de jobs em servidores de impressão, onde processos curtos devem ser finalizados rapidamente para evitar congestionamento.

### 2. Priority Scheduling

#### Descrição
- Esse algoritmo atribui prioridades aos processos, onde processos com maior prioridade são executados primeiro. Ele pode ser **preemptivo** ou **não preemptivo**.

#### Vantagens
- Flexível e adequado para sistemas de tempo real, onde processos críticos podem receber prioridade mais alta.
- Permite a customização do escalonamento com base em políticas específicas, como tempo de resposta ou criticidade do processo.

#### Desvantagens
- Pode levar à inanição de processos com baixa prioridade, especialmente em sistemas onde processos de alta prioridade chegam continuamente.
- Complexidade adicional para gerenciar prioridades e evitar inversão de prioridade (resolvida, em parte, com técnicas como herança de prioridade).

#### Impacto do custo de processamento
- O gerenciamento das prioridades e a necessidade de reorganizar a fila de processos a cada nova chegada aumentam o custo computacional. Em sistemas com alta carga, essa sobrecarga pode ser significativa.

#### Exemplo de aplicação
- Muito utilizado em sistemas de tempo real, como controle de tráfego aéreo, onde processos relacionados à segurança devem ser tratados com maior prioridade.
- Também é usado em sistemas operacionais modernos, como Windows, para gerenciar tarefas do sistema versus tarefas do usuário.

### Comparação e Cenários de Aplicação

1. **Sistemas de tempo real**:  
   - **Priority Scheduling** é preferido devido à necessidade de garantir a execução de processos críticos dentro de prazos rigorosos.

2. **Servidores web**:  
   - **Shortest Job Next** é mais eficaz quando os tempos de execução das requisições são previsíveis, pois minimiza o tempo médio de resposta para os usuários.

3. **Sistemas de uso geral**:  
   - Uma combinação de **Priority Scheduling** com preempção controlada pode equilibrar processos do sistema e do usuário, garantindo responsividade sem comprometer tarefas importantes.

---

## Questão 5: Caminho das instruções em Python e C

O caminho que as instruções seguem, desde a escrita em Python ou C até a execução pelo hardware, difere substancialmente devido à natureza das linguagens e ao papel dos mecanismos de execução. Aqui está uma análise detalhada:

### 1. Python: Linguagem Interpretada

#### Papel do interpretador
- Um programa Python é lido e executado pelo interpretador Python (por exemplo, CPython).
- O código-fonte é convertido em **bytecode**, uma representação intermediária de baixo nível, que é executada pela Máquina Virtual Python (PVM).
- Não há etapa explícita de compilação para código binário; o bytecode é interpretado dinamicamente, o que permite alta portabilidade, mas com impacto na performance.

#### Interação com o kernel e drivers
- Durante a execução, operações como abertura de arquivos, alocação de memória e interações de entrada/saída são feitas através de chamadas de sistema fornecidas pelo kernel do sistema operacional.
- O interpretador Python faz essas solicitações ao kernel, que coordena os drivers para interagir com o hardware correspondente.

#### Tradução final para binário
- O kernel transforma as solicitações de alto nível em instruções binárias executáveis pela CPU, que acessam diretamente os dispositivos por meio dos drivers.

#### Características do caminho em Python
- **Vantagem**: Flexibilidade e portabilidade.
- **Desvantagem**: A tradução em tempo de execução adiciona sobrecarga, tornando a execução mais lenta em comparação a linguagens compiladas.

### 2. C: Linguagem Compilada

#### Processo de compilação
- O código-fonte em C é transformado em código binário executável (formato de máquina) pelo compilador (por exemplo, GCC ou Clang).
- Esse processo envolve etapas de pré-processamento, compilação, montagem e ligação (linking).
- O resultado é um arquivo executável otimizado, diretamente interpretável pelo hardware.

#### Interação com o kernel e drivers
- Assim como no Python, o executável faz chamadas de sistema para interagir com o kernel, que gerencia os recursos de hardware.
- No entanto, o código em C, por ser diretamente compilado, interage com o sistema operacional de maneira mais eficiente.

#### Tradução final para binário
- As instruções já estão em formato binário antes da execução, eliminando a necessidade de interpretação em tempo de execução. A CPU executa diretamente essas instruções.

#### Características do caminho em C
- **Vantagem**: Performance elevada, pois elimina a necessidade de interpretação.
- **Desvantagem**: Menos portabilidade; um binário compilado é específico para o hardware e o sistema operacional.

### Comparação entre Python e C

| **Aspecto**               | **Python**                                         | **C**                                              |
|---------------------------|---------------------------------------------------|---------------------------------------------------|
| **Execução**              | Interpretada em tempo de execução.                | Pré-compilada para código binário executável.     |
| **Velocidade**            | Mais lenta devido à interpretação.                | Mais rápida, pois as instruções já estão otimizadas. |
| **Portabilidade**         | Alta, requer apenas um interpretador compatível.  | Depende do binário ser recompilado para a plataforma-alvo. |
| **Complexidade do Processo** | Simples para o desenvolvedor.                   | Mais complexo, com etapas explícitas de compilação e linkagem. |

### Exemplo Prático
- **Python**: Um script que lê e manipula dados em um arquivo interage com o kernel para abrir o arquivo e realizar operações de leitura e escrita. O interpretador gerencia essas operações.
- **C**: Um programa similar em C realiza essas operações diretamente através de funções como `fopen` e `fwrite`, cuja execução é otimizada durante a compilação.

---


