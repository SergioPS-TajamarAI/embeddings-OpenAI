Para poder ejecutar correctamente los ejercicios, se debe tener un fichero config.json con la siguiente estructura: 
```json
{
  "EMBEDDINGS_MODEL": "text-embedding-ada-002",
  "OPENAI_API_BASE": "<API_ENDPOINT>",
  "OPENAI_API_KEY": "<API_KEY>",
  "OPENAI_API_VERSION": "2022-12-01"
}
```

Crear un entorno virtual (venv) para ejecutar el notebook, para ello: 
Intalar virtualenv si no se tiene
```bash
pip install virtualenv
```
Crear un venv en la carpeta del proyecto
```bash
virtualenv .venv
```
Entrar en el venv:
```bash
.\.venv\Scripts\activate
```
Instalar los paquetes:
```bash
pip install -r requirements.txt
```
Una vez instalados los paquetes necesarios del requirements.txt, el notebook debe funcionar correctamente
