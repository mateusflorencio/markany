# Caso de Uso: Login da Empresa

**Ator Principal:** Empresa

**Objetivo:** Permitir que a empresa faça login no sistema utilizando seu número de telefone e senha.

**Pré-condições:** A Empresa deve estar cadastrado no sistema.

**Fluxo Básico:**

1. A empresa acessa a página de login no sistema.
2. A empresa insere o número de telefone e a senha cadastrados previamente.
3. A empresa clica no botão "Entrar" para efetuar o login.
4. O sistema verifica se o número de telefone e a senha fornecidos correspondem a uma conta válida.
5. Se as credenciais estiverem corretas, o sistema autentica a empresa e a redireciona para a página principal do sistema.
6. Se as credenciais estiverem incorretas, o sistema exibe uma mensagem de erro informando que o login falhou.

**Fluxo Alternativo:**

4a. Se o número de telefone fornecido não estiver cadastrado no sistema, o sistema exibe uma mensagem de erro informando que a empresa não está registrada.
4b. Se a senha fornecida estiver incorreta, o sistema exibe uma mensagem de erro informando que a senha é inválida.

**Pós-condições:** A empresa está autenticada no sistema e pode acessar as funcionalidades disponíveis para ela.

**Observações:**

- O sistema deve garantir a segurança das informações de login, protegendo as senhas armazenadas com técnicas adequadas de criptografia.
- É importante fornecer mecanismos para redefinir a senha em caso de esquecimento ou perda.
- Pode ser útil adicionar uma opção "Lembrar-me" para permitir que a empresa permaneça autenticada por um período de tempo.

< [indíce](../indice.md)
