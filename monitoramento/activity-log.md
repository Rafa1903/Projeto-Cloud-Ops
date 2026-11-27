# Azure Activity Log e Service Health

Explicação de como funciona e a importância dos recursos Activity Log e Service Health.

## 1. Azure Activity Log

O **Azure Activity** Log é um recurso utilizado para consultar o histórico de atividades administrativas realizadas na assinatura do Azure.

Por meio dele, é possível acompanhar operações que aconteceram nos recursos, como criação, exclusão e alteração de configurações.

Essas informações ajudam a identificar quais operações foram realizadas e quando aconteceram.

### Informações registradas

O **Activity Log** apresenta informações relacionadas às operações administrativas, como:

- Nome da operação realizada.
- Recurso afetado.
- Data e horário da atividade.
- Resultado da operação.
- Informações sobre quem realizou a ação, quando disponíveis.

Por exemplo, imagine que uma máquina virtual foi excluída de uma assinatura.

Essa operação pode aparecer no histórico do Activity Log, permitindo identificar que houve uma exclusão e consultar os detalhes disponíveis sobre ela.

### Importância do Activity Log

O histórico de atividades é importante porque permite acompanhar as alterações realizadas no ambiente.

Com essas informações, o administrador consegue investigar determinadas situações, verificar operações realizadas e identificar possíveis alterações inesperadas.

## 2. Service Health

O **Service Health** é um serviço do Azure utilizado para acompanhar problemas, interrupções e situações que podem afetar a disponibilidade dos serviços da plataforma.

Por meio dele, é possível verificar se existe algum problema relacionado aos serviços do Azure que possa prejudicar o funcionamento dos recursos utilizados.

Por exemplo, se determinado serviço do Azure estiver apresentando uma interrupção em uma região, o **Service Health** pode apresentar informações sobre essa situação.

## 3. Diferença entre Activity Log e Service Health

Apesar de os dois serviços ajudarem no acompanhamento do ambiente, eles possuem finalidades diferentes.

- **Azure Activity Log:** Registra operações administrativas realizadas na assinatura.
- **Service Health:** Apresenta informações sobre problemas e interrupções que podem afetar os serviços do Azure. 

O **Activity Log** permite acompanhar as alterações realizadas nos recursos, enquanto o **Service Health** ajuda a identificar problemas relacionados à própria plataforma Azure.

## 4. Importância para Cloud Ops

Esses recursos ajudam no acompanhamento e na administração de ambientes em nuvem.

O Activity Log permite consultar o histórico de operações, enquanto o Service Health ajuda a identificar situações que podem afetar a disponibilidade dos serviços.

Dessa forma, o administrador consegue acompanhar melhor o ambiente e investigar possíveis problemas.
