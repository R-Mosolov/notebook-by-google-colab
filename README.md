# Sociology Scientometric Analysis

## The General Information
This repository contains the result of scientometric analysis of sociology using the dataset with articles from CyberLeninka (_N_ = 49820 articles). CyberLeninka is the Russian scientific database indexed in Russian Scientific Citation Index (RSCI).

## Notations
1. _Publication_ – article
1. _Common publication_ – publication with 2 and more co-authors

## The Scientific Indicators
| # | Indicator Title                    |
| - |:----------------------------------:|
| 1 | Full Author(-s) Name               |
| 2 | Publication Year                   |
| 3 | Article Title                      |
| 4 | Journal Level                      |
| 5 | Used Sources List                  |
| 6 | Journal Title                      |
| 7 | Annotation                         |
| 8 | Relevant Publications List         |
| 9 | Article PDF Version                |
| 10 | Article Text                      |
| 11 | Article Key Words                 |
| 12 | Article Views                     |
| 13 | Article Downloads                 |
| 14 | Author Link                       |
| 15 | Article Link                      |
| 16 | Used Sources Quantity             |
| 17 | Key Words Quantity                |
| 18 | Links Quantity with Self-Citation |
| 19 | Creative Commons Availability     |

## The Research Targets
### For analysis of articles list (metadata)
| # | Research Target | Needed Indicators |
| - |:---------------:|:-----------------:|
| 1 | Most puplicating author | Full Author(-s) Name |
| 2 | Average quantity of authors in publications | Full Author(-s) Name |
| 3 | Year of publications peak | Publication Year |
| 4 | Relativity between publications languages | Article Title |
| 5 | Relativity between levels of publications journals | Journal Level |
| 6 | Quantity of articles with free license (Creative Commons) in Russia | Creative Commons Availability |
| 7 | Correlation between author's publications quantity and journal levels where articles have published | Full Author(-s) Name, Journal Level |
| 8 | Check the hypothesis: average quantity of co-authors and publications intensivity have been lower before 2012 year and have grown after appearing # 2433-r «O gosudarstvennoj programme RF “Razvitie nauki i tehnologij”» order and «5-100» project | Full Author(-s) Name, Publication Year |

### For analysis of articles content
| # | Research Target | Needed Indicators |
| - |:---------------:|:-----------------:|
| 1 | Most citating publications | Used Sources List, Article Views, Article Downloads |
| 2 | Journals analysis | Journal Title, Journal Level |
| 3 | Most stable text revolutions using into annotations | Annotation |
| 4 | Correlation between an article view/downloads/citations | Used Sources List, Article Views, Article Downloads |
| 5 | Difference between a publication year and median value of an used sources year (degree of science information actuality) | Publication Year, Used Sources List |
| 6 | Average quantity of words/symbols in an annotation | Annotation |
| 7 | Hierarchy between authors of common publications | Full Author(-s) Name |
| 8 | Most stable terms at the scientific area | Article Title, Annotation, Article Key Words, Article Text |

## The Technological Stack
| # | Technology       | Functions                                                                       |
| - |:----------------:|:-------------------------------------------------------------------------------:|
| 1 | Python           | The main program language for analysis                                          |
| 2 | Requests         | Creates user sessions to parse initial data for analysis                        |
| 4 | Pandas           | Reads datasets as Excel files (CSV)                                             |
| 5 | Pandas Profiling | Generate a report about main, high level datasets information                   |
| 6 | NLTK             | Uses for content analysis to calculate frequency of words                       |
| 7 | Statistics       | Gives instruments complex with main statistics methods, e.g., mean, median, etc.|
