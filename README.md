# The Office Character Interactions

## Description
This project aims to visualize the number of times the 17 main characters of the popular TV show "The Office" have mentioned each other's names in their dialogues over the course of 9 seasons. The project uses various data visualization techniques to bring out the relationships between the characters and the frequency of their mentions.

## Workflow
```mermaid
flowchart LR
  A[Installations] --> B[Imports]
  B --> C[Parsing]
  C --> D[Viz]
```

### Data Collection
The project uses web scraping techniques to collect the data for the dialogues of the 17 main characters from each episode of the 9 seasons of The Office. This data was then used to form a dataframe and keep a count of the mentions of each character's name. BeautifulSoup (bs4) package was used to scrap the data from a fandom website.

### Visualization Techniques
The following visualization techniques have been used in the project to depict the relationships between the characters and their frequency of mentions:

- Network Graph using Networkx
- Sankey Diagram using Plotly
- Heatmap using Seaborn
- Chord Plot using d3Blocks


## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You need to have the following packages installed:

pandas | numpy | matplotlib | seaborn | networkx | requests | bs4 | plotly | nbformat | d3blocks

You can install them using the following command:
```python
pip install pandas numpy matplotlib seaborn networkx
```

### Running the Project
Clone the repository to your local machine using the following command:

```git
https://github.com/venkycdmbrm98/The_Office_Character_Interactions.git
```
Open the Jupyter Notebook - TheOfficeViz.ipynb and run the cells to see the visualizations.

## Conclusion
This project provides a unique way to visualize the relationships between the characters of The Office and their frequency of mentions. It not only showcases the skills in data collection and data visualization but also provides an insight into the dynamics between the characters of the popular TV show.
