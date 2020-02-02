# cowsay_continer
# image cowsay on ubutu 


*  stap 1
make file name test 
*  stap 2
open notpad and write
```
FROM ubuntu

RUN apt update && apt install -y cowsay

CMD ["/usr/games/cowsay", "Dockerfiles are cool!"]

```
*  stap 3
save file whit name Dockerfile

* stap 4
open terminal in file
```
docker build -t cowsay .
```
whait to complet command excute 

* stap 5
```
docker run --rm cowsay
```
