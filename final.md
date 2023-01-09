# Final Report - Work in Progress
- Research Hypothesis / Questions:
    - Is Formula 1 fandom Toxic?
    - Are there specific groups that show more toxic behaviour then others?
    - Is the toxicity a "self-made" problem of Formula 1?
- APIs: Youtube
    - (Not reddit as post are often off topic especially during the off season, that we are currently in)
- Methods:
    - TBD
    - Dictionary
        - Formula 1 specific words that are toxic
        - racism / ethnic slurs -> [@ethnic_slurs]
        - toxicity -> [@orthrus-lexicon_orthrus_2022]
        - hate speech -> [@van_der_vegt_grievance_2021]
        - insults -> [@van_der_vegt_grievance_2021]
    - Transformer classifier
        - sentiment -> cardiffnlp/twitter-roberta-base-sentiment-latest [@tweet_sentiment_classifier]
        - racism -> jaumefib/datathon-against-racism [@hate_speech_classifier]
        - hate speech -> Hate-speech-CNERG/dehatebert-mono-english [@racism_classifier]
    - statistical analysis
        - group toxic behavior by drivers and teams
        - group by topics
            - topic modelling?
- Contents:
    - Introduction
        - What is Formula 1
        - Why do we need to analyze this
        - introduce the three research questions / hypothesis
    - Fundamentals
        - What is fandom
        - Defining toxic fan behavior
        - Youtube API
        - Maybe explaining the used methods?
    - Concept
        - What will be done
        - How will i be doing it
    - Creating the Dataset
        - Explain Dataset creation
    - Applying Method 1
    - Applying Method 2
    - Results


```python
import pandas as pd
```

<!--


```python
import os
os.system("jupyter nbconvert --to markdown final.ipynb")
os.system("pandoc -s final.md -t pdf -o final.pdf --citeproc --bibliography=refs.bib --csl=apa.csl")
```

    [NbConvertApp] Converting notebook final.ipynb to markdown
    [NbConvertApp] Writing 1791 bytes to final.md





    0




```python
-->
```
