ID: CT-002 
Título: Login com erro de digitacão com espaco 

Pré-condições: 
- O site https://practicetestautomation.com/practice/ 
está aberto 
- Usuário de teste cadastrado: " student" 
- Senha correta: "Password123" 

Passos:
 1. Digitar usuário " student" no campo de login 
 2. Digitar senha "Password123" no campo de senha
 3. Clicar no botão "Submit" (Enviar) 
 
Resultado esperado:
- O sistema não deve permitir o login 
- deve aparecer a mensagem: "dizendo q o usuario colocou espaco no nome de usuario!" 
- Usuário permanece na página de login

Resultado observado:
- mensagem de sucesso "Your username is invalid!"
 
Evidências:

<img width="927" height="461" alt="user espaco" src="https://github.com/user-attachments/assets/70dec6a7-a4f1-4cc9-9ea9-ea5fea7578d8" />

Observação:
- ter um novo tipo de aviso caso esse problema aconteca, para o usuario ficar ciente do erro de digitacao q nao e permitido.
- ou colocar algum codico q impeca colocar espaco automaticamente
