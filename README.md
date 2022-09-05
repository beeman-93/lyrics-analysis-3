# lyrics-analysis-3
In this repository, I will clean the text data. There are 6 rounds of cleaning. 
Round1: Remove words in the [], because those words are not part of lyrics. Example: [Intro:]
Round2: Remove punctuation: "," , "'", "..."
Round3: We notice some lyrics are constructed like "meThen", "beforeLaying".
        # To solve this problem, we put a space in front of every capital letter. 
Round4: We lowercase the capitalized words.
Round5: Remove stopwords 
        Stopwords are words that have little meaning to the context such as "the", "is", and "and"
Round6: Second around of removing stopwords
        Let's see if there are more words that are better removed.
        First join verses together and convert into an array.  
        Then put the result in a series so that we can see what are the common used words in the lyrics.  
        And we see there are words such as "oh", "til", "like","til", "ay", "ah". 
        So we store them in a list and remove those words in the lyrics.
        
