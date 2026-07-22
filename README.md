![icone_github](https://github.com/Wilkor/doc-clonebots/assets/34819624/15ef8fb6-2549-4f08-b4b2-1529be63b734)

# Como clonar e migrar fluxos, blocos e recursos de bots no Blip com CloneBots

O **CloneBots** aumenta a produtividade da equipe permitindo a clonagem da estrutura do Builder, variáveis, ações globais, regras de atendimento, gerenciamento de filas, respostas prontas e recursos de um bot para outro, além da mesclagem de blocos específicos através da funcionalidade Merge of Blocks.

**Palavras-chave:** CloneBots, Clonar Bot, Merge of Blocks, Chassi Bot, Broadcast Desk, Notificação Ativa

---

### 1. Vídeo demonstrativo
Assista aos vídeos abaixo para conferir demonstrações práticas da extensão:

- **Demonstração Geral de Funcionalidades:**  
  https://youtu.be/nmxkEgLyZz0

- **Resource and Builder Flow (Padrão Chassi):**  
  [![IMAGE_ALT](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/builderFlow2.png)](https://youtu.be/E8YskEEM5Pc)

### 2. Introdução
O **CloneBots** é uma extensão que permite duplicar a estrutura completa ou parcial de um bot para outro no Blip. Ideal para promover versões do bot de um ambiente BETA para PROD com agilidade e segurança.

### 3. Funcionalidades
O **CloneBots** oferece as seguintes funcionalidades:

- **Clone Builder**: Clonagem completa da estrutura do builder, ações globais, configurações gerais, recursos (conteúdos), gerenciamento de filas, respostas prontas e tags.
- **Merge of Blocks**: Clonagem individual de um ou mais blocos específicos (com blocos pré-setados para validações como e-mail e CPF).
- **Resource and Builder Flow (Padrão Chassi)**: Estrutura otimizada para bots desenvolvidos no padrão chassi (conceito .parse).
- **Broadcast Desk (Uso em Roteadores + WhatsApp)**: Integração para disparo de notificações ativas pelo Blip Desk definindo templates padrão (serviço pago).
- **Send Notification (Uso em Roteadores + WhatsApp)**: Envio de notificações ativas com inclusão de variáveis nos extras do contato.

A extensão **CloneBots** é suportada nos seguintes canais: **Blip / WhatsApp (para notificações ativas)**.

### 4. Instalação e Configuração
Após ativar a extensão através da Blip Store, ela deve ser instalada no bot de destino.

#### Passo a passo de Instalação e Uso:

1. Instale o **CloneBots** no seu bot destino;
2. Na aba **Clone Builder**, insira a chave **HTTP/key** do bot origem no campo *"Enter the source bot key"*;
3. Selecione as opções que deseja clonar:

![image](https://user-images.githubusercontent.com/34819624/231840840-50841104-9cdc-41b1-bb35-3456a4011d97.png)

- **Builder:** Clone da estrutura do builder + ações globais;
- **General Settings:** Copia configurações gerais do bot origem para o destino;
- **Resource:** Leva todo conteúdo (menu '...' -> conteúdo) do bot origem para o destino;
- **Queue Management:** Clona o gerenciamento de filas;
- **Ready Answers:** Clona as respostas prontas;
- **Tags:** Clona todas as tags.

4. Clique no botão **Clone** para transferir o fluxo.

*Obs: Prática recomendada: Montar um bot BETA, validar as funções, habilitar todas as opções e clonar para o bot de PROD.*

#### Uso da funcionalidade Merge of Blocks:
1. Insira a chave **HTTP/Key** do bot origem no campo **bot key** e clique em **get builder**;
2. Selecione o bloco desejado, mova para a caixa à direita e clique em **Merge**;
3. O bloco selecionado aparecerá no bot destino na mesma posição que estava no bot origem.

![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/merge-of-blocks.png)

### 5. Exemplos de Uso e Recursos Avançados

#### Resource and Builder Flow (Padrão Chassi)
Esta sessão é voltada para a criação de bots no padrão **chassi** (conceito .parse) na plataforma Blip, oferecendo:
- Redução de caixinhas, deixando o builder objetivo;
- Tracking automático gerado conforme navegação em inputs;
- Reaproveitamento de bots (altera apenas o recurso do chassi ao trocar de skill);
- Responsabilidade por bloco (Requisições trata chamadas/validações);
- Suporte a multicanal.

#### Broadcast Desk
Configuração de envio ativo direto pelo Blip Desk:
*(Obs: Serviço pago)*

![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/desk-configuration.png)

#### Send Notification
Envio de notificações ativas setando variáveis nos extras do contato:

![N|Solid](https://raw.githubusercontent.com/Wilkor/img-clonebots/main/Send-notification.png)

### 6. Suporte
Em caso de dúvidas ou necessidade de auxílio na configuração do CloneBots, entre em contato conosco:

- **E-mail**: contato@wconsulting.tech
- **Telefone/WhatsApp**: 1191628-2384
