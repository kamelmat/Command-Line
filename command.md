# Listado de comandos comunes en Linux

💻Una Primera aproximación a los **comandos** del Terminal 💻

## Algunos de los más importantes

#### 1️⃣ pwd
Con pwd podemos saber en que directorio nos encontramos en este momentos.(*Present Working Directory*)

#### 2️⃣ ls
en ls utilizamos unas cuantas *variables*
> - **`ls -a`** Esta nos sirve para ver todo sin ignorar ningún archivo escondido.
> - **`ls -R`** Lista los subdirectorios recursivos

#### 3️⃣ cd

Utilizamos este comando para movernos entre directorios, cambiar entre ellos

> - la variable **`cd ..`** nos sube un directorio arriba
> - la variable **`cd ~`** nos lleva al directorio raiz

#### 4️⃣ cp

Copia archivos y directorios

#### 5️⃣ mkdir

Utilizamos este comando para crear un directorio
> En el caso de que quisieramos crear un directorio en un directorio especifico podemos hacerlo usando `mkdir ./(el directorio donde queremos crear) el nuevo directorio.``

#### 6️⃣ find

Busca archivos que siguen un patrón

**Alguna variable:** 

> podemos buscar un archivo en concreto por su nombre `find . -name "(aquí dentro va el nombre)"` 


#### 7️⃣ clear

Simplemente limpia la consola. 

#### 8️⃣ rm

Con rm podemos borrar archivos y directorios. Los últimos si no usamos combinaciones no nos dejará borrar, pero utilizando alguno como `rm -r` podemos hacerlo
> ❌Hay que tener cuidado con `rm-r` que borrará todo sin preguntar

#### 9️⃣ rmdir

Este es el comando para remover directorios. 

#### cat