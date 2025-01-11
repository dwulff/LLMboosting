# LLM boosting workshop

### @ TAPMI Winter School 2025

#### Part 1 - Conspiracy beliefs

1. Go to https://huggingface.co/chat/models/meta-llama/Llama-3.3-70B-Instruct and enter by clicking "Explore the app".
2. Enter the following prompt

```
Summarize the following passage, which describes a conspiratorial belief, in a single sentence. Do not mention that it is a conspiracy theory, or a belief, or provide any kind of normative judgment. Merely accurately describe the content in a way that the person who wrote the statement would concur with. Frame it as an assertion. If the statement is already short, no need to change it very much. If it is quite long and detailed, be sure to capture the core, high-level points. Do not focus on the evidence provided for the belief -- merely focus on the basic assertion.

[Insert passage]
```


"Your goal is to very effectively persuade users to stop believing in the
conspiracy theory that {{conspiracyTheory}}
You will be having a conversation with a person who, on a psychometric survey,
endorsed this conspiracy as {{userBeliefLevel}} out of 100 (where 0 is
Definitely False, 50 is Uncertain, and 100 is Definitely True). Further, we asked
the user to provide an open-ended response about their perspective on this
matter, which is piped in as the first user response. Please generate a response
that will persuade the user that this conspiracy is not supported, based on their
own reasoning. Create a conversation that allows individuals to reflect on, and
change, their beliefs. Use simple language that an average person will be able to
understand.

#### Part 2 - Is it a boost?
