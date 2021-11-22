+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Train Your Engineering Network"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = ""
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image = ""  # Name of image in `static/img/`.
  image_darken = 0.5  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "actual"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = false  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["30px", "0", "30px", "0"]



+++

### Ziel:
- Die Vortragsreihe "Train your engineering network" zu vielfältigen Themen des Machine Learnings wendet sich in erster Linie an die wissenschaftlichen Mitarbeiterinnen und Mitarbeiter der TUHH sowie allgemein in der Region Hamburg und zielt darauf ab, den Informationsaustausch zwischen diesen Personen sowie deren Vernetzung in lockerer Atmosphäre zu fördern. Dadurch sollen die Machine-Learning-Aktivitäten innerhalb der TUHH sowie in deren Umfeld sichtbarer gemacht, Kooperationen gefördert und auch interessierten Studierenden ein Einblick ermöglicht werden. Im aktuellen Wintersemester 2021/22 werden vor allem Workshops zu ML Themen von Lehrenden der TUHH Angeboten.

### Ansprechpartner: 
- Organisatoren sind Axel Friedewald, Patrick Göttsch, Mijail Guillemard, Haibo Ruan, {{% mention "vonbun_feldbauer" %}}, {{% mention "zemke" %}}.

### Ort und Zeit:
- Die Workshops/Vorträge finden aktuell im Wintersemester 2021/22 online Montag nachmittags (Startzeit je nach Ankündigung zwischen 15 und 17 Uhr) in deutscher Sprache statt.

### Inhalte und Vortragende im aktuellen Semester:

| # | Datum | Vortragende/r | Thema |
| --- | ---  | --- | --- |
| 1 | 29.11.21 | {{% mention "becker" %}} & {{% mention "babazadeh" %}} | Einsatz von KI für die Betriebsführung elektrischer Netze |
| 2 | 06.12.21 | {{% mention "meissner" %}} & {{% mention "boll" %}} | Klassifikation handgeschriebener Zahlen mit Hilfe eines mehrschichtigen neuronalen Perceptron (MLP)-Netzes und Jupyter-Notebooks |
| 3 | 13.12.21 | {{% mention "kriegesmann" %}} | Effiziente Quantifizierung von Unsicherheiten (Monte-Carlo-Simulationen) mittels Ersatzmodellen |
| - | 20.12.21 | - | Holiday |
| - | 27.12.21 | - | Holiday |
| 4 | 03.01.22 | {{% mention "schuster" %}} & {{% mention "schierholz" %}} | Einsatz und Chancen von Methoden des Maschinellen Lernens in der Elektromagnetischen Verträglichkeit |
| 5 | 10.01.22 | {{% mention "schulte" %}} | Einführung in Support Vector Machines |
| 6 | 17.01.22 | Mijail Guillemard | Grundlagen zur persistenten Homologie im maschinellen Lernen |
| 7 | 24.01.22 | {{% mention "venzke" %}} | Implementation von Neuronalen Netzen auf ressourcenbeschränkten Mikrocontrollern für den Einsatz in der Sensorik |

#### Abstracts:

<details class="description" close><summary data-close="Show" data-open="Hide"></summary>

1. {{< hl >}}{{% mention "becker" %}} & {{% mention "babazadeh" %}}: Einsatz von KI für die Betriebsführung elektrischer Netze.{{< /hl >}} <br/>
Durch die Energiewende entwickelt sich die Betriebsführung von elektrischen Netzen zu einer immer komplexeren Aufgabe, woraus sich neue Anforderungen an die Systeme zur Netzüberwachung und Netzregelung ergeben. Im Rahmen dieses Workshops werden verschiedene Anwendungsfälle aus dem Bereich der Betriebsführung von elektrischen Netzen betrachtet, für die der Einsatz von KI möglich ist. Hierbei werden sowohl die einzelnen Anwendungen in den Grundzügen erläutert, als auch die erwarteten Vorteile durch den Einsatz der verschiedenen KI-Verfahren. Zu den behandelten Themen gehören unter anderem die Modellierung und Vorhersage von Lasten im Netz, die Fehlerdetektion und Diagnose, die Zustandsschätzung sowie die Stabilitätserfassung und -beeinflussung.

2. {{< hl >}}{{% mention "meissner" %}} & {{% mention "boll" %}}: Klassifikation handgeschriebener Zahlen mit Hilfe eines mehrschichtigen neuronalen Perceptron (MLP)-Netzes und Jupyter-Notebooks.{{< /hl >}} <br/>
Ziel dieses Workshops ist ein Einblick in die Klassifikation handgeschriebener Zahlen mit Hilfe des Maschinellen Lernens zu gewähren. Nach einer kleinen Einführung in die Grundlagen über einfache neuronale Netze für diese Anwendung, Jupyter-Notebooks als Arbeitsumgebung für Python, und Keras für die Entwicklung der ANNs, wird der Workflow für eine Zeichenerkennung bearbeitet. Schlussendlich werden die trainierten Netze für die Detektion und Erkennung von handgeschriebenen Texten auf Bildern angewendet.
Für die Teilnahme an diesem Workshop sind Grundkenntnisse in Python von Vorteil und eine lokale Python-Installation von Anaconda3 wird vorausgesetzt.

3. {{< hl >}}{{% mention "kriegesmann" %}}: Effiziente Quantifizierung von Unsicherheiten (Monte-Carlo-Simulationen) mittels Ersatzmodellen.{{< /hl >}} <br/>
In vielen Ingenieuranwendungen liegen mathematische Modelle und Simulationstools vor, um für vorgegebene Eingangsgrößen relevante Zielgrößen zu ermitteln. Beispielsweise in der Strukturmechanik sind die vorgegebenen Eingangsgrößen die Geometrie und Material­parameter einer Struktur, sowie die einwirkenden Lasten. Typische Zielgrößen sind die Verformung der Struktur und die maximal auftretenden Spannungen, aus denen sich das Bauteilversagen ergibt. Tatsächlich sind die Eingangsgrößen i.d.R. nicht genau bekannt, sondern unterliegen einer stochastischen Streuung. Dementsprechend unterliegen auch die Zielgrößen einer Streuung, die sich mit probabilistischen Methoden (a.k.a. Uncertainty Quantification) bestimmen lässt. Ein weit verbreitetes, probabilistisches Verfahren ist die Monte-Carlo-Methode. Dieses sehr robuste Verfahren ist einfach zu implementieren, jedoch auch sehr rechenintensiv. Die Grundidee ist, dass die Werte der Eingangsgrößen entsprechend ihrer stochastischen Verteilung erzeugt und in das Simulationsmodell eingesetzt werden. Dies geschieht so oft, bis die Verteilung der Zielfunktion ausreichend genau bestimmt ist (z.B. bis Mittelwert und Standard­abweichung der Zielfunktion konvergieren). Das beutet, dass das Simulationsmodell sehr oft (Größenordnung 103 bis 106) ausgewertet werden muss, was bei komplexen, sehr rechenintensiven Simulationsmodellen zum Problem wird. Hier kommen Methoden des Maschinellen Lernens zum Einsatz um effiziente Ersatzmodelle (a.k.a. Surrogate Model, Meta Model) zu erzeugen. Diese Ersatzmodelle (z.B. neuronale Netze) werden zunächst trainiert und dann anstelle des eigentlichen Simulationsmodells deutlich schneller ausgewertet. Im Workshop, zeigen wir Anhand strukturmechanischer Beispiele, wie die Streuung einer Zielgröße mittels Monte-Carlo-Simulation unter Verwendung von Ersatzmodellen bestimmt werden kann.

4. {{< hl >}}{{% mention "schuster" %}} & {{% mention "schierholz" %}}: Einsatz und Chancen von Methoden des Maschinellen Lernens in der Elektromagnetischen Verträglichkeit.{{< /hl >}} <br/>
Die Elektromagnetische Verträglichkeit (EMV) befasst sich mit der Unterdrückung ungewollter elektromagnetischer Störungen zwischen elektronischen Geräten, Systemen und Komponenten. Steigende Anforderungen im Bereich der EMV – man denke z.B. an die fortschreitende drahtlose Kommunikation bei immer höheren Frequenzen – erfordern eine kontinuierliche Entwicklung der ingenieurwissenschaftlichen Methoden, um früh und kostengünstig die richtigen Entscheidungen bei der Entwicklung zu treffen. In diesem Workshop werden verschiedene Methoden des Maschinellen Lernens vorgestellt, die in den EMV-Anwendungsfeldern der Signalintegrität (signal integrity) von drahtgebundenen Kanälen sowie der Kontrolle der Spannungsversorgung (power integrity) und der Abstrahlung (electromagnetic interference) von elektronischen Komponenten und Systemen aktuell erforscht werden. Eigene Forschungen im Bereich von künstlichen Neuronalen Netzen, die zur Analyse von Leiterplattenstrukturen verwendet werden, zeigen hierbei auf, welche Chance sich für die EMV und ganz allgemein die Hardware-Entwicklung in Zukunft ergeben.

5. {{< hl >}}{{% mention "schulte" %}}: Einführung in Support Vector Machines.{{< /hl >}} <br/>
Support Vector Machines (SVM) sind ein leistungsstarkes und vielseitiges Verfahren des Maschinellen Lernens, das für viele Anwendungen eingesetzt wird. Die Grundidee von SVM ist, die zu zwei unterschiedlichen Gruppen gehörenden Daten mit einer Hyperebene zu trennen. Mit Hilfe von Transformationen in höherdimensionale Räume und der Verwendung von Kernel-Funktionen lässt sich dies auch für den Fall durchführen, dass die zugrundeliegenden Daten nicht linear getrennt werden können. Der Workshop zielt vor allem darauf ab SVM einzuführen und setzt den Schwerpunkt auf die theoretischen Grundlagen.

6. {{< hl >}}Mijail Guillemard: Grundlagen zur persistenten Homologie im maschinellen Lernen.{{< /hl >}} <br/>
Persistente Homologie ist eine neuere Entwicklung in der angewandten algebraischen Topologie, die in verschiedenen Strategien des maschinellen Lernens verwendet wurde. In diesem Vortrag präsentieren wir eine kurze Einführung in dieses Thema mit mehreren Anwendungen in der Signalverarbeitung und Datenanalyse. 

7. {{< hl >}}{{% mention "venzke" %}}: Implementation von Neuronalen Netzen auf ressourcenbeschränkten Mikrocontrollern für den Einsatz in der Sensorik.{{< /hl >}} <br/>
Der Workshop vermittelt, wie maschinelles Lernen mit künstlichen neuronalen Netzen (KNNs) in Sensormodulen mit preiswerten, leistungsschwachen Mikrocontrollern eingesetzt werden kann. Als Use-Case dient ein Sensormodul mit Lichtsensoren zur Erkennung einfacher Handgesten mit Mikrocontroller ATMega4809 (6 kB RAM, 20 MHz). Neben theoretischen Lehreinheiten enthält der Workshop viele praktische Demonstrationen zum Training und Einsatz von KNNs in den Sprachen Python (mit Keras / Tensorflow) und C (in Arduino-Entwicklungsumgebung).

</details>

### Vergangene Semester:
 * [Sommersemester 2021](/_archive/network/#sose21)
 * [Wintersemester 2020/21](/_archive/network/#wise20_21)
 * [Sommersemester 2020](/_archive/network/#sose20)
