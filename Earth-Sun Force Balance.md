# Earth–Sun Force Balance with r₁·r₂

Oct 14, 2026 · @Shaimaa Soltan

## 1. The balance condition

The modified law gives the real Newtonian force only when r₁·r₂ = r², so r is the geometric mean of r₁ and r₂.

Newton's law needs the gravitational constant G = 6.674×10⁻¹¹ N·m²/kg². Labels follow the sketch: M₁ = Earth (small body), M₂ = Sun (large body).

```latex
F = \frac{G\,m_1 m_2}{r^2} \qquad F' = \frac{G\,m_1 m_2}{r_1 r_2}
```

Setting F′ = F gives the balance condition:

```latex
r_1 \, r_2 = r^2 \quad\Longleftrightarrow\quad r = \sqrt{r_1 r_2}
```

Every pair on the hyperbola r₂ = r²/r₁ balances. If r₁ = k·r, then r₂ = r/k: stretching one distance shrinks the other by the same factor.

| Input | Value |
| --- | --- |
| m₁ (Earth) | 5.972×10²⁴ kg |
| m₂ (Sun) | 1.989×10³⁰ kg |
| r (Earth–Sun distance) | 1.496×10¹¹ m (1 AU) |

## 2. Linking r₁ and r₂ to the masses

A symmetric split, where each body contributes an equal share, fixes the pair: r₁/r₂ = m₁/m₂.

The balance condition alone allows infinitely many pairs. Writing the force as a product of two "mass per distance" factors and making them equal adds the second rule:

```latex
F = G\left(\frac{m_1}{r_1}\right)\left(\frac{m_2}{r_2}\right), \qquad \frac{m_1}{r_1} = \frac{m_2}{r_2} \;\Rightarrow\; \frac{r_1}{r_2} = \frac{m_1}{m_2}
```

Solving this with r₁·r₂ = r²:

```latex
r_1 = r\sqrt{\frac{m_1}{m_2}} \qquad r_2 = r\sqrt{\frac{m_2}{m_1}}
```

Each factor then equals √(m₁m₂)/r, so the two bodies contribute equally to the force.

## 3. Earth–Sun numbers

For Earth and the Sun the split gives r₁ ≈ 259,000 km and r₂ ≈ 577 AU, and the force is 3.54×10²² N.

| Quantity | Value | Note |
| --- | --- | --- |
| m₁/m₂ | 3.003×10⁻⁶ | Earth is \~1/333,000 of the Sun |
| √(m₁/m₂) | 1.733×10⁻³ | scale factor k |
| r₁ | 2.59×10⁸ m | \~259,000 km, about 2/3 of the Earth–Moon distance |
| r₂ | 8.63×10¹³ m | \~577 AU |
| r₁·r₂ | 2.238×10²² m² | equals r² ✓ |
| F | 3.54×10²² N | same as standard Newton |

```latex
F = \frac{6.674\times10^{-11} \times 5.972\times10^{24} \times 1.989\times10^{30}}{2.238\times10^{22}} \approx 3.54\times10^{22}\ \text{N}
```

## 4. When Earth stays in its orbit

Earth keeps its circular orbit at 29.8 km/s only when r₁·r₂ = r²; any other product changes the orbit.

Gravity must supply exactly the centripetal force, and the centripetal side uses the real distance r:

```latex
\frac{G\,m_1 m_2}{r_1 r_2} = \frac{m_1 v^2}{r} \quad\Rightarrow\quad v = \sqrt{\frac{G\,m_2\,r}{r_1 r_2}}
```

| Case | Force | What Earth does |
| --- | --- | --- |
| r₁·r₂ = r² | Exactly Newton's | Circular orbit, v = √(G·m₂/r) = 29.8 km/s |
| r₁·r₂ < r² | Too strong | Falls inward onto a tighter ellipse |
| r₁·r₂ > r² | Too weak | Drifts outward; far enough off, it escapes |

The orbit fixes the product r₁·r₂; the masses only decide how that product is split between r₁ and r₂.

## 5. A split that fails: distances to the barycenter

Using each body's distance to the shared centre of mass makes the force about 333,000 times too strong.

- r₁ = r·m₂/(m₁+m₂) ≈ 1.496×10¹¹ m (Earth to barycenter)
- r₂ = r·m₁/(m₁+m₂) ≈ 449 km (Sun to barycenter)

```latex
r_1 r_2 = r^2\,\frac{m_1 m_2}{(m_1+m_2)^2} \approx 3\times10^{-6}\,r^2
```

### Summary

| Condition | Meaning |
| --- | --- |
| r₁·r₂ = r² | Required for the real force and a stable orbit |
| r₁/r₂ = m₁/m₂ | Mass-weighted split with equal shares |
| r₁ ≈ 2.59×10⁸ m, r₂ ≈ 8.63×10¹³ m | Earth–Sun balance point |
| F ≈ 3.54×10²² N, v ≈ 29.8 km/s | Same as standard Newton |

## 6. Where r₁ and r₂ are measured from

If r₁ and r₂ run from M₁ and M₂ to one shared point P, then P must lie on a Cassini oval. The mass rule finds a point on it only when 0.382 ≤ m₁/m₂ ≤ 2.618.

Define r₁ = |M₁P| and r₂ = |M₂P|, as in the sketch. The balance condition then becomes a curve in the plane:

```latex
|M_1P|\cdot|M_2P| = r^2
```

This is a Cassini oval with foci at M₁ and M₂. Its constant (r) is twice the half-distance between the foci (r/2), so it is one closed loop around both bodies.

| Point P on the oval | r₁ | r₂ | Where it sits |
| --- | --- | --- | --- |
| Equal split | r | r | Apex of the equilateral triangle on M₁M₂ |
| Golden point beyond M₁ | 0.618 r | 1.618 r | On the line, outside M₁ |
| Golden point beyond M₂ | 1.618 r | 0.618 r | On the line, outside M₂ |

On the line M₁M₂ the condition reads d(d + r) = r², so d = r(√5 − 1)/2 = 0.618 r. That is the golden ratio φ, and r₂/r₁ = φ² = 2.618 there.

### The mass limit

The mass rule needs r₁ = r√(m₁/m₂) and r₂ = r√(m₂/m₁). From a single point the triangle inequality forces |r₂ − r₁| ≤ r. Along the oval, r₁/r₂ ranges only from 1/φ² to φ²:

```latex
\frac{1}{\varphi^2} = 0.382 \;\le\; \frac{m_1}{m_2} \;\le\; \varphi^2 = 2.618
```

When the masses meet this limit, P sits where the circle of radius r₁ around M₁ crosses the circle of radius r₂ around M₂.

| Pair | m₁/m₂ | Shared point P? |
| --- | --- | --- |
| Equal binary stars | 1 | Yes: the apex, r₁ = r₂ = r |
| Binary star 0.6 | 0.6 | Yes: r₁ = 0.775 r, r₂ = 1.291 r |
| Charon / Pluto | 0.122 | No |
| Moon / Earth | 0.0123 | No |
| Earth / Sun | 3.0×10⁻⁶ | No: needs r₂ − r₁ ≈ 577 r |

For Earth and the Sun, r₁ and r₂ cannot share a measuring point. They are two separate scales: r₁ ≈ 259,000 km measured from Earth's centre, and r₂ ≈ 577 AU measured from the Sun's centre.

Interactive tools: [r₁·r₂ Orbit Balance](https://claude.ai/artifact/BXTExkoCanGtak3pTJ9gm2) and [r₁·r₂ Measurement Point](https://claude.ai/artifact/D8hu88NVQGcfFJNm6DXcHc).

## 7. Splitting G into G₁ and G₂

G can be split three ways around the point P. In each one the true G is recovered as a mean or a product of the two parts. G has units (m³·kg⁻¹·s⁻²), so "G as a ratio" here means a ratio of measurable quantities, not a pure number.

### Option A: G as a geometric mean

Measure the force from P using only one distance. Each distance then needs its own constant:

```latex
F = \frac{G_1\,m_1 m_2}{r_1^2} = \frac{G_2\,m_1 m_2}{r_2^2} \quad\Rightarrow\quad G_1 = G\,\frac{r_1}{r_2}, \qquad G_2 = G\,\frac{r_2}{r_1}
```

```latex
G = \sqrt{G_1 G_2} \qquad \frac{G_1}{G_2} = \left(\frac{r_1}{r_2}\right)^2
```

G is the geometric mean of the two local values, just as r = √(r₁·r₂). With the mass rule r₁/r₂ = m₁/m₂, the parts become G₁ = G·m₁/m₂ and G₂ = G·m₂/m₁, and the force takes a symmetric form:

```latex
F = \frac{G\,m_1^2}{r_1^2} = \frac{G\,m_2^2}{r_2^2}
```

Each body alone, at its own distance, produces the full mutual force.

| Earth–Sun value | Option A |
| --- | --- |
| G₁ = G·m₁/m₂ | 2.00×10⁻¹⁶ |
| G₂ = G·m₂/m₁ | 2.22×10⁻⁵ |
| √(G₁·G₂) | 6.674×10⁻¹¹ ✓ |
| G·m₁²/r₁² | 3.54×10²² N ✓ |

### Option B: G as a product

Give each body half of G, scaled by its distance to P:

```latex
G_1 = \sqrt{G}\,\frac{r_1}{r}, \qquad G_2 = \sqrt{G}\,\frac{r_2}{r}, \qquad G_1 G_2 = G\,\frac{r_1 r_2}{r^2} = G\,\varepsilon
```

The ratio G₁/G₂ = r₁/r₂ = |M₁P|/|M₂P|. On the Cassini oval G₁·G₂ = G exactly. Off the oval G₁·G₂ = G·ε, and the r₁·r₂ in F′ cancels, so the force is Newton's from any P.

This is the trade-off: either G stays fixed and P must sit on the oval, or the split of G moves with P and any point works.

| Earth–Sun value (√G = 8.17×10⁻⁶) | Option B |
| --- | --- |
| G₁ = √G·r₁/r | 1.42×10⁻⁸ |
| G₂ = √G·r₂/r | 4.71×10⁻³ |
| G₁·G₂ | 6.674×10⁻¹¹ ✓ |

### Option C: G as a ratio of lengths

With the speed of light c, G turns each mass into a length, its gravitational radius ρ = G·m/c². The force becomes the product of two unit-free ratios, one per body, each measured to P:

```latex
F = F_{\max}\,\frac{\rho_1}{r_1}\,\frac{\rho_2}{r_2}, \qquad \rho_i = \frac{G\,m_i}{c^2}, \qquad F_{\max} = \frac{c^4}{G} = 1.21\times10^{44}\ \text{N}
```

G plays two roles here: inside each ratio it turns mass into length (the G₁, G₂ split), and in F\_max it sets the largest possible force. Each ratio ρ/r also equals the depth of that body's gravitational potential at P, divided by c².

With the mass rule the two ratios are equal, so P is where both bodies are equally "strong":

| Earth–Sun value | Earth (M₁) | Sun (M₂) |
| --- | --- | --- |
| Gravitational radius ρ | 4.43 mm | 1,477 m |
| Distance to P | r₁ = 2.59×10⁸ m | r₂ = 8.63×10¹³ m |
| Ratio ρ/r | 1.71×10⁻¹¹ | 1.71×10⁻¹¹ |

F = 1.21×10⁴⁴ × (1.71×10⁻¹¹)² = 3.54×10²² N ✓. The shared ratio is √(F/F\_max).

The two distances also have a direct physical meaning:

- r₁ = r√(m₁/m₂) is the distance at which Earth's pull equals the Sun's pull at Earth (G·m₁/r₁² = G·m₂/r²).
- r₂ = r√(m₂/m₁) is the distance at which the Sun's pull drops to Earth's pull at 1 AU (G·m₂/r₂² = G·m₁/r²).

### Other standard ways to read G as a ratio

| Form | Meaning | Earth–Sun check |
| --- | --- | --- |
| G = 4π²a³ / (M·T²) | Orbit geometry per unit of mass (Kepler's third law) | 6.672×10⁻¹¹ ✓ |
| G = g·R² / M | Surface pull times area, per unit of mass | Earth: 9.81 × (6.371×10⁶)² / 5.972×10²⁴ ≈ 6.67×10⁻¹¹ |
| G = v²·r / M | Orbital speed squared times distance, per unit of mass; with r₁, r₂ it is G = v²·r₁r₂ / (m₂·r) | 29.78 km/s gives 6.67×10⁻¹¹ |
| G = c²·ℓ\_P / m\_P | Planck length over Planck mass, times c²; in natural units G = 1 | definition |

Interactive tool for Option C: [Equal-Strength Point](https://claude.ai/artifact/4euW5DtKPJ7ZUuU49FyMMV).

## 8. What r₁ and r₂ measure, and where G comes back

Ratios built from r₁, r₂ and r measure only the masses; G cancels out of them. G returns once motion (v) or the force limit (F\_max) is brought in.

### The ratios that work

With the mass rule r₁ = r√(m₁/m₂) and r₂ = r√(m₂/m₁), four ratios hold for any pair of bodies:

```latex
\frac{r_1 r_2}{r^2} = 1 \qquad \frac{r_1}{r_2} = \frac{m_1}{m_2} \qquad \frac{r_2 - r_1}{r} = \sqrt{\frac{m_2}{m_1}} - \sqrt{\frac{m_1}{m_2}} \qquad \frac{r_1 + r_2}{r} = \sqrt{\frac{m_2}{m_1}} + \sqrt{\frac{m_1}{m_2}}
```

The value 8.91 seen in the Measurement Point tool is (r₂ − r₁)/r for the Moon and Earth. It is set by their mass ratio, not by G: G = 6.674×10⁻¹¹ in SI, and a ratio of lengths has no units while G does.

| Pair | m₁/m₂ | (r₂ − r₁)/r | (r₁ + r₂)/r |
| --- | --- | --- | --- |
| Charon / Pluto | 0.122 | 2.51 | 3.21 |
| Moon / Earth | 0.0123 | 8.91 | 9.13 |
| Jupiter / Sun | 9.55×10⁻⁴ | 32.3 | 32.4 |
| Earth / Sun | 3.0×10⁻⁶ | 577 | 577 |

### The reduced mass

Squaring the sum gives the reduced mass μ = m₁m₂/(m₁ + m₂), the mass that appears in every two-body orbit:

```latex
\left(\frac{r_1 + r_2}{r}\right)^2 = \frac{(m_1+m_2)^2}{m_1 m_2} = \frac{m_1 + m_2}{\mu} \qquad \left(\frac{r_2 - r_1}{r}\right)^2 = \frac{m_1 + m_2}{\mu} - 4
```

So r₁ and r₂ encode the total mass M = m₁ + m₂ in units of μ: M = μ·((r₁ + r₂)/r)².

| Pair | μ | ((r₁ + r₂)/r)² = M/μ |
| --- | --- | --- |
| Moon / Earth | 7.25×10²² kg | 83.3 |
| Earth / Sun | 5.97×10²⁴ kg | 333,056 |

### G from the orbit: G = v²·r / M

The orbit brings time back through the speed v, so it can measure G. In our variables:

```latex
G = \frac{v^2\, r_1 r_2}{m_2\, r} \;\xrightarrow{\;r_1 r_2 = r^2\;}\; G = \frac{v^2\, r}{m_2}
```

For the exact two-body orbit, v is the relative speed and the mass is the total M = m₁ + m₂. Writing M through the reduced mass and r₁, r₂:

```latex
G = \frac{v^2\, r}{m_1 + m_2} = \frac{v^2\, r}{\mu}\left(\frac{r}{r_1 + r_2}\right)^2 = \frac{v^2\, r^3}{\mu\,(r_1 + r_2)^2}
```

Earth–Sun check: 29.78 km/s, 1 AU and M = 1.989×10³⁰ kg give G = 6.67×10⁻¹¹ ✓.

### G from the force limit: G = c⁴ / F\_max

F\_max = c⁴/G is the definition, so it does not measure G by itself. It becomes useful with the equal-strength level at P, L = √(F/F\_max) = ρ₁/r₁ = ρ₂/r₂ (section 7, Option C). Since ρ = G·m/c²:

```latex
G = \frac{c^4}{F_{\max}} = \frac{L\,c^2\, r_1}{m_1} = \frac{L\,c^2\, r_2}{m_2} = \frac{F\, r_1 r_2}{m_1 m_2}
```

Read this way, G is the distance to P per unit of mass, times c²L. The two bodies give the same G because the mass rule makes r₁/m₁ = r₂/m₂.

Earth–Sun check: L = 1.71×10⁻¹¹, so L·c²·r₁/m₁ = 1.71×10⁻¹¹ × 8.99×10¹⁶ × 2.59×10⁸ / 5.972×10²⁴ = 6.674×10⁻¹¹ ✓.

### How the two routes connect

Combining the orbit with the equal-strength level ties v, P and F\_max together without G:

```latex
\frac{v^2}{c^2} = \frac{\rho_2}{r} = L\,\frac{r_2}{r} \qquad\Rightarrow\qquad v = c\,\sqrt{L\,\frac{r_2}{r}}
```

Earth–Sun check: c × √(1.71×10⁻¹¹ × 577) = 29.8 km/s, Earth's orbital speed ✓.

| Route | Formula for G | Inputs |
| --- | --- | --- |
| Orbit, light body | G = v²·r / m₂ | v, r, m₂ |
| Orbit, two-body | G = v²·r³ / (μ·(r₁ + r₂)²) | v, r, r₁, r₂, μ |
| Force at P | G = F·r₁r₂ / (m₁m₂) | F, r₁, r₂, m₁, m₂ |
| Equal-strength level | G = L·c²·r₁ / m₁ = L·c²·r₂ / m₂ | L, c, r₁ or r₂, mass |
| Force limit | G = c⁴ / F\_max | F\_max (by definition) |

## 9. Potential depth at P and why G is constant

The equal-strength point and the orbit meet in one number, the potential depth at P, Φₚ. G is that depth times the distance to P, per kilogram of the body, and it comes out the same for every system.

### Step 1: equal strength means equal potential depth

A body's potential depth at distance d is Φ = G·m/d (energy per kg). Since ρ/d = Φ/c², equal strength at P means:

```latex
\Phi_P = \frac{G\,m_1}{r_1} = \frac{G\,m_2}{r_2} = L\,c^2
```

### Step 2: the orbit sets the same depth

For a circular orbit, v² = G·m₂/r, the Sun's potential depth at Earth's distance r. Moving out from r to r₂ lowers the depth by the factor r/r₂:

```latex
\Phi_P = v^2\,\frac{r}{r_2} = v^2\sqrt{\frac{m_1}{m_2}}
```

Joined together: at P, each body's potential depth is the same, L·c², and the orbit fixes that depth as v²·√(m₁/m₂). The speed v, the point P and the force limit (through L = √(F/F\_max)) are three views of one number, Φₚ.

Earth–Sun check: L·c² = 1.71×10⁻¹¹ × 8.99×10¹⁶ = 1.54×10⁶ J/kg, and v²·√(m₁/m₂) = (29,780)² × 1.733×10⁻³ = 1.54×10⁶ J/kg ✓.

### Definition of G from these parameters

Dividing the potential depth by mass per distance at P:

```latex
G = \Phi_P\,\frac{r_1}{m_1} = \Phi_P\,\frac{r_2}{m_2} = v^2\sqrt{\frac{m_1}{m_2}}\,\frac{r_1}{m_1} = \frac{v^2\, r}{m_2} = \frac{L\,c^2\, r_1}{m_1}
```

**Definition:** G is the potential depth at P times the distance to P, per kilogram of the body. More generally, G = Φ·d/m = 6.674×10⁻¹¹ (J/kg)·m/kg for any body at any distance, including every P.

### Why G stays constant while everything else changes

Every input changes from one system to the next; the combination does not. Using measured orbital speeds and separations, with G = v²·r/M and M = m₁ + m₂:

| System | Orbital speed v | Separation r | Potential depth at P, Φₚ | G = v²·r/M |
| --- | --- | --- | --- | --- |
| Earth / Sun | 29.78 km/s | 1.496×10¹¹ m | 1.54×10⁶ J/kg | 6.67×10⁻¹¹ |
| Jupiter / Sun | 13.07 km/s | 7.785×10¹¹ m | 5.27×10⁶ J/kg | 6.68×10⁻¹¹ |
| Moon / Earth | 1.022 km/s | 3.844×10⁸ m | 1.15×10⁵ J/kg | 6.64×10⁻¹¹ (slightly elliptical orbit) |

The speeds, distances, r₁, r₂, L and Φₚ all change, by up to a factor of 1,000, while potential depth × distance ÷ mass stays fixed. That sameness is what "G is constant" means. G is not a property of Earth, the Sun or P; it is the fixed exchange rate between mass and potential depth × distance.

### Caveat: where the value of G comes from

Orbits measure only the product G·m, never m alone. Separating G from m needs a laboratory measurement with known masses, such as the Cavendish torsion balance. So this framework shows that G is constant across systems, but its value in SI units comes from that laboratory measurement.

## 10. A non-circular definition of G

Sections 7–9 are circular: every form there already contains G. A non-circular definition uses only lengths, angles, times and masses measured without G, and the Cavendish torsion balance gives one: G = 2π²·L·r²·θ / (M·T²).

### Where the circularity is

| Quantity | How it was defined | Where G hides |
| --- | --- | --- |
| Φ (potential depth) | G·m/d | directly |
| ρ (gravitational radius) | G·m/c² | directly |
| L (equal-strength level) | ρ/r, or √(F/F\_max) | through ρ, or through F and F\_max |
| F\_max | c⁴/G | directly |
| F | G·m₁m₂/r² | directly |

So "G = Φ·d/m" rearranges a definition. It shows how G connects these quantities, but it does not measure G.

### The rule for a non-circular definition

Every input must come from a basic instrument, without using G:

- Length: a ruler or laser
- Angle: a protractor or optical lever
- Time: a clock
- Mass: a balance, which gives kilograms through the SI standard and does not involve gravity's strength

Units then force the shape of any such formula:

```latex
G = (\text{pure number}) \times \frac{\text{length}^3}{\text{mass} \times \text{time}^2}
```

As a ratio, G means metres³ of motion per kilogram per second².

### Non-circular formula 1: the Cavendish torsion balance

A rod of length L carries two small balls and hangs from a thin wire. Two large balls of mass M sit at distance r from the small ones. Gravity twists the rod by a small angle θ, and the rod swings with period T.

The swing period gives the wire's stiffness, and the twist balances gravity's torque:

```latex
\kappa = \frac{2\pi^2\, m\, L^2}{T^2} \qquad \kappa\,\theta = \frac{G\,M\,m\,L}{r^2}
```

The small-ball mass m cancels:

```latex
G = \frac{2\pi^2\, L\, r^2\, \theta}{M\, T^2}
```

| Input | Instrument | Contains G? |
| --- | --- | --- |
| L, r | ruler or laser | no |
| θ | optical lever | no |
| T | clock | no |
| M | balance (kg) | no |

Illustrative numbers, close to Cavendish's 1798 setup:

| Input | Value |
| --- | --- |
| M | 158 kg |
| L | 1.86 m |
| r | 0.225 m |
| T | 420 s |
| θ | 1.00×10⁻³ rad |

G = 2π² × 1.86 × 0.225² × 1.00×10⁻³ / (158 × 420²) = 6.67×10⁻¹¹ ✓

### Non-circular formula 2: G as an orbit ratio

Kepler's law gives a cleaner ratio. Any small body orbiting a known mass M gives:

```latex
G = \frac{4\pi^2}{M}\cdot\frac{a^3}{T^2} = \frac{4\pi^2\,(r_1 r_2)^{3/2}}{M\,T^2}
```

- a³/T² is the orbit's size cubed over its period squared: pure geometry and timing, with no G.
- M comes from a balance.
- The second form uses r = √(r₁·r₂) from section 1.

So G is the ratio of orbit size³ per period² to mass, times 4π². The torsion balance is the lab version of this: its swing period plays the role of the orbital period.

The one limit: the Sun and planets cannot be weighed on a balance, so their orbits measure only the product G·M. That is why a lab measurement comes first.

### The non-circular order

1. Measure G once in the lab, from lengths, an angle, a time and a mass in kg.
2. Measure G·M for each body in the sky from its orbit (a³/T²). This needs no G.
3. Divide: M = (G·M)/G. This is how the Sun's mass is known.
4. Then define Φ, ρ, F\_max, L and P as before. They are now derived from measurements, not circular.

In this order, sections 7–9 are consistent consequences of step 1 rather than definitions of G.

## 11. G as a balance ratio

G can be read as a balance ratio without a lab instrument, with time as the only observed quantity besides distance. Three balances do it. Each fixes what G means; its size still comes from one observation.

### Balance 1: gravity against motion (the orbit)

In a circular orbit, gravity exactly balances the turning motion. That balance contains only geometry and observed time:

```latex
K = \frac{4\pi^2\, a^3}{T^2} = v^2\, r
```

K is the body's gravitational mass in m³/s², read straight from its orbit with no G and no instrument. (K is not the reduced mass μ of section 8, which is in kg.) A body also has an inertial mass M in kg, which is a balance too: force against acceleration, F = M·a. G is the exchange rate between the two balances:

```latex
G = \frac{K}{M} = \frac{\text{gravitational mass (orbit)}}{\text{inertial mass } (F = M a)}
```

| Body | K from orbits (m³/s²) | M (kg) | G = K/M |
| --- | --- | --- | --- |
| Sun | 1.327×10²⁰ | 1.989×10³⁰ | 6.674×10⁻¹¹ |
| Jupiter | 1.267×10¹⁷ | 1.898×10²⁷ | 6.675×10⁻¹¹ |
| Earth | 3.986×10¹⁴ | 5.972×10²⁴ | 6.674×10⁻¹¹ |

The ratio is the same for every body. That is the equivalence principle: gravitational mass is always proportional to inertial mass, and G is the proportionality constant.

### Balance 1 with P: G as a product of two balance ratios

Section 8 gives a second balance ratio, about how the two bodies share one orbit. It comes only from where P sits:

```latex
\frac{\mu}{M} = \left(\frac{r}{r_1 + r_2}\right)^2 = \frac{m_1 m_2}{(m_1 + m_2)^2}
```

This ratio has no units and changes from system to system, so it is not G. Splitting G = K/M through the reduced mass μ:

```latex
G = \frac{K}{M} = \frac{K}{\mu}\cdot\frac{\mu}{M} = \frac{K}{\mu}\left(\frac{r}{r_1 + r_2}\right)^2
```

| Factor | Meaning | Units | Same for every system? |
| --- | --- | --- | --- |
| K / μ | orbit balance per kg of reduced mass | m³·kg⁻¹·s⁻² | no |
| (r / (r₁ + r₂))² | how the two bodies share the balance, from P | none | no |
| Product = G | gravity against inertia | m³·kg⁻¹·s⁻² | yes |

Neither factor is constant alone, but the product is: changes in the P geometry exactly cancel changes in K/μ.

| System | K / μ | (r / (r₁ + r₂))² | Product = G |
| --- | --- | --- | --- |
| Earth / Sun | 2.22×10⁻⁵ | 3.00×10⁻⁶ | 6.67×10⁻¹¹ |
| Moon / Earth | 5.53×10⁻⁹ | 1.20×10⁻² | 6.64×10⁻¹¹ (slightly elliptical orbit) |

This is why K and μ must stay separate symbols. Writing both as μ would turn K/μ into 1 and leave G = (r/(r₁ + r₂))², a unit-free number that changes with the system (3.0×10⁻⁶ for Earth/Sun, 0.012 for Moon/Earth) and is not G.

### Balance 2: gravity against light (F\_max at P)

From section 7, F = F\_max·(ρ₁/r₁)·(ρ₂/r₂). Each ratio ρ/r reaches 1 when that body's P sits at its gravitational radius, where its pull matches the limit set by light:

```latex
F = F_{\max} \text{ when } \frac{\rho_1}{r_1} = \frac{\rho_2}{r_2} = 1, \qquad G = \frac{c^4}{F_{\max}}
```

F\_max is not measured: it is the force at the far end of the balance scale. Every real force is F\_max times how far each body is from its own balance point. For Earth–Sun both ratios are 1.71×10⁻¹¹, so F = F\_max × (1.71×10⁻¹¹)² = 3.54×10²² N.

### Balance 3: gravity against the quantum (unit-free G)

Any mass has a quantum size, ħ/(m·c), and a gravitational size, G·m/c². They balance at exactly one mass, the Planck mass:

```latex
m_P = \sqrt{\frac{\hbar\, c}{G}} = 2.18\times10^{-8}\ \text{kg} \qquad G = \frac{\hbar\, c}{m_P^2}
```

Comparing a real particle with that balance point removes every unit:

```latex
\alpha_G = \left(\frac{m_p}{m_P}\right)^2 = \frac{G\, m_p^2}{\hbar\, c} = 5.9\times10^{-39}
```

This pure number holds G's full content: how far a proton sits below the gravity–quantum balance point. The electric version gives the same kind of number: between two protons, gravity / electric force = 8.1×10⁻³⁷.

### How the three balances connect

| Balance | What balances | G as a ratio | Observed input |
| --- | --- | --- | --- |
| 1. Orbit | gravity = motion | G = K/M | time T and size a |
| 2. Light | ρ/r = 1 at P | G = c⁴/F\_max | c (light's time per metre) |
| 3. Quantum | quantum size = gravitational size | G = ħ·c/m\_P² | the pure number α\_G = 5.9×10⁻³⁹ |

All three say the same thing: G measures how far everyday matter sits from gravity's balance point. Balance 1 compares two kinds of mass, balance 2 compares a force with its limit, and balance 3 compares a mass with the Planck mass.

### The open problem

The balances fix what G means, not its value. Each keeps one observed number: T in balance 1, the size of F\_max in balance 2, or α\_G = 5.9×10⁻³⁹ in balance 3. No current theory explains why α\_G has that size; why gravity is about 10³⁸ times weaker than the other forces is the open "hierarchy problem".

> G is the constant ratio between a body's gravitational mass (read from orbit timing) and its inertial mass. Its size reflects how far ordinary matter sits below the Planck balance point, α\_G = 5.9×10⁻³⁹.

## 12. G is a product of two balanced ratios

The orbit gives one total balance, K. The point P splits that total between the two bodies. G turns each body's share back into kilograms:

```latex
G = \frac{K}{\mu}\left(\frac{r}{r_1 + r_2}\right)^2 = \frac{K}{M}
```

### The orbit balance K: one total for the pair

K = 4π²a³/T² comes from watching the orbit. It is not one body's property; it is the pull of the pair together:

```latex
K = G\,(m_1 + m_2) = G\,M
```

The orbit cannot tell how K divides between the two bodies. That is what P does.

### How P shares the balance

Taken as fractions of their sum, r₁ and r₂ equal each body's share of the total mass:

```latex
\frac{r_1}{r_1 + r_2} = \frac{m_1}{M} = f_1 \qquad \frac{r_2}{r_1 + r_2} = \frac{m_2}{M} = f_2
```

So P splits r₁ + r₂ in the same proportions as the masses. Each body's share of the orbit balance is its distance to P over the total:

```latex
G\,m_1 = K\,\frac{r_1}{r_1 + r_2} \qquad G\,m_2 = K\,\frac{r_2}{r_1 + r_2}
```

The sharing factor is the product of the two shares. Since r = √(r₁·r₂):

```latex
\left(\frac{r}{r_1 + r_2}\right)^2 = \frac{r_1 r_2}{(r_1 + r_2)^2} = f_1 f_2 = \frac{\mu}{M}
```

It is largest, 1/4, for equal masses, and tiny when one body dominates.

### G as the exchange rate

```latex
G = \frac{K}{\mu}\, f_1 f_2 = \frac{K}{M}
```

- K/μ is the whole orbit balance measured against the reduced mass μ, the effective orbiting mass. On its own it overstates G by M/μ.
- f₁·f₂, from P, corrects that by exactly how the pair shares the balance.

**G is the orbit balance per kilogram of total mass. P tells how that balance divides between the bodies, so G applies equally to each body's share.** That is why G comes out the same for both bodies and for every system.

### Checks

Earth / Sun (K = 1.327×10²⁰ m³/s²):

| Quantity | Earth | Sun |
| --- | --- | --- |
| Share fᵢ = rᵢ/(r₁ + r₂) | 3.00×10⁻⁶ | 0.999997 |
| G·mᵢ = K·fᵢ | 3.986×10¹⁴ m³/s² | 1.327×10²⁰ m³/s² |
| Known G·m | 3.986×10¹⁴ ✓ | 1.327×10²⁰ ✓ |
| G = K·fᵢ / mᵢ | 6.674×10⁻¹¹ | 6.674×10⁻¹¹ |

Moon / Earth (K ≈ 4.02×10¹⁴ m³/s², from v and r):

| Quantity | Moon | Earth |
| --- | --- | --- |
| Share fᵢ | 0.0121 | 0.9879 |
| G·mᵢ = K·fᵢ | 4.88×10¹² m³/s² | 3.97×10¹⁴ m³/s² |
| Known G·m | 4.90×10¹² | 3.99×10¹⁴ |

The Moon/Earth values are about 0.5% off because the Moon's orbit is not a perfect circle.

Equal masses show the mechanism plainly: f₁ = f₂ = 1/2, so f₁·f₂ = 1/4, and P sits at the apex of the equilateral triangle from section 6. Then K/μ = 4G, and the factor of 4 is exactly undone by the 1/4 from P.

## 13. Symbol reference

Every symbol used in sections 1–12, with what it means, what it looks like in the geometry, its formula and how it is defined. Earth–Sun values are in brackets. M₁ and M₂ name the bodies; m₁ and m₂ are their masses; M is the total mass.

### Bodies and distances

| Symbol | Meaning | Geometric meaning | Formula | Definition |
| --- | --- | --- | --- | --- |
| m₁ | Mass of the small body M₁ (Earth) \[5.972×10²⁴ kg\] | The circle M₁ in the sketch | m₁ = f₁·M | Inertial mass in kg, from a balance (F = m·a) |
| m₂ | Mass of the large body M₂ (Sun) \[1.989×10³⁰ kg\] | The circle M₂ in the sketch | m₂ = f₂·M | Inertial mass in kg, from a balance |
| M | Total mass of the pair | – | M = m₁ + m₂ = μ·((r₁ + r₂)/r)² | Sum of the two masses |
| μ | Reduced mass \[≈ 5.97×10²⁴ kg\] | – | μ = m₁m₂/(m₁ + m₂) = M·f₁f₂ | The effective mass of the two-body orbit |
| r | Separation \[1.496×10¹¹ m, 1 AU\] | The segment between the two centres | r = √(r₁·r₂) | Measured centre-to-centre distance |
| r₁ | Distance from M₁ to P \[2.59×10⁸ m\] | Radius of the circle around M₁ on which P lies | r₁ = r·√(m₁/m₂) | Distance at which M₁'s pull equals M₂'s pull at M₁ |
| r₂ | Distance from M₂ to P \[8.63×10¹³ m, 577 AU\] | Radius of the circle around M₂ on which P lies | r₂ = r·√(m₂/m₁) | Distance at which M₂'s pull falls to M₁'s pull at distance r |
| P | The measuring point | Where the r₁ circle around M₁ meets the r₂ circle around M₂; for a shared point, on the Cassini oval | M₁P · M₂P = r² | The point both r₁ and r₂ are measured to |
| a | Orbit size (semi-major axis) | Radius of the orbit, for a circle a = r | a = r (circle) | Observed size of the orbit |

### Balance and geometry

| Symbol | Meaning | Geometric meaning | Formula | Definition |
| --- | --- | --- | --- | --- |
| ε | Balance ratio \[1 when balanced\] | Where the point (r₁, r₂) sits against the hyperbola r₁r₂ = r²: below is too strong, above is too weak | ε = r₁·r₂/r² | How far the r₁·r₂ split is from Newton's r² |
| k | Scale factor \[1.733×10⁻³\] | How much r₁ is shrunk and r₂ stretched relative to r | k = r₁/r = r/r₂ = √(m₁/m₂) | The stretch that keeps r₁·r₂ = r² |
| φ | Golden ratio \[1.618\] | Where the Cassini oval crosses the line M₁M₂: at 0.618·r and 1.618·r | φ = (1 + √5)/2 | Solution of d(d + r) = r² on the line |
| f₁, f₂ | Mass shares \[3.0×10⁻⁶ and 0.999997\] | P divides r₁ + r₂ into these proportions | fᵢ = rᵢ/(r₁ + r₂) = mᵢ/M | Each body's fraction of the total mass |
| f₁·f₂ | Sharing ratio \[3.0×10⁻⁶\] | The square of r/(r₁ + r₂) | f₁·f₂ = (r/(r₁ + r₂))² = μ/M | How the two bodies share one orbit balance; largest (1/4) for equal masses |

### Force and orbit

| Symbol | Meaning | Geometric meaning | Formula | Definition |
| --- | --- | --- | --- | --- |
| F | Newton's gravitational force \[3.54×10²² N\] | – | F = G·m₁m₂/r² | Mutual pull between the two bodies |
| F′ | Modified force | – | F′ = G·m₁m₂/(r₁·r₂) = F/ε | Newton's law with r² split into r₁·r₂ |
| v | Orbital speed \[29.78 km/s\] | Speed along the orbit circle, tangent to it | v = √(G·m₂·r/(r₁r₂)), which is √(G·m₂/r) when balanced | Observed: v = 2πr/T |
| T | Orbital period \[1 year\] | Time for one full loop of the orbit | T = 2π·√(a³/K) | Observed with a clock |
| K | Orbit balance, the pair's gravitational mass \[1.327×10²⁰ m³/s²\] | – | K = 4π²a³/T² = v²·r = G·M | Read from orbit size and timing, with no G |

### G and its parts

| Symbol | Meaning | Geometric meaning | Formula | Definition |
| --- | --- | --- | --- | --- |
| G | Gravitational constant \[6.674×10⁻¹¹ m³·kg⁻¹·s⁻²\] | – | G = K/M = (K/μ)·(r/(r₁ + r₂))² | The fixed exchange rate between gravitational mass (K) and inertial mass (M) |
| G₁, G₂ (Option A) | Local values of G seen from each side of P | Scale with the ratio of distances to P | G₁ = G·r₁/r₂, G₂ = G·r₂/r₁ | G = √(G₁·G₂), as r = √(r₁·r₂) |
| G₁, G₂ (Option B) | Each body's half of G | Scale with each distance to P | G₁ = √G·r₁/r, G₂ = √G·r₂/r | G₁·G₂ = G·ε, exactly G on the Cassini oval |
| Φ, Φₚ | Potential depth; Φₚ is its value at P \[1.54×10⁶ J/kg\] | – | Φ = G·m/d; Φₚ = L·c² = v²·√(m₁/m₂) | Energy per kg needed to climb out of a body's pull |
| ℓ, θ, κ (Cavendish) | Rod length, twist angle, wire stiffness (section 10, where the rod length is written L) | Rod hanging from a wire, twisted by angle θ | κ = 2π²·m·ℓ²/T²; G = 2π²·ℓ·r²·θ/(M·T²) | Lab measurement of G from lengths, an angle, a time and a mass |

### Light and quantum

| Symbol | Meaning | Geometric meaning | Formula | Definition |
| --- | --- | --- | --- | --- |
| c | Speed of light \[2.998×10⁸ m/s\] | Distance light travels per second | – | Fixed by the SI definition of the metre |
| ρ (ρ₁, ρ₂) | Gravitational radius \[4.43 mm Earth, 1,477 m Sun\] | The distance at which a body's strength ratio ρ/d reaches 1 | ρ = G·m/c² | A mass turned into a length |
| F\_max | Force limit \[1.21×10⁴⁴ N\] | The force when both bodies' P sit at their gravitational radii | F\_max = c⁴/G | The far end of the balance scale |
| L | Equal-strength level \[1.71×10⁻¹¹\] | Height of the horizontal level line in the Equal-Strength Point tool | L = ρ₁/r₁ = ρ₂/r₂ = √(F/F\_max) | The shared strength ratio at P (not the Cavendish rod length) |
| ħ | Reduced Planck constant \[1.055×10⁻³⁴ J·s\] | – | ħ = h/(2π) | Quantum of action |
| m\_P | Planck mass \[2.18×10⁻⁸ kg\] | – | m\_P = √(ħ·c/G) | The mass whose quantum size equals its gravitational size |
| m\_p | Proton mass \[1.673×10⁻²⁷ kg\] | – | – | Measured particle mass |
| α\_G | Gravitational coupling \[5.9×10⁻³⁹\] | – | α\_G = G·m\_p²/(ħ·c) = (m\_p/m\_P)² | Unit-free strength of gravity: how far a proton sits below the Planck balance point |

Two letters have more than one use in the doc: L is the equal-strength level in sections 7–11 but the rod length in section 10 (written ℓ here), and μ is the reduced mass, while the orbit balance is K.
