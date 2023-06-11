# Caso de Uso: Perfil da Empresa

**Ator Principal:** Empresa

**Objetivo:** Permitir que a empresa visualize e atualize as informações do seu perfil no sistema.

**Pré-condições:** A empresa deve estar autenticada no sistema e acessar a página do perfil.

**Fluxo Básico:**

1. A empresa acessa a página do seu perfil no sistema.
2. O sistema exibe as informações atuais do perfil da empresa, como nome, endereço, número de telefone, categoria de serviços, foto de perfil e contas vinculadas de redes sociais.
3. A empresa pode editar as informações do seu perfil, como nome, endereço, número de telefone, categoria de serviços, foto de perfil e contas vinculadas de redes sociais.
4. A empresa salva as alterações realizadas no perfil.
5. O sistema valida as alterações feitas no perfil.
6. O sistema atualiza as informações do perfil da empresa com as alterações realizadas.
7. O sistema exibe uma mensagem de sucesso informando que as alterações foram salvas com sucesso.

**Fluxo Alternativo:**

5a. Se alguma informação obrigatória não for fornecida ou estiver inválida, o sistema exibe uma mensagem de erro indicando qual campo precisa ser corrigido.
5b. Se ocorrer algum erro durante a atualização do perfil, o sistema exibe uma mensagem de erro informando que as alterações não puderam ser salvas.

**Pós-condições:** O perfil da empresa é atualizado com as informações modificadas.

**Observações:**

- O sistema pode oferecer campos adicionais no perfil da empresa, dependendo dos requisitos específicos do seu sistema, como descrição da empresa, horário de funcionamento, avaliações dos clientes, entre outros.
- É importante garantir a segurança das informações do perfil da empresa, protegendo as informações pessoais e permitindo que apenas a empresa autenticada possa editar e visualizar as informações do seu perfil.
- O sistema pode implementar validações adicionais nos campos editáveis do perfil para garantir que as informações fornecidas sejam corretas e consistentes.
- É recomendado fornecer feedback adequado ao usuário, informando sobre o status das alterações realizadas no perfil (por exemplo, mensagens de sucesso ou erro) para uma melhor experiência do usuário.

< [indíce](../indice.md)
