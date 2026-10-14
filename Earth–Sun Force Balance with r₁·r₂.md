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
