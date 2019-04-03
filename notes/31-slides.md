---
layout: slide
theme: white
transition: slide
---

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

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-vt)}dk$ where $v$ is a known constant, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something complicated!
5. ???

Note:
* Correct Answer: C

</section>

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-vt)}dk$ where $v$ is a known constant, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something complicated!
5. ???

Note:
* Correct Answer: C

</section>

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-v(k)t)}dk$ where $v(k)$ is function, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something more complicated!
5. ???

Note:
* Correct Answer: D

</section>

<section data-markdown>

Last class, we found that the wave packet that we constructed from a Gaussian distribution of $k$'s centered around $k_0$ was,

$$f(x) = e^{-x^2/4\sigma} e^{-ik_0x}$$

Sketch this wave packet.

</section>

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-vt)}dk$ where $v$ is a known constant, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something complicated!
5. ???

Note:
* Correct Answer: C

</section>

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-v(k)t)}dk$ where $v(k)$ is function, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something more complicated!
5. ???

Note:
* Correct Answer: D

</section>

<section data-markdown>

**True or False:** EM Waves can have velocities higher than $c$.

1. True
2. False
3. I don't know what to believe anymore

Note:
* Correct answer: A

</section>

<section data-markdown>

Given two waves, $f_1(t) = A \cos (\omega_1 t)$ and $f_2(t) = A \cos (\omega_2 t)$, let's propose an average frequency: $\omega_a = \frac{1}{2}(\omega_1+\omega_2)$ and a modulation frequency: $\omega_m = \frac{1}{2}(\omega_1-\omega_2)$. How can you write $\omega_1$ and $\omega_2$ in terms of these frequencies?

1. $\omega_1 = \omega_a - \omega_m \qquad \omega_2 = \omega_a + \omega_m$
2. $\omega_1 = \omega_a + \omega_m \qquad \omega_2 = \omega_a - \omega_m$
3. $\omega_1 = \frac{\omega_a + \omega_m}{2} \qquad \omega_2 = \frac{\omega_a - \omega_m}{2}$
4. $\omega_1 = \frac{\omega_a - \omega_m}{2} \qquad \omega_2 = \frac{\omega_a + \omega_m}{2}$
5. None of these

Note:
* Correct Answer: B

</section>

<section data-markdown>

Given two waves, $f_1(t) = A \cos (\omega_1 t)$ and $f_2(t) = A \cos (\omega_2 t)$, which of the following correspond to the total wave, $f_T(t)$?

1. $A \cos (\omega_1 t) + A \cos (\omega_2 t)$
2. $A^2 \cos (\omega_1 t) \cos (\omega_2 t)$
3. $2A \cos ((\omega_1+\omega_2) t)\cos((\omega_1-\omega_2)t)$
4. $2A \cos (\frac{(\omega_1+\omega_2)}{2} t)\cos(\frac{(\omega_1-\omega_2)}{2} t)$
5. More than one of these

Note:
* Correct Answer: E (it's A and D)


</section>

<section data-markdown>

For our atomic model of permittivity we found $\widetilde{\varepsilon}$ to be

$$\widetilde{\varepsilon} = \varepsilon_0\left(1+\dfrac{Nq^2}{\varepsilon_0 m}\sum_i \dfrac{f_i}{(\omega_i^2-\omega^2)-i\gamma_i\omega}\right)$$

We also know that $\dfrac{n}{c} = \dfrac{\widetilde{k}}{\omega} = \sqrt{\widetilde{\varepsilon}\mu}.$
* Find (and simplify) a formula for $n$, assuming the term adding to "1" above is small.
* In that limit, find $k_R$ and $k_I$. What does each one tell you, physically?
* Sketch both of these as functions of $\omega$ (assuming that only one term in that sum "dominates")

</section>

<section data-markdown>

Two major results of special relativity are Time Dilation and Lorentz Contraction. Please pick one of the choices below which best describes how well you feel you understand them.

1. No idea what these effects are
2. I remember having heard about these, but couldn't define them precisely right now.
3. I know what these effects are, (but I've forgotten how to derive them)
4. I know what these effects are, and I even sort of remember the derivation, but it would take me a while to sort it out
5. I'm confident I could derive these results right now

</section>


<section data-markdown>

## Announcements

* Quiz 6 (This Friday)
  * Given two infinite plane waves at different frequencies, determine the resulting wave in a "good conductor"
  * Sketch the waves in free space and in the conductor
  * Discuss the implications from your analysis
* Poster rubric will be posted this week

</section>

<section data-markdown>

You are standing next to a conveyer belt that is transporting a baby (don't ask questions) at 1 m/s **to the right**. The baby is crawling at **2 m/s to the right**. What is the velocity of the baby in your frame?

1. 1 m/s to the left
2. 1 m/s to the right
3. 3 m/s to the right
4. 3 m/s to the left
5. Something else

Note:
* Correct Answer: C

</section>

<section data-markdown>

You are standing next to a conveyer belt that is transporting a baby (don't ask questions) at **1 m/s to the right**. The baby is crawling at **2 m/s to the left**. What is the velocity of the baby in your frame?

1. 1 m/s to the left
2. 1 m/s to the right
3. 3 m/s to the right
4. 3 m/s to the left
5. Something else

Note:
* Correct Answer: A

</section>

<section data-markdown>

## Demo

[Galilean relativity example courtesy of Jamiroquai](https://vimeo.com/58139812)

</section>

<section data-markdown>

Standing on a moving walkway in the airport that is moving at 1 m/s to the right, you toss a ball into the air. You observe the ball moving straight up and down.

I'm sitting on a bench watching your shenanigans. What do I have to do to make my physics match yours? That is, what do I have to do to reproduce all your measurements?

1. Add 1 m/s to the left
2. Add 1 m/s to the right
3. Subtract 1 m/s to the right
4. Subtract 1 m/s to the left
5. None or more than one of these

Note:
* Correct Answer: E (it's A and C)

</section>

<section data-markdown>

A rocket is moving to the right at speed $v = (3/4)c$, relative to Earth.  On the  front of the rocket is a headlight which emits a flash of light.

<img src="./images/rocket_light.png" align="center" style="width: 700px";/>

In the reference frame of a passenger on the rocket, the speed of the light flash is

1. $c$
2. 7/4 $c$
3. 1/4 $c$
4. None of these

Note:
* Correct Answer: A

</section>

<section data-markdown>

A rocket is moving to the right at speed $v = (3/4)c$, relative to Earth.  On the  front of the rocket is a headlight which emits a flash of light.

<img src="./images/rocket_light.png" align="center" style="width: 700px";/>

According to a person at rest on the earth, the speed of the light flash is

1. $c$
2. 7/4 $c$
3. 1/4 $c$
4. None of these

Note:
* Correct Answer: A

</section>

<section data-markdown>

A rocket is moving to the right at speed $v = (3/4)c$, relative to Earth.  On the  front of the rocket is a headlight which emits a flash of light.

<img src="./images/rocket_light.png" align="center" style="width: 700px";/>

According to a person moving toward the rocket at speed $(3/4)c$, relative to earth, the speed of the light flash is

1. $c$
2. 7/4 $c$
3. 1/4 $c$
4. None of these

Note:
* Correct Answer: A

</section>

<section data-markdown>

<img src="./images/simul_train.png" align="center" style="width: 400px";/>

A light bulb flashes in the center of a train car that is moving at speed v with respect to the ground.  In the frame of reference of the train car, light wave from the flash strikes the front and back of the train simultaneously.

In the frame of reference of the ground, the light strikes the back of the train **(fill in the blank)** the light strikes the front of the train.

1. before
2. after
3. at the same time as

Note:
* Correct Answer: A
</section>
