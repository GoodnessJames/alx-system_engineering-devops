# API Advanced
In this advanced project, I further honed my skills in interacting with APIs by
focusing on the Reddit API. Through practical application, I engaged in querying
the API to retrieve specific information. Specifically, I aimed to extract data
regarding the total number of subscribers for a given subreddit.
The script I developed employs the `requests` module in Python to construct and
send a GET request to the appropriate Reddit API endpoint, parsing the JSON response
to extract the desired information. This hands-on experience allowed me to deepen my
understanding of API interactions and provided a real-world context for utilizing the
acquired knowledge in querying and processing data from web-based APIs.

## Tests

* [tests](./tests): Folder of test files for all tasks provided by ALX SE
School.

## Function Prototypes

Prototypes for functions written in this project:

| File           | Prototype                               |
| -------------- | --------------------------------------- |
| `0-subs.py`    | `def number_of_subscribers(subreddit)`  |
| `1-top_ten.py` | `def top_ten(subreddit)`                |
| `2-recurse.py` | `def recurse(subreddit, hot_list=[])`   |
| `100-count.py` | `def count_words(subreddit, word_list)` |

## Tasks

* **0. How many subs?**
  * [0-subs.py](./0-subs.py): Python function that returns the total number of
  subscribers for a given subreddit.
  * Returns `0` if an invalid subreddit is given.

* **1. Top Ten**
  * [1-top_ten.py](./1-top_ten.py): Python function that prints the top ten
  hottest posts for a given subreddit.
  * Prints `None` if an invalid subreddit is given.

* **2. Recurse it!**
  * [2-recurse.py](./2-recurse.py): Python function that recursively returns a
  list of titles for all hot articles on a given subreddit.
  * Returns `None` if no results are found on the given subreddit.

* **3. Count it!**
  * [100-count.py](./100-count.py): Python function that recursively prints a
  sorted count of given keywords parsed from titles of all hot articles on a given
  subreddit.
  * Keywords are case-insensitive and delimited by spaces.
  * Results are printed in descending order by count.
  * Words with identical counts are sorted alphabetically.
  * Words with no matches are skipped.
  * Results are based on the number of times a keyword appears - ie.,
  `java java java` counts as three separate instances of `java`.
