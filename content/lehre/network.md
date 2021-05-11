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
- Organisatoren sind Axel Friedewald, Patrick Göttsch, Mijail Guillemard, Haibo Ruan, {{% mention "vonbun_feldbauer" %}}, {{% mention "zemke" %}}.
- Ansprechpartner für Professorinnen und Professoren, die beitragen wollen, sind {{% mention "leborne" %}} und [Marc-André Pick](https://www.tuhh.de/mum/mitarbeiter/oberingenieur/marc-andre-pick.html).

### Ort und Zeit:
- Die Vorträge finden aktuell im Sommersemester 2021 online montags ab 17:00 und je nach Ankündigung (siehe Vortragstitel) in deutscher oder englischer Sprache statt.

### Inhalte und Vortragende im aktuellen Semester:
[Vergangene Semester](/_archive/lehre/#network_ws20)



| # | Datum | Vortragende/r | Thema |
| --- | ---  | --- | --- |
| 1 | 12.04.21 | - | - |
| 2 | 19.04.21 | Hidde&nbsp;Lekanne&nbsp;Deprez | Enhancing simulation images with GANs |
| 3 | 26.04.21 | N/A | - |
| 4 | 03.05.21 | {{% mention "stender" %}} | Physics-Informed Learning [(Zoom)](https://tuhh.zoom.us/j/85800601422?pwd=RCt4U2FQdTE1WlVrcndvMWcrbm5pZz09) |
| - | 10.05.21 | - | Holiday |
| 5 | 17.05.21 | Daniel&nbsp;Höche | Towards predictive maintenance [(Zoom)](https://tuhh.zoom.us/j/93080364767?pwd=ZG5BYTBtdG1keE1LckcvaHJmVWVYdz09) |
| - | 24.05.21 | - | Holiday |
| 6 | 31.05.21 | Amir&nbsp;Kotobi | Dynamic structure investigation of biomolecules with pattern recognition algorithms and X-ray experiments [(Zoom)](https://tuhh.zoom.us/j/93080364767?pwd=ZG5BYTBtdG1keE1LckcvaHJmVWVYdz09) |
| 7 | 07.06.21 | Mijail&nbsp;Guillemard| Basics of Persistent Homology in Machine Learning [(Zoom)](https://tuhh.zoom.us/j/98032176135?pwd=YUpBSEp3MHJWQmZzUE0zaGFOekUvdz09) |
| 8 | 14.06.21 | Nihat&nbsp;Ay | Information Geometry for Deep Learning |
|   | (Prof.&nbsp;Date) | Mirko&nbsp;Skiborowski | tba |
| 9 | 21.06.21 | Benedikt&nbsp;Kriegesmann | Efficient uncertainty quantification using surrogate models: application to fiber composite structures |
|   | (Prof.&nbsp;Date) | Matthias&nbsp;Mnich | Reinforcement Learning for Integer Programming |
| 10 | 28.06.21 | {{% mention "bock" %}} | Data-driven Machine Learning Corrections of Physics-Based Analytical Model Predictions towards High-Fidelity Simulation Solutions – a Hybrid Modelling Approach |
| 11 | 05.07.21 | Patrick&nbsp;Göttsch | MARL Simulation – Multi-Agent Reinforcement Learning Simulation Software |
| 12 | 12.07.21 | N/A | - |

### Abstracts:

<details class="description" close><summary data-close="Show" data-open="Hide"></summary>

2. {{< hl >}}Hidde Lekanne Deprez: Enhancing simulation images with GANs{{< /hl >}} <br/>
In the Standard Platform League, certain types of annotations such as semantic segmentations, depth maps and object localization are difficult to obtain from real world recordings. The use of synthetic data could circumvent this problem as obtaining these annotations within a simulation is trivial. However, there is a catch, the reality gap makes algorithms trained on the synthetic images perform much worse in actual applications. Researchers can painstakingly implement more features to the simulation to close this gap. However, there are alternatives such as the neural networks presented here.
The CycleGan and MUNIT architectures are able to make a domain translation, maintaining semantic information but changing the style, without any labels or matchings. This could mean that a translation between simulation and real images is possible as long as we have images of both domains. For my bachelor thesis I experimented with using these two neural networks to make this translation and my insights are presented in this talk. 

3. {{< hl >}}N/A{{< /hl >}} <br/>

4. {{< hl >}}{{% mention "stender" %}}: Physics-Informed Learning{{< /hl >}} <br/>
Machine Learning and Deep Learning have brought disruptive innovations to many fields since 2012. Today the application of those data-driven, and mostly black-box type models,  can be regarded state-of-the-art in many scientific disciplines. However, the question of knowledge conservation arises: how to bring prior knowledge from generations of research and experience into the modeling process? 
This talk summarizes recent advances, lines of research and perspectives on “Physics-Informed Learning”, which is an umbrella term for blending first principles into evidence-based and data-driven models. Particular focus is put on engineering vibrations and spatio-temporal dynamics, e.g. water waves. 

5. {{< hl >}}Daniel Höche: Towards predictive maintenance{{< /hl >}} <br/>
Sustainable engineering requires reliable and plannable material behaviour in critical working environments like offshore. The extension of digital-twins towards virtual engineering assisted circular economy therefore needs computational models that enable the calculation of maintenance intervals or even the material condition at the end of its service life. 
The talk outlines how the combination of AI tools, data based models and physics based models facilitate predictive maintenance for metallic engineering materials exposed to severe conditions in-service. Aspects related to uncertainty, data availability or validation will be discussed. 

6. {{< hl >}}Amir Kotobi: Dynamic structure investigation of biomolecules with pattern recognition algorithms and X-ray experiments{{< /hl >}} <br/>
The biological functions of macromolecular systems, such as peptides and proteins, are largely defined by their spatial and electronic structures and thus it is of great importance to have high resolution view over these structures. Dynamic structure investigation of biomolecules with advanced molecular dynamic simulations and machine learning approaches on the basis of free energy calculations can give valuable opportunity in analysing the trajectories.

7. {{< hl >}}Mijail Guillemard: Basics of Persistent Homology in Machine Learning{{< /hl >}} <br/>
Persistent Homology is a recent development in applied algebraic topology that has been used in several machine learning strategies. In this talk, we present a short introduction to this topic with several applications in signal processing and data analysis.

8. {{< hl >}}Prof. Date: Nihat Ay: Information Geometry for Deep Learning{{< /hl >}} <br/>
In the first part of my presentation I will highlight the importance of the geometric perspective when dealing with learning systems. Information geometry offers a general framework for the identification of natural geometric structures for learning. The impact of this approach has been demonstrated in terms of the natural gradient method, one of the most prominent information-geometric methods within the field of machine learning. It was proposed by Amari in 1998 and uses the Fisher-Rao metric as a Riemannian metric for the definition of a gradient within optimisation tasks. Since then it proved to be extremely efficient in the context of neural networks, reinforcement learning, and robotics. However, training deep neural networks with this method remains a difficult task. I will present recent results that allow us to greatly simplify the natural gradient for deep learning. I will conclude my talk with an outline of further applications and extensions of information geometry that are particularly important for mathematical data science. <br/>
<br/>
{{< hl >}}Prof. Date: Mirko Skiborowski{{< /hl >}} <br/>
tba

9. {{< hl >}}Prof. Date: Benedikt Kriegesmann: Efficient uncertainty quantification using surrogate models: application to fiber composite structures{{< /hl >}} <br/>
Uncertainty quantification in engineering sciences takes into account the uncertainties that may exist and affect a certain physical system in an a priori unknown manner. If the input parameters of a system or model are subject to stochastic scatter, then also the output parameters (i.e. objective values) scatter randomly. The stochastic distribution of an objective value can be determined with uncertainty quantification methods such as Monte Carlo simulations. This requires a multitude of evaluations of the underlying model (up to 103, 106). Hence, this approach is infeasible for computationally demanding models. For such applications, surrogate models, like artificial neural networks, Kriging and polynomial chaos expansions, can be first trained with a small amount of model evaluations and then used as a proxy instead of the expensive model. <br/>
In the current talk, this procedure is demonstrated by the example of fiber composite structures. Here, the random objective functions are the strength and the stiffness of a component. Random input parameters are (amongst others) material properties, geometric deviations and manufacturing defects. Some random input parameters can only be modelled on a smaller scale than the whole component. Therefore, surrogate-boosted Monte Carlo simulations are performed on different scales and the results in each case are propagated to the higher scale. Strength however can hardly be approximated with standard surrogate models. Here, hierarchical surrogate models are used, which link models of different fidelity, to still allow for an efficient and accurate prediction of the stochastic distribution of strength properties. <br/>
<br/>
{{< hl >}}Prof. Date: Matthias Mnich: Reinforcement Learning for Integer Programming{{< /hl >}} <br/>
The integer programming problem is one of the most fundamental problems in combinatorial optimization, where one seeks an optimal solution among a finite, but usually extremely large set of discrete alternatives. Integer programs are ubiquitous in engineering and industrial applications, as they can model a large variety of highly complex tasks by means of discrete variables which are tight together through constraints. Powerful commercial solvers exists, which can solve large-scale instances with thousands of variables generally quite fast, but there are still several important integer programming models which cannot be solved at all. Theoretical and design and analysis of integer programming algorithms usually fails to explain both the successes, and the failures, of industrial solvers, as worst-case run times of those algorithms are often super-exponential in the number of variables. We discuss novel approaches based on methods of reinforcement learning to attack some of the most prominent integer programming models for which classical methods suffer from expensive time and memory usage, talking about their advantages and limitations.

10. {{< hl >}}{{% mention "bock" %}}: Data-driven Machine Learning Corrections of Physics-Based Analytical Model Predictions towards High-Fidelity Simulation Solutions – a Hybrid Modelling Approach{{< /hl >}} <br/>
N/A

11. {{< hl >}}Patrick Göttsch: MARL Simulation – Multi-Agent Reinforcement Learning Simulation Software{{< /hl >}} <br/>
In this talk a MARL Simulation environment will be introduced to let heterogeneous groups of agents controlled by hand crafted control algorithms or by learned control policies flock for search and rescue missions or to move in a formation by avoiding obstacles. This environment allows simulations of agents constrained by non-ideal communication.

12. {{< hl >}}N/A{{< /hl >}} <br/>

</details>


