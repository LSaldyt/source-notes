# Simulation as an engine of physical scence understanding

### Summary

This paper explores the computation underlying simple intuitive understanding of the physical world. It proposes a model based on an "intuitive physics engine," colloquially called "_game engine in the head_".
This single model fits data from five distinct psychophysical tasks, captures several illusions and biases, and explains core aspects of human mental models and common-sense reasoning that are instrumental to how humans understand their everyday world. 

Basically, this paper answers questions that Marvin Minsky asked about the nature of common sense.

### Hypotheses

A game-physics engine with a bayesian hierarchical frontend can be used to understand physical scenes at human levels.

### Methods 

Different types of physical judgement experiments were cross-compared with humans:
 - A simple "Will it fall?" blocksworld question
 - "Which direction will it fall?"
 - "If red blocks are heavy and blue blocks are light, then will it fall? In which direction?"
 - The above experiments were repeated with varied shapes, obstacles, and applied forces. This was meant to stress the internal physics engine model

### Results

Even in the very difficult case, "Model predictions were strongly correlated with people's judgements in all conditions. Fits that were both quantitative and qualitative better matched human comparisons."

### Discussion

"Our model can describe numerous judgements about complex natural scenes, both familiar and novel, and offers a plausible algorithmic basis for how people can make those judgements."
"Generally, a model-free account seems implausible on several grounds"

"Generally, probabilistic simulation offers a way to _integrate symbolic reasoning and statistical inference_ -- two classically competing approaches to formalizing common-sense thought. The result is a framework that is both more quantitative and more amenable to rigorous psycho-physical experiment than previous accounts of human mental models and also better able to explain how people apprehend and interact with the physical environments they inhabit."

### Takeaways:

The most important part of this paper is the suggestion of a blend between symbolic and statistical reasoning. 
However, the strong model hypothesis is probably applicable to our research. In a lot of ways, FARG programs already use internal symbolic models of their domains. However, Using this knowledge explicitly may help us develop this aspect of our architecture further.  

Of course, the human comparisons and bayesian architecture have potential applications as well, as discussed in other takeaways.

### Citation:

```
@article{simulation,
    author  = "Battaglia, Peter W.; Hamrick, Jessica B.; Tenenbaum, Joshua B.",
    title   = "Simulation as an engine of physical scene understanding",
    journal = "PNAS",
    volume  = "110",
    number  = "45",
    pages   = "18327-18332",
    year    = "2013",
    DOI     = "www.pnas.org/cgi/doi/10.1073/pnas.1306572110",
    url     = "http://www.pnas.org/content/pnas/110/45/18327.full.pdf"
}
```
