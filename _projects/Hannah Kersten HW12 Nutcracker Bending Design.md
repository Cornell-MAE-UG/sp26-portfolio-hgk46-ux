## **Find**
Our goal is to design an actuator-integrated nutcracker with elastic deflection mitigated to less than 2% of the total device length. 

## **Assumptions**
Below are the assumptions required to complete this calculation. 
1. Average load to crack a macadamia nut is 225 kg, which is 500lbf, or 2210 N (2.210 kN) (Schrauf et al.)
2. Average macadamia nut shell diameter is about 25 mm, so a radius of 12.5 mm. For the macadamia nut, we will assume a circular shape.
3. Average grip strength is about 35kg, and the actuator replacement must replace this squeezing load completely.

## **Plan**
1. Linear actuator allocation
2. Free body diagram / schematic of the nutcracker design with the actuator implementation.
3. Free body diagrams of respective top and bottom levers
4. Deflection calculations for top and bottom levels
5. Find the maximum deflection in both levers-- the higher deflection governs the design (limiting equation)
6. Use limiting equation to solve for a moment of inertia of the cross-sectional area of the levers
7. Report final material, dimensions, and linear actuator pick.

## **Solve**
1. Using the grip strength values, an adequate linear actuator should be able to output a force of about 150 lbs, which is equal to about 667.2 Newtons (we will use this value in further calculations)

**Design Choice 1: Linear Actuator**

_Model_: PA-14-1-150

_Title_: Mini Linear Actuator - Optional Feedback

_Stroke_: 1 inch

_Force_: 150 lbs

_Cost_: $119.99 USD

2. FBD/Schematic

<img src="/assets/images/ActuatorNutFBD.jpg" width="60%">

3. (and 4, 5) Deflection Analysis
<img src="/assets/images/Deflection.jpg" width="60%">

Based on the calculations, the bottom lever governs our design choice. Let's pick a strong, commercialized material for design in the lever arms, such as industrial steel with an elastic modulus of 200 GPa. Using this materal...

6. The moment of Inertia of the cross sections must be 442 kg mm^4. Let's use circular cross sections, so that the radius must be 4.87 mm.

7. **Design choice 2: Level Material and Dimensions**

_Material_: Industrial steel, E=200 GPa

_Cross-sectional shape_: Circular.

_Diameter_: 9.74 mm.

_Total volume of Required_: 0.023848 cubic meters

_Cost_: Using density of steel= 7850 kg/m^3, the mass is 187.21 kg. This would cost about $0.75 per kg, so $140.40 (https://vmtcnc.com/mild-steel-price-per-kg).

## **Final Design**

<img src="/assets/images/Finaldesign.jpg" width="60%">

## **Reflection**
The total cost of materials for this design is about $260, making it a costly device more equipped for industrial use. The actuator implemented is high-speed, so this also makes the design adequate for an industrial setting. One limitation of this design is that it can only crack one nut at a time, so it should be adjunct with a device that can place the nut in the nutcracker fast and efficiently for optimal use.










