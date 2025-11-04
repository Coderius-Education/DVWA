---
sidebar_position: 1
sidebar_label: 'Low'
doc_id: dvwa_tutorial/command_injection/low
---

# Low
Voor `Command Injection` is het belangrijk dat we ons eerst verdiepen in `ping`.
Bekijk onderstaande video om een idee te krijgen van wat dit commando doet:


<iframe width="920" height="517" src="https://www.youtube.com/embed/xIT0yrYsyWY" title="The ping command in 60 seconds or less" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## De opdracht
Start `DVWA` en ga naar de challenge `Command Injection`. Zorg dat je `DVWA Security` òp `low` hebt staan.
Ben je vergeten hoe dit moest? Ga dan naar de [cheatsheet](../../docs/cheatsheet).


1. Begin met het invullen van een IP adres in het formulier en bekijk de output (bijvoorbeeld `127.0.0.1`)
2. Bedenk hoe je twee Linux commando's op 1 regel kan laten uitvoeren
3. Bedenk nu een "IP adres" waardoor het ping commando nog steeds lukt, maar ook een tweede linux commando wordt uitgevoerd (bijvoorbeeld `ls`)

Het resultaat van een succesvolle poging zie je hieronder:

![succes](succes.png)

## De walkthrough

<iframe width="920" height="517" src="https://www.youtube.com/embed/WiqRvlN_UIU?start=9" title="2 - Command Injection (low/med/high) - Damn Vulnerable Web Application (DVWA)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>