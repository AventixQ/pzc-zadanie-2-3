Przed uruchomieniem skryptów, upewnij się, że masz zainstalowane:
* **Docker**
* **`pack-cli`**

## Budowanie obrazu za pomocą `pack`

`pack build java-app --builder heroku/builder:22`

## Uruchamianie Dockera

`docker run -p 8080:5000 java-app`