 
Título: Login com senha inválida 

Pré-condições: 
- O site https://practicetestautomation.com/practice/ 
está aberto 
- Usuário de teste cadastrado: "student" 
- Senha incorreta: "SenhaErrada" 

Passos: 
1. Digitar usuário "student" no campo de login 
2. Digitar senha "SenhaErrada" no campo de senha 
3. Clicar no botão "Submit" (Enviar) 

Resultado esperado: 
- O sistema não deve permitir o login 
- Mensagem de erro é exibida: "Your username or password is invalid!" 
- Usuário permanece na página de login 

Resultado observado:
- mensagem de erro "Your username or password is invalid!"

 Evidências:
 
  <img width="725" height="388" alt="evidencia de login invalido" src="https://github.com/user-attachments/assets/59c4f748-6235-4b31-8e9b-5d944aee05eb" /> 
  
  
Status: passou


Observação: Ao ocorrer erro de login, os campos de usuário e senha não precisam ser limpos, mantendo os valores digitados pelo usuário para facilitar correção.

***

 
Título: Login com sucesso 

Pré-condições: 
- O site https://practicetestautomation.com/practice/ 
está aberto 
- Usuário de teste cadastrado: "student" 
- Senha correta: "Password123" 

Passos:
 1. Digitar usuário "student" no campo de login 
 2. Digitar senha "Password123" no campo de senha
 3. Clicar no botão "Submit" (Enviar) 
 
Resultado esperado:
- O sistema deve permitir o login 
- deve aparecer a mensagem: "Congratulations student. You successfully logged in!" 
- Usuário deve está nessa url:https://practicetestautomation.com/logged-in-successfully/ 

Resultado observado:
- mensagem de sucesso ""Congratulations student. You successfully logged in!"
 
Evidências:

<img width="1343" height="549" alt="login com sucesso002" src="https://github.com/user-attachments/assets/a476a1a4-df4d-4726-a67b-fbec0833bace" /> Status: passou

***

ID: CT-003 
Título: Login com usuario inválido 

Pré-condições:
- O site https://practicetestautomation.com/practice/ 
está aberto 
- Usuário incorreto: "studentERRO" 
- Senha correta: "Password123"

Passos:
 1. Digitar usuário "studentERRO" no campo de login 
 2. Digitar senha "Password123" no campo de senha 
 3. Clicar no botão "Submit" (Enviar) 
 
Resultado esperado:
- O sistema não deve permitir o login 
- Mensagem de erro é exibida: "Your username is invalid!" 
- Usuário permanece na página de login 
 
Resultado observado:
- mensagem de erro "Your username is invalid!" 
 
 Evidências: 
 
 <img width="945" height="412" alt="userinvalido" src="https://github.com/user-attachments/assets/a5dbe3a8-602b-41b1-9a7f-02a029fae193" />

 Status: passou

 ***


Título: Login com erro de digitacão com espaco 

Pré-condições: 
- O site https://practicetestautomation.com/practice/ 
está aberto 
- Usuário de teste cadastrado: " student" 
- Senha correta: "Password123" 

Passos:
 1. Digitar usuário " student" (com espaco antes)no campo de login 
 2. Digitar senha "Password123" no campo de senha
 3. Clicar no botão "Submit" (Enviar) 
 
Resultado esperado:
- O sistema não deve permitir o login 
- Mensagem de erro é exibida: "Your username is invalid!" 
- Usuário permanece na página de login

Resultado observado:
- mensagem de sucesso "Your username is invalid!"
 
Evidências:

<img width="927" height="461" alt="user espaco" src="https://github.com/user-attachments/assets/70dec6a7-a4f1-4cc9-9ea9-ea5fea7578d8" />


status:passou

Observação:
- Seria interessante exibir um aviso específico para espaços indevidos ou impedir a digitação de espaços no campo de usuário, para melhorar a experiência do usuário.

***

Título: Login com campos vazios

Pré-condições:

- O site https://practicetestautomation.com/practice/ está aberto
- Usuário de teste cadastrado: "student"
- Senha correta: ""

Passos:
1. Digitar usuário "student"no campo de login
2. Digitar senha ""(sem senha)
3. Clicar no botão "Submit" (Enviar)

Resultado esperado:
- O sistema não deve permitir o login.
- Mensagem de erro é exibida (ex.: ‘Your username is invalid!’).
- Idealmente, poderia ser uma mensagem específica para senha vazia.

Resultado observado:
- mensagem de erro "Your username is invalid!"

Evidências:

<img width="793" height="392" alt="005" src="https://github.com/user-attachments/assets/1ae199d3-a9be-4a29-bc46-8e7b23cf68ef" />

status:passou

Observacão;Seria interessante ter uma mensagem especifica para esse tipo de erro tipo"voce esqueceu de preencher a sua senha"

***


Título: Login campo vazio 

Pré-condições: 
- O site https://practicetestautomation.com/practice/ 
está aberto 
- Usuário de teste cadastrado: "" 
- Senha correta: "" 

Passos:
 1. Digitar usuário "" (compo vazio)no campo de login 
 2. Digitar senha "" (campo vazio) no campo de senha
 3. Clicar no botão "Submit" (Enviar) 
 
Resultado esperado:
- O sistema não deve permitir o login 
- Mensagem de erro é exibida: "Your username is invalid!" 
- Usuário permanece na página de login

Resultado observado:
- mensagem de sucesso "Your username is invalid!"
 
Evidências:

<img width="927" height="461" alt="user espaco" src="https://github.com/user-attachments/assets/70dec6a7-a4f1-4cc9-9ea9-ea5fea7578d8" />


status:passou


Observacao:Poderia exibir uma mensagem específica para login com campos vazios (ex.: “Preencha usuário e senha”) ou desabilitar o botão “Submit” enquanto os campos estiverem vazios, evitando envio inválido.

***