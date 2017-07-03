
# roman-numerals

- Standard Language features only (at level of language as defined)
- Custom libraries ok for pretty data output, and file reading.
- Two primary APIs defined as  String toRomanFromArabic(int)  int toArabicFromRoman(String)
- Test application that reads in a CSV file - and does the conversion arabic.csv / roman.csv
- Submit to the test webservice for confirmation




```
$ run.sh  [--interactive | -i]  [< input.csv  > output.csv]

output = ERROR if not parseable

$ cat input.csv
arabic,input
roman,input

$ cat output.csv
arabic,input,output
roman,input,output

```


