This organization hosts the open-source data and tools behind [vehicletrends.us](https://vehicletrends.us) — an interactive dashboard tracking trends in the U.S. automobile market.

The project was created by [Nithin Sarva](https://www.linkedin.com/in/nithin-sarva/) and [Dr. John Paul Helveston](//https://jhelvy.com), an Associate Professor in the [Engineering Management and Systems Engineering Department](https://emse.engineering.gwu.edu/) at The George Washington University.

The main repositories are:

- [`dashboard`]([url](https://github.com/vehicletrends/dashboard)): Source code for the interactive data visualization dashboard (built using [Quarto]([url](https://quarto.org/))).
- [`vehicletrends`]([url](https://github.com/vehicletrends/vehicletrends)): Source code for the R data package containing tidy, analysis-ready summary statistics on U.S. vehicle trends. 

View the live dashboard at https://vehicletrends.us (preview below)

<div align="center">

<a href="https://vehicletrends.us/">
<img src="images/vehicletrends.gif" alt="gif of browsing through the main dashboard site" width="600"/>
</a>

</div>

## Data Source

The underlying data consists of **74,894,001 new** and **94,658,664 used** vehicle listings from over 100,000 dealerships across all 50 U.S. states between 2018 and 2025, licensed from [marketcheck.com](https://www.marketcheck.com/). The raw listings are not public, but summary statistics are freely available through the R package and dashboard.

## Citation

If you use this project in your work, please cite it - see [vehicletrends.us/cite](https://vehicletrends.us/cite)

## License

The `vehicletrends` R package is licensed under the [MIT License](https://github.com/vehicletrends/vehicletrends/blob/main/LICENSE.md). The dashboard website and its content are licensed under [CC-BY-SA 4.0](https://vehicletrends.us/license).
