# Versionskontrolle mit git

## Ultraschall

<!-- .slide: data-transition="zoom" -->

---

## Versionskontrolle

- VCS (version control system) - [Versionskontrolle](https://de.wikipedia.org/wiki/Versionsverwaltung)
- Übersicht, Geschichte einzelner Änderungen  
- "rollback", Kontrolle, alles da, alles erreichbar
- wann, wer, was, warum...
- "TimeMachine" für txt

---

## git

- [Git](https://de.wikipedia.org/wiki/Git) - _das_ führende (verteilte) VCS
- verteilt, offline
- Zusammenarbeit, öffentlich
- Anbieter / Plattformen: [GitHub](https://de.wikipedia.org/wiki/GitHub), [GitLab](https://de.wikipedia.org/wiki/GitLab), [BitBucket](https://de.wikipedia.org/wiki/Bitbucket)

---

## git - Stärken & Schwächen

- Stärken
  - reiner Text, txt
  - jegliche Details
- Schwächen
  - binäre Dateien
  - große / riesige Dateien

- ABER: git ist in Entwicklung

---

## Tipps

- merge often, merge early
- Hilfen
  - [_Das_ Buch "Pro Git"](https://git-scm.com/book/en/v2)
  - gitready.com
  - [offizielle Webseite](https://git-scm.com/)
****

|h1|h2|h3|
|-|-|-|
|a|b|c|

****

---

## More markdown (code)

```
version: '2'
services:
  slides:
    image: msoedov/hacker-slides

    ports:
      - 8080:8080
    volumes:
      - ./slides:/app/slides
    restart: always

    environment:
     - USER=bob
     - PASSWORD=pa55

```

---

## Local images

![demoPicture](/images/demo.png)

Copy images into slides/images/ & include with MD:

```
![demoPicture](/images/demo.png)

```
or HTML:

```
<img src="/images/demo.png">

```

---

## Learn more

- [RevealJS Demo/Manual](http://lab.hakim.se/reveal-js)
- [RevealJS Project/README](https://github.com/hakimel/reveal.js)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
