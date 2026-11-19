# OmniLift app

**Gestão de manutenção de ascensores, instalações e avarias.**

A OmniLift liga o trabalho dos técnicos no terreno à consola de administração. A aplicação para telemóvel permite consultar instalações, registar manutenções e acompanhar avarias, utilizando os dados do servidor central.

<p align="center">
  <img src="imagens/omnilift-telemovel.png" alt="Ecrã inicial da OmniLift para telemóvel, com os menus Manutenção, Avarias, Instalações e Aplicação" width="340">
</p>

*Ecrã demonstrativo da aplicação. O nome apresentado é fictício; não são mostrados dados de clientes.*

## Manutenções, avarias e instalações no telemóvel

| Manutenções | Avarias | Instalações |
| :---: | :---: | :---: |
| <img src="imagens/omnilift-manutencoes-telemovel.png" alt="Manutenções por concluir com dados fictícios" width="240"> | <img src="imagens/omnilift-avarias-telemovel.png" alt="Avarias por resolver com dados fictícios" width="240"> | <img src="imagens/omnilift-instalacoes-telemovel.png" alt="Lista de instalações com moradas, números, contratos e lugares fictícios" width="240"> |

*Ecrãs demonstrativos com dados inteiramente fictícios: moradas, instalações, contratos, lugares, técnicos, contactos, ocorrências e datas. Nenhum registo real foi utilizado.*

Da esquerda para a direita: o técnico consulta e confirma as manutenções pendentes; acompanha as avarias e o respetivo responsável; e pesquisa instalações para consultar a sua ficha.

## Consola de administração

![Consola de administração da OmniLift com instalações, técnicos e rotas fictícios](imagens/omnilift-consola-administracao.png)

*Imagem demonstrativa: todas as moradas, números, localidades, técnicos, rotas e contagens apresentados são fictícios. Não contém dados reais de clientes.*

## Como funciona

### Acesso autorizado

O supervisor autoriza o equipamento antes da primeira utilização. O técnico entra com o seu próprio acesso e encontra os menus correspondentes às permissões concedidas. A administração gere os utilizadores e os equipamentos autorizados.

### Manutenções

Cada técnico consulta as manutenções por concluir das instalações que lhe estão atribuídas, com ou sem rota. O botão **Feito** pede confirmação antes de guardar o registo, com data e hora automáticas. O contador indica as manutenções pendentes.

No início de cada mês começa um novo ciclo. Os registos e os fechos anteriores ficam disponíveis para consulta na administração.

### Avarias

É possível registar uma avaria, indicar quem telefonou, descrever o problema e escolher o técnico responsável. Os técnicos com permissão para esta área podem consultar as avarias; o aviso é enviado ao técnico escolhido nos equipamentos com notificações ativadas.

Uma avaria pode ser passada a outro técnico. Para a dar como resolvida, é necessário confirmar e descrever o trabalho realizado, com a opção de enviar um e-mail ao cliente. As avarias por resolver transitam para o mês seguinte.

### Instalações

A pesquisa permite encontrar instalações pelo número, morada, código postal, localidade ou lugar, incluindo pesquisas sem acentos. Em instalações agrupadas, como **2033/4**, é possível pesquisar por **2033** ou **2034**.

Ao tocar na instalação, o técnico abre uma ficha de consulta com os dados necessários ao serviço. Os botões **E-mail** e **Navegação** permitem contactar o cliente e abrir o percurso na aplicação de mapas.

### Proximidade por GPS

Em Manutenção e Instalações, a aplicação pode apresentar primeiro as seis instalações mais próximas com coordenadas disponíveis, seguidas das restantes. A localização é atualizada enquanto estas páginas estão abertas e a aplicação está visível, mediante autorização do utilizador.

A posição do técnico é utilizada apenas no equipamento: não é enviada ao servidor nem guardada. O acompanhamento para ao sair destas páginas, minimizar ou fechar a aplicação.

### E-mail e notificações

O técnico revê e confirma a mensagem antes do envio pelo servidor. O cliente recebe o e-mail e o escritório recebe uma cópia. As notificações de novas avarias dependem da autorização no equipamento e do suporte do navegador e do sistema operativo.

### Consola de administração

A consola permite gerir instalações, técnicos, permissões, rotas e respetivas atribuições; consultar manutenções e avarias por mês; desativar e reativar clientes; e exportar informações das instalações para PDF.

## Utilização

A OmniLift é uma aplicação web com apresentação adaptada ao telemóvel e à consola de administração. O acesso operacional é reservado a utilizadores autorizados. É necessária ligação ao servidor para consultar dados atualizados e guardar alterações.

## Sobre este repositório

Este repositório contém apenas a apresentação da OmniLift e imagens demonstrativas. Não disponibiliza o software, o código-fonte, a base de dados, credenciais ou dados operacionais de clientes.

© 2026 Eduardo Arraia - OmniLift - Todos os direitos reservados.
