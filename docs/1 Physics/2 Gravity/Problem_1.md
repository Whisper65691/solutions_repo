# Derivation of Kepler's Third Law for Circular Orbits

Kepler's Third Law states that the square of the orbital period of a planet is proportional to the cube of the semi-major axis (orbital radius for circular orbits). We derive this relationship using Newtonian mechanics.

---

## Step 1: Equating Gravitational Force and Centripetal Force

For a small body of mass $m$ orbiting a much larger body of mass $M$ in a circular orbit of radius $r$:

$$
\frac{G M m}{r^2} = \frac{m v^2}{r}
$$

Where:
- $G$: Gravitational constant
- $v$: Orbital speed
- $m$: Mass of the orbiting body (cancels out)
- $M$: Mass of the central object

---

## Step 2: Simplify the Equation

Canceling $m$ from both sides:

$$
\frac{G M}{r^2} = \frac{v^2}{r}
\Rightarrow v^2 = \frac{G M}{r}
$$

---

## Step 3: Express Orbital Period in Terms of Velocity

The orbital period $T$ is:

$$
T = \frac{2\pi r}{v} \Rightarrow v = \frac{2\pi r}{T}
$$

Substitute into the equation for $v^2$:

$$
\left( \frac{2\pi r}{T} \right)^2 = \frac{G M}{r}
$$

---

## Step 4: Simplify and Solve for $T^2$

$$
\frac{4\pi^2 r^2}{T^2} = \frac{G M}{r}
\Rightarrow \frac{4\pi^2 r^3}{T^2} = G M
\Rightarrow T^2 = \frac{4\pi^2}{G M} r^3
$$

---

## Final Result

$$
T^2 \propto r^3
$$

This is Kepler's Third Law. The constant of proportionality is $\frac{4\pi^2}{G M}$, which depends on the mass $M$ of the central body.
