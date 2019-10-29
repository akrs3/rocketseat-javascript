## Condição Ternária

- Apenas duas verificações no **IF**, ou seja, se else está validando uma condição ou não está.

- Para isto, usa-se apenas um **IF** e um **ELSE**.

- Exemplo:

    ``
    if (sexo === 'Feminino'){
        retorno = 'Feminino';
    } else {
        retorno = 'Masculino';
    }
    ``
    
    
    Isto equivale a condição ternária:


    `` (condicao) ? (resultado se a condição for verdadeira) : (resultado se a condição for falsa) ``
    ``var retorno = (sexo === 'F') ? 'Feminino' : 'Masculino';``