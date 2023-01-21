# semantics
This project aligns the ontology with external Knowledge Bases (KBs) such as DBpedia and Wikidata, and verifies if the provided links are valid. 

The instruction on how to launch, configure, and use the solution is below:

1. Install a compiler for Python (one of the following):
- PyCharm: https://www.jetbrains.com/pycharm/
- Anaconda: https://www.anaconda.com/products/distribution/

2. Installing the required packages in Python:
- For PyCharm: you need to go to PyCharm, temporarily create a project and open Terminal at the bottom
- For Anaconda: open Anaconda Prompt
In an open terminal or console, enter the following commands:
pip install rdflib
pip install sparqlwrapper
pip install multiprocessing
pip install pprintpp
pip install requests
pip install pandas
pip install asyncio
pip install aiohttp

3. Open main.py:
- For PyCharm: File->Open, find and select main.py
- For Anaconda: Open Jupyter Notebook and File->Open, find and select main.py

4. Run the code and wait. Once the execution is completed, the output will be appeared. All the generated files will appear in the folder with main.py. 
