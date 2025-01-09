## Exercício 4

Crie um Secret chamado "app-secret" contendo informações sensíveis. Injete o Secret como uma variável de ambiente em um pod e teste se está acessível.

<div align="center"><img src="../assets/image4.png"/>
    <p><i>Todos os recursos</i></p>
</div>
<div align="center"><img src="../assets/image4-1.png"/>
    <p><i>Checando as secrets que foram utilizadas como variáveis de ambiente</i></p>
</div>
<div align="center"><img src="../assets/image4-2.png"/>
    <p><i>Acessando as variáveis de ambiente que foram inseridas no container do PostgreSQL, já decodificadas a partir de código em base64</i></p>
</div>
