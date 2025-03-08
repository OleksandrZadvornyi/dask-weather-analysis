# Distributed Weather Data Analysis with Dask

## Project Overview

This project uses Dask and Jupyter Notebook to perform distributed processing and analysis of daily weather station summaries from the Global Historical Climatology Network Daily (GHCN-Daily) dataset.

## Data Source

- **Dataset**: Global Historical Climatology Network Daily (GHCN-Daily)
- **Provider**: NOAA National Centers for Environmental Information (NCEI)
- **Full Dataset Link**: [GHCN-Daily Archive](https://www.ncei.noaa.gov/data/global-historical-climatology-network-daily/archive/)

The GHCN-Daily dataset is a comprehensive collection of daily meteorological observations from ground-based stations worldwide, providing crucial climate and weather data for research and analysis.

## Environment Setup

### Anaconda Environment

1. Clone the repository

```bash
git clone https://github.com/yourusername/weather-data-analysis.git
cd weather-data-analysis
```

2. Create Conda Environment with Dependencies

```bash
conda env create -f environment.yml
```

## Running the Notebook

Open Jupyter Lab:

```bash
jupyter lab
```

Navigate to and open the `dask-weather-analysis.ipynb` notebook.

## Key Components

- Distributed data processing using Dask
- Local cluster configuration
- Comprehensive weather station data analysis
- Metadata extraction
- Monthly climate statistics aggregation

## Performance Features

- Utilizes ~90% of available CPU cores
- Parallelizes data processing
- Includes Dask dashboard for real-time computation monitoring

## Potential Improvements

- Enhanced error handling
- Advanced statistical analyses
- Data visualization modules
- Cloud-based distributed computing support

## Citing the Dataset

When using this data in research or publications, please cite:

- NOAA National Centers for Environmental Information. (2024). Global Historical Climatology Network-Daily (GHCN-Daily) Dataset.

## Troubleshooting

- Verify Anaconda environment is activated
- Ensure all dependencies are installed
- Check data file column structures
- Confirm system resource availability

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Acknowledgments

- NOAA/NCEI for providing the GHCN-Daily dataset
- Dask Project for distributed computing tools
