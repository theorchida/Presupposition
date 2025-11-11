# Presupposition Recognition in Chat-Optimized Language Models

## Abstract

Despite the impressive human-like conversational abilities of recent language models, a lot of research has pointed out issues in their linguistic comprehension and reasoning capabilities. Understanding natural language encompasses both the semantic meaning of the discourse, as well as the assumptions made during communication. Presuppositions are an integral part of this process. We evaluate the ability of ChatGPT and Llama 2 70B Chat models in predicting entailment status across 10 types of presupposition triggers. We find that these models are poor at recognising presuppositions with softer triggers, and that in general, they tend to predict entailment labels more frequently than the correct label. Some of their achievement can be attributed to flawed heuristics like lexical overlap, but it is difficult to be completely sure since we cannot isolate the effects of few-shot examples and prompting.

## Conclusion

We find that the models predict entailment "E" much more often, even when that is not the gold label. This is in line with the findings of Basmov et al. (2023). Furthermore, we also find that the higher accuracy of most presupposition triggers is, to some extent, a result of error-prone heuristic like lexical overlap. We conclude that even though recent LLMs are far from achieving an “understanding” of natural language presupposition tasks, we cannot definitively say that the models only use fallible heuristics to accomplish the given NLI task. It is possible that the models are bad at inferring what the task is from the instructions and in-context learning examples. It could also be that many of the in-context learning examples can be solved through a lexical overlap heuristic, and therefore, the models apply the same heuristic for the NOPE test data. In a more naturalistic conversation, on the other hand, it may be that the model is able to draw the right inferences.


If you would like to use the results in the project, please cite the GitHub :)
