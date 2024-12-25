# Data Science Case Studies - Web Scraping and Visualization

The codes and plots for parliament web scraping task can be found in ```section_one```. You can view a summary of the overall analysis in the attached file ```parliament_case_study_analysis.pptx```.

## Code Structure

```bash
parliament_web_scraping
├── LICENSE
├── README.md
├── env.yml
└── section_one/
    ├── figures/
    ├── scraped_data/
    ├── data_visualisation.ipynb
    └── web_scraping.ipynb
```
## Conda Environment

The conda environment can be created by running the following command:

```bash
conda env create -f env.yml
```

<br>

If there is the need to update dependencies, make the changes in ```env.yml``` and run the command:
```bash
conda env update -f env.yml
```

## Section One

Web scraping was performed to obtain data from the [Official Reports - Parliamentary Debates](https://sprs.parl.gov.sg/search/#/home) in 
```web_scraping.ipynb```. The extracted data is stored in ```scraped_data```.

The data is then retrieved for visualisation in ```data_visualisation.ipynb```, and the respective plots are stored in ```figures```.
