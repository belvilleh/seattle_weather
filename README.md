# Seattle Weather Project

> Comparison of annual rain data for Seattle, Washington and Kailua-Kona, Hawaii

---

## Project Overview

Summary analysis of precipitation data to determine which city receives more annual rainfall.

- **Objective:** Determine if Seattle rains more than Kailua-Kona
- **Domain:** Climate
- **Key Techniques:** Imputed missing data using average

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** (https://www.ncei.noaa.gov/cdo-web/search)
- **Description:** General precipitation records including inches of snow and rainfall
- **License:** N/A

---

## Analysis

Weather_Data notebook should be executed in order, and can be executed in indiviudal sections. Required data files are stored in ../data.

---

## Results

Seattle, Washington receives significantly more rainfall than Kona, Hawaii. The amount of precipitation in Seattle almost doubles the rainfall in Kona, and the snowfall in Seattle only accounts for a small portion of that precipitation. The only months where Seattle and Kona are not significantly different are March, May, and June.

---

## Authors

- Hannah Belville - [@belvilleh](https://github.com/belvilleh)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used:
        pandas
        numpy
        matplotlib.pyplot
        seaborn
        scipy
- Tutorials or papers referenced
        Data processing instructions from Dr. Fischer via Canvas
- Inspiration or collaborators
        Self completed
