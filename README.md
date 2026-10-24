# Siddharth Satte

Independent researcher, Pune, India. Thermal and lifetime models of electrochemical energy systems, and what the aggregate costs.

Most thermal and lifetime models rest on an aggregate: a cell as a uniform heat source, a stack as its mean cell voltage. My work measures what that assumption costs, how large the error is, what sets it, and how to carry it to a decision rather than assume it away. Every study here was run the same way: predictions committed to the repository before the analysis, failed predictions reported beside the held ones, and code, results and a one-page note archived with a DOI.

## Manuscripts (sole author)

- **Error of the uniform heat-generation assumption in base-cooled prismatic lithium-ion cells: the roles of current collection and event duration.** A 70 Ah prismatic cell modelled from published parameters, with the heat distributed over the foils, tab strips and foil-to-terminal joints by a current-collector solve; the uniform source underestimates the steady peak surface temperature by 0.06 K for a welded roll and by up to 5.9 K for the narrowest tabs, and misplaces the hot spot. Submitted for publication, October 2026. Preprint: [doi.org/10.2139/ssrn.7570666](https://doi.org/10.2139/ssrn.7570666). Code and data: [doi.org/10.5281/zenodo.23053419](https://doi.org/10.5281/zenodo.23053419).
- **Worst-cell degradation and stack-mean life projections in PEM fuel cell stacks: the IEEE PHM 2014 benchmark and a test on a heavy-duty stack.** The worst cell lost voltage 16.7 and 21.4 % faster than the stack mean, against 7.5 and 20.0 % from selection alone. Under review. Preprint: [doi.org/10.2139/ssrn.7564865](https://doi.org/10.2139/ssrn.7564865). Code: [doi.org/10.5281/zenodo.23054091](https://doi.org/10.5281/zenodo.23054091).

## Five pre-registered studies

| Repository | What it measures | Archive |
|---|---|---|
| [geslin-floor-pilot](https://github.com/siddharth161204-wq/geslin-floor-pilot) | The cell-to-cell lifetime floor in a public 92-cell dataset: duplicates under one protocol differ by 3.0 % on average and 8.7 % at the 95th percentile. | [10.5281/zenodo.23205412](https://doi.org/10.5281/zenodo.23205412) |
| [thermal-lever-duplicate-floor](https://github.com/siddharth161204-wq/thermal-lever-duplicate-floor) | Lifetime against temperature, measured in two laboratories' data (144 KIT cells, 86 Sandia cells): minus 3.45 to plus 1.91 % per kelvin near 35 °C with the sign set by the charge rate, and minus 2.44 for the same cell at Sandia; negative in every KIT protocol from 10 to 25 °C. | [10.5281/zenodo.23309130](https://doi.org/10.5281/zenodo.23309130) |
| [m50-two-cell-pilot](https://github.com/siddharth161204-wq/m50-two-cell-pilot) | A neighbour cell solved as one temperature and as a resolved field: the resolved hottest point reaches the self-heating temperature about a minute before the lumped node; the busbars carry 86 to 90 % of its heat intake. | [10.5281/zenodo.23253737](https://doi.org/10.5281/zenodo.23253737) |
| [m50-neighbour-onset-kinetics](https://github.com/siddharth161204-wq/m50-neighbour-onset-kinetics) | Published Bayesian runaway kinetics on that neighbour: over 200 posterior draws the lumped node never starts first, and the lead runs from 15 to 59 s. Against measured two-cell propagation tests, a trigger matched to the tests ignites neither neighbour by conduction and radiation; the ignition condition is the next question. | [10.5281/zenodo.23279455](https://doi.org/10.5281/zenodo.23279455) |
| [m50-radial-vs-resolved-field](https://github.com/siddharth161204-wq/m50-radial-vs-resolved-field) | The radial thermal model behind a published multi-unit cell model, tested in three dimensions: within 0.29 K with insulated ends; a one-term end correction cuts the cooled-end offset from 1.19 to 0.10 K. | [10.5281/zenodo.23320969](https://doi.org/10.5281/zenodo.23320969) |

Across the five studies, 92 predictions were committed before the data were opened; 35 failed and 2 could not be scored, and all are reported with the rest.

## Links

Research page: [siddharth161204-wq.github.io](https://siddharth161204-wq.github.io) · ORCID: [0009-0001-3584-1008](https://orcid.org/0009-0001-3584-1008) · siddharth161204@gmail.com
