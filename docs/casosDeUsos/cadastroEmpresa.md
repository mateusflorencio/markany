# Caso de Uso: Cadastro da Empresa com Confirmação de Telefone OTP

**Ator Principal:** Empresa

**Objetivo:** Permitir que a empresa se cadastre no sistema fornecendo informações básicas, de contato e confirmando o número de telefone com um código OTP.

**Pré-condições:** Nenhuma.

**Fluxo Básico:**

1. A empresa acessa a página de cadastro no sistema.
2. A empresa preenche os campos obrigatórios de informações, como nome, endereço, número de telefone (WhatsApp), categoria de serviços e senha.
3. A empresa recebe um código OTP por meio de um método de comunicação definido, como mensagem de texto ou chamada telefônica.
4. A empresa insere o código OTP recebido no campo correspondente no formulário de cadastro.
5. O sistema verifica se o código OTP fornecido pela empresa corresponde ao código enviado.
6. Se o código OTP estiver correto, o sistema prossegue com o cadastro.
7. O sistema valida os campos preenchidos e verifica se todas as informações obrigatórias foram fornecidas.
8. O sistema cria uma conta para a empresa com base nas informações fornecidas.
9. O sistema exibe uma mensagem de sucesso informando que o cadastro foi realizado com sucesso.

**Fluxo Alternativo:**

5a. Se o código OTP fornecido pela empresa estiver incorreto, o sistema exibe uma mensagem de erro informando que a confirmação do número de telefone falhou.
7a. Se alguma informação obrigatória não foi fornecida ou está inválida, o sistema exibe uma mensagem de erro indicando qual campo precisa ser corrigido.
7b. Se o sistema detectar que já existe uma empresa cadastrada com o mesmo número de telefone, exibe uma mensagem de erro informando que a empresa já está cadastrada no sistema.

**Pós-condições:** A empresa está cadastrada no sistema e pode fazer login utilizando o número de telefone e senha fornecidos durante o cadastro.

**Observações:**

- A empresa pode posteriormente editar suas informações de contato, senha e vinculação das contas do Instagram, Facebook e YouTube.
- O sistema deve garantir a segurança dos dados fornecidos pela empresa durante o cadastro, protegendo as informações pessoais, senhas e o código OTP.
- É recomendado fornecer orientações claras e dicas para preencher corretamente os campos durante o cadastro, a fim de evitar erros e garantir que as informações sejam fornecidas de forma precisa.
- O sistema deve implementar medidas de segurança adicionais para proteger o processo de confirmação do telefone, como limitar o número de tentativas de inserção do código OTP e definir uma validade para o código.

< [indíce](../indice.md)
