# MakAir Casing

## History

| Version | Last Changelog | Ready? | Live CAD Models |
| ------- | -------------- | ------ | --------------- |
| V1 | Initial design & fits | ❌ | [view model](https://a360.co/2JyIU9P)
| V2 | Update mensurations | ✅ | [view model](https://a360.co/2RlnfGp)
| V3 | Experimental casing (canceled) | ❌ | [view model](https://a360.co/2BoKPgj)
| V4 | MakAir Mini casing w/ a smaller footprint | ✅ | [view model](https://a360.co/2RHpseW)

## 🧪 MakAir Mini Experimental Design

![Experimental Casing Header](./res/schemes/Experimental/V4/Casing%20(Header).jpg)

On the side, we are working on an experimental, fully 3D-printable casing. It has the benefit of being more user-friendly, as well as much more compact and practical to use and handle (eg. if the MakAir needs to be moved to another room). It also has a minimum cubic footprint: `20cm x 20cm x 20cm`, and aims at being lightweight.

**➡️ You can [view it in 3D](https://a360.co/2RHpseW) in your Web browser.**

Multiple of those casings can be stacked on the top of each other, as well as on the sides of each other. This makes shipping of a large number of those ventilators much handier than with previous casing versions, by stacking them in a truck without any extra protections overhead (other than a compact cubic packaging box and some tight foam).

The screen is set on the top, as to save casing space. The legacy 4 lines small display was removed, while the 7" touchscreen handles all control tasks — that came previously from hardware buttons.

This design makes mass-manufacturing more convenient, as components are split into 2 stages: pneumatics and electronics. Both stages can be separately assembled by specialized workers on  the assembly line, and can then be inserted in the molded casing from the bottom, and finally are screwed into place.

Maintenance is also easier with this new design, as stages can be unscrewed and slided out of the casing. If a stage cannot be repaired onto place, it can be swapped with a replacement stage in a matter of minutes.

Note that all parts from this casing were designed to be moldable. A mold is expensive, but for high production volumes one can produce a lot of casing parts in a matter of seconds, for less than 5€ per casing unit — once the mold is fully amortized (this contrasts with the high unit cost of our V2 respirator casing).

**⚠️ Note: this design is not ready yet. We are currently testing it and making refinements. There is a concern regarding the thermal performance of the design, as it is much more compact than any previous design we released (the blower may need some extra cooling). Note that it also requires using a 6S Lithium-ion battery pack, which we have not sourced nor adapted yet.**

### Parts

1. **Casing [x1]:** the exterior casing, largest part to be molded, fits every other part;
2. **Pneumatics Stage [x1]:** the stage holding into place all pneumatic parts (lower level);
3. **Electronics Stage [x1]:** the stage holding into place all electronic parts (upper level);
4. **Air Plug [x1]:** pneumatic input/output connectors, inserted in the casing from the front at the end of the assembly process, screwed to the pnematics stage;
5. **Electrical Plugs [x1]:** electrical input/output connectors, inserted in the casing from the rear at the end of the assembly process, screwed to the electronics stage;
6. **Blower Holder [x1]:** holds the blower firmly into place, screwed from the top of the blower, on the pneumatics stage;
7. **Piping Holder [x3]:** holds all flexible pipes and apply a constraint onto them, screwed from the top, on the pneumatics stage;
8. **Blower To O2 Mixer Connector [x1]:** connects the blower output to the O2 mixer input, with a minimum space footprint (unfortunately, using connectors from the market consumed too much space in this case);
9. **Filter Box Top Fit [x2]:** the top fit of each of the 2 filter boxes, holds the disposable HEPA filter into place;
10. **Filter Box Casing (Exhaust Out) [x1]:** the exhaust output line filter box casing, screwed to the pneumatics stage (filters air coming out from the patient lungs);
11. **Filter Box Casing (Blower In) [x1]:** the blower input line filter box casing, screwed to the pneumatics stage (filters air coming in to the blower, ultimately to the patient lungs);

_Adding to that: adapted stickers should be added on the Electrical Plugs + Air Plug parts as to provide information on input/output channels, and hide screws. As well, a MakAir logo and brand name should be printed and fitted into the front logo fit on the Casing part._

### Renders

<p align="center">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%201).png" width="377">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%202).png" width="335">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%203).png" width="346">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%204).png" width="312">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%205).png" width="413">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%206).png" width="381">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%207).png" width="351">
  <img alt="Experimental Casing Render" src="./res/schemes/Experimental/V4/Casing%20(Render%208).png" width="352">
</p>

### Pictures

#### 1️⃣ Validation parts (3D printed)

Pictures of our early FDM & SLA print tests can be found below. Large parts (casing and stages) are printed using FDM, while smaller parts (adapters et al) are printed using SLA (which is more dimensionally accurate than FDM; though more expensive).

_Those parts will help validating the experimental design, before proceeding with manufacturing molds._

<p align="center">
  <img alt="Printed Casing" src="./res/pictures/Experimental/V4/Casing%201.jpg" width="347">
  <img alt="Printed Small Parts" src="./res/pictures/Experimental/V4/Casing%202.jpg" width="426">
  <img alt="All Printed Parts" src="./res/pictures/Experimental/V4/Casing%203.jpg" width="766">
</p>

#### 2️⃣ Assembly process

Pictures of the assembly process of our MakAir Mini can be found below. The parts used there come from our standard, larger MakAir ventilator. To the exception of the AC/DC power converter, which has been swapped to a smaller, 50W unit.

<p align="center">
  <img alt="Assembled Stages" src="./res/pictures/Experimental/V4/Assembly%201.jpg" width="426">
  <img alt="Assembled Casing" src="./res/pictures/Experimental/V4/Assembly%202.jpg" width="364">
  <img alt="Inserting Stages In The Casing" src="./res/pictures/Experimental/V4/Assembly%203.jpg" width="766">
</p>

#### 3️⃣ Final proof-of-concept

The pictures of the assembled MakAir Mini proof-of-concept can be found below. The ventilator final weight went from 25Kg down to 2.5Kg (including batteries, which went from lead-acid to Lithium Ion).

<p align="center">
  <img alt="Lateral View Of The MakAir Mini" src="./res/pictures/Experimental/V4/Final%201.jpg" width="426">
  <img alt="Top View Of The MakAir Mini" src="./res/pictures/Experimental/V4/Final%202.jpg" width="280">
  <img alt="Global View Of The MakAir Mini" src="./res/pictures/Experimental/V4/Final%203.jpg" width="766">
</p>

#### ℹ️ Size comparisons

Those pictures show a MakAir Mini, compared to our first MakAir Standard design. A GameCube has been added for scale.

_Note that the MakAir Mini that appears on the pictures here is a first-off dirty shot. As the 3D printer that we used to print the casing could not print 20x20x20cm straight, we had to split the casing into 8 parts that were connected with tape. The final validation casing shown on the pictures above has been printed in one solid part, hence why it looks much better._

<p align="center">
  <img alt="Size Comparison Of MakAir Standard, MakAir Mini And A GameCube" src="./res/pictures/Experimental/V4/Size%201.jpg" width="760">
</p>
