# Green Cloud Frameworks and Standardisation Efforts

Bestrebungen zur energieeffizienten Nutzung von IT sind in einigen Bereichen bereits seit Jahren erfolgreich – etwa bei der Vergleichbarkeit der Energieeffizienz von CPUs, Speichersystemen, Server-Computern, PCs oder Notebook-Computern, Bildschirmen u.ä. Im stark wachsenden Cloud-Umfeld gibt es bisher kaum Möglichkeiten für die NutzerInnen von Cloudservices, die für einen Cloudservice benötigte Energiemenge zu ermitteln. Viele Cloud Provider beschreiben zwar ihre allgemeinen Bestrebungen zur Umsetzung von CO2-neutralen Rechenzentren und Services, welchen „ökologischen Fußabdruck“ oder Ausstoß an „CO2-Äquivalent“ dabei allerdings die Nutzung eines bestimmten Cloud Services mit sich bringt, wird bisher kaum angegeben. Für höhere Transparenz bei der Energieeffizienz sind Standardisierungen und eventuell auch zwingende gesetzliche Regelungen erforderlich. Diese Arbeit soll eine Einführung in das Problem der Transparenz von Energieeffizienz bei Cloudservices geben. Der aktuelle Stand soll übersichtlich dargestellt werden: Gibt es schon praxistaugliche technische Standards? Sind taugliche gesetzliche Regelungen verfügbar oder absehbar, um Cloud-Provider zu mehr Transparenz zu bringen?

## Einführung

Im Rahmen der Lehrveranstaltung "Selected Topics in Network Technologies" an der Fachhochschule JOANNEUM in Graz, führten die beiden Studenten Florian Gartner, BSc und Marcel Kahr, BSc eine Umfrage zum Thema "Green Cloud Frameworks und Standardisierungsbemühungen" durch.
In der Umfrage ging es um das Thema Transparenz der Energieeffizienz bei Cloud-Diensten (VM's) sowie um den "ökologischen Fußabdruck" / "Kohlenstoff-Emissionen", der durch die Nutzung bestimmter Cloud-Dienste entsteht. 
Für die kurze fünfminütige Umfrage wurde mit weltweitbekannten Cloudprovidern und auch kleineren regionalen Cloudprovidern Kontakt aufgenommen und um die Teilnahme bei der Umfrage gebeten. Die Umfrage wurde in diesem Zusammenhang in englischer Sprache verfasst, da es sich um ein globales Thema handelt und um somit eine Vielzahl an Teilnehmer anzusprechen.
Die gesamte Umfrage wurde anonym durchgeführt und alle Daten wurden vertraulich behandelt. Die Daten wurden nicht an Dritte weitergegeben und nur in zusammengefasster Form in einer GitHub Page veröffentlicht.

## Auswertung

### Frage 1
Bei der ersten Frage, wie wichtig es den Unternehmen ist, Cloud Services in einer energieeffizienten Form zur Verfügung zu stellen, haben die beteiligten Unternehmen von einer Skala von 1 bis 100 Prozent folgendermaßen geantwortet. Zwei Teilnehmer haben bei der Wichtigkeit rund 75 Prozent angegeben, ein Teilnehmer nur rund 10 Prozent und ein weiterer Teilnehmer rund 85 Prozent. Das ergibt einen Mittelwert von rund 61,25 Prozent. Somit ist zu sagen, dass die Wichtigkeit von energieeffizienten Cloud Services bereits einen sehr hohen Stellenwert hat und auch in Zukunft zunehmen wird.

![image](/diagrams/question1.png)
 
 ### Frage 2
 Bei drei der vier beteiligten Unternehmen gibt es kein Monitoring der CO2 Emissionen.
 ![image](/diagrams/question2.png)
 ### Frage 3
 Bei den beteiligten Unternehmen führen drei der vier Unternehmen keine Aufzeichnung ihrer CO2 Bilanzen.
 ![image](/diagrams/question3.png)
 ### Frage 4
 Auf die Frage, ob die Unternehmen interne Regulierungen oder Standards haben, die verpflichtend sind für das Monitoring der C02 Äquivalenz der Services, haben drei der Beteiligten mit nein geantwortet und ein Beteiligter keine Angabe gemacht. Somit ist ersichtlich, dass die Unternehmen zurzeit keine vordefinierten Standards verfolgen hinsichtlich des Monitorings des CO2 Äquivalenz. Falls doch Aufzeichnungen vorgenommen werden, wie bereits bei der vorherigen Frage beantwortet, basiert diese Aufzeichnung auf freiwilliger Basis.
![image](/diagrams/question4.png)
 ### Frage 5
 Bei der Frage, ob es für den Endkonsumenten möglich ist, ihren CO2-Verbrauch, den sie bei der Verwendung von Cloud Services erzeugen einzusehen, gaben alle Unternehmen an, dies nicht zu unterstützen.
![image](/diagrams/question5.png)
 ### Frage 6
 Bei der Frage, wie die Unternehmen ihre CO2 Emissionen monitoren, hat die Hälfte angegeben, dass sie kein Monitoring durchführen und die andere Hälfte gab an, dass sie ihre Services monitoren aber wie genau das Monitoring durchgeführt wird, wurde leider nicht angegeben.
 ![image](/diagrams/question6.png)
 ### Frage 7
 Bei der Frage, ob es eine verantwortliche Person / Abteilung im Unternehmen gibt, welche sich mit dem Thema Green Cloud beschäftigt, gab es unterschiedliche Rückmeldungen. Zwei Teilnehmer haben angegeben, dass es keine verantwortlichen Personen im Unternehmen gibt, ein Teilnehmer hat keine Angaben gemacht und ein Teilnehmer hat angegeben, dass es Verantwortlichkeiten im Unternehmen gibt. 
 ![image](/diagrams/question7.png)
 ### Frage 8
 Bei der Frage, wie viel Prozent der benötigten/eingesetzten Energie für den Betrieb der Cloud Services aus erneuerbarer Energie kommt, haben drei der vier Beteiligten mit 100 Prozent geantwortet und ein Teilnehmer mit rund 83 Prozent.
  ![image](/diagrams/question8.png)
 ### Frage 9
 Von vier Beteiligten haben zwei Unternehmen kein Ranking in Bezug auf den Energieverbrauch von ihren Services, bei einem Unternehmen ist solch ein Ranking nicht bekannt und nur bei einem Unternehmen gibt es ein Ranking ihrer Services. 
  ![image](/diagrams/question9.png)
 ### Frage 10
 Weiters haben zwei Teilnehmer auch ein Ranking ihrer Cloud Services mit dem höchsten Energieverbrauch angegeben. Dazu nachfolgend eine Auflistung der energiereichsten Services in den Unternehmen:
1.	metal as a service
2.	gpu as a service
3.	database as a service
4.	machine learning service
5.	virtual machine cluster service
6.	virtual machines service
7.	container as a service
8.	volume storage
9.	object storage
10.	other services (DNS, Networking)

Das andere Unternehmen hat angegeben, dass sie mehr Energie bei den Backup Services verbrauchen als für andere Services im Unternehmen, aufgrund der hohen Anzahl an spinning disks (HDD’s).

Da uns vor alle der Begriff Metal as a Service aufgefallen ist und wir keinen Bezug dahingehend hatten, möchten wir kurz nachfolgend auf den Begriff Metal as a Service eingehen:

 ## Metal as a Service /Metal (Bare-Metals) as a Service
 ### Bedeutung:
 Hierbei geht es um die Vermietung von Bare-Metals (echter physische Hardware) von Dienstleiter, anstatt diese selbst zu kaufen. Bei Metal-as-a-Service (MAAS) geht es einfach ausgedrückt darum, dass Unternehmen hunderte bis sogar tausende Server auf Basis echter Hardware im eigenen Rechenzentrum betreiben können. Über den Dienst kann auf der Hardware im eigenen Netzwerk eine private Cloud auf Basis echter Server erstellt werden. Über diesen Weg lassen sich Betriebssysteme, wie z.B. „Ubuntu“, „CentOS“, „Windows“ und „Red Hat Linux Enterprise“ (RHEL) installieren - mit mehreren Images.
 
**Beispiel:** Ein Server im Netzwerk wird mit dem OS Ubuntu betrieben. Auf diesem Server wird die MAAS-Software für das Rechenzentrum installiert. Dieser Server steuert die private Hardware-Cloud im eigenen Rechenzentrum und verfügt über die notwendigen Ressourcen und Images. Die Verwaltung erfolgt über eine Web-Oberfläche. Mit dem Dienst im lokalen Rechenzentrum lassen sich alle anderen hardwarebasierten Server im Netzwerk installieren. [Joos & Ostler]
  
You can use the [editor on GitHub](https://github.com/kahrmarc17/Green-Cloud-Frameworks-and-Standardisation-Efforts-/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kahrmarc17/Green-Cloud-Frameworks-and-Standardisation-Efforts-/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
