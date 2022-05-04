<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AV1.1</title>
<link rel="stylesheet" href="css.styles.css">
<style>


#page-header {
    background-image: url(https://media.istockphoto.com/vectors/different-types-of-musical-instruments-vector-id820405712);
height: 100px;
background-size: 100px 100px;
}
</style>
</head>

<body>
    <div id="page-header">
        <font color="#6cdf7c">
            <h1 style="text-align: center;">Aulas de Musica</h1>
            <h2 style="text-align: center;">aulas com os melhores professores da cidade</h2>
        </font> 

    </div>

<main>
    <div id="page-sub-header" style="border: 10px #6cdf7c solid;">
        <h3 style="text-align: center;">Não é estudante ainda?
         cadastre-se</h3>
    </div>

       

    <form action="">
        <label for="email">
            <span>E-mail</span>
            <input type="email" id="email" name="email">
           </label>

           <label for="Senha">
            <span>Senha</span>
            <input type="password" id="senha" name="senha">
            </label>
     
            <input type="submit" value="Entrar">
     </form>

</main>
      
<main> <hr>
    <h1 style="text-align: center;">Nossos Professores:</h1>
<h3 style="text-align: center;">Bruno Fragoso (Piano)</h3>
<h3 style="text-align: center;">Nathan Neuman (Violino)</h3>
<h3 style="text-align: center;">Isabelle Castro (Flauta Tranversal)</h3>
<h3 style="text-align: center;">Miqueias Vieira (Violão)</h3>
<h3 style="text-align: center;">Zacarias Fernandes (Canto)</h3>
</main>


</form>
</h3>

    </h3>
    </div>
        <thead> 
        
<h1>Horários:</h1>
    <table border="black">
        <thead style="text-align: center;"> 
            <tr>
                <th>Instrumentos</th>
                <th>Professores</th>
                <th>Segunda</th>
                <th>Terça</th>
                <th>Quarta</th>
                <th>Quinta</th>
                <th>Sexta</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Piano</td>
                <td>Bruno Fragoso</td>
                <td style="text-align: center;">19hrs-20hrs</td>
                <td>18hrs-22hrs</td>
                <td>18hrs-22hrs</td>
                <td>18hrs-22hrs</td>
                <td>18hrs-22hrs</td>
            </tr>
            <tr>
                <td>Violino</td>
                <td>Nathan Neuman</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
            </tr>
            <tr>
                <td>Flauta</td>
                <td>Isabelle Castro</td>
                <td>7hrs-12hrs</td>
                <td>7hrs-12hrs</td>
                <td>7hrs-12hrs</td>
                <td>7hrs-12hrs</td>
                <td>7hrs-12hrs</td>
            </tr>
            <tr>
                <td>Violão</td>
                <td>Miqueias Vieira</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
            </tr>
            <tr>
                <td>Canto</td>
                <td>Zacarias Fernandes</td>
                <td>18hrs-19hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
                <td>13hrs-17hrs</td>
            </tr>
        </tbody>
    </table>
</Td>
</body>

</html>

@import url(https://media.istockphoto.com/vectors/different-types-of-musical-instruments-vector-id820405712);

body {
    background-color: #263b74;
    color: white;
    font-weight: 100;

}
main h1 {
    color:#f7f7fc;
    font-size: 3rem;
    margin-bottom: 3rem;
}

main h3{
    color: white;
    font-size: 1rem;
    margin-bottom: 1rem;
    height: 25px;
    padding: 0 0.5rem;
}

main form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

main form label {
    display: flex;
    flex-direction: column;
}

main form label span {
    font-size:1rem ;
    margin-top: 1rem;
}

main form input {
    background: #edf0f8;
    width: 200px;
    height: 25px;
    padding: 0 0.5rem;
    margin-top: 1rem;
    outline: none;
    color: rgb(159, 199, 192);
    font-size: 1rem;
    border: 1px solid #040B18;
    border-radius: 5px;
}

main form input[type="submit"] {
    cursor: pointer;
    width: 20%;
    margin-top: 1rem;
    border: none;
    border-radius: 22px;
    background: #6c63ff;
    color: white;
    font-size: 1.1rem;
    transition: all .3s ease-in-out;
}

main form input[type="submit"]:hover {
    background: #777f99;
}
