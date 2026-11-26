# Comandos Linux e Azure CLI

A parte a seguir, explicarei o funcionamento dos comandos básicos do Linux e do Azure.

## 1. Comandos básicos do Linux

O **Linux** possui diversos comandos que permitem realizar tarefas pelo terminal, como navegar entre pastas, visualizar arquivos e criar diretórios.

Alguns dos principais comandos são:

| Comando | Função |
|---|---|
| `pwd` | Mostra o caminho da pasta atual. |
| `ls` | Lista os arquivos e pastas do diretório atual. |
| `cd` | Permite acessar outra pasta. |
| `mkdir` | Cria uma nova pasta. |
| `clear` | Limpa as informações exibidas no terminal. |
| `touch` | Cria um arquivo vazio. |

### Exemplos

```bash
pwd
```
Mostra em qual diretório o usuário está.

```bash
ls
```
Mostra os arquivos e pastas disponíveis no diretório atual.

```bash
mkdir projeto
```
Cria uma pasta chamada projeto.

```bash
cd projeto
```
Acessa a pasta projeto.

## 2. Azure CLI

O **Azure CLI** é uma ferramenta de linha de comando utilizada para gerenciar recursos do Microsoft Azure.

Por meio dela, é possível consultar informações, criar recursos, modificar configurações e realizar outras operações sem precisar utilizar somente o portal do Azure.

### Principais comandos

```bash
az login
```
Realiza o processo de autenticação na conta do Azure.

```bash
az account show
```
Mostra informações sobre a assinatura e a conta utilizada.

```bash
az group list
```
Lista os grupos de recursos existentes na assinatura.

```bash
az vm list
```
Lista as máquinas virtuais existentes na assinatura.

```bash
az vm list --output table
```
Exibe a lista de máquinas virtuais em formato de tabela, facilitando a visualização.

## 3. Importância dos comandos

Os **Comandos** são importantes porque permitem realizar tarefas de forma mais rápida e organizada, principalmente quando é necessário administrar vários recursos.

O Linux é bastante utilizado na administração de servidores, enquanto o Azure CLI facilita o gerenciamento dos serviços disponíveis na nuvem.

É importante lembrar que alguns comandos apenas consultam informações, enquanto outros podem modificar ou criar recursos. Por isso, é necessário entender o que cada comando faz antes de executá-lo.