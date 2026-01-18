# ML i eksploracja danych

Ten katalog zawiera projekt ksiazki w Quarto oraz konfiguracje srodowiska Python 3.12.

## Uruchomienie srodowiska (uv)

```bash
uv venv --python 3.12
source .venv/bin/activate
uv sync
```

## Renderowanie ksiazki

```bash
python -m ipykernel install --user --name ml-and-dm-uv --display-name "ml-and-dm (uv)"
quarto render
```
