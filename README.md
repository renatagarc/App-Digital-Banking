# App digital banking

### Escopo versao 1.0

1. Cadastro e autenticação de usuários: Permitir que os usuários criem contas e façam login no aplicativo.
    1. Quais funções deveriam existir no cadastro de contas?
        1. Validação de dados: Verificar se os dados fornecidos pelo usuário são válidos e estão completos antes de permitir o cadastro.
        1. Criação de conta: Armazenar as informações fornecidas pelo usuário (nome, email, senha, etc.) em um banco de dados.
        1. Envio de confirmação de email: Enviar um email de confirmação para o endereço de email fornecido pelo usuário, para garantir que ele tenha acesso ao endereço de email.
        1. Verificação de email: Verificar se o endereço de email fornecido pelo usuário é válido e não está sendo usado por outra conta.
        1. Criação de senha segura: Forçar o usuário a criar uma senha segura, com uma combinação de letras, números e caracteres especiais.
        1. Armazenamento de senha seguro: Armazenar a senha criptografada de forma segura, para evitar vazamentos de dados.
        1. Autenticação: Permitir que o usuário faça login na sua conta usando seu email e senha.
        1. Geração de token: Gerar um token de acesso que será usado para autenticação em requisições futuras.
        1. Envio de informações de conta: Enviar informações sobre a conta criada para o usuário, como saldo inicial, limite de crédito, etc.
    1. Quais informacoes deveria existir na conta criada
        1. Nome completo: O nome completo do usuário, que pode ser usado para identificação e contato.
        1. Endereço de email: O endereço de email do usuário, que é usado como nome de usuário para fazer login e para contato.
        1. Senha: A senha criptografada do usuário, usada para autenticar o usuário.
        1. Informações bancarias: Numero da conta, agencia, banco e CPF/CNPJ.
        1. Data de nascimento: A data de nascimento do usuário, que pode ser usada para verificação de idade ou para identificação.
        1. Telefone: O número de telefone do usuário, que pode ser usado para contato ou para envio de mensagens de verificação.
        1. Endereço: O endereço do usuário, que pode ser usado para envio de correspondência ou para verificação de residência.
        1. Saldo: O saldo atual da conta do usuário.
        1. Limite de crédito: O limite de crédito disponível para o usuário.
        1. Histórico de transações: Um registro das transações feitas pela conta do usuário.
        1. Token: Um token gerado para cada usuário para autenticação.
        1. Data de criação da conta: A data em que a conta foi criada.
        1. Data da última atualização: A data da última atualização dos dados da conta.
1. Gerenciamento de contas: Os usuários podem visualizar seus saldos, histórico de transações e detalhes das suas contas.
    1. Quais funções deveriam existir no "Gerenciamento de contas"
        1. Visualização de saldo: Permitir que o usuário veja o saldo atual da sua conta.
        1. Histórico de transações: Permitir que o usuário veja o histórico de transações da sua conta, incluindo detalhes como data, hora, valor e descrição da transação.
        1. Extrato: Permitir que o usuário baixe ou visualize o extrato de sua conta, com informações sobre transações e saldo.
        1. Alteração de dados da conta: Permitir que o usuário altere informações da sua conta, como endereço, telefone, e-mail, senha.
        1. Bloqueio de conta: Permitir que o usuário bloqueie sua conta temporariamente ou permanentemente, para evitar transações não autorizadas.
        1. Exclusão de conta: Permitir que o usuário exclua sua conta permanentemente.
        1. Acompanhamento de limite de crédito: Permitir que o usuário veja o limite de crédito disponível e o usado.
        1. Notificações: Enviar notificações para o usuário sobre transações, limite de crédito e saldo.
        1. Suporte ao cliente: Fornecer um canal de suporte ao cliente para ajudar o usuário com dúvidas ou problemas relacionados à sua conta.
        1. Segurança: Implementar medidas de segurança para proteger as informações pessoais e financeiras do usuário.
    1. Quais informacoes deveria existir no "Gerenciamento de contas"
        1. Saldo: O saldo atual da conta do usuário.
        1. Limite de crédito: O limite de crédito disponível para o usuário.
        1. Histórico de transações: Um registro das transações feitas pela conta do usuário, incluindo data, hora, valor e descrição da transação.
        1. Extrato: Um relatório detalhado das transações da conta do usuário, incluindo data, hora, valor e descrição da transação.
        1. Dados da conta: Informações pessoais e bancarias do usuário, como nome, endereço, telefone, e-mail, agencia, conta, CPF/CNPJ.
        1. Status da conta: Informação sobre se a conta está ativa ou bloqueada.
        1. Notificações: Um registro de notificações enviadas para o usuário sobre transações, limite de crédito e saldo.
        1. Data da última atualização: A data da última atualização dos dados da conta.
        1. Token de acesso: Um token gerado para cada usuário para autenticação.
        1. Informação de investimentos: histórico, saldo e informação de investimentos relacionados a conta do usuário.
1. Transferências: Os usuários podem enviar dinheiro para outros usuários do aplicativo ou para contas bancárias externas.
    1. Quais funções deveriam existir no "Transferências"
        1. Validação de dados: Verificar se os dados fornecidos pelo usuário (nome do destinatário, número de conta, valor, etc.) são válidos antes de permitir a transferência.
        1. Verificação de saldo: Verificar se o usuário tem saldo suficiente para realizar a transferência.
        1. Transferência para conta bancária: Permitir que o usuário transfira dinheiro para outra conta bancária, seja ela da mesma instituição ou de outra.
        1. Transferência para outro usuário do aplicativo: Permitir que o usuário transfira dinheiro para outro usuário do aplicativo.
        1. Confirmação de transferência: Exibir uma tela de confirmação com todos os detalhes da transferência, incluindo valor, destinatário e data prevista para transferência.
        1. Notificação: Enviar notificações para o usuário e para o destinatário sobre a transferência, incluindo valor, data e status da transferência.
        1. Histórico de transferências: Armazenar um registro de todas as transferências realizadas pelo usuário, incluindo detalhes como valor, destinatário e data.
        1. Suporte ao cliente: Fornecer um canal de suporte ao cliente para ajudar o usuário com dúvidas ou problemas relacionados à transferência.
        1. Segurança: Implementar medidas de segurança para proteger as informações pessoais e financeiras do usuário e garantir a segurança das transferências.
    1. Quais informacoes deveria existir no "Transferências"
        1. Nome do destinatário: O nome completo do destinatário da transferência.
        1. Número de conta: O número da conta bancária do destinatário.
        1. Banco: O banco onde a conta do destinatário está registrada.
        1. Agencia: A agencia da conta do destinatário.
        1. CPF/CNPJ: O CPF ou CNPJ do destinatário.
        1. Valor: O valor da transferência.
        1. Data da transferência: A data em que a transferência foi realizada.
        1. Data prevista para transferência: A data prevista para a transferência ser processada e concluida.
        1. Status da transferência: Informação sobre o status da transferência (pendente, processando, concluída, cancelada).
        1. Descrição: Uma descrição da transferência, se fornecida pelo usuário.
        1. Notificações: Um registro de notificações enviadas para o usuário e o destinatário sobre a transferência.
        1. Histórico de transferências: Um registro das transferências realizadas pelo usuário, incluindo detalhes como destinatário, valor e data.
1. Pagamentos: Os usuários podem pagar contas, fazer compras e utilizar o cartão de débito virtual do aplicativo para pagamentos.
    1. Quais funções deveriam existir no "Pagamentos"
        1. Validação de dados: Verificar se os dados fornecidos pelo usuário (nome do destinatário, número de conta, valor, etc.) são válidos antes de permitir o pagamento.
        1. Verificação de saldo: Verificar se o usuário tem saldo suficiente para realizar o pagamento.
        1. Pagamento para conta bancária: Permitir que o usuário faça pagamentos para outra conta bancária, seja ela da mesma instituição ou de outra.
        1. Pagamento para estabelecimentos: Permitir que o usuário efetue pagamentos em estabelecimentos comerciais (lojas, restaurantes, etc.) através do aplicativo.
        1. Pagamento para prestadores de serviços: Permitir que o usuário efetue pagamentos para prestadores de serviços (prestadores de serviços financeiros, contas de luz, água, etc.) através do aplicativo.
        1. Confirmação de pagamento: Exibir uma tela de confirmação com todos os detalhes do pagamento, incluindo valor, destinatário e data prevista para pagamento.
        1. Notificação: Enviar notificações para o usuário e para o destinatário sobre o pagamento, incluindo valor, data e status do pagamento.
        1. Histórico de pagamentos: Armazenar um registro de todos os pagamentos realizados pelo usuário, incluindo detalhes como valor, destinatário e data.
        1. Suporte ao cliente: Fornecer um canal de suporte ao cliente para ajudar o usuário com dúvidas ou problemas relacionados ao pagamento.
        1. Segurança: Implementar medidas de segurança para proteger as informações pessoais e financeiras do usuário e garantir a segurança dos pagamentos.
    1. Quais informacoes deveria existir no "Pagamentos"
        1. Nome do destinatário: O nome completo do destinatário do pagamento.
        1. Número de conta: O número da conta bancária do destinatário.
        1. Banco: O banco onde a conta do destinatário está registrada.
        1. Agencia: A agencia da conta do destinatário.
        1. CPF/CNPJ: O CPF ou CNPJ do destinatário.
        1. Valor: O valor do pagamento.
        1. Data do pagamento: A data em que o pagamento foi realizado.
        1. Data prevista para pagamento: A data prevista para o pagamento ser processado e concluído.
        1. Status do pagamento: Informação sobre o status do pagamento (pendente, processando, concluído, cancelado).
        1. Descrição: Uma descrição do pagamento, se fornecida pelo usuário.
        1. Notificações: Um registro de notificações enviadas para o usuário e o destinatário sobre o pagamento.
        1. Histórico de pagamentos: Um registro dos pagamentos realizados pelo usuário, incluindo detalhes como destinatário, valor e data.
1. Segurança: Implementar medidas de segurança para proteger as informações pessoais e financeiras dos usuários.
    1. Quais funções deveriam existir no "Segurança"
        1. Autenticação de usuário: Verificar a identidade do usuário através de métodos de autenticação, como senha, token, reconhecimento facial ou digital.
        1. Criptografia de dados: Criptografar informações sensíveis, como senhas e dados bancários, para protegê-las de acessos não autorizados.
        1. Proteção contra fraudes: Implementar medidas de segurança para detectar e prevenir fraudes, como verificação de endereço IP e comportamento anormal do usuário.
        1. Alertas de segurança: Enviar alertas para o usuário em caso de tentativas de acesso não autorizadas ou atividade suspeita.
        1. Backup de dados: Armazenar cópias de segurança dos dados do usuário para protegê-los em caso de perda ou danificação.
        1. Atualização de segurança: Manter o aplicativo atualizado com as últimas correções de segurança e atualizações de segurança.
        1. Política de privacidade: Ter uma política de privacidade clara e transparente para informar os usuários sobre como suas informações serão usadas e protegidas.
        1. Monitoramento de segurança: Monitorar constantemente o aplicativo e as transações para detectar e prevenir qualquer atividade suspeita.
        1. Suporte ao cliente: Fornecer suporte ao cliente para ajudar os usuários com problemas relacionados à segurança e fornecer instruções sobre como
    1. Quais informacoes deveria existir no "Segurança"
        1. Informações de autenticação: Dados utilizados para verificar a identidade do usuário, como senha, token de acesso, reconhecimento facial ou digital.
        1. Informações criptografadas: Dados sensíveis, como senhas e informações bancárias, que foram criptografados para proteção contra acessos não autorizados.
        1. Registros de acesso: Um registro de todas as tentativas de acesso, incluindo data, hora e origem do acesso.
        1. Alertas de segurança: Um registro de alertas de segurança enviados para o usuário, incluindo data, hora e tipo de alerta.
        1. Informações de backup: Informações sobre quando os dados do usuário foram backupados e onde essas cópias de segurança estão armazenadas.
        1. Informações de atualização: Data e detalhes das últimas atualizações de segurança aplicadas ao aplicativo.
        1. Política de privacidade: A política de privacidade do aplicativo, que especifica como as informações do usuário serão usadas e protegidas.
        1. Registros de monitoramento de segurança: Um registro de todas as atividades de monitoramento de segurança realizadas, incluindo data, hora e resultados.
        1. Informações de suporte ao cliente

1.  Design System pastas
```
src/
  assets/
  components/
    common/
    form/
    navigation/
  pages/
    account/
      account.js
      account.scss
      accountActions.js
      accountReducer.js
    transfer/
      transfer.js
      transfer.scss
      transferActions.js
      transferReducer.js
    payments/
      payments.js
      payments.scss
      paymentsActions.js
      paymentsReducer.js
    security/
      security.js
      security.scss
      securityActions.js
      securityReducer.js
  services/
    api.js
    auth.js
    storage.js
  store/
    index.js
  App.js
```
Nesta estrutura, cada página (Account, Transfer, Payments, Security) contém seus próprios arquivos de estilo (*.scss), ações (Actions.js), reducers (Reducer.js) e componentes (page.js) para garantir a separação de responsabilidades.
Os componentes comuns são guardados na pasta "components" e os serviços, como autenticação e armazenamento são guardados na pasta "services".
A pasta "store" contém o arquivo index.js onde é configurado o gerenciamento de estado

# Alguns exemplos de componentes que eu criaria na pasta "components" seriam:
    1. Header: Um componente para exibir o cabeçalho do aplicativo com o logo e as opções de navegação.
    1. Footer: Um componente para exibir o rodapé do aplicativo com links de contato e outras informações.
    1. Input: Um componente para exibir campos de entrada de dados comuns, como nome, endereço, etc.
    1. Button: Um componente para exibir botões comuns como "Enviar", "Cancelar" etc.
    1. Card: Um componente para exibir informações em formato de cartão, como histórico de transações, detalhes da conta etc.
    1. Form: Um componente para exibir formulários comuns, como cadastro de conta, transferência e pagamentos.
    1. Modal: Um componente para exibir modais comuns, como confirmação de transferência e pagamento.
# Alguns exemplos de nomes dos arquivos seriam:
    1. header.js
    1. footer.js
    1. input.js
    1. button.js
    1. card.js
    1. form.js
    1. modal.js


# escopo versao 1.5
1. Investimentos: Oferecer aos usuários a opção de investir seu dinheiro em diferentes opções de investimento.
1. Gerenciamento de cartão de crédito: Os usuários podem visualizar seu limite de crédito, fatura e histórico de transações.
1. Suporte ao cliente: Fornecer suporte ao cliente para ajudar os usuários com quaisquer dúvidas ou problemas que possam surgir.

backend:

Criação de conta:
Endpoint: POST /accounts
Descrição: Cria uma nova conta bancária para o usuário.
Parâmetros: Nome do usuário, CPF/CNPJ, endereço, número de conta, banco, agência.

Gerenciamento de contas:
Endpoint: GET /accounts/{id}
Descrição: Recupera informações detalhadas sobre uma conta específica.
Parâmetros: ID da conta.
Endpoint: PUT /accounts/{id}
Descrição: Atualiza as informações de uma conta específica.
Parâmetros: ID da conta, novos dados da conta (opcional).
Endpoint: DELETE /accounts/{id}
Descrição: Exclui uma conta específica.
Parâmetros: ID da conta.

Transferências:
Endpoint: POST /transfers
Descrição: Cria uma nova transferência entre contas.
Parâmetros: ID da conta de origem, ID da conta de destino, valor da transferência.
Endpoint: GET /transfers/{id}
Descrição: Recupera informações detalhadas sobre uma transferência específica

Pagamentos:
Endpoint: POST /payments
Descrição: Cria um novo pagamento para um destinatário específico.
Parâmetros: ID da conta de origem, nome do destinatário, número de conta do destinatário, banco do destinatário, valor do pagamento.
Endpoint: GET /payments/{id}
Descrição: Recupera informações detalhadas sobre um pagamento específico.
Parâmetros: ID do pagamento.
Endpoint: PUT /payments/{id}
Descrição: Atualiza as informações de um pagamento específico.
Parâmetros: ID do pagamento, novos dados do pagamento (opcional).

Segurança:
Endpoint: POST /auth
Descrição: Autentica o usuário com suas credenciais.
Parâmetros: Nome de usuário, senha.
Endpoint: POST /logout
Descrição: Encerra a sessão do usuário atual.
Parâmetros: Nenhum.
Endpoint: POST /security/alerts
Descrição: Envia alertas de segurança para o usuário

```yml
openapi: 3.0.0
info:
  title: Banco Digital
  version: 1.0.0
servers:
  - url: https://api.banco-digital.com/v1
tags:
  - name: accounts
  - name: payments
  - name: transfer
  - name: utils
paths:
  /accounts/{id}:
    post:
      summary: Cria uma nova conta bancária
      tags:
        - accounts
      parameters:
        - in: path
          name: id
          required: true
          schema:
            type: string
      requestBody:
        required: true
        content:
          application/json:
            schema:
              type: object
              properties:
                name:
                  type: string
                cpf_cnpj:
                  type: string
                address:
                  type: string
                account_number:
                  type: string
                bank:
                  type: string
                agency:
                  type: string
      responses:
        201:
          description: Conta bancária criada com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  name:
                    type: string
                  cpf_cnpj:
                    type: string
                  address:
                    type: string
                  account_number:
                    type: string
                  bank:
                    type: string
                  agency:
                    type: string
    get:
      summary: Recupera informações detalhadas sobre uma conta específica
      tags:
        - accounts
      parameters:
        - in: path
          name: id
          required: true
          schema:
            type: string
      responses:
        200:
          description: Informações da conta recuperadas com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  name:
                    type: string
                  cpf_cnpj:
                    type: string
                  address:
                    type: string
                  account_number:
                    type: string
                  bank:
                    type: string
                  agency:
                    type: string
    put:
      summary: Atualiza as informações de uma conta específica
      tags:
        - accounts
      parameters:
        - name: id
          in: path
          required: true
          schema:
            type: string
      requestBody:
            required: true
            content:
              application/json:
                schema:
                  type: object
                  properties:
                    name:
                      type: string
                    cpf_cnpj:
                      type: string
                    address:
                      type: string
                    account_number:
                      type: string
                    bank:
                      type: string
                    agency:
                     type: string
      responses:
        204:
          description: Conta excluída com sucesso
    delete:
      summary: Exclui uma conta específica
      tags:
        - accounts
      parameters:
      - name: id
        in: path
        required: true
        schema:
          type: string
      responses:
        204:
          description: Conta excluída com sucesso
  /transfers/{id}:
    post:
      summary: Cria uma nova transferência entre contas
      tags:
        - transfer
      parameters:
        - name: id
          in: path
          required: true
          schema:
            type: string
      requestBody:
        required: true
        content:
          application/json:
            schema:
              type: object
              properties:
                source_account_id:
                  type: string
                destination_account_id:
                  type: string
                amount:
                  type: number
      responses:
        201:
          description: Transferência criada com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  source_account_id:
                    type: string
                  destination_account_id:
                    type: string
                  amount:
                    type: number
                  status:
                    type: string
    get:
      summary: Recupera informações detalhadas sobre uma transferência específica
      tags:
        - transfer
      parameters:
        - name: id
          in: path
          required: true
          schema:
            type: string
      responses:
        200:
          description: Informações da transferência recuperadas com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  source_account_id:
                    type: string
                  destination_account_id:
                    type: string
                  amount:
                    type: number
                  status:
                    type: string
  /payments/{id}:
    post:
      summary: Cria um novo pagamento para um destinatário específico
      tags:
        - payments
      parameters:
        - name: id
          in: path
          required: true
          schema:
            type: string
      requestBody:
        required: true
        content:
          application/json:
            schema:
              type: object
              properties:
                source_account_id:
                  type: string
                recipient_name:
                  type: string
                recipient_account_number:
                  type: string
                recipient_bank:
                  type: string
                amount:
                  type: number
      responses:
        201:
          description: Pagamento criado com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  source_account_id:
                    type: string
                  recipient_name:
                    type: string
                  recipient_account_number:
                    type: string
                  recipient_bank:
                    type: string
                  amount:
                    type: number
                  status:
                    type: string
    get:
      summary: Recupera informações detalhadas sobre um pagamento específico
      tags:
        - payments
      parameters:
        - name: id
          in: path
          required: true
          schema:
            type: string
      responses:
        200:
          description: Informações do pagamento recuperadas com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  source_account_id:
                    type: string
                  recipient_name:
                    type: string
                  recipient_account_number:
                    type: string
                  recipient_bank:
                    type: string
                  amount:
                    type: number
                  status:
                    type: string
    put:
      summary: Atualiza as informações de um pagamento específico
      tags:
        - payments
      parameters:
        - name: id
          in: path
          required: true
          schema:
            type: string
      requestBody:
        required: true
        content:
          application/json:
            schema:
              type: object
              properties:
                source_account_id:
                  type: string
                recipient_name:
                  type: string
                recipient_account_number:
                  type: string
                recipient_bank:
                  type: string
                amount:
                  type: number
      responses:
        200:
          description: Pagamento atualizado com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: string
                  source_account_id:
                    type: string
                  recipient_name:
                    type: string
                  recipient_account_number:
                    type: string
                  recipient_bank:
                    type: string
                  amount:
                    type: number
                  status:
                    type: string
  /auth:
    post:
      summary: Autentica o usuário com suas credenciais
      tags:
        - utils
      requestBody:
        required: true
        content:
          application/json:
            schema:
              type: object
              properties:
                username:
                  type: string
                password:
                  type: string
      responses:
        200:
          description: Usuário autenticado com sucesso
          content:
            application/json:
              schema:
                type: object
                properties:
                  token:
                    type: string
  /logout:
    post:
      summary: Encerra a sessão do usuário atual
      tags:
        - utils
      responses:
        204:
          description: Sessão encerrada com sucesso
  /security/alerts:
    post:
      summary: Envia alertas de segurança para o usuário
      tags:
        - utils
      requestBody:
        required: true
        content:
          application/json:
            schema:
              type: object
              properties:
                alert_type:
                  type: string
                message:
                  type: string
      responses:
        204:
          description: alertas de segurança enviado para o usuário
```
