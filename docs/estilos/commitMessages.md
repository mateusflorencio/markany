# Padrão de Mensagens de Commit

O Git é um sistema de controle de versão muito utilizado que nos permite registrar e acompanhar as alterações feitas em um projeto. Ao realizar um commit, é recomendado seguir um padrão para fornecer mensagens claras e informativas sobre o que foi alterado. O padrão a seguir é baseado nas melhores práticas e convenções comumente adotadas.

## Formato do Commit

```text

<tipo>(<escopo>): <mensagem>

[corpo]

[rodapé]
```

### Tipos de Commit

Aqui estão alguns tipos comumente utilizados em mensagens de commit:

- `feat`: Adição de uma nova funcionalidade
- `fix`: Correção de um bug
- `docs`: Atualização ou adição de documentação
- `style`: Alterações relacionadas a estilos de código
- `refactor`: Refatorações de código
- `test`: Adição ou modificação de testes
- `chore`: Tarefas de manutenção geral

### Escopo

Usado para indicar a área afetada pelo commit, como o nome do componente, módulo ou funcionalidade.

- `front`: Alterações no frontend
- `back`: Alterações no backend
- `db`: Alterações no banco de dados

### Mensagem

A mensagem deve ser uma descrição clara e breve do que foi realizado no commit. Use o imperativo e escreva em letras minúsculas, iniciando com um verbo no infinitivo. Evite terminar a mensagem com um ponto final.

### Corpo

O corpo é opcional e pode conter uma descrição mais detalhada do que foi realizado no commit. Inclua informações adicionais relevantes, como contexto, motivação ou instruções.

### Rodapé

O rodapé é opcional e pode ser usado para fazer referência a problemas, tarefas ou outros commits relacionados. Também pode incluir outras notas ou informações relevantes.

## Exemplo de Mensagem de Commit

```text

fix(front): Corrige bug de exibição de botão no cabeçalho

- O botão de login estava sobreposto pelo logotipo no cabeçalho
- Corrige o problema ajustando o espaçamento do botão

```

< [indíce](../indice.md)
