# Simulador sorteo Primitiva

Un peque�o experimento del 2012 escrito en Python con una interfaz en WxPython para visualizar las posibilidades de conseguir un premio de cada categor�a en base a un n�mero determinado de intentos.

## Demo

<img src="/docs/demo.gif"/>

## Utilizaci�n con Pipenv

```bash
# Instalaci�n de pipenv
pip install pipenv

# Instalaci�n de dependencias
cd primitiva-python/
pipenv install -r requirements.txt

# Ejecuci�n del script
pipenv run python primitiva.py
```

## Nota

Este simulador no est� planteado correctamente y tiene varios fallos, como codificar directamente en el fichero de la interfaz o un mal uso (aunque funcional) de los threads. Pero a fin de cuentas forma parte de mi aprendizaje y cuando lo realic� estaba muy orgulloso de �l.