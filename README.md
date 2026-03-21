# **A Study on the Analysis of Operating Conditions Based on an Inverse Physics-Informed DeepONet**

Piezoelectric inkjet is a drop-on-demand printing technology in which droplets are generated through the electromechanical deformation of a piezoelectric actuator. Owing to its high precision and controllability, it has recently been applied to various advanced manufacturing fields, including printed electronics, bio-printing, and precision coating. However, defective droplet formation can occur depending on the ink properties, nozzle geometry, and actuator driving conditions. In particular, because the droplet behavior is highly sensitive to interfacial dynamics, real-time stability analysis based on volumetric flowrate variation is required. This study aimed to track droplet-related material properties through the interfacial volumetric flowrate response. For this purpose, an inverse Physics-Informed Neural Network framework was developed to estimate ink properties from the dynamic interfacial behavior. The results showed that the material properties could be inversely identified from the interfacial volumetric flowrate variations under different ink property and voltage conditions. Furthermore, the dynamic response was converted into representative dynamic response parameters, enabling real-time analysis of the transient behavior. These findings suggest that the proposed framework can be effectively used for monitoring and analyzing droplet formation stability in piezoelectric inkjet systems.


<p align="center">
  <img src="Schematicdiagram.jpg" alt="Schematic diagram" width="1000">
</p>

<p align="center"><strong>Fig 1. Schematic diagram of the inverse PIDoN</strong></p>
