# ED.03.02 - RDD

Ejercicios prácticos, proyecto de calificaciones y pregunta de reflexión sobre RDDs en PySpark.

Gustavo Adalid Catalán Carmen - 125052712

## Archivos

- `ejercicios_rdd.ipynb`: notebook con todo resuelto
- `notas_mates.txt`, `notas_fisica.txt`, `notas_ingles.txt`: datos del proyecto
- `logs.txt`: datos del ejercicio 5

## Cómo correrlo en Fedora

Instalar Java, Python y git:

```bash
sudo dnf install -y java-17-openjdk-headless python3 python3-pip git
```

Clonar el repositorio y entrar a la carpeta:

```bash
git clone https://github.com/gustavoadalid1-debug/ED.03.02.-RDD--GustavoAdalid.git
cd ED.03.02.-RDD--GustavoAdalid
```

Entorno virtual y dependencias:

```bash
python3 -m venv venv
source venv/bin/activate
pip install pyspark jupyter
```

Abrir el notebook:

```bash
jupyter notebook ejercicios_rdd.ipynb
```

Ejecutar todas las celdas desde cero (Kernel > Restart Kernel and Run All Cells).

## Exportar a PDF

```bash
sudo dnf install -y pandoc texlive-xetex
jupyter nbconvert --to pdf ejercicios_rdd.ipynb
```

Si no se quiere instalar LaTeX, exportar a HTML con `--to html` e imprimir a PDF desde el navegador.
