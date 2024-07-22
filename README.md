# Repositório do projeto ```SBBD-DSW 2024```: [https://github.com/NESPEDUFV/sbbd-dsw-2024](https://github.com/NESPEDUFV/sbbd-dsw-2024)

# Dicas para manipular os _datasets_

> ## 1. Crie um ambiente virtual para instalar os pacotes pip necessários.

```sh
sudo apt-get install python3-dev python3-venv python3-tk
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

> ## 2. Abra o arquivo ```Exemplo de uso.ipynb``` (Dica para o VSCode)
> - Clique em ```Select kernel```
> - Clique em ```Python Enviroments...```
> - Selecione: ```venv/bin/python3```

> ## 3. Extraia os arquivos ```*.7z``` localizados na pasta ```data```

> ## 4. Execute as células do arquivo ```Exemplo de uso.ipynb```

> ## 5. (Opcional) Caso seja necessário construir as rotas de ônibus através dos vértices enriquecidos, o arquivo ```data/linhas_de_onibus_sp_curitiba.csv``` conta com as linhas de ônibus das duas cidades, já mapeadas para os IDs dos vértices dos grafos.