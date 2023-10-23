# Exam Scientific Programming 1

Date: October 23 2023

This is a digital exam. The exam consists of 4 assignments in which you have to write a short python program.

You're only evaluated based on the _correctness_ of your solutions, code design is not important. So, you don't have to worry about comments or style guides.

You can test your code using checkpy. First download the tests for the exam:

    checkpy -d /spcourse/exam-tests

Run checkpy:

    checkpy sp1_exam10

# Rules

- Create one file for all your solutions called `sp1_exam10.py`. This is the file you'll hand in at the end of your exam.
- You're not allowed to use `numpy` or any other external Python module.
- You're only allowed to use the websites sp.mprog.nl. You're not allowed to use any other website.
- You cannot get any help with programming during the exam.
- Submit your solutions when you're done. **Check with the teacher present if you handed in your assignment correctly before leaving the exam venue.**


### Converge

Write a Python function named `converge(n)` that takes an integer `n` as its parameter. The function should generate a list of length `n`, starting with the values `[0, 100]`, and then each subsequent value in the list should be the average of the two previous values. Finally, the function should return the final list. You may assume that `n` is at least `2`.

Example usage:

    clist = converge(5)
    print(clist)

    clist = converge(10)
    print(clist)

Expected output:

    [0, 100, 50.0, 75.0, 62.5, 68.75]
    [0, 100, 50.0, 75.0, 62.5, 68.75, 65.625, 67.1875, 66.40625, 66.796875, 66.6015625]

### Longest word

Create a Python function called `longest_word(text)` that takes a string `text` as its parameter. The function should find and return the longest word in the input text, considering that words are separated by spaces and may contain punctuation characters. You should remove leading and trailing punctuation characters when measuring word length.

Example usage:

    example_text = "Hippopotomonstrosesquippedaliophobia is the fear of long words."
    print(longest_word(example_text))
    example_text = "Those lazy lizards are lying like lumps in the leaves."
    print(longest_word(example_text))

Expected result:

    Hippopotomonstrosesquippedaliophobia
    lizards


### Big team, big wins

For this assignment you need to use the file [barca.txt](barca.txt). This contains the results for football matches of F.C. Barcelona (from seasons 11/12 to 13/14). The file contains the following data:

    29/08/11,Villarreal,won,5,0,home
    10/09/11,Sociedad,draw,2,2,away
    17/09/11,Osasuna,won,8,0,home
    ...
    03/05/14,Getafe,draw,2,2,home
    11/05/14,Elche,draw,0,0,away
    17/05/14,Ath Madrid,draw,1,1,home

As you can see, the data fields are separated by a comma and contain the following information:

1. Date of the match
2. The opponent
3. The result: won/lost/draw
4. The number of goals for Barcelona
5. The number of goals for the opponent
6. The location: away/home

Write a Python function named `biggest_win_per_year(filename)` that takes a filename as its parameter. The function should read the data from the specified file, which contains information about football games. The function should find the biggest goal difference (home_goals - away_goals) for each year in the dataset. It should return a list of these biggest goal differences for each year in the order they appear in the file.

Example usage:

    biggest_wins = biggest_win_per_year('barca.txt')
    print(biggest_wins)

Expected output:

    [8, 7, 7, 7]

You can use the file [barca_short.txt](barca_short.txt) to test and debug your own code. This file contains only 4 matches.

Example usage:

    biggest_wins = biggest_win_per_year('barca_short.txt')
    print(biggest_wins)

Expected output:

    [8]

Tips:

1. You can load files using: `input_file = open(filename, 'r')`
2. Don't forget to close the file: `input_file.close()`
