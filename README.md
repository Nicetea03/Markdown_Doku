# Markdown_Doku

# Markdown-Dokumentation

Willkommen zur Markdown-Dokumentation! Hier lernen Sie alles über die verschiedenen Funktionen und Syntax-Elemente von Markdown. Markdown ist eine einfache Markup-Sprache, mit der Sie Text schnell und einfach formatieren können. In diesem Dokument werden wir verschiedene Markdown-Elemente und deren Verwendung besprechen.

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

In Markdown können Sie Überschriften mit unterschiedlichen Ebenen erstellen. Eine Hauptüberschrift wird mit einem oder mehreren Hash-Zeichen (#) gefolgt von einem Leerzeichen eingeleitet. Hier ist ein Beispiel:

```
# Hauptüberschrift
```

Unterüberschriften werden mit mehreren Hash-Zeichen eingeleitet. Je mehr Hash-Zeichen verwendet werden, desto niedriger ist die Ebene der Überschrift. Hier ist ein Beispiel für eine Unterüberschrift:

```
## Unterüberschrift
```

## Trennstriche

Sie können Trennstriche verwenden, um Abschnitte zu trennen. Verwenden Sie drei oder mehr Bindestriche (-), um einen horizontalen Trennstrich zu erzeugen. Hier ist ein Beispiel:

---
Trennstrich

---

## Hervorgehobene Wörter

In Markdown können Sie Wörter hervorheben, indem Sie sie kursiv oder fett formatieren. Ein Wort kann kursiv formatiert werden, indem es von einem oder zwei Sternchen (*) oder Unterstrichen (_) umgeben wird. Hier sind Beispiele für kursiv formatierte Wörter:

*kursiv* oder _kursiv_

Ein Wort kann fett formatiert werden, indem es von zwei oder drei Sternchen (*) oder Unterstrichen (_) umgeben wird. Hier sind Beispiele für fett formatierte Wörter:

**fett** oder __fett__

## Aufzählungen

Sie können Aufzählungen erstellen, indem Sie Listen mit Punkten oder Zahlen verwenden. Verwenden Sie einen Bindestrich (-) oder ein Pluszeichen (+) für ungeordnete Listen. Hier ist ein Beispiel:

- Erster Punkt
- Zweiter Punkt
- Dritter Punkt

Verwenden Sie Zahlen für geordnete Listen. Hier ist ein Beispiel:

1. Erster Punkt
2. Zweiter Punkt
3. Dritter Punkt

Sie können auch

 verschachtelte Aufzählungen erstellen, indem Sie Leerzeichen vor den Punkten hinzufügen. Hier ist ein Beispiel für eine verschachtelte Liste:

- Erster Punkt
  - Unterpunkt 1
  - Unterpunkt 2
- Zweiter Punkt

## Links

In Markdown können Sie Links erstellen, indem Sie den Link-Text in eckige Klammern [] platzieren und den Link dahinter in runden Klammern () angeben. Hier ist ein Beispiel:

[GitHub](https://github.com/)

## Quellcode

Sie können Quellcode in Markdown mit oder ohne Syntax-Hervorhebung angeben. Um eine Code-Zeile einzufügen, umgeben Sie sie mit Backticks (`). Hier ist ein Beispiel:

`print("Hello, World!")`

Um mehrere Code-Zeilen einzufügen, können Sie drei Backticks verwenden. Sie können auch eine Sprache nach den ersten drei Backticks angeben, um die Syntaxhervorhebung zu aktivieren. Hier ist ein Beispiel:

```python
def greet():
    print("Hello, World!")
```

## Tabellen

Markdown ermöglicht die Erstellung von Tabellen. Sie können die Ausrichtung des Texts in den Tabellenzellen festlegen. Hier ist ein Beispiel für eine Tabelle:

| Name  | Alter | Stadt    |
|-------|-------|----------|
| Alice | 25    | New York |
| Bob   | 30    | London   |

Sie können die Ausrichtung des Texts in den Tabellenzellen festlegen, indem Sie Doppelpunkte (:) in der Trennzeile verwenden. Hier ist ein Beispiel:

| Name      | Alter | Stadt    |
|:---------:|:-----:|:--------:|
| Alice     | 25    | New York |
| Bob       | 30    | London   |

## Bilder

In Markdown können Sie Bilder einfügen, indem Sie den Bild-URL in eckige Klammern [] platzieren und optional einen Alternativtext in Anführungszeichen angeben. Hier ist ein Beispiel:

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

## Blockzitate

Sie können Blockzitate erstellen, indem Sie den Text mit einem Größer-als-Zeichen (>) einrücken. Hier ist ein Beispiel:

> Dies ist ein Blockzitat.
> Es erstreckt sich über mehrere Zeilen.

## Fußnoten

Fußnoten können in Markdown mit eckigen Klammern [] und einem Karat (^) erstellt werden. Die Fußnoten selbst werden am Ende des Dokuments definiert. Hier ist ein Beispiel:

Eine Fußnote[^1].

[^1]: Dies ist der Inhalt der Fußnote.

## Task-Listen

Sie können Aufgabenlisten erstellen, indem Sie Listenpunkten eckige Klammern [] und Leerzeichen voranstellen. Hier ist ein Beispiel:

- [x] Aufgabe erledigt
- [ ] Aufgabe nicht erledigt

## Durchgestrichene Absätze

Sie können Absätze in Markdown durchstreichen, indem Sie sie mit Tilden (~) umgeben. Hier ist ein Beispiel:

~~Dieser Absatz ist durchgestrichen.~~

## Text-Highlighting

Sie können Text in Markdown hervorheben, indem Sie ihn mit Doppel-Tilden (~~) umgeben. Hier ist ein Beispiel:

==Dieser Text ist hervorgehoben.==

## Hoch- und tiefgestellte Zeichen



Sie können Zeichen in Markdown hoch- oder tiefstellen, indem Sie sie mit Hoch- (^) oder Tiefstrich (_) umgeben. Hier ist ein Beispiel:

Hochgestellt: X^2^
Tiefgestellt: H~2~O

## Deaktivierte URL-Verknüpfungen

Um eine URL in Markdown zu deaktivieren, können Sie vor die URL ein Ausrufezeichen (!) setzen. Dadurch wird die URL nicht als Verknüpfung angezeigt. Hier ist ein Beispiel:

!http://example.com

Das war eine umfassende Einführung in die verschiedenen Funktionen von Markdown. Sie sollten nun mit den grundlegenden Elementen und der Syntax vertraut sein und Ihre eigenen Markdown-Dokumente erstellen können. Viel Spaß beim Formatieren von Texten mit Markdown!
