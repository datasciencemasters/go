_These projects enable students to get hands on data with interesting and impactful projects. Projects contain a thesis or prompt, strengths focus, suggested tools and datasources._

## Types of Projects
- Tools that solve common problems in Data Science (software engineering)
- Analytical and predictive projects (pivot, correlation, testing)
- Theory-heavy projects (causal modeling, anomaly detection)
- Structure discovery (flow, graphs, topics)

## Projects

### 1) Memes and Twitter

**What is the half-life of a meme over time?** This project focuses on creative data sourcing, engagement measurement, and leverage your own beliefs about socio-cultural artifacts.

**Toolkit** Python `nltk`, Twitter API

- Start with trends.google.com and seek out a few "discrete cultural islands" that you find interesting. Search multiple memes and overlay them on each other. This visualization style may influence your own visualization styles.
- Use the twitter api to gather engagement around a handful of memes. Dig into knowyourmeme to find a few new ones. Iterate on that definition of engagement based on your intuition. Look for memes that have peaked at different points in the last ten years, then plot the engagement with each over time. 
- What other types of cultural media exhibit this half-life type of engagement cycle?
- Is there a difference between memes that are "funded" (movies, songs, books, etc) and non-economically-driven memes (ie: simple, easily mutable image memes like "Good Guy Greg", "Bad Luck Brian", and "Moth meme")?
- How many variations of a meme appeared? Does that relate to its popularity over time?


### 2) Neurodiversity in Literature
Google trends shows us how releveant a term is over time, but what about a phenomenon that has been named more recently? Many psychiatric phenomena have existed longer than we've "known" about them, but they may have been described.

**Toolkit** Python `nltk`, Gutenberg Texts

**What fictional characters exhibit psychiatric illness?** This project focuses on semantic analysis, natural language, and natural language in vector spaces.
- Search trends.google.com for "autism." When does it appear to show up? What can you learn about the point where medicine began describing the phenomenon?
- Read about the history of Autism, Schizophrenia, Depression, Bipolar on Wikipedia to learn about how medicine has come to understand the phenomenon of mental illness and non-neurotypicality and the people who experience it over time. Pay special attention to how a non-neurotypical person was described in various time periods.
- Download a sampling of literature in .txt from Gutenberg texts. Write a python script to try to write a rules-based prototyping of descriptors you found in Wikipedia articles about a particular mental disorder or non-neurotypical behavior. NLTK is a great tool for iterating on this problem.
- [Nate to complete suggested next steps / guide]


### 3) Migration and Climate in the United States
We know two things: people migrate from place to place in the United States, and the climate in every part of the US changes over times. **How does the climate relate to migration?** This project will require you to be thoughtful about building tools to help you parse lat/longs and manipulate data without full support from libraries.

**Toolkit** python

- Download Tiger migration data [Nate to help rewrite this] and average temperature of MSAs [Census Bureau?]
- What seems to be the "correct" climate? Does this differ by demographic (age, income, education, ethnic affiliation)?
- Where have people migrated over the last 30 years, and in what direction? Do you believe it will continue?
- How do you believe people's lives have changed over time as a result of changes in climate across the country? Do you believe there is a causal connection between movement of people and climate? How might you try to prove that it is causal or not causal?
- (Harder Task) What do you believe the next timestep will look like? What cities will grow?
- Search for tools online that enable you (for free) to visualize your results geospatially. Figure out how to produce data in a format that can be visualized, and produce your map(s).




