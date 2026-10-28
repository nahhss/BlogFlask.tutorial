# Diagrama de Components

Descriure tots els components de l'aplicació

Components: db, _init_ ,  auth , blog

## db
Desripció: funcions d'accés  a BBDD
Metodes:
- get(): Retorna  connexió :  Mètode que retorna  la connexió a BBDD

- close_(): Tanca la connexió  a BBDD

- init_db() : Inicialitza la base de dades 

- init_db_command() : Crea una comanda per inicialitzar la base de dades

- init_app(): Inicialitza el component de la base de dades dins de l'aplicació

## _init_
Descripció: inicialització de l'aplicació
Metodes:
- create_app():  Crea i configura l'aplicació

- hello(): Retorna un missatge de benvinguda

## auth
Descripció:gestió de l'autenticació dels usuaris
Metodes:
- login_required(): Comprova si l'usuari ha iniciat sessió

- load_logged_in_user(): Carrega les dades de l'usuari que ha iniciat sessió

- register() : Permet registrar un usuari nou

- login(): Permet iniciar sessió

- logout(): Tanca la sessió de l'usuari

## blog
Descripció: gestió de les publicacions del blog
Mètodes:
- index(): Mostra les publicacions del blog

- create(): Permet crear una publicació nova

- update(): Permet modificar una publicació

- delete(): Permet eliminar una publicació

- get_post(): Busca una publicació a la base de dades

