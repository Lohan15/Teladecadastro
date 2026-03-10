<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Ficha de Inscrição</title>
</head>
<body>

    <form action="#" method="post">
        <table border="1" align="center" cellpadding="10">
            <tr>
                <td>
                    <h2 align="center">Ficha de Inscrição</h2>
                    
                    <table border="0" cellpadding="5">
                        <tr>
                            <td>Nome do candidato:</td>
                            <td colspan="3">
                                <input type="text" name="nome" size="60">
                            </td>
                        </tr>

                        <tr>
                            <td>Endereço:</td>
                            <td colspan="3">
                                <input type="text" name="endereco" size="60">
                            </td>
                        </tr>

                        <tr>
                            <td>CEP:</td>
                            <td>
                                <input type="text" name="cep" size="15">
                                -- Cidade --
                                <select name="cidade">
                                    <option value="">Selecione</option>
                                </select>
                                -- UF --
                                <select name="uf">
                                    <option value="">--</option>
                                </select>
                            </td>
                        </tr>

                        <tr>
                            <td>Telefone:</td>
                            <td colspan="3">
                                <input type="text" name="tel1" size="15">
                                <input type="text" name="tel2" size="15">
                                <input type="text" name="tel3" size="15">
                            </td>
                        </tr>

                        <tr>
                            <td>RG:</td>
                            <td>
                                <input type="text" name="rg" size="15">
                                CPF: <input type="text" name="cpf" size="15">
                                Sexo: 
                                <input type="radio" name="sexo" value="M"> Mas.
                                <input type="radio" name="sexo" value="F"> Fem.
                            </td>
                        </tr>

                        <tr>
                            <td>Escolaridade:</td>
                            <td>
                                <select name="escolaridade">
                                    <option value="">-- Selecione --</option>
                                </select>
                                Email: <input type="email" name="email" size="30">
                            </td>
                        </tr>

                        <tr>
                            <td>Curso:</td>
                            <td>
                                <select name="curso">
                                    <option value="">-- Selecione --</option>
                                </select>
                                Senha de acompanhamento: <input type="password" name="senha" size="10">
                            </td>
                        </tr>

                        <tr>
                            <td colspan="4" align="center">
                                <br>
                                <input type="submit" value="CADASTRAR">
                            </td>
                        </tr>
                    </table>

                </td>
            </tr>
        </table>
    </form>

</body>
</html>
