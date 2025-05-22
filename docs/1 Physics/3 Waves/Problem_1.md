# Problem 1

#  Wave Interference from Point Sources on Water Surface

A circular wave on the water surface, emanating from a point source located at $(x_0, y_0)$, can be described by the Single Disturbance equation:

$$
\eta(x, y, t) = \frac{A}{\sqrt{r}} \cdot \cos (kr - \omega t + \phi)
$$

### Where:
- $\eta(x, y, t)$ is the displacement of the water surface at point $(x, y)$ and time $t$,
- $A$ is the amplitude of the wave,
- $k = \frac{2\pi}{\lambda}$ is the wave number, related to the wavelength $\lambda$,
- $\omega = 2\pi f$ is the angular frequency, related to the frequency $f$,
- $r = \sqrt{(x - x_0)^2 + (y - y_0)^2}$ is the distance from the source to the point $(x, y)$,
- $\phi$ is the initial phase.

---

##  Problem Statement

**Your task** is to analyze the interference patterns formed on the water surface due to the **superposition of waves** emitted from point sources placed at the **vertices of a chosen regular polygon**.

---

##  Steps to Follow

### 1. Select a Regular Polygon
Choose a polygon with evenly spaced vertices:
- Triangle (3 sources)
- Square (4 sources)
- Pentagon (5 sources)
- etc.

Let $N$ be the number of sides (and hence the number of sources).

### 2. Position the Sources
Place each source at a vertex of a regular polygon inscribed in a circle of radius $R$ centered at the origin $(0, 0)$.

Coordinates of the $i$-th vertex (source):

$$
(x_i, y_i) = \left(R \cos\left(\frac{2\pi i}{N}\right), R \sin\left(\frac{2\pi i}{N}\right)\right), \quad i = 0, 1, \ldots, N-1
$$

### 3. Wave Equations for Each Source

Each point source emits a wave:

$$
\eta_i(x, y, t) = \frac{A}{\sqrt{r_i}} \cdot \cos(k r_i - \omega t + \phi_i)
$$

Where:
- $r_i = \sqrt{(x - x_i)^2 + (y - y_i)^2}$
- $A$, $k$, $\omega$ are as defined earlier
- $\phi_i$ is the phase offset (can be zero or varied)

### 4. Superposition of Waves

Total wave displacement at any point $(x, y)$ at time $t$ is:

$$
\eta_{\text{sum}}(x, y, t) = \sum_{i=1}^{N} \eta_i(x, y, t)
$$

---
##  Analyze and Visualize

### 1. Analyze Interference Patterns
Examine the resulting displacement $\eta_{\text{sum}}(x, y, t)$ as a function of $(x, y)$ and $t$.
- Look for **constructive interference** (wave amplification)
- Identify **destructive interference** (wave cancellation)

### 2. Visualization
Present your findings graphically to illustrate the interference patterns formed by the chosen regular polygon.

---

##  Considerations

- Assume all sources emit waves with the same amplitude $A$, wavelength $\lambda$, and frequency $f$.
- The waves are **coherent**, maintaining a constant phase difference.
- Use simulation tools like **Python + Matplotlib** or similar graphical tools to assist with your analysis and visualization.


