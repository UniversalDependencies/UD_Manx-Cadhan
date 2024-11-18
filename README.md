
# Summary

This is the Cadhan Aonair UD treebank for Manx Gaelic,
created by Kevin Scannell.

# Introduction

The sentences in the original treebank (UD v2.7) came from a large web-crawled
corpus of Manx consisting of more than 8M words of text.
This corpus was segmented by sentences, shuffled, and then
300 random sentences were chosen to be tagged.
I believe that the web corpus is nearly comprehensive, which is to say
it contains virtually all non-trivial Manx language texts on the open web.
Therefore, the initial release of the UD corpus was as close as possible
to a “random sample” of Manx on the web. As such,
[the Bible](http://bible.learnmanx.com/) is heavily represented,
but there are also quite a few sentences from modern sources such as the
[Manx Wikipedia](https://gv.wikipedia.org/),
news stories from
[Manx Radio](https://www.manxradio.com/),
blog posts,
translations of literature, etc.

All POS tags and dependency annotations in the initial release
were added manually. The upstream source code and datasets supporting
the treebank can be found [here](https://github.com/kscanne/gaelg).

The treebank was expanded greatly for UD v2.8, released in May 2021.
Most of the new sentences in this release came from Phil Kelly's Manx
"usage file", taken from example sentences in various Manx-English
dictionaries. Full morphological features were added to this release as
well.

Only a test file was provided for releases 2.7 through 2.10.
With v2.11 (November 2022), we randomly resplit the corpus into
test and train files with about 10k tokens each,
following
[the recommendation](https://universaldependencies.org/release_checklist.html#data-split) of the UD maintainers.  This means that any experiments
run on earlier versions of the treebank would need to be rerun
with the new split.

# Acknowledgments

I created the treebank while visiting Acadamh na hOllscolaíochta Gaeilge
in Carna, Co. na Gaillimhe as a Fulbright Scholar. All of the work was
done during the COVID-19 lockdown in Ireland.

I am grateful to the staff at the Acadamh in Carna for their hospitality
during my visit, to the Fulbright Program for the financial support
which made it possible, and to Saint Louis University for a
much-needed sabbatical leave.

Thanks also to Teresa Lynn and Colin Batchelor for their work on the 
Irish and Scottish Gaelic treebanks, respectively. Since all three
Goidelic languages are grammatically very similar, I was able to
consult their work when deciding how to resolve tricky annotation problems.

## References

* Scannell, Kevin P., [_Universal Dependencies for Manx Gaelic_](https://cs.slu.edu/~scannell/pub/ud-final.pdf), Proceedings of the Universal Dependencies Workshop at COLING 2020, 13 December 2020, pp. 152–157.

# Changelog

* 2020-11-15 v2.7
  * Initial release in Universal Dependencies.

* 2021-05-15 v2.8
  * Expanded to over 20k tokens
  * Full morphological features added

* 2021-11-15 v2.9

* 2022-05-15 v2.10

* 2022-11-15 v2.11
  * Resplit data into train and test (~10k tokens each)


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.7
License: CC BY-SA 4.0
Includes text: yes
Genre: news fiction nonfiction blog social wiki web bible
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: Scannell, Kevin
Contributing: elsewhere
Contact: kscanne@gmail.com
===============================================================================
</pre>
