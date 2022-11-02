# C# e .Net

## Estruturas de projeto

- Após o comando **> dotnet new [tipo de aplicação] ** será criada duas pastas e dois arquivos no diretório usado;
- No começo é criada uma classe chamada Program.cs, .cs se trata de um arquivo escrito em c#;
- Também é criado um arquivo .csproj que contém metadados escritos em xml;
- A pasta obj possui arquivos de debug;
- A pasta bin contém os binários do projeto.

## Conceito de classe

- O conceito de classe está diretamente relacionado ao conceito de abstração;

- Molde para criação de objetos que representam entidades do mundo real;

- Convenção do C#: nomes começam com maiúscula no código;

- Class é a palavra chave para definição de classes em C#.

## NameSpaces 

  - Conjunto de classes;

  - È possível criar classes com nomes iguais, porém é necessário ter NameSpaces diferentes;

  - Com a palavra chave **using** é possível usar as classes de um NameSpace em outro arquivo.

## Instanciando uma classe

- Uma classe é instanciada quando um objeto é criado com o seu molde, é usada a palavra new.

## Convenções de escrita

- O C# usa o camelCase e Pascalcase;

- Métodos, classes e propriedades são escritos usando o PascalCase;

- Variáveis usam camelCase;

- Não usar abreviações na escrita de classes;

- O nome do arquivo precisa usar o nome da classe também;

- o _ é o único caractere aceitável para variáveis;

- A sintaxe precisa ser seguida para o código funcionar, embora convenções não sejam obrigatórias para a execução precisam ser usadas para dar mais clareza ao código;

## Tipos de dados no C#

- Utilizar tipo decimal ao invés de double para representar valores monetários, pois o double tem precisão menor;
- Utilizar tipo de dado certo dependendo da precisão ou tamanho;
- A variavél é um espaço da memória do computador;
- È possíverl armazenar data e hora com o tipo DateTime;
- Exemplo DateTime: **DateTime dataAtual = DateTime.Now**, representa o momento atual.
- Pdf dos [slides](https://drive.google.com/file/d/1YLYvIKpMs4d0P2YoiMsoo7aUdheX6g5k/view) da aula.