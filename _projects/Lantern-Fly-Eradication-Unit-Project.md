---
layout: project
title: Lantern Fly Eradication Unit
image: /assets/images/SLF.jpg
---

<p align="center">
  <b>Reducing Spotted Lanternfly Contamination During Mechanical Grape Harvest</b><br>
  <b>Lantern Fly Eradication Unit</b>
</p>

This MAE 2250 project focused on reducing spotted lanternfly contamination during mechanical grape harvesting. Our team developed and tested a gear-driven gas dispersion prototype intended to deter lanternflies immediately before grape collection. The milestones below show the development of the project from initial client pitch, to functional prototype, to final client report.

## Project Milestones

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)

---

## Client Pitch

<p align="center">
  <b>Problem Statement</b>
</p>

During mechanical grape harvest, spotted lantern flies (SLF) remain on the vines and can be collected with the fruit, contaminating loads. Even minimal contamination is unacceptable: as few as 1–2 SLFs (~0.5–1 g each) can contaminate a 1000 g core sample, triggering shipment rejection. With deliveries occurring every 10 minutes at roughly 22 tons per load, a single rejected shipment results in substantial product loss, contributing to an estimated $14.3 million of damages across the Lake Erie and Finger Lakes regions in the first three years of infestation. Current solutions, such as chemical treatments or post-harvest separation, are either ineffective during active harvest, reduce yield, or are operationally inefficient. The challenge is therefore to deter SLF from vines before or during harvest, or to separate them from harvested material, without damaging grape quality or reducing yield.

---

<p align="center">
  <b>Why This Matters to the End-User</b>
</p>

Solving this problem would allow vineyards to avoid yield loss from post-harvest washing, reduce SLF contamination in harvested loads, and eliminate the need for additional chemical treatments during a critical harvest window. By preventing shipment rejections and harvest slowdowns, the solution would preserve grape quality, protect the winery’s reputation, and reduce significant economic losses.

---

<p align="center">
  <b>Proposed Directions</b>
</p>

**Smoke Machine Attached to Harvester** — Attach a smoke (or similar gas) delivery system to the front of the harvester to temporarily deter SLFs from the vines immediately before harvest. The goal is to use a non-lethal substance to clear the vines without relying on pesticides, potentially by rerouting harvester exhaust or using a small gas canister with forward-facing nozzles. We would prototype with a canister connected to two spray nozzles with an attachment mechanism to the harvester. Key risks/unknowns include whether SLFs will consistently fly away when exposed to smoke or exhaust, whether exposure could affect grape quality, and whether harvesters have sufficient space and power capacity to support the system. These factors would require rigorous prototyping and testing.

**Bristles as a Filter** — Install a system of brush bristles along the inner conveyor of the harvester to mechanically filter SLFs from grapes immediately after harvest. The bristles would comb over the harvested material, allowing grapes and juice to pass while removing SLFs from the harvest. We would prototype this by designing a brush and running it over grapes with flour or another substance on them. Key risks/unknowns include whether the bristles can reliably filter out SLFs without blocking or damaging grapes, and whether they are durable enough for long-term use. Effective implementation would require experimentation with bristle density and spacing.

---

<p align="center">
  <b>Our Questions</b>
</p>

* **Will SLF consistently disperse when exposed to smoke or exhaust?** — Determines whether or not we move forward with the gas or bristle solution.
* **Are there grape regulatory or flavor concerns regarding smoke or gas exposure?** — Clarifies feasibility of the smoke solution, ensuring regulations and flavor are not compromised.
* **Given a known deterrent, how long will it take for SLFs to return to the vines?** — Important for designing the potency, speed, and distribution of our solution.
* **What are the constraints to the modification of the harvester?** — Ensures feasibility of attaching a tank to the front of the harvester.
* **Is there space in the internal compartment of most grape harvesters to add enough bristles to be an effective filter?** — Determines whether we move forward with the bristle solution.

---

<p align="center">
  <b>Works Cited</b>
</p>

Bekelja, K., & Russo, J. *Spotted Lanternfly Discussion*. Zoom meeting recording, MAE 2250, Spring 2026.

Cornell University. “Spotted SLFs Could Cost NYS Grape Industry Millions.” *Cornell Chronicle*, January 2025.  
https://news.cornell.edu/stories/2025/01/spotted-SLFs-could-cost-nys-grape-industry-millions

---

## Functional Prototype

### Purpose

The purpose of this prototype is to test a gear-driven mechanism that enables controlled rotation of a gas dispersion nozzle, allowing for directional dispersal of gas to deter spotted lanternflies during mechanical harvesting.

---

### Design Tests

#### Test 1: Rotation Smoothness  
**Part tested:** Gears  
**What it tests for:** Whether the handle-driven gears rotate the nozzle smoothly without binding, slipping, or excessive friction  
**How we tested it:** Handle was rotated through desired range of motion while observing gear motion and checking for slip, jerky motion, or interference  
**Test results:** Before applying constraints to the range of motion, we rotated the gears through 20 full rotations of 360 degrees. Throughout the test, there was no slippage or binding of the gear teeth.  
**Conclusion for next iteration:** While we did not see any slipping/binding, we noted that the gears must be perfectly placed to achieve that. To provide slight room for error, if we re-fabricate the gears we will increase the gear tooth height by 5mm.  

---

#### Test 2: Aiming Range  
**Part tested:** Tube/Nozzle  
**What it tests for:** Whether gear system allows tube/nozzle to rotate through motion required to cover desired volumetric space by the gas  
**How we tested it:** Handle was turned from one extreme to the other and total angular rotation of the nozzle was measured  
**Test results:** The gear system completed 10 full back-and-forth cycles. With the constraints we applied, we achieved a range of motion of 90 degrees. There were 0 instances of slipping or binding by the gear teeth during the test, and the nozzle was able to achieve the range of motion without exhibiting any significant stress.  
**Conclusion for next iteration:** Our method of constraining the gears was effective. However, to make the design more robust, we will increase the diameter of the wooden cylinder constraints and use an aluminum base instead of wood.  

---

#### Test 3: Repeated-Use Durability  
**Part tested:** Screws/Gears/Wooden Board assembly  
**What it tests for:** If mechanism maintains functionality after repeated use without loosening, slipping, or increasing friction  
**How we tested it:** Handle was cycled at a minimum of 20 times while observing changes in motion smoothness, gear interface, and structural stability  
**Test results:** We cycled the gear through 20 full cycles at 20 RPM once the design was fully constructed, including constraints. The design held up with no clear signs of wear and tear.  
**Conclusion for next iteration:** While our initial design holds up, it is primarily constructed out of cheap wood and tape, meaning that it will lose significant strength over time. For our final design, we will convert the constraint shafts and the base to aluminum. We will also use screws to keep the gears in place instead of wooden sticks.  

---

#### Test 4: Tube Stability  
**Part tested:** Pipe Clamp  
**What it tests for:** Whether gas tube remains securely attached and doesn’t interfere with nozzle rotation during operation  
**How we tested it:** Rotate tube through full range of motion while observing clamps, checking for twisting, sagging, or resistance to rotation  
**Test results:** We were not able to directly test this due to our clamp ordering issue. However, we used painter’s tape, which is significantly weaker than clamps, and it held through ~20 full cycles at varying speeds without failure.  
**Conclusion for next iteration:** We are confident that once we have the correct clamps, they will be strong enough to hold our tube and handle down to demonstrate functionality of our design.  

---

#### Test 5: Structural Stability  
**Part tested:** Wood Mounting Board  
**What it tests for:** If wooden base remains rigid and maintains gear alignment during use  
**How we tested it:** Handle was rotated repeatedly while checking for board flexing, shifting, or misalignment of the gears  
**Test results:** We rotated the board through 10 full cycles at 20 RPM while applying a 10 N load. The base exhibited no flexing or bending, and the gears remained aligned with no slippage.  
**Conclusion for next iteration:** While the base performed well, we will use an aluminum base in the next iteration to improve long-term durability.  

---

### Success Criteria

Our main goal of this iteration is to ensure our gear rotation system for gas dispersion is effective and durable.

- After repeated testing (>1 minute), gears must rotate at least 90° without interference or skipping  
- All parts must remain structurally intact under repeated use  
- The nozzle must maintain ~90° range of motion without significant resistance  

---

### Demo

Upon spinning the handle, the nozzle rotates with a 90-degree range of motion due to the smooth interaction of the spur gears, demonstrating controlled directional gas dispersion.

---

[📄 **View Full Functional Prototype Report (PDF)**]({{ '/assets/MAE_2250_5_Functional Prototype.pdf' | relative_url }})

---

## Client Report

### Context & Problem 

Spotted Lantern Flies are wreaking havoc on the wine industry by contaminating grape harvests at a devastating scale. To address this issue, our team focused specifically on preventing SLFs from contaminating the harvest by deterring them during grape collection. This stage of the harvesting process represents a critical control point, where even small reductions in SLF presence can significantly reduce the risk of wasting thousands of pounds of grapes.

We chose to focus on pre-harvest and in-process mitigation rather than broader population control because it offers a more immediate and controllable intervention that can be integrated directly into existing harvesting operations. At this point, we believe that seeking to eliminate the SLF population is a much larger issue both in scale and timeline, and we wanted to enable clean harvests now.

Several key constraints shaped our design: it needed to operate in real time alongside harvesting equipment, avoid disrupting current operations, remain low-cost and mechanically simple, and ensure safety for both grapes and workers. These constraints led us to prioritize a solution that targets SLFs just before or during harvest without requiring major changes to existing systems.

### Final Prototype & Application

Our team developed a directional nozzle system designed to deter SLFs immediately prior to grape collection. The system uses a gear-driven mechanism connected to a handle, allowing the user to control the orientation of the nozzle to disperse gas across a larger area of the grape vine. Our device, when placed into commission, will be attached to the front of the grape harvester to dispel gas into the harvesting chamber. When operated, the nozzle will emit lanternfly-deterrent gas intended to disturb and displace SLFs from the vine just before the harvester passes over the grapes and collects them. The oscillating gas distribution system ensures that the most lanternflies possible are repelled away from the grapes immediately before harvest.

In practice, this system would be integrated into existing harvesting equipment and connected to a servo motor. This system would allow an operator to harvest as normal, while gas is automatically dispersed once the system is activated due to the servo motor. This allows SLFs to be removed at the point of harvest without interrupting the harvesting process or requiring significant changes to current operations. The low-hassle implementation of our product is intended to create minimal impact on farmers and keep installation and maintenance costs low. 

To test our design, we made a simple mock-up out of metal and 3D printed gears. This system demonstrates the gear mechanism to disperse gas into the grape collection chamber. Although on a final design our system would be actuated by a servo motor, for our final prototype, we determined it sufficient for there to be a handle on one of the gears to mimic the motion the servo motor would provide. Images of the device are provided in the following figures. 

### Conclusion & Recommendation

Our design so far has been promising and warrants further exploration. Firstly, tests should be conducted to determine a gas that effectively repels lanternflies from the grapes being harvested. It is important to keep in mind when choosing this gas that it could affect harvest quality. It is also critical to consider the availability and cost of the gas to have minimal impact on the farmers implementing this system. Once a gas is decided, field testing can begin with two mechanical systems mounted on either side of the grape harvester, each dispersing the selected gas into the grape harvesting chamber. It is important to keep in mind that in implementation, our mechanical design will be regulated by two servo motors to control the gear actuation and gas dispersal. 

We believe our design is feasible due to the proven effectiveness of the mechanical portion. Testing showed that after 50 full rotation cycles, the gears continued to rotate smoothly without slipping or disengaging, the tube remained securely mounted without interfering with motion, and the aluminum base maintained structural stability and gear alignment throughout operation. These results indicate that the core mechanism is reliable enough to withstand repeated use in a harvesting environment and can be integrated into existing equipment with minimal redesign.

Our successful testing, along with the fact that our design is relatively cheap, mechanically reliable, and easy to implement, means that once a gas is fully fleshed out after some further testing, our design is ready for rapid field testing and implementation on grape farms across the Northeast.

### Key Testing Results

To evaluate whether this concept is practical for vineyard implementation, we tested the most important mechanical risks: rotational reliability, tubing security, and structural rigidity.

The gear-driven rotation system was tested through 50 full operating cycles across an approximately 90° range of motion. Throughout testing, the gears rotated continuously without observable slipping, disengagement, or excessive friction. This indicates that the mechanism can provide consistent repeated nozzle positioning during harvest operations.

The tube mounting system was also tested through 50 full cycles while monitoring for twisting, sagging, or resistance to motion. The tube remained securely attached and did not interfere with nozzle rotation. This suggests the gas delivery system can remain stable during repeated use and is suitable for future powered actuation.

The aluminum mounting base was evaluated for structural stability and alignment retention. After repeated cycling, the base showed no visible flexing, shifting, or gear misalignment. This confirms the supporting structure is rigid enough to maintain reliable operation under normal use.

Finally, flow rate and volume loss. We conducted 2 different experiments: one at a fixed angle and one rotating the nozzle from -45 degrees to 45 degrees, while collecting data on flow rate and efficiency. When testing the flow rate of a fixed nozzle, we noticed an average flow rate of 38.19 mL/s. Starting at 1000 mL, we lost, on average, 61.8 mL, or about 6.2% of the original volume. When testing the flow rate with the rotating nozzle, it has an average flow rate of 29.32 mL/s. Starting at 1000 mL, we lost, on average, 130.2 mL, about 13% of the original volume.

Overall, testing demonstrated that the core mechanical system is low-cost, repeatable, and structurally sound, supporting progression to powered prototypes and field testing.

### Prototype and Testing Details

Our prototype was developed as a simple proof of concept to demonstrate the mechanical feasibility of directing deterrent gas across the grape harvesting chamber. The system was constructed using an aluminum mounting base, two large 3D-printed gears, a manual handle, a rubber tube to represent the gas delivery line, and pipe clamps used to secure the tube to the rotating gear.

The aluminum base was used to support the gear shafts and maintain alignment between the driving and driven gears. A handle was attached to the lower gear so that manual rotation could mimic the powered motion that would be produced by a servo motor in a final implementation. As the lower gear rotates, it drives the upper gear, causing the attached tube and nozzle to sweep through the intended range of motion.

The tube was mounted to the upper gear using clamps positioned to keep the tube secure while still allowing smooth rotation. This setup was chosen to represent how a future gas line could be integrated into the system while maintaining directional control of the nozzle. The prototype was intentionally made using simple, low-cost components in order to validate the concept before investing in powered hardware or field-ready materials.

Testing focused on repeated operation of the gear mechanism, tube stability during motion, and structural stability of the base. The handle was rotated repeatedly through the intended range of motion while observing for slipping, binding, interference, or shifting of components. Minor adjustments were made during assembly to improve gear alignment and maintain smooth operation.

In a final design, the manual handle would be replaced by servo motors integrated with the harvesting system, and the prototype materials would be replaced with more durable components suitable for repeated outdoor agricultural use.


[📄 **View Full Client Report (PDF)**]({{ '/assets/ODP 6_ Client Report.pdf' | relative_url }})