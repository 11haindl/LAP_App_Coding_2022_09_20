# Fachgespräch

Bei meiner LAP wurden mir folgende Fragen gestellt:

## Datenbanken

- Welche Arten von Datenbanken kennen Sie?
- Worin unterscheiden sich relationale Datenbanken von NoSQL-Datenbanken
- Welche SQL-Operationen kennen Sie?
- Welche Möglichkeit haben sie Daten aus mehreren Tabellen abzufragen?
- Welche Arten von JOINS kennen Sie?
- Wie können Sie die Schnelligkeit von Datenbankabfragen beeinflussen?

## Programmieren

Auf der Tafel steht Pseudo-Code:

### Beispiel 1

```
a = 4
b = 3
c = 5

if(a < 2){
    print("z")
}else if (b > 3 and a < 5){
    print("y")
}else if (c < 3 or a > 2){
    print("x")
}else{
    print("v")
}
```

- Welche Datentypen haben die Variablen im Programmcode
- Erklären Sie was im Programmcode passiert. 
- Was wird ausgegeben und warum?
- Welchen Datentyp hätte ```"x"``` wenn man es in eine Variable speichern möchte?


### Beispiel 2

```
array[] = []
m = 1
for(i = 0, i < 3, i++){
  array[m] = i
  print(array[m])
  m++
}
```

- Was passiert hier?
- Was wird ausgegeben?
- Was muss verändert werden, damit das Array an erster Stelle einen Wert bekommt?

### Beispiel 3

```
i = 3
m = 1
for(i = 0, i < 100, i++){
  print(m)
  m++
}
```

- Wie oft wird die Schleife durchlaufen?
- Was wird ausgegeben?


## Datenschutz/DSGVO

### Szenario des Prüfers
Sie arbeiten ja mit medizinischen Daten. 
Ich rufe Sie an und gebe Ihnen meine Sozialversicherungsnummer und möchte Auskünfte zu meinen Laborauswertungen haben. 
Bekomme ich diese Informationen von Ihnen? Wie reagieren Sie?

### Szenario2 des Prüfers
Es wird in Ihrem Betrieb einen Betriebsausflug geben. Ich bin das Busunternehmen. Ich rufe Sie an und bitte Sie mir die Reisepassdaten der Mitarbeiter zu geben.
Bekomme ich diese? Welches Gesetz liegt hier zugrunde?

## IT-Sicherheit
- Wie erkennen Sie beim Aufruf einer Website, ob diese sicher ist?
- Sie rufen eine Website auf und sehen https und ein Schloss als Sicherheitsmerkmal, trotzdem wird Ihnen im Browser angezeigt, dass diese Seite nicht sicher ist. Wie kann das sein?
- Was ist der Unterschied, wenn ein Zertifikat von einer Zertifizierungsstelle ausgestellt wird im Gegensatz zu eine self-signed Zertifikat?
- Was ist eine Man-in-the-Middle-Attack? Wie können sie Ihre Datenbank vor einer solchen Man-in-the-Middle-Attack schützen?


