# Persistência de dados no kubernetes de forma dinâmica, cloud GCP(Google Cloud Platform).

 > Explicação: pods kurbernetes são efêmeros, com isso caso algum pod seja deletado, os dados contidos nele, também seram perdidos. Para persistência desses dados em casos de falhas ou exclusões de pod, podemos utilizar como base, os recursos e configurações descritas nesse material disponibilizado.

### Requisitos necessários na GCP:

- Criar uma conta.
- Criar um cluster kubernetes.
- Para criação dos pods e recursos, executar os arquivos .yaml disponibilizados, no cloud shell.

### baixando os arquivos do repositorio git e executando no cloud shell, para crianção dos pods.
```sh
$git clone https://github.com/samela-pessoa/kurbernetes-storage-classes.git
$cd kurbernetes-storage-classes
$kubectl aplly - f "nomedoarquivo.yaml"
```