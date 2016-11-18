<!-- .slide: data-state="c-slide-inter" -->

# HTML

>>>
* První, co si prohlížeč stahuje, je HTML soubor, který obsahuje informace o stránce.
* Je to textový soubor, takže ho můžete upravovat v jakémkoli textovém editoru jako je Poznámkový blok (Notepad) apod., my samozřejmě budeme používat Thimble

---

# Značkovací jazyk

>>>
* Značkovací, protože význam a strukturu dokumentu popisuje pomocí značek, anglicky tagů.

---

# Tag
```html
<jmenotagu>
	Obsah tagu
</jmenotagu>
```
<!-- .element: class="c-text-xl stretch" -->

>>>
* Tag se skládá ze špičatých závorek, názvu tagu mezi nimi.
* Uzavírací tag má pak ještě za první závorkou lomítko.
* Mezi tagy je jeho obsah, tedy to co obaluje. To může být obyčejný text nebo další tag nebo tagy. 

---

## Základní struktura HTML

```html
<!DOCTYPE HTML>
<html>
    <head>
        <!-- vlastnosti stránky -->
    </head>
    <body>
        <!-- samotný obsah stránky -->
    </body>
</html>
```
<!-- .element: class="c-text-md stretch" -->

>>>
* HTML dokument má mít tuto strukturu.
* Úplně první je tzv. doctype. Říká prohlížeči jaké HTML má čekat. Není potřeba se jím nyní zabývat, jen ho tam vždy mějte.
* Všechno ostatní je obaleno tagem `<html>`.
* V hlavičce (`<head>`) jsou definovány vlastnosti pro celou stránku. Většinou „nejsou vidět“.
* V těle stránky (`<body>`) je vlastní text stránky, obrázky atd. Většinou „je vidět“.
* Všimněte si komentářů.

---

<!-- .slide: data-background="img/keyboard-cs-html.svg" -->

>>>
* Protože je pro psaní HTML potřeba některé méně časté znaky, máte na stole pomůcku pro nalezení znaků.
* Kouzelná je klávesa AltGr s kterou napíšete většinu znaků.
* Někdo může mít trochu jiné rozložení.


---

<!-- .slide: data-state="c-slide-task" -->

# Úkol

* Otevři si adresu <a href="http://tiny.cc/tvorim01" target="_blank">tiny.cc/tvorim01</a>
* Vpravo nahoře klikni na „Upravit“.
* Vytvoř hlavní nadpis (název webu)

---

<!-- .slide: data-state="c-slide-break" -->

# Přestávka do 10:15