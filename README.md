# Andre Costa: Environmental Portfolio

A one-page portfolio for environmental, water resources and analyst work, built around my Senior Seminar capstone at San José State University. It is plain HTML, CSS and JavaScript with no build step, published with GitHub Pages.

**View it live:** [andrecosta505.github.io/Andre-s-Portfolio](https://andrecosta505.github.io/Andre-s-Portfolio/)

## What is in this repository

| File | What it is |
| :--- | :--- |
| `index.html` | The portfolio page: summary, skills, education and certifications, field and project experience, coursework, and a research-poster view of the capstone with its results charts |
| `senior-seminar.docx` | The full capstone paper |
| `resume.pdf` | Résumé |
| `favicon.svg` | Site icon |

## Senior Seminar capstone

**"A comparison of pH, nitrate and phosphate levels found in eutrophied and non-eutrophied ocean zones."**
San José State University, EnvS 198, spring 2023.

**Question.** Do pH, nitrate and phosphate levels differ between eutrophied and non-eutrophied North American coastal waters? The hypothesis was lower pH and higher nitrate and phosphate in eutrophied zones.

**Data.** NOAA's Coastal Ocean Data Analysis Product in North America, CODAP-NA (Jiang et al., 2020, [doi:10.25921/531n-c230](https://doi.org/10.25921/531n-c230)): 3,391 oceanographic profiles from 61 research cruises on the continental shelves of North America. Variables used: latitude, longitude, date, cruise ID, observation type, depth, nitrate, phosphate and pH (total scale, calculated in situ).

**Method.**

- Narrowed the dataset from **28,208 samples to 780** in Excel.
- Chose **seven site pairs**, each a eutrophied site and a non-eutrophied site on the same coastline and ocean current, by comparing the CODAP-NA sampling map with the World Resources Institute's eutrophication and hypoxia map and a NOAA ocean circulation map.
  - West Coast: Bodega Bay and Mendocino, Seal Beach and San Juanico, Vancouver and Tillamook
  - East Coast and Gulf of Mexico: Daytona Beach and Cárdenas, Bar Harbor and Sydney, Charleston and Virginia Beach, Port Sulphur and Tampico
- Kept depths of **0 to 200 m**, where light allows photosynthesis.
- Ran **three two-way ANOVAs without replication** (eutrophied or non-eutrophied, by East or West Coast), one each for pH, nitrate and phosphate.

**Results.** Mean values from the paper's Tables 1 to 3:

| Mean | West, eutrophied | West, non-eutrophied | East, eutrophied | East, non-eutrophied |
| :--- | ---: | ---: | ---: | ---: |
| Nitrate | 14.07 | 7.41 | 2.03 | 0.04 |
| Phosphate | 1.216 | 0.845 | 0.359 | 0.201 |
| pH | 7.923 | 7.964 | 8.013 | 8.022 |

Nitrate and phosphate were higher in eutrophied zones on both coasts. pH was lower in eutrophied waters overall; the pattern held at the West Coast sites, with no clear difference at the East Coast sites. The West Coast samples date from 2007 and the East Coast samples from 2017 and 2018, so the two coasts were examined separately, and the data cannot separate the effect of geography from the effect of time. The paper recommends a same-period comparison with more sites on each coast.

## View it locally

Clone or download the repository and open `index.html` in a browser. No build step or server is needed.

```
git clone https://github.com/andrecosta505/Andre-s-Portfolio.git
```

## About me

Andre Costa, Gilroy, California. Founder and designer at [Loomwest](https://loomwest.com), a web design studio for local businesses, and Design Engineer and Land Surveyor in Training at Faria Engineering & Surveying. [LinkedIn](https://www.linkedin.com/in/andre-costa-98535b199) · [GitHub](https://github.com/andrecosta505)
