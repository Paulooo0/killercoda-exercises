## Exercício 8

Crie um Horizontal Pod Autoscaler para um Deployment chamado "hpa-deployment" e configure-o para escalar com base no uso de CPU. Aumente a carga e observe o escalonamento.

<div align="center"><img src="../assets/image8.png"/>
    <p><i>Todos os recursos antes do escalonamento</i></p>
</div>
<div align="center"><img src="../assets/image8-1.png"/>
    <p><i>Instalando o Metrics Server para monitorar o escalonamento</i></p>
</div>
<div align="center"><img src="../assets/image8-2.png"/>
    <p><i>Métricas antes de iniciar o teste de carga</i></p>
</div>

```bash
sudo apt install -y hey
hey -z 5m -c 50 http://localhost:30080
```

<div align="center">
    <p><i>Comandos para instalar e iniciar o teste de carga</i></p>
</div>
<div align="center"><img src="../assets/image8-3.png"/>
    <p><i>Novos pods foram levantados devido ao uso intensivo de CPU após iniciar o teste de carga</i></p>
</div>

<div align="center"><img src="../assets/image8-4.png"/>
    <p><i>Todos os recursos após o escalonamento</i></p>
</div>
