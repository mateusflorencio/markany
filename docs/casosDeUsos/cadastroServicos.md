# Caso de Uso: Cadastro de Serviços

**Ator Principal:** Empresa

**Objetivo:** Permitir que a empresa cadastre os serviços que oferece, incluindo informações como nome, preço, tempo estimado e descrição.

**Pré-condições:** A empresa deve estar autenticada no sistema.

**Fluxo Básico:**

1. A empresa acessa a página de cadastro de serviços no sistema.
2. A empresa preenche os campos de informações do serviço, incluindo nome, preço e tempo estimado.
3. A empresa pode opcionalmente fornecer uma descrição detalhada do serviço.
4. A empresa clica no botão "Cadastrar" para adicionar o serviço ao sistema.
5. O sistema valida os campos preenchidos e verifica se todas as informações necessárias foram fornecidas.
6. O sistema cria uma entrada para o serviço na base de dados da empresa.
7. O sistema exibe uma mensagem de sucesso informando que o serviço foi cadastrado com sucesso.

**Fluxo Alternativo:**

5a. Se alguma informação obrigatória não foi fornecida ou está inválida, o sistema exibe uma mensagem de erro indicando qual campo precisa ser corrigido.
5b. Se ocorrer um erro inesperado durante o cadastro, o sistema exibe uma mensagem de erro genérica informando que não foi possível cadastrar o serviço.

**Pós-condições:** O serviço é cadastrado no sistema e fica disponível para ser oferecido aos clientes pela empresa.

**Observações:**

- A empresa pode posteriormente editar ou excluir os serviços cadastrados, caso seja necessário.
- É recomendado fornecer orientações claras sobre como preencher corretamente os campos durante o cadastro do serviço, a fim de evitar erros e garantir que as informações sejam fornecidas de forma precisa.
- O sistema deve permitir que a empresa visualize a lista de serviços cadastrados para facilitar a gestão e atualização.

< [indíce](../indice.md)
