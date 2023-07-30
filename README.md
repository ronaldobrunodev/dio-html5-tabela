# dio-html5-tabela
Este é um modelo prévio usando HTML e CSS para demonstrar as funcionalidades das TAGs do TABLE.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!--<link rel="stylesheet" href="style.css" />-->
    <style>
    body{
    background-color: #e5e7e7; /*#0d1b2a*/   
    font-family:sans-serif ; 
    font-size: 16px; 
    } 
    table{
        -webkit-box-shadow: 10px 10px 6px 3px rgba(0,0,0,0.35);
        box-shadow: 10px 10px 6px 3px rgba(0,0,0,0.35);
        border: solid 1px #312635;       
    }
    caption{
        padding-top: 3px;
        background-color: #312635;
        color: bisque;
        border-top-left-radius: 3px;
        border-top-right-radius: 3px
    }
    table thead th {
        background-color: #312635;
        color: bisque;
        min-width: 120px;
        max-width: 250px;   
        padding: 2px;        
    }
    table tfoot td{
        background-color: #312635;
        color: bisque;
        min-width: 120px;
        max-width: 250px;   
        padding: 2px;    
        text-align: center;
    }    
    table tbody tr:nth-child(even) td{
        background-color: #c9ccbf;
    }  
    table tbody tr:hover td{
        background-color: #312635;
        color: bisque;
    }
    </style>
    <title>Html 5 Dio - Tabela</title>
</head>
<body>
    <table cellspacing="0">
        <caption>TABELA DE DADOS</caption>
        <thead>
            <tr>
                <th title="Nome completo">NOME</th>
                <th title="Idade">IDADE</th>
            </tr>
        </thead>
       <tbody>
            <tr>
                <td>Ronaldo</td>
                <td>32</td>
            </tr>
            <tr>
                <td>Bruno</td>
                <td>33</td>
            </tr>
            <tr>
                <td>Cardoso</td>
                <td>34</td>
            </tr>
            <tr>
                <td>Fenômeno</td>
                <td>35</td>
            </tr>           
       </tbody>
       <tfoot>
        <tr>
            <td>Total</td>
            <td>365</td>        
        </tr>
    </tfoot>
    </table>
</body>
</html>
