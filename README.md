# Dipole Moment Lab

An interactive practice tool for general and organic chemistry students on molecular dipole moments.

**Live tool:** https://lufox2021.github.io/Dipole-Moment-Lab/  
**Bond dipole moment database:** https://lufox2021.github.io/Dipole-Moment-Lab/database/

## How it works

1. **Draw the Lewis structure** of the molecule shown (Levels 1–3), or press **✎ Draw your own molecule** to analyze any neutral molecule.
2. **See it in 3D** with a dipole arrow on every polar bond (crossed arrows pointing toward the δ⁻ end).
3. **Draw the molecular dipole**: aim an arrow in the 3D view (Rotate, Move and Aim modes), or choose *No net dipole*.
4. **Submit**: the calculated dipole direction is shown on top of your arrow. Only the direction is graded; within ±25° counts as correct.

## Notes on the chemistry

- The calculated direction is the vector sum of bond dipoles (chemistry convention, arrow toward δ⁻). Bond moments come from standard bond-moment tables, with C–H = 0.30 D (C⁻–H⁺).
- Carbon monoxide is included as the classic exception: experiment gives C⁻O⁺, opposite to the bond-dipole prediction, and the tool grades against experiment there.
- Molecules where a lone pair opposes the bond dipoles (NF₃, PCl₃, OF₂, SF₄ …) are not in the graded problem set.
- Only neutral molecules are used, because an ion's dipole moment depends on the choice of origin.
- Experimental dipole moments shown in the feedback are gas-phase values from the NIST Computational Chemistry Comparison and Benchmark Database (CCCBDB).

## Bond Dipole Moment Database (`database/`)

A companion reference page with sortable, searchable tables and a CSV copy button:

- **Bond moments** from two published source sets (Smyth-type values and the common introductory-textbook table), with a side-by-side comparison.
- **Diatomics (CCCBDB):** 63 main-group diatomic molecules, where the measured molecular moment *is* the bond moment, with uncertainties and original references.
- **μ vs Δχ plot** for the closed-shell diatomics.
- **Decompose & transfer:** fits bond moments to the experimental dipoles of 38 molecules (vector sum, least squares), then predicts held-out molecules, with a leave-one-out transfer test.
- Aromatic group moments, reference molecular moments, and full sources.

Each tool is a single self-contained `index.html`; open it in any modern browser. No installation needed.
