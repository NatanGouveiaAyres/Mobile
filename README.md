README – Calculadora de Desconto

1. O que é entrada em um sistema computacional? Dê dois exemplos.

Entrada é qualquer informação fornecida pelo usuário ou por outro dispositivo para ser processada pelo sistema.

Exemplos:

- Digitar o preço de um produto em um campo de texto.
- Informar o percentual de desconto em uma calculadora.

2. Qual é a diferença entre processamento e saída?

Processamento é quando o sistema realiza operações com os dados recebidos. Saída é o resultado apresentado após esse processamento.

Na aplicação, o processamento é o cálculo do desconto, enquanto a saída é a exibição do preço final.

3. Por que o valor digitado em um TextField é inicialmente tratado como texto?

Porque o TextField recebe os caracteres digitados pelo usuário como uma String. Para realizar cálculos matemáticos, é necessário converter esse texto para um tipo numérico, como Double.

4. Qual é a finalidade de remember e mutableStateOf?

mutableStateOf cria uma variável observável, cujo valor pode ser alterado. remember mantém esse estado durante as recomposições da interface, evitando que ele seja reiniciado a cada atualização.

5. O que é um evento? Cite os eventos utilizados nesta aplicação.

Evento é uma ação que acontece durante a utilização do sistema e pode provocar uma resposta da aplicação.

Os eventos utilizados são a digitação nos TextFields, por meio de onValueChange, e o clique no botão CALCULAR, por meio de onClick.

6. O que significa recomposição no Jetpack Compose?

Recomposição é o processo pelo qual o Jetpack Compose atualiza as partes necessárias da interface quando um estado utilizado por elas é alterado.

7. Qual é a responsabilidade da MainActivity neste projeto?

A MainActivity é responsável por iniciar a aplicação e definir qual interface será exibida ao usuário, chamando CalculadoraDescontoScreen().

8. Qual é a responsabilidade de CalculadoraDescontoScreen?

É responsável por construir a interface da calculadora, controlar os estados dos campos, receber os valores digitados, validar as entradas, chamar a função de cálculo e apresentar o resultado.

9. Por que calcularPrecoComDesconto foi colocada em outro arquivo?

Para separar a regra de negócio da interface gráfica, deixando o código mais organizado e facilitando sua manutenção e reutilização.

10. Qual é a vantagem de uma função de regra de negócio não depender do Compose?

Ela pode ser utiliza
