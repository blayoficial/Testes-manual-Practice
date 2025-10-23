ID: CT-005 Título: Login com campos vazios

Pré-condições:

O site https://practicetestautomation.com/practice/ está aberto
Usuário de teste cadastrado: "student"
Senha correta: ""
Passos:

Digitar usuário "student"no campo de login
Digitar senha ""(sem senha)
Clicar no botão "Submit" (Enviar)
Resultado esperado:

O sistema não deve permitir o login
Mensagem de erro é exibida: "Your password is invalid!"
Usuário permanece na página de login

Resultado observado:
mensagem de erro "Your username is invalid!"
Evidências:

<img width="793" height="392" alt="005" src="https://github.com/user-attachments/assets/1ae199d3-a9be-4a29-bc46-8e7b23cf68ef" />

Observacão;Seria interessante ter uma mensagem especifica para esse tipo de erro tipo"voce esqueceu de preencher a sua senha"
