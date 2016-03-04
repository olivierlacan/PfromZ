# PfromZ
Find P values from Z scores.

Use PfromZ here: http://olivierlacan.com/PfromZ/

## Purpose
This little tool will give you [P values](https://en.wikipedia.org/wiki/P-value) from
any positive or negative [Z score](https://en.wikipedia.org/wiki/Standard_score) you enter.

It will only give you the result for a [one-tailed hypothesis](https://en.wikipedia.org/wiki/One-_and_two-tailed_tests).

Just multiply the result by 2 if you need two-tail.

## Why?

My fiancée was working on analyzing her research statistically and she had to use some awful
unmaintained ASP website with a completely opaque server-side equation to calculate P values.

After finding a way to create [an Excel function](https://gist.github.com/olivierlacan/5e73ca5a6d315a3aa26e)
to help her get through her research faster I thought I could probably find a way to create a fully
client-side P value from Z score calculator. And thanks to [jStat](https://github.com/jstat/jstat) I did.

## License

This project is [MIT licensed](LICENSE).
