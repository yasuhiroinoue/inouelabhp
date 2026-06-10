---
title: "Our Research"
date: 2026-06-10T00:00:00+09:00
lastmod: 2026-06-10T00:00:00+09:00
showAuthor: false
authors:
  - "yasuhiroinoue"
showAuthorsBadges: false
---

## What kind of lab is this?

A beetle's horn, the jagged edge of a leaf, the tube that becomes the brain, a lobster's shell — living things take shape reliably, the same way every time, even though no one drew a detailed blueprint. How is that possible?

Our lab works to uncover the **mathematical laws hidden inside living systems**. Rather than only observing organisms, we rebuild their mechanisms as **mathematical models and computer simulations**. A model lets us predict "if this, then that," and by comparing the prediction with the real organism, we can discover the hidden rules behind it. We call this emerging field **"Life and Mathematical Sciences."**

What makes it exciting is that the rules we find in living things can also inspire **the design of robot legs and the creation of new materials**. Our reach spans from the motion of molecules, to cells, tissues, and the development of organs, all the way to the workings of **cognition** — what it means to "understand" or to "hesitate." Connecting everything from matter to mind in one mathematical language is the challenge we have set ourselves.

Below we introduce our research grouped into five themes, explained as plainly as we can. Each topic links to the original announcement and paper via "→ Learn more."

---

## 1. How is the "shape" of a living thing decided? — The mathematics of morphogenesis

![How the shape of a living thing is decided: the mathematics of morphogenesis](image/research/topic1-morphogenesis.png)

A flat sheet of cells (an epithelium) can fold, bulge, or form a mesh. Why do such different shapes arise from the same kind of cell? Using mathematical models, we showed that the **asymmetry of a cell's physical environment** is one of the principles that decide whether protrusions, folds, or meshes form. We also describe tissue shaping as an "energy landscape" to understand why shapes form so reliably and robustly.

- → [Environmental asymmetry in epithelial morphogenesis (Scientific Reports, 2022)](/en/news/2022-07-05-scientific-reports/)
- → [Epithelial folding in a confined geometry (2019)](/en/news/2019-11-15-epithelial-folding-bmmb/)
- → [An energy landscape of tissue morphogenesis (2019)](/en/news/2019-09-07-adachi-lab-bmmb/)

A beetle's magnificent horn grows from a crumpled, folded "horn primordium" inside the pupa. Through simulation, we deciphered how that folding blueprint encodes the 3D shape of the horn, and how **adhesion and shrinkage** transform a rounded shape into a sharp adult horn. We took on the same question in plants, showing in collaborative work why **a petal takes a different shape from a leaf**, and how **the sharp tip and concave joints of a leaf arise from growth rates that differ from region to region**.

- → [Folding that encodes the 3D beetle horn (Scientific Reports, 2021)](/en/news/2021-01-13-kondo-lab-sci-reports/)
- → [Adhesion and shrinkage make a rounded horn angular (Development, 2024)](/en/news/2024-03-13-kondo-lab-dev/)
- → [Why a petal differs in shape from a leaf (Development, 2022)](/en/news/2022-12-12-tsukaya-lab-dev/)
- → [Biregional growth that shapes leaf tips and joints (The Plant Journal, 2025)](/en/news/2025-07-09-tpj-leaf/)

Shaping also proceeds through the **rearrangement of cells**. In international collaboration, we revealed a new cell-rearrangement mechanism behind how the **neural tube** (the origin of the brain) is built. We also study **carapace morphogenesis as the spiny lobster metamorphoses**, and how **the curvature of the surface beneath a tissue directs its patterns**. On spheres the pattern goes from dots to a labyrinth; on elongated surfaces it forms beetle-horn-like zig-zags — the fate of a shape is written not only in molecular instructions but in the macroscopic geometry of the whole tissue.

- → [A new cell rearrangement that builds the neural tube (Current Biology, 2024)](/en/news/2024-11-28-hayashi-current-biology/)
- → [Carapace morphogenesis in lobster metamorphosis (Zoological Letters, 2026)](/en/news/2026-04-08-zoological-letters/)
- → [Surface curvature directs buckling patterns (JBSE, 2026)](/en/news/2026-06-04-jbse-kuninishi-mimura/)

---

## 2. Recreating cells and tissues in the computer — models and methods

![Recreating cells and tissues in the computer with models and methods](image/research/topic2-models.png)

To recreate morphogenesis in a computer, we first need a foundational model of "how to express a cell mathematically." We developed our own **"cell-center model,"** which represents cells as points (centers) to simulate three-dimensional tissue deformation, and we have released the code so anyone can use it.

How to compute a tissue's "bendability" on a computer (the **discretization of bending energy**) is a crucial problem that determines a simulation's accuracy. By comparing several methods, we clarified when to use which: one method when you want quantitatively accurate predictions, another when you want to capture the rough trend efficiently. This kind of **research into the methods themselves** underpins simulations we can trust.

- → [A cell-center model for 3D tissue deformation (JTB, 2023)](/en/news/2023-06-08-mimura-jtb/)
- → [Comparing bending-energy discretizations (arXiv, 2025)](/en/news/2025-03-01-mimura-arxiv-bending-energy/)
- → [Bending-energy discretization on anisotropic meshes (Transactions of JSCES, 2025)](/en/news/2025-08-26-mimura-jsces/)
- → [Review: computational mechanics of epithelial folding (JBSE, 2024)](/en/news/2024-03-14-morikawa-jbse-review/)
- → [Review: modeling viscous frictional forces in morphogenesis (2026)](/en/news/2026-02-19-koyama-biophysico/)

We also take on an "inverse" challenge. From **just two images** — before and after growth — we developed a way to infer "where, and how much, growth occurred." Reading the growth rules behind an observed shape is a technique that connects observation with models.

- → [Inferring differential growth from images (JTB, 2023)](/en/news/2023-10-25-morikawa-jtb/)

---

## 3. The "right and left hands" of molecules — chirality and the cytoskeleton

Your right hand and left hand look identical in a mirror, yet they can never be superimposed. The molecular world has the same "right vs. left" handedness (**chirality**), and life makes clever use of this difference.

**Actin filaments**, which act as the cell's internal scaffolding, form a variety of ordered structures simply through the rod-like "excluded-volume" effect of straight filaments avoiding one another. We further discovered that when the molecular motor **myosin** is active, high concentrations of actin spontaneously form **ring structures that all rotate in the same direction**. The result offers a clue to how left–right asymmetry (chirality) arises inside cells.

- → [Ordered structures from actin's rod-like excluded volume (Soft Matter, 2020)](/en/news/2020-01-02-purdue-collab-soft-matter/)
- → [Myosin-driven actin chiral rings (PNAS, 2026)](/en/news/2026-01-29-pnas-paper/)

We also study handedness at the level of individual molecules. In theory, right- and left-handed molecules should differ by a tiny amount of energy (the **parity-violating effect**). Through theoretical calculation, we showed the molecular conditions under which this minuscule difference can be **enhanced**, and that **exciting electrons can strengthen chirality**.

- → [Enhancing the parity-violating energy difference of chiral molecules (JPSJ, 2023)](/en/news/2023-11-06-kuroda-jpsj/)
- → [Enhancing molecular electron chirality by excitation (Physical Review A, 2024)](/en/news/2024-11-12-kuroda-pra/)

---

## 4. Manufacturing inspired by living things — robots, materials, and 4D printing

![Manufacturing inspired by living things: robots, materials, and 4D printing](image/research/topic4-manufacturing.png)

The ingenious mechanisms of living things offer hints for new ways of making things. Take the legs of a walking robot. Using a **genetic algorithm** (an optimization method that mimics biological evolution), we proposed a way to design a one-degree-of-freedom link leg mechanism that walks — without predefining its shape or trajectory. We then extended this to **multi-objective optimization** that satisfies several goals, such as speed and stability, at once.

- → [Link leg mechanism design without a predetermined trajectory (JAMDSM, 2024)](/en/news/2024-10-11-matsumoto-jamdsm/)
- → [Multi-objective link leg design via NSGA-II (MEJ, 2026)](/en/news/2026-01-15-matsumoto-mej/)

We also learned from how organisms turn flat sheets into 3D forms by **varying growth rates from place to place (differential growth)**. By simply 3D-printing non-shrinking resin pieces onto a heat-shrink film, we can freely produce a desired curved surface. Combined with a surface coating inspired by insect exoskeletons, the structural stiffness rose by about **166-fold**. The principles of biological morphogenesis are connecting to the materials engineering of the future.

- → [Curved-surface shaping and 4D printing from differential growth (J. R. Soc. Interface, 2026)](/en/news/2026-06-10-jrsi-morikawa/)

---

## 5. Cognition, "understanding," and play, in mathematics — from life to society and culture

![Capturing cognition, understanding, and play through mathematics](image/research/topic5-cognition.png)

Our interests are not limited to the bodies of living things. What does it even mean to **"understand"** something? We take on this philosophical question, too, from the standpoint of mathematical modeling.

Everyday "play" is also a research subject. We built a framework to mathematically systematize the **rules of pencil puzzles** such as Sudoku and Slitherlink, succeeding in writing those rules in a formal way. This opens the door to **automatic puzzle generation** by computer and to AI-assisted creation of diverse new rules.

A form that rises from matter goes on to process information (cognition), to relate to others, and to give rise to collective order — something we might call society or culture. Connecting every one of these layers in the same language of mathematics and computation is the future we envision for the Life and Mathematical Sciences.

- → [Toward a mathematical model of life and "understanding" (2022)](/en/news/2022-02-18-morikawa-tomita-collab/)
- → [A mathematical framework for pencil-puzzle rules (arXiv, 2025)](/en/news/2025-01-06-maeda-arxiv/)

---

## Want to know more?

What we have introduced here is just the entrance to our research. The latest results are posted regularly in our [News](/en/news/). If you are interested in joining the lab, please also see [To Prospective Students](/en/prospective-students/). The most original research in the world can begin from your own sense of "that's fascinating!"
