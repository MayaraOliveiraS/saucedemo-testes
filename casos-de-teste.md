# Casos de Teste - SauceDemo

## CT-001 - Login com credenciais válidas

**Pré-condição:**  
Usuário está na tela de login.

**Dados de teste:**
- Usuário: `standard_user`
- Senha: `secret_sauce`

**Passos:**
1. Informar o usuário `standard_user`.
2. Informar a senha `secret_sauce`.
3. Clicar em Login.

**Resultado esperado:**  
O usuário deve conseguir realizar o login e acessar a página de produtos.

**Resultado obtido:**  
O login foi realizado com sucesso e a página de produtos foi exibida.

**Status:** PASS


---

## CT-002 - Login com senha inválida

**Pré-condição:**  
Usuário está na tela de login.

**Dados de teste:**
- Usuário: `standard_user`
- Senha: senha inválida

**Passos:**
1. Informar o usuário `standard_user`.
2. Informar uma senha inválida.
3. Clicar em Login.

**Resultado esperado:**  
O sistema deve impedir o login e apresentar uma mensagem de erro.

**Resultado obtido:**  
A preencher após a execução do teste.

**Status:** A EXECUTAR


---

## CT-003 - Login sem preencher os campos

**Pré-condição:**  
Usuário está na tela de login.

**Passos:**
1. Não preencher o campo de usuário.
2. Não preencher o campo de senha.
3. Clicar em Login.

**Resultado esperado:**  
O sistema deve impedir o login e apresentar uma mensagem informando que os campos são obrigatórios.

**Resultado obtido:**  
A preencher após a execução do teste.

**Status:** A EXECUTAR


---

## CT-004 - Adicionar produto ao carrinho

**Pré-condição:**  
Usuário está autenticado e na página de produtos.

**Passos:**
1. Selecionar um produto.
2. Clicar em Add to cart.
3. Acessar o carrinho.

**Resultado esperado:**  
O produto deve ser adicionado ao carrinho corretamente.

**Resultado obtido:**  
A preencher após a execução do teste.

**Status:** A EXECUTAR


---

## CT-005 - Remover produto do carrinho

**Pré-condição:**  
Usuário possui um produto no carrinho.

**Passos:**
1. Acessar o carrinho.
2. Localizar o produto.
3. Clicar em Remove.

**Resultado esperado:**  
O produto deve ser removido do carrinho.

**Resultado obtido:**  
A preencher após a execução do teste.

**Status:** A EXECUTAR
