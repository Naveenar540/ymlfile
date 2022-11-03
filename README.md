# ymlfile
sample yml file
---  # yaml document beginning
# comment syntax

# basic syntax - key and value separated by colon and space before the value
key: value

# Scalar data types
integerValue: 1                     # integer value
floatingValue: 1                     # floating vale

stringValue: "456"                   # string with double quotes
stringValue: 'abc'                  # string with single quotes
stringValue: wer                   # string without quotes

booleanValue:true                   # boolean values - true or false


# Multiline string with literal block syntax -preserved new lines
string1: |
   Line1
   line2
   "line3"   
  line4

# Multiline strings with folded block syntax - new lines are not preserved, leading and trailing spaces are ignore
  string1: >
   Line1
   line2
   "line3"   
  line4
# Collection sequence data types
 # sequence arraylist example
 - One
 - two
 - Three

  # another way of sequence  syntax example
  [one, two , three]

### dictionary
  mysqldatabase:
    hostname: localhost
    port: 3012
    username: root
    password: root
