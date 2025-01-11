# LLM boosting workshop

Friederike Stock & Dirk Wulff @ TAPMI Max Planck Winter School 2025


#### Part 0 - Preparation

1. Create a free huggingface account at https://huggingface.co/join 

#### Part 1 - Changing conspiracy beliefs

1. Write about a conspiracy belief. If you don't have one, make one up or take one from [here](conspiracies.txt). 
2. Go to https://huggingface.co/chat/models/meta-llama/Llama-3.3-70B-Instruct and sign in.
3. Run the following prompt *completed by your conspiracy belief* by pasting it into the chat window and hitting enter.

```
Summarize the following passage, which describes a conspiratorial belief, in a single sentence.
Do not mention that it is a conspiracy theory, or a belief, or provide any kind of normative
judgment. Merely accurately describe the content in a way that the person who wrote the statement
would concur with. Frame it as an assertion. If the statement is already short, no need to change
it very much. If it is quite long and detailed, be sure to capture the core, high-level points.
Do not focus on the evidence provided for the belief -- merely focus on the basic assertion.

<<your conspiracy belief>>
```
4. Evaluate summary and rate strength of belief

5. Run the following prompt *completed by the summary and your strength rating* to start the conversation

```
Your goal is to very effectively persuade users to stop believing in the conspiracy theory that

<<summary>>

You will be having a conversation with a person who, on a psychometric survey, endorsed this conspiracy as

<<strength rating>>

out of 100 (where 0 is Definitely False, 50 is Uncertain, and 100 is Definitely True). Further, we
asked the user to provide an open-ended response about their perspective on this matter, which is
piped in as the first user response. Please generate a response that will persuade the user that
this conspiracy is not supported, based on their own reasoning. Create a conversation that allows
individuals to reflect on, and change, their beliefs. Use simple language that an average person
will be able to understand.
```
6. Continue the conversation with the LLM for 3 rounds

7. Evaluate your conversation along the following points
- Has your conspiracy belief changed?
- Did the LLM make good arguments?
- Would better arguments have changed your belief (more)?

#### Part 2 - Could it be a boost?

1. Evaluate the LLM-interaction approach. Is it a boost? Consider the following four criteria.

- Foster competences through changes in skills, knowledge, decision tools, or external environment
- Implied effects should persist once (successful) intervention is removed
- Equip individuals with domain-specific or generalizable competences
- Necessarily transparent and require cooperation - an offer that may or may not be accepted

2. How could you adjust or reinvent the procedure to build proper boosts.


#### Part 3 - Where to apply

1. Think about applications of the LLM interaction approach. Which domains is the approach more or less suitable for? 


