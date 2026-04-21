# Mein Hydroponic Tagebuch

## Einführung

Tagebuch und Berichte über Hydroponic (meist mit DWC) Projekte.

## Projekte

| Projekt Nummer | Beschreibung |
| --- | --- |
| 1 | Chilis, nicht wirklich dokumentiert |
| 2 | [San Marzano Tomaten & Erdbeeren Florian F1](/Project2/project.md) |

## Tools

### ImageMagick

Bildqualität reduzieren

``` Bash
magick mogrify -resize 1920x -quality 80 -strip *
```

### EXIFTool

Metadaten von Bildern entfernen.

``` Bash
exiftool -all= -overwrite_original *
```
