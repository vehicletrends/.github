# Vehicle Trends

This organization hosts the open-source data and tools behind [vehicletrends.us](https://vehicletrends.us) — an interactive dashboard tracking trends in the U.S. automobile market.

The project was created by [Nithin Sarva](https://www.linkedin.com/in/nithin-sarva/) and [Dr. John Paul Helveston](https://jhelvy.com), an Associate Professor in the [Engineering Management and Systems Engineering Department](https://emse.engineering.gwu.edu/) at The George Washington University.

---

## Repositories

### [`vehicletrends`](https://github.com/vehicletrends/vehicletrends)

An R data package containing tidy, analysis-ready summary statistics on U.S. vehicle trends. Datasets cover:

- **Vehicle Miles Traveled (VMT)** — daily and cumulative mileage distributions by powertrain and vehicle type
- **Depreciation** — value retention curves by powertrain, vehicle type, make, and model
- **Market Share** — share of listings and share of dealers by powertrain, vehicle type, and price bin over time
- **Market Concentration** — Herfindahl–Hirschman Index (HHI) across U.S. census tracts
- **Registrations** — annual light-duty vehicle registration counts by state and powertrain (2016–2024)

Install from GitHub:

```r
# install.packages("remotes")
remotes::install_github("vehicletrends/vehicletrends")
```

📦 Package documentation: [pkg.vehicletrends.us](https://pkg.vehicletrends.us)

### [`dashboard`](https://github.com/vehicletrends/dashboard)

The source code for the [vehicletrends.us](https://vehicletrends.us) interactive dashboard, built with [Quarto](https://quarto.org). Visualizes the datasets from the `vehicletrends` R package with interactive charts, maps, and tables.

---

## Data Source

The underlying data consists of **74,894,001 new** and **94,658,664 used** vehicle listings from over 100,000 dealerships across all 50 U.S. states between 2018 and 2025, licensed from [marketcheck.com](https://www.marketcheck.com/). The raw listings are not public, but summary statistics are freely available through the R package and dashboard.

---

## Citation

If you use this project in your work, please cite it - see [vehicletrends.us/cite](https://vehicletrends.us/cite)

---

## License

The `vehicletrends` R package is licensed under the [MIT License](https://github.com/vehicletrends/vehicletrends/blob/main/LICENSE.md). The dashboard website and its content are licensed under [CC-BY-SA 4.0](https://vehicletrends.us/license).
