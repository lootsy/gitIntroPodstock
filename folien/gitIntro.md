# Versionskontrolle mit git

## Ultraschall etc.

<!-- .slide: data-transition="zoom" -->

---

## Versionskontrolle

- VCS (version control system) - [Versionskontrolle](https://de.wikipedia.org/wiki/Versionsverwaltung)
- Übersicht, Geschichte einzelner Änderungen  
- "rollback", Kontrolle, alles da, alles erreichbar
- wann, wer, was, warum...

---

## git

- [Git](https://de.wikipedia.org/wiki/Git) - _das_ führende (verteilte) VCS
- verteilt, offline
- Zusammenarbeit, öffentlich
- [GitHub](https://de.wikipedia.org/wiki/GitHub), [GitLab](https://de.wikipedia.org/wiki/GitLab), [BitBucket](https://de.wikipedia.org/wiki/Bitbucket)

---

## More markdown (fragments)

* static text
* fragment <!-- .element: class="fragment" -->
* fragment grow <!-- .element: class="fragment grow" -->
* fragment highlight-red <!-- .element: class="fragment highlight-red" -->
* press key down <!-- .element: class="fragment fade-up" -->

---

## More markdown (tables)

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
