---
layout: project
title: Lantern Fly Eradication Unit
image: /assets/images/SLF.jpg
---

<p align="center">
  <b>Reducing Spotted Lanternfly Contamination During Mechanical Grape Harvest</b><br>
  <b>Lantern Fly Eradication Unit</b>
</p>

## Project Milestones

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)

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