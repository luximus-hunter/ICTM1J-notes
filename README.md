# Notities voor klas ICTM1J

## Home

Om te beginnen ga je naar de [HOME](HOME.md). Je hoeft daarna niet meer terug naar dit bestand.

## Installatie

### Git

Installeer [Git](https://git-scm.com/). Loop de installatie door zoals je zelf wilt. Zorg wel dat je "Git van de command-line" aanvinkt.

### Downloaden

Om te downloaden, open de plek waar je de map wilt opslaan in de command-line. Als de map op het bureaublad moet komen, open dan het bureaublad in de command-line. Voer daarna `git clone https://github.com/luximus-hunter/ICTM1J-notes.git`. Dit zal de map `ICTM1J-notes` maken op de plek die je hebt geopend.

### Obsidian

Voor de beste leeservaring kun je het beste [Obsidian](https://obsidian.md/) installeren en deze repository daarin open. Je kunt de folder die je hebt gedownload openen als een `Vault`. Zet daarna de preview mode aan om de markdown te converteren naar leesbare tekst.

### Obsidian extensions

- [Obsidian Git](https://github.com/denolehov/obsidian-git). Hiermee kun je instellen dat je bij het openen van Obsidian alle veranderingen download van GitHub.
- [Admonition](https://github.com/valentine195/obsidian-admonition). Hiermee worden informatie en waarschuwings blokken goed weergegeven.

```ad-bug
title: Test
Als dit wordt weegeven als een `Test`, dan werkt de Admonition extensie.
```

### Pull foutmelding

Als je de [Obsidian Git](#Obsidian%20extensions) hebt geïnstalleerd en deze geeft een foutmelding bij het opstarten, dan kun je het volgende doen. Sluit Obsidian en open [de folder waar de notities staan](#Downloaden) opnieuw in de command-line. Daar kun je de volgende commando's uitvoeren. Je kunt ook het [force-pull](force-pull.ps1) script uitvoeren. Daarna kun je Obsidiaan weer openen.

```cmd
git reset --hard
git clean -fd
git pull
```
