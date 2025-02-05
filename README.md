# Teste técnico QA Compliense Station 

## Bug Reports

### Bug ao deletar usuário
- **ID**: BUG-001
- **Título**: Deletar usuário
- **Severidade**: alta
- **Status**: Aberto
- **Descrição**: Ao clicar no icone de deletar não acontece a exclusão do usuário
- **Passos para Reproduzir**:
  1. Acessar a tela de listagem de usuários
  2. Clicar no icone de lixeira
- **Comportamento Esperado**: Remoção do usuário da lista de usuários
- **Comportamento Atual**: Não exclusão do usuário da lista
- **Ambiente**: Desenvolvimento
- **Data de Identificação**: 02/02/2025

### Bug ao editar usuário
- **ID**: BUG-002
- **Título**: Editar usuário
- **Severidade**: alta
- **Status**: aberto
- **Descrição**: Quando clicado no icone de editar não acontece nada
- **Passos para Reproduzir**:
  1. Acessar a tela de listagem de usuário
  2. Clicar no icone de editar
- **Comportamento Esperado**: Possivel edição de algum item no cadastro
- **Comportamento Atual**: Não acontece nada quando clicado no icone de editar
- **Ambiente**: Desenvolvimento
- **Data de Identificação**: 03/02/2025

### Bug Cadastro data de nascimento
- **ID**: BUG-003
- **Título**: Cadastro data de nascimento  
- **Severidade**: media
- **Status**: aberto
- **Descrição**: Escolhido uma determinada data quando clicado em salvar na tela de listagem apresenta-se a data um dia antes da data selecionada
- **Passos para Reproduzir**:
  1. Clicar em novo usuário
  2. Cadastrar data de nascimento 
  3. Clicar em salvar
  4. Acessar a tela de listagem de usuário
- **Comportamento Esperado**: Aparecer na tela principal o dia correto que foi selecionado
- **Comportamento Atual**: A data aparece um dia anterior ao dia escolhido
- **Ambiente**: Desenvolvimento
- **Data de Identificação**: 03/02/2025

### Bug Input telefone
- **ID**: BUG-004
- **Título**: Cadastro input telefone
- **Severidade**: alta
- **Status**: Aberto
- **Descrição**: Na documentação do projeto é dito que o campo de telefone é de preenchimento
  obrigatório, mas na aplicação não está sendo obrigatório o preenchimento
- **Passos para Reproduzir**:
  1. Clicar em novo usuário
  2. Preencher o cadastro deixando o input telefone em branco
  3. Clicar em salvar
- **Comportamento Esperado**: Mensagem alertando q é obrigatório o preenchimento do input telefone 
- **Comportamento Atual**: Não está sendo obrigatório preencher o input
- **Ambiente**: Desenvolvimento
- **Data de Identificação**: 03/02/2025

### Bug data de nascimento inválida
- **ID**: BUG-005
- **Título**: Data inválida
- **Severidade**: media
- **Status**: aberto
- **Descrição**: Após selecionar uma data inválida a aplicação quebrou
- **Passos para Reproduzir**:
  1. Clicar em novo usuário
  2. Adicionar uma data inválida
  3. Clicar em salvar
- **Comportamento Esperado**: Mensagem de erro após selecionar uma data inválida
- **Comportamento Atual**: A aplicação quebrou
- **Ambiente**: desenvolvimento
- **Data de Identificação**: 04/02/2025



## Sugestões de Melhorias


### Input e-mail
- **ID**: MEL-001
- **Título**: Utilização de "type=email" no input
- **Prioridade**: Média
- **Descrição**: Utilizar type email no input
- **Justificativa**: Para melhorar a validação dos dados adicionados no input
- **Benefícios Esperados**: 
  - Bloqueio de dados inesperados
  - Melhor validação 
  - Feedback de erro ao colocar dado inesperado
- **Impacto**: Baixo - Requer alterações no frontend 
- **Data da Sugestão**: 02/02/2025

### Responsividade
- **ID**: MEL-002
- **Título**: Responsividade para mobile  
- **Prioridade**: media
- **Descrição**: Responsividade para telas menores 
- **Justificativa**: Melhorar a visibilidade para o cliente 
- **Benefícios Esperados**:
  - Melhor visualização para o cliente
  - Proporcionar uma experiência consistente e adaptável
  - Aumentar a satisfação do cliente 
- **Impacto**: Baixo - Requer alterações no frontend
- **Data da Sugestão**: 03/02/2025

### Input telefone
- **ID**: MEL-003
- **Título**: Input telefone
- **Prioridade**: média
- **Descrição**:  utilizar type number no input telefone
- **Justificativa**:  Para aceitar somente números no input
- **Benefícios Esperados**:
  - Bloqueio de dados inesperados 
  - Melhor validação
  - Feedback de erro ao colocar dado inesperado
- **Impacto**: Baixo - Requer alterações no frontend
- **Data da Sugestão**: 03/02/2025

### Máscara no input de número
- **ID**: MEL-004
- **Título**: Input número
- **Prioridade**: baixa
- **Descrição**: Adicionar parênteses no DDD do input de telefone
- **Justificativa**: Para facilitar a leitura e a validação dos dados inseridos pelo usuário
- **Benefícios Esperados**: 
  - Facilitar o entendimento do campo
  - Evita a inserção de caracteres indesejáveis por parte do usuário
- **Impacto**: Baixo - Requer alterações no frontend 
- **Data da Sugestão**: 03/02/2025

### Definir quantidade de digitos no input telefone
- **ID**: MEL-005
- **Título**: Input telefone, minimo e máxima quantidade de digitos
- **Prioridade**: baixa
- **Descrição**: Definir uma quantidade minima e máxima de digitos no input de telefone
- **Justificativa**: Para facilitar a leitura e a validação dos dados inseridos pelo usuário
- **Benefícios Esperados**: 
  - Evitar erros de digitação do cliente
  - Previnir que foi preenchido corretamente este campo 
- **Impacto**: Baixo - Requer alterações no frontend 
- **Data da Sugestão**: 03/02/2025

### Números inteiros no input de números
- **ID**: MEL-006
- **Título**: Definir para usar apenas números inteiros no input de telefone
- **Prioridade**: media
- **Descrição**: Bloquear números reais e permitir apenas números inteiros 
- **Justificativa**: Para o campo seja preenchido corretamente
- **Benefícios Esperados**:
  - Validação do cadastro
  - Previnir erro de digitação
- **Impacto**: Baixo - Requer alterações no frontend
- **Data da Sugestão**: 04/02/2025

### Input nome
- **ID**: MEL-007
- **Título**: Input nome
- **Prioridade**: Baixa
- **Descrição**: Validar para ter no minimo três caracteres obrigatórios no input nome 
- **Justificativa**: Para melhor validação do cadastro  
- **Benefícios Esperados**: 
  - Bloqueio de dados inesperados
  - Melhor validação do cadastro
- **Impacto**: Baixo - Requer alterações no frontend
- **Data da Sugestão**: 03/02/2025

### Cadastro de usuário
- **ID**: MEL-008
- **Título**: Cadastro de novo usuário
- **Prioridade**: média
- **Descrição**: Validar para não permitir que dois usuários possuem o mesmo email
- **Justificativa**: Para validar o cadastro corretamente
- **Benefícios Esperados**: 
  - Bloqueio de dados iguais
  - Garantir que não tenha dois usuários com as mesmas informações
  - Validação do cadastro
- **Impacto**: Baixo - Requer alterações no frontend
- **Data da Sugestão**: 03/02/2025

### Input data de nascimento
- **ID**: MEL-009
- **Título**: Bloqueio de datas acima do ano atual
- **Prioridade**: Média
- **Descrição**: Bloquear datas acima do ano de 2025
- **Justificativa**: Para evitar erro no preenchimento da data de nascimento
- **Benefícios Esperados**: 
  - Mensagem de erro ao selecionar uma data que não está disponivel
  - Previnir erro de digitação 
- **Impacto**: Baixo - Requer alterações no frontend 
- **Data da Sugestão**: 03/02/2025

### Aréa de cadastro 
- **ID**: MEL-010
- **Título**: Caracteres especias no nome
- **Prioridade**: Baixa
- **Descrição**: Bloqear o uso de caracteres especiais no input nome
- **Justificativa**: Para não haver erro de digitação 
- **Benefícios Esperados**:
  - Evitar qualquer tipo de simbolo indesejado
  - Melhor leitura do cadastro
- **Impacto**: Baixo - Requer alterações no frontend 
- **Data da Sugestão**: 03/02/2025

### Mensagem de confirmação após o cadastro
- **ID**: MEL-011
- **Título**: Mensagem de confirmação 
- **Prioridade**: Baixa
- **Descrição**: Na área de cadastro quando clicado no botão de salvar aparecer
  uma mensagem de validação do cadastro de um novo usuário
- **Justificativa**: Para melhorar a interação com o usuário
- **Benefícios Esperados**: 
  - Feedback de que foi feito corretamente o cadastro
- **Impacto**: Baixo - Requer alterações no frontend 
- **Data da Sugestão**: 04/02/2025


## Casos de Teste (Gherkin) 
### Feature: Cadastro de usuário

#### Cenário: Cadastro com sucesso
```gherkin
Dado que estou na tela de cadastro do usuário
E todos os campos obrigatórios estão preenchidos corretamente
Quando clico no botão "Salvar"
Então o sistema deve salvar o registro com sucesso
E redirecionar para a tela de listagem mostrando
o novo usuário criado
```

#### Cenário: Tentativa de cadastro sem campos obrigatórios
```gherkin
Dado que estou na tela de cadastro 
E deixei de preencher campos obrigatórios
Quando clico no botão "Salvar"
Então o sistema deve exibir mensagens de validação
E destacar os campos obrigatórios não preenchidos
```

#### Cenário: Tentativa de cadastro com o mesmo email
```gherkin
Dado que estou na tela de cadastro 
e preencho o campo de email com um email já cadastrado
Quando clico no botão de salvar
Então o sistema deve exibir uma mensagem de erro ao criar usuário
e destacar o campo de email
```

#### Cenário: Cancelar cadastro de novo usuário
```gherkin
Dado que estou na tela de cadastro e fiz
o preenchimento dos campos obrigatórios
Quando clico no icone de fechar a tela de cadastro
Então deve me direcionar a página de listagem de usuário
cancelando as informações colocadas no cadastro
```

### Feature: Tela de listagem de usuários

#### Cenário: Deletar usuário
```gherkin
Dado que estou na tela de listagem de usuário
Quando cliclo no icone de deletar usuário
Então deve exibir uma mensagem "usuário deletado com sucesso",
e deletar o usuário selecionado da tela de listagem
```

#### Cenário: Editar usuário
```gherkin
Dado que estou na tela de listagem de usuários
Quando clico no icone de editar usuário
Então deve abrir uma tela de edição das informações
do usuário
```


## Resultados dos Casos de Teste

### Sumário Executivo
- **Total de Casos de Teste**: 6
- **Casos Bem-Sucedidos**: 2
- **Casos Falhos**: 4
- **Taxa de Sucesso**: 33.33%

### Detalhamento dos Resultados

#### ✅ Casos Bem-Sucedidos
1. **Cadastro com Sucesso**
   - Status: PASSOU
   - Data da Execução: 04/02/2025
   - Observações: Fluxo principal de cadastro funcionando conforme esperado

2. **Cancelar Cadastro de Novo Usuário**
   - Status: PASSOU
   - Data da Execução: 04/02/2025
   - Observações: Funcionalidade de cancelamento operando corretamente

#### ❌ Casos Falhos
1. **Tentativa de Cadastro sem Campos Obrigatórios**
   - Status: NÃO PASSOU
   - Data da Execução: 04/02/2025
   - Motivo da Falha: Validação de campos obrigatórios não está funcionando
   - Relacionado ao Bug: BUG-004

2. **Tentativa de Cadastro com o Mesmo Email**
   - Status: NÃO PASSOU
   - Data da Execução: 04/02/2025
   - Motivo da Falha: Sistema não valida duplicidade de email
   - Relacionado à Melhoria: MEL-008

3. **Deletar Usuário**
   - Status: NÃO PASSOU
   - Data da Execução: 04/02/2025
   - Motivo da Falha: Funcionalidade de exclusão não está respondendo
   - Relacionado ao Bug: BUG-001

4. **Editar Usuário**
   - Status: NÃO PASSOU
   - Data da Execução: 04/02/2025
   - Motivo da Falha: Funcionalidade de edição não está respondendo
   - Relacionado ao Bug: BUG-002
