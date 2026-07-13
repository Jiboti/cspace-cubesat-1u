<h1 align="center">🛰️ C'space CubeSat 1U — "Boîte Noire"</h1>
<h4 align="center">Onboard black-box CubeSat for an experimental rocket — C'Space campaign (CNES / Planète Sciences)</h4>



> ⚠️ **Work in progress & competition project.** This CubeSat is still under active development as part of a national competition. To protect the team's technical know-how, this page stays at a general level — exact measurements, detailed schematics and precise flight data are intentionally not disclosed.

---

## 📋 Context — The C'Space campaign

C'Space is a national campaign run by **Planète Sciences** in partnership with the **CNES** (French space agency), gathering student teams each year around experimental rocket projects. It frames a complete space project — from design to flight — through technical reviews and rigorous testing phases.

I am part of the **CubeSat "Boîte Noire" (Black Box)** team from LéoFly.

## 🛰️ The mission

The CubeSat Boîte Noire belongs to the rocket's **experiments** section. Experiments are independent compartments, each dedicated to a specific task such as data collection, computing the rocket's rotation, and so on.

<p align="center">
  <img src="images/experiences.jpg" alt="Experiments section of the rocket" width="500"/>
</p>

It operates throughout the whole flight, from liftoff to landing. Its role is to **securely record** the rocket's velocity, GPS position and telemetry data, and to drive a **buzzer signal** used to locate the rocket after touchdown.

In the flight chain, it is active from initialization before liftoff and stays operational all the way to the ground, interfacing with:

- the **CubeSat rack** — for mechanical support and power,
- the **battery rack** — through the BMS,
- the **sequencer** — at the moment of separation.

It also serves as a **test bench** for the systems of the future **ASTRA-AP** rocket.

<p align="center">
  <img src="images/chaine-de-vol.jpg" alt="Flight-chain integration" width="500"/>
</p>

## 🔧 What we did

With the CubeSat team, we started by **modeling the complete solution** in CAD. After running **MATLAB simulations**, we used the results to **rearrange the internal layers into the most optimal configuration**.

<p align="center">
  <img src="images/simulation-matlab.jpg" alt="MATLAB simulation results" width="500"/>
</p>

This iterative process led us to the **final assembly**.

<p align="center">
  <img src="images/assemblage-final.jpg" alt="Final CubeSat assembly" width="500"/>
</p>

## 🛠️ Tools & technologies

`CATIA` · `MATLAB` · `Arduino` · `C++`

---

<p align="center"><a href="https://github.com/Jiboti">⬅️ Back to profile</a></p>
