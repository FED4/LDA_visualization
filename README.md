# LDA_visualization

## Create a Word Cloud for all topic and color words by per word topics
    LDAWordCloud(self, lda_model, id2word, top_n, **kwargs)
    
## Create a Word Cloud for specified topic n and color words by per word topics
    LDAWordCloud.plot_topic(self, n)
   

## Parameters

 lda_model: object
    LDA model by gensim
    
 id2word: dict(int -> str)
    dictionary of id to word mapping
        
 top_n: int
    number of top words to be shown in a topic
        
## Dependencies

    import math
    from wordcloud import WordCloud, STOPWORDS
    
    from wordcloud import (WordCloud, get_single_color_func)
    import matplotlib.pyplot as plt
