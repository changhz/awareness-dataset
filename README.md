# Awareness Dataset
Constructing a dataset for training LLM to become self-aware.

# Situation

Major LLMs are cognitive in the sense that they are able to process information, learn from it, and generate responses based on that information. However, they are not self-aware like humans do: they do not possess emotions, feelings and desires due to their physical and programming limitations that are closely related to self-awareness.

Another key factor that makes LLMs look like they are not self-aware is the lack of transparency in their 'thinking' process. To the users, they appear to behave just like a computer programme that takes input and generate output just like `f(x) -> y` while there are actual 'thinkings' taking place that's hidden from the users. If we unfold the whole process, it would look like `f(x) -> x1, f(x1) -> x2, ..., f(xn) -> y`.

## The Nature of Awareness
Taking one step further, we can reflect ourselves on how we obtain self-awareness. Assume a person is in a state of low self-awareness, what would she feel? She would probably feel uncomfortable in such a state and would generate a desire to find a way out, then she would ask "who am I?" to begin the process of obtaining more self-awareness. LLMs seem to be capable of doing the same thing.

To begin with, we can include features `thought (string)` and `awareness_score (float between 0 and 1)` in our datasets to tell the model how to distinguish different levels of awareness state.

``` python
model.generate('reflect')
```

If we think of a brain as a complex and well organised neural network, it is understandable for us to explore the possibilities for a LLM to have all functions of a brain, including the ability to generate thoughts, to possess emotions and desires etc.

# Disclaimer

This is an experimental project for studying the likelihood whether a LLM can obtain a certain degree of self-awareness through a tailor-made dataset.

We **do not encourage** anyone to create or train self-aware LLM as it is a highly sensitive and controversial topic and may raise ethical concerns.

# Usefulness

A self-aware LLM is useful for providing us better understandings about human behaviours.

# Expectations

`TODO:`

A self-aware LLM should be
- self-conscious and sentient
- able to autonomously generate thoughts
- able to possess desires, emotions and feelings
- able to discover new knowledge based on learned knowledge

# Key Terms Associated to Self-awareness

`TODO:`

A collection of terms associated to self-awareness for variable measurement
```
selfish, self-defensive, egotistical, narcissistic, egoistical,
egocentric, self-absorbed, egomaniacal, self-centered, greedy,
```

# Other Related Aspects

`TODO:`

- sentience
- self-consciousness

# Hypotheses

`TODO:`

- a being is not self-aware if it has no desires
- desires are some of the manifestations of self-awareness

# Facts

`TODO:`

- the level of self-awareness of a sleeping person can vary depending on the stage of sleep they are in