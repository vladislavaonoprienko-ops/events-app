# Events – Tapahtumapalvelu

**Events** on verkkosovellus, jonka avulla käyttäjät voivat selata ja järjestää erilaisia tapahtumia (kuten harrastustapaamisia, peli-iltoja ja työpajoja) sekä ilmoittautua niihin.

* **Tekijä:** Vladyslava Onopriienko
* **Julkaistu sovellus:**
---

## Keskeiset toiminnallisuudet

* Käyttäjätilin luominen (rekisteröityminen) ja sisäänkirjautuminen.
* Tulevien tapahtumien selaaminen ja tapahtuman tarkempien tietojen katsominen.
* Tapahtumaan ilmoittautuminen ja oman ilmoittautumisen peruminen.
* Uusien tapahtumien luominen sekä omien tapahtumien muokkaaminen ja poistaminen.
* Osallistujalistan ja vapaiden paikkojen seuranta.

---

## Käytetyt teknologiat

* **Frontend:** React (käyttöliittymä ja näkymät) + komponenttikirjasto (esim. Material UI / Bootstrap)
* **Backend:** Node.js ja Express (REST API ja sovelluslogiikka)
* **Tietokanta:** MySQL (Azure Database for MySQL)
* **Autentikaatio:** JSON Web Token (JWT) ja salasanan tiivistys (bcrypt)
* **Julkaisu ja versionhallinta:** Microsoft Azure (App Service), Git ja GitHub (CI/CD)

---

## Asennus- ja käynnistysohjeet (paikallinen kehitys)

### 1. Vaaditut työkalut
* Node.js (versio 18 tai uudempi) ja npm
* Git
* MySQL-tietokanta (paikallinen MySQL tai Azure Database for MySQL)

### 2. Projektin lataaminen ja riippuvuuksien asennus
Kloonaa repositorio omalle koneelle:
```bash
git clone<oma-kayttajatunnus>/events-app.git
cd events-app# events-app
