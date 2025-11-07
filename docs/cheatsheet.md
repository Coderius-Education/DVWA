---
sidebar_position: 1
displayed_sidebar: null
---

# Cheatsheet

## WSL

<details>
    <summary>Hoe start ik WSL op?</summary>

Open `Windows Powershell` en voer het volgende commando uit:
```powershell
wsl -d kali-linux
```
</details>

## DVWA

<details>
    <summary>Hoe start ik DVWA?</summary>

Open kali-linux in WSL en kopieer het volgende commando:

```bash
sudo systemctl start apache2.service
```

Ga vervolgens naar een browser (bijvoorbeeld Google Chrome) en ga naar de volgende url:

```
http://localhost/DVWA
```

</details>

<details>
    <summary>Hoe log ik in op DVWA?</summary>

De gebruikersnaam is `admin` en het wachtwoord is `password`.
</details>

<details>
    <summary>Wat stel ik nog in na de installatie?</summary>

Nog twee dingen:
1. Klik in het scherm `Setup / Reset DB` op de knop `Create / Reset database` onderaan de pagina.
2. Klik in het menu op `DVWA Security` en kies daar `low` en klik op `Submit`.

</details>
