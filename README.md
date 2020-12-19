# Resume-Pasrer

Resumer parser that helps you to get data from CV/resume  


## Installation

``` pip install requirements.txt ```

also you need nltk for  NLP (Natural Language Processing) 
``` #spacy english
python -m spacy download en_core_web_sm

#nltk
python -m nltk.downloader words
python -m nltk.downloader stopwords 
```
# Supported File Formats : 
* .pdf Files 
* .doc Files

# Structure 
You need to place your CV/Resume file in /resumes directory then all you have to do is :  
``` python resume.py ``` 

** P.S : just one resume file **

# Output 
The code will return a json file : data.json and it looks like this :  
``` {
    "name": "",
    "email": null,
    "mobile_number": null,
    "skills": [
        "C++",
        "Spanish",
        "Analyze",
        "Css",
        "C",
        "French",
        "German",
        "Requests",
        "Sql",
        "Html",
        "Drafting",
        "C#",
        "Python",
        "Javascript",
        "Technical",
        "Programming",
        "English",
        "Training",
        "Schedule",
        "Java",
        "Engineering"
    ],
    "education": [],
    "experience": [
        " Ubisoft Blue Byte Software Developer"
    ],
    "competencies": {
        "teamwork": [
            "support"
        ],
        "leadership": [
            "establish"
        ]
    },
    "measurable_results": {}
} ```

# References 
[link](https://medium.com/@divalicious.priya/information-extraction-from-cv-acec216c3f48)