This is a small project which uses Natural Language Processing to give the user summary of any article. The user needs to give the url of the site as input.
A small description of the packages, libraries and the various methods used in the code is :-
• Beautiful Soup - A python library used to remove html and xml from documents.
• urrlib.requets – to fetch url’s
• Return type of urlopen – gives access to header from http server
• Using read() we can get the data of the url fetched.
• As we will first fetch all the paragraph tags from the article, we use the find_all method of beautiful soup on the object of beautiful soup article_parsed.
• p.text we find the data stoed in the p tags
• stopwords from nltk to remove unnecessary words like the,a,an etc
• PorterStemmer to find the root word of the different words ex. – cooking,cooked has root word cook
• Then making a dictionary with key being the word and value being the frequensvy of each word.
• Word_tokenize – to find out syllabuls from a single word
• Sent_tokenize – to split paragaraph into sentences
• Tkinter is used to make the gui for the project.
