# prueba-ia
> 	Intento de gestionar una ia localmente. Para luego crear un agente propio todo en una vm normal. 


<details>
<summary>Instalar docker</summary>

```bash

curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker $USER

```

</details>

<details>
<summary>Clonar Repositorio</summary>

```bash

git clone https://github.com/PabloCarrai/prueba-ia.git


```

Generar .env


```bash


cp .env-Ejemplo .env


```

</details>



<details>
<summary>Iniciar Ollama</summary>

```bash

docker compose up -d
docker compose exec ollama ollama run llama3


```


</details>
