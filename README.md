# Angular-11
<hello name="{{ name }}"></hello>
<p>
  Start  2021 autor > MatheusAnalista language: node_js
node_js:
  - 4.2.6
before_script: 
  - npm install -g grunt-cli
  - grunt build :)
</p>

<html>

<head>
<title>--Formulário Contato--</title>
<meta charset="utf-8" />
<!--   <link href="ContatoEstilo.css" rel="stylesheet" media="all" />
    <script src="JavaScript1.js"></script>-->
</head>

<body>
<form name="meu_form">

  <h1>Entre em contato</h1>

 <form action="#">
    <div class="row">
        <div class="small-3 columns">
            <label for="lbNumero">CPF/CNPJ</label>
                    </div>
        <div class="small-9 columns">
            <input type="text" id="txtNumero" />
        </div>
    </div>
    <div class="row">
        <div class="small-3 columns">
            <label for="lbNome">SENHA:</label>
        </div>
        <div class="small-9 columns">
            <input type="text" id="txtNome" />
        </div>
    </div>
    <div class="row">
        <div class="small-3 columns">
            <label for="lbSexo">Confirmar:</label>
             <input type="text" id="txtNome" />
        </div>
        <form>
  <div class="form-group">
    <label for="exampleFormControlFile1">Arquivo Documentos: </label>
    <input type="file" class="form-control-file" id="exampleFormControlFile1">
  </div>
</form>
          </div>
    <div class="row">
        <div class="small-3 columns">    
            <label for="lbDataNasc">Data Nascimento:</label>
        </div>
        <div class="small-9 columns">
            <input type="date" id="txtDataNasc" />
        </div>
    </div>
    <div class="row">
        <div class="small-3 columns">   
        </div>
        <div class="small-9 columns">   
            <input type="button" id="btCriarCliente" class="button small" value="Criar" />
            <input type="reset" id="btCancelar" class="button small" value="Cancelar"/>
        </div>
        <button type="submit" name="submit">Enviar</button>
    </div>
</form>

<table>
    <thead>
        <tr>
            
        </tr>
    </thead>
    <tbody>

    </tbody>
</table>
    <fieldset>
      <fieldset class="grupo">
            <div class="campo">
                <label for="nome">Estado onde mora</label>
                <input type="text" id="nome" name="nome" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="snome">Cidade</label>
                <input type="text" id="snome" name="snome" style="width: 10em" value="">
            </div>
        </fieldset>
      <fieldset class="grupo">
            <div class="campo">
                <label for="nome">Nome da Empresa</label>
                <input type="text" id="nome" name="nome" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="snome">Inscrição Estadual</label>
                <input type="text" id="snome" name="snome" style="width: 10em" value="">
            </div>
        </fieldset>
        <fieldset class="grupo">
            <div class="campo">
                <label for="nome">Nome</label>
                <input type="text" id="nome" name="nome" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="snome">Sobrenome</label>
                <input type="text" id="snome" name="snome" style="width: 10em" value="">
            </div>
        </fieldset>
        <div class="campo">
            <label>Sexo</label>
            <label>
                <input type="radio" name="sexo" value="masculino"> Masculino
            </label>
            <label>
                <input type="radio" name="sexo" value="feminino"> Feminino
            </label>
        </div>
        <div class="campo">
            <label>CPF</label>
            <label>
                <input type="radio" name="documento" value="cpf"> 
            </label>
            <label>
                <input type="radio" name="documento" value="cnpj"> CNPJ
            </label>
        </div>
        <div class="campo">
            <label for="email">E-mail</label>
            <input type="text" id="email" name="email" style="width: 20em" value="">
        </div>
        <div class="campo">
            <label for="telefone">Telefone</label>
            <input type="text" id="telefone" name="telefone" style="width: 10em" value="">
        </div>

        <fieldset class="grupo">
            <div class="campo">
                <label for="cidade">Cidade</label>
                <input type="text" id="cidade" name="cidade" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="estado">Estado</label>
                <select name="estado" id="estado">
                    <option value="">--</option>
                    <option value="PR">PR</option>
                    <option value="PR">SP</option>
                    <option value="PR">RJ</option>
                    <option value="PR">GO</option>
                </select>
            </div>
        </fieldset>

        <div class="campo">
            <label for="mensagem">Mensagem</label>
            <textarea rows="6" style="width: 20em" id="mensagem" name="mensagem"></textarea>
        </div>

        <div class="campo">
            <label>Newsletter</label>
            <label>
                <input type="checkbox" name="newsletter" value="1"> Gostaria de receber a Newsletter da empresa
            </label>
        </div>
        <a href="https://api.whatsapp.com/send?phone=5519999999999&text=Texto%20aqui"
    target="_blank"
    style="position:fixed;bottom:20px;right:30px;">
    <svg enable-background="new 0 0 512 512" width="50" height="50" version="1.1" viewBox="0 0 512 512" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><path d="M256.064,0h-0.128l0,0C114.784,0,0,114.816,0,256c0,56,18.048,107.904,48.736,150.048l-31.904,95.104  l98.4-31.456C155.712,496.512,204,512,256.064,512C397.216,512,512,397.152,512,256S397.216,0,256.064,0z" fill="#4CAF50"/><path d="m405.02 361.5c-6.176 17.44-30.688 31.904-50.24 36.128-13.376 2.848-30.848 5.12-89.664-19.264-75.232-31.168-123.68-107.62-127.46-112.58-3.616-4.96-30.4-40.48-30.4-77.216s18.656-54.624 26.176-62.304c6.176-6.304 16.384-9.184 26.176-9.184 3.168 0 6.016 0.16 8.576 0.288 7.52 0.32 11.296 0.768 16.256 12.64 6.176 14.88 21.216 51.616 23.008 55.392 1.824 3.776 3.648 8.896 1.088 13.856-2.4 5.12-4.512 7.392-8.288 11.744s-7.36 7.68-11.136 12.352c-3.456 4.064-7.36 8.416-3.008 15.936 4.352 7.36 19.392 31.904 41.536 51.616 28.576 25.44 51.744 33.568 60.032 37.024 6.176 2.56 13.536 1.952 18.048-2.848 5.728-6.176 12.8-16.416 20-26.496 5.12-7.232 11.584-8.128 18.368-5.568 6.912 2.4 43.488 20.48 51.008 24.224 7.52 3.776 12.48 5.568 14.304 8.736 1.792 3.168 1.792 18.048-4.384 35.52z" fill="#FAFAFA"/></svg>
</a>

        <button type="submit" name="submit">Enviar</button>
        <input type="submit" value="Cadastrar"/> 
        <input type="submit" value="Atualizar"/> 
    </fieldset>
</form>
<div class="container" >
    <a class="links" id="paracadastro"></a>
    <a class="links" id="paralogin"></a>
    
    <div class="content">      
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Criptografia Moip">
    <meta name="author" content="Moip">
    <title>Validação de contas bancárias</title>

    <link href='//fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>
    <link href="https://moip.com.br/docs/stylesheets/screen.css" rel="stylesheet" type="text/css" media="screen" />
    <link href="https://moip.com.br/docs/stylesheets/print.css" rel="stylesheet" type="text/css" media="print" />
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap-theme.min.css">

    <script type="text/javascript" src="http://code.jquery.com/jquery-2.1.3.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>

    <script type="text/javascript" src="build/bank-account-validator.min.js"></script>

  </head>

  <script type="text/javascript">

    $(document).ready(function() {
      $("#validate_bank_account").click(function() {
        Moip.BankAccount.validate({
          bankNumber         : $("#bank_number").val(),
          agencyNumber       : $("#agency_number").val(),
          agencyCheckNumber  : $("#agency_check_number").val(),
          accountNumber      : $("#account_number").val(),
          accountCheckNumber : $("#account_check_number").val(),
          valid: function() {
            $("#success_message").removeClass('hide').fadeIn('slow');
            $("#error_message").fadeOut();
          },
          invalid: function(data) {
            var errors = "Ocorreram os seguintes erros:<br/>";
            for(i in data.errors){
              errors += "- " + data.errors[i].description + "<br/>";
            }
            $("#error_message").removeClass('hide').fadeIn('slow');
            $("#error_message").html(errors);
            $("#success_message").fadeOut();
          }
        });
      });
    });
  </script>

  <body>

    <div class="row">
      <h2 class="form-signin-heading" align="center">Bank Account Validator</h2>
      <hr>

      <div class="col-md-4">&nbsp;</div>

      <div class="col-md-4">

        <div id="success_message" class="alert alert-success hide">Conta Bancária válida</div>
        <div id="error_message" class="alert alert-danger hide"></div>

        <form class="form-signin">

          <div class="row">
            <div class="col-md-12">

              <label>Banco</label>
              <select id="bank_number" class="form-control">
                <option value="">Selecione o banco</option>
                <optgroup label="Principais bancos">
                  <option value="001">BANCO DO BRASIL S.A.</option>
                  <option value="237">BANCO BRADESCO S.A.</option>
                  <option value="341">BANCO ITAÚ S.A.</option>
                  <option value="104">CAIXA ECONOMICA FEDERAL</option>
                  <option value="033">BANCO SANTANDER BANESPA S.A.</option>
                  <option value="399">HSBC BANK BRASIL S.A.</option>
                  <option value="745">BANCO CITIBANK S.A.</option>
                </optgroup>
              </select>
            </div>
          </div>

          <br/>

          <div class="row">
            <div class="col-md-5">
              <label>Agência</label>
              <input id="agency_number" placeholder="Exemplo: 0170" maxlength="5" type="text" class="form-control" />
            </div>
            <div class="col-md-4">
              <label>Dígito</label>
              <input id="agency_check_number" placeholder="Exemplo: 8" maxlength="2" type="text" class="form-control" />
            </div>
          </div>

          <br/>

          <div class="row">
            <div class="col-md-5">
              <label>Conta corrente</label>
              <input id="account_number" placeholder="Exemplo: 97845" maxlength="12" type="text" class="form-control" />
            </div>
            <div class="col-md-4">
              <label>Dígito</label>
              <input id="account_check_number" placeholder="Exemplo: 1" maxlength="2" type="text" class="form-control" />
            </div>
          </div>

          <br/>

          <input type="button" value="Validar conta bancária" id="validate_bank_account" class="btn btn-lg btn-primary btn-block"/>

        </form>

      </div>
    </div>
    <div class="col-md-4"></div>
    <footer class="footer">
      <div class="container">
        <div class="text-muted pull-right">Powered by <b><a href="http://www.moip.com.br">Moip</a></b></div>
      </div>
    </footer>
    <div class="col-md-4"></div>
    
