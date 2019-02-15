---
layout: slide
theme: white
transition: slide
---

<section data-markdown>
Two LR circuits driven by an AC power supply are shown below.

<img src="./images/two_RL_circuits.png" align="center" style="width: 800px";/>

Which circuit is a low pass filter?

1. The left circuit
2. The right circuit
3. Both circuits
4. Neither circuit

Note:
* Correct Answer: B

</section>

<section data-markdown>
Two RC circuits driven by an AC power supply are shown below.

<img src="./images/two_RC_circuits.png" align="center" style="width: 800px";/>

Which circuit is a high pass filter?

1. The left circuit
2. The right circuit
3. Both circuits
4. Neither circuit

Note:
* Correct Answer: A

</section>


<section data-markdown>

Ampere's Law relates the line integral of B around some closed path, to a current flowing through a surface bounded by the chosen closed path.

$\oint \mathbf{B} \cdot d\mathbf{l} =  \mu_0 I$

By calling it a "Law", we expect that:

1. It is neither correct nor useful.
2. It is sometimes correct and sometimes easy to use.
3. It is correct and sometimes easy to use.
4. It is correct and always easy to use.
5. None of the above.

Note:
* Correct Answer: C

</section>

<section data-markdown>

## Announcements
* Quiz 3 (Friday 2/12) - RLC circuits
  * Solve a circuit problem using the phasor method
  * Discuss limits on the response and how it might act as a filter

</section>

<section data-markdown>

Take the divergence of the curl of any (well-behaved)
vector function $\mathbf{F}$, what do you get?

$$\nabla \cdot \left(\nabla \times \mathbf{F}\right) = ???$$

1. Always 0
2. A complicated partial differential of $\mathbf{F}$
3. The Laplacian: $\nabla^2 \mathbf{F}$
4. Wait, this vector operation is ill-defined!

Note:
* Correct Answer: A

</section>

<section data-markdown>

Take the divergence of both sides of Faraday's law:

$$\nabla \times \mathbf{E} = -\dfrac{\partial \mathbf{B}}{\partial t}$$

What do you get?
1. 0 = 0 (is this interesting?)
2. A complicated partial differential equation (perhaps a wave equation of some sort ?!) for $\mathbf{B}$
3. Gauss’ law!
4. ???

Note:
* Correct Answer: A
</section>

<section data-markdown>

Take the divergence of both sides of Ampere's law:

$$\nabla \times \mathbf{B} = \mu_0 \mathbf{J}$$

**According to this**, the divergence of $\mathbf{J}$ is:


1. $-\partial \rho/\partial t$
2. A complicated partial differential of $\mathbf{B}$
3. Always 0
4. ???

Note:
* Correct Answer: C
</section>

<section data-markdown>

Ampere's Law relates the line integral of $\mathbf{B}$ around some closed path, to a current flowing through a surface bounded by the chosen closed path.

$\oint \mathbf{B} \cdot d\mathbf{l} =  \mu_0 I$

The **path** can be:

1. Any closed path
2. Only circular paths
3. Only sufficiently symmetrical paths
4. Paths that are parallel to the B-field direction.
5. None of the above.

Note:
* Correct Answer: A

</section>

<section data-markdown>

Ampere's Law relates the line integral of $\mathbf{B}$ around some closed path, to a current flowing through a surface bounded by the chosen closed path.

$\oint \mathbf{B} \cdot d\mathbf{l} =  \mu_0 I$

The **surface** can be:

1. Any closed bounded surface
2. Any open bounded surface
3. Only surfaces perpendicular to $\mathbf{J}$.
4. Only surfaces tangential to the B-field direction.
5. None of the above.

Note:
* Correct Answer: B

</section>


<section data-markdown>

Rank order $\int \mathbf{J} \cdot d\mathbf{A}$ (over blue surfaces) where $\mathbf{J}$ is uniform, going left to right:

<img src="./images/current_surfaces.png" align="center" style="width: 600px";/>


1. iii > iv > ii > i
2. iii > i > ii > iv
3. i > ii > iii > iv
4. Something else!!
5. Not enough info given!!

Note:
* CORRECT ANSWER: D
* They are all the same!

</section>

<section data-markdown>

We are interested in $\mathbf{B}$ on the dashed "Amperian loop", and plan to use $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I_t$ to figure it out. What is $I_t$ here?

<img src="./images/wire_w_cap.png" align="center" style="width: 700px";/>


1. $I$
2. $I/2$
3. 0
4. Something else

Note:
* Correct Answer: A
</section>

<section data-markdown>

We are interested in $\mathbf{B}$ on the dashed "Amperian loop", and plan to use $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I_t$ to figure it out. What is $I_t$ here? *The surface over which we integrate $\mathbf{J}\cdot d\mathbf{A}$ is shown
 in blue.*

<img src="./images/cap_w_wire_highlighted.png" align="center" style="width: 700px";/>


1. $I$
2. $I/2$
3. 0
4. Something else

Note:
* Correct Answer: A
</section>

<section data-markdown>

We are interested in $\mathbf{B}$ on the dashed "Amperian loop", and plan to use $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I_t$ to figure it out. What is $I_t$ here? *The surface over which we integrate $\mathbf{J}\cdot d\mathbf{A}$ is shown
 in blue.*

<img src="./images/cap_soap_bubble.png" align="center" style="width: 700px";/>


1. $I$
2. $I/2$
3. 0
4. Something else

Note:
* Correct Answer: C
</section>

<section data-markdown>

The complete differential form of Ampere's Law is now argued to be:

$$\nabla \times \mathbf{B} = \mu_0\mathbf{J} + \mu_0 \epsilon_0\dfrac{\partial \mathbf{E}}{\partial t}$$

The integral form of this equation is:

1. $\iint \mathbf{B}\cdot d\mathbf{A} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\oint \mathbf{E}\cdot d\mathbf{l}$
2. $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\oint \mathbf{E}\cdot d\mathbf{l}$
3. $\iint \mathbf{B}\cdot d\mathbf{A} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\iint \mathbf{E}\cdot d\mathbf{A}$
4. $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\iint \mathbf{E}\cdot d\mathbf{A}$
5. Something else/???

Note:
* Correct Answer: D

</section>


<section data-markdown>

How amazing is that $\dfrac{1}{\sqrt{\epsilon_0 \mu_0}} = 3\times10^8 \mathrm{m/s}$?

1. OMGBBQPIZZA, so amazing!
2. It's pretty cool
3. Meh
4. Whatever

</section>

<section data-markdown>
## Correct Answer
OMGBBQPIZZA, so amazing!

</section>

<section data-markdown>

What do you want to do today?
1. Clickers and lecture
2. Tutorial

*Either way, we are covering the same example.*

</section>

<section data-markdown>

Consider a large parallel plate capacitor as shown, charging so that $Q = Q_0+\beta t$ on the positively charged plate. Assuming the edges of the capacitor and the wire connections to the plates can be ignored, what is the direction of the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt.png" align="left" style="width: 400px";/>

1. $\pm \hat{\phi}$
2. 0
3. $\pm \hat{z}$
4. $\pm \hat{s}$
5. ???

Note:
* Correct Answer: A

</section>

<section data-markdown>

Same capacitor with $Q = Q_0+\beta t$ on the positively charged plate. What is the direction of the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt.png" align="left" style="width: 400px";/>

1. $+\hat{\phi}$
2. $-\hat{\phi}$
3. Not sure how to tell

Note:
* Correct Answer: A

</section>

<section data-markdown>

Same capacitor with $Q = Q_0+\beta t$ on the positively charged plate. What kind of amperian loop can be used between the plates to find the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt_loop.png" align="center" style="width: 500px";/>

D) A different loop  E) Not enough symmetry for a useful loop

Note:
* Correct Answer: B
</section>

<section data-markdown>

Same capacitor with $Q = Q_0+\beta t$ on the positively charged plate. What is the magnitude of the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt_smaller.png" align="left" style="width: 400px";/>

1. $\frac{\mu_0 \beta}{2 \pi r}$
2. $\frac{\mu_0 \beta r}{2 d^2}$
3. $\frac{\mu_0 \beta d}{2 a^2}$
4. $\frac{\mu_0 \beta a}{2 \pi r^2}$
5. None of the above

Note:
* Correct Answer: E

</section>

<section data-markdown>

<img src="./images/cap_plates_boxed.png" align="right" style="width: 400px";/>

Consider the surface of an imaginary volume (dashed lines, at right) that partly encloses the left capacitor plate. For this closed surface, is the total flux of the current density, $\iint \mathbf{J} \cdot d\mathbf{A}$ positive, negative or zero?



1. Positive
2. Negative
3. Zero

Note:
* Correct Answer: B
* The charge density is increasing, so the total charge in the region is increasing with time, thus the flux of the current density must be negative (conservation of charge).
</section>


<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 3**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: A
* There is no current or charge inthe region

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 2**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: D
* One way to think about this is that the charge on the plate is increasing (so the density is increasingly more positive - positive charge). So the divergence of the current density is negative (jives with previous CQ also).

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 4**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: E
* One way to think about this is that the charge on the plate is increasing (so the density is increasingly more negative - negative charge). So the divergence of the current density is positive.

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 1**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: A
* The divergence of the curl of the magnetic field is zero and there's no electric field out there, so the divergence of J must vanish.

</section>


<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 5**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: A
* The divergence of the curl of the magnetic field is zero and there's no electric field out there, so the divergence of J must vanish.

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>

Suppose the original Ampere's law $\nabla \times \mathbf{B} = \mu_0\mathbf{J}$ were correct without any correction from Maxwell (it’s not, but suppose for a moment that it is). What would this imply about $\nabla \cdot \mathbf{J}$ at points 2 and 4 in the diagram?

1. The remain unchanged
2. They swap signs
3. They become zero
4. ???

Note:
* Correct Answer: C


</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>

Let's continue with the (incomplete) definition of Ampere's Law: $\nabla \times \mathbf{B} = \mu_0\mathbf{J}$.

What does this form tell you about the signs of $(\nabla \times \mathbf{B})_x$ at locations 1, 3, and 5?

1. All positive
2. All negative
3. Positive at 1 and 5, zero at 3
4. Negative at 1 and 5, zero at 3
5. Something else


Note:
* Correct Answer: C
* All we need here is the direction of Jx, which is zero at 3
</section>

<section data-markdown>
