# Caso de Uso: Login do Cliente

**Ator Principal:** Cliente

**Objetivo:** Permitir que o cliente faça login no sistema utilizando seu número de telefone e senha.

**Pré-condições:** O cliente deve estar cadastrado no sistema.

**Fluxo Básico:**

1. O cliente acessa a página de login no sistema.
2. O cliente insere o número de telefone e a senha cadastrados previamente.
3. O cliente clica no botão "Entrar" para efetuar o login.
4. O sistema verifica se o número de telefone e a senha fornecidos correspondem a uma conta válida de cliente.
5. Se as credenciais estiverem corretas, o sistema autentica o cliente e o redireciona para a página principal do sistema.
6. Se as credenciais estiverem incorretas, o sistema exibe uma mensagem de erro informando que o login falhou.

**Fluxo Alternativo:**

4a. Se o número de telefone fornecido não estiver cadastrado no sistema, o sistema exibe uma mensagem de erro informando que o cliente não está registrado.
4b. Se a senha fornecida estiver incorreta, o sistema exibe uma mensagem de erro informando que a senha é inválida.

**Pós-condições:** O cliente está autenticado no sistema e pode acessar as funcionalidades disponíveis para ele.

**Observações:**

- O sistema deve garantir a segurança das informações de login do cliente, protegendo as senhas armazenadas com técnicas adequadas de criptografia.
- É importante fornecer mecanismos para redefinir a senha em caso de esquecimento ou perda.
- Pode ser útil adicionar uma opção "Lembrar-me" para permitir que o cliente permaneça autenticado por um período de tempo.

< [indíce](../indice.md)
