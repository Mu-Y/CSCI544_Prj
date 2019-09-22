# crawler and genre classifier for lyrics

This is a classifier that can distinguish the genre of a song by analyzing its lyrics. Intuition is from the course project of USC CSCI 544. Final report is [here](final_report.pdf). 

This project accomplishes:
- Implement a Lyrics crawler to request meta data via [iTunes Search API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/index.html) and [Genius](https://genius.com/).
- Clean up the crawled lyrics(removing too-short lyrics, deduplication, etc.).
- Save the lyrics dataset as a single json file (`final.json`), which includes 30649 lyrics from 8 genres.
- We apply multiple Machine Learning classfiers to compare their performance on lyrics classification. 
