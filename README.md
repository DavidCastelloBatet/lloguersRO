# RO Challenge: Lloguer d'eines entre particulars

- cases
- cotxe / moto
- eines
- bàsicament objectes

## Tips principals:

- Establir les necesitats tecnològiques
  - Quines tecnologies (HTML5, CSS3, PHP, JS)
  - 1 Idioma
- Requisits mínims PMV
- Diagrama de flux
- Establir les pantalles
- Programar HTML / Bàsics CSS

## Establir les necessitats tecnològiques

- Les tecnologies pel front seran HTML5, CSS3 i JS
- Les tecnologies pel back seran PHP i MySql
- S'establirà com a idioma principal de la pàgina, el català

## Requisits mínims PMV

### A nivell de plataforma

- Monetització:

  - La plataforma inserirà publicitat i programes d'afiliats
  - % de l'operació

- Gestió d'usuaris posen a lloguer / lloguen
- Gestió d'articles a lloguer (alta / baixa)

### A nivell d'usuari que posa l'article a lloguer

- La persona que vol posar a lloguer haurà d'establir:
  - Registre / Login
  - Objecte a llogar:
    - Preu 
    - Temps del lloguer
    - Com i on s'entrega / recull l'eina

### A nivell d'usuari que lloga l'article

- Buscador d'articles
- Selecció de l'article
- Lloc d'enviament (retorn de l'eina), que coincidirà amb l'adreça de l'emisor


## Pantalles

### Estructura pàgina index
<img width="1035" alt="pagina inicial" src="https://user-images.githubusercontent.com/56063955/154659261-7fb22918-4e65-4e6b-b8ef-33cc8864a78e.png">

### Estructura pàgines eines per llogar / necessito una eina
<img width="1031" alt="Captura de pantalla 2022-02-18 a les 10 54 08" src="https://user-images.githubusercontent.com/56063955/154659660-70eaaaca-b46c-4dbc-a648-9e2250859b03.png">
A part del text explicatiu, et convida a loguejarte / registrarte

### Pantalla d'introduccio de mail / contrasenya
<img width="1031" alt="Captura de pantalla 2022-02-18 a les 11 33 04" src="https://user-images.githubusercontent.com/56063955/154666309-5eb53e72-b004-4f0a-b114-417220fd83fd.png">

Internament, es fa la comprobacio si l'usuari ja existeix:
  - si no existeix, apareix pantalla de registre completa
    Camps bàsics
    - nom de l'usuari
    - dni usuari
    - carrer
    - codi postal
    - població
    - telefon
    
  - si existeix, vas a la fitxa completa d'usuari

<img width="1042" alt="Captura de pantalla 2022-02-18 a les 12 01 02" src="https://user-images.githubusercontent.com/56063955/154670477-0dd815a8-3ffa-4d06-a967-0ad2b21a4cd1.png">

  - Des de l'apartat Dades personals pots editar la fitxa d'usuari
  - Des de l'apartat Articles per llogar (forma de llistat) pots donar d'alta, editar (alta i editar - pop-up amb formulari) i donar de baixa (boto i solicitud de confirmació)els articlies que vulguis llogar
     - Les dades bàsiques necessaries son:
        - id: assignat automaticament (us intern)
        - eina disponible (us intern)
        - Nom de l'article
        - Tipus d'eina
        - Preu / Temps disponible
        - Descripció
        - Fotografia





