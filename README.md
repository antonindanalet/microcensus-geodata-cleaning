# Geodata cleaning of the Mobility and Transport Microcensus '20 & '21
This R code cleans the geodata of the Swiss <a href="https://www.are.admin.ch/mtmc">Mobility and Transport Microcensus (MTMC)</a>:
- It makes sure that the geodata are coherent (e.g. distances are plausible)
- It adds some typologies based on the geodata (e.g. <a href="https://s.geo.admin.ch/91f3a3a9e2">public transport quality categories</a>)

This code is public but it cannot be run outside of the Swiss Federal Administration, since the raw data (input data) are not publicly available. This code shows what are the modifications that are made to the raw data. The goal is to be transparent about this data cleaning process before using these data for official analysis and making them available to researchers.
