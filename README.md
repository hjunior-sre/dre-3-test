Projeto Airflow Celery
Este projeto cria uma instância do Airflow com plugin Celery para execução de Dags programadas.

As instruções abaixo permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Pré-requisitos
Para a instação do projeto, necessário instalar os componentes:
Docker
Docker Compose

Instalação
Após a instalação dos componetes, navegue até a pasta do projeto e execute:
docker-compose up
Acompanhe os logs até a inicilização dos containers

O sistema estará disponível via browser em http://localhost:8080

Implantação
Recomendada a adaptação do projeto em uma Estrutura EKS para o ambiente produtivo, não esqueça de mover as senhas das aplicações para variáveis Secrets

Construído com:
Python

Versão
1.0.1

Autores
Caui
Hermes Junior

Licença
Este projeto está sob a licença (sua licença) - veja o arquivo LICENSE.md para detalhes.