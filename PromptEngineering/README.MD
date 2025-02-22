# 🚀 **Prompting Engineering Structure**

## 1️⃣ **Instructions**
A Task for the model to do.

## 2️⃣ **Context**
External information to guide the model.

## 3️⃣ **Input Data**
The input you want a response for.

## 4️⃣ **Output Indicator**
The output type or format.

---

# 🚀 **Prompting Engineering Types**

## 1️⃣ **Zero-Shot**
Zero Shot prompting describes the technique where you present a task to an LLM without giving it further examples.

**Example**:

**Human**: Add 10+10  
**Assistant**: 20

---

## 2️⃣ **Few-Shot**
Giving the model more information about the tasks at hand via examples is called Few-Shot Prompting.

**Example**:

- **Tweet**: "I hate it when my phone battery dies.”  
  **Sentiment**: Negative

- **Tweet**: "My day has been great.”  
  **Sentiment**: Positive

- **Tweet**: "This is the link to the article.”  
  **Sentiment**: Neutral

- **Tweet**: "This new music video was incredible”  
  **Sentiment**: (To be filled)

---

## 3️⃣ **Chain-of-Thought**
Chain-of-Thought (CoT) prompting breaks down complex reasoning tasks through intermediary reasoning steps. Chain-of-Thought prompts are usually very specific to a problem type.

**Example**:

On a given week, the viewers for a TV channel were:

- **Monday**: 6500 viewers
- **Tuesday**: 6400 viewers
- **Wednesday**: 6300 viewers

**Question**: How many viewers can we expect on Friday?  
**Answer**: Based on the numbers given and without any more information, there is a daily decrease of 100 viewers. If we assume this trend will continue during the following days, we can expect 6200 viewers on Thursday and therefore 6100 viewers on Friday.

**Question**: How many viewers can we expect on Saturday? *(Think Step-by-Step)*  
**Answer**: 

