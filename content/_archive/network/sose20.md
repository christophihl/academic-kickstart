+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 100  # Order that this section will appear.

title = ""

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

## Sommersemester 2020

### Inhalte und Vortragende:


| # | Datum | Vortragende/r | Thema |
| --- | ---  | --- | --- |
| 1 | 20.04.20 |{{% mention "dostal" %}} | Towards Reinforcement Learning-based Control of an Energy Harvesting Pendulum [(Video)](http://webcast.tu-harburg.de/Mediasite/Play/a360b2dfc7854250837a1b8bfdf22adc1d)|
| 2 | 27.04.20 | {{% mention "dostal" %}} | Advances in the development of car simulation models for vibration load prediction using Machine Learning [(Video)](http://webcast.tu-harburg.de/Mediasite/Play/df17d927c5a8405a8bc53349d70577f11d)|
| 3 | 04.05.20 | {{% mention "grossert" %}} | A Hybrid Approach for Modeling of Multibody Systems with Nonlinear Force Elements |
| 4 | 11.05.20 | {{% mention "schoepflin" %}} | Bilddatengenerierung als Trainingsdatensatz für eine KI-Objektidentifikation in der Intralogistik [(Video)](http://webcast.tu-harburg.de/Mediasite/Play/b94a47b0850c448fbab1097928bbaf1c1d)|
| 5 | 18.05.20 <br/> (Prof&nbsp;Date) | {{% mention "knopp" %}} <br/> {{% mention "fey" %}} <br/> {{% mention "meissner" %}} | Deep Learning for the Classification of Diseases in Chest X-Ray <br/> Artificial Neural Networks and Faults <br/> An automatic, data-driven definition of atomic-scale structural motifs |
| 6 | 25.05.20 | Kai&nbsp;Sellschopp & <br/> {{% mention "wuerger" %}}| Exploration of structure - property relationships with unsupervised ML [(Video)](http://webcast.tu-harburg.de/Mediasite/Play/269456c1ead74566916bbbe2f23196071d )|
| - | 01.06.20 | - | Pfingsten Holiday |
| 7 | 08.06.20 | {{% mention "kellner" %}} & <br/> {{% mention "stender" %}} | Explainable AI and its application to ice mechanics |
| 8 | 15.06.20 | {{% mention "bahnsen" %}}| Emulation von neuronalen Netzen unter Hardwarefehlern |
| 9 | 22.06.20 <br/> (Prof&nbsp;Date) | {{% mention "schlaefer" %}} <br/> Christian&nbsp;Cyron <br/> Carlos&nbsp;Jahn | Machine Learning for Spatio-Temporal Signal Processing <br/> Maschinelles Lernen in der Materialmodellierung <br/> ML in der maritimen Logistik - Anwendungen aus Schifffahrt und Hafen |
| 10 | 29.06.20 | {{% mention "schierholz" %}} | Application of Artificial Neural Networks for Power Integrity Evaluation |
| 11 | 06.07.20 | {{% mention "lindner_s" %}} | Predictive medium access techniques for wireless networks |
| 12 | 13.07.20 | Maximilian&nbsp;Stark | End-to-end learning in Wireless Communications |
| 13 | 20.07.20 | Rüdiger&nbsp;Schmitz | tbd |
| 14 | 27.07.20 | {{% mention "jahn" %}} | ML-unterstützte Problembeschreibungen in digitalen Assistenzsystemen |


#### Abstracts:

<details class="description" close><summary data-close="Show" data-open="Hide"></summary>

1. {{< hl >}}{{% mention "dostal" %}}: Towards Reinforcement Learning-based Control of an Energy Harvesting Pendulum.{{< /hl >}} <br/>
Harvesting energy from the environment, e. g. ocean waves, is a key capability for the long-term operation of remote electronic systems where standard energy supply is not available. Rotating pendulums can be used as energy converters when excited close to their eigenfrequency. However, to ensure robust operation of the harvester, the energy of the dynamic system has to be controlled. In this study, we deploy a lightweight reinforcement learning algorithm to drive the energy of an Acrobot pendulum towards a desired value. We analyze the algorithm in an extensive series of simulations. Moreover, we explore the real world application of our energy-based reinforcement learning algorithm using a computationally constrained hardware setup based on low-cost components, such
as the Raspberry Pi platform.

2. {{< hl >}}{{% mention "dostal" %}}: Advances in the development of car simulation models for vibration load prediction using Machine Learning.{{< /hl >}} <br/>
Nowadays electric cars are a focus area in automotive research. In this context we consider data based approache as tools to improve and facilitate the car design process. Hereby, we address the challenge of vibration load prediction for electric cars using neural network based machine learning (ML), a data-based frequency response function approach, and a hybrid combined model. We extensively study the challenging case of vibration load prediction of car components, such as the traction battery of an electric car. We show using experimental data from a 1:5 scale model car as well as data from a Fiat 500e car that the proposed ML approach is able to outperform the classical model estimation by means of ARX and ARMAX models. Moreover, we evaluate the performance of a hybrid-ML concept for combination of ML and ARMAX. Our promising results motivate further research in the field of vibration load prediction using machine learning based approaches in order to facilitate design processes.

3. {{< hl >}}{{% mention "grossert" %}}: A Hybrid Approach for Modeling of Multibody Systems with Nonlinear Force Elements.{{< /hl >}} <br/>
Due to the introduction of simplifications and idealizations during the modeling process of a real-world system, the created mathematical model will always behave slightly different compared to the real-world system. This might become problematic, depending e.g. on the use case of the model or the size of the deviation itself. In such a case, more complex models might produce relief, even though they cannot ensure satisfactory results. Furthermore, such modeling is not always possible, e.g. due to a lack of information about the real world system. In this talk, an approach for solving that kind of problems is presented. By inserting neural networks into the model created before, it is possible to reduce the deviation between model and real-world system without the need of more information except the measured data that is used to compare the model and the real-world system. The approach is presented by comparison of different modeling approaches of a nonlinear single mass oscillator.

4. {{< hl >}}{{% mention "schoepflin" %}}: Bilddatengenerierung als Trainingsdatensatz für eine KI-Objektidentifikation in der Intralogistik.{{< /hl >}} <br/>
Der massive Bedarf an Daten zum Training von neuronalen Netzwerken stellt den industriellen Transfer erforschter Ansätze vor hohe Herausforderungen. Frei verfügbare Datensätze sind oftmals nicht in der Lage, die spezifischen und individuellen Anforderungen von Unternehmen abzudecken. Die synthetische Erzeugung von Trainingsdaten zeigt sich hierbei als erfolgsversprechende Alternative. In diesem Vortrag wird die Generierung von Trainingsbildern für eine KI-Objektidentifikation im intralogistischen Umfeld beleuchtet und aufgezeigt, welche Hürden für eine erfolgreiche Implementierung genommen werden müssen.

5. {{< hl >}}{{% mention "knopp" %}}, {{% mention "fey" %}}, Robert Meissner: tbd.{{< /hl >}} <br/>
N/A

6. {{< hl >}}Kai Sellschopp, {{% mention "wuerger" %}}: Exploration of structure - property relationships with unsupervised ML.{{< /hl >}} <br/>
Many areas of applications – ranging from corrosion engineering to catalysis on inorganic surfaces and from drug design to polymer composites in organic materials – are influenced by the atomic structure of the materials involved. Luckily, due to modern experimental and simulation methods, it is often possible to obtain a detailed atomistic understanding of the achieved material properties. However, as the sheer number of potentially useful agents and their huge space of possible configurations renders comprehensive analyses resource- and time-consuming, other measures to predict the performance of yet untested molecules are required. One potential approach is the investigation of quantitative structure-property relationships (QSPR) using the Smooth Overlap of Atomic Positions (SOAP) kernel - a descriptor for atomic environments, that provides a translationally and rotationally invariant representation and therefore allows to calculate molecular similarities. Plotting these similarities on a map and combining them with
experimental and theoretical results can then be used to intuitively explore structure-property relationships and predict yet unknown material properties. <br/> In our talk, we first explain the basics of the SOAP kernel and how it can be used to distinguish atomic structures and speed up the process of finding the most favorable configurations. Then we show how SOAP is used in real life applications, such as in the control of magnesium-electrolyte interface properties, to gain deeper insights into fundamental mechanisms on an atomistic level.

7. {{< hl >}}{{% mention "kellner" %}}, {{% mention "stender" %}}: Explainable AI and its application to ice mechanics.{{< /hl >}} <br/>
Criticism of data based models evolves around the problem of causation/correlation and the lack of knowledge generation when using those models. Naturally, and particularly for large black box models, this criticism is strongly connected to discussions under the umbrella of explainable or interpretable AI (XAI). After all, understanding why a model makes a prediction is key for, among others, trust, accountability, debugging and generalizability. A lack of understanding impedes improvement of models and input data as well as insight into the process being modeled. <br/> To begin with, we give a general motivation and overview on interpretability of data based models. This includes why interpretability is important, possible perspectives on interpretability, and lastly interpretability-related methods and tools. <br/> Secondly, we show-case machine learning and the SHAP (SHapley Additive exPlanation) interpretability toolbox to understand and predict the behavior of ice under compressive loads. Specifically, we are not interested in the best model but in which features drive model predictions, e.g. in a feature importance ranking. The identification of these features will be used as an addition to domain knowledge to create better material models for ice using a large experimental data base. 


8. {{< hl >}}{{% mention "bahnsen" %}}: Emulation von neuronalen Netzen unter Hardwarefehlern. {{< /hl >}} <br/>
Neueste Errungenschaften in verschiedenen Bereichen werden durch den Einsatz künstlicher neuronaler Netze (NN) erzielt, z.B. im Bereich der Spracherkennung oder der Bildverarbeitung. Ein NN löst Probleme durch statistisches Lernen mit ressourcenlastigen Berechnungen. Um NN für mobile Geräte, eingebettete oder IoT-Systeme zu implementieren, wird Hardwarebeschleunigung immer wichtiger, um Energie-, Kosten- oder Rechenzeitanforderungen zu erfüllen. In einem Hardwarebeschleuniger werden die arithmetischen Operationen des NN sequentiell auf wenigen Recheneinheiten berechnet, so dass ein Fehler in der Verarbeitungshardware einen erheblichen Einfluss auf die Ausgabe des NNs haben kann. Die Zuverlässigkeit eines NNs und damit auch der zugehörigen Anwendung hängt dann nicht mehr ausschließlich von statistischen Fehlern im NN-Modell ab - die Zuverlässigkeit wird vielmehr durch das Zusammenspiel von NN-Modell und Hardware bestimmt. In dem Vortrag wird eine Technik zur Emulation von NN-Inferenz auf Hardware-Ressourcenbeschreibungen erläutert. Anschließend werden die Injektion von Hardwarefehlern und deren Auswirkung an verschieden Beispielen erörtert.

9. {{< hl >}}{{% mention "knopp" %}}, {{% mention "fey" %}}, {{% mention "meissner" %}}: tbd.{{< /hl >}} <br/>
N/A

10. {{< hl >}}{{% mention "schierholz" %}}: Application of Artificial Neural Networks for Power Integrity Evaluation. {{< /hl >}} <br/>
Increasing demands on modern electronic systems with respect to Signal and Power Integrity on printed circuit boards require many simulations during an optimization process. The necessity of additional and more complex simulations requires new and advanced simulation and optimization techniques. Using machine learning is one attempt to improve the efficiency of these optimization processes. The high dimensional problem of the power integrity analysis is especially challenging. The approach to improve the power delivery network of printed circuit boards with decoupling capacitors is analysed with artificial neural networks. The focus is based on the importance of preprocessing the input data and exploit the available domain knowledge to increase the accuracy of the artificial neural network.

11. {{< hl >}}{{% mention "lindner_s" %}}: Predictive medium access techniques for wireless networks. {{< /hl >}} <br/>
Spectrum scarcity requires novel approaches for sharing frequency resources between different radio systems. Where coordination is not possible, intelligent approaches are needed, allowing a novel "secondary" system to access unused resources of a legacy (primary) system without requiring modifications of this primary system. Machine Learning is a promising approach to recognize patterns of the primary system and adapt the channel access accordingly. In this contribution we investigate the capability of Feed-Forward Deep Learning and Long Short Term Memory (LSTM) Recurrent Neural Networks (RNNs) to detect communication patterns of the primary user. <br/> Therefore, we take the example of a new aeronautical system (LDACS) coexisting with three different systems. Firstly, the coexistence with the Distance Measurement Equipment (DME) providing a deterministic interference to the secondary user and secondly with two synthetic channel access patterns, realized by a 2-state Markov model, modeling a bursty channel access behavior, as well as through a sequential channel access model. <br/> It can be shown that the Markov property of a Gilbert-Elliot channel model limits the predictability; nonetheless, we show that the model characteristics can be fully learned, which could leverage the design of interference avoidance systems that make use of this knowledge. The determinism of DME allows an error-free prediction, and it is shown that the reliability of sequential access model prediction depends on the model's parameter. <br/>The limits of Feed-Forward Deep Neural Networks are highlighted, and why LSTM RNNs are state-of-the-art models in this problem domain. We show that these models are capable of online learning, as well as of learning correlations over long periods of time.

12. {{< hl >}}{{% mention "stark" %}}: End-to-end learning in Wireless Communications. {{< /hl >}} <br/>
N/A


13. {{< hl >}} Rüdiger Schmitz: tbd. {{< /hl >}} <br/>
N/A


14. {{< hl >}}{{% mention "jahn" %}}: ML-unterstützte Problembeschreibungen in digitalen Assistenzsystemen. {{< /hl >}} <br/>
Im industriellen Umfeld ermöglichen Augmented-Reality-Anwendungen die Erstellung am Bauteil dreidimensional verorteter Rückmeldungen. Diese dokumentieren mit kurzen Texten und Fotos Montageprobleme und Bauteilfehler in der Produktion. Allerdings schwankt die Informationsqualität der Rückmeldungen in Abhängigkeit des Erstellers und dessen Zeit zur Eingabe der Beschreibungen auf dem mobilen Endgerät.
Auf maschinellem Lernen basierende Empfehlungsdienste bieten einem Nutzer die unterstützende Möglichkeit, Vorschläge für sinnvolle Textbausteine einer Problembeschreibung zu erhalten. <br/> Ich werde einen Prototyp für einen dafür geeigneten hybriden Empfehlungsdienst vorstellen, welcher sich aus einer Bildklassifikation mittels Deep Learning und einer Textverarbeitung mittels Data Mining und Natural Language Processing zusammensetzt. <br/>Einen weiteren Schwerpunkt stellt die Integration des Prototyps in Form eines ML-Microservices in eine Cloud-Infrastruktur am Beispiel von Kubernetes und Python-Webservices dar, sodass dieser von externen Anwendungen genutzt und gleichzeitig leicht weiterentwickelt werden kann.






</details>


