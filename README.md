# Boolean-Retrieval-Model
This project implements a Boolean retrieval model in Python that reads a
collection of documents and builds an inverted and positional index,
which is used to answer Boolean queries expressed as combinations of
terms and Boolean operators and Proximity queries expressed as terms
and k (Skip words value).

## Methodology
1. Data Preprocessing for stop words removal, lower case, stemming
and removing Unicode.
2. Built Inverted Index and applied precedence to deal with Boolean
queries and tokenization of queries.
3. Built Positional Index and extracted positional lists for Proximity
queries.
4. Skipped k words mentioned by the query by subtracting
positions and extracting the required k-positioned documents
## Limitations:
• It can run Boolean queries with unlimited "and or not"

• It can run with both upper and lower case "and or not"

• It can run complex queries with brackets. For eg:
( psl or t20 ) and ( cricket or rohit or india ) and ( not ( impossible
or pakistan ) )
## Usage
• Boolean Queries: spin AND feast

• Phrasal Queries: t20 world

• Proximity Queries: replacement players /9

## Requirements
Python 3.6 or later

pip (Python package installer)
## Installation
• Download and extract Project

• Install all the required Python packages

• Run ir_k201895_assignment_01.py file
