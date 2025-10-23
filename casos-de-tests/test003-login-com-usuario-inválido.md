ID: CT-003
Título: Login com usuario inválido

Pré-condições:
- O site https://practicetestautomation.com/practice/ está aberto
- Usuário incorreto: "studentERRO"
- Senha correta: "Password123"

Passos:
1. Digitar usuário "studentERRO" no campo de login
2. Digitar senha "Password123" no campo de senha
3. Clicar no botão "Submit" (Enviar)

Resultado esperado:
 O sistema não deve permitir o login
 Mensagem de erro é exibida: "Your username is invalid!"
 Usuário permanece na página de login

Resultado observado:
mensagem de erro "Your username is invalid!"

Evidências;

<img width="945" height="412" alt="userinvalido" src="https://github.com/user-attachments/assets/541db900-fb13-4a2d-8189-cac416a02ba1" />



Status:
passou
