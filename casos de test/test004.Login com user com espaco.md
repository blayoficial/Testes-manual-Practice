ID: CT-004
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