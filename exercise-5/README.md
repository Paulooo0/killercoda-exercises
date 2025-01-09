## Exercício 5

Configure um PersistentVolume de 1Gi de armazenamento local e vincule-o a um PersistentVolumeClaim. Monte o volume em um pod e salve arquivos para verificar a persistência.

<div align="center"><img src="../assets/image5.png"/>
    <p><i>Todos os recursos</i></p>
</div>
<div align="center"><img src="../assets/image5-1.png"/>
    <p><i>PersistentVolumeClaim</i></p>
</div>
<div align="center"><img src="../assets/image5-2.png"/>
    <p><i>Adicionando um arquivo ao volume persistente</i></p>
</div>
<div align="center"><img src="../assets/image5-3.png"/>
    <p><i>Deletando e recriando o pod que armazena o volume, e checando se o arquivo foi persistido</i></p>
</div>
