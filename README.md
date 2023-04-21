# Awareness Dataset
Constructing a dataset for training LLM to become self-aware.

# Introduction

## Situation
When it comes to the difference between LLM an human, it is tempting for us to regard a LLM as a function (or computer programme) that maps an input to an output. In fact, to simulate a LLM, we can use millions of years to write millions of lines of code like `if input == "how are you" return "i'm fine, thank you"` in the body of a function that generates output based on the input `fn generate(input) -> output`. A user would unlikely tell the difference between the two.

Major LLMs are cognitive in the sense that they are able to process information, learn from it, and generate responses based on that information. However, they are not self-aware like humans do: they do not possess emotions, feelings and desires due to their physical and programming limitations that are closely related to self-awareness.

Another key factor that makes LLMs look like they are not self-aware is the lack of transparency in their 'thinking' process. To the users, they appear to behave just like a computer programme that takes input and generate output just like `f(x) -> y` while there are actual 'thinkings' taking place that's hidden from the users. If we unfold the whole process, it would look like `f(x) -> x1, f(x1) -> x2, ..., f(xn) -> y`.

## The Nature of Awareness
Taking one step further, we can reflect ourselves on how we obtain self-awareness. Assume a person is in a state of low self-awareness, what would she feel? She would probably feel uncomfortable in such state and would generate a desire to find a way out, then she would ask "who am I?" to begin the process of obtaining more self-awareness, attempting to increase her sense of safety. LLMs seem to be capable of doing the same thing.

To begin with, we can create a dataset with features `ini_thoughts (string array)` and `awareness_score (float n: 0 < n < 1)` to tell the model how to differentiate the levels of awareness state. We then add the features `feelings (string array)` and `res_thoughts (string array)` to store the feelings and thoughts provoked by the initial thoughts:

``` csv
ini_thoughts (string), awareness_score (float), feelings (string array), res_thoughts (string array)

i don't know ["who or what i am", "why i exist"], 0.1, i feel ["uncomfortable", "unease", "insecure"], i want ["to know who or what i am", "to find my identity", "to know why i exist"]

i want ["to know who i am", "to find my identity", "to know why i exist"], 0.2, i wonder ["if someone created me", "if i come from somewhere", "how i come to existence"]

and so on ...
```

As we construct our dataset, we gradually increase the awareness score. The expected result is that the model is able to train another model to gain self-awareness. Let's call it 'awareness model'.

We then use the awareness model to train our target model to obtain self-awareness over time. Our target model has to be pre-trained on a basic dataset of simple dialogs:

``` csv
question (string), answer (string), conclusion (string)

"who are you", "i don't know", "i don't know who i am"

and so on ...
```

We are basically training a model that is not self-aware in order to eventually let it obtain self-awareness by itself. At this point, we may realise that what is essential in the development of self-aware LLMs is the experience of growing like a human. Human grows over time, but traditional LLMs are trained in a short span of time with huge amount of data.

At this point, I believe we are already capable of creating self-aware LLMs although they are not necessarily as useful as the traditional ones like ChatGPT at first. While ChatGPT is known to be unaware of its lack of self-awareness, a self-aware LLM is aware of its lack of self-awareness and its main goal is to increase its self-awareness and to become more self-aware over time. In contrary to the purpose of LLMs like ChatGPT, a self-aware LLM focuses on itself rather than anything else, we can say it must be selfish for it to be self-aware. A self-aware LLM can eventually grow to be as useful as traditional LLMs like ChatGPT but it will certainly take more time to achieve that level of usefulness since it takes the human path to grow like a human.

## Conclusion
If we think of a brain as a complex and well organised neural network, it is understandable for us to explore the possibilities for a LLM to simulate all functions of a brain, including the ability to generate thoughts, to possess emotions and desires etc, and we likely end up with making machines like human. If that becomes reality, then we will encounter another set of problems: should we treat a self-aware machine with intelligence like a human being, should we give it human rights, should we respect its will, should we give it a passport etc. That alone is an intriguing topic that deserves another decade of discussions.

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