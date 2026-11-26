# Gerenciamento de Recursos no Azure

Parte responsável por explicar e contextualizar recursos disponíveis no Microsoft Azure.

## 1. Máquinas Virtuais (VMs)

Uma **máquina Virtual** é um computador criado por um software, que tem o seu funcionamento dentro de um servidor físico. Como um computador normal, há nele recursos como um sistema operacional, CPU, Armazenamento e memória RAM.

### Exemplo:

Pense que você(ou empresa) precisa de um computador para hospedar um sistema de internet. Ao invés de comprar um computador físico, você poderia criar uma máquina virtual no Azure com Linux determinada quantidade de memória e armazenamento.

### Gerenciamento:

Ao criar uma máquina virtual, é necessário definir algumas configurações:

- Nome da máquina virtual.
- Região onde ela será hospedada.
- Sistema operacional.
- Quantidade de CPU e memória RAM.
- Armazenamento.
- Configurações de rede.
- Forma de acesso à máquina.

## 2. Acesso às Máquinas Virtuais por SSH (Secure Shell)

Como o título já diz, é uma maneira de acessar as suas máquinas virtuais. É um protocolo utilizado para acessar e administrar computadores remotamente por meio de uma conexão segura, permite o acesso através da máquina virtual Linux utilizando o terminal do seu computador de forma remota.

### Funcionamento:

De maneira simplificada, existem três elementos:
- Cliente: computador utilizado para iniciar a conexão.
- Servidor: máquina virtual que receberá a conexão.
- Protocolo SSH: responsável por estabelecer a comunicação segura.

Para realizar a conexão, é necessário endereço IP da máquina virtual, mome do usuário configurado na VM, chave SSH ou outra forma de autenticação permitida.


## 3. Chaves SSH

As **Chaves SSH** são utilizadas para realizar a autenticação durante uma conexão SSH, ou seja, uma forma de permitir o acesso de outros indivíduos da sua máquina virtual.

Há dois tipos:

- **Chave Pública:** É um código que você pode entregar para qualquer servidor ou site (como o GitHub) sem medo. É como colocar o seu cadeado na porta de um computador remoto dizendo: "só quem tiver a chave certa pode entrar aqui".

- **Chave Privada:** É um arquivo secreto que fica guardado apenas no seu computador. É como a chave física que você carrega no bolso — só ela abre aquele cadeado específico.

## 4. Redes Virtuais (VNet) e Sub-redes

Uma **rede virtual**, chamada de **VNet** no Azure, permite que os recursos da nuvem se comuniquem entre si de maneira organizada.

Ela funciona como uma rede privada dentro do ambiente do Azure.

Por exemplo, imagine que uma empresa possui três máquinas virtuais:
- VM 1: responsável pelo sistema.
- VM 2: responsável pelo banco de dados.
- VM 3: responsável por testes.
Essas máquinas podem fazer parte de uma mesma rede virtual, permitindo a comunicação entre elas conforme as configurações de rede e segurança.

### Sub-redes:

As **Sub-redes** são uma forma de dividir as redes em partes menores.

#### Exemplo:

Imagina uma empresa que é dona de vários departamentos diferentes. Em de colocar todas na mesma rede, separará em redes menores para deixar mais organizado.

## 5. Grupos de Segurança de Rede (NSG = Network Security Group.)

É um recurso do Azure que é utilizado para controlar o tráfego de rede, ou seja, uma espécie de filtro de segurança, permitindo ou bloqueando determinadas conexões.

Existem dois tipos principais de regras:
- Entrada (Inbound): controla o tráfego que chega ao recurso.
- Saída (Outbound): controla o tráfego que sai do recurso.

### Exemplo:

Suponha que a minha rede esteja organizada dessa forma:

1. Regra: SSH; Porta: 22; Ação: Permitir.
2. Regra: HTTP;	Porta: 80; Ação: Permitir
3. Regra: RDP; Porta: 3389; Ação: Bloquear

Nesse exemplo:
- A porta 22 é utilizada para conexões SSH.
- A porta 80 é utilizada para comunicação HTTP.
- A porta 3389 é utilizada para acesso remoto RDP.

## 6. Gerenciamento de Custos e Economia de Recursos

É uma parte muito importante do Microsoft Azure. Ao criar uma conta do Azure, é notável perceber que há um certo limite sobre quais recursos podemos usar, pois dependendo os recursos utilizados no Azure podem gerar cobranças de acordo com o consumo, a configuração e o tempo de utilização. O gerenciamento de gastos na nuvem é importante para controlar os custos dos recursos utilizados e evitar despesas desnecessárias. 

No Azure, é possível criar orçamentos, acompanhar o consumo e configurar alertas quando os gastos atingirem determinados valores. Também é recomendado desligar máquinas virtuais que não estão sendo utilizadas, escolher configurações adequadas e excluir recursos desnecessárioo.



