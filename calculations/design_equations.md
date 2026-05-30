# Antenna Design Equations

## 1. Patch Width
W = c / (2 × fr × sqrt((εr + 1) / 2))
- c = 3 × 10^8 m/s (speed of light)
- fr = 3.5 GHz (resonant frequency)
- εr = 4.4 (FR-4 dielectric constant)
Result: Wp ≈ 29 mm

## 2. Effective Dielectric Constant
εeff = (εr + 1)/2 + (εr - 1)/2 × (1 / sqrt(1 + 12h/W))
- h = 1.6 mm (substrate thickness)
Result: εeff ≈ 3.75

## 3. Quarter-Wave Transformer Length
λg = λ0 / sqrt(εeff)
l = λg / 4
Result: l ≈ 21.8 mm

## 4. Patch Length
L = c / (2 × fr × sqrt(εeff)) - 2ΔL
Result: Lp ≈ 19 mm