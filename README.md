# seuratOnline: R Shiny interface for Seurat single-cell analysis library


## Install:

```
devtools::install_github("aymanm/seuratOnline")
```

## Run:

```
library(seuratOnline)
seuratOnline()
```
This will run on http://0.0.0.0:1234/ by default

***

To run on specific ip/port:

```
ip = '127.0.0.1'
portNumber = 5555
seuratOnline(ip,portNumber)
```
This will run on http://127.0.0.1:5555/

## Screenshots:
![alt text](screenshots/screenshot-input.png "Input Data")

![alt text](screenshots/screenshot-vln.png "Vln Plots")

![alt text](screenshots/screenshot-biomarkers.png "Cluster Biomarkers")
