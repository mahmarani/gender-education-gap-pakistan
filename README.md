# Gender Gap in Education Enrollment — Pakistan & South Asia

A data analysis project tracking the gender gap in education enrollment (primary, secondary, and tertiary levels) in Pakistan, with a regional comparison against neighboring South Asian countries.

## Why This Project

Education access is one of the clearest indicators of gender equality in a society. This project looks beyond a single snapshot to ask: **has Pakistan's gender gap in education actually been closing, and how does its trajectory compare to its neighbors?**

## Project Structure

```
gender-education-gap-pakistan/
├── README.md
├── gender_education_gap_analysis.ipynb
└── data/
    └── 4gender-gap-education-levels.csv
```

## Key Findings

- **Pakistan's primary education gap improved from 2003 to 2013 (17.9 → 8.6 points), but then partially reversed**, climbing back to 11.6 points by 2018 — progress was not linear or guaranteed to continue.
- **Pakistan's tertiary education gap looks small (under 1.5 points throughout), but this is misleading on its own.** Since overall tertiary enrollment is low for both genders (under 13%), the small gap likely reflects a "selection effect" among a privileged few who reach university — not genuine equality. The larger, more consequential gap is at the primary and secondary level, which affects far more of the population.
- **Most South Asian neighbors have moved toward — or reversed — the tertiary gender gap.** Nepal and Bangladesh shifted from male-favoring gaps toward female-favoring ones between 2003–2021, and Sri Lanka has shown a large female-favoring gap for over a decade.
- **Pakistan stands out as the most "stuck" country in the region at the tertiary level**, with its gap remaining close to zero throughout — neither closing nor reversing like its neighbors.
- **A data quality issue was identified and corrected during analysis**: comparing only each country's most recent value produced a misleading result for Bangladesh, which had only one valid data point for primary enrollment. This was caught by inspecting the raw numbers rather than trusting a surprising result at face value.

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib
- Jupyter Notebook

## Data Source

Global Education dataset (male/female enrollment rates by country and year), via Kaggle.

## Related Projects

This project is part of a broader series analyzing social and health outcomes in Pakistan:
- [Maternal Health in Pakistan & South Asia](https://github.com/mahmarani/maternal-health-pakistan)

## About Me

I'm a Computer Science student building toward a career in data analytics. This project is part of my portfolio as I work on real-world analysis projects and prepare for freelance and junior analyst roles.

[LinkedIn](https://linkedin.com/in/mahma-rani1) · [GitHub](https://github.com/mahmarani)
