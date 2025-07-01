# mental-health-discussion-on-reddit
This repository contains the code used to analyze mental health-related discussions across multiple Reddit communities.
The file called main contains the whole analysis, which includes:
- A brief exploratory analysis
- Sentiment analysis
- Topic modeling with LDA and BERTopic
- Domain specific emotional tone analysis with customized lexicon
The other two files include the collection and preprocessing of data.

This analysis can be reproduced by following the instructions:
1. clone the repository

```git clone https://github.com/SamC-dev/mental-health-in-reddit.git```

2. create a virtual environment (if you have windows use the following command)

```python -m venv venv```

3. Install the dependencies contained inside requirements.txt

```pip install -r requirements.txt```

4. Store your Reddit credentials in a .env file

Be sure to avoid sharing sensitive data (e.g: your credentials and Reddit users' data)!
