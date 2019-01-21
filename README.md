# openmensa-feed-berlin
This repo provides daily updated openmensa xml feeds for Studierenden Werk Berlin's university canteens.

## Correctness
No guarantees are given. The data is fetched and parsed in a automatic fashion. So if the upstream website changes, this could lead to errors. Especially consider this in regard to meal annotations offered to allergic persons. You should only rely on information provided on site.

## Parser
The parser at https://github.com/escrl/openmensa-parser-berlin is used to generate feeds. If you detect an error feel free to file a bug or even better issue a pull request fixing it at the parser's repo.

## Data Source
Data is fetched from the official site of the canteens at https://www.stw.berlin/. Look at the parser for more details.
