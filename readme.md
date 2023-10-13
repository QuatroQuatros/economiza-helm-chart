# Helm Chart instalação e configuração
Neste guia, vou mostrar como instalar e configurar o meu Helm Chart. Antes de prosseguir, certifique-se de ter instalado e configurado corretamente o
[Helm](https://helm.sh/docs/intro/install/) e o [Kubernetes](https://kubernetes.io/docs/setup/)

## Prérequisitos

Certifique-se de que os seguintes pré-requisitos estejam atendidos:

Helm: Helm deve estar instalado e configurado em seu ambiente.
Kubernetes: Seu cluster Kubernetes deve estar configurado e em execução.

## Passo 1: Clone o repositório do chart

Se você ainda não possui o Helm Chart em seu computador, faça um clone do repositório com o seguinte comando:

```bash
git clone git@github.com:QuatroQuatros/economiza-helm-chart.git
```


## Passo 2: Configure os valores

Navegue até o diretório do Helm Chart:

```bash
cd economiza
```

Agora, edite o arquivo values.yaml com suas preferências e configurações específicas para o aplicativo.



## Passo 3: Instale o chart

Após ter configurado os valores do Chart de acordo com suas necessidades, você pode prosseguir com a instalação. Use o seguinte comando:

```bash
helm install meu-app ./economiza -n meu-namespace --create-namespace
```

A flag --create-namespace criará um novo namespace, caso você ainda não tenha criado um.

## Passo 4: Acesse a aplicação

Se a instalação for concluída com êxito, você receberá um link para acessar o aplicativo. O endereço deste link será o mesmo configurado na chave host no arquivo values.yaml.




