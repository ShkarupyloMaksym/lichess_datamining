# Overview
## db_creation.ipynb
- Environment Setup and Dependencies: The notebook begins with commands to install necessary Python packages (zstandard for compression and chess for chess game analysis) and imports a suite of Python libraries for handling date and time, web requests, compression, chess game parsing, file operations, and random number generation.

- Constants Definition: It defines constants such as the name of the dataset (e.g., '2013 - July', '2017 - May') and sizes for the evaluated and cut datasets.

- Data Handling Instructions:

- Provides methods for converting month names to numbers, downloading files from URLs, and decompressing data.
It includes a section for downloading the dataset based on its name, suggesting that the notebook can handle data for different months or years.
Data Processing:

- There's functionality to create smaller subsets of the data for easier handling or specific analysis.
Methods for counting the number of games in large PGN (Portable Game Notation) files and splitting big PGN files into smaller ones based on the number of games.
The notebook also contains a process for filtering and creating PGN files that only include games with evaluations (probably using engine evaluations).
Export to CSV: It converts PGN files to CSV format, extracting game metadata into a structured form suitable for analysis. This part likely transforms chess game data into a tabular format, making it easier to analyze with tools like pandas.

- Use API to Get Players Info: This section deals with fetching detailed player information from Lichess API, including profiles, game counts, and other relevant metadata. It shows that the notebook not only processes game data but also enriches it with player-specific information.

- Cleaning Operations: The notebook includes functions to clear out files, potentially for cleanup after processing to save space or organize output.

- File Management and Export: Finally, there are snippets for deleting specific files and exporting data, possibly to share or move the processed information to different environments or storage solutions.
