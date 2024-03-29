## Desafio

Considerando as aplicações presentes neste repositório detalhadas abaixo, precisamos de uma stack que permita a comunicação entre ambas e o acesso de desenvolvedores.

* **Aplicação Frontend** - Aplicação em Python com Flask expondo na porta 8000 um formulário de criação de usuário contendo os campos ID e Name que realiza uma chamada Post com tais dados para a aplicação Backend.

* **Aplicação Backend** - Aplicação em Go (Golang) expondo na porta 8080 o CRUD de Usuários e armazena em um banco Sqlite3 local.

## Como entregar sua solução?

1) Realize as alterações necessárias para construção/automação da stack. Considere um ambiente local (máquina do desenvolvedor) ou algum provedor de cloud (AWS ou GCP).

2) Adicione e commit todos os arquivos criados/alterados (todos mesmo)

## Requisitos

* Crie imagens Docker para ambas as aplicações. 
* Considere que os desenvolvedores estão iniciando carreira e precisarão de mais detalhes de como executar sua solução.
* A Stack pode usar os recursos do próprio desenvolvedor(ex. VirtualBox, Docker, Docker-Compose) ou recursos de um provedor de cloud (Amazon Web Service ou Google Cloud)
* Não se preocupe em montar uma solução complexa. Dê preferência em montar uma solução simples que permita que o desenvolvedor realize melhorias.
* Apresente um desenho macro de arquitetura de sua solução.

## Bonus

* Sinta-se a vontade para realizar melhorias no código das aplicações, caso julgue necessário.

## Dúvidas

Entre em contato e nos questione.
