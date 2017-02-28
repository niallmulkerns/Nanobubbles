# Nanobubbles Project Log

*All work below was undertaken and compiled by Niall Mulkerns and Shivani Shah. Please do not copy any parts of this - this is meant only as a reference for the authors.*

## Table of Contents
- [Project Aims](#project-aims)
- [Log of Project Improvements/Directions](#log-of-project-improvementsdirections)
- [Skills Learnt](#skills-learnt)
- [Data](#data)

---

## Project Aims

- To create and monitor bubbles in the TIRF system inside Bill. Including:
  - How the bubbles fluctuate in the x/y direction.
  - How they change in height over time.
  - Determine the resolution of the TIRF.
  - Find the smallest bubbles that can be created and at what voltage.
  - Frequency of bubble creation against time/voltage (how many bubbles visible at each time as a function of voltage).


---

## Log of Project Improvements/Directions

- At first, the project was focussed upon using the AFM and TIRF to examine the growth and other properties of electrochemically and/or static nanobubbles. AFM was featured more due to its wider use in literature, as TIRF has only been used very sparsely.

- Started out with the idea of using ITO (Indium Tin Oxide) as the substrate for bubbles and the cell being made ofrom two slides separated by a small spacer (potentially made from an O-ring or double-sided tape). The liquid would be contained within, most likely by capillary action and surface tension. 

- We had to learn about electrochemistry and how the cell would work. The working electrode would be the surface to create bubbles on, the counter would be an inert metal (platinum-iridium wire - inert over a wide range of potentials) and the reference would be a specifically created silver chloride wire. 

- The first phase was to create a initial iteration of a cell on the microscope such that macro bubbles could be observed, both on a surface and also on a wire.

- Found bubbles easily using potentiostat for steel wire and thick gold surface (non-transparent). Next to try was to find bubbles on an ITO surface. 

- Found that ITO would not support bubbles on the surface like gold would, the coating would be destroyed/fall off by the low potentials (although we did not know this at the time because the ITO is transparent). There would also be a change in colour before that time, which was found to be documented in literature, after which the coating sloped off.

- Thought that it might be to with poor contact from the cell connection to the ITO coverslip, and created many different prototypes to try to combat this, none of which worked. Contact made using silver paint and copper strips, as well as using conductive glue. Thought it could also be due to contamination from plastic, but this was proved wrong when done inside a glass elctrode cell. 

- Tried to determine the "bubble point" of the thick gold sample, as the ITO samples were not producing bubbles. Found that the "dirty" (i.e. not cleaned) gold sample had a significantly higher bubble point (approx -1040 mV) than that of the clean gold sample (approx 575 mV). [Not sure about this as logic dictates that the bubble point should be lower for the dirty sample as the bubbles form around impurities on the surface. Also unsure that the cell was set up correctly for these values to be 100% true].  

- Then tried to deposit silver coating onto the ITO coverslips, however, this silver coating was again delaminated when the coverslip was exposed to low potetnials, approx -1 V, with no bubbles being formed either. The silver coating did take, but was no good for use in the cell due to no bubbles and loss of conductivity/coating at low potential values.

- After this, we decided to try evaporating a gold surface onto the ITO coverslips, which unfortunately did not work either due to reasons mentioned above. Then found the papers on ITO delamination at low potentials [Senthikumar et al 2007] and decided to change tact and start work with normal glass coverlsips instead. However, it is well known that glass and gold do not adhere well to each other, so an adhesive layer must be present between the two to stop the gold from peeling away from the glass at low potentials. 

- Explored multiple options:
  - Electroless plating [Hu et al. 2007]: glass coverslips are silanised with APTES-like solution which allows gold nanoparticles to form a SAM on the surface through a series of chemical baths. Has the disadvantage of being a slow and expensive procedure. *Has not been attempted (to the gold nanoparticles stage) as of yet - see final bullet point.*
  - Evaporate a thin layer of chromium/titanium onto glass (as an adhesive layer between the glass and gold), then evaporate another layer of gold on top. This has the disadvantages of being difficult to control, chromium is toxic, both form oxides in air (which are non-adhesive and impossible to avoid, except using Neil's evaporator) and the fact that both are opaque, so would not help the cause of being transparent. *Has not been attempted as of yet - see final bullet point.*
  - Coat the glass with active groups (such as NH<sub>3</sub> through silanisation or amination) then evaporate gold onto the glass, so that the adhesive layer is the attached molecules. Effectively doing the first part of electroless plating then evaporating instead of using gold nanoparticles. *Attempted first with aminated and silanted glass - silanated glass was sucessful so other options were not followed up.*

---

## Skills Learnt

- How to use a potentiostat.

- Cleaning glassware (and gold samples) chemically using sulfuric and nitric acid (or sulfuric then anneal). Gold samples were cleaned sucessfully such that the characteristic gold cyclic voltammetry response could be seen. [INSERT PICTURE].

- Creating a simple reference electrode for an HCl cell. Achieved by connecting a cell with a silver wire and a stainless steel counter to a DC power suppy at +1 V for five minutes until a brownish coating has formed on the outside of the electrode.

- Creating a standardised solution of a specific molar concentration. 

- Using the TIRF microscope in basement, especially starting it up and focusing the optics of it. Making sure that the laser is properly focused on the centre of the microscope and no scattering occurs. Can take pictures of bubbles and measure their position/height fluctuations. [INSERT PICTURE OF TIRF APPARATUS].

- How to use the evaporator safely and how to set it up consistently such that a film of approximately costant thickness could be achieved (mass of gold used each time is the same, 0.0188 g). 

---

## Data 

![AFM image of gold surface on glass](pictures/SilanGoldBatch2b.jpg)
>*Above: An AFM image of an ultra-thin evaporated gold layer on a glass cover slip that has been silanised using technique described above. The centre part (lighter - graphic is false-coloured based on relative height of surface) shows a scratch in the gold layer, allowing us to see the height difference between glass and the coated glass.*

![AFM profile of surface height](pictures/ProfilefromSilanGoldBatch2b.jpg)
>*Above: Height profile from above AFM image (shown by line). The change in height is approximately 30 nm, however the error on this measurement is fairly large (probably +/- 5 nm, needs more data to compare).*

![TIRF microscopy image of bubble in cell](pictures/LargeBubble.png)
>*Above: A total internal reflectance microscopy image of the left hand side of a large (micro-scale, not nano-scale) bubble on the gold surface of a coated glass slide (the large arc in white, the intense white spots are most likely dust/dirt on the surface). Taken using the cell we created (Bill). Focus needs to be improved.*

---
