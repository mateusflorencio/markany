# Padrão de Estilo

1. **Pastas:**
   - Utilize o padrão de nomeação em **camelCase** para nomear pastas.
   - Evite nomes de pastas muito genéricos. Dê preferência a nomes descritivos e significativos relacionados ao conteúdo da pasta.

2. **Arquivos:**
   - Utilize o padrão de nomeação em **camelCase** para nomear arquivos.
   - Classes e componentes React devem ser nomeados com a primeira letra em **maiúscula** (UpperCamelCase).
   - Para arquivos que definem componentes React, nomeie o arquivo com o mesmo nome da classe/componente nele definida.
   - Para arquivos que definem funções utilitárias ou serviços, nomeie o arquivo de forma descritiva relacionada ao seu propósito.

3. **Convenções gerais:**
   - Utilize a extensão `.js` para arquivos JavaScript.
   - Utilize a extensão `.jsx` para arquivos que contêm componentes React.
   - Utilize a extensão `.test.js` para arquivos de teste e2e.
   - Utilize a extensão `.spec.js` para arquivos de teste unitários.
   - Agrupe arquivos relacionados dentro de pastas temáticas.
   - Evite aninhamento excessivo de pastas. Mantenha a estrutura de pastas o mais plana possível, mantendo a organização lógica.

Exemplo de estrutura de pastas e arquivos com as convenções mencionadas:

```text

my-app/
  ├── backend/
  │   ├── src/
  │   │   ├── controllers/
  │   │   │   ├── UserController.js
  │   │   │   └── ...
  │   │   ├── models/
  │   │   │   ├── User.js
  │   │   │   └── ...
  │   │   ├── routes/
  │   │   │   ├── userRoutes.js
  │   │   │   └── ...
  │   │   ├── services/
  │   │   │   ├── AuthService.js
  │   │   │   └── ...
  │   │   └── app.js
  │   ├── tests/
  │   └── ...
  ├── frontend/
  │   ├── public/
  │   ├── src/
  │   │   ├── components/
  │   │   │   ├── Header.jsx
  │   │   │   └── ...
  │   │   ├── pages/
  │   │   │   ├── HomePage.jsx
  │   │   │   └── ...
  │   │   ├── services/
  │   │   │   ├── ApiService.js
  │   │   │   └── ...
  │   │   ├── utils/
  │   │   │   ├── formatDate.js
  │   │   │   └── ...
  │   │   ├── App.js
  │   │   └── index.js
  │   ├── tests/
  │   └── ...
  ├── .gitignore
  ├── package.json
  ├── README.md
  ├── .env (opcional)
  └── ...
  
```

Lembrando que essas são apenas diretrizes gerais de estilo e organização de pastas e arquivos.

< [indíce](../indice.md)
