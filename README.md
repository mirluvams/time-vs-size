# time-vs-size

By [mirluvams](https://github.com/mirluvams) ([mirluvams@gmail.com](mailto:mirluvams@gmail.com)), student of the Distributed Computing 2022-2 class taught by Dr. [Victor de la Luz](https://github.com/itztli) at [*Escuela Nacional de Estudios Superiores*, campus Morelia](https://www.enesmorelia.unam.mx/), [UNAM](https://www.unam.mx/).

## Problem
This problem consists in implementing the command "[Mb, time_up, time_download] = pingmb -n <Mb> -ip <dst>".
#### where:
> Mb: file size in Mb
> dst: IP destination
  
## Methodology
* Test for 2 interfaces from 192.168.0.200 from 1Mb, 10Mb, 20Mb,... up to 100Mb (in 10Mb steps):
> 10.99.1.138
> 132.247.186.67
## Instructions
* Finally, plot size vs. time for up and download for the two interfaces.
  
## Procedure - steps
### Steps:
> 1) Exchange keys between the web server and the storage server.
> 2) Copy the file to your account's public directory on the web server.
> 3) Use wget and scp for downloading and uploading data.
> 4) Upload everything to github.
> 5) 1Mb = 1024x1024 bytes.
  
  
## Toolset
* [subprocess]([https://numpy.org/](https://docs.python.org/3/library/subprocess.html))
* pingmb
* [sys](https://docs.python.org/es/3.10/library/sys.html)
* [matplotlib.pyplot](https://matplotlib.org/)
* [Jupyter](https://jupyter.org/)

## References
De la Luz, V. (2022). Class: Dynamic Systems 2022-2. [ENES Unidad Morelia](https://www.enesmorelia.unam.mx/).

## Conclusions
![](s_square.png)
