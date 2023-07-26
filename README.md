# RegEx URL Matching Tutorial

Regular Expressions (RegEx) are powerful patterns used to match and manipulate text. Regex uses a sequence of characters to define a specific search pattern. In this tutorial, we will explore how to create a simple RegEx pattern for matching URLs.

# Understanding URLs

 A URL (Uniform Resource Locator) is a reference to a web resource on the internet. It typically consists of several components:


- scheme: The protocol or scheme used to access the resource (e.g., "http", "https", "ftp").
- host: The domain or IP address of the server hosting the resource.
- port (optional): The port number on which the server is listening (e.g., 80 for HTTP, 443 for HTTPS).
- path: The specific path on the server that represents the resource.
- query (optional): Parameters passed to the server in the form of key-value pairs (e.g., "?name=John&age=30").
- fragment (optional): A specific section of the resource to display or link to
 
 # Creating a Regex Pattern for Matching URLs
 
  Keep in mind that URL validation can be complex due to the various possible components and formatting. Let's create a simple RegEx pattern to match URLs! For this tutorial, we'll create a basic pattern that works for most common URLs.

/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
While this expression may seem a bit unorthodox upon initial inspection, let's break it down into individual elements in order to understand how the sequence functions.

### Anchors
The two principal anchors in this regex expression are the ^ at the beginning and the $ at the end which constitute an string match with the components within the two anchors. When used alone, the ^ anchor matches a string that begins with the characters that follow the anchor. The $ matches a string that ends with the characters that precede it. 

### Quantifiers
Define how many times a character or group of characters can occur. 

### OR Operator
The main OR operator is the [] expression, that will match for any characters or character classes included in the brackets. 

### Character Classes
Represented by square brackets [ ], character classes match any single character within the brackets. 

### Flags
Flags are special identifiers that can be added to regex to give it a special functionality. 

### Grouping and Capturing
Captured groups can specify what characters can be used between specific anchors such as parenthesis (). 


## Author

This regex tutorial was created by Valerie Elizabeth Guerra, a fellow software engineer and coder. Hope you enjoyed! 
Github: Valliebby (https://github.com/Valliebb)
