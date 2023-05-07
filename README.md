## Rodando o mkdocs 
1 - Instale o Python na sua máquina;

2 - Instale a biblioteca mkdocs com `pip install mkdocs` e o template `pip install mkdocs-material`

3 - Com o mkdocs instalado, fica disponível os seguintes comandos
```
mkdocs serve // Inicia o live-reloading server na máquina
mkdocs build // Faz o build da documentação


## para windows é melhor recorrer aos seguintes comandos
python -m mkdocs serve
python -m mkdocs build

## Comando para deploy
mkdocs gh-deploy

python -m mkdocs gh-deploy
```
