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
|              |                                                              |



Source: [py4e](py4e.com), [programiz](https://www.programiz.com/python-programming/regex) 

