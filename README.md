# Spustenie AWS Localstack služieb
----


### Potrebný softvér
- Python vo verzii aspoň 3.7 resp. v novšej verzii. Link na stiahnutie -> https://www.python.org/downloads/ 
- Pip (Python package manager). Link na stiahnutie -> https://pip.pypa.io/en/stable/installation/
- Docker. Link na stianutie -> https://www.docker.com/get-started/

----

#### Inštalácia Localstack-u pomocou pip
Najjednoduchšia cesta pre inštaláciu Localstack-u je použitie nasôedujúceho príkazu.
```console
> pip install localstack
```
----
  
### Spustenie Localstack-u v Docker kontajneri
```console
> localstack start -d
```
![v](http://drive.google.com/uc?export=view&id=1y90lPE3vqpo-Mw3QpNUKt_WW7yeAPD_O)

----
Následne si viete pozrieť spustený kontajner v Dockeri. Vyzerá to nasledovne:
![v](http://drive.google.com/uc?export=view&id=14yAP89P4L9_RkRdjBO_XmUzb_meQAvUT)
----

### Služby Localstack-u
Na statusy príslušných služieb Localstack-u sa viete pozrieť nasledujúcim príkazom:
```console
> localstack status services
```

Po spustení príkazu sa vám zobrazia jednotlivé statusy služieb Localstack-u, čo môže vyzerať nasledovne:

![v](http://drive.google.com/uc?export=view&id=1y62ka5cLa1SXSjYreXLMyKPuq41yKa2F)

