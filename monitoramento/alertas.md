# Monitoramento e Alertas no Azure

Nessa parte, explicarei de maneira simples como funciona o monitoramento e os alertas do Azure.

## 1. Azure Monitor

O **Azure Monitor** é um serviço utilizado para acompanhar o funcionamento e o desempenho dos recursos disponíveis no Azure.

Por meio dele, é possível analisar informações sobre os recursos, identificar possíveis problemas e acompanhar o comportamento dos serviços.

O monitoramento é importante porque permite identificar situações que podem prejudicar o funcionamento de uma infraestrutura na nuvem.

## 2. Métricas de monitoramento

As **Métricas** são informações utilizadas para acompanhar o desempenho de determinado recurso.

No Azure, é possível acompanhar diferentes tipos de informações, dependendo do serviço utilizado.

Alguns exemplos são:

- **CPU:** mostra a quantidade de processamento utilizada pela máquina virtual.
- **Rede:** apresenta informações sobre o tráfego de entrada e saída de dados.
- **Disponibilidade:** permite acompanhar se determinado recurso está disponível.
- **Memória:** pode ser monitorada quando existem os recursos e agentes necessários para coletar essas informações.

Essas informações ajudam a identificar se um recurso está funcionando corretamente ou se apresenta algum problema.

## 3. Alertas

Os **Alertas** são utilizados para avisar quando determinada condição é identificada durante o monitoramento de um recurso.

Por exemplo, imagine que uma máquina virtual esteja utilizando uma quantidade muito alta de processamento.

É possível configurar uma condição para que o Azure gere um alerta quando o uso da CPU ultrapassar determinado valor.

Dessa maneira, o administrador pode receber uma notificação e verificar o que está acontecendo.

## 4. Como funcionam os alertas?

De maneira geral, a configuração de um alerta envolve:

1. Escolher o recurso que será monitorado.
2. Selecionar a métrica ou condição que será acompanhada.
3. Definir o limite que deverá gerar o alerta.
4. Configurar uma ação ou notificação.
5. Acompanhar os alertas gerados.

Por exemplo, um alerta pode ser configurado para identificar quando o uso da CPU de uma máquina virtual ultrapassar 80% durante determinado período.

Esse valor é apenas um exemplo e pode ser alterado de acordo com a necessidade do ambiente.

## 5. Importância do monitoramento

O **Monitoramento** permite acompanhar o desempenho dos recursos e identificar problemas antes que eles prejudiquem o funcionamento dos serviços.

Além disso, os alertas ajudam o administrador a perceber situações que precisam de atenção, facilitando o acompanhamento da infraestrutura na nuvem.