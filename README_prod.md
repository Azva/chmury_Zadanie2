*(Pliki Dockerfile - bez zmian)*

Zbudowanie obrazów
```
docker build -t mskrz/zadanie2:z2_nginx ./nginx/
docker push mskrz/zadanie2:z2_nginx
```
```
docker build -t mskrz/zadanie2:z2_client ./client/
docker push mskrz/zadanie2:z2_client
```
```
docker build -t mskrz/zadanie2:z2_server ./server/
docker push mskrz/zadanie2:z2_server
```
```
docker build -t mskrz/zadanie2:z2_worker ./worker/
docker push mskrz/zadanie2:z2_worker
```

Stworzenie kontenerów (zmienne zadeklarowane w pliku .env)
```docker compose up```

