---
layout: page
title: Research
permalink: /research/
description: My research focuses on automated micromanipulation, cellular manipulation, dielectrophoresis, and digital microfluidics.
nav: true
nav_order: 2
---

## Research Overview

My research focuses on developing automated micromanipulation systems using dielectrophoresis (DEP) for various biological applications. The key research areas include:

- **Single-particle micropatterning** using robotic nDEP-tweezers
- **Biological cell patterning** on different substrates
- **Large-scale cell cluster patterning** with microchip systems
- **Embryo manipulation** via robotic nDEP-tweezers

---

## Research Projects

### 1. Single-particle Micropatterning

High-quality single-bead patterns are constructed through the system. Multiple relays are connected to the microchip to energize individual dot-electrodes to generate different electric field forms for micro bead holding and patterning. PS bead pattern with orange fluorescent color is fabricated.

{% include figure.liquid path="assets/img/research/single_particle.jpg" title="Single-particle Micropatterning" class="img-fluid rounded z-depth-1" %}

**Description:**
High-quality single-bead patterns are constructed through the system. Multiple relays are connected to the microchip to individually energize the dot electrodes to generate the electric fields for micro bead (Polystyrene bead) holding and patterning. Optimization patterning strategies are proposed to reduce the time for patterning. In order to prevent more than one bead from being trapped by the same electrode, vision-based algorithms are developed to manipulate the target bead toward the desired position with respect to the electrode such that the redundant beads near the target bead can be repelled by the electric field. To avoid the target bead being influenced by local electric field minima or other electrodes, path planning is incorporated for bead manipulation. A controller is used to guide the microparticles follow the created path. 40um diameter PS bead with a fluorescent color is considered to conduct the experiments. A series of tests are performed to validate the effectiveness and robustness of this system.

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    <iframe width="100%" height="315" src="https://www.youtube.com/embed/EQhd-nqbMF0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div class="caption">
  Video demonstration of single-particle micropatterning (youku: https://v.youku.com/v_show/id_XNDY2NzA5MDA1Ng==.html)
</div>

Compared to the LOC device, the proposed system offers high flexibility for micropatterning. The movability of the microchip not only increases the working area, but also provides a possibility to be applied with a controller for precise control. Besides, the cost for large numbers of microparticles manipulating and patterning is low. By increasing the number of electrodes, it is easy to construct a high-throughput microparticles pattern. The controllability for the individual electrodes achieves different micropatterns fabrication. The microchip can selectively trap the microparticles for forming different patterns.

**Related Publications:**
1. **K. Huang**, Z. Cui, J. Lai, B. Lu and H. K. Chu, "Optimization of A Single-particle Micropatterning System with Robotic nDEP-Tweezers", in IEEE Transactions on Automation Science and Engineering (T-ASE), 2020.
2. **K. Huang**, Z. Cui, I. A. Ajamieh, J. Lai, J. K. Mills, and H. K. Chu, "Automated Single-Particle Micropatterning System using Dielectrophoresis", 2020 IEEE International Conference on Automation Science and Engineering (CASE), Hong Kong, China, 2020.

---

### 2. Yeast Cell Cluster Patterning on Different Substrate

Biological cell cluster patterning is conducted through the system. Different cell cluster patterns are formed on the substrate by controlling the opening of each dot electrode on the microchip.

{% include figure.liquid path="assets/img/research/cell_pattern.jpg" title="Cell Patterning on Different Substrates" class="img-fluid rounded z-depth-1" %}

**Description:**
Biological yeast cell (8um) cluster patterning is conducted through the system. Cell behavior is investigated under DEP force with different media, voltage inputs for generating electric fields, and voltage frequencies to enhance the performance and efficiency of nDEP patterning. Different cell cluster patterns are formed on the substrate by controlling the opening of each dot electrode on the microchip. By holding the cells in clusters and transferring the microchip, clean cell cluster patterns can be created. In order to form the cell pattern in different substrates, the mechanism for cells to adhere to the substrate is also examined to optimize cell attachment. With the system, we can trap and pattern cells on the surface of any substrate with design forms.

{% include figure.liquid path="assets/img/research/cell_pattern_detail.jpg" title="Patterns observed from the microscope and the corresponding inputs on various substrates" class="img-fluid rounded z-depth-1" %}
<div class="caption">
  Patterns observed from the microscope and the corresponding inputs on various substrates: (A,B) glass; (C,D) PMMA; (E,F) PDMS; and (G,H) PVC
</div>

Different from the LOC device, the separation between the microchip and the substrate in this system makes it possible to pattern the biological cells to any biocompatible material substrate instead of the glass. The open environment of the system enables cell patterning in a shaped hydrogel substrate as the hydrogel can be picked and manipulated after crosslinking. Moreover, the relative movement between the microchip and the substrate increases the flexibility of the microchip, providing a way to construct a large-scale cell pattern.

**Related Publications:**
1. **K. Huang**, B. Lu, J. Lai, and H. K. Chu, "Microchip System for Patterning Cells on Different Substrates via Negative Dielectrophoresis", in IEEE Transactions on Biomedical Circuits and Systems (TbioCAS), vol. 13, no. 5, pp. 1063-1074, Oct. 2019. <a href="/files/tbiocas_2019.pdf">[paper]</a>
2. **K. Huang**, H. K. Chu, B. Lu, L. Cheng, "Characterization of a Microchip Device for Cell Patterning via Negative Dielectrophoresis", 2018 IEEE Conference on Robotics and Biomimetics (ROBIO), Kuala Lumpur, Malaysia, 2018, pp. 1521-1526. <a href="/files/robio_2018.pdf">[paper]</a>

---

### 3. Large-scale Cell Cluster Patterning with the Proposed System

A large-scale yeast cell pattern is achieved using the moving platform of the microscope. The relative movement between the microchip and the substrate on the platform aids in constructing cell cluster patterns anywhere in the substrate.

{% include figure.liquid path="assets/img/research/large_cell_pattern.png" title="Large-scale Cell Cluster Patterning" class="img-fluid rounded z-depth-1" %}

**Description:**
A large-scale yeast cell pattern is also achieved using the moving platform of the microscope. The relative movement between the microchip and the substrate on the platform aids in constructing cell cluster patterns anywhere in the substrate. A series of cell cluster characters are patterned by intermittently energize the specific electrodes while the platform is moving. Experiments on cell cluster dissipation time are conducted to decrease patterning time and improve performance.

{% include figure.liquid path="assets/img/research/polyu_pattern.png" title="A serial character pattern 'P', 'O', 'L', 'Y', 'U'" class="img-fluid rounded z-depth-1" %}
<div class="caption">
  A serial character pattern 'P', 'O', 'L', 'Y', 'U'
</div>

**Related Publications:**
1. **K. Huang**, H. K. Chu, B. Lu, J. Lai and L. Cheng, "Automated Cell Patterning System with a Microchip using Dielectrophoresis," 2019 International Conference on Robotics and Automation (ICRA), Montreal, QC, Canada, 2019, pp. 634-639. <a href="/files/icra_2019.pdf">[paper]</a>

---

### 4. Embryo Manipulation via Robotic nDEP-tweezers

Equipped with a large-scale quadrupole microchip, the system enables mouse embryo alignment and rotation for laser drilling.

{% include figure.liquid path="assets/img/research/translation.png" title="Embryo Manipulation" class="img-fluid rounded z-depth-1" %}

**Description:**
Equipped with a large-scale quadrupole microchip, the system enables mouse embryo rotation and alignment. The microchip simulation shows that the designed quadrupole electrode microchip can trap and rotate the embryos in the center of the electrodes. Vision-based algorithms are developed to acquire necessary information such as, the position and orientation of the embryo relative to the electrodes for precise control. With this information, the PID controller is applied to the system for precise embryo manipulation. The PID controller is applied to the system for embryo translation and rotation to increase the accuracy of the system. A series of tests is performed to validate the effectiveness and robustness of the system.

This system offers a non-contact method for embryo manipulation, avoiding the adhesion force between the embryo and the tool. The controllers applied to the system guarantee the operation accuracy for manipulation. The most important is that, compared with the LOC device, the open environment of the system provides the possibility of further processing after cell manipulation, such as cell injection.

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    <iframe width="100%" height="315" src="https://www.youtube.com/embed/1zbdfI6GYKA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div class="caption">
  Video demonstration of embryo manipulation (youku: https://v.youku.com/v_show/id_XNDY2NzA2NTYyOA==.html)
</div>

---

## Research Impact

Our research on automated micromanipulation systems has applications in:
- **Tissue Engineering**: Precise cell patterning for artificial tissue construction
- **Drug Screening**: High-throughput cell-based assays
- **Assisted Reproduction**: Non-contact embryo manipulation
- **Biomedical Research**: Cell behavior studies and analysis
