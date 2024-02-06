
<h1 align="center">

<img src="https://img.shields.io/static/v1?label=RISK%20WOMAN%20POR&message=Bates&color=7159c1&style=flat-square&logo=ghost"/>

<h3> <p align="center">Maternal Health Risk</p> </h3>

<h3> <p align="center"> ================= </p> </h3>

>> <h3> Objetivo </h3>
-----
<p> O objetivo principal deste projeto é desenvolver um modelo de Machine Learning para prever o risco de pacientes. O modelo será treinado com base em um conjunto de dados contendo informações sobre pacientes, como idade, sexo, histórico médico, resultados de exames e nível de risco.
 </p>



>> <h3> Glossary </h3>

Fields              | Description                                               | Categorical | Numerical | Ordinal | Nominal
---------------------|:---------------------------------------------------------:|:-----------:|:---------:|:-------:|:-------:
Age                 | Idade em anos.                                             | False       | True      | False   | False
SystolicBP          | Denota o valor superior da pressão arterial em milímetros de mercúrio (mmHg), um atributo significativo durante a gravidez.                    | False       | True      | False   | False
DiastolicBP         | Representa o menor valor da pressão arterial em milímetros de mercúrio (mmHg), outro atributo crucial no monitoramento da saúde materna. | False       | True      | False   | False
BS                  | Indica os níveis de glicose no sangue medidos em termos de concentração molar, especificamente em milimoles por litro (mmol/L). | False       | True      | False   | False
BodyTemp	   | Denota a temperatura corporal da mulher grávida em Fahrenheit (°F), fornecendo informações adicionais sobre os aspectos fisiológicos relevantes para a saúde materna.| False | True | False | False
HeartRate           | Representa a frequência cardíaca normal em repouso em batimentos por minuto (bpm), um parâmetro vital para avaliar a saúde cardiovascular durante a gravidez.       | False       | True      | False   | False
RiskLevel           | Nível de intensidade de risco previsto durante a gravidez, levando em consideração os atributos de saúde mencionados. Esta variável serve como alvo para nossos modelos de aprendizado de máquina.         | True        | False     | False   | True

