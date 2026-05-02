# estudos-notebooklm
Repositório para estudos voltado ao NotebookLM

Assunto escolhido foi as funções trignométricas, por conta que é um tema que desafiou bastante quando estava no ensino médio e foi
onde precisei de um empenho maior para aprender, e com meu esforço e emprenho no fim consegui aprender e tirar notas excelentes nas provas. 
Então gostaria de relembrar esse tema de forma carinhosa desse tempo que passou!


Links das Fontes: 

https://www.todamateria.com.br/funcoes-trigonometricas/

https://brasilescola.uol.com.br/matematica/funcoes-trigonometricas-1.htm

https://pt.khanacademy.org/math/trigonometry/unit-circle-trig-func


📘 Teste de Prompts – Funções Trigonométricas
🔹 Diferenças entre seno, cosseno e tangente
Definição no ciclo trigonométrico:

Seno: ordenada (eixo y).

Cosseno: abscissa (eixo x).

Tangente: razão 
tan
⁡
𝑥
=
sin
⁡
𝑥
cos
⁡
𝑥
.

Domínio e Imagem:

Seno e Cosseno: domínio 
𝑅
, imagem 
[
−
1
,
1
]
.

Tangente: domínio 
𝑅
∖
{
𝜋
2
+
𝑘
𝜋
}
, imagem 
𝑅
.

Período e Paridade:

Seno e Cosseno: período 
2
𝜋
.

Tangente: período 
𝜋
.

Paridade: seno e tangente são ímpares; cosseno é par.

Comportamento nos quadrantes:

Seno: positivo em I e II.

Cosseno: positivo em I e IV.

Tangente: positiva em I e III, sempre crescente.

Gráficos:

Seno: senoide.

Cosseno: cossenoide.

Tangente: tangentoide com assíntotas verticais.

🔹 Multiplicar seno “por fora” ou “por dentro”
Por fora (
𝑏
⋅
sin
⁡
𝑥
):

Afeta a amplitude vertical.

Expansão se 
∣
𝑏
∣
>
1
; contração se 
0
<
∣
𝑏
∣
<
1
.

Se 
𝑏
<
0
, há inversão de fase.

Por dentro (
sin
⁡
(
𝑐
⋅
𝑥
)
):

Afeta o período/frequência horizontal.

Se 
𝑐
>
1
, contração horizontal (mais ciclos).

Se 
0
<
𝑐
<
1
, expansão horizontal (menos ciclos).

Novo período: 
𝑇
=
2
𝜋
∣
𝑐
∣
.

🔹 Situações da vida real
Saúde: pressão arterial, batimentos cardíacos.

Natureza: marés, variação de temperatura, luz solar.

Economia: preços sazonais, oscilações de mercado.

Engenharia/Navegação: cálculo de distâncias, movimento circular.

Física: intensidade luminosa, ondas.

🔹 Aplicação em programação (Python)
Exemplo: modelagem da pressão arterial

python
import math

# Parâmetros
a = 99      # valor médio
b = 21      # amplitude
k = 3 * math.pi  # frequência (90 bpm)

def calcular_pressao(t):
    return a + b * math.cos(k * t)

# Exemplo de uso
t = 0.5
print(f"Pressão no instante {t}s: {calcular_pressao(t):.2f} mmHg")



📘 RESUMO SOBRE AS FUNÇÕES TRIGONOMÉTRICAS

1. Conceito
As funções trigonométricas relacionam ângulos com razões entre lados de triângulos retângulos. Elas são periódicas e fundamentais para descrever fenômenos cíclicos como ondas, oscilações e movimentos circulares.

2. Principais Funções
Seno (sen x): Mede a razão entre o cateto oposto e a hipotenusa.

Cosseno (cos x): Mede a razão entre o cateto adjacente e a hipotenusa.

Tangente (tan x): Mede a razão entre o cateto oposto e o cateto adjacente.

3. Características
Domínio: Conjunto de valores possíveis para a variável (ângulo).

Imagem: Intervalo de valores que a função pode assumir.

Período: Intervalo em que os valores se repetem (seno e cosseno têm período 
2
𝜋
; tangente tem período 
𝜋
).

Paridade:

Seno e tangente → funções ímpares.

Cosseno → função par.

4. Aplicações
Matemática: Resolução de triângulos, análise de gráficos periódicos.

Física: Estudo de ondas, movimentos harmônicos e vibrações.

Engenharia: Circuitos elétricos alternados, telecomunicações e modelagem de estruturas.

Ciências Naturais: Fenômenos como marés e órbitas planetárias.

5. Pontos-chave para estudo
Memorizar os gráficos das funções.

Entender domínio, imagem e período.

Reconhecer simetrias (funções pares e ímpares).

Praticar aplicações em problemas reais e exercícios.


📘 Glossário – Funções Trigonométricas

🔹 Função Seno
Definição: Relaciona o valor de um ângulo com a ordenada (y) do ponto correspondente no ciclo trigonométrico.

Características:

Domínio: todos os números reais (
𝑅
).

Imagem: intervalo 
[
−
1
,
1
]
.

Período: 
2
𝜋
 (360°).

Paridade: função ímpar (
sin
⁡
(
−
𝑥
)
=
−
sin
⁡
(
𝑥
)
).

Raízes: 
𝑥
=
𝑘
𝜋
, com 
𝑘
∈
𝑍
.

Gráfico: curva chamada senoide, oscilando entre -1 e 1.

Sinais nos quadrantes: positivo no 1º e 2º quadrantes; negativo no 3º e 4º.

Aplicações: modelagem de fenômenos periódicos (batimentos cardíacos, marés, intensidade da luz solar).

🔹 Função Cosseno
Definição: Associa cada ângulo à abscissa (x) do ponto correspondente no ciclo trigonométrico.

Cálculo:

No ciclo: projeção da extremidade do arco sobre o eixo horizontal.

Em triângulos retângulos: razão entre cateto adjacente e hipotenusa.

Valores notáveis:

cos
⁡
(
0
)
=
1

cos
⁡
(
𝜋
/
2
)
=
0

cos
⁡
(
𝜋
)
=
−
1

cos
⁡
(
3
𝜋
/
2
)
=
0

cos
⁡
(
2
𝜋
)
=
1

Características:

Domínio: todos os números reais (
𝑅
).

Imagem: intervalo 
[
−
1
,
1
]
.

Período: 
2
𝜋
.

Paridade: função par (
cos
⁡
(
−
𝑥
)
=
cos
⁡
(
𝑥
)
).

Gráfico: curva chamada cossenoide.

Transformações:

𝑓
(
𝑥
)
=
𝑎
+
𝑏
⋅
cos
⁡
(
𝑐
𝑥
+
𝑑
)
, onde:

𝑎
: deslocamento vertical.

𝑏
: amplitude.

𝑐
: período (
𝑇
=
2
𝜋
∣
𝑐
∣
).

𝑑
: deslocamento horizontal (fase).

🔹 Função Tangente
Definição: Razão entre seno e cosseno (
tan
⁡
𝑥
=
sin
⁡
𝑥
cos
⁡
𝑥
).

Características:

Domínio: 
𝑅
∖
{
𝜋
2
+
𝑘
𝜋
,
𝑘
∈
𝑍
}
.

Imagem: todos os números reais (
𝑅
).

Período: 
𝜋
 (180°).

Paridade: função ímpar (
tan
⁡
(
−
𝑥
)
=
−
tan
⁡
(
𝑥
)
).

Crescimento: sempre crescente nos intervalos de seu domínio.

Gráfico: curva chamada tangentoide, composta por ramos separados por assíntotas verticais (
𝜋
/
2
,
3
𝜋
/
2
,
.
.
.
).

Inversa: arco tangente (
arctan
⁡
𝑥
), definida no intervalo 
[
−
𝜋
/
2
,
𝜋
/
2
]
.

- CONJUNTO DE PROMPTS -

Quais as principais diferenças entre as funções seno, cosseno e tangente?

Em quais situações da vida real eu posso utilizar as funções seno, cosseno ou tangente?

Como identificar se uma função é par ou ímpar?

O que acontece com o gráfico se multiplicarmos o seno?
