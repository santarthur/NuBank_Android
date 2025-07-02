## NuBankAndroid
Este projeto marca meu primeiro contato com desenvolvimento mobile Android utilizando Java . Inspirado no app do Nubank, o objetivo foi construir um aplicativo simples com múltiplas telas, focando na passagem de dados entre Atividades e na manipulação de elementos da interface .

<br>

## 📱 Sobre o Projeto
O app simula uma experiência de transferência de valores com três telas diferentes. O usuário pode aumentar ou diminuir um número, e esse valor é transferido entre as telas, sendo atualizado e reaproveitado em cada etapa.

<br>

 🚀 Funcionalidades

✅ Tela 1 – MainActivity:
- Exibe o valor atual
- Botões + e – para alterar o valor
- Botão para ir na próxima tela , enviando o valor viaIntent
✅ Tela 2 – PrincipalActivity:
- Recebe o valor da tela anterior
- Permite modificá-lo com botões + e –
- Envie o valor para a próxima tela
✅ Tela 3 – TransferenciaActivity:
- Receba o valor atualizado
- Continuar permitindo alterações
- Exibe o valor de forma destacada
- Possui botão para retornar à primeira tela, mantendo o valor atualizado

<br>

## 🧱 Estrutura do Projeto
- MainActivity.java→ Primeira tela
- PrincipalActivity.java→ Segunda tela
- TransferenciaActivity.java→ Terceira tela
- activity_main.xml, activity_principal.xml, activity_transferencia.xml→ Layouts de telas

<br>

## 💡 Conceitos Aplicados
- Passagem de dados entre Atividades comIntent
- Retorno de valores comActivityResultLauncher
- Manipulação de componentes visuais ( TextView, Button, FloatingActionButton)
- Criação de layouts comConstraintLayout
- Organização de código para facilitar a reutilização e o entendimento do ciclo de vida das Atividades

<br>

## 🛠️ Tecnologias Utilizadas
- Java
- SDK Android (API 34)
- Layout de Restrição
- Componentes de material (FloatingActionButton)


📘 Nota: Desenvolvido em parceria com um colega como parte de uma atividade acadêmica, esse projeto me permitiu explorar a lógica e a estrutura de um aplicativo Android, reforçando conceitos de navegação, estado e manipulação de dados em tempo real. Foi um passo importante na minha jornada como desenvolvedor mobile!
