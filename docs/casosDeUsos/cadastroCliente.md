# Caso de Uso: Criação de Perfil com Confirmação de Telefone OTP

**Ator Principal:** Cliente

**Objetivo:** Permitir que o cliente crie um perfil no sistema, fornecendo informações básicas e confirmando seu número de telefone por meio de um código OTP (One-Time Password).

**Pré-condições:** O cliente deve acessar a página de registro no sistema.

**Fluxo Básico:**

1. O cliente acessa a página de registro no sistema.
2. O cliente fornece as informações básicas necessárias, como nome, número de telefone e outras informações relevantes.
3. O sistema verifica se o número de telefone fornecido é válido.
4. O sistema envia um código OTP para o número de telefone do cliente.
5. O cliente recebe o código OTP por mensagem de texto ou outro método de comunicação.
6. O cliente insere o código OTP recebido no sistema.
7. O sistema verifica se o código OTP fornecido pelo cliente corresponde ao código enviado.
8. Se o código OTP estiver correto, o sistema confirma o número de telefone do cliente.
9. O sistema registra as informações do cliente, criando um perfil individual.
10. O cliente recebe uma confirmação de que o perfil foi criado com sucesso.

**Fluxo Alternativo:**

3a. Se o número de telefone fornecido pelo cliente não for válido, o sistema exibe uma mensagem de erro informando que o número de telefone é inválido.

7a. Se o código OTP fornecido pelo cliente estiver incorreto, o sistema exibe uma mensagem de erro informando que a confirmação do número de telefone falhou.

**Pós-condições:** O cliente cria um perfil no sistema com as informações fornecidas e o número de telefone é confirmado por meio do código OTP.

**Observações:**

- É importante garantir a segurança do processo de confirmação do número de telefone, evitando a possibilidade de ataques de força bruta ou vazamento de informações confidenciais.
- O sistema pode implementar medidas de segurança adicionais, como a limitação de tentativas de inserção do código OTP, a expiração do código após um determinado tempo ou a verificação adicional de outros dados do cliente.
- O sistema pode oferecer recursos adicionais, como a possibilidade de adicionar informações adicionais ao perfil do cliente, criar senhas seguras ou vincular perfis de mídia social.

< [indíce](../indice.md)
