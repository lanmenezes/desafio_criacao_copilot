# Desafio de Criação do Copilot usando Copilot Studio

## 1. Criando uma Conta no Microsoft 365
Antes de iniciar, é necessário criar uma conta no Microsoft 365 ou conectar-se a uma conta existente.

## 2. Criando um Ambiente e uma Solução

### Criando um Ambiente
Acesse o link [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/environments) e siga os passos abaixo:
1. Clique em "Novo".
2. Escolha um nome para o ambiente.
3. Selecione a região desejada.
4. Escolha o tipo "Desenvolvedor".
5. Adicione uma descrição para o ambiente.

> **Nota:** Escolhendo o tipo "Desenvolvedor", as opções "Adicionar armazenamento de dados do Dataverse" e "Pagar conforme o uso com o Azure" não poderão ser alteradas.

Aguarde a criação do ambiente antes de prosseguir para a próxima etapa.

### Criando uma Solução
A solução organiza os componentes do projeto e facilita a implantação em produção.

1. Acesse [Power Apps](https://make.powerapps.com/).
2. Certifique-se de escolher o ambiente criado anteriormente.
3. No menu à esquerda, clique em "Solutions".
4. Clique em "New Solution".
5. Preencha os campos necessários:
   - **Publisher:** Pode ser customizado com um nome identificador do desenvolvedor ou empresa.
   - **Version:** Pode ser ajustado de acordo com os padrões de versionamento adotados.
6. Clique em "Criar" e aguarde a criação da solução.

## 3. Criando um Copilot
Com o ambiente e a solução prontos, acesse [Copilot Studio](https://copilotstudio.microsoft.com) e selecione o ambiente criado.

Existem três formas principais de criar um Copilot:

### Criar Baseado em Modelos
Os modelos fornecidos pela Microsoft facilitam a criação do Copilot, mas podem variar conforme a região.

1. Escolha um modelo.
2. Forneça um nome, uma descrição e as instruções. A instrução é um prompt, força o Copilot a responder conforme desejado.
3. Personalize o ícone e adicione idiomas, se necessário.

Os modelos possuem:
- Base de dados existente.
- Ações, gatilhos e tópicos pré-configurados.

Criar o Copilot baseado em modelos te dá uma visão geral da arquitetura do Copilot Studio.

### Criar Baseado em IA
1. Na tela inicial, forneça um prompt descrevendo o objetivo do Copilot.
2. Utilize prompts em inglês para melhores resultados.


### Criar Copilot em Branco
1. Selecione a opção "Criar um modelo em branco". É sempre a primeira opção da página inicial.
2. Informe os dados solicitados por meio do chat ou pule diretamente para o painel de configuração.
3. Configure:
   - Idioma principal.
   - Ícone.
   - Descrição e prompt.
4. **Não** adicione a base de conhecimento na criação. Primeiro finalize o Copilot e depois forneça a base de dados.
5. Em "Opções Avançadas", selecione a solução criada no início, para organizar o seu projeto.

---

Este documento fornece um guia para a criação de um Copilot usando o Copilot Studio. Para mais detalhes, consulte a documentação oficial da Microsoft no link [Documentação oficial do Copilot Studio](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/)

