# Final_individual_project
## The corpus
Wuxia World is a popular Chinese web novel platform that has attracted a large international readership since its founding in 2014 and is currently one of the world's largest English-translated Chinese web novel websites. I scraped all the reviews of Chinese novels (85 novels) on Wuxia World website, about 9000 reviews. To improve the efficiency, this assignment only selects the reviews of the top 5 novels in rating, about 500 of them, as the corpus.

## Target audience and the intended use of the corpus
The corpus can be used by scholars, readers, or the operators of the Wuxia World website and so on, which allows text mining of book reviews to extract keywords, popular topics, and other important information about the novel.

## Collecting data
I chose to use Selenium because the Wuxia World website has implemented an anti-scraping mechanism that requires browser simulation to obtain complete data. 

## Cleaning and preprocessing
Initially, non-English reviews are excluded, and any non-letter, number, space, or punctuation special characters are eliminated from the text. Furthermore, to ensure uniformity and streamline analysis, all reviews undergo a conversion to lowercase. As a subsequent step to enhance the corpus quality, invalid reviews can also be removed manually. 

## Adding annotations
By using spaCy for Lemmatization and Part-of-Speech (POS) tagging, thus making the text data more detailed and informative.
