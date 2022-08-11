# Scrubber_project

Scrubbers or Exhaust Gas Cleaning Systems (EGCS) are used to remove particulate matter and harmful components, such as sulphur oxides (SOx) and nitrogen oxides (NOx) from the exhaust gasses generated as a result of combustion processes in marine engines, to implement pollution control.

These scrubbing systems have been developed and employed to treat exhaust from engines, auxiliary engines and boilers, onshore and onboard marine vessels, to ensure that no damage is done to human life and the environment by toxic chemicals.

A vessel is supposed to satisfy four conditions in order to be classified as a compliant vessel. The **four parameters** are :
- pH value
- PAH value(poly aromatic hydrocarbons)
- Turbidity Difference
- Gas Ratio
<br><br>    
     
<p align="center" width="100%">
    <img width="50%" src="https://user-images.githubusercontent.com/96611030/184178979-a3e79718-742a-44a0-8f55-59049e5c9c77.jpeg">
</p>

<br>  
A vessel usually has four sensors to calculate and record the four values. A fifth sensor(virtual sensor) is used to perform compliance check in case of a failure of any one sensor.     
Certain regions are labelled as *ECA(Emission Control Areas)* regions have more stringent compliance limits than the global regions. Therefore gas ratio checking depends on the location(lat,long) of the vessel as well.

<br>Therefore the first step is the ECA check where we determine if the vessel is positioned within an ECA polygon. Subsequently a compliance check is performed using a set of rules. 
Further Machine learning models are used to predict missing values for the virtual sensor.
