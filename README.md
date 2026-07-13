<h1 align="center">🛰️ C'space CubeSat 1U — "Boîte Noire"</h1>
<h4 align="center">Onboard black-box CubeSat for an experimental rocket — C'Space campaign (CNES / Planète Sciences)</h4>



> ⚠️ **Work in progress & competition project.** This CubeSat is still under active development as part of a national competition. To protect the team's technical know-how, this page stays at a general level — exact measurements, detailed schematics and precise flight data are intentionally not disclosed.

---

## 📋 Context — The C'Space campaign

C'Space is a national campaign run by **Planète Sciences** in partnership with the **CNES** (French space agency), gathering student teams each year around experimental rocket projects. It frames a complete space project — from design to flight — through technical reviews and rigorous testing phases.

I am part of the **CubeSat "Boîte Noire" (Black Box)** team from LéoFly.

## 🛰️ The mission

The CubeSat Boîte Noire belongs to the rocket's **experiments** section. Experiments are independent compartments, each dedicated to a specific task such as data collection, computing the rocket's rotation, and so on.

<img width="567" height="163" alt="Image" src="https://github.com/user-attachments/assets/2e06b269-d366-4219-b36b-aa9c7f32b415" />


It operates throughout the whole flight, from liftoff to landing. Its role is to **securely record** the rocket's velocity, GPS position and telemetry data, and to drive a **buzzer signal** used to locate the rocket after touchdown.

In the flight chain, it is active from initialization before liftoff and stays operational all the way to the ground, interfacing with:

- the **CubeSat rack** — for mechanical support and power,
- the **battery rack** — through the BMS,
- the **sequencer** — at the moment of separation.

It also serves as a **test bench** for the systems of the future **ASTRA-AP** rocket.

<img width="521" height="283" alt="Image2" src="https://github.com/user-attachments/assets/ee7bcb32-c879-4f1a-ae95-ac75197668a5" />
<img width="720" height="302" alt="image" src="https://github.com/user-attachments/assets/072413cb-4eec-4803-a72f-eb1727c2d653" />


I joined the team at the start of the second semester, after a semester abroad. A first functional version of the mechanical parts had already been modeled, but the RCE 1 design review had shown that it did not yet meet all the required constraints. The objective was therefore reset around a clear goal: remodel and optimize the existing layers so the assembly would fully comply with the 1U format and integrate cleanly into the CubeSat rack.

The approach was deliberately iterative — start from the existing version, identify the non-conformities, then remodel and optimize the parts concerned. In practice, the work went through a few main stages:


Onboarding — regular exchanges with the team to establish a precise picture of the project and define priorities.
Layer recalculation — reworking the internal stack-up so the electronic board integrates correctly into the rack, while accounting for the fixed thickness of the mechanical protection layers.
Rack redesign — the biggest structural change: consolidating the electronics from several boards down to a single one, which let us rebuild the rack from three shelves to one — freeing up space and simplifying the mechanical fixation.
Design review (RCE 1) — preparing the technical presentation to formalize the progress made and gather feedback for the next steps.

In parallel, we ran MATLAB simulations to justify the shock-absorption strategy across the key flight phases (static, liftoff and landing). The modeling was itself instructive: it exposed the limits of a simplified 1D approach and pushed us to ground the final design choice in the physical crush behavior of the damping material rather than on the simulation alone — a good reminder that the model is a tool to reason with, not a proof on its own.

<img width="210" height="479" alt="Image3" src="https://github.com/user-attachments/assets/9ad5711f-8f54-4d1f-a64e-c51a9403dda5" />


This whole process — mechanical CAD/CAM in Fusion 360, custom PCB design in KiCad, and numerical simulation in MATLAB — led us to a more compact, better-optimized configuration and, ultimately, to the final assembly.

<img width="1520" height="842" alt="Assemblage CubeSat Insh v15" src="https://github.com/user-attachments/assets/5e8a03f2-a235-43ce-af19-57ebdfb51ba1" />


## 🛠️ Tools & technologies

`Fusion` · `MATLAB` · `Arduino` .

---

<p align="center"><a href="https://github.com/Jiboti">⬅️ Back to profile</a></p>
