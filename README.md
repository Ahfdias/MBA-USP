# MBA-USP

O conjunto de dados de fadiga de aços (NIMS) do Instituto Nacional de Ciência de Materiais foi usado neste trabalho, sendo reconhecido na literatura como um dosmaiores bancos de dados do mundo com detalhes sobre a composição química, propriedadesmecânicas oriundas do processo de laminação e parâmetros relacionados ao processo detratamento térmico. O banco de dados inclui aços carbono e de baixa liga.

Os dados de vida de fadiga, que dizem respeito aos testes de fadiga por flexãorotativa em condições de temperatura ambiente, foram a propriedade alvo para a qualobjetivamos construir modelos preditivos. Os atributos do problema em questão podemser categorizados da seguinte forma:

- Composição química: %C, %Si, %Mn, %P, %S, %Ni, %Cr, %Cu, %Mo (% em peso).
- Dados da laminação: tamanho do lingote e taxa de redução.
- Dados de tratamento térmico: temperatura e tempo de processo para as fasesde normalização, carburização, difusão, endurecimento e têmpera, medidas emlaboratório.
- Propriedade mecânica: resistência à fadiga (Mpa).

Os dados usados neste trabalho possuem 437 instâncias, 25 atributos e 1 variávelobjetivo (resistência à fadiga). As 437 instâncias de dados incluem 371 referentes à açoscarbono e de baixa liga, 48 outros tipos de aço. Esses dados referem-se a vários tiposde tratamento térmico de cada tipo de aço e diferentes condições de processamento.

Feature	Details

C	        %Carbon

Si	      %Silicon

Mn	      %Manganese

P	        %Phosphorus

S	        %Sulphur

Ni	      %Nickel

Cr	      %Chromium

Cu	      %Copper

Mo	      %Molybdenum

NT	      Normalizing Temperature

THT	      Through HardeningTemperature

THt	      Through HardeningTime

THQCr	    Cooling Rate for Through Hardening

CT	      Carburization Temperature

Ct	      Carburization Time

DT	      Diffusion Temperature

Dt	      Diffusion time

QmT	      Quenching Media Temperature (for Carburization)

TT	      Tempering Temperature

Tt	      Tempering Time

TCr	      Cooling Rate for Tempering

RedRatio	Reduction Ratio(IngottoBar)

dA	      Area Proportion of Inclusions Deformed by Plastic Work

dB	      Area Proportion of Inclusion Occurring in Discont. Array

dC	      Area Proportion of Isolated Inclusions

Fatigue	  Fatigue Strength ( 107 , rotating bending cycles)
