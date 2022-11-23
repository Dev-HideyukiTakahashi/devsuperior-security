## Desafio resolvido
Implemente as funcionalidades necessárias para que os testes do projeto abaixo passem:

https://github.com/devsuperior/bds03

Collection do Postman:

https://www.getpostman.com/collections/9c19a0ad21eb8a7d864a

Este é um sistema de funcionários e departamentos com uma relação N-1 entre eles:

![uml](https://github.com/Dev-HideyukiTakahashi/devsuperior-security/blob/main/Screenshot%20from%202022-11-23%2012-31-35.png)


Neste sistema, todas as rotas são protegidas. Usuários ADMIN podem ler e alterar recursos, enquanto que usuários OPERATOR podem apenas ler.

* Validações de Employee:
  * Nome não pode ser vazio
  * Email deve ser válido
  * Departamento não pode ser nulo

* Passos para resolver:
  * Modelo de dados User-Role
  * Incluir infraestrutura de validação ao projeto
  * Incluir infraestrutura de segurança ao projeto
  * Implementar as funcionalidades


Bootcamp spring, dev superior.
