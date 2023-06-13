# Mussum-faixa-preta-cumpadi
Primeito projeto em HTML
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício 1</title>
</head>

<body>
    <div id="div-boas-vindas">
        <h1>Olá, bem-vindos ao projeto de HTML - Por Diogo Gomes!</h1>

        <h6>O Melhor Processo de Aprendizagem</h6>
    </div>

    <h4>Controle de Cursos</h4>
    <img src="notebook.png" title="Cadastro de Aluno" style="cursor: pointer;" />
    <img src="database.png" title="Consulta de Registros" style="cursor: pointer;" />
    <br>
    <br>

    <div id="div-menu">
        <table>
            <thead style="background-color: #05142b; color: rgba(226, 220, 220, 0.918); line-height: 24px;">
                <tr>
                    <th>Nome do Curso</th>
                    <th>Carga Horária</th>
                    <th>Grade Curricular</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Adobe Ilustrator</td>
                    <td>30h</td>
                    <td>link</td>
                </tr>
                <tr>
                    <td>Banco de Dados Oracle</td>
                    <td>60h</td>
                    <td>link</td>
                </tr>
                <tr>
                    <td>Linguagem Python</td>
                    <td>60h</td>
                    <td>link</td>
                </tr>
                <tr>
                    <td>Marketing Digital</td>
                    <td>40h</td>
                    <td><a href="https://github.com/Diogo-Ag33" target="_blank">link</a></td>
                </tr>
            </tbody>
        </table>
    </div>

    <div id="div-form">
        <h4>Formulário de Contato</h4>
        
        <p>
            Mussum faixa preta cumpadi. 
        </p>

        <form>
            <label style="margin-right: 80px;">Nome</label>
            <input type="text" required />
            <br>   

            <label style="margin-right: 81px;">Email</label>
            <input type="email" />
            <br>

            <label style="margin-right: 20px;">Tipo de contato</label>
            <select>
                <option>Selecione uma opção</option>
                <option>Crítica</option>
                <option>Dúvida</option>
                <option>Sugestão</option>
            </select>
            <br>

            <label style="margin-right: 50px;">Mensagem</label>
            <textarea cols="25" rows="3"></textarea>
            <br>

            <input type="checkbox"> Informo que os dados fornecidos são válidos
            <br><br>

            <button type="submit" style="border:none; background-color: #5294F9; padding: 10px 25px; border-radius:5px; font-weight: bold; width: 330px; cursor: pointer;" title="Clique para enviar o form
        </form>
    </div>
</body>

</html>




