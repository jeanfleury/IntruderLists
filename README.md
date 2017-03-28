# Burp Suite Payload Lists

A repository for Burp Suite Intruder payload lists.  Lists are updated periodically.  Any suggestions, additions, or recommendations are welcome.

## Available Files

#### 1. XSS.txt
A compiled list of XSS payloads from multiple sources and researchers (RSnake, JHaddix, etc). List has been checked for duplicate files and removed all lines that contained comments.  Payloads have been reduced to include only the necessary special characters.

#### 2. URL Redirect.txt
An initial list of payloads to test for unvalidated URL redirects.  The list includes different versions of payloads.  For example, a payload will be prefaced with `http`, then repeated using 'https' and in some cases `ftp`.

#### 3. Unicode Chars 00-ff.txt
This list has all UTF-8 characters URL encoded from `%00` to `%ff`. This is an abbreviated version of the following list.

#### 4. All UTF-8 Unicode 00-cfbf.txt
This is a full list of all possible UTF-8 characters, beginning at `%00` and ending with `%cf%bf`. Checkout [this site](http://www.fileformat.info/info/charset/UTF-8/list.htm) for a full reference list and description of each character.
