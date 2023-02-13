# Unsere Website

## Verwendete HTML Tags:

### `<!DOCTYPE HTML>`:

### `<meta charset="UTF-8">`:

### ` <title/>`:

### `<link>`:

### `<a/>`:

### `<img>`:

### `<iframe/>`:

Ein iframe oder auch Inlineframe wird verwendet, um andere HTML-Elemente in einem definierten Bereich einzubinden.

## Verwendetes CSS:

### Positionierung
- `margin`: Der Abstand um ein Element.
- `padding`: Der Abstand des Inhalts eines Elements zur Außenwand des Elements.
- `position`: Die CSS-Positionierungsfunktion, die verwendet wird, um die Elemente im Elternelement

### Font Konfiguration
- `font-family`: Die Schriftart, die wir für die Seite verwenden.
- `font-size`: Die größe der Schrift auf der Seite.
- `text-decoration`: Formatierungsanweisung für Texte (Unterstrichen, Fett, usw.)

### Farben
- `color`: Die Farbe des Elements.
- `background-color`: Die Hintergrundfarbe hinter einem Element.

> ## Klassen:
> Klassen sind Möglichkeiten Elementen Attributen zuzuweisen, ohne diese Attribute typabhängig zu machen. Sie können
> beliebig kombiniert werden. Man kann Klassen definieren, indem man in einem Stylesheet `.klassemmame {}` schreibt. In
> den geschweiften Klammern werden, wie in normalem CSS auch, die Attribute für die Elemente angegeben. Verwenden tut
> man eine Klasse, indem man einem HTML-Tag das `class`-Attribut hinzufügt: `<p class="klassenname"/>`. Es können auch
> mehrere Klassen auf einen HTML-Tag angewendet werden, indem man ihren Namen in dem `class`-Attribut mit Leerzeichen
> trennt: `<p class="klassenname1 klassenname2 klassenname3"/>`.

> ## Zustände:
> Einige HTML-Elemente haben verschiedene Zustände. So zum Beispiel Links. Ein Link hat die
> Zustände `link`, `visited`, `hover` und `active` haben.
>
> `link`: `link` ist der Grundzustand eines Links. \
> `hover`: Ein Link hat den Zustand hover, wenn sich ein Maus-Cursor darüber befindet. \
> `visited`: Sobald ein Link bereits geklickt wurde, hat er den Zustand `visited`.

> ## Relative Breiten- und Höhenangaben
> Außer den bereits bekannten absoluten Höhenangaben und den prozentualen Angaben gibt es noch `vw` und `vh`.
> `vw` steht für "viewport-width" (dt. Fensterbreite) und gibt die Breite des Inhaltsbereiches in Prozent an.
> Demnach sind 100vw die gesamte Bildschirmbreite.
> `vh` steht für "viewport-height" (dt. Fensterhöhe) und gibt die höhe des Inhaltsbereiches an.
> Auch hier werden die Werte wieder relativ angegeben.
>
> Wenn der Inhalt einer HTML-Datei in einem `iframe` angezeigt wird, beziehen sich `vw` und `vh` auf die Breite und Höhe
> des frames.
> Das ist relevant für unsere Kopf- und Fußzeile.