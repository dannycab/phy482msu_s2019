---
layout: slide
theme: white
transition: slide
---


<section data-markdown>

**Claim:** For a wave heading towards a boundary between two media at an oblique angle, $\omega_I = \omega_R = \omega_T$.

1. True
2. False

Note:
* Correct Answer: A
* All are the same

</section>

<section data-markdown>

## Announcements

* Quiz 5 (this Friday)
  * Construct the expression for plane wave given a description
    * Both complex and real expressions
  * Combine two plane waves and describe the resulting superposed wave
  * Think: Problem 2 on HW 8

</section>

<section data-markdown>

**Claim:** For a wave heading towards a boundary between two media at an oblique angle, at the boundary, $\mathbf{k}_I\cdot\mathbf{r} = \mathbf{k}_R\cdot\mathbf{r} \neq \mathbf{k}_T\cdot\mathbf{r}$.

1. True
2. False

Note:
* Correct Answer: B
* All are equal

</section>

<section data-markdown>

An EM wave passes from air to metal, what does **your intution** say happens to the wave in the metal?

1. It will be amplified because of free electrons
2. It will die out over some distance
3. It will be blocked right at the interface because there's no E field in a metal
4. Not sure

</section>

<section data-markdown>

An EM wave passes from air to metal, which do you think is **most likely** the physics will give us?

1. It will be amplified because of free electrons
2. It will die out over some distance
3. It will be blocked right at the interface because there's no E field in a metal
4. Not sure

</section>


<section data-markdown>

Suppose I stick some charge $\rho_f$ down somewhere in a metal (with conductivity $\sigma$). What does $\rho(t)$ look like if we can invoke Ohm's law ($\mathbf{J} = \sigma \mathbf{E}$)? *Hint: Think about charge conservation.*

1. $\rho(t) = \rho_f \sin(\sigma t/\varepsilon_0)$
2. $\rho(t) = \rho_f \cos(\sigma t/\varepsilon_0)$
3. $\rho(t) = \rho_f e^{-\sigma t/\varepsilon_0}$
4. $\rho(t) = \rho_f e^{-\varepsilon_0 t/\sigma}$
5. Something else

Note:
* Correct Answer: C

</section>

<section data-markdown>

Consider a good conductor ($\sigma \sim 10^8$ S/m), how long roughly does it take for free charge to dissipate ($t \sim \varepsilon_0/\sigma$)?

1. 10$^{-19}$s
2. 10$^{-12}$s
3. 10$^{-8}$s
4. 10$^{12}$s
5. Something else

Note:
* Correct Answer: A

</section>

<section data-markdown>

Given our estimates of collision times (10$^{-14}$s), for what kinds of light is our analysis not so great for?

1. X-Rays ($\sim 10^{18}$ Hz)
2. Visible light ($\sim 10^{15}$ Hz)
3. IR ($\sim 10^{13}$ Hz)
4. Radio ($\sim 10^{8}$ Hz)
5. More than one of these

Note:
* Correct Answer: E (it's A and B)

</section>

<section data-markdown>

What does this ansatz attempt (i.e., using $\sim e^{(kz-i\omega t)}$) remind you for this?

1. Solving the simple harmonic oscillator
2. Solving the damped harmonic oscillator
3. Solving the driven harmonic oscillator
4. Some other set up

Note:
* Correct Answer: is likely B

</section>

<section data-markdown>

With the proposed solution, $\widetilde{\mathbf{E}} = \widetilde{\mathbf{E}}_0 e^{i(kz-\omega t)}$, what equation does $k$ satisfy?

Think about the wave equation: $\nabla^2 \mathbf{E} = \mu \sigma \dfrac{\partial \mathbf{E}}{\partial t}+\mu \varepsilon \dfrac{\partial^2 \mathbf{E}}{\partial t^2}$

1. $k^2 = i \omega \mu \sigma + \omega^2 \sigma \varepsilon$
2. $k^2 = \omega \mu \sigma + i \omega^2 \sigma \varepsilon$
3. $k = \omega \mu \sigma + i \omega^2 \sigma \varepsilon$
4. $k = i \omega \mu \sigma + \omega^2 \sigma \varepsilon$
5. Something else

Note:
* Correct Answer: A

</section>

<section data-markdown>

What is the $\sqrt{i}$?

1. -$i$
2. $\frac{1+i}{\sqrt{2}}$
3. -1
4. $e^{i\pi/4}$
5. None or more than one of these

Note:
* Correct Answer: E (B and D)

</section>

<section data-markdown>

An EM wave passes from air to metal, what happens to the wave in the metal?

1. It will be amplified because of free electrons
2. It will die out over some distance
3. It will be blocked right at the interface because there's no E field in a metal
4. Not sure

</section>

<section data-markdown>

We found a traveling wave solution for the conductor situation,

$$\widetilde{\mathbf{E}}(\mathbf{r},t) = \widetilde{\mathbf{E}}_0e^{i(\widetilde{k}z-\omega t)}$$

where $\widetilde{k} = \omega^2\mu \varepsilon + i(\omega \mu \sigma)$

True (A) or False (B): This traveling wave is transverse.

(C) I'm not sure.

Note:
* Correct Answer: A
* Comes from divergence

</section>

<section data-markdown>
The magnetic field amplitude in a metal associated with a linearly polarized electric EM wave is:

$$\widetilde{B}_0 = \left(\dfrac{k_R+ik_I}{\omega}\right)\widetilde{E}_0$$

True (A) or False (B): The B field is in phase with the E field.

(C) It depends!

Note:
* Correct Answer: B

</section>

<section data-markdown>
The magnetic field amplitude in a highly conductive metal  ($\sigma \gg \varepsilon \omega$) associated with a linearly polarized electric EM wave is

$$\widetilde{B}_0 = \sqrt{\dfrac{\mu \sigma}{\omega}}\dfrac{1+i}{\sqrt{2}}\widetilde{E}_0$$
$$\widetilde{B}_0 = \sqrt{\dfrac{\sigma}{\varepsilon_0 \omega}}\dfrac{1+i}{\sqrt{2}}\dfrac{\widetilde{E}_0}{c}$$

True (A) or False (B): The B field is in phase with the E field.

(C) It depends!

Note:
* Correct Answer: B

</section>
