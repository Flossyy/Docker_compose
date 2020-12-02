# Docker_compose
Stworzony projekt składa się z serwerów: **php**, **Apache** i **Mysql**.
#### Projekt jest tworzony przez uruchomienie **docker-compose.yml** za pomocą komendy
    sudo docker-compose build
#### Zestaw serwerów uruchamiamy poleceniem
    sudo docker-compose up
#### Po uruchomieniu możemy sprawdzić działanie prostego skryptu w pliku index.php za pomocą komendy
    curl localhost:6666
Nie byłem w stanie sprawdzić widoku strony w przeglądarce i wynika to prawdopodobnie z tego, że port jest w jakiś sposób przez nią wykorzystywany.
#### Komenda aby wyświetlić zawartość pliku html
    curl localhost:6666/index.html
#### Reprezentacja graficzna
![Reprezentacja graficzna](https://github.com/Flossyy/Docker_compose/blob/main/docker-compose.png?raw=true)