# Plano de testes

Para cada caso de uso, elabore um **procedimento de teste** para testar o cenário principal.

Em cada procedimento de teste, siga o modelo abaixo:

**Nome do caso de uso:** Consultar tarefas

**Preparação:**

* Criar no sistema um usuário com o perfil de **Funcionário**.
* Cadastrar 5 tarefas para o usuário criado.

**Procedimento de teste:**
![](LoginMack.png)

| Passo | Procedimento | Resultado esperado |
| --- | --- | --- |
| 1 | Executar o navegador Chrome e acesse a URL http://18.188.27.136/mackcupons/ | Apresentação da tela de login do sistema | 
| 2 | Preencher os campos **login** e **password** com os dados de um usuário com perfil de **Aluno ou funcionario**. | Apresentação do painel do menu principal. |
| 3 | Clicar no link **Listar Lanchonetes e Cupons**. | Apresentação das 5 tarefas cadastradas para o funcionário. |

| Passo | Procedimento | Resultado esperado |
| --- | --- | --- |
| 4 | Após clicar no Listar lanchonetes e Cupons, clique em algum restaurante. | Apresentação do menu com lanchonetes | 
| 5 | Verificar qual lanchonete de seu gosto e verificar as promoções.| Apresentação da lanchonete |
| 6 | Pegar o cupom que mais lhe agrada. | Apresentação dos cupons e codigos para oferta. |
