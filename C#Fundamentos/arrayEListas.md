## Array e Listas

- O array é uma estrutura de dados que armazena valores do mesmo tipo, possui tamanho fixo;
- Exemplos de arrays no C#:

	1. int[] array = new int[4];
	2. int[] array = new int[] {42, 75, 74, 61};
	3. string[] nomes = {"Jan", "Fev"};
- Arrays começam a partir do índice 0 no C#;
- Um array também pode ser percorrido com foreach, tem a sintaxe mais simples que um loop for;
- A Classe **Array** possui operações para se trabalhar com um array;
- Para redimensionar um array pode ser usado Array.Resize(), por exemplo:

​		Array.Resize(ref arrayInteiros, arrayInteiros.Length * 2);

- Todo array tem um tamanho fixo que não pode ser reajustado, o Array.Resize apenas copia os valores em um novo Array;
- Array.Copy copia os elementos de um array para outro;
- A lista é semelhante ao array, porém não tem uma capacidade máxima fixa e é mais completa que um array;
- Exemplo da declaração de uma lista:

​		List<string> listaString = new List<string>{};

- A lista trabalha internamente como um array;
- [Slides](https://drive.google.com/file/d/1pj26rJGtM55rtVqOyUhh4KdWODXdyfKb/view) da aula.