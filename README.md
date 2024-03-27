# RF02 - Cadastrar Usuário

#### Autor: @brenoborgesbr - Breno Borges.

- - -
#### Revisor : @uGonzaguinha - Gustavo Gonzaga dos Santos.

| Item            | Descrição                                                              |
| --------------- | ---------------------------------------------------------------------- |
| Caso de uso     | RF02 - Efetuar Cadastro de Usuário.                                    |
| Resumo          | Este caso de uso descreve o processo pelo qual um usuário não registrado pode criar uma conta no site de agendamento de consulta, fornecendo as informações necessárias.|
| Ator principal  | Usuário não registrado                                                                                                        |
| Pré-condição| O usuário acessa a página inicial do site e  usuário seleciona a opção de registro de conta.|
|Pós-condições| O usuário acessa a página inicial do site e  usuário preenche as informações de registro de conta.      |
                                
## Descrição Sucinta:
Realiza o cadastramento dos usuários na plataforma
						
#### Fluxo principal:
1. o usuario ao abrir o link do site é encaminhado a pagina de login.
2. Nesse momento é exibido um botão com título “Cadastre-se” que redireciona o usuário à tela de Cadastro.
3. A aplicação dispõe ao autor um formulário para ser preenchido com seus respectivos dados.
4. Ao preencher os campos o autor confirma os dados no botão de “criar conta”.
5. Em seguida o ator passa para um processo de verificação a fim de confirmar sua conta recém criada.

                                
#### Fluxo alternativo:
 FA01 - Se o sistema detectar que as informações fornecidas são inválidas ou já existem em outra conta, ele notificará o usuário e solicitará que ele corrija os campos relevantes. 



#### Campos do formulário.

| Campo    | Obrigatório? | Editável? | Formato      |
| -------- | ------------ | --------- | ------------ |
| Nome     | Sim          | Sim       | Texto        |
| Email    | Sim          | Sim       | Texto        |
| Senha    | Sim          | Sim       | Texto        |
| CPF      | Sim          | Sim       | Alfanumérico |
| Endereço | Não          | Sim       | Texto        |
| Contato  | Sim          | Sim       | Numérico     |
| Gênero   | Sim          | Sim       | Checkbox     |