# Exam Scientific Programming 2

Date: October 25 2023

This is a digital exam. The exam consists of 3 assignment in which you have to write a short python program.

You're only evaluated based on the _correctness_ of your solutions, code design is not important. So, you don't have to worry about comments or the style guide.

You can test your code using checkpy. First download the tests for the exam:

    checkpy -d /spcourse/exam-tests

Run checkpy:

    checkpy sp2_exam10

# Rules

- Create one file for all your solutions called `sp2_exam10.py`. This is the file you'll hand in at the end of your exam.
- You're only allowed to use `pandas` package. You're not allowed any other external Python package.
- You're only allowed to use the websites sp.mprog.nl and the Pandas documentation from https://pandas.pydata.org/. You're not allowed to use any other website. (So also no Google!)
- You are allowed to look at your own code that you wrote during the course.
- You cannot get any help with programming during the exam.
- Submit your solutions when you're done. **Check with the teacher present if you handed in your assignment correctly before leaving the exam venue.**

### 1. Alice

Write a Python function called `repeated_words(text)` that takes a text string as input and returns a list of words that appear more than once in the text. The function should consider words case-insensitively and should ignore common punctuation marks such as commas, periods, parentheses, exclamation marks, and question marks. You can use the following `tokenize()` function to convert the text to a list of words:

    def tokenize(text):
        return [word.strip(" ,\n.);(!?)'").lower() for word in text.split(' ')]

Example usage 1:

    text1 = "'GOD' is an acronym which stands for 'GOD Over Djinn'."
    print(repeated_words(text1))

Expected output:

    ['god']

Example usage 2:

    text2 = """There was nothing so very remarkable in that; nor did Alice think it
    so very much out of the way to hear the Rabbit say to itself, 'Oh dear! Oh dear!
    I shall be late!'"""
    print(repeated_words(text2))

Expected output:

    ['so', 'very', 'the', 'to', 'oh', 'dear']

### 2. Sentiment

Write a Python function called `sentiment_of_text(text, sentiment_of_word)` that takes a text string and a dictionary of word sentiments as input and returns the overall sentiment score of the text. The sentiment score is calculated as the sum of sentiment scores for individual words in the text using the provided `sentiment_of_word` dictionary. You may assume that words that cannot be found in the dictionary have a sentiment score of 0. You can use the `tokenize()` function of the previous assignment.

This is the `sentiment_of_word` dictionary:

    sentiment_of_word = {
        "abysmal": -5, "agonizing": -4, "dreadful": -5, "grim": -3, "horrible": -5,
        "miserable": -4, "terrible": -5, "upset": -3, "unpleasant": -2, "woeful": -4,
        "horrific": -5, "disastrous": -5, "appalling": -5, "repulsive": -4, "noxious": -3,
        "atrocious": -5, "vile": -4, "wretched": -3, "deplorable": -5, "abominable": -5,

        "amazing": 5, "fantastic": 4, "joyful": 4, "excellent": 5, "delightful": 4,
        "wonderful": 5, "terrific": 4, "great": 3, "awesome": 5, "superb": 4,
        "fabulous": 4, "incredible": 5, "marvelous": 4, "phenomenal": 5, "outstanding": 4,
        "brilliant": 5, "spectacular": 4, "splendid": 3, "glorious": 4, "fantabulous": 5
    }

As you can see, negative words have negative scores and positive words have positive scores.


Example usage:

    text1 = "Wow, what an amazing day it has been! The weather is fantastic!"
    text2 = "Today has been abysmal. The weather is dreadful, and I feel miserably upset."

    print(sentiment_of_text(text1, sentiment_of_word))
    print(sentiment_of_text(text2, sentiment_of_word))

Expected output:

    9
    -13

### 3. Spotify

For this assignment you're going to use the datafile [spotify.csv](spotify.csv). This file contains information about the popularity of songs on Spotify. It contains these columns:

| Column Name           | Description                                      |
|-----------------------|--------------------------------------------------|
| track_name            | The name of the music track.                     |
| artist(s)_name        | The name(s) of the artist(s) who performed the track. If there are multiple artists, they are separated by commas. |
| released_date (yyyy-mm) | The release date (month) of the track in the "yyyy-mm" format. |
| streams               | The number of streams for the track.            |

The is a small sample of the contents of the file:

| track_name                  | artist(s)_name                  | released_date (yyyy-mm) | streams   |
|-----------------------------|---------------------------------|-------------------------|-----------|
| Seven (feat. Latto) (Explicit Ver.) | "Latto, Jung Kook" | 2023-7                  | 141,381,703 |
| LALA                        | Myke Towers                     | 2023-3                  | 133,716,286 |
| vampire                     | Olivia Rodrigo                   | 2023-6                  | 140,003,974 |
| Cruel Summer                 | Taylor Swift                     | 2019-8                  | 800,840,817 |
| WHERE SHE GOES              | Bad Bunny                        | 2023-5                  | 303,236,322 |
| ...                    |...             | ...                  | ... |

So for instance, the song "Cruel Summer" was written by "Taylor Swift", was released in August 2019 (2019-8) and was streamed on Spotify a total of 800,840,817 times.

Write the following two Python functions:

The first function, `find_artist_of_most_popular_song_based_on_number_of_streams(filename)`, reads the data from the CSV file and returns the artist(s) of the most popular song based on the total number of streams.

The second function, `find_most_popular_release_month_based_on_number_of_songs(filename)`, is designed to find the release month with the most songs.

Example usage:

    song = find_artist_of_most_popular_song_based_on_number_of_streams('spotify.csv')
    print(song)
    date = find_most_popular_release_month_based_on_number_of_songs('spotify.csv')
    print(date)

Expected output:

    The Weeknd
    2022-5
