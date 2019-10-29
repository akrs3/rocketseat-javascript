## Intervalo e timeout

- Intervalo: finção que executa várias vezes num intervalo.

* setInterval: Repete uma função a cada intervalo de tempo:

    - Formato: setInterval(nome-da-function, tempo);
    - Ex: 

        function exibeAlgo(){
            console.log('Hello World');
        }
        setInterval(exibeAlgo, 1000);

- Timeout:

* setTimeout: executa 1 vez com um delay de X segundos.

    - Formato: setTimeout(nome-da-function, tempo-delay);
    - Ex: setTimeout(exibeAlgo, 5000);