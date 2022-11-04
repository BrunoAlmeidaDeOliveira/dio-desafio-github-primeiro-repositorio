## Casting

- Casting: conversão do tipo da variável;
- Casting em c# usa a classe **Convert** seguida por um método que informa o tipo da conversão, por exemplo **Convert.ToInt32("9");** que converte o dado em um inteiro de 32 bits;
- Existe também o método **Parse** que converte um tipo em outro, por exemplo **int.Parse("7");**;
- A diferença entre o método **Parse** e a classe **Convert** está no tratamento de nulos , convert converte o nulo em 0 e Parse lança um erro e encerra o programa;
- O método **.ToString** converte o dado em uma string;
- O C# obedece a ordem das operações matemáticas;
- O método **TryParse()** tenta converter um valor e caso não consiga usa o segundo argumento como valor convertido, exemplo **int.TryParse(a, out b)**, no qual a é o valor que será convertido e b é o valor usado em caso de falha na conversão; 

- [Pdf](https://drive.google.com/file/d/1ofWoOF1kjrWzNSSJZkohvGkx66ENiFbI/view) com outros assuntos da aula.