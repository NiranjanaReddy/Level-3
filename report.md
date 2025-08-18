# MECHANICAL DESIGN:  
## Assembly & Stimulation
I designed a simple two-finger gripper in CAD by first defining the finger geometry and the required jaw opening. The base, fingers, and sliding slots were modeled with precise constraints to ensure smooth movement.After modeling, the parts were virtually assembled in CAD to check alignment and motion. The final assembly was verified using CAD motion simulation to ensure proper gripping action.

![Screenshot 74](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/Screenshot%20(74).png)

![Screenshot 75](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/Screenshot%20(75).png)

---

## Computational Fluid Dynamics:
I imported the aerofoil model from Level 1 Task 2a into Autodesk CFD and set up a virtual wind tunnel environment. The inlet air velocity was specified as **28 m/s**, with appropriate boundary conditions and a fine mesh for accuracy. After running the simulation, I extracted the results to determine the **lift force** generated and compiled the findings into the report.
[Report](https://docs.google.com/document/d/1VBB4w922ytHomtGFuSAT8n4LHZNlrIBp/edit)

---
## Generative Design: 
I used Fusion 360’s **Generative Design** workspace to create an optimized GE bracket model. Starting with the base geometry, I defined the preserve and obstacle regions, applied the required load cases, and set material constraints. The generative solver automatically explored multiple design iterations, optimizing for strength-to-weight ratio, and I selected the best-performing design for further refinement and export.
![Screenshot 80](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/Screenshot%20(80).png)

![Screenshot 79](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/Screenshot%20(79).png)

---

## Piston and crankshaft mechanism:
I began by designing each component of the piston–crankshaft mechanism in **Fusion 360**, starting with the crankshaft, connecting rod, piston, and other necessary parts, ensuring that all dimensions matched realistic engine specifications. Once the individual models were complete, I assembled them within the CAD environment, applying the correct joints and constraints to replicate the actual mechanical motion. I then performed a **motion simulation** to check for smooth operation, verify clearances, and ensure there was no interference between parts. After confirming the design’s functionality, I switched to the **CAM workspace** in Fusion 360, defined the manufacturing setup, selected appropriate machining operations, and generated precise **G-code/NC code** for both the piston and crankshaft, making them ready for CNC manufacturing.
[![Screenshot 81](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/Screenshot%20(81).png)

G_CODE file

---

## Animation and rendering:
I started by creating the Lego man and Lego structure in Fusion 360, carefully modeling each brick and component with precise dimensions to ensure an accurate and realistic build. After completing the individual parts, I assembled them into a full structure, applying the correct joints and constraints to make it functional. Using motion studies, I animated the Lego man and structure, simulating assembly and movement to bring the model to life.

Once the motion was verified, I switched to the rendering workspace, where the  Lego figure stands on a narrow cobblestone street flanked by parked cars and tall buildings. The street is illuminated by warm, yellow-toned streetlights, creating a cozy yet urban nighttime atmosphere. The brick textures of the walls and the glistening reflections on the cobblestones add a sense of realism, while the Lego figure provides a playful and contrasting element in the otherwise realistic setting. The angled perspective of the scene enhances depth, making the Lego figure appear as if it’s casually strolling through the busy city street.
![Lego Man 2.0](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/lego%20man%202.0.png)

![Screenshot 76](https://raw.githubusercontent.com/NiranjanaReddy/Level-3/main/Screenshot%20(76).png)


---

## Geometric Dimensioning and Tolerancing (GD&T):






---

## Introduction to laser engraving:

### Report on Laser Engraving and Keychain Design:

### 1. Introduction to Laser Engraving
Laser engraving is a non-contact process that utilizes a highly focused laser beam to permanently mark or etch a material's surface. This is achieved by the laser beam vaporizing, melting, or changing the color of the material at precise locations according to a pre-designed pattern. The result is a high-resolution, durable mark that can range from shallow surface etching to deeper material removal. Laser engraving is valued for its accuracy, speed, versatility across various materials, and the permanence of the resulting mark.


### 2. Key Components of a Laser Engraving System
A typical laser engraving machine consists of several essential parts:

Laser Source: This component generates the laser beam. Common types include CO2 lasers, which are effective for non-metals like wood, acrylic, and leather, and fiber lasers, which are better suited for metals and some plastics. The power output of the laser source determines the engraving speed and depth.

Power Supply: Provides the necessary electrical power to the laser source.

Laser Tube (for CO2 lasers) or Laser Diode (for fiber/diode lasers): This is where the laser light is produced.

Optical System: This includes mirrors and lenses that direct and focus the laser beam onto the workpiece. The focusing lens is crucial for achieving a small, intense spot size necessary for detailed engraving.

Motion Control System: Consists of motors and belts or lead screws that precisely move the laser head (or the material on a movable bed) in the X and Y axes according to the design.

Control Panel and Software: This allows the user to set parameters such as laser power, engraving speed, and resolution, and to upload and position the design. The software interprets the digital design file and translates it into the movements of the laser head.

Exhaust System: Laser engraving can produce fumes and particulate matter, especially when working with certain materials. An effective exhaust system is crucial for safety and to maintain air quality around the machine.

Cooling System: The laser source generates heat during operation, which needs to be managed to prevent damage and ensure consistent performance. CO2 lasers often use water or air cooling systems.

Work Bed: The platform where the material to be engraved is placed and secured. Different types of work beds are available depending on the application, such as honeycomb beds for better airflow or pin tables for holding irregular shapes.

### 3. Use Cases of Laser Engraving
Laser engraving has a broad spectrum of applications across various industries:

Personalization and Customization: Engraving names, dates, logos, or custom designs on items like jewelry, gifts, promotional products, and awards.

Industrial Marking and Traceability: Applying serial numbers, barcodes, QR codes, and logos to products for identification, tracking, and quality control in sectors like automotive, aerospace, and electronics.

Signage and Display: Creating durable and precise signs, labels, and informational plaques from materials like wood, acrylic, and metal.

Medical and Dental: Marking surgical instruments and medical devices for identification and sterilization tracking.

Artistic and Decorative Applications: Engraving intricate designs and patterns on materials like wood, glass, leather, and textiles for artistic expression and decorative purposes.

Manufacturing: Creating precise stencils, templates, and molds for various manufacturing processes.

Electronics: Marking components and creating circuit board prototypes.

### 4. The Laser Engraving Process: From Basic to End
The laser engraving process typically involves the following steps:

Design Creation: The desired design is created using graphic design software. For engraving, vector graphics are generally preferred as they can be scaled without loss of quality. Common software includes Adobe Illustrator, CorelDRAW, and Inkscape.

File Preparation: The design file is then prepared for the laser engraver's software. This often involves setting line weights, colors (which may correspond to different laser operations like cutting or engraving), and ensuring the design is in the correct format (e.g., .svg, .ai, .dxf).

Material Selection and Preparation: The appropriate material for the application is chosen and prepared. This may involve cleaning the surface or applying a masking material to prevent scorching or residue in certain cases.

Machine Setup: The material is placed securely within the laser engraver. The laser head is then focused to ensure the optimal distance between the lens and the material surface for a sharp and precise engraving.

Parameter Setting: Using the laser engraver's software interface, the user sets the engraving parameters. These typically include:

Power: The intensity of the laser beam, which affects the depth and darkness of the engraving.

Speed: The rate at which the laser head moves across the material. Slower speeds generally result in deeper engravings.

Frequency (PPI/DPI): The density of laser pulses per inch or dot per inch, which affects the detail and smoothness of the engraving.

Test Run (Recommended): Before engraving the final piece, it is advisable to perform a test run on a scrap piece of the same material using the intended parameters to ensure the desired result is achieved.

Engraving: Once the parameters are set and the material is ready, the engraving process is initiated. The laser beam follows the path defined by the digital design, creating the mark on the material's surface.

Post-Processing: After engraving, the material may require some post-processing. This could involve removing any masking material, cleaning off any residue with a soft cloth or appropriate solvent, or applying a finish to enhance the engraved area.


design imageeeee


