# Human level concept learning through probabilistic program induction

### Summary

This paper describes a cognitive-inspired model of one-shot letter-concept learning.  
In the author's own words: "On a challenging one-shot classification task, the model achieves human-level performance while _outperforming recent deep learning approaches_" (Emphasis mine).

### Hypotheses

The hypothesis of this paper is that the concept of a letter can be represented by a script (generative model) that produces that letter. 
In lecture, tenenbaum refers to this hypothesis as _"baby as hacker"_ (read: "baby as coder"). This is based on the older idea of "baby as scientist". 
He refers to the script hypothesis as _"game engine in the head"_.
In a nutshell, it seems clear that we navigate and interact with our world in part by creating and improving a model of it.

### Methods 

Using modern hierarchical bayesian induction (See Tenenbaum group paper on this subject), this model learns scripts that describe letters (In paper, this is called BPL: Bayesian Program Learning). 
Importantly, this is one-shot, "real" (as Tenenbaum calls it in-lecture) learning (The implication is that "Deep Learning" isn't learning in the sense that matters to anyone actually trying to model intelligence). 

### Results

This model outperforms each compared "Deep learning" apprach (and actually has a smaller error rate than the tested human subjects).
The best "deep learning" approach achieves an 8% error rate (Hausdorf distance), while humans achieve 4.5% and the BPL model is 3.3%.
Later, the model is shown to pass visual turing tests against humans. 

The model is also able to produce novel characters, which are statistically indistinguishable from human-drawn characters.

### Discussion

The authors claim that two concepts are central to the model (If taken away, the model no longer passes the visual turing test): Compositionality and learning-to-learn (The hierarchical part of hierarchical Bayesian Learning).
"Our work suggests that the principles of compositionality, causality, and learning to learn will be critical in building machines that narrow [the gap between human and machine concept learning]".

### Takeaways:

Positively, this paper focuses on psychologically inspired and plausible architecture. Like our group, it focuses on concepts. 

From influence, this paper contains a lot of Minskian ideas.  
This has made me personally go back to many of Marvin Minsky's materials, which I will upload summaries of soon.  
I especially like that this paper was able to test Marvin's hypotheses, as at times he got lost in novelism...

Which brings me to the point that this paper is _full_ of robust statistical analyses and tests!! 
In my opinion, this is something that work in our architecture desparately needs.  
For every hypothesis, there should be a hypothesis test!  
For example, our architecture includes some human tests, but doesn't (to my knowledge) include any statistical turing tests.  
If our group used Amazon's mechanical turk (like this paper does), we could test many of our hypotheses, and improve the architecture in a systematic way.  
(Of course, I understand the value of intuition, and how most of science is intuition, but at the end of the day, results must be demonstrated!)  

Sidenote: in Fluid Concepts and Creative Analogies, Douglas Hofstadter describes how he chose not to read Newell's Unified Theories of Cognition, because it lacked any treatment of the word "Concept". This research paper is the opposite of that! 

### Citation:

```
@article{human-concept-learning,
    author =       "Lake, B. M., Salakhutdinov, R., and Tenenbaum, J. B.",
    title =        "Human-level concept learning through probabilistic program induction",
    journal =      "Science",
    volume =       "350",
    number =       "6266",
    pages =        "1332-1338",
    year =         "2015",
    DOI =          "http://science.sciencemag.org/content/350/6266/1332"
}
```
