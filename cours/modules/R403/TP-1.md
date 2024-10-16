---
Author:
  - Alexis Opolka
  - Mathys Domergue
Subject: R403-TP1
Company: IUT de Béziers
Copyright: All Rights Reserved
---

# R403 - TP1

> [!NOTE]
> Sur ce TP, nous utiliserons un `Passe haut`.

<span style="text-align: center">

![circuit-theorique](./src/circuit-theorique.drawio.svg)

</span>

## Etablir $H(j \omega)$ et $\frac{\omega_c}{f_c}$

Nous avons:

$$

  H(j \omega) = \frac{u_s}{u_e} \\
  \frac{\omega_c}{f_c}

$$

## Déterminer RC pour $F_e \approx 10 \text{ khz}$

$$

  \omega_0 = \frac{1}{RC} \\
  2 \times 10 \times 10^3 \times \Pi = \frac{1}{RC} \\
  RC = \frac{1}{2 \times 10 \times 10^3 \times \Pi} \\
  RC = 1.59 \times 10^{-5} \\
  C = \frac{1.59 \times 10^{-5}}{10 \times 10^3} \\
  = 1.5 \textbf{ nF}

$$

## GBF Oscillo

[![table-values](./src/values.png)](https://github.com/alexis-opolka/import-cours-but-rt/blob/master/cours/modules/R403/src/values.png)

> [!NOTE]
> Phi se lit sur l'axe vertical de gauche, $u_e$ et $u_s$ se lisent sur l'axe vertical de droite.

> [!TIP]
> Cliquez sur l'image pour ouvrir sa version en ligne.
