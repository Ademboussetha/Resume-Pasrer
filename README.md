# Resume-Pasrer

Resumer parser that helps you to get data from CV/resume  
This is the first version so it has some errors (for exemple sometimes it doesnt't get all the informations from the resume).  
But i will work on it with time :D 

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
} 
```

# References 
This article helped me for NLP : https://medium.com/@divalicious.priya/information-extraction-from-cv-acec216c3f48
also this one : https://www.kaggle.com/nirant/hitchhiker-s-guide-to-nlp-in-spacy