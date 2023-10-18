# ChatGPT-Testing
ChatGPT Testing


O ChatGPT é um modelo de linguagem desenvolvido pela OpenAI, projetado para gerar respostas e interagir com os usuários em linguagem natural. Ele é treinado em uma ampla variedade de dados e possui a capacidade de compreender e produzir textos coerentes e relevantes.

Na área de testes de software, o ChatGPT pode ser extremamente útil de várias maneiras. Primeiro, ele pode ser usado para criar diálogos simulados entre usuários e sistemas, permitindo a realização de testes de interação e verificação de como um software se comporta em diferentes cenários de conversação.

Além disso, o ChatGPT pode auxiliar no desenvolvimento de casos de teste e na criação de scripts de automação. Ao interagir com o modelo, os testadores podem obter sugestões valiosas sobre entradas possíveis e explorar diferentes caminhos de execução do software.

O ChatGPT também pode ser usado para a geração automatizada de dados de teste. Ele pode gerar inputs variados e complexos, ajudando a verificar a robustez e a capacidade de resposta do software sob diferentes condições.

Outra aplicação do ChatGPT é na verificação de respostas do sistema. Os testadores podem usar o modelo para comparar as respostas do software com as geradas pelo ChatGPT, verificando se as respostas são coerentes e corretas.

Em resumo, o ChatGPT é uma ferramenta poderosa para a área de testes de software, fornecendo suporte na criação de diálogos simulados, no desenvolvimento de casos de teste, na automação de testes, na geração de dados de teste e na verificação de respostas do sistema. Sua capacidade de entender e gerar linguagem natural permite uma abordagem mais abrangente e eficiente na realização de testes de software.





Pré-Requisitos: conhecer e ter aplicado fundamentos de Testes de software.

Exemplos de Prompts: exemplos de possíveis entradas.

Obs.: Com entradas controladas e detalhadas e conhecimento prático em fundamentos de teste de software e possivel ter acesso ao um número maior de variações de cenários de testes com mais velocidade e automatizar todas parte de criação, modelagem de testes.


- **Critérios de Aceitação**

**História de Usuário**:

Como ****um aluno de medicina

**Eu quero** ter acesso a um aplicativo móvel interativo de estudo do corpo humano

**Para que** eu possa aprimorar meu conhecimento anatômico de forma eficiente

**Entrada Prompt ChatGPT**:

“Poderia criar  5 critérios de aceitação baseado na historia de usuário informada abaixo

**Como** um aluno de medicina

**Eu quero** ter acesso a um aplicativo móvel interativo de estudo do corpo humano

**Para que** eu possa aprimorar meu conhecimento anatômico de forma eficiente”


Saída:

![image](https://github.com/FelipeGeraldi/ChatGPT-Testing/assets/11202772/9db32d73-4640-486a-ab01-efbd2581b7ec)



Critérios de Aceitação:

1. O aplicativo móvel deve fornecer acesso a um atlas anatômico completo, que abranja todos os sistemas do corpo humano, como o sistema esquelético, muscular, cardiovascular, respiratório, digestivo, entre outros.
2. O aplicativo deve apresentar uma interface intuitiva e de fácil navegação, permitindo ao aluno explorar de forma eficiente os diferentes sistemas e regiões anatômicas.
3. Deve ser possível interagir com modelos anatômicos em 3D, permitindo zoom e rotação para uma visualização detalhada das estruturas.
4. O aplicativo deve fornecer informações detalhadas sobre cada estrutura anatômica, incluindo nome, função e relações com outras estruturas.
5. Deve ser possível realizar anotações e marcações nas estruturas anatômicas, permitindo ao aluno revisar e registrar observações importantes durante o estudo.




- **Cenários de Testes**

**Entrada Prompt ChatGPT**:

Poderia criar 5 cenários de testes utilizando as técnicas de testes (Partição de equivalência, Análise de valor limite e Tabela de decisão) para cada  critérios de aceitação informados abaixo

1. O aplicativo móvel deve fornecer acesso a um atlas anatômico completo, que abranja todos os sistemas do corpo humano, como o sistema esquelético, muscular, cardiovascular, respiratório, digestivo, entre outros.
2. O aplicativo deve apresentar uma interface intuitiva e de fácil navegação, permitindo ao aluno explorar de forma eficiente os diferentes sistemas e regiões anatômicas.
3. Deve ser possível interagir com modelos anatômicos em 3D, permitindo zoom e rotação para uma visualização detalhada das estruturas.
4. O aplicativo deve fornecer informações detalhadas sobre cada estrutura anatômica, incluindo nome, função e relações com outras estruturas.
5. Deve ser possível realizar anotações e marcações nas estruturas anatômicas, permitindo ao aluno revisar e registrar observações importantes durante o estudo.

**Saída**:

Cenários de teste utilizando a técnica de Partição de Equivalência:

1. Cenário: Acesso ao atlas anatômico
    - Partição de Equivalência 1: Usuário sem conexão com a internet
    - Partição de Equivalência 2: Usuário com conexão com a internet
    - Teste: Verificar se o aplicativo exibe corretamente o atlas anatômico quando o usuário está sem conexão com a internet e quando está conectado.
2. Cenário: Interface intuitiva e de fácil navegação
    - Partição de Equivalência 1: Usuário inexperiente
    - Partição de Equivalência 2: Usuário experiente
    - Teste: Avaliar se a interface do aplicativo é intuitiva e fácil de navegar para ambos os perfis de usuários, verificando a facilidade de encontrar e acessar os diferentes sistemas e regiões anatômicas.
3. Cenário: Interação com modelos anatômicos em 3D
    - Partição de Equivalência 1: Zoom máximo permitido
    - Partição de Equivalência 2: Zoom mínimo permitido
    - Teste: Verificar se é possível realizar zoom máximo e mínimo nos modelos anatômicos em 3D, garantindo que a visualização detalhada das estruturas seja mantida sem distorções excessivas.
4. Cenário: Informações detalhadas sobre estruturas anatômicas
    - Partição de Equivalência 1: Estrutura anatômica com informações completas
    - Partição de Equivalência 2: Estrutura anatômica com informações parciais
    - Teste: Verificar se o aplicativo exibe corretamente as informações detalhadas sobre cada estrutura anatômica, incluindo nome, função e relações com outras estruturas, tanto para estruturas com informações completas quanto para estruturas com informações parciais.
5. Cenário: Anotações e marcações nas estruturas anatômicas
    - Partição de Equivalência 1: Anotações simples em uma estrutura
    - Partição de Equivalência 2: Marcações múltiplas em diferentes estruturas
    - Teste: Avaliar se é possível realizar anotações simples e marcações múltiplas nas estruturas anatômicas, permitindo ao aluno revisar e registrar observações importantes durante o estudo, verificando a precisão e a facilidade de uso dessas funcionalidades.

Cenários de teste utilizando a técnica de Análise de Valor Limite:

1. Cenário: Acesso ao atlas anatômico
    - Teste de Valor Limite Inferior: Verificar se o aplicativo exibe uma mensagem de erro quando não há acesso a nenhum sistema do corpo humano.
    - Teste de Valor Limite Superior: Verificar se o aplicativo exibe uma mensagem de erro quando há acesso a todos os sistemas do corpo humano.
2. Cenário: Interface intuitiva e de fácil navegação
    - Teste de Valor Limite Inferior: Verificar se o aplicativo exibe uma mensagem de erro quando a interface não é intuitiva e dificulta a navegação.
    - Teste de Valor Limite Superior: Verificar se o aplicativo exibe uma mensagem de erro quando a interface é altamente intuitiva e facilita a navegação.
3. Cenário: Interação com modelos anatômicos em 3D
    - Teste de Valor Limite Inferior: Verificar se o aplicativo exibe uma mensagem de erro quando não é possível realizar zoom ou rotação nos modelos anatômicos.
    - Teste de Valor Limite Superior: Verificar se o aplicativo exibe uma mensagem de erro quando é possível realizar zoom e rotação com alta precisão nos modelos anatômicos.
4. Cenário: Informações detalhadas sobre estruturas anatômicas
    - Teste de Valor Limite Inferior: Verificar se o aplicativo exibe uma mensagem de erro quando não fornece informações sobre nenhuma estrutura anatômica.
    - Teste de Valor Limite Superior: Verificar se o aplicativo exibe uma mensagem de erro quando fornece informações detalhadas sobre todas as estruturas anatômicas.
5. Cenário: Anotações e marcações nas estruturas anatômicas
    - Teste de Valor Limite Inferior: Verificar se o aplicativo exibe uma mensagem de erro quando não permite realizar nenhuma anotação ou marcação nas estruturas anatômicas.
    - Teste de Valor Limite Superior: Verificar se o aplicativo exibe uma mensagem de erro quando permite realizar um número máximo de anotações e marcações nas estruturas anatômicas.

Cenários de teste utilizando a técnica de Tabela de Decisão:

1. Cenário: Acesso ao atlas anatômico
    - Condição 1: O aplicativo está conectado à internet
    - Condição 2: O aplicativo não está conectado à internet
    - Decisão: O aplicativo exibe corretamente o atlas anatômico
2. Cenário: Interface intuitiva e de fácil navegação
    - Condição 1: O usuário é inexperiente
    - Condição 2: O usuário é experiente
    - Decisão: A interface do aplicativo é intuitiva e fácil de navegar
3. Cenário: Interação com modelos anatômicos em 3D
    - Condição 1: O usuário realiza zoom máximo
    - Condição 2: O usuário realiza zoom mínimo
    - Decisão: É possível visualizar corretamente as estruturas anatômicas em 3D
4. Cenário: Informações detalhadas sobre estruturas anatômicas
    - Condição 1: A estrutura anatômica possui informações completas
    - Condição 2: A estrutura anatômica possui informações parciais
    - Decisão: O aplicativo exibe informações detalhadas sobre cada estrutura anatômica
5. Cenário: Anotações e marcações nas estruturas anatômicas
    - Condição 1: O usuário realiza anotações simples em uma estrutura
    - Condição 2: O usuário realiza marcações múltiplas em diferentes estruturas
    - Decisão: É possível realizar anotações e marcações nas estruturas anatômicas





**Entrada Prompt ChatGPT**:

para tabela de decisão poderia criar uma tabela para os 5 cenários acima

**Saída**:

**Tabela de Decisão:**



![image](https://github.com/FelipeGeraldi/ChatGPT-Testing/assets/11202772/52117f94-123f-4384-87ad-df61948ce4ba)


Essa tabela de decisão permite identificar as diferentes combinações de condições e as decisões correspondentes para cada cenário de teste. Cada cenário pode ser testado em conformidade com as condições e decisões específicas da tabela.




- **Matriz de Riscos**

**Entrada Prompt ChatGPT**:

Poderia criar uma matriz de riscos baseada nos cenários de testes criados

**Saída**:

**Matriz de Riscos:**


![image](https://github.com/FelipeGeraldi/ChatGPT-Testing/assets/11202772/2c56f095-574c-40e7-8c4d-91c522209a49)


Nessa matriz de riscos, foram identificados os riscos potenciais associados a cada cenário de teste, bem como a severidade, a probabilidade e a detecção de cada risco. A severidade indica o impacto que o risco pode causar, a probabilidade representa a chance de o risco ocorrer e a detecção indica a facilidade de detectar o risco durante os testes. Essa matriz pode auxiliar na identificação e no gerenciamento dos riscos mais críticos durante o processo de teste.



**Entrada Prompt ChatGPT**:

Poderia justificar os riscos de cada cenário

**Saída**:

1. **Acesso ao atlas anatômico:**
    - Risco: Falha ao exibir o atlas anatômico.
    - Justificativa: Se o aplicativo não exibir corretamente o atlas anatômico, os usuários não conseguirão acessar as informações essenciais sobre os sistemas do corpo humano. Isso compromete a funcionalidade principal do aplicativo e afeta negativamente a experiência do usuário.
2. **Interface intuitiva e de fácil navegação:**
    - Risco: Interface confusa e difícil de navegar.
    - Justificativa: Uma interface confusa e difícil de navegar dificulta a utilização eficiente do aplicativo. Os usuários podem ficar frustrados, ter dificuldade em encontrar as informações desejadas e perder tempo na busca por funcionalidades específicas. Isso compromete a usabilidade do aplicativo e impacta negativamente a experiência do usuário.
3. **Interação com modelos anatômicos em 3D:**
    - Risco: Falha na visualização dos modelos em 3D.
    - Justificativa: Se os modelos anatômicos em 3D não forem visualizados corretamente, os usuários não poderão explorar e examinar as estruturas anatômicas de forma adequada. Isso compromete a compreensão detalhada das estruturas e a capacidade de aprendizado do usuário.
4. **Informações detalhadas sobre estruturas anatômicas:**
    - Risco: Falta de informações detalhadas sobre estruturas.
    - Justificativa: Se o aplicativo não fornecer informações detalhadas sobre as estruturas anatômicas, os usuários podem ficar com dúvidas sobre a nomenclatura, função e relacionamentos entre as estruturas. Isso limita a utilidade educacional do aplicativo e compromete a qualidade do conteúdo fornecido.
5. **Anotações e marcações nas estruturas anatômicas:**
    - Risco: Incapacidade de realizar anotações e marcações.
    - Justificativa: A funcionalidade de realizar anotações e marcações nas estruturas anatômicas é importante para que os usuários possam registrar observações e revisar informações importantes durante o estudo. Se essa funcionalidade estiver ausente ou apresentar falhas, os usuários perderão a oportunidade de aprofundar seu aprendizado e registrar suas observações de forma eficaz.

Essas justificativas destacam a importância de identificar e mitigar os riscos associados a cada cenário de teste, visando garantir a qualidade e a eficácia do aplicativo móvel no cumprimento dos critérios de aceitação estabelecidos.

- **Possíveis Falhas a serem geradas**

**Entrada Prompt ChatGPT**:

Poderia me dar exemplos de possíveis falhas geradas pelo desenvolvimento

**Saída**:

1. **Falha de conexão**: O aplicativo não consegue se conectar à fonte de dados necessária para exibir o atlas anatômico, resultando em falta de acesso às informações anatômicas.
2. **Interface confusa**: A interface do aplicativo apresenta um layout desorganizado, falta de hierarquia visual adequada e elementos de navegação mal posicionados, dificultando a compreensão e a navegação do usuário.
3. **Problemas de renderização 3D**: Os modelos anatômicos em 3D não são renderizados corretamente, resultando em distorções visuais, falta de detalhes ou falhas na interação com as estruturas.
4. **Informações incompletas**: Algumas estruturas anatômicas não possuem informações detalhadas associadas, como nome, função e relações com outras estruturas, resultando em lacunas de conhecimento para os usuários.
5. **Funcionalidade de anotações e marcações com falhas**: Os recursos de anotações e marcações nas estruturas anatômicas não funcionam corretamente, levando à perda de anotações feitas pelo usuário, incapacidade de realizar anotações ou marcações múltiplas, ou exibição incorreta das anotações na visualização.
6. **Problemas de desempenho**: O aplicativo pode apresentar lentidão durante a navegação, com carregamentos demorados das informações anatômicas ou resposta lenta aos comandos de interação com os modelos 3D.
7. **Erros de compatibilidade**: O aplicativo pode apresentar incompatibilidades com determinados dispositivos móveis, sistemas operacionais ou versões específicas, resultando em problemas de funcionalidade ou exibição inadequada.
8. **Bugs e crashes**: O aplicativo pode conter erros de programação (bugs) que causam falhas, instabilidades e até mesmo encerramento inesperado (crashes) durante o uso.

Esses são apenas alguns exemplos de falhas que podem ocorrer durante o desenvolvimento do aplicativo. É importante realizar testes abrangentes para identificar e corrigir essas falhas antes do lançamento, garantindo um produto final de alta qualidade.


























