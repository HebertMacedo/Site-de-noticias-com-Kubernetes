# Site de Notícias com Kubernetes

## Descrição

Este projeto é um site de notícias desenvolvido utilizando Kubernetes. O objetivo é demonstrar como implementar um sistema de notícias em um ambiente Kubernetes, gerenciando diferentes componentes e serviços.

## Funcionalidades

- **Portal de Notícias:** Interface de usuário para visualização e interação com as notícias.
- **Gestão de Conteúdo:** Ferramentas para criação, edição e exclusão de notícias.
- **Banco de Dados:** Armazenamento das notícias e informações dos usuários.

## Tecnologias Utilizadas

- ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) **Kubernetes**


## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/HebertMacedo/Site-de-noticias-com-Kubernetes.git

2. Navegue até o diretório do projeto:
   ```bash
   cd Site-de-noticias-com-Kubernetes

3. cd Site-de-noticias-com-Kubernetes
   ```
   kubectl apply -f db-configmap.yaml
   kubectl apply -f db-noticias.yaml
   kubectl apply -f portal-configmap.yaml
   kubectl apply -f portal-noticias.yaml
   kubectl apply -f sistema-configmap.yaml
   kubectl apply -f sistema-noticias.yaml
   kubectl apply -f svc-db-noticias.yaml
   kubectl apply -f svc-portal-noticias.yaml
   kubectl apply -f svc-sistema-noticias.yaml
## Estrutura do Projeto

* db-configmap.yaml: Configurações do banco de dados.
* db-noticias.yaml: Definição do deployment do banco de dados.
* portal-configmap.yaml: Configurações do portal de notícias.
* portal-noticias.yaml: Definição do deployment do portal de notícias.
* sistema-configmap.yaml: Configurações do sistema de gestão de notícias.
* sistema-noticias.yaml: Definição do deployment do sistema de gestão de notícias.
* svc-db-noticias.yaml: Serviço para o banco de dados.
* svc-portal-noticias.yaml: Serviço para o portal de notícias.
* svc-sistema-noticias.yaml: Serviço para o sistema de gestão de notícias.

 ## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.


   
