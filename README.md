<h1>🪪Um sistema de controle de piscinas de um clube.</h1>

<h2>💻Tecnologia:</h2>

- Linguagem C

<h2>🚀Sobre o sistema:</h2>
Este clube possui 4 piscinas de profundidades diferentes:

* Piscina com 40cm de profundidade, onde apenas crianças menores de 7 anos e seus responsáveis (maior de 18 anos) podem frequentar.
* Piscina com profundidade de 1,50m, onde apenas pessoas a partir de 7 anos podem acessar.
* Piscina com profundidade de 2,50m, onde apenas adultos podem frequentar
* E uma piscina de 3m de profundidade, onde apenas os atletas do clube podem acessar.

<h2>
    🚀O software precisa apresentar um menu para o usuário com as seguintes opções:
</h2>
<ol>
    <li>- Cadastrar cliente</li>
    <li>- Buscar cadastro de cliente</li>
    <li>- Editar cadastro de cliente</li>
    <li>- Listar todos os clientes cadastrados</li>
    <li>- Listar clientes por piscina permitida</li>
    <li>- Listar apenas clietes atletas</li>
    <li>- Excluir cliente cadastrado</li>
    <li>- Sair do sistema</li>
</ol>

  * Todo cliente precisa possuir um Nome completo, CPF, idade, Endereço, matrícula e informar se é um atleta ou não.

 <h3>
   🚀Exigências:
  </h3>
  
* A matrícula deve ser um número de 7 dígitos gerados de forma aleatória no momento em que o cliente é cadastrado.

* Cada item do menu deve ser processado por uma subrotina.
  
* O sistema só pode ser encerrado quando o usuário escolher a opção 8 do menu.
  
* O sistema deve comportar no máximo 200 clientes cadastrados. Se passar desta quantidade, não pode permitir que o usuário cadastre, retornando pra ele um alerta.
  
* A exclusão, edição ou busca de um cliente cadastrado no sistema deve ser realizada por CPF ou Matrícula.

<h3>
  🚀Etapa final: Validação de dados
</h3>

* O código não pode permitir que sejam inseridas informações em branco nos campos de cadastro do cliente.

* O código não deve aceitar caracteres que não sejam numéricos no CPF e deve exigir que o CPF possua 11 digitos.
  
* O código deve validar se aquele CPF informado é um CPF válido.
  
* O desenvolvedor deve garantir que evitou buffer overflow nos vetores.
