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
- Die Vortragsreihe "Train your engineering network" zu vielfältigen Themen des Machine Learnings wendet sich in erster Linie an die wissenschaftlichen Mitarbeiterinnen und Mitarbeiter der TUHH sowie allgemein in der Region Hamburg und zielt darauf ab, den Informationsaustausch zwischen diesen Personen sowie deren Vernetzung in lockerer Atmosphäre zu fördern. Dadurch sollen die Machine-Learning-Aktivitäten innerhalb der TUHH sowie in deren Umfeld sichtbarer gemacht, Kooperationen gefördert und auch interessierten Studierenden ein Einblick ermöglicht werden. 

### Ansprechpartner: 
- Organisatoren sind Axel Friedewald, Mijail Guillemard, Haibo Ruan, {{% mention "vonbun_feldbauer" %}}, {{% mention "zemke" %}}.
- Ansprechpartner für Professorinnen und Professoren, die beitragen wollen, sind {{% mention "leborne" %}} und [Marc-André Pick](https://www.tuhh.de/mum/mitarbeiter/oberingenieur/marc-andre-pick.html).

### Ort und Zeit:
- Die Vorträge finden aktuell im Wintersemester 2020 online montags ab 17:00 und je nach Ankündigung (siehe Vortragstitel) in deutscher oder englischer Sprache statt.

### Inhalte und Vortragende im aktuellen Semester:
[Vergangene Semester](/_archive/lehre/#network_ss20)



| # | Datum | Vortragende/r | Thema |
| --- | ---  | --- | --- |
| 1 | 16.11.20 | Lennart Bargsten | Deep learning approaches for intravascular ultrasound image processing: dealing with data scarcity |
| 2 | 23.11.20 | {{% mention "schierholz" %}} | Data Sources for Machine Learning Applications in Engineering |
| 3 | 30.11.20 | {{% mention "kastner" %}} | How to Talk About Machine Learning with Jupyter Notebooks |
| 4 | 07.12.20 | Thomas Kohlsche | Data-driven construction of fast predictors for complex systems using Gaussian process regression techniques |
| 5 | 14.12.20 | {{% mention "boll" %}} | Data-driven construction of fast predictors for complex systems using Gaussian process regression techniques |
| - | 21.12.20 | - | Winter break |
| - | 28.12.20 | - | Winter break |
| 6 | 04.01.21 | Lars Köttner, Jan Mehnen, Denys Romaneko | Prozessüberwachung mit maschinellem Lernen für semi-automatisches Bohren von Nietlöchern in der Luftfahrtindustrie |
| 7 | 11.01.21 | {{% mention "feiler" %}}| Exploring Chemical Space using Computational Techniques |
| 8 | 18.01.21 | {{% mention "angerbauer" %}} | Exploring Chemical Space using Computational Techniques |
| 9 | 25.01.21 | Pascal Gleske, Konrad Nölle, Hendrik Sieck ([HULKS](/lehre/#hulks)) | Distributed Genetic Neural Network Architecture Search at HULKs |

### Abstracts:

<details class="description" close><summary data-close="Show" data-open="Hide"></summary>

1. {{< hl >}}Lennart Bargsten: Deep learning approaches for intravascular ultrasound image processing: dealing with data scarcity.{{< /hl >}} <br/>
Intravascular ultrasound (IVUS) plays a major role in clinical practice when it comes to assessing vessel morphologies during percutaneous coronary interventions (PCIs) or for treatment planning. Usually, the physician estimates morphological features by marking important regions in multiple IVUS images. This is a rather time consuming task and the results depend heavily on the physician's experience. Automated detection and segmentation of meaningful image content can thus help streamlining the clinical workflow. Data driven methods like deep learning have gained huge importance in the field of medical image analysis over the last years. The usual scarcity of annotated image data in the medical field makes it important to tailor deep learning methods with respect to specific tasks and imaging modalities. Possibilities are generating synthetic image data, considering specific image characteristics as well as performing multi-task learning. This talk presents such approaches for improving deep learning performance on IVUS image analysis. 

2. {{< hl >}}{{% mention "schierholz" %}}: Data Sources for Machine Learning Applications in Engineering.{{< /hl >}} <br/>
Investigating the possibility of machine learning tools and techniques in the domain of engineering is a widely found concept with an increased number of authors and increasing audience. This development in the machine learning community has been led by researchers from data science. However this development has been possible due to large amount of data that has been available to these researchers in combination with an increased number of computational resources. For example the object recognition on images or in speech would not have been progressed as quickly without the widely available images over the internet. 
Generating and sharing knowledge is a broadly established concept in engineering domain, in form of conferences or other publications. However it is observed that in the domain of data the sharing of those is not established. First data sources are available where data is shared, however larger projects are not observed. We therefore propose a new database to share data and knowledge of this data. Thereby enabling researches that do not have the possibility to create those data samples by themselves, to work with interesting and rich data and apply new tools and techniques of the machine learning domain or others. 
Besides the data that is available in the database and the investigated machine learning tools and techniques on this data, a general overview of the database is given. 

3. {{< hl >}}{{% mention "kastner" %}}: How to Talk About Machine Learning with Jupyter Notebooks.{{< /hl >}} <br/>
In the field of Machine Learning, scientists often use programming for data preprocessing, running the learning algorithms, and obtaining key metrics. To increase transparency, nowadays more and more additional material (such as datasets, code, documentation etc.) is shared so that fellow researchers can replicate these experiments. Jupyter Notebooks are a very valuable medium in this context – they are capable of displaying documentation, code, its output (such as visualizations, tables or logging messages) etc. side by side. 
Recently, Jupyter Notebooks have also been used in university courses more often. Here, the students benefit from the integration of code, its documentation, and the related exercise questions into a single interactive document. There are plenty of options how to design very appealing exercises for a course. 
Both in the scenario of transparent science and when using Jupyter Notebooks for teaching, the author’s code is meant to be run at another machine and achieve the same results. During this talk, possible issues during replication and suitable fixes are highlighted. The open source application JupyterHub can be part of that strategy. While the backend of the Integrated Development Environment runs on TUHH resources, the frontend is just a simple browser application. This reliefs the students from having up-to-date equipment for replication. Especially in times of COVID-19 this allows students to program from home. 

4. {{< hl >}}Thomas Kohlsche: Data-driven construction of fast predictors for complex systems using Gaussian process regression techniques.{{< /hl >}} <br/>
In many real life applications, engineers are often interested in accessible predictions of a complex systems behavior for which only sparse data is available. The data may arise either from measurements or numerical simulations. Especially for numerical design tasks like optimization and uncertainty quantification where a very large number of model evaluations is required, cheap predictors, often called meta- or surrogate models, are unavoidable. Since gathering data from such systems is typically very costly, this task requires machine learning techniques that are capable of operating on small data sets.
For the problem described, Gaussian process regression has proved itself to be a powerful and flexible tool. New extensions of the technique to, e.g., data-fusion concepts can offer solutions to problems that are hard to tackle with other techniques. 

5. {{< hl >}}{{% mention "boll" %}}: Weakbond Detection -- Enhancing Vibro-Acoustic Modulation Analysis by Machine Learning.{{< /hl >}} <br/>
N/A

6. {{< hl >}}Lars Köttner, Jan Mehnen, Denys Romaneko: Prozessüberwachung mit maschinellem Lernen für semi-automatisches Bohren von Nietlöchern in der Luftfahrtindustrie.{{< /hl >}} <br/>
Die meisten der mehreren hundert Millionen gebohrten Flugzeugnietbohrungen pro Jahr werden mit semi-automatischen und manuell gesteuerten, pneumatisch angetriebenen Maschinen hergestellt, da eine Vollautomatisierung aufgrund von Arbeitsraumbeschränkungen oft ungeeignet ist. Diese Maschinen sind im Hinblick auf die Anpassbarkeit der Bohrungsparameter unflexibel, was u.a. auf die hohen Qualitätsanforderungen der Luftfahrtbranche zurückzuführen ist. Um zuverlässige und sichere Nietverbindungen herzustellen, ist das Bohren in mehreren Prozessschritten, der Einsatz von Minimalmengenschmierung sowie anschließendes manuelles Entgraten und Reinigen der Bohrungen unabdingbar. Vor diesem Hintergrund ermöglichen neu entwickelte elektrisch angetriebene semi-automatische Advanced Drilling Units (ADUs) neue Potenziale, wie z.B. intelligente Prozesslayouts, eine Online-Zustandsüberwachung durch die Auswertung integrierter Sensordaten und eine automatische Anpassung der Prozessparameter. 
Für die Zustandsüberwachung des Bohrprozesses wurde der Einsatz von maschinellem Lernen (ML) überprüft, um Schnittkräfte und Prozessbedingungen auf der Grundlage der Ströme der verwendeten Elektromotoren der ADUs vorherzusagen. Die Anwendung von ML auf ADU- Daten ist vorteilhaft, da die hohe Anzahl zu fertigender Nietbohrungen große Datensätze liefert. ML-Methoden wie lineare Regression, künstliche neuronale Netze, Entscheidungsbäume und k-Nearest-Neighbor wurden hinsichtlich ihrer Anwendbarkeit bewertet. Bohrprozesseigenschaften wie Material- und Vorschubgeschwindigkeitsauswahl wurden mit den Modellvorhersagen verglichen. Die vorgestellten Ergebnissen zeigen, dass eine ML-basierte Prozessüberwachung das Potenzial besitzt Prozessabweichungen zuverlässig zu identifizieren und auf diese Weise manuelle Nacharbeit zu reduzieren, eine umfassende Qualitätssicherung zu gewährleisten und die Ausnutzung der Werkzeugstandzeiten zu erhöhen. 

7. {{< hl >}}{{% mention "feiler" %}}: Exploring Chemical Space using Computational Techniques.{{< /hl >}} <br/>
The degradation behaviour of magnesium (Mg) renders it one of the most versatile engineering materials available today as it can be employed in a large variety of applications ranging from automotive and aerospace components to battery applications where Mg is used as anode material. However, a prerequisite to unlock the full potential of Mg–based materials is gaining control over the corrosion rate. Consequently, bespoke additives must be identified for each application for an optimal performance. Corrosion prevention is essential in transport applications to avoid material failure whereas constant dissolution of the material is required to boost the efficiency of Mg-air primary batteries. Furthermore, the search for benign and efficient corrosion inhibitors has become critical due to the imminent ban of highly effective but toxic chromates. The vast number of small molecules with potentially useful dissolution modulating properties (inhibitors or accelerators) renders conventional experimental discovery methods too time- and resource-consuming. Consequently, computer-assisted selection prior to experimental investigations of the most promising candidates is of great benefit in the search for efficient corrosion modulating additives for Mg-based materials. One of the major challenges is the identification of sound molecular descriptors that correlate well with experimentally derived properties as input parameters with low or no relevance to the modelled property will degrade the model. Towards this end, we utilized colour-coded correlation maps to facilitate an intuitive screening for reliable input features. We recently illustrated the potential of complementary quantum chemical density functional theory (DFT) calculations and machine learning methods for the prediction of corrosion modulating properties of small organic molecules for commercially pure Mg (CP Mg). Furthermore, we developed a workflow that facilitates screening of a large commercial database for an unbiased selection of untested additives for the control of the degradation rate of Mg.  


8. {{< hl >}}{{% mention "angerbauer" %}}: Anwendung von Methoden des Maschinellen Lernens zur Darstellung komplexer Strömungsfelder. {{< /hl >}} <br/>
tba

9. {{< hl >}}Pascal Gleske, Konrad Nölle, Hendrik Sieck ([HULKS](/lehre/#hulks)): Distributed Genetic Neural Network Architecture Search at HULKs.{{< /hl >}} <br/>
The increasing application of artificial neural networks (ANN) in various domains of robotics demands highly optimized ANN architectures. The efficient architecture search requires horizontal and vertical scaling of ANN evaluation. In this talk the HULKs present their approach and application of a scalable genetic algorithm based on distributed task execution, to be used in the context of RoboCup soccer competitions. 





</details>


