---
layout: page
title: "Technik"
permalink: /tech/
---

Ich interessiere mich für Technik. 

- Mit [ZNATOK](https://znatok.ru) baue ich Schaltkreise und programmiere sie mit [GraphZ](https://znatok.ru/files/arduino_mobile/Znatok-Arduino-Mobile-Graph-Z-Manual-Rus_1.pdf)
- Mit meinem Raspberry Pi 5 erkunde ich Linux 

<div style="text-align: center;">
	<img src="../assets/images/2024-10-13-technoseum-ausschnitt.jpg" alt="Bild: GraphZ-Programmierung" style="width: 75%;text-align: center;" />
</div>

<!--
![](../assets/images/2024-10-13-technoseum-ausschnitt.jpg)
-->

# Linux Terminal 

## Wie kann ich ein Verzeichnis  öffnen?

- Beim Start von einem neuem Fenster ist der Ordner `home` offen
- Wir gehen zum Beispiel in das Verzeichnis `videos`
	- Um in Das Verzeichnis `videos` zu öffnen sagen sie
	
			$> cd Videos

	- Der Computer sagt

			chiarcos_viktor@Linux-Viktor:~/Videos $>

- Sie können nun auch raus aus dem Verzeichnis mit 

		$> cd ..

- Um ein neues Verzeichnis zu öffnen machen sie genau das gleiche
- wenn sie ein weiteres Verzeichnis öffnen wollen dann sagen sie:

		$> cd videos/Ordner Name

- **Ende**

&nbsp;

## Was bedeutet der Befehl `sudo`?

- `sudo` ist ein Befehl, um Administratorrechte zu aktivieren
- `sudo` benötigst Du, um Daten im System zu verstellen
- Benutzer, die keine Administratorrechte haben, können `sudo` nicht verwenden
- Mit `sudo` kannst du: Apps installieren, Herrunterfahren, Zugrifsrechte von anderen Personen Verwenden, Benutzer Hinzufügen und vieles mehr
- Zum Beispiel:
    chiarcos_viktor@Linux-Viktor:~ $ sudo adduser neue-person-1


&nbsp;

# Wie kann ich einen Benutzer Hinzufügen?
- Wenn du einen Benutzer Hinzufügen willst soltest du dir einen Nutzernamen überlegen
- Dannach gibst du den Befehl ein:
    chiarcos_viktor@Linux-Viktor:~ $ adduser neue-person-1
- adduser gibt eine Rückmeldung:
    adduser: Nur root darf Benutzer oder Gruppen zum System hinzufügen.
- Wir haben gelernt wofür man sudo braucht.
- bevor sie adduser schreiben setzen sie sudo.
- nächster versuch:
    chiarcos_viktor@Linux-Viktor:~ $ sudo adduser neue_person_eins
- Also es geht:
    Lege Benutzer »neue_person_eins« an ...
Lege neue Gruppe »neue_person_eins« (1003) an ...
Lege neuen Benutzer »neue_person_eins« (1003) mit Gruppe »neue_person_eins« (1003) an ...
Erstelle Home-Verzeichnis »/home/neue_person_eins« ...
Kopiere Dateien aus »/etc/skel« ...
Geben Sie ein neues Passwort ein:
- Zu ihrer Sicherheit Wird die Passworteingabe nicht angezeigt
- Wenn sie das Passwort eingegeben haben kommt diese Rückmeldung:
     Vollständiger Name []:
    	Zimmernummer []:
      Telefon geschäftlich []:
      Telefon privat []:
      Sonstiges []: 
- Dannach fragt er mich ob die Info korrekt ist:
     Sind die Informationen korrekt? [J/n]
- Wenn Ja dann Drücken sie ENTER
- Wenn Nein dann schreiben sie n

  ***ENDE*** 


&nbsp;

## ZNATOK

- Meine [GraphZ](https://znatok.ru/link/?start-graphz))-Schaltkreise auf [GitHub](https://github.com/viktor-chiarcos/GraphZ)
- Check out my [ZNATOK programming shows](https://www.youtube.com/playlist?list=PLSWV8OnoemY7cPA46sp0pD5PcdmatZXrN)

<!-- mit automatischer skalierung -->
<div style="text-align: center;">
	<img src="../assets/images/2024-11-23-graphz.jpg" alt="Bild: GraphZ-Programmierung" style="width: 60%;text-align: center;" />
</div>

<!--
![](../assets/images/2024-11-23-graphz.jpg)
-->

<!-- 
![](../assets/images/2024-11-23-wir-lernen-git.jpg)
-->
