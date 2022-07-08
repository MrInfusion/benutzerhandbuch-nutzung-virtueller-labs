## Benutzerhandbuch für Virtuelle Labs 

Dies ist das offizielle Benutzerhandbuch für das erstellen und importieren von virtuellen EVE-NG Labs. Außerdem wird hier erklärt, wie man einen Penetrationstest anhand eines Beispiel mit Metasploit durchführt.

### Vorbereitungen treffen

Auf dem Pentesting Computer läuft die Linux Distribution Kali Linux. Über den Browser navigiert man auf die EVE-NG Instanz. Folgende Daten sind wichtig für die weitere Nutzung:

**EVE-NG Zugangsinformationen:**
* IP-Adresse: 10.0.0.200
* Eingabe mittels https://10.0.0.200
* Nutzername: admin
* Passwort: eve

**Pentesting Computer Zugangsinformationen:**
* Nutzername: pentester
* Passwort: hacking

Außerdem sollte eine Netzwerkverbindung bestehen. Eine Netzwerkkonfiguration bekommt man für gewöhnlich über den Router mittels DHCP. Sollte das nicht funktionieren, fragen Sie den Netzwerkadministrator, oder vergeben Sie eine statische IP-Adresse!

### Die EVE-NG Benutzeroberfläche

Die EVE-NG Benutzeroberfläche besteht im wesentlichen sehr schlicht und simpel aufgebaut. Auf der unteren Leiste, sieht man gängige Operationen für die virtuellen Labs. Es können virtuelle Labs erstellt, importiert und gelöscht werden. Zudem kann man auch die Ansicht Aktualisieren.

![Eve-NG Übersicht](benutzerhandbuch-nutzung-virtueller-labs/eve-ng-overview.png)

### Was es sonst noch zu beachten gibt

Damit mehrere gleichzeitig mit eigenen Labs oder auch gemeinsam an einem Lab arbeiten können, muss ein neuer Nutzer angelegt werden. Dazu geht man in dem Bereich *Management > Usermanagement* und legt dort entsprechend einen neuen Nutzer an

![Nutzer anlegen](benutzerhandbuch-nutzung-virtueller-labs/create-user.png)

Erforderliche Daten:
* User Name
* Password
* Password Confirmation
* POD 

### Starterkit - Beispiel fürs Hacken von Diensten und Computern

Im folgenden Szenario wird ein Beispiel gezeigt, wie man virtuelle Labs für Penetrationstests nutzen kann. Hier wird ein fertiges bereits erstelles Lab genutzt um den Einstieg dementsprechend zu vereinfachen. Natürlich kann man auch für später ein eigenes Lab erstellen. Das ist ja nämlich der Sinn des ganzen.

#### Fertiges vLab benutzen

1. Virtuelles Lab importieren

Dazu geht man unter das Symbol *Hochladen* was für Importieren steht. Danach öffnet sich ein Dialogfenster mit der Aufforderung eine Datei auszuwählen. Eine ZIP-Datei:

![Lab importieren](benutzerhandbuch-nutzung-virtueller-labs/lab-import.png)

2. ZIP Datei upload durchführen

Dann ist noch ein Upload Schritt notwendig, der die Datei in den Transit befördert :) Dazu geht man oben rechts auf Upload:

![Lab upload](benutzerhandbuch-nutzung-virtueller-labs/lab-upload.png)

3. Öffnen das Labs

Mit einem Klick auf das vLab erscheint ein Informationsfenster. Unter den Metadaten steht dann *Open*. Nach einem Klick gelangt man in das virtuelle Labor:


![Lab upload](benutzerhandbuch-nutzung-virtueller-labs/lab-open.png)

#### Übersicht des Pentesting Szenarios

Im folgenden sieht man das Pentesting Szenario, welches bereits vorbereitet wurde. Darin erkennt man eine Cisco ASA Firewall, einen Cisco Switch, eine Kali Linux Maschine und ein anfälliges Gerät mit Schwachstellen. Dieser anfällige Computer ist ein Metasploitable. Das ist perfekt für das Kennenlernen von Hackingabläufen. Vor allem für Einsteiger:

![Lab upload](benutzerhandbuch-nutzung-virtueller-labs/lab-overview.png)




```markdown
Syntax highlighted code block

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/MrInfusion/benutzerhandbuch-nutzung-virtueller-labs/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
