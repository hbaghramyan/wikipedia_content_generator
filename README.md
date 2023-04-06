# wikipedia_content_generator
Extract the content from a Wikipedia webpage and generate a description

The code extracts the text from English Wikipedia page, breaks it down into words and sentences, eliminates common stopwords, 
and counts the frequency of individual words and bigrams within sentences. After that, it uses 10 most common words and bigrams to write a description to Wikipedia page. 
In the end, additionally I use some Transformer models to generate the description instead of creating it manually.
