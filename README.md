# Restaurant & Cafe data of Azerbaijan
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4EAEAA?logo=python&logoColor=fff)](https://seaborn.pydata.org/)

## Project Description
This project involves analyzing and visualizing restaurant data scraped from online sources. The data includes information such as restaurant names, votes, rating stars, and types. The project processes raw data, cleans it, and provides insights through various visualizations, such as rating distribution, top restaurant kinds, and the relationship between votes and ratings. Additionally, the cleaned data is saved for further analysis.

[Source website](https://oneclick.az/business/Restaurant/Restaurant/Restoranlar)

## Team Allocation
| Team Member                 | Role              | Contribution (%) |
|-----------------------------|-------------------|------------------|
| Ismayil Panahli (Team Leader) | Data Scraping & Processing   | 25%              |
| Shamsi Nagiyev               | Found websites for scraping    | 25%              |
| Huseyn Jafarli               | Machine Learning Part     | 25%              |
| Kazim Hummetov             | Testing & Debugging     | 25%              |

## Notes
- The `Votes` column required preprocessing to extract numeric data from text entries.
- The project uses Python libraries such as:
    - [NumPy](https://numpy.org/) and [Pandas](https://pandas.pydata.org/) for data analysis
    - [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for data visualization
    - [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) for data scraping
- The processed dataset is saved as `processed_data_team_13.csv` in the `./data/` directory.
