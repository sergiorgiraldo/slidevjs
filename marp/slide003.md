---
marp: true
theme: default
footer: "Sergio Giraldo - Utrecht - 2025"

---

# COVER default theme

**I went to the woods because I wished to live deliberately, to front only the essential facts of life, and see if I could not learn what it had to teach**

---

<!-- paginate: true -->

# How to

1. Write a markdown (.md) file with the front-matter `marp: true`
2. Each slide is separated by ---
3. Export to PDF: `Marp: Export Slide Deck`
4. Project: https://marp.app/
5. Syntax: https://marpit.marp.app/
6. VSCode extension: https://github.com/marp-team/marp-vscode

---

# This is the first slide

Quo usque tandem abutere, Catilina, patientia nostra? Lorem ipsum dolor sit amet, consectetur adipisici elit, sed eiusmod tempor incidunt ut labore et dolore magna aliqua. Cras mattis iudicium purus sit amet fermentum.

---

# This is the second slide

Pellentesque habitant morbi tristique senectus et netus. Lorem ipsum dolor sit amet, consectetur adipisici elit, sed eiusmod tempor incidunt ut labore et dolore magna aliqua. Phasellus laoreet lorem vel dolor tempus vehicula.

---

<!-- _backgroundColor: orange -->
<!-- _color: white -->

# This is the third slide

* one
* two
* three

---

<!-- _footer: you can override with the _ in the directive. Only in this slide -->

# This is the fourth slide

Lorem ipsum dolor sit amet, consectetur adipisici elit, sed eiusmod tempor incidunt ut labore et dolore magna aliqua. Paullum deliquit, ponderibus modulisque suis ratio utitur. Cras mattis iudicium purus sit amet fermentum.

---

# Image 1

\!\[w:300px](https://placehold.co/300) 

![w:300px](https://placehold.co/300) 

---

# Image 2

\!\[w:400px h:150px](https://placehold.co/400x150) 

![w:400px h:150px](https://placehold.co/400x150)

---

# Image 3

\!\[w:600px h:50px blur:10px](https://placehold.co/400x150) 

![w:600px h:50px blur:2px](https://placehold.co/600x50)

filters: blur:10px/ brightness:1.5/ contrast:200%/ drop-shadow:0,5px,10px,rgba(0,0,0,.4)/ grayscale:1/ hue-rotate:180deg/ invert:100%/ opacity:.5/ saturate:2.0/ sepia:1.0

---

![bg](https://picsum.photos/500)

# Background slide 1

Gallia est omnis divisa in partes tres, quarum. Lorem ipsum for photos: `https://picsum.photos/`

---

![bg left](https://picsum.photos/id/29/720)

# Background slide 2

The space of a slide content will shrink to the right side.

---

![bg left:33%](https://picsum.photos/id/25/720)

# Background slide 3

Split backgrounds with specified size

---

# CSS customization

<style scoped>
section {
  background: yellow;
  color: green;
  font-family: Courier;
  font-size: xx-large;
}
</style>

This is a yellow slide with green big courier text.

* **the css element is always `section`**

* **notice the `scoped` keyword. it means this is applied to this slide; without it, it is a global style.**
