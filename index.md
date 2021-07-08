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
  
  
 ## Erkenntnis der Umfrage
Das Monitoring der CO2 Emissionen wird auch für die Unternehmen immer wichtiger und bereits ein Viertel der Befragten monitoren schon aktiv ihren Energieverbrauch und haben sogar eine interne Aufzeichnung. Leider wurden keine genaueren Angaben angeben, wie das Monitoring durchgeführt wird. Somit gibt es offensichtlich bereits eine Auflistung der CO2 Werte für die Reduzierung und der Verkleinerung des CO2- Fußabdrucks intern, jedoch ist noch eine geringe Transparenz hinsichtlich der zur Verfügungstellung der Werte für den Endkonsumente gegeben. Außerdem hat ein Unternehmen auch angegeben, dass es interne Standards gibt, welche das Monitoring der Services vorgeben sowie eine zuständige Abteilung / Person, welche sich mit dem Thema beschäftigt. Auch die Energieeffizienz der Services liegt den Unternehmen sehr stark am Herzen, sodass bereits drei der vier Befragten zu 100 Prozent erneuerbare Energie nutzen.
  
 ## Ausgangssituation
 Das Cloud Computing nimmt immer mehr einen größeren Stellenwert ein, wird von Tag zu Tag bedeutender und ist ein sogenannter Hype in der Computerwelt, sei es die AWS Cloud, Azure Cloud oder Google Cloud usw. All diese Cloudlösungen ermöglichen es Unternehmen und auch Privatkunden ihre Daten wie z.B. in OneDrive oder Dropbox aber auch Anwendungen in das Internet auszulagern, ohne die eigenen Anwendungen und Daten physisch auf den heiminternen PCs oder Festplatten zu speichern. Das ermöglicht Unabhängigkeit, Skalierbarkeit, Flexibilität und reduziert auf lange Sicht gesehen Kosten für die Wartung und Instandhaltung der eigenen Infrastruktur. Die Konsumenten und Unternehmen profitieren von dieser Nutzung und den Möglichkeiten, allerdings hinterlässt dies enormen Schaden bei der Umwelt. Man geht davon aus, dass bis 2025 der europäische Energiebedarf von Rechenzentren allein durch das Cloud Computing auf mehr als 90 Terawattstunden pro Jahr ansteigen wird. Vergleicht man den Wert mit Werten des Energieverbrauchs von Ländern, dann wird man würde man durch den Einsatz von Cloud Computing jährlich mehr Energie als das Land Österreich im Jahr benötigt (75 Terawattstunden), verbrauchen. Grund für den enormen Energieanstieg ist einerseits die zunehmende Nutzung der Cloud Services aber auch aufgrund der Digitalisierung. Somit wäre es sinnvoll den Energiebedarf des Cloud-Computings auf energieeffiziente Methoden zu minimieren (z.B. erneuerbarer Energie) oder auch die Nutzung der Abwärme der Rechenzentren für die Einspeisung ins Fernwärmenetz, um so den Energieverbrauch nachhaltig zu gestalten und dadurch auch langfristig zu reduzieren, ohne auf die Funktionalitäten des Cloud-Computings verzichten zu müssen. Auch wäre es für die Anwender und Nutzer der Cloud Services von Vorteil, wenn diese mehr Transparenz über die Cloud Anbieter sowie Informationen über den Ausstoß an CO2-Äquivalent ihrer genutzten Cloud Services erhalten würden. Um den Anstieg des Energieverbrauchs reduzieren zu können müsste vor allem die Wirtschaft mit der Politik zusammenarbeiten, indem man auf den Einsatz energieeffizienter Technologien setzt und auch in der Forschung- und Entwicklungspolitik die richtigen Maßnahmen trifft. [Environment Agency Austria 2020]
 
 ## Standards und Regulierungen
 
  In der EU gibt es schon einige Studien und Empfehlungen zum Thema Verhaltenskodex, Cloud Strategien zu energieeffizienten Cloud-Computing-Technologien sowie sogenannte Richtlinien für Cloud Computing. Zum Thema „Energieeffiziente Cloud-Computing-Technologien und Richtlinien für einen umweltfreundlichen Cloud-Markt“ gibt es eine Studie, verfasst vom Umweltbundesamt Österreich und dem Borderstep Institute for Innovation und Sustainability, welche sich mit dem steigenden Energieverbrauch durch den Ausbau von Cloud-Diensten in Europa beschäftigt. Weiters gibt es auch schon eine europäische Digitalisierungsstrategie, die das Ziel hat, bis 2030 alle Rechenzentren klimaneutral, hochenergieeffizient und nachhaltig zu betreiben. Das Thema des Cloud-Computings wird bereits von der EU gehört und es wird auch schon an Maßnahmen gearbeitet, dass die Rechenzentren energieeffizienter werden, die Abwärme der Server wiederverwendet werden und mehr erneuerbare Energiequellen zum Einsatz für den Betrieb der Server verwendet werden. Die Ergebnisse der Studie waren unter anderem, dass der Energieverbrauch von Rechenzentren vom Jahr 2018 bis zum Jahr 2030 von rund 76,8 Terawattstunden (TWh) auf rund 98,53 Terawattstunden ansteigen wird. Das bedeutet ein Anstieg von rund 28 Prozent. Weiters wurde in der Studie darauf hingewiesen, dass aufgrund der Natur des Cloud-Computings und der zahlreichen Anbieter weltweit man vermutlich bis 2030 die gesetzten Ziele der Digitalisierungsstrategie nicht erreichen könnte. Dennoch setzt die Kommission auf bestehende Instrumente wie z.B. die europäische Digitalisierungsstrategie, die hier beschriebene Studie aber auch auf weitere Instrumente, wie z.B. den EU-Verhaltenskodex zur Energieeffizienz von Rechenzentren, die Ökodesign-Verordnung für Server und Datenspeicherprodukten, die EU-Kriterien für umweltfreundliche öffentliche Beschaffung für Rechenzentren, Serverräumen und Cloud-Diensten sowie die bundesweiten und europäischen Energieeffizienzrichtlinien. Mit Hilfe dieser Studien konnte der EU-Kommission der Ernst der Lage für energieeffizientes Cloud-Computing nähergebracht werden und vermutlich könnte man auch bereits neue Verordnungen in der neuen Energieeffizienzrichtline der EU mit Geltungsbereich 2021 bis 2030 erwarten, welche aktuell noch ausgearbeitet wird. Weitere Informationen zum [Abschlussbericht](https://ec.europa.eu/newsroom/dae/document.cfm?doc_id=71330)  der Studie findet man unter Abschlussbericht. Förderprogramme wie z.B. Horizont Europa, Programm Digitales Europa, InvestEU usw. könnten dabei behilflich sein eine innovative grüne und sichere Cloud umzusetzen und zu implementieren. [European Commission 2021]
  
  Unterhalb eine Grafik die beschreibt, wie die Entwicklung des Energieverbrauchs der Rechenzentren in der EU von 2010 bis 2030 aussehen könnte. Dabei könnte im Worst Case, falls keine Maßnahmen zur Verbesserung vorgenommen werden und die Anzahl der Rechenzentren aufgrund des Datenzuwachs steigt, der Energieverbrauch bis 2030 auf bis zu 160 TWh ansteigen und somit stark die Umwelt belasten. Würde man den Trend linear weiterlaufen lassen, dann hätte man bis 2023 einen Energieverbrauch von rund 100 TWh und falls man schon heute mit energieeffizienten Maßnahmen immer und immer mehr starten würde, dann könnte man den Energieverbrauch bis 2030 auf nahezu den Ausgangswert wie vor 10 Jahren auf rund 55 TWh reduzierten.
  
  
  
  
  
  
  #  Vorlage
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
