# Solving Bongard Problems with a Visual Language and Pragmatic Reasoning

### Summary

A bayesian program learning approach to bongard problems. Lacks some theory, but demonstrates application well enough for this to require further consideration. See discussion.

### Hypotheses

BPL works for bongard problems.

### Methods 

### Results

35/39 Problems in subset solved... others not attempted. No human comparison

### Discussion

Pros:

    In contrast to the RF4 paper, I believe this system works directly on images, which is clearly essential (4).
    I always love a good put-down of "Deep learning" (1,2).
    Approaching BPs as "concept communication problems" is pretty insightful (6, 14). I find it interesting that they didn't define a hierarchical model here (for learning abstractions and modeling set of BPs as a whole) -- this is one of the main strengths of this approach (~Analogous to the LTM in the Phaeaco system).

Cons:

    I don't believe the phrase "cognitive plausibility" appears in the paper.. but the concept is used implicitly:
    Exclusion criteria (page 15), are rather subjective. I agree most with the first, but they should've mentioned cognitive plausibility (Bayesian program learning has a few agreements with certain psychology experiments, but disagreements with others). The third criterion is easily changed, because of how easy it is to add new primitives.. I'm surprised that a few iterations of improvement weren't done here. There's some discussion in the Phaeaco dissertation of a fair way to improve the system without introducing ad-hoc solutions.
    More on the above: Isn't restricting the valid space of problems only to the problems the system can solve ad-hoc itself?
    It would be relatively easy to make answers be in ~natural language (BPL has a primary use in language models!) (17)
    Page 18: Hint of a "visual turing test," -- this would be extremely interesting. Even comparison to the human data from the Phaeaco dissertation would've enriched this paper a lot.
    The performance metric (As Alex noted) is the number of problems solved in the artificial subset.  Other metrics should've been discussed. However, just because I disagree with this metric doesn't mean I think that this program couldn't be compared to Phaeaco some other way.
    Speaking of performance metrics, the data in the appendix is interesting: The burn-in rate and number of samples are ludicrous -- I don't know off of the top of my head, but I don't think these compare favourably to the MIT results on similar tasks. (My current BPL model of seqsee needs  (for very sharp results) 1000 samples with a burn of 100, but this paper uses numbers 10x that)
    Some style issues, like the ridiculously long introduction and over-detail in some places and lack of detail in others
    No code provided, relatively sparse data

But here are my thoughts on bayesian program learning in general:

Despite that long list of cons, I think that his technique could be tested and -- after some improvement -- compared to Phaeaco.
Right now, I'm working on similar statistical models that solve the Seqsee task (or maybe numerical bongard). I want to learn more about this approach, in particular about the relation between their sampling method (Metropolis Hastings) and the parallel terraced scan. I have a hunch that these two algorithms are similar in the abstract... but the amount of math used in the MH probabalistic algorithm raises interesting questions about cognitive plausibility. I want to get some clarification on this.
If desired, I'll share more about the seqsee model, once it's finished.

### Takeaways:

BPL could be applicable to future FARG-problems, but I'm not certain that this group approached it as well as they could have. The main concern I have is the lack of psychologically-grounded theory, even though the sources they draw from are rich in it.

### Citation:

```
@article{bongard-visual-language,
    author  = "Stefan Depeweg, Constantin A. Rothkopf Frank Jakel",
    title   = "Solving Bongard Problems with a Visual Language and Pragmatic Reasoning",
    journal = "arxiv",
    volume  = "",
    number  = "",
    pages   = "",
    year    = "2018",
    DOI     = "1804.04452"
}
```
