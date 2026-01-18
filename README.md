# Literary Mapping Gazetteers

This repository hosts a **growing collection of literary gazetteers** developed for
digital mapping and spatial analysis of literary texts. It is designed as both a
**research repository** and a **pedagogical resource** for digital humanities work
on literary space.

The project foregrounds **gazetteer making as an interpretive practice**, showing
how spatial data derived from literary texts can be structured, annotated, and
visualized to support narrative analysis rather than merely illustrating locations.

---

## Project Scope

Rather than focusing on a single literary work, this repository is conceived as an
**extensible framework** for composing, documenting, and visualizing literary
gazetteers.

Across different case studies, the repository aims to:

- model literary space as structured, interpretable data  
- encode humanistic judgments (e.g. narrative function, sentiment) as annotations  
- support spatial visualization as a form of literary inquiry  
- provide reusable workflows for research and teaching  

Each gazetteer corresponds to a specific literary text while sharing a common
methodological foundation.

---

## Core Case Study: *The Sign of the Four* (1890)

The first completed gazetteer in this repository is based on  
Arthur Conan Doyle’s *The Sign of the Four*.

This case study demonstrates how digital mapping can illuminate:

- the spatial organization of detective fiction  
- London as an imperial metropolitan space  
- colonial locations as narratively and affectively charged sites  

Rather than treating places as neutral coordinates, the gazetteer encodes
interpretive attributes such as narrative role, emotional valence, and degree of
involvement in the plot. Spatial visualization thus functions as **literary
interpretation**, not cartographic reproduction.

---

## Methodological Orientation

All gazetteers in this repository share several guiding principles:

- **Human-in-the-loop data modeling**  
  Place data is manually extracted and annotated through close reading.

- **Gazetteer-first workflow**  
  Spatial analysis begins with structured tabular data, not with maps or GIS tools.

- **Interpretive attributes as data**  
  Sentiment, narrative relevance, and symbolic function are treated as analyzable
  variables.

- **Visualization as inquiry**  
  Maps are used to generate new questions about narrative structure, spatial
  relations, and historical context.

Detailed methodological documentation is provided in the `methodology/` directory.

---

## Repository Structure

```
literary-mapping-gazetteers/
│
├── README.md
│
├── gazetteers/
│   └── sign_of_the_four/
│       ├── README.md
│       ├── The Sign of the Four_Gazetteer_Chs.1-9.xls
│       └── The Sign of the Four_Gazetteer_Chs.1-9.csv
│
├── methodology/
│   ├── gazetteer_design.md
│   ├── annotation_guidelines.md
│   └── visualization_workflow.md
│
├── maps/
│   └── sign_of_the_four/
│
└── docs/
    └── classroom_workflow.md
```

Some directories represent planned or future additions as the repository expands.

---

## Tools and Platforms

- Spreadsheet software (e.g. Microsoft Excel or compatible tools)  
- **Datawrapper** for map visualization  
  https://www.datawrapper.de  

No programming or advanced GIS expertise is assumed.

---

## Pedagogical Use

This repository is intended for use in:

- literature and digital humanities courses  
- hands-on workshops on literary mapping  
- student projects involving spatial annotation  

Its modular structure allows instructors and students to reuse individual
gazetteers, compare multiple texts, or build new gazetteers following the same
methodological model.

---

## Citation

If you use or adapt materials from this repository, please cite:

> Yun, Misun. *Literary-Mapping-Gazetteers*. 2025.
> https://github.com/msyun207/Literary-Mapping-Gazetteers/.

A scholarly publication, "Mapping the Narrative Space of *The Sign of the Four*," *JTEL* 29.3 (2025): 105-42, accompanies the *The Sign of the Four* case study.

---

## License

- Gazetteer data and documentation are shared under **CC BY-NC 4.0**.  
- Reuse is permitted for research and educational purposes with attribution.

---

## Maintainer

**Misun Yun**  
Associate Professor of English Literature and Digital Humanities  
Inha University  

Research interests include nineteenth-century British fiction, literary mapping,
digital humanities pedagogy, and AI and narrative studies.

Contact: msy207@inha.ac.kr

---

## Future Development

Planned additions include:

- additional Sherlock Holmes texts  
- comparative London-based literary gazetteers  
- student-generated gazetteers created in classroom settings  
