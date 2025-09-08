## ECT\* Workshop: Analytic Structure of QCD and Yang-Lee Edge singularity

Organizers:

- Gokce Basar
- Christian Schmidt-Sonntag
- Vladi Skokov

Supported by FBK ECT\*, Bielefeld University, and CRC TR 211 (Strong interaction
matter under extreme conditions)

---

 <!-- .slide: data-transition="convex" -->

## Outline

- **Introduction**

 <div class="medmath">

1. Why QCD analytic structure?

2. State of the art

3. Open questions

 </div>

<span class="fragment">

- **Goals of the workshop**

</span>

 <span class="fragment">

- **Timetable and workshop structure**

</span>

---

 <!-- .slide: data-transition="convex" -->

## QCD Phase diagram

<img src="img/phase.png" width="70%">

---

 <!-- .slide: data-transition="convex" -->

## QCD Phase diagram: theory

- **Lattice Monte-Carlo**

_Talks throughout this week_

- **Functional methods**: Functional Renormalization Group / Dyson-Schwinger

_Talks by J. Pawlowski and F. Gao on Th_

</br>

### **Limitations:**

 <div class="medmath">

- Lattice QCD calculations are only feasible at zero baryon density due to the
  sign problem
- Functional methods require truncation improvement at larger values of chemical
  potential

 </div>

 </br>

---

 <!-- .slide: data-transition="convex" -->

## **Indirect methods:**

- Functional methods: failure of truncation indicate the approach to
  criticality?
- Lattice: Taylor series coefficients/imaginary $\mu$ $\to$ non-zero baryon
  density

$$
\frac{p}{T^4} = \sum\_{n=0}^{\infty} \frac{ \chi_n
}{n!}\left(\frac{\mu}{T}\right)^n
$$

---

 <!-- .slide: data-transition="convex" -->

## Taylor series expansion

- Consider an arbitrary function expanded around a regular point

 <div class="medmath">
  $$f(x) = \sum_{n=0}^{\infty} \frac{1}{n!}  f_n x^{n}$$
 </div>

- What limits the predictive power of this expansion?

 <div class="medmath">
$$|x| < R_c \equiv \left(  \lim_n \sup \left| f_n^{1/n} \right| \right)^{-1}$$
 </div>

- $R_c$ is the radius of convergence
- $R_c =$ distance in **complex** plane from expansion point to nearest
  singularity

---

<!-- .slide: data-transition="convex" -->

## Two sides of the same coin

<span class="fragment">
<div class="warning-box">
⚠️ Finite $R_c$ defines the limit beyond which naive application of Taylor series is fruitless
</div>
</span>

<span class="fragment">
 <div class="success-box">
✅ $R_c$ encodes the location of the closest singularity, and thus a critical point
</div>
</span>

---

## Most omnipresent critical point

| Type of critical point:       | <p class="fragment fade-in" data-fragment-index="2"> protocritical = **YLE** </p> | critical | tricritical |
| ----------------------------- | --------------------------------------------------------------------------------- | -------- | ----------- |
| Number of relevant variables: | <p class="fragment fade-in" data-fragment-index="1"> 1 </p> &nbsp;                | 2        | 4           |

<span class="fragment fade-in" data-fragment-index="2">

**YLE** = Yang-Lee edge singularity

1 independent crit. exp., c.f. standard critical point with 2 independent crit.
exp.

 </span>

--

<!-- .slide: data-transition="convex" -->

## Illustration in Ising model $h = i |z_c|^{-\beta \delta} t^{\beta \delta}$

<img src="img/IsingYLE.png"  width="50%">

- In contrast to the critical point, YLE form lines
- YLE are continuously connected to critical point

---

## Universal location of YLE

For each universality class:

- universal magnetic equation of state
- **universal location of YLE singularity**
- mapping to QCD requires non-universal parameters

| d                                | 1   | 2          | 3        | 4           |
| -------------------------------- | --- | ---------- | -------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma}$ | 1   | 1.32504(2) | 1.621(4) | $3/2^{2/3}$ |

_Talks by F. Rennecke (Tue) and H.-L. Xu (Fr)_

---

<!-- .slide: data-transition="convex" -->

## Back to QCD phase diagram

<img src="img/phase.png" width="45%">
<img src="img/RWMODEL.png" width="37%">

---

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T_c<T<T_{RW}$

<img src="img/YLEs.png" width=50% >

_Talks by M. Stephanov on Wed, S. Yin on Th_

<div class="cite">
M. Stephanov, hep-lat/0603014 
</div>

--

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T\to T_c$

<img src="img/YLEtoTc.png" width=50% >

--

<!-- .slide: data-transition="convex" -->

## QCD: Expected analytic structure $T\to T_{RW}$

<img src="img/YLEtoRW.png" width=50% >

---

## Naive mapping

<!-- .slide: data-transition="convex" -->

Near chiral transition

 <div class="medmath">

\begin{align} z &= z_0 \left( \frac{m_l}{m_s}\right)^{-\frac{1}{\beta\delta}}
\times \left[ \frac{T-T_c}{T_c} + \kappa^B_2 \left( \frac{\mu}{T_c} \right)^2 +
\kappa^B_4 \left( \frac{\mu}{T_c} \right)^4 + \dots \right] \,. \label{eq:z}
\end{align}

</div>

<img src="img/R.png"  width="40%">

<div class="cite">
S. Mukherjee, V.S., 1909.04639
</div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: RW critical point

Lattice QCD and indirect methods to locate YLE:

input from Im $\mu$ \& analytic continuation

<img src="img/RW_YLE.png" height=280em >

$$
  z = z_c \to \text{Re} \mu_{YLE} \propto (T_{RW}-T)^{\beta \delta} \quad \leadsto T_{RW} = 211.1 \pm 3.1 \text{MeV}.
$$

_Talk by C. Schmidt on Tue_

<div class="cite">
 C. Schmidt et al,     2209.04345
</div>

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: chiral critical point

Lattice input from Taylor series coeff. at $\mu=0$ or Im $\mu$ \& analytic
continuation

<img src="img/BasarYLE.png" height=300em >
<img src="img/LatticeYLElocation.png" height=300em >

<div class="cite">
G. Basar, 2312.06952 <br>
D. Clarke et. al., 2405.10196
</div>

_Talks by K. Zambello after coffee break and G. Basar on Wed_

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: estimate for critical point

 <div class=smallmath>
$$ T_c \approx 110 \text{ MeV} , \mu_c \approx 650 \text{ MeV}$$
</div>

 <img src="img/LatticeQCDPD.png" height=300em >

---

<!-- .slide: data-transition="convex" -->

## Tracing YLE singularity: systematics

 <img src="img/DoubleExtra.png" height=300em >

 <div class="warning-box">
⚠️ Double extrapolation
</div>

_Talk by A. Adam this afternoon_

---

<!-- .slide: data-transition="convex" -->

## Goals of the workshop

- **Improve Understanding of QCD Equation of State Analytic Structure**

- **Assess Reliability of Analytic Continuation Methods for Singularity
  Location**

- **Develop Strategy to Minimize Systematic Errors in Locating QCD Critical
  Point**

- **Improve Understanding of Universal Analytic Structure Near Second-Order
  Critical Point**

---

<!-- .slide: data-transition="convex" -->

## Workshop

### Monday and Tuesday

**Lattice QCD**: extrapolations, systematics, new methods

**Discussion** on systematics os locating YLEs/LYZs and critical point

---

### Wednesday

**Amalytic strucutre**

**Analysis of lattice data**

**Discussion** on analytic strucutre

**Free afternoon and Workshop dinner**

---

<!-- .slide: data-transition="convex" -->

### Thursday

**Functional methods**

### Friday

**Universal location of YLE** in Ising model
