# Guía de Inicio – Inventrack

## Instalación

Sigue estos pasos para instalar Inventrack en Windows:

=== "Windows"

    ```powershell
    git clone https://github.com/miempresa/inventrack.git
    cd inventrack
    python -m venv .venv
    .venv\Scripts\activate
    pip install -r requirements.txt
    ```

=== "Linux / macOS"

    ```bash
    git clone https://github.com/miempresa/inventrack.git
    cd inventrack
    python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```

??? info "¿Y si me sale error con pip?"
    Ejecutá `python -m ensurepip` para forzar la instalación de pip si no lo detecta.

![Pantalla inicial del sistema](img/screenshot.png)
