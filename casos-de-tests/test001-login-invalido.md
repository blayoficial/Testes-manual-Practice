ID: CT-001
Título: Login com senha inválida

Pré-condições:
- O site https://practicetestautomation.com/practice/ está aberto
- Usuário de teste cadastrado: "student"
- Senha incorreta: "SenhaErrada"

Passos:
1. Digitar usuário "student" no campo de login
2. Digitar senha "SenhaErrada" no campo de senha
3. Clicar no botão "Submit" (Enviar)

Resultado esperado:
 O sistema não deve permitir o login
 Mensagem de erro é exibida: "Your username or password is invalid!"
 Usuário permanece na página de login

Resultado observado:
mensagem de erro "Your username or password is invalid!"

Evidências:

Status:
passou
