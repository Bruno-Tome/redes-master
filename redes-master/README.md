# Universidade de São Paulo

# Aplicativo Cliente e Servidor com uso de socket
<h3>Trabalho 1 - SSC0641 - Redes de Computadores (2022-2)</h3>

Bruno Tomé Rosa - Nº USP: 10276654 </br>
Luiz Fernando Silva Eugênio dos Santos - Nº USP: 10892680 </br>


<p>Prof. Dr. Rodolfo Ipolito Meneguette</p>

<hr>
<h3>Descrição</h3>
<p>O projeto consiste de um servidor que atende a vários clientes em uma ala médica. Esses clientes são medidores de batimentos cardíacos que enviam os valores coletados dos pacientes a cada um determinado intervalo de tempo. Cada cliente que acessa os serviços do servidor tem seus valores de batimentos e horário instantâneo registrados no arquivo do devido paciente. Além disso, existe um tratamento de dados no servidor que analisa os dados dos batimentos e retorna o quadro do paciente (estável ou com necessidade de cuidados urgentes).</p>

<p>Versão do sistema operacional: Ubuntu 18.04</p>

<p>Compilador: gcc (Ubuntu 7.5.0-3ubuntu1~18.04) 7.5.0</p>


<hr>
<h3>Executar:</h3>

#### Compilar programa:
`$ make`

#### Executar servidor:
`$ ./server`

#### Executar cliente:
`$ ./client`

