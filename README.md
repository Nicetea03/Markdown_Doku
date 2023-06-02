# Markdown_Doku

# Markdown-Dokumentation

 Markdown ist eine einfache Markup-Sprache, mit der Text schnell und einfach formatiert werden kann. In diesem Dokument werden  verschiedene Markdown-Elemente und deren Verwendung vorgezeigt.

## Inhaltsverzeichnis

1. [Überschriften](#überschriften)
2. [Trennstriche](#trennstriche)
3. [Hervorgehobene Wörter](#hervorgehobene-wörter)
4. [Aufzählungen](#aufzählungen)
5. [Links](#links)
6. [Quellcode](#quellcode)
7. [Tabellen](#tabellen)
8. [Bilder](#bilder)
9. [Blockzitate](#blockzitate)
10. [Fußnoten](#fußnoten)
11. [Task-Listen](#task-listen)
12. [Durchgestrichene Absätze](#durchgestrichene-absätze)
13. [Text-Highlighting](#text-highlighting)
14. [Hoch- und tiefgestellte Zeichen](#hoch-und-tiefgestellte-zeichen)
15. [Deaktivierte URL-Verknüpfungen](#deaktivierte-url-verknüpfungen)

## Überschriften

In Markdown kann man Überschriften mit unterschiedlichen Ebenen erstellen. Eine Hauptüberschrift wird mit einem oder mehreren Hash-Zeichen (#) gefolgt von einem Leerzeichen eingeleitet. Hier ist ein Beispiel:

```
# Hauptüberschrift
```

Unterüberschriften werden mit mehreren Hash-Zeichen eingeleitet. Je mehr Hash-Zeichen verwendet werden, desto niedriger ist die Ebene der Überschrift. Hier ist ein Beispiel für eine Unterüberschrift:

```
## Unterüberschrift
```

## Trennstriche

Man kann Trennstriche verwenden, um Abschnitte zu trennen. Verwendet man drei oder mehr Bindestriche (-), erzeugt man einen horinzontalen Trennstrich. Hier ist ein Beispiel:

---
Trennstrich

---

## Hervorgehobene Wörter

In Markdown kann man Wörter hervorheben, indem man sie kursiv oder fett formatiert. Ein Wort kann kursiv formatiert werden, indem es von einem oder zwei Sternchen (*) oder Unterstrichen (_) umgeben wird. Hier sind Beispiele für kursiv formatierte Wörter:

*kursiv* oder _kursiv_

Ein Wort kann fett formatiert werden, indem es von zwei oder drei Sternchen (*) oder Unterstrichen (_) umgeben wird. Hier sind Beispiele für fett formatierte Wörter:

**fett** oder __fett__

## Aufzählungen

Man kann Aufzählungen erstellen, indem man Listen mit Punkten oder Zahlen verwendet. Man benutzt einen Bindestrich (-) oder ein Pluszeichen (+) für ungeordnete Listen. Hier ist ein Beispiel:

- Erster Punkt
- Zweiter Punkt
- Dritter Punkt

Für geordnete Listen verwendet man Zahlen. Hier ist ein Beispiel:

1. Erster Punkt
2. Zweiter Punkt
3. Dritter Punkt

Man kann auch

 verschachtelte Aufzählungen erstellen, indem man Leerzeichen vor den Punkten hinzufügt. Hier ist ein Beispiel für eine verschachtelte Liste:

- Erster Punkt
  - Unterpunkt 1
  - Unterpunkt 2
- Zweiter Punkt

## Links

In Markdown kann man Links erstellen, indem man den Link-Text in eckige Klammern [] platziert und den Link dahinter in runden Klammern () angibt. Hier ist ein Beispiel:

[GitHub](https://github.com/)

## Quellcode

Man kann Quellcode in Markdown mit oder ohne Syntax-Hervorhebung angeben. Um eine Code-Zeile einzufügen,umgibt man sie mit Backticks (`). Hier ist ein Beispiel:

`print("Hello, World!")`

Um mehrere Code-Zeilen einzufügen, können Sie drei Backticks verwenden. Sie können auch eine Sprache nach den ersten drei Backticks angeben, um die Syntaxhervorhebung zu aktivieren. Hier ist ein Beispiel:

```python
def greet():
    print("Hello, World!")
```

## Tabellen

Man kann mit Markdown auch Tabellen erstellen. Man kann die Ausrichtung des Texts in den Tabellenzellen festlegen. Hier ist ein Beispiel für eine Tabelle:

| Name  | Alter | Stadt    |
|-------|-------|----------|
| Alice | 25    | New York |
| Bob   | 30    | London   |

Man kann die Ausrichtung des Texts in den Tabellenzellen festlegen, indem man Doppelpunkte (:) in der Trennzeile verwendet. Hier ist ein Beispiel:

| Name      | Alter | Stadt    |
|:---------:|:-----:|:--------:|
| Alice     | 25    | New York |
| Bob       | 30    | London   |

## Bilder

In Markdown kann man Bilder einfügen, indem man den Bild-URL in eckige Klammern [] platziert und optional einen Alternativtext in Anführungszeichen angibt. Hier ist ein Beispiel:

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

## Blockzitate

Man kann Blockzitate erstellen, indem man den Text mit einem Größer-als-Zeichen (>) einrückt. Hier ist ein Beispiel:

> Dies ist ein Blockzitat.
> Es erstreckt sich über mehrere Zeilen.

## Fußnoten

Fußnoten können in Markdown mit eckigen Klammern [] und einem Karat (^) erstellt werden. Die Fußnoten selbst werden am Ende des Dokuments definiert. Hier ist ein Beispiel:

Eine Fußnote[^1].

[^1]: Dies ist der Inhalt der Fußnote.

## Task-Listen

Man kann Listen erstellen, indem man Listenpunkten eckige Klammern [] und Leerzeichen voranstellt. Hier ist ein Beispiel:

- [x] Aufgabe erledigt
- [ ] Aufgabe nicht erledigt

## Durchgestrichene Absätze

Man kann Absätze in Markdown durchstreichen, indem man sie mit Tilden (~) umgibt. Hier ist ein Beispiel:

~~Dieser Absatz ist durchgestrichen.~~

## Text-Highlighting

Man kann Text in Markdown hervorheben, indem man ihn mit Doppel-Tilden (~~) umgeben. Hier ist ein Beispiel:

==Dieser Text ist hervorgehoben.==

## Hoch- und tiefgestellte Zeichen



Man kann Zeichen in Markdown hoch- oder tiefstellen, indem man sie mit Hoch- (^) oder Tiefstrich (_) umgibt. Hier ist ein Beispiel:

Hochgestellt: X^2^
Tiefgestellt: H~2~O

## Deaktivierte URL-Verknüpfungen

Um eine URL in Markdown zu deaktivieren, kann man vor die URL ein Ausrufezeichen (!) setzen. Dadurch wird die URL nicht als Verknüpfung angezeigt. Hier ist ein Beispiel:

!http://example.com


