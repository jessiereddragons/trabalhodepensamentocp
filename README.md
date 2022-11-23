# trabalhodepensamentocp

codigoHTML

Html

<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<title>Aparecida Nutrição</title>
		<link rel="icon" href="favicon.ico" type="image/x-icon">
		<link rel="stylesheet" type="text/css" href="css/reset.css">
		<link rel="stylesheet" type="text/css" href="css/index.css">

	</head>
	<body>

		<header>
			<div class="container">
				<h1 class="titulo">Aparecida Nutrição</h1>
			</div>
		</header>
		<main>
			<section class="container">
				<h2>Meus pacientes</h2>
				<table>
					<thead>
						<tr>
							<th>Nome</th>
							<th>Peso(kg)</th>
							<th>Altura(m)</th>
							<th>Gordura Corporal(%)</th>
							<th>IMC</th>
						</tr>
					</thead>
					<tbody id="tabela-pacientes">
						<tr class="paciente" >
							<td class="info-nome">Paulo</td>
							<td class="info-peso">100</td>
							<td class="info-altura">2.00</td>
							<td class="info-gordura">10</td>
							<td class="info-imc">25</td>
						</tr>

						<tr class="paciente" >
							<td class="info-nome">João</td>
							<td class="info-peso">80</td>
							<td class="info-altura">1.72</td>
							<td class="info-gordura">40</td>
							<td class="info-imc">0</td>
						</tr>

						<tr class="paciente" >
							<td class="info-nome">Erica</td>
							<td class="info-peso">54</td>
							<td class="info-altura">1.64</td>
							<td class="info-gordura">14</td>
							<td class="info-imc">0</td>
						</tr>

						<tr class="paciente">
							<td class="info-nome">Douglas</td>
							<td class="info-peso">85</td>
							<td class="info-altura">1.73</td>
							<td class="info-gordura">24</td>
							<td class="info-imc">0</td>
						</tr>
						<tr class="paciente" >
							<td class="info-nome">Tatiana</td>
							<td class="info-peso">46</td>
							<td class="info-altura">1.55</td>
							<td class="info-gordura">19</td>
							<td class="info-imc">0</td>
						</tr>
					</tbody>
				</table>

			</section>
		</main>

		<script> scr="js/principal.js"

		
var titulo = document.querySelector(".titulo");

titulo.textContent = "Aparecida Nutricionista";

var pesoEhValido = true;
var alturaEhValida = true;

if (peso <= 0 || peso >= 1000) {
    console.log("Peso inválido!");
    pesoEhValido = false;
    tdImc.textContent = "Peso inválido";
}

if (altura <= 0 || altura >= 3.00) {
    console.log("Altura inválida!");
    alturaEhValida = false;
    tdImc.textContent = "Altura inválida";
			
	[ 
    {  
        "nome": "Jéssica",
        "peso": 47,
        "altura": 1.54,
        "gordura": 17,
        "imc": 19.82

    },
    {
        "nome": "Flavio",
        "peso": 70,
        "altura": 1.7,
        "gordura": 17,
        "imc": 20.76
    }
//...
}

		</script>
<script src="js/calcula-imc.js"></script>
<script src="js/form.js"></script>
<script src="js/remover-paciente.js"></script>
<script src="js/filtra.js"></script>
<script src="js/buscar-pacientes.js"></script>
	</body>
	
	
	console.log("Aqui tem um recado para você");
	
	alert("Olá");
	
	IMC = peso / altura x altura;
	
	< tr class="paciente" id="primeiro-paciente">...</tr>
<td class="info-peso">100</td>
	
	</script>
	</css>
</html>

