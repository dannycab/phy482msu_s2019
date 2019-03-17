---
layout: slide
theme: white
transition: slide
---

<section data-markdown>
For a wave on a 1d string that hits a boundary between 2 strings of different material we get,

$$\widetilde{f}(z<0) = \widetilde{A}_I e^{i(k_1)z-\omega t} + \widetilde{A}_Re^{i(-k_1z-\omega t)}$$
$$\widetilde{f}(z>0) = \widetilde{A}_T e^{i(k_2)z-\omega t}$$

where continuity (BCs) give,

$$\widetilde{A}_R = \left(\dfrac{k_1-k_2}{k_1+k_2}\right)\widetilde{A}_I$$
$$\widetilde{A}_T = \left(\dfrac{2k_1}{k_1+k_2}\right)\widetilde{A}_I$$

Is the transmitted wave in phase with the incident wave?

A) Yes, always B) No, never C) Depends

Note:
* Correct answer: A

</section>

<section data-markdown>
For a wave on a 1d string that hits a boundary between 2 strings of different material we get,

$$\widetilde{f}(z<0) = \widetilde{A}_I e^{i(k_1)z-\omega t} + \widetilde{A}_Re^{i(-k_1z-\omega t)}$$
$$\widetilde{f}(z>0) = \widetilde{A}_T e^{i(k_2)z-\omega t}$$

where continuity (BCs) give,

$$\widetilde{A}_R = \left(\dfrac{k_1-k_2}{k_1+k_2}\right)\widetilde{A}_I$$
$$\widetilde{A}_T = \left(\dfrac{2k_1}{k_1+k_2}\right)\widetilde{A}_I$$

Is the reflected wave in phase with the incident wave?

A) Yes, always B) No, never C) Depends

Note:
* Correct answer: C
* Can be 180 out of phase

</section>

<section data-markdown>

An electromagnetic plane wave propagates to the right.  Four vertical antennas are labeled 1-4. 1, 2, and 3 lie in the $x-y$ plane.  1, 2, and 4 have the same $x$-coordinate, but antenna 4 is located further out in the $z$-direction.
Rank the time-averaged signals received by each antenna.

<img src="./images/EM_waves_antenna.png" align="right" style="width: 700px";/>

1. 1=2=3$>$4
2. 3$>$2$>$1=4
3. 1=2=4$>$3
4. 1=2=3=4
5. 3$>$1=2=4

Note:
* Correct Answer: D

</section>

<section data-markdown>

A point source of radiation emits power $P_0$ isotropically (uniformly in all directions).  A detector of area $a_d$ is located a distance $R$ away from the source.  What is the power $P_d$ received by the detector?

<img src="./images/detector_spherical.png" align="right" style="width: 300px";/>


1. $\frac{P_0}{4\pi R^2}a_d$
2. $P_0\frac{a_d^2}{R^2}$
3. $P_0\frac{a_d}{R}$
4. $\frac{P_0}{\pi R^2}a_d$
5. None of these

Note:
* Correct Answer: A

</section>

<section data-markdown>

In matter we have,

$$\nabla \cdot \mathbf{D} = \rho_f \qquad \nabla \cdot \mathbf{B} = 0$$
$$\nabla \times \mathbf{E} = -\dfrac{\partial \mathbf{B}}{\partial t} \qquad \nabla \times \mathbf{H} = \mathbf{J}_f + \dfrac{\partial \mathbf{D}}{\partial t}$$
with
$$\mathbf{D} = \varepsilon_0 \mathbf{E} + \mathbf{P} \qquad \mathbf{H} = \mathbf{B}/\mu_0 - \mathbf{M}$$

If there are no free charges or current, is $\nabla \cdot \mathbf{E} = 0$?

1. Yes, always
2. Yes, under certain conditions (what are they?)
3. No, in general this will not be true
4. ??

Note:
* Correct answer: B
</section>

<section data-markdown>

In linear dielectrics, $\mathbf{D} = \varepsilon_0\mathbf{E} + \mathbf{P} = \varepsilon \mathbf{E}.$ In a linear dielectric is $\varepsilon > \varepsilon_0$?

1. Yes, always
2. No, never
3. Sometimes, it depends on the details of the dielectric.

Note:
* Correct answer: A

</section>

<section data-markdown>

In a non-magnetic, linear dielectric,

$$v = \dfrac{1}{\sqrt{\mu \varepsilon}} = \dfrac{1}{\sqrt{\mu \varepsilon_r \varepsilon_0}} = \dfrac{c}{\sqrt{\varepsilon_r}}$$

How does $v$ compare to $c$?

1. $v>c$ always
2. $v<c$ always
3. It depends

Note:
* Correct Answer: B

</section>

<section data-markdown>

A light rope (small $m/L$) is fused to a heavy rope (large $m/L$). If I wiggle the **light** rope,

1. most of the wiggles are reflected back; very few wiggles transmit through the heavy rope
2. some of the wiggles are reflected back; some of the wiggles transmit through the heavy rope
3. very few of the wiggles are reflected back; most of the wiggles transmit through the heavy rope
4. ???

Note:
* Correct answer: A

</section>

<section data-markdown>

A light rope (small $m/L$) is fused to a heavy rope (large $m/L$). If I wiggle the **heavy** rope,

1. most of the wiggles are reflected back; very few wiggles transmit through the light rope
2. some of the wiggles are reflected back; some of the wiggles transmit through the light rope
3. very few of the wiggles are reflected back; most of the wiggles transmit through the light rope
4. ???

Note:
* Correct answer: B/C

</section>

<section data-markdown>

How do the speed of the waves compare in the light rope ($v_l$) and heavy rope ($v_H$)?

1. $v_l < v_H$
2. $v_l = v_H$
3. $v_l > v_H$

Note:
* Correct Answer: C

</section>

<section data-markdown>
For our reflected and transmitted waves, how many unknowns have we introduced?

$$\mathbf{E}_R = \widetilde{E_R}e^{i(k_Rz-\omega_Rt)}\hat{n}_R$$
$$\mathbf{E}_T = \widetilde{E_T}e^{i(k_Tz-\omega_Tt)}\hat{n}_T$$

1. 2
2. 4
3. 8
4. 12
5. None of the above

Note:
* Correct answer: D
* It's about 12.

</section>

<section data-markdown>
For our reflected and transmitted waves, how many unknowns have we introduced?

$$\mathbf{E}_R = \widetilde{E_R}e^{i(k_Iz-\omega_It)}\hat{n}_I$$
$$\mathbf{E}_T = \widetilde{E_T}e^{i(k_Tz-\omega_It)}\hat{n}_I$$

1. 2
2. 4
3. 8
4. 12
5. None of the above

Note:
* Correct answer: A

</section>

<section data-markdown>

An EM wave is normally incident on a boundary between two materials ($n_1 \ll n_2$). If the incident wave starts in **material 1**,

1. most of the wave is reflected back; very little of the wave transmits through material 2
2. some of the wave is reflected back; some of the wave transmits through material 2
3. very little of the wave is reflected back; most of the wave transmits through material 2
4. ???

Note:
* Correct Answer: A

</section>

<section data-markdown>

An EM wave is normally incident on a boundary between two materials ($n_1 \ll n_2$). If the incident wave starts in **material 2**,

1. most of the wave is reflected back; very little of the wave transmits through material 1
2. some of the wave is reflected back; some of the wave transmits through material 1
3. very little of the wave is reflected back; most of the wave transmits through material 1
4. ???

Note:
* Correct Answer: A

</section>

<section data-markdown>

An EM wave is normally incident on a boundary between two materials ($n_1$ is close to $n_2$). If the incident wave starts in **material 1**,

1. most of the wave is reflected back; very little of the wave transmits through material 1
2. some of the wave is reflected back; some of the wave transmits through material 1
3. very little of the wave is reflected back; most of the wave transmits through material 1
4. ???

Note:
* Correct Answer: C

</section>
