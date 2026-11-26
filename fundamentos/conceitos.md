# Fundamentos de Cloud OPS

Nessa parte vai ser responsável em explicar os conceitos básicos de Cloud OPS.

## 1. Computação em Nuvem e IaaS, PaaS e SaaS:

A **computação de nuvem** é a disponibilidade de recursos e serviços de tecnologia na internet, como servidores, armazenamentos e redes, sob demanda, com cobrança geralmente de uso.

### Modelos de Nuvem:
- **IaaS:** Oferta de infraestrutura como serviço, oferece recursos como máquinas virtuais, armazenamento e redes.(Ex: Servidores, hardware, cabiamento, etc);

- **PaaS:** Oferta de plataforma como serviço, oferece um ambiente para desenvolver e executar aplicações, sem precisar administrar toda a infraestrutura.(Ex: Sistema operacional, Ferramentas para desenvolvimento de software, etc);

- **SaaS:** Oferta de software como serviço, disponibiliza aplicações prontas pela internet.(Ex: Aplicativo de planilha de cálculo, aplicativo de editor de texto, etc).

### Modelo de Implantação:

- **Nuvem Privada:** usa recursos dedicados a uma única organização(com mais controle e segurança);

- **Nuvens Pública:** é compartilhada e gerenciada por terceiros.

- **Nuvem híbrida:** é a mistura dos dois.

## 3. Microsoft Azure:

O **Microsoft Azure** é uma plataforma em nuvem criada para hospedar, gerenciar e escalar aplicativos e serviços por meio da internet. Permite alugar o poder de processamento, armazenamento e ferramentas tecnológicas pela internet, sem precisar comprar servidores ou computadores físicos.

Exemplos de utilização:

- Hospedar aplicações.
- Criar e utilizar máquinas virtuais.
- Configurar recursos e serviços.

## 4. Assinatura:

As **Assinaturas** no Microsoft Azure são unidades utilizadas para organizar, gerenciar e cobrar serviços e recursos na nuvem. Elas também permitem controlar o acesso aos recursos e acompanhar os custos relacionados à sua utilização.

Uma **Assinatura** funciona como um limite de cobrança dentro do Azure, no qual podem existir diferentes grupos de recursos.

## 5. Grupos de Recursos(Resource Group):

O **Grupo de Recursos** um contêiner lógico usado para agrupar e gerenciar juntos os recursos relacionados de uma solução na nuvem, como máquinas virtuais, bancos de dados, redes virtuais e contas de armazenamento.

Ele funciona como uma pasta virtual que facilita o controle de ciclo de vida, permissões e custos desses componentes, basicamente um local onde "guarda" ferramentas(servidores, banco de dos, redes virtuais, etc) que fazem o projeto funcionar.

## 7. Máquinas virtuais (VMs)

Uma **Máquina Virtual** é um computador criado por meio de virtualização, que funciona utilizando os recursos de uma máquina física.

Ela pode possuir seu próprio sistema operacional, memória, processador e armazenamento.

No Azure, as máquinas virtuais permitem utilizar servidores pela internet, sem precisar ter um servidor físico próprio.

Podem ser utilizadas para executar aplicações, hospedar serviços e realizar diferentes atividades.

## 8. Linux

O **Linux** é um sistema operacional utilizado em computadores e servidores.

Ele é bastante utilizado em ambientes de infraestrutura e computação em nuvem, pois permite administrar recursos e executar serviços por meio de comandos no terminal.

Em máquinas virtuais, o Linux pode ser utilizado como sistema operacional para executar aplicações e serviços.

## 9. SSH (Secure Shell)

O **SSH** é um protocolo utilizado para realizar conexões remotas e acessar outros computadores ou servidores de forma segura.

Ele permite que um usuário acesse e execute comandos em uma máquina sem precisar estar fisicamente no local.

No Cloud Computing, o SSH pode ser utilizado para acessar máquinas virtuais Linux e realizar atividades de administração.
