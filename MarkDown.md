## H3 Versionhallinta

## z)Lue ja tiivistä

[https://commonmark.org/help/](https://commonmark.org/help/)

- Kappaleiden väliin aina tyhjä rivi

- `_kursivoitu_` tulee _kursivoitu_ teksti

- `**lihavoitu**` tulee **lihavoitu** teksti

- `# Otsikko tai ## Otsikko` tulee otsikko

- Linkki tehdään `[Link](url)`

- Kuva lisätään `![Image](url)`

- Lista tehdään - merkillä

## a)Tee raportti MarkDown:na

Se on tässä :-)

## b)First Pull

Muokkaa kahta tiedostoa MarkDown.md ja README.md ja ajan komennot

- git add --all
- git commit
- git pull
- git push

![Image](pics/kuva1024.png)

Ja tarkistin GiTHub:sta että kaikki muutokset tulivat voimaan

## b)Kaikki kirjataan

`git log --pretty=oneline` komento näyttää kaikki commit käskyt ja niiden SHA avaimen

[Yllä oleva tieto löydetty](https://git-scm.com/docs/git-log)

![Image](pics/kuva1026.png)

`git blame MarkDown.md`komento näyttää kirjaimellisesti kenen vika (blame) tai ansioita täällä tehdyt asiat ovat

![Image](pics/kuva1028.png)

`git diff`komento näyttää viime commit käskyn jälkeen tehdyt muutokset, mutta en saa sillä mitään tulostetta aikaiseksi vaikka sitä missä kohtaa vaan yritän antaa?

## c)Huppis!

Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset ‘git reset --hard’. Huomaa, että tässä toiminnossa ei ole peruutusnappia.


