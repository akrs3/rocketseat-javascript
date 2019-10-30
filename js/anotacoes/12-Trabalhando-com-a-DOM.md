## Trabalhando com a DOM

- Como referenciar elementos do HTML através do JS? Sem ser apenas disparando eventos do HTML para o JS?

1. documento.getElementById('nome'): 
   - Retorna o elemento que possui este ID

2. document.getElementsByTagName('nome'): 
   - Retorna uma lista de elementos que possui esse 'name'

3. document.getElementsByClassName('nome'): 
   - Retorna uma lista de elementos que possuem essa classe

4. document.querySelector('div#app input');
   - Este aqui pode substituir as opcoes anteriores, pois vc informa o local exato onde se encontra o elemento

    - Mais usos: 
    document.querySelector('input[name=nome]');
    inputElement = document.querySelector('input');
    document.querySelector('button.botao');