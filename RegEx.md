# Regular Expressions

|     Type     |                                                              |
| :----------: | :----------------------------------------------------------- |
|    **^**     | Beginning of line                                            |
|    **$**     | End of line                                                  |
|    **.**     | Any character                                                |
|    **\***    | repeats char 0 or more times                                 |
|    ***?**    | Non-greedy version of **\***                                 |
|    **+**     | Repeats a character one or more times                        |
|    **+?**    | Non-greedy version of **+**                                  |
| **[aeiou]**  | Matches a single character in the listed set                 |
|  **[^XYZ]**  | Matches a single character not in the listed set             |
| **[a-z0-9]** | The set of characters can include a range                    |
|    **()**    | used to group sub-patterns                                   |
|  **{n, m}**  | at least n, and at most m repetitions of the pattern to the left to it |
|    **\|**    | or                                                           |
|    **\A**    | Matches if the specified characters are at the start of a string |
|    **\b**    | Matches if the specified characters are at the beginning or end of a word. |
|    **\B**    | Matches if the specified characters are **not** at the beginning or end of a word |
|    **\d**    | Decimal Digit                                                |
|    **\D**    | non decimal digit                                            |
|    **\s**    | whitespace                                                   |
|    **\S**    | non-whitespace                                               |
|    **\w**    | alphanumeric character [a-zA-Z0-9_]                          |
|    **\W**    | non-alphanumeric character                                   |
|    **\Z**    | Matches if the specified characters are at the end of a string |



#### Python  

```python
import re

re.findall(regex_pattern, string)		# returns a list of strings containing all matches
re.split(regex_pattern, string) 		# splits the string where there is a match
re.sub(regex_pattern, replace, string)		# matched occurrences are replaced with replace variable value
re.subn(regex_pattern, replace, string)		# returns a tuple of 2 items: (new string, no.of substitutions made)
re.search(regex_pattern, string)		# returns the first location where the pattern matches

# Match object

match.group(index) 			# returns the matched part of the string if no index is specified
match.start()				# returns index of the starting char of the matched substring
match.end()				  	# returns the end index of the matched substring
match.span()				# returns a 2 item tuple: (match.start(), match.end())
match.re					# returns regex pattern
match.string				# returns original string
```

Source: [py4e](https://py4e.com), [programiz](https://www.programiz.com/python-programming/regex) , [python3 docs](https://docs.python.org/3/library/re.html)