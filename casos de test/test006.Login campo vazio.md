ID: CT-006
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


Observado:Poderia exibir uma mensagem específica para login com campos vazios (ex.: “Preencha usuário e senha”) ou desabilitar o botão “Submit” enquanto os campos estiverem vazios, evitando envio inválido.