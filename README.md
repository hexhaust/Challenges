# Desafios técnicos - DevOps

**Resumo**

A ideia é criar um repositório para cada desafio, documentar e aplicar melhorias sempre que possível.

Caso o desafio seja muito fácil: Tente deixar ele mais complexo. Se pergunte como você poderia melhorar o que fez.

Caso seja muito difícil: Pesquise em fóruns, vídeos no youtube e leia documentações.

## Index

* [Desafio 1](#desafio-1)
* [Desafio 2](#desafio-2)
* [Desafio 3](#desafio-3)
* [Desafio 4](#desafio-4)
* [Desafio 5](#desafio-5)
* [Desafio 6](#desafio-6)
* [Desafio 7](#desafio-7)
* [Desafio 8](#desafio-8)
* [Desafio 9](#desafio-9)
* [Desafio 10](#desafio-10)

## Pre-reqs

As seguintes ferramentas devem estar instaladas para que você não tenha problemas durante os desafios:

* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Docker](https://docs.docker.com/engine/install/)
* [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)
* [Vagrant](https://developer.hashicorp.com/vagrant/downloads)
* [Packer](https://developer.hashicorp.com/packer/downloads)
* [Runtimes de Desenvolvimento]
    * [Python](https://python.org.br/instalacao-linux/)
    * [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
    * [Rust](https://www.rust-lang.org/tools/install)
* [CLI para algum Cloud Provider]
    * [AWS](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
    * [Azure](https://learn.microsoft.com/pt-br/cli/azure/install-azure-cli-linux?pivots=apt)
    * [GCP](https://cloud.google.com/sdk/docs/install?hl=pt-br)
* [Ferramentas de IaC]
    * [Terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
    * [Pulumi](https://www.pulumi.com/docs/install/)

***Lembre-se de verificar se as mesmas já não estão instaladas. Git e Python por exemplo, vem por default em alguns Linux OS***

### Desafio 1

1. Configuração de um WebServer.

Para esse desafio, utilize o nginx ou apache para configurar um webserver.

Critérios de aceite:

* [O conteúdo deve ser estático]

* [A criação deve ser automatizada após testes]

* [Documentação do que foi realizado]

* [O conteúdo do site deve estar hospedado publicamente]
Dica: Utilize o [GitHub Pages](https://pages.github.com)

### Desafio 2

2. Implementação de testes unitários.

A ideia desse desafio é criar um Health Check na sua página do GitHub Pages.

Critérios de aceite:

* [Script para health check]
Dica: O script deve ser capaz de se um site ou server está online (talvez usando ping ou curl)

* [O script deve rodar de forma automatizada]
Dica: Leia sobre cronjobs ou criação de services no Linux

* [Documentação do que foi realizado]


### Desafio 3

3. Containerização de uma aplicação.

Crie uma aplicação qualquer em Python. Ideias? 

* [Uma CLI simples]
* [Bot de WhatsApp]
* [App web com Flask]

Critérios de aceite:

* [Dockerfile criado]

* [Imagem hospedada em algum Registry]

* [Documentação do que foi realizado]


### Desafio 4

4. Criar um playbook Ansible.

Aqui vamos criar um Playbook do Ansible que deve fazer deploy de um servidor e algumas configurações.

Critérios de aceite:

* [Playbook criado para deployar uma VM linux]

* [O playbook deve instalar o nginx, grafana, curl e htop]

* [Documentação do que foi realizado]

### Desafio 5

5. Implementar uma infraestrutura como código, ou IaC.

É hora de criar uma automação para provisionamento de Infraestrutura.

Critérios de aceite:

* [Provisionamento de 2 VMs básicas com os nomes server-1 e server-2]

* [Após o provisionamento, seu Playbook do Ansible deve ser aplicado nos servidores] 

* [Documentação do que foi realizado]

* [Bonus: Caso consiga, tente utilizar o Packer]

### Desafio 6

6. Uso do ELK Stack.

Configure agora a stack do Elastic, também conhecida como ELK.

Critérios de aceite:

* [Elasticsearch instalado]

* [Logstash instalado]

* [Kibana instalado e acessível via browser]

* [Documentação do que foi realizado]

* [Bonus: Tente pesquisar sobre os "beats" da ELK Stack]

### Desafio 7

7. Networking

Agora vamos instalar várias ferramentas de redes. Esse desafio é voltado para estudos e não tem critérios de aceite.

Softwares para serem estudados e instalados:

Ping, Traceoute, Nslookup ou Dig, Wireshark, Iperf, Tshark, Nessus, Arp, Netcat, Nethogs, Ntop, Tcpdump e Telnet.

### Desafio 8

8. Implementar observabilidade.

Hora de implementar a observabilidade COMPLETA. Queremos agora monitoração de Logs, Traces e Métricas. A ferramenta você quem escolhe.

Critérios de aceite:

* [Métricas sendo monitoradas]

* [Logs sendo monitorados]

* [Traces sendo capturados]

* [Documentação do que foi realizado]

### Desafio 9

9. Configurar uma Pipeline CI/CD

Lembra dos desafios de Conteinerização de Aplicação, Provisionamento de Infra e Configuração de Server? Hora de juntar tudo em uma Pipeline.

Critérios de aceite:

* [A Pipeline deve provisionar a Infra]

* [A Pipeline deve configurar os servidores]

* [A Pipeline deve fazer deploy da aplicação]

* [Documentação do que foi realizado]

### Desafio 10

10. Orquestração de containers com Kubernetes

Última etapa! Crie um Cluster Kubernetes e faça deploy da aplicação do desafio 3 nele.

Critérios de aceite:

* [O Cluster deve estar rodando]

* [Pods rodando com a aplicação]

* [Arquivo de Deployment para a aplicação com 3 replicas]

* [Documentação do que foi realizado]

#### Detalhes e dicas

Lembre-se de pesquisar em todas as fontes possíveis. Google, Youtube, Stack OverFlow, fóruns e até livros, obviamente.

Caso não consiga: Peça ajuda. 

Porém quero as seguintes informações antes de ajudar:
* [O que você tentou até agora?]
* [Quais fontes você usou para pesquisa?]
* [Quanto tempo você estudou esse tópico de dúvida?]
