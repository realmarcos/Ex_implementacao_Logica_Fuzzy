## Exercício de implementação aplicando Lógica Fuzzy

Sistema fuzzy para calcular a dose de quinino a ser aplicada para um viajante com o fim de prevenção de malária. 

### Exercício

**Considere os seguintes conjuntos nebulosos e regras de inferência:**

- Temperatura média do destino (T)
    - Alta: A = {(0, 25), (1, 100)}
    - Baixa: B = {(1, 0), (0, 75)}

- Umidade média do destino (U)
    - Alta: A = {(0, 0), (1, 100)}
    - Baixa: B = {(1, 0), (0, 100)}

- Proximidade a grandes massas de  água (P)
    - Perto: P = {(1, 0), (1, 10), (0, 40)}
    - Longe: L = {(0, 0), (0, 10), (1, 40)}

- Industrialização do destino (I)
    - Alta: A = {(0, 0), (0, 10), (1, 20)}
    - Baixa: B = {(1, 0), (1, 10), (0, 20)}

- Dose de quinino (Q)
    - Alta: A = {(0, 40), (1, 100)}
    - Baixa: B = {(1, 0), (0, 50)}
    - Muito Baixa M = {(1, 0), (0, 10)}

**Regras:**

- Regra 1:
    SE a temperatura for alta
    E a umidade for alta
    E a proximidade da água for perto
    E a industrialização for baixa
    ENTAO a dose de quinino será alta

- Regra 2:
    SE a industrialização for alta
    ENTAO a dose de quinino será baixa

- Regra 3:
    SE a umidade for alta
    E a temperatura for alta
    E a industrialização for baixa
    OU a proximidade da água for perto
    ENTAO a dose de quinino será alta 

- Regra 4:
    SE a temperatura for baixa
    E a umidade for baixa
    ENTAO a dose de quinino será muito baixa

 

 _Sobre: Exemplo prático aplicando a lógica fuzzy. Disciplina de Inteligência Artificial do IFTO campus Paraíso._
