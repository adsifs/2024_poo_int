# Caso de Uso: Gerenciamento de Funcionários

- **Ator Principal**: Administrador da Barbearia
- **Objetivo**: Permitir que o administrador cadastre, visualize, edite ou remova funcionários, armazenando as informações necessárias para organizar a equipe e seus papéis.

## Fluxo Principal

1. O administrador acessa o módulo de Gerenciamento de Funcionários no sistema.
2. O sistema exibe a lista de funcionários cadastrados com opções de **adicionar**, **editar** e **remover** funcionários.

### 2.1. Adicionar Funcionário
   - a. O administrador seleciona a opção de adicionar um novo funcionário.
   - b. O sistema apresenta um formulário para o preenchimento dos dados do funcionário.
   - c. O administrador insere o **nome**, **cargo**, uma **breve descrição** das responsabilidades ou especialidades do funcionário, e o **status** (com opções: ativo, férias, afastado, inativo).
   - d. O sistema valida os dados fornecidos e, em seguida, o administrador confirma o cadastro.
   - e. O sistema armazena as informações no banco de dados e exibe uma mensagem de sucesso indicando que o funcionário foi cadastrado.

### 2.2. Editar Funcionário
   - a. O administrador seleciona um funcionário existente na lista.
   - b. O sistema exibe um formulário com os dados atuais do funcionário.
   - c. O administrador altera o **nome**, **cargo**, **descrição** ou **status**, conforme necessário.
   - d. O sistema valida as alterações e o administrador confirma a edição.
   - e. O sistema atualiza as informações no banco de dados e exibe uma mensagem de sucesso indicando que os dados do funcionário foram atualizados.

### 2.3. Remover Funcionário
   - a. O administrador seleciona um funcionário para remover.
   - b. O sistema solicita uma confirmação de remoção.
   - c. O administrador confirma a remoção.
   - d. O sistema exclui o funcionário do banco de dados e exibe uma mensagem de sucesso.

## Fluxo Alternativo

- **2.1.d / 2.2.d. Dados inválidos**:
   - Se algum dado fornecido for inválido, o sistema informa o erro ao administrador e solicita a correção antes de permitir o cadastro ou a edição.

## Pré-condições

- O administrador deve estar autenticado no sistema para acessar o módulo de Gerenciamento de Funcionários.

## Pós-condições

- As informações do funcionário, incluindo o status, são adicionadas, atualizadas ou removidas do banco de dados conforme a ação realizada.
