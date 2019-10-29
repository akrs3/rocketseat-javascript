## Condicionais

- IF, ELSE IF, ELSE

    ``function retornaSexo(sexo){
        // M, F
        // Masculino, Feminino
        if (sexo === 'M'){
            return 'Masculino';
        } else if (sexo === 'F'){
            return 'Feminino';
        }
        else {
            return 'Outro';
        }
    }``

- Switch

    ``function retornaSexo2(sexo){
        switch (sexo){
            case 'M':
                return 'Masculino';
            case 'F':
                return 'Feminino';
            default:
                return 'Outro';
        }
    }``