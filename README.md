# Projeto - To-do List

## Sistema de Gerenciamento de Tarefas

Este projeto é um sistema de To-Do List desenvolvido do zero com Spring Boot, apresentado em uma aula prática e abrangente. O objetivo é ensinar, de maneira didática e aplicada, como construir uma API RESTful para gerenciamento de tarefas, cobrindo as principais operações de um CRUD.

### Funcionalidades

- **API de Tarefas:**  
  Utiliza as anotações `@RestController` e `@RequestMapping` para criar uma API RESTful que gerencia tarefas.

- **Listar Tarefas:**  
  Endpoints com `@GetMapping` para listar todas as tarefas disponíveis no TodoList.

- **Criar Tarefas:**  
  Utilização de `@PostMapping` junto com `@RequestBody` para adicionar novas tarefas ao sistema.

- **Deletar Tarefa:**  
  Implementação de `@DeleteMapping` e `@PathVariable` para remover tarefas específicas do TodoList.

- **Atualizar Tarefa:**  
  Uso de `@PutMapping`, `@RequestBody` e `@PathVariable` para atualizar tarefas existentes.

- **Testes com HTTP Client Bruno:**  
  Demonstração do uso do cliente HTTP Bruno para testar e validar o funcionamento correto da API Spring Boot.

### Objetivo

Esta aula prática é ideal para desenvolvedores que desejam dominar as principais funcionalidades de uma API REST com Spring Boot, proporcionando uma base sólida para construção e gerenciamento de aplicações Java modernas.

---

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/matalvesdev/todo-list-spring.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd todo-list-spring
   ```

3. Execute o projeto com o Maven ou sua IDE favorita:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Acesse os endpoints conforme definido nos controllers.

## Testando a API

- Utilize o HTTP Client Bruno para testar os endpoints.
- Consulte a documentação ou exemplos fornecidos para validar as operações de listar, criar, atualizar e deletar tarefas.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Maven
- HTTP Client Bruno

---

Desenvolvido para fins educacionais e práticos. Ideal para quem deseja aprender a construir APIs RESTful modernas com Spring Boot.
