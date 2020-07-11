# Razão carga-massa

O algoritmo [carga-massa.py](https://github.com/thiagofe/razao_carga_massa-uncertainties/blob/master/Raz%C3%A3o%20carga-massa/carga-massa.py) pode ser aplicado no experimento razão carga-massa para efetuar cálculos que envolvem incertezas experimentais, como por exemplo, campo magnético e razão carga-massa do elétron.

Para executar **carga-massa.py**, utilize um interpretador Python ou [Jupyter Notebook](https://jupyter.org/), contanto é necessário realizar instalação do módulo [Python Uncertainties](https://pythonhosted.org/uncertainties/), vide abaixo guia de instalação. 

## Instalação do Módulo Python Uncertainties

### Distribuições Linux

Se você tem [pip](https://pypi.org/project/pip/), você pode instalar a versão mais recente com:

```pip install --upgrade uncertainties```

Se você tiver [setuptools](https://pypi.org/project/setuptools/), você poderá instalar/atualizar automaticamente este pacote 
com:

```easy_install --upgrade uncertainties```

### Windows

Para instalar este pacote com o [conda](https://pypi.org/project/pip/), execute um dos seguintes procedimentos:

```conda install -c conda-forge uncertainties``` 

```conda install -c conda-forge/label/gcc7 uncertainties``` 

```conda install -c conda-forge/label/cf201901 uncertainties```

### MacOS X

 Usuários que utilizam o gerenciador MacPorts podem instalar uncertainties utilizando:
 
 ```sudo port install py**-uncertainties```, onde ```**``` representa a versão do Python. 
