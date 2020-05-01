fakenews-ml
# Detecting Fake News – ML using Python

Note: This coding solution was developed on 1st May 2020 when the World is in a critical condition dealing with the SARS CoV-2 or COVID 19 Virus which has turned into global pandemic. In this extreme situation, there has been an escalation in fake news circulation. There may be several reasons behind it and that is why tracing every single source and discontinuing the further spread of such misinformation may be a tedious task in itself and is probably impossible. Fake News can have serious impact and there is a necessity of somehow identifying whether a particular news is fake or true. 


# EFFECTS OF FAKE NEWS:
Anyone with a social media account has no doubt seen at least one example of such news. While fake news is nothing new, the consequences of such news related to COVID-19 demonstrates we have another epidemic moving alongside the current global pandemic. Fake news related to COVID-19 can negatively impact measures people are taking to try and prevent the spread of the virus, their own physical health, as well as their mental health.

If people actually believe that sipping water every 15 minutes can cure or prevent the virus, then people may stop taking measures recommended by the CDC that are aimed at reducing the spread of the virus. These include hand washing, social distancing, wearing masks in public, covering our own coughs or sneezes, and cleaning and disinfecting our homes. At a more extreme consequence, believing that a chemical is a treatment for the virus, when it is not scientifically proven, led a couple in Arizona to take chloroquine phosphate, leading to hospitalization and death. Additionally, believing that COVID-19 is a hoax can lead to people behaving as such, taking minimal to no measures to prevent the spread of the virus as well as sharing that belief online, leading not only to contracting the illness but also dying from it.

# OBJECTIVE: 
To develop a Machine learning model that can help detect whether a particular information is fake or true, which can aid in managing the SARS CoV-2 pandemic


# SOLVING THE PROBLEM:

TfidfVectorizer: 
TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

PassiveAggressiveClassifier:
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.
