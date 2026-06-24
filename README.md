# UAIV DataHub

**UAIV DataHub** is the unified public gateway for the UAIV low-altitude data ecosystem.

It is designed to be the clean first-stop page for:

- conference QR-code access;
- external visitors who need one stable project entry;
- collaborators who need to navigate across the dataset, annotation platform, and data-production infrastructure;
- readers who want to understand current public assets without digging through multiple repositories first.

> From low-altitude visual data to annotation, quality control, release packaging, and benchmark preparation.

## What DataHub Connects

UAIV DataHub does not host the full engineering stack itself.  
Instead, it connects three different layers of the UAIV ecosystem:

| Layer | Component | Role |
| --- | --- | --- |
| **Data Product** | **UAIV-Real / CityGov** | Standardized low-altitude city-governance dataset package |
| **Human Workbench** | **UAIV-Labeler** | Low-altitude-native multi-task annotation and review platform |
| **Data OS** | **UAIV-Foundry** | Data production, QA, release-readiness, dataset card, and benchmark protocol infrastructure |

In parallel, it also links to **LAMD-DATASETS**, which currently serves as a public-facing low-altitude dataset showcase.

## Current Public Asset Status

| Asset | Status | Public Role |
| --- | --- | --- |
| **LAMD-DATASETS** | Released | Public low-altitude multimodal dataset showcase |
| **UAIV-Real CityGov** | Release candidate | Flagship city-governance dataset package; standardized structure complete, public deposition still advancing |
| **UAIV-Labeler** | Released / live demo available | Production annotation and review workbench |
| **UAIV-Foundry** | Public project page ready | Data production and release infrastructure layer |
| **UAIV-Benchmark** | Planned | Future unified AI-ready benchmark layer |

## Why This Repository Exists

Without a gateway page, external users land on one isolated repository and miss the full system picture.

This repository exists to make the UAIV ecosystem legible:

1. `UAIV-Real` explains what data is being built and released.
2. `UAIV-Labeler` explains where human annotation and review happen.
3. `UAIV-Foundry` explains how data planning, QA, release checks, and benchmark preparation are organized.

The DataHub page is the bridge across these three concerns.

## Public Links

| Resource | Link |
| --- | --- |
| LAMD Project Page | https://jennyzhang0810.github.io/LowAltitude-Multimodal-Dataset/ |
| LAMD GitHub | https://github.com/JennyZhang0810/LowAltitude-Multimodal-Dataset |
| LAMD ScienceDB | https://www.scidb.cn/detail?dataSetId=203705443be44f7882bb9ddfd7d401da |
| UAIV-Labeler Project Page | https://jennyzhang0810.github.io/UAIV-Labeler/ |
| UAIV-Labeler GitHub | https://github.com/JennyZhang0810/UAIV-Labeler |
| UAIV-Labeler Demo | http://8.137.184.86/ |
| UAIV-Foundry Project Page | https://jennyzhang0810.github.io/UAIV-Foundry/ |
| UAIV-Foundry GitHub | https://github.com/JennyZhang0810/UAIV-Foundry |
| UAIV-Real GitHub | https://github.com/JennyZhang0810/UAIV-Real |

## Repository Scope

This repository should stay lightweight.

It is intended to contain:

- `index.html` for the public landing page;
- `README.md` and `DEPLOYMENT.md` for maintenance and publishing;
- a small `assets/` directory with only the visuals required by the landing page.

It should not become a dump for:

- raw images;
- annotation exports;
- internal logs;
- large model assets;
- private planning materials better kept in the individual component repositories.

## Repository Description

Recommended GitHub repository description:

```text
Unified gateway for UAIV low-altitude multimodal datasets, labeling platform, data foundry, and benchmarks.
```

Recommended topics:

```text
low-altitude-vision, uav, multimodal-dataset, data-centric-ai, annotation-tool, dataset-benchmark, computer-vision, remote-sensing, data-foundry, uaiv
```

## Files

```text
UAIV-DataHub/
├── index.html
├── README.md
├── DEPLOYMENT.md
├── assets/
└── .nojekyll
```

This repository is designed as a lightweight public portal. Data files, annotation exports, and engineering tools stay in their dedicated repositories. The page itself should remain small, visual, and safe to share publicly.
