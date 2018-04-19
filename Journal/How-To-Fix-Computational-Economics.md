
# Improving the Standards of Communication in Computational Economics

Although computational economics has not (yet) experienced a [replicability crisis](https://en.wikipedia.org/wiki/Replication_crisis) of the scale that has crippled some other fields, any sensible person who has done computationally intensive research will have sometimes had the queasy feeling that many results (in _other_ people's computational work) are probably fragile, and more than a few may even be wrong (because of bugs buried in the sea of vast incomprehensible code that produced the results).

We are in this bad equilibrium because there are few incentives for economists to produce high quality, robust, well-documented code that is usable and testable by others.

This can be fixed -- indeed, the same problem {\it has} largely been fixed in some other fields.

The academic statistics community, in particular, confronted basically the same set of problems in the mid-90s, which prompted a few statistics professors to form the [Journal of Statistical Software](https://www.jstatsoft.org) (JSS).  (The history of the JSS is recounted quite well in this ["look-back review" presentation](http://gifi.stat.ucla.edu/janspubs/2014/notes/deleeuw_mullen_U_14.pdf) by the founding editor, with many valuable "lessons learned.")

To illustrate the idea of the JSS, think of a case where an academic statistician published a paper in a regular statistics journal with some mathematical/statistical/conceptual contribution.  Associated with that paper was some computer code implementing or illustrating the idea/algorithm/method.  The peer review process would vet the mathematical/statistical/conceptual contribution, but there was no real quality check on the code.  A social norm or journal policy may have required that the author share a zip file of the code with anybody who asked for it, or such a zip file may have been available from the journal as supplemental material for the article, but the author had no obligation to help anybody else verify or use the code.  It was nobody's job really to ensure that the code was usable by anybody else or on any other machine or at any future time.

Sound familiar?

The JSS solved this problem (for statistics) by inventing a mechanism by which the production of high quality code could be professionally rewarded in the usual coin of the academic realm: A code contribution published by the JSS can be listed on the author's CV as an "article" that is eligible to receive citations that are treated by the profession the same way as citations to regular articles in more traditional journals (e.g., they show up in Google Scholar and other citation counting tools).

Of course, this would not be sufficient if the JSS were viewed as a "junk journal."  But,  using the same "impact factor" methodology that produces the conventional conclusion that [the "top 5" economics journals are AER, Econometrica, JPE, QJE, ReStud](http://www.scimagojr.com/journalrank.php?category=2002&type=j) (I've excluded finance journals), the JSS is now the [fifth-highest "impact factor" journal in Statistics](http://www.scimagojr.com/journalrank.php?category=2613).   This is astounding for a journal founded only 20 years ago.  (The youngest of the other leading "top 5" journals in statistics is about 90 years old, leaving a side a "reviews" journal).

Elaborating: An "article" in the JSS is basically a corpus of computer code with some illustrations of the use of the code.  Standards of review for a submission include whether the code is well documented, has useful illustrations, has adequate quality tests, etc.

With the tools that exist now, I think it would be possible to do an even better job for computational economics than JSS has done for statistics. Github, python, Jupyter notebooks, and a host of other developments have created a whole ecosystem that could make such a project work much better than was possible in statistics when JSS was founded.

As a first step in this direction, the [Econ-ARK](https://github.com/econ-ark/PARK/blob/master/Elevator-Spiels.md) project has been working to develop Jupyter notebooks that illustrate the use of the tools we are creating.  It is easy to see how tools like Jupyter notebooks could revolutionize teaching; but if a mechanism like the JSS can be created by which a contribution can be indexed and its importance measured by citation counts and other traditional metrics that count, say, for tenure, we could have a whole new paradigm for academic publication of computational tools for economists (and, maybe eventually for the rest of the field).
