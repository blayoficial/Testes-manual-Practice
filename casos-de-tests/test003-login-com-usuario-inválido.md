ID: CT-003
Título: Login com usuario inválido

Pré-condições:
- O site https://practicetestautomation.com/practice/ está aberto
- Usuário de teste cadastrado: "studentERRO"
- Senha incorreta: "Password123"

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

Evidências:




Status:
passou