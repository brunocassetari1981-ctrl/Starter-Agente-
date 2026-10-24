# Starter Agente

Este repositório foi criado para servir como base para um agente de tarefas, onde você pode pedir desenvolvimento de programas, sites, sistemas, automações e utilitários usando linguagem natural.

A ideia é simples:
- você descreve o que precisa;
- o agente interpreta a tarefa;
- o código é organizado na pasta src;
- os arquivos principais ficam separados por responsabilidade e funcionalidade.

## Como pedir trabalhos para o agente

Para obter bons resultados, escreva a tarefa de forma clara e objetiva. Descreva:
1. O que deve ser criado;
2. A linguagem ou tecnologia;
3. O objetivo do projeto;
4. As funcionalidades principais;
5. O estilo ou comportamento esperado;
6. Como a estrutura deve ficar organizada.

### Modelo de prompt
> Crie um programa em Python para controlar estoque de produtos. Ele deve permitir cadastrar, listar, editar e excluir itens, além de buscar por nome. Use organização em pasta src e mantenha o código limpo e documentado.

### Dicas importantes
- Seja específico sobre o objetivo;
- Informe a linguagem/framework;
- Liste as telas ou módulos esperados;
- Defina se o projeto deve ser simples ou completo;
- Peça organização em pastas e arquivos quando quiser manter a estrutura limpa.

## Estrutura sugerida do projeto

```text
Starter-Agente/
├── README.md
├── src/
│   ├── app.py
│   ├── main.py
│   ├── models/
│   │   └── ...
│   ├── services/
│   │   └── ...
│   ├── controllers/
│   │   └── ...
│   ├── templates/
│   │   └── ...
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   ├── utils/
│   │   └── ...
│   └── config/
│       └── ...
├── requirements.txt
├── .gitignore
├── docs/
│   └── ...
└── tests/
    └── ...
```

## Pasta src

A pasta `src` é o lugar onde fica o código-fonte principal do projeto. Ela organiza o desenvolvimento e deixa o repositório mais profissional.

Use a pasta `src` para:
- lógica do sistema;
- classes e funções;
- regras de negócio;
- interfaces;
- arquivos de execução principal;
- módulos auxiliares.

## Como pedir um programa

Use um pedido como este:

> Crie um programa em Python para gerenciar uma biblioteca. O sistema deve permitir cadastrar livros, listar todos os livros, buscar por título, atualizar informações e remover itens. Organize o código dentro da pasta src e mantenha a estrutura simples.

### Exemplo prático
> Desenvolva um programa em JavaScript para calcular o salário líquido de funcionários com base em valores de salário bruto, descontos e benefícios. Exiba os resultados em console e organize tudo na pasta src.

## Como pedir um site

Use um prompt como este:

> Crie um site moderno para uma loja de roupas. O site deve ter página inicial, catálogo de produtos, seção de destaque, formulário de contato e design responsivo. Use HTML, CSS e JavaScript e organize os arquivos dentro da pasta src.

### Exemplo prático
> Construa um site institucional para uma empresa de consultoria. Inclua banner inicial, serviços, depoimentos, área de contato e rodapé. O código deve estar organizado em src com estrutura limpa e responsiva.

## Como pedir um sistema

Use um pedido como este:

> Crie um sistema de gestão escolar em Python com Flask. O sistema deve ter cadastro de alunos, professores, turmas, notas e presença. Também deve possuir login e dashboard inicial. Organize todo o código na pasta src.

### Exemplo prático
> Desenvolva um sistema de controle financeiro para uma pequena empresa. Ele deve permitir cadastro de usuários, lançamentos de receitas e despesas, relatórios mensais e exportação em CSV. Use estrutura organizada em src e boas práticas de desenvolvimento.

## Exemplo final de pedido

> Crie um sistema completo de gestão de clientes em Python com Flask. O sistema deve ter cadastro, listagem, edição, exclusão e busca de clientes. Também deve permitir login e salvar os dados em banco SQLite. Organize todo o código dentro da pasta src e mantenha uma arquitetura simples e clara.

## Boas práticas ao escrever pedidos

- Use frases curtas e diretas;
- Informe a tecnologia;
- Especifique os módulos ou telas;
- Peça organização em pastas;
- Defina se quer backend, frontend ou full stack;
- Solicite documentação quando necessário.

## Resumo

Este repositório foi pensado para você usar como ponto de partida para criar projetos por meio de instruções em linguagem natural. A organização em src facilita a criação, manutenção e expansão do código.

Se quiser, você pode pedir ao agente:
- um programa;
- um site;
- um sistema completo;
- uma API;
- automação;
- script de tarefas;
- ou qualquer solução em qualquer linguagem.

---

Este README pode ser adaptado para qualquer stack, mas a estrutura básica já está pronta para começar a desenvolver com organização e clareza.
