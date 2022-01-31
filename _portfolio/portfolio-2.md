---
title: "Hydrothermal-Assisted Jet Fusion (HJF): A Binder-free Additive Manufacturing Approach for Ceramics - 2nd Generation "
excerpt: "2nd generation of HJF process based on a piezoelectric-based inkjet printhead. Related [[Paper]](https://fanfeiuiowa.github.io/files/1-s2.0-S2351978920315687-main.pdf) and [[Patent]](https://patents.google.com/patent/US20210154742A1/en)<br/><img src='/images/2nd_gen_design_2.png' width='400'/>"

collection: portfolio
---
Related [[Paper]](https://fanfeiuiowa.github.io/files/1-s2.0-S2351978920315687-main.pdf)<br/>
* **Printing procedure of HJF process:** It contains five steps, including powder spreading, powder packing, solution deposition, hydrothermal fusion, and de-powdering. 
  * Powder spreading. Similar to many powder-based AM methods, a thin layer of fresh powder is spread on top of the building platform or previous layers by a roller. 
  * Powder compaction. The new layer is then compacted by a piston at a certain level of pressure (e.g., 1 MPa) to increase the packing density of the powder bed, as shown in the image b below. 
  * Ink solution deposition. A piezo nozzle is used to selectively deposit an volatile ink, such as deionized (DI) water or aqueous precursor suspensions, in the powder bed, as shown in image c. These three steps are repeated until all the layers of a 3D model are printed in the powder bed. 
  * Hydrothermal fusion. A hydrothermal environment comprised of a uniaxial pressure and a low temperature is applied to the whole powder bed to trigger the fusion between ceramic particles in ink-wetted regions due to a hydrothermal-mediated dissolution-precipitation mechanism, as shown in image d. The pressure is controlled at a desired level (e.g., 1-50 MPa) through a load cell mounted under the powder platform, and the temperature is maintained at a mild level (e.g., 100 °C) that can effectively evaporate the volatile ink. We define the compaction press in the hydrothermal fusion step as final press. 
  * Finally, a de-powdering process (e.g., brush or ultrasound) is used to separate the fused part with a designed geometry from the surrounding loose powder in the powder bed, as shown in image e. Since no organic binders are used during the HJF process, the printed part does not need any de-binding process to burn out the binders and can potentially exhibit much better material properties including higher relative green density (e.g., more than 90% relative to theoretical density).

<p align="center">
  <img src='/images/2nd_gen_procedure.png' width="600"/>
</p>

* **Prototype of the 2nd generation printer:** The 2nd generation HJF process is a powder-bed-based AM approach. Compared to the 1st generation, the 2nd generation printer has new components of
  * A piezo inkjet nozzle mounted on a XY stage to selectively deposit a volatile ink in each layer.
  * A pressing piston driven by a high-power stepper motor, which applies a pre-press (up to 50 MPa) to each new layer after powder spreading and applies a final press for hydrothermal fusion.

<p align="center">
  <img src='/images/2nd_gen_design_2.png' width="600"/>
</p>

* **Samples:** Complex 3D structure (a Mobius ring) by 2nd generation printer. More printed samples are available in the new paper under review.
<p align="center">
    <img src='/images/2nd_gen_sample.png' width="600"/>
</p>
