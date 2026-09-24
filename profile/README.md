<div align="center">

<img src="profile/banner.svg" alt="CH4114 SBS group" width="100%" />

**Nine computational physics projects · nine private repositories · one register.**

[![Register](https://img.shields.io/badge/register-live-28407D?style=flat-square)](https://ch4114-tem-project-sbs-group.github.io/project-tracker/)
[![Projects](https://img.shields.io/badge/projects-9-E76051?style=flat-square)]
[![Access](https://img.shields.io/badge/access-view--only%20for%20members-A19D94?style=flat-square)](https://ch4114-tem-project-sbs-group.github.io/project-tracker/#access)

</div>

---

## The register

This organisation holds the project register for **CH4114** at IISER Kolkata. Each
roll number owns one private repository. Everyone in the group can read every
project; only the owner (and the maintainer) can write to it.

Read the full problem statements, methodology and analysis plans on the tracker:

> **https://ch4114-tem-project-sbs-group.github.io/project-tracker/**

---

## Projects

| Roll | Project | Area | Challenge |
| --- | --- | --- | --- |
| [`25RS109`](../../25RS109-water-phase-separation) | Low-temperature phase separation of water | Molecular dynamics | ML potentials, nucleation, ionic doping |
| [`23MS211`](../../23MS211-gold-nanostructures) | Material response of gold nanostructures | Nanomechanics | Gold-based alloys |
| [`25MP014`](../../25MP014-solvation-free-energy) | Solvation free energy | Free-energy calculations | ML potentials |
| [`23MS163`](../../23MS163-doped-crystals) | Doped crystals | Electronic structure · magnetism | Domain response to perturbations |
| [`23MS006`](../../23MS006-cof-mof-gas-adsorption) | Gas adsorption in COFs and MOFs | Porous materials | Humidity / moisture effects |
| [`23MS029`](../../23MS029-hbond-dynamics-solvation) | Solvation free energy and H-bond dynamics | Hydrogen bonding | Stable / metastable structures |
| [`23MS070`](../../23MS070-solvation-solvent-comparison) | Solvation free energy across solvents | Solvation thermodynamics | ML potentials |
| [`23MS164`](../../23MS164-josephson-junction) | Josephson junction | Quantum transport | To be discussed |
| [`25MP040`](../../25MP040-piezoelectric-crystals) | Piezoelectric response of crystals | Electromechanics | Doping effects |

---

## Access model

| Role | Read | Clone | Discuss | Write |
| --- | :---: | :---: | :---: | :---: |
| Group members | ✅ | ✅ | ✅ | ❌ |
| Project owner | ✅ | ✅ | ✅ | ✅ (own repo) |
| Maintainer | ✅ | ✅ | ✅ | ✅ |

Every repository is **private**. The organisation-wide default is **read**, so an
invited member immediately sees all nine projects and can follow the work without
being able to modify it.

Want a change in a repository you do not own? Open an issue. The owner lands it.

---

## Repositories

| Repository | What it holds |
| --- | --- |
| [`project-tracker`](../../project-tracker) | Public Astro site — problem statements, activity, changelog |
| [`.github`](../../.github) | This organisation profile |
| `25RS109-*` … `25MP040-*` | Nine private project repositories (above) |

Every project repository follows the same scaffold:

```
README.md            banner, problem statement, access model
ACCESS.md            who can read and who can write
environment.yml      reproducible software environment
docs/                problem-statement · methodology · analysis · software · timeline · references
simulations/         input decks and run scripts
analysis/            post-processing scripts (one per figure or table)
notebooks/           exploratory work
data/                raw and processed data (heavy files not committed)
results/             figures and tables (regenerated, not committed)
```

---

<div align="center">
<sub>CH4114 · Computational Physics · IISER Kolkata</sub>
</div>
