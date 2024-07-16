# Data Science Case Studies - Web Scraping and Visualization

The codes and plots for parliament web scraping task can be found in ```section_one```. The codes and plots in ```section_two``` focus on other datasets to extract insights via data visualization and perform some classification.

## Code Structure

```bash
parliament_web_scraping
├── LICENSE
├── README.md
├── env.yml
├── section_one/
│   ├── figures/
│   ├── scraped_data/
│   ├── data_visualisation.ipynb
│   └── web_scraping.ipynb
└── section_two/
    ├── data/
    ├── figures/
    ├── association.ipynb
    ├── classification.ipynb
    └── visualisation.ipynb
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

## Section Two

The following notebooks are independent from one another and should be run separately.

<br>

- ```association.ipynb```
- ```classification.ipynb```
- ```visualisation.ipynb```

<br>

The required data to run the above notebooks are stored in ```data```. All generated plots are saved in sub-folders of ```figures``` which correspond to the respective notebook names.