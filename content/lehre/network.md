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
Die Vortragsreihe "Train your engineering network" zu vielfältigen Themen des Machine Learnings wendet sich in erster Linie an die wissenschaftlichen Mitarbeiter*innen der TUHH sowie allgemein in der Region Hamburg und zielt darauf ab, den Informationsaustausch zwischen diesen Personen sowie deren Vernetzung in lockerer Atmosphäre zu fördern. Dadurch sollen die Machine-Learning-Aktivitäten innerhalb der TUHH sowie in deren Umfeld sichtbarer gemacht, Kooperationen gefördert und auch interessierten Studierenden ein Einblick ermöglicht werden.

### Ansprechpartner: 
Organisatoren sind Mijail Guillemard, {{% mention "vonbun_feldbauer" %}}, {{% mention "zemke" %}}.

### Ort und Zeit:
Die Vorträge finden aktuell im Sommersemester 2022 online montags ab 16:00 und je nach Ankündigung (siehe Vortragstitel) in deutscher oder englischer Sprache statt.

### Inhalte und Vortragende im aktuellen Semester:

| # | Datum | Zeit | Vortragende/r | Thema |
| --- | --- | --- | --- | --- |
| 1 | 25.04.22 | 16:00&nbsp;-&nbsp;17:00 | Florian&nbsp;Schneider | Transformer Models for Cross-Modal Text-Image Retrieval |
| 2 | 02.05.22 | 16:00&nbsp;-&nbsp;17:00 | Lina&nbsp;Fesefeldt | Second Order Information in Neural Network Training |
| 3 | 09.05.22 | - | - | - |
| 4 | 16.05.22 | 16:00&nbsp;-&nbsp;17:00 | {{% mention "stolpmann" %}} | Distributed Reinforcement Learning on a High Performance Cluster Using Ray |
| - | 23.05.22 | - | - | Holiday |
| 5 | 30.05.22 | 16:00&nbsp;-&nbsp;17:00 | Cornelia&nbsp;Hofsäß | Pulmonary Embolus Detection with Dual-Energy CT Data Augmentation |
| - | 06.06.22 | - | - | Holiday |
| 6 | 13.06.22 | - | - | - |
| 7 | 20.06.22 | 16:00&nbsp;-&nbsp;17:00 | Mijail&nbsp;Guillemard | Tangential bundles, curvature and persistent homology for material defect detection |
| 8 | 27.06.22 | 16:00&nbsp;-&nbsp;17:00 | N.N. | N.N. |
| 9 | 04.07.22 | 16:00&nbsp;-&nbsp;17:00 | Trishita&nbsp;Banerjee | Machine Learning in Security |
| 10 | 11.07.22 | 16:00&nbsp;-&nbsp;17:00 | Denys&nbsp;Romanenko | Holistic process monitoring with machine learning classification methods using internal machine sensors for semi-automatic drilling |

#### Abstracts:

<details class="description" close><summary data-close="Show" data-open="Hide"></summary>

1. {{< hl >}}Florian Schneider: Transformer Models for Cross-Modal Text-Image Retrieval.{{< /hl >}} <br/>
When the Transformer architecture was first introduced, its target research domain was Natural Language Processing, where the famous BERT model pushed the boundaries in several downstream tasks. Motivated by these breakthroughs, other research fields like Computer Vision started to leverage Transformers with great success. <br/>
In state-of-the-art cross-modal text-image retrieval, where images are searched via textual queries, the acquired knowledge from both fields is combined to significantly improve the quality of retrieved images. Further, employing Transformer models enables computing not only global text-image similarity but also fine-granular word-region alignments, which allows in-image search, useful for many real world applications.

2. {{< hl >}}Lina Fesefeldt: Second Order Information in Neural Network Training.{{< /hl >}} <br/>
When choosing an optimizer for your neural network, you will probably consider methods that are based only on first order derivatives, like Stochastic Gradient Descent or Adam. But recent research suggests that second order optimizers are also applicable for neural network training. This is possible via implicit Hessian-vector products. <br/>
This talk tackles the problem of minimizing your cost function from a mathematical point of view. While talking about the use of second order optimizers in neural network training, we will stumble across some interesting properties of neural networks and their cost functions.

3. {{< hl >}}N/A{{< /hl >}} <br/>

4. {{< hl >}}{{% mention "stolpmann" %}}: Distributed Reinforcement Learning on a High Performance Cluster Using Ray.{{< /hl >}} <br/>
Ray is a Python framework for developing distributed applications. While not limited to it, it has a strong focus on Machine Learning and supports it with a variety of included libraries. For example, Ray RLlib provides implementations of many common Reinforcement Learning algorithms, which reduces development time and allows the user to quickly compare different approaches to best solve the problem at hand. As Reinforcement Learning algorithms can be very sensitive to the choice of hyperparameters, Ray Tune can be used to tune them via optimization-based methods. While this typically requires a large number of simulation runs, Ray can speed up the process by running them in parallel on multiple processors or machines. <br/>
This talk gives an introduction to Ray, its libraries and how they can be used to seamlessly scale Reinforcement Learning applications from a laptop to the High Performance Cluster (HPC) of the TUHH.

5. {{< hl >}}Cornelia Hofsäß: Pulmonary Embolus Detection with Dual-Energy CT Data Augmentation.{{< /hl >}} <br/>
3D segmentation U-Nets are trained for pulmonary embolus (PE) detection on three different data sets. We investigate the impact of the training data set on the generalization capabilities and use dual-energy CT data augmentation to increase performance.

6. {{< hl >}}N/A{{< /hl >}} <br/>

7. {{< hl >}}Mijail Guillemard: Tangential bundles, curvature and persistent homology for material defect detection.{{< /hl >}} <br/>
An application to the detection of material defects using persistent homology is presented. We combine tangent bundles and curvature with persistent homology in the context of machine learning.

8. {{< hl >}}N.N.: N.N.{{< /hl >}} <br/>
N.N.

9. {{< hl >}}Trishita Banerjee: Machine Learning in Security.{{< /hl >}} <br/>
Tba

10. {{< hl >}}Denys Romanenko: Holistic process monitoring with machine learning classification methods using internal machine sensors for semi-automatic drilling.{{< /hl >}} <br/>
Since one third of rivet holes during aircraft assembly are produced with semi-automatic drilling units, in this work reliable and efficient methods for process state prediction using Machine Learning (ML) classification methods were developed for this application. Process states were holistically varied in the experiments, gathering motor current and machine vibration data. These data were used as input to identify the optimal combination of five data feature preparation and nine ML methods for process state prediction. K-nearest-neighbour, decision tree and artificial neural network models provided reliable predictions of the process states: workpiece material, rotational speed, feed, peck-feed amplitude and lubrication state. Data preprocessing through sequential feature selection and principal components analysis proved to be favourably for these applications. The prediction of the workpiece clamping distance revealed frequent misclassifications and thus, was not reliable.

</details>

### Vergangene Semester:
 * [Wintersemester 2021/22](/_archive/network/#wise21_22)
 * [Sommersemester 2021](/_archive/network/#sose21)
 * [Wintersemester 2020/21](/_archive/network/#wise20_21)
 * [Sommersemester 2020](/_archive/network/#sose20)
