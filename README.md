# Data Analysis & Visualization Coursework
A portfolio of labs and assignments completed for a course at Western University. The work covers a progression from core Python programming to data analysis, visualization, network analysis, geospatial mapping, and natural language processing.

## 📂 Repository Structure

### Assignments

#### Spotify Dataset Analysis
#### `spotify-dataset-analysis.ipynb`
Exploratory data analysis of a Spotify tracks dataset using pandas. Covers data cleaning and transformation, descriptive statistics, boolean filtering, and data visualization with matplotlib.

**Visualizations:**

<div style="display: flex; gap: 16px;">
  <img src="[a2] Spotify Dataset Analysis/previews/genre-distribution.png" alt="Genre Distribution Pie Chart" width="48%">
  <img src="[a2] Spotify Dataset Analysis/previews/track-distribution.png" alt="World/Life Tracks Line Chart" width="48%">
</div>

#### eBook Dataset Analysis
#### `ebook-dataset-analysis.ipynb`
String parsing and data manipulation in Python using a Project Gutenberg eBook dataset. Covers string slicing and splitting, custom sorting functions, dictionary aggregation, and list manipulation.


### Labs

#### Network Analysis
#### `network-analysis.ipynb`
Introduction to network analysis using NetworkX and pandas. Covers graph theory concepts, building graphs from CSV data, computing weighted degree and betweenness centrality, and visualizing networks with node sizing scaled to centrality values.

**Visualizations:**

<div style="display: flex; gap: 16px;">
  <img src="Network Analysis/output/betweenness_centrality_network.png" alt="Betweeness Chart" width="48%">
  <img src="Network Analysis/output/relation.png" alt="Relation Chart" width="48%">
</div>

#### Movies Dataset Analysis I
#### `movie-dataset.ipynb`
Pandas lab using a Hollywood movies dataset (2,000 films). Covers loading and inspecting data, dropping and renaming columns, creating derived columns, sorting, and slicing DataFrames.

#### Movies Dataset Analysis II
#### `movie-dataset-extended.ipynb`
Structured data analysis and visualization using an extended movies dataset. Covers handling missing values, boolean filtering, label-based and positional slicing, value counts, and pie chart visualization with matplotlib.

#### Sentiment Analysis
#### `text-analysis.ipynb`
Sentiment analysis using spaCy on the 2017 *Beauty and the Beast* screenplay. Covers polarity and subjectivity scoring, interpreting sentiment results, analyzing a full screenplay sentence-by-sentence, and visualizing sentiment trends across the plot.


#### Geocoding & Interactive Maps
#### `geocoding.ipynb`
Geocoding and interactive map visualization using geopy and folium. Covers coordinate lookup, location attributes, multi-result geocoding, and adding custom markers to an interactive map centered on London, Ontario.

## 🛠️ Tools & Libraries

#### Data Science
| Library                             | Purpose                                     |
|-------------------------------------|---------------------------------------------|
| [pandas](https://pandas.pydata.org) | Data manipulation and analysis              |
| [NumPy](https://numpy.org)          | Multi-dimensional arrays and matrix support |

#### Data Visualization
| Library                                                  | Purpose                       |
|----------------------------------------------------------|-------------------------------|
| [matplotlib](https://matplotlib.org)                     | Static data visualization     |
| [folium](https://python-visualization.github.io/folium/) | Interactive map visualization |

#### Network Analysis
| Library                          | Purpose                                                  |
|----------------------------------|----------------------------------------------------------|
| [NetworkX](https://networkx.org) | Relationships and communication patterns within networks |

#### Natural Language Processing
| Library                           | Purpose                                                  |
|-----------------------------------|----------------------------------------------------------|
| [spaCy](https://spacy.io)         | Advanced NLP pipeline and text processing                |
| [SpaCyTextBlob](https://spacy.io) | Sentiment analysis via polarity and subjectivity scoring |