---
sidebar_position: 2
sidebar_label: 'Medium'
doc_id: dvwa_tutorial/authorization_bypass/medium
---

# Medium
Start `DVWA` en ga naar de challenge `Authorization bypass`. Zorg dat je `DVWA Security` op `medium` hebt staan.
Ben je vergeten hoe dit moet? Ga dan naar de [cheatsheet](../../docs/cheatsheet).

Laten we eerst `Network Tools` in je browser eens wat beter bekijken:

<iframe width="920" height="517" src="https://www.youtube.com/embed/e1gAyQuIFQo" title="Inspect Network Activity - Chrome DevTools 101" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Het probleem snappen
- Log op DVWA in met gebruikersnaam `gordonb` en wachtwoord `abc123`
- Ga in je browser naar `http://localhost/DVWA/vulnerabilities/authbypass/`
- Welke foutmelding zie je bij `Network activity` (zie video hierboven)?

## Burpsuite
- Download [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)
- Open het programma `Burp Suite Community Edition`

## De opdracht
- Ga in de Burp Suite browser naar `http://localhost/DVWA/vulnerabilities/authbypass/`

Volg onderstaande tutorial:
<iframe width="813" height="457" src="https://www.youtube.com/embed/Nr2fYpStshA" title="Intercept HTTP traffic with Burp Proxy" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## De walkthrough
<iframe width="920" height="517" src="https://www.youtube.com/embed/Qcgu34eWQa4?start=313" title="15 - Authorisation Bypass (low/med/high) - Damn Vulnerable Web Application (DVWA)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>