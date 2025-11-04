---
sidebar_position: 2
sidebar_label: 'Medium'
doc_id: dvwa_tutorial/command_injection/medium
---

# Medium
De aanvaller heeft ons door. We kunnen niet meer `&&` of `;` gebruiken, omdat deze tekens nu uit de invoer worden gefilterd.

## De opdracht
Start `DVWA` en ga naar de challenge `Command Injection`. Zorg dat je `DVWA Security` op `medium` hebt staan.
Ben je vergeten hoe dit moest? Ga dan naar de [cheatsheet](../../docs/cheatsheet).


Wat zouden we tussen het IP-adres en ons commando kunnen zetten, zodat het eerste commando wordt uitgevoerd en Linux daarna doorgaat met het volgende?

Het resultaat van een succesvolle poging zie je hieronder:

![succes](medium_succes.png)

## De walkthrough

<iframe width="920" height="517" src="https://www.youtube.com/embed/WiqRvlN_UIU?start=456" title="2 - Command Injection (low/med/high) - Damn Vulnerable Web Application (DVWA)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>