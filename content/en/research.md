---
title: "Our Research"
date: 2026-06-10T00:00:00+09:00
lastmod: 2026-10-06T00:00:00+09:00
showAuthor: false
authors:
  - "yasuhiroinoue"
showAuthorsBadges: false
---

## What kind of lab is this?

A beetle's horn, the jagged edge of a leaf, the tube that becomes the brain, a lobster's shell — living things take shape reliably, the same way every time, even though no one drew a detailed blueprint. How is that possible?

Our lab works to uncover the **mathematical laws hidden inside living systems**. Rather than only observing organisms, we rebuild their mechanisms as **mathematical models and computer simulations**. A model lets us predict "if this, then that," and by comparing the prediction with the real organism, we can discover the hidden rules behind it. We call this emerging field **"Life and Mathematical Sciences."**

What makes it exciting is that the rules we find in living things can also inspire **the design of robot legs and the creation of new materials**. Our reach spans from the motion of molecules to cells, tissues, and organ development, all the way to the workings of **cognition** — what it means to "understand" or to "hesitate." Connecting everything from matter to mind in one mathematical language is the challenge we have set ourselves.

Below we introduce our research grouped into five themes, explained as plainly as we can. The links marked with arrows (→) lead to research announcements, where you can find links to the papers.

---

## 1. How is the "shape" of a living thing determined? — The mathematics of morphogenesis

![How the shape of a living thing is determined: the mathematics of morphogenesis](image/research/topic1-morphogenesis.png)

A flat sheet of cells (an epithelium) can fold, bulge, or form a mesh. Why do such different shapes arise from the same kind of cell? Using mathematical models, we showed that the **asymmetry of a cell's physical environment** is one of the principles that determine whether protrusions, folds, or meshes form. We also describe tissue shaping as an "energy landscape" to understand why shapes form so reliably and robustly.

- → [Environmental asymmetry in epithelial morphogenesis (Scientific Reports, 2022)](/en/news/2022-07-05-scientific-reports/)
- → [Epithelial folding in a confined geometry (2019)](/en/news/2019-11-15-epithelial-folding-bmmb/)
- → [An energy landscape of tissue morphogenesis (2019)](/en/news/2019-09-07-adachi-lab-bmmb/)

A beetle's magnificent horn develops from a crumpled, folded "horn primordium" that forms beneath the larval cuticle and unfolds during pupation. Through simulation, we deciphered how that folding blueprint encodes the 3D shape of the horn, and how **adhesion and shrinkage** transform a rounded shape into a sharp adult horn. We took on the same question in plants, showing in collaborative work why **a petal takes a different shape from a leaf**, and how **a leaf's sharp tip and the inward-curving regions on either side of it (concave joints) arise from growth patterns that differ from region to region**.

- → [Folding that encodes the 3D beetle horn (Scientific Reports, 2021)](/en/news/2021-01-13-kondo-lab-sci-reports/)
- → [Adhesion and shrinkage make a rounded horn angular (Development, 2024)](/en/news/2024-03-13-kondo-lab-dev/)
- → [Why a petal differs in shape from a leaf (Development, 2022)](/en/news/2022-12-12-tsukaya-lab-dev/)
- → [Biregional growth that shapes leaf tips and joints (The Plant Journal, 2025)](/en/news/2025-07-09-tpj-leaf/)

Shaping also proceeds through the **rearrangement of cells**. Through an international collaboration, we revealed a new cell-rearrangement mechanism underlying the formation of the **neural tube** (the precursor of the brain). We also study **carapace morphogenesis during spiny lobster metamorphosis**, and how **the curvature of the surface beneath a tissue directs its patterns**. On spheres the pattern goes from dots to a labyrinth; on elongated surfaces it forms beetle-horn-like zigzags — the fate of a shape is written not only in molecular instructions but also in the macroscopic geometry of the whole tissue.

- → [A new cell rearrangement that builds the neural tube (Current Biology, 2024)](/en/news/2024-11-28-hayashi-current-biology/)
- → [Carapace morphogenesis in lobster metamorphosis (Zoological Letters, 2026)](/en/news/2026-04-08-zoological-letters/)
- → [Surface curvature directs buckling patterns (JBSE, 2026)](/en/news/2026-06-04-jbse-kuninishi-mimura/)

---

## 2. Recreating cells and tissues on a computer — models and methods

![Recreating cells and tissues on a computer with models and methods](image/research/topic2-models.png)

To recreate morphogenesis on a computer, we first need a foundational model of "how to represent a cell mathematically." We developed our own **"cell-center model,"** which represents each cell as a single point (its center) to simulate three-dimensional tissue deformation, and we have released the code so anyone can use it.

How to compute a tissue's "bendability" on a computer (the **discretization of bending energy**) is a crucial problem that determines a simulation's accuracy. By comparing several methods, we clarified which method to use when: one method when you want quantitatively accurate predictions, another when you want to capture the overall trend efficiently. This kind of **research into the methods themselves** underpins simulations we can trust.

- → [A cell-center model for 3D tissue deformation (JTB, 2023)](/en/news/2023-06-08-mimura-jtb/)
- → [Comparing bending-energy discretizations (arXiv, 2025)](/en/news/2025-03-01-mimura-arxiv-bending-energy/)
- → [Bending-energy discretization on anisotropic meshes (Transactions of JSCES, 2025)](/en/news/2025-08-26-mimura-jsces/)
- → [Review: computational mechanics of epithelial folding (JBSE, 2024)](/en/news/2024-03-14-morikawa-jbse-review/)
- → [Review: modeling viscous frictional forces in morphogenesis (2026)](/en/news/2026-02-19-koyama-biophysico/)

We also tackle an **inverse problem**: we developed a way to infer where and by how much growth occurred from **just two images**, taken before and after growth. This ability to read the growth rules behind an observed shape links observation to modeling.

- → [Inferring differential growth from images (JTB, 2023)](/en/news/2023-10-25-morikawa-jtb/)

---

## 3. The "right and left hands" of molecules — chirality and the cytoskeleton

![The "right and left hands" of molecules: chirality and the cytoskeleton](image/research/topic3-chirality.png)

Your right and left hands are mirror images of each other, yet they can never be superimposed. The molecular world has the same "right vs. left" handedness (**chirality**), and life makes clever use of this difference.

We showed that **actin filaments**, which act as the cell's internal scaffolding, form a variety of ordered structures simply through the **excluded-volume effect** — straight, rod-like filaments avoiding one another. We further discovered that when the molecular motor **myosin** is active, actin at high concentrations spontaneously forms **ring structures that all rotate in the same direction**. The result offers a clue to how left–right asymmetry (chirality) arises inside cells.

- → [Ordered structures from actin's rod-like excluded volume (Soft Matter, 2020)](/en/news/2020-01-02-purdue-collab-soft-matter/)
- → [Myosin-driven actin chiral rings (PNAS, 2026)](/en/news/2026-01-29-pnas-paper/)

We also study handedness at the level of individual molecules. In theory, right- and left-handed molecules should differ by a tiny amount of energy (the **parity-violating effect**). Through theoretical calculations, we identified molecular conditions under which this minuscule difference can be **enhanced**. We also showed that **electronic excitation can enhance molecular electron chirality**.

- → [Enhancing the parity-violating energy difference of chiral molecules (JPSJ, 2023)](/en/news/2023-11-06-kuroda-jpsj/)
- → [Enhancing molecular electron chirality by excitation (Physical Review A, 2024)](/en/news/2024-11-12-kuroda-pra/)

---

## 4. Manufacturing inspired by living things — robots, materials, and 4D printing

![Manufacturing inspired by living things: robots, materials, and 4D printing](image/research/topic4-manufacturing.png)

The ingenious mechanisms of living things offer hints for new approaches to manufacturing. Take the legs of a walking robot. Using a **genetic algorithm** (an optimization method that mimics biological evolution), we proposed a way to design a one-degree-of-freedom link leg mechanism that walks — without predefining its shape or trajectory. We then extended this to **multi-objective optimization** that satisfies several goals, such as speed and stability, at once.

- → [Link leg mechanism design without a predetermined trajectory (JAMDSM, 2024)](/en/news/2024-10-11-matsumoto-jamdsm/)
- → [Multi-objective link leg design via NSGA-II (MEJ, 2026)](/en/news/2026-01-15-matsumoto-mej/)

We also learned from how organisms turn flat sheets into 3D forms by **varying growth rates from place to place (differential growth)**. By simply 3D-printing non-shrinking resin pieces onto a heat-shrink film, we can produce a variety of curved surfaces. With the addition of a surface coating inspired by insect exoskeletons, the structure became about **166 times stiffer**. These principles of biological morphogenesis can guide future advances in materials engineering.

- → [Curved-surface shaping and 4D printing from differential growth (J. R. Soc. Interface, 2026)](/en/news/2026-06-10-jrsi-morikawa/)

---

## 5. The mathematics of cognition, "understanding," and play — from life to society and culture

![Capturing cognition, understanding, and play through mathematics](image/research/topic5-cognition.png)

Our interests are not limited to the bodies of living things. What does it even mean to **"understand"** something? We take on this philosophical question, too, from the standpoint of mathematical modeling.

Everyday "play" is also a research subject. We built a framework to mathematically systematize the **rules of pencil puzzles** such as Sudoku and Slitherlink, and succeeded in expressing those rules formally. This opens the door to **automatic puzzle generation** by computer and to AI-assisted creation of diverse new rules.

Mathematics also hides in the familiar act of stacking objects. We based our study on **Playstix**, a construction toy made of rods with periodic surface corrugations. Using theory and simulation, we showed that these rods can form a helicoidal stack **only at certain discrete angles** between successive layers. Each layer is rotated relative to the one below while their grooves remain in contact. The geometry of these stacks also helps us understand helicoidal structures found in living organisms and composite materials.

A form that arises from matter goes on to process information (cognition), to interact with others, and to give rise to collective order — something we might call society or culture. Connecting every one of these layers in the same language of mathematics and computation is the future we envision for Life and Mathematical Sciences.

- → [Toward a mathematical model of life and "understanding" (2022)](/en/news/2022-02-18-morikawa-tomita-collab/)
- → [A mathematical framework for pencil-puzzle rules (arXiv, 2025)](/en/news/2025-01-06-maeda-arxiv/)
- → [Angle conditions for helicoidal stacking of corrugated rods (JPSJ, 2026; Editors' Choice)](/en/news/2026-09-04-mimura-sato-jpsj/)

---

## Want to know more?

What we have introduced here is just a glimpse of our research. The latest results are posted regularly on our [News page](/en/news/). If you are interested in joining the lab, please also see our page for [Prospective Students](/en/prospective-students/). The most original research in the world can begin with your own sense of "that's fascinating!"
