+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

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
- Die Vortragsreihe "Train your engineering network" zu vielfältigen Themen des Machine Learnings wendet sich in erster Linie an die wissenschaftlichen Mitarbeiter*innen der TUHH und zielt darauf ab, den Informationsaustausch zwischen diesen Personen sowie deren Vernetzung in lockerer Atmosphäre zu födern. Dadurch sollen die Machine-Learning-Aktivitäten innerhalb der TUHH sichtbarer gemacht, Kooperationen gefördert und auch interessierten Student*innen ein Einblick ermöglicht werden. 

### Ansprechpartner: 
- Organisatoren sind Axel Friedewald, Mijail Guillemard, Haibo Ruan, {{% mention "vonbun_feldbauer" %}}, {{% mention "zemke" %}}.

### Ort und Zeit:
- Die Vorträge finden aktuell im Sommersemester Montags vorerst online ab 17:30 und je nach Ankündigung in deutscher oder englischer Sprache statt.

### Inhalte und Vortragende:


| # | Datum | Vortragende/r | Thema |
| --- | ---  | --- | --- |
| 1 | 20.04.20 |{{% mention "dostal" %}} | Towards Reinforcement Learning-based Control of an Energy Harvesting Pendulum |
| 2 | 27.04.20 | {{% mention "dostal" %}} | Advances in the development of car simulation models for vibration load prediction using Machine Learning |
| 3 | 04.05.20 | {{% mention "grossert" %}} | A Hybrid Approach for Modeling of Multibody Systems with Nonlinear Force Elements |
| 4 | 11.05.20 | Daniel Schoepflin | Bilddatengenerierung als Trainingsdatensatz für eine KI-Objektidentifikation in der Intralogistik |
| 5 | 18.05.20 | Prof. tbd | tbd |
| 6 | 25.05.20 | Kai Sellschopp, {{% mention "wuerger" %}}| Exploration of structure - property relationships with unsupervised ML |
| - | 01.06.20 | - | Pfingsten Holiday |
| 7 | 08.06.20 | {{% mention "kellner" %}}, Merten Stender | Explainable AI and its application to ice mechanics |
| 8 | 15.06.20 | {{% mention "bahnsen" %}}| Emulation von neuronalen Netzen unter Hardwarefehlern |
| 9 | 22.06.20 | Prof. tbd | tbd |
| 10 | 29.06.20 | Julias Harms | tbd |
| 11 | 06.07.20 | {{% mention "lindner_s" %}} | Predictive medium access techniques for wireless networks |
| 12 | 13.07.20 | Maximilian Stark | End-to-end learning in Wireless Communications |
| 13 | 20.07.20 | Ruediger Schmitz | tbd |
| 14 | 27.07.20 | {{% mention "jahn" %}} | ML-supported Problem Descriptions in Digital Assistance Systems |


### Abstracts:

<details class="description" close><summary data-close="Show" data-open="Hide"></summary>

1. {{< hl >}}{{% mention "dostal" %}}: Towards Reinforcement Learning-based Control of an Energy Harvesting Pendulum.{{< /hl >}} <br/>
Harvesting energy from the environment, e. g. ocean waves, is a key capability for the long-term operation of remote electronic systems where standard energy supply is not available. Rotating pendulums can be used as energy converters when excited close to their eigenfrequency. However, to ensure robust operation of the harvester, the energy of the dynamic system has to be controlled. In this study, we deploy a lightweight reinforcement learning algorithm to drive the energy of an Acrobot pendulum towards a desired value. We analyze the algorithm in an extensive series of simulations. Moreover, we explore the real world application of our energy-based reinforcement learning algorithm using a computationally constrained hardware setup based on low-cost components, such
as the Raspberry Pi platform.

2. {{< hl >}}{{% mention "dostal" %}}: Advances in the development of car simulation models for vibration load prediction using Machine Learning.{{< /hl >}} <br/>
Nowadays electric cars are a focus area in automotive research. In this context we consider data based approache as tools to improve and facilitate the car design process. Hereby, we address the challenge of vibration load prediction for electric cars using neural network based machine learning (ML), a data-based frequency response function approach, and a hybrid combined model. We extensively study the challenging case of vibration load prediction of car components, such as the traction battery of an electric car. We show using experimental data from a 1:5 scale model car as well as data from a Fiat 500e car that the proposed ML approach is able to outperform the classical model estimation by means of ARX and ARMAX models. Moreover, we evaluate the performance of a hybrid-ML concept for combination of ML and ARMAX. Our promising results motivate further research in the field of vibration load prediction using machine learning based approaches in order to facilitate design processes.

</details>


