## Manipulando a DOM: Eventos Inline

- A DOM é composta por todos os elementos dispostos na tela.

- onclick: Evento chamado quando ocorre um click em determinada área da tela
    
    > Ex:   <button onclick="mostraAlerta()">Me pressione</button>
            <script>
                function mostraAlerta(){
                    alert('Botão foi clicado');
                }
            </script>

- onmouseover> Evento chamado ao passar o mouse acima de determinada área da tela

    > Ex: <button onmouseover="mostraAlerta()">Passe a seta</button>
