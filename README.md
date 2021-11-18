# produtos

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aprendendo Javascript</title>
</head>
<body>
    <h1>Lógica de programação com javascript</h1>

    <div id="output"></div>
</body>

<script>
    /*Problema: mostrar na tela todos os produtos disponiveis para compra. Os nomes dos produtos devem estar agrupados num array*/
    var produtos=newArray('caneta', 'lapis', 'tesoura','borracha', 'caderno','livro');

    var output=document.querySelector('#output');

    var msg='';
    for(var i=0; i<6; i++){
        msg+=produto+(i+1)+':'+produtos[i]+'<br>';
    }

    output.innerHTML=msg;
</script>

</html>
