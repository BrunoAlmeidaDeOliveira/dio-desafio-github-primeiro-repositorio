## Estrutura de um programa C#

- **.csproj** possui informações referentes ao projeto (build, debug, versão);
- **.sln** (solution) contém informações que carregam um agrupamento de projetos, ele serve para melhorar a organização do projeto;
- Projeto auxiliar common pode ter classes que diferentes projetos usam, evitando ter que escrever o mesmo código duas vezes;
- Ao criar um projeto automaticamente é usada a ultima versão do .NET instalada na máquina, para usar outra versão, a 5.0 por exemplo **dotnet new console --framework net5.0 **;
- O arquivo program.cs é o ponto de entrada principal do projeto;
- Antes da versão 6.0 o código era implementado dentro do método **main**, logo após o método main está oculto;
- Não há problema em inserir o método main nas novas versões, apenas não será usado;
- [Slides](https://drive.google.com/file/d/1JPKcUPpxdjCipJFzeND2WuOM8npY7vzL/view) da aula.