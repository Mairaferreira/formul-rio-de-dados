# formul-rio-de-dados

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="PT-BR">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="	https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <title>CADASTRO</title>

</head>

<body class="container ">
    <form>
    <legend>CADASTRAR NOVO PRODUTO</legend>
    <h5>Dados básicos</h5>

    <div>
            <div class="row">

                <div class="col-6">
                    <label class="form-label"> Nome do produto:</label>
                    <input ctype="text" class="form-control"></input>
                </div>

                <div class="col-2">
                    <label class="form-label"> Código (SKU):</label>
                    <input ctype="text" class="form-control"></input>
                </div>

                <div class="col-2">
                    <label class="form-label"> preço venda:</label>
                    <input ctype="value" class="form-control"></input>
                </div>

                <div class="col-2">
                    <label class="form-label"> unidade:</label>
                    <input ctype="value" class="form-control"></input>
                </div>
            </div>
    </div>
    <div class="container">
        <div class="row">

            <div class="col-2">
                <label class="form-label"> Condição:</label>
                <select name="opção">
                    <option value="">Usado</option>
                    <option value=""> Semi novo </option>
                    <option value=""> Novo</option>

                </select>


            </div>
            <div class="col-2">
                <label class="form-label">Tipo:</label>
                <select name="opção">
                    <option value="">Tortas</option>
                    <option value="">bebidas e sucos</option>
                    <option value="">Bolos</option>
                    <option value="">Quentinhas</option>
                </select>
            </div>
            <div class="col-2">
                <label class="form-label">produtos com composição:</label>
                <div class="form-check form-switch">
                    <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckChecked" checked>
                    <label class="form-check-label" for="flexSwitchCheckChecked">Desativado</label>
                </div>

            </div>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-2">
                <label class="form-label">categoria:</label>
                <select name="opção">
                    <option value=""> sem categoria</option>
                    <option value=""> com categoria</option>
                    <option value=""> Neutro </option>
                </select>
            </div>
        </div>

        <footer>
            <div class="row">
                <div class="footeres">
                    <br><br> <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
                    <button type="button" class="btn btn-outline-success" class="col-2">Cancelar</button>
                    <label class="colors">Ir para detalhes do protudo</label>
                    <button type="button" class="btn btn-success">Avançar</button>
                </div>

            </div>
        </footer>

      <style>.colors{
        color: darkgreen;
    }
    s
    footer{
        position: absolute;
        margin: 400px;
        
    }
    
    .footer{
        display: flex;
        justify-content: space-evenly;
        
    }
    
    .bek{
        margin-top: 20px;
    }
    </style>
  




