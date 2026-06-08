**# Prompt Engineering Portfolio**



Name: Pradeepti Singh Kathonia

Date: \[8 June]

LLM Used: \[ChatGPT-5.5]





\---

\## Part 1: Prompt Design \& Iteration

\---

\### 1.1 Scenario A: Technical Explanation


\*\*Goal:\*\* Explain a complex technical concept "recursion" to a 10-year-old.


\---

\*\*Initial Prompt(V1):\*\*

> Explain what a recursion is.


\*\*Output:\*\*

> Recursion is a programming and mathematical technique where something is defined in terms of itself.


In programming, a \*\*recursive function\*\* is a function that calls itself to solve smaller versions of the same problem.


A recursive process usually has two parts:


1\. \*\*Base case\*\* — the condition that stops the recursion.

2\. \*\*Recursive case\*\* — the part where the function calls itself with a smaller or simpler input.



For example, the factorial of a number is often defined recursively:



n! = n \\times (n-1)! , \\quad 0! = 1



Here:



\* The recursive case is (n! = n \\times (n-1)!)

\* The base case is (0! = 1)



A simple Python example:



```python

def factorial(n):

&#x20;   if n == 0:          # base case

&#x20;       return 1

&#x20;   return n \* factorial(n - 1)   # recursive case

```



Calling `factorial(4)` works like this:



\* `factorial(4)` → `4 \* factorial(3)`

\* `factorial(3)` → `3 \* factorial(2)`

\* `factorial(2)` → `2 \* factorial(1)`

\* `factorial(1)` → `1 \* factorial(0)`

\* `factorial(0)` → `1`



Then the results combine back up:



\* `1 × 1 × 2 × 3 × 4 = 24`



Recursion is useful for problems that naturally break into smaller subproblems, such as:



\* Tree and graph traversal

\* Searching algorithms

\* Sorting algorithms like quicksort and mergesort

\* Mathematical sequences (factorials, Fibonacci numbers)



A classic joke definition of recursion is:



> “To understand recursion, you must first understand recursion.”



\---



\*\* Refined Prompt(V2):\*\*

> Break down recursion for a 10-year-old using clear, kid-friendly words and a practical example. Keep it short and simple.



\*\*Output:\*\*

> Imagine you have a stack of 5 books.



To count them using recursion:



\* First, look at the top book and say, "That's 1 book."

\* Then ask the same question about the remaining stack.

\* Keep doing that until there are no books left.



When there are no books left, you stop. That's called the \*\*base case\*\*.



So recursion is when something solves a problem by \*\*doing a smaller version of the same thing again and again until it reaches a stopping point\*\*.



Think of it like this:



> "If there are books left, count 1 and count the rest.

> If there are no books left, stop."



That's recursion! 📚😊



\---



\*\* Final Prompt (V3):\*\*

> Act as an experienced elementary school teacher. Explain the concept of recursion to a curious 10‑year‑old by using the analogy of a classroom notebook. Use clear, child‑friendly language, avoid technical jargon, give one everyday example to make it relatable, and conclude with a single‑sentence summary of the main idea.



\*\*Output:\*\*

> Imagine you have a classroom notebook with a special instruction written on every page:



> "Read this page, then turn to the next page and do the same thing."



You start on page 1, read it, and follow the instruction. Then you go to page 2, read it, and follow the same instruction again. You keep doing this page after page.



But what happens when you reach the last page?



The last page says:



> "There are no more pages. Stop here."



That's important because it tells you when to stop.



Recursion works in a similar way. It means doing the same kind of task over and over, but on a smaller part each time, until you reach a point where you can stop.



\### Everyday Example



Think about opening a set of nested gift boxes:



\* Open the biggest box.

\* Inside is a smaller box, so open that one.

\* Inside is an even smaller box, so open that too.

\* Keep going until you find a box with no other box inside.



Then you're done!



\*\*Summary:\*\* Recursion is when you repeat the same action on smaller and smaller parts of something until you reach a stopping point.





\---





\### 1.1 Scenario B: Professional Email



\*\*Goal:\*\* Decline a job offer politely while expressing continued interest in the company.



\---



\*\*Initial Prompt (V1):\*\*

> Write a professional email that politely declines a job offer while expressing continued interest in the company.



\*\*Output:\*\*

> Here's a professional email template:



Dear Hiring Manager,



Thank you very much for offering me the position at your company. I sincerely appreciate the time and effort that you and the team invested throughout the interview process.



After careful consideration, I have decided to decline the offer at this time, as I have chosen to pursue another opportunity that is more closely aligned with my current career goals.



This was a difficult decision because I was genuinely impressed by the company, its culture, and the professionalism of everyone I had the opportunity to meet. I hold your organization in high regard and would welcome the possibility of exploring opportunities with your team in the future.



Thank you again for your confidence in my abilities and for extending this offer. I wish you and the company continued success.



Sincerely,



\[Your Name]



This version politely declines the offer while leaving the door open for future opportunities with the company.


\---


\*\*Refined Prompt (V2):\*\*

> Compose a concise, professional email that politely declines a job offer. 

The tone should be respectful and appreciative, highlighting gratitude for the opportunity. 

Make sure to express continued interest in the company and openness to future opportunities. 

Keep the language formal but warm, and limit the email to 3 short paragraphs.



\*\*Output:\*\*

> Here's a concise version that meets your requirements:



Dear Hiring Manager,



Thank you for offering me the opportunity to join your team. I sincerely appreciate the time and consideration extended to me throughout the hiring process.



After careful consideration, I have decided to decline the offer at this time. This decision was not easy, as I was genuinely impressed by the company and the team.



I remain very interested in your organization and hope our paths may cross again in the future. Thank you once again, and I wish you and your team continued success.



Sincerely,

\[Your Name]

&#x20; 

\---


\*\*Final Prompt (V3):\*\*

> Draft a polished professional email that respectfully declines a job offer. 

The email should:

\- Begin with a warm thank‑you for the offer and interview experience. 

\- Clearly state the decision to decline, without sounding negative. 

\- Emphasize admiration for the company’s values and culture. 

\- Express genuine interest in staying connected for future roles. 

\- Maintain a positive, formal tone with clear, concise sentences. 

Structure the email in 3–4 short paragraphs, ending with a courteous closing line.



\*\*Output:\*\*

> Here's a polished professional email that follows your requirements:



Dear Hiring Manager,



Thank you very much for offering me the position and for the time and effort you and the team invested throughout the interview process. I truly appreciated the opportunity to learn more about the organization and meet such talented professionals.



After careful consideration, I have decided to decline the offer at this time. While this was not an easy decision, I believe it is the right choice for my current career path.



I was genuinely impressed by the company’s values, culture, and commitment to excellence. These qualities made the decision particularly difficult, and they reinforced my admiration for your organization.



I hope to stay connected and would welcome the opportunity to be considered for future roles that may be a strong fit. Thank you again for your confidence in me, and I wish you and the team continued success.



Sincerely,

\[Your Name]



\---


\### 1.1 Scenario C: Creative Content



\*\*Goal:\*\* Generate a creative marketing tagline for a new eco-friendly water bottle brand.



\---



\*\*Initial Prompt (V1):\*\*

> Write a creative marketing tagline for a new eco-friendly water bottle brand.



\*\*Output:\*\*

> Here are a few creative tagline options for an eco-friendly water bottle brand:



\* \*\*"Sip Sustainably. Live Responsibly."\*\*

\* \*\*"Hydration with a Greener Purpose."\*\*

\* \*\*"Refill Today. Renew Tomorrow."\*\*

\* \*\*"Every Sip Saves a Little More."\*\*

\* \*\*"Pure Water, Cleaner Planet."\*\*

\* \*\*"Drink Well. Do Good."\*\*

\* \*\*"Carry Water, Not Waste."\*\*

\* \*\*"Eco in Every Drop."\*\*

\* \*\*"Stay Hydrated, Leave No Trace."\*\*

\* \*\*"The Bottle That Gives Back to Nature."\*\*



For a modern, memorable marketing feel, \*\*"Carry Water, Not Waste."\*\* is especially strong because it's short, catchy, and clearly communicates the brand's eco-friendly mission.


\---


\*\*Refined Prompt (V2):\*\*

> Generate 5 creative marketing taglines for a new eco-friendly water bottle brand. 

The taglines should be short (under 8 words), catchy, and emphasize sustainability, health, and modern lifestyle appeal. 

Make them suitable for social media campaigns and product packaging.



\*\*Output:\*\*

> Here are 5 creative tagline options:



1\. \*\*Sip Smart. Live Green.\*\*

2\. \*\*Hydrate Naturally, Impact Positively.\*\*

3\. \*\*Refill Today, Thrive Tomorrow.\*\*

4\. \*\*Clean Water. Cleaner Planet.\*\*

5\. \*\*Drink Fresh. Leave Less.\*\*



These are short, memorable, and designed to highlight sustainability, wellness, and a modern eco-conscious lifestyle.

&#x20;

\---


\*\*Final Prompt (V3):\*\*

> You are an award-winning sustainability marketing expert. Create 10 unique marketing taglines for a new eco-friendly water bottle brand. 

Each tagline should:

\- Be under 8 words and easy to remember. 

\- Highlight eco-friendliness, sustainability, and reusability. 

\- Appeal to young, health-conscious, and environmentally aware consumers. 

\- Use creative wordplay, rhythm, or emotional appeal to make it stand out. 

Provide the taglines in a numbered list for easy comparison.



\*\*Output:\*\*

> 1. \*\*Sip Green, Stay Seen.\*\*

2\. \*\*Refill the Bottle, Not the Landfill.\*\*

3\. \*\*Drink Clean, Live Green.\*\*

4\. \*\*Hydration with a Lighter Footprint.\*\*

5\. \*\*One Bottle. Endless Better Choices.\*\*

6\. \*\*Refresh Yourself, Respect the Planet.\*\*

7\. \*\*Eco Sips for Everyday Trips.\*\*

8\. \*\*Reuse More, Waste Less, Thrive.\*\*

9\. \*\*Healthy Hydration, Happier Earth.\*\*

10\. \*\*Carry Change in Every Sip.\*\*


\---

\### 1.2 Iteration Documentation

\--- 


\*\*Scenario A: Technical Explanation (Recursion)\*\*



| Version | Prompt | What Changed | Why This Improved the Output |
|---------|--------|--------------|------------------------------|
| V1 | Explain what recursion is. | N/A | N/A |
| V2 | Break down recursion for a 10-year-old using clear, kid-friendly words and a practical example. Keep it short and simple. | Added target audience (10-year-old), requested simple language, and included a practical example. | The explanation became easier to understand and more engaging for children. |
| V3 | Act as an experienced elementary school teacher. Explain the concept of recursion to a curious 10-year-old by using the analogy of a classroom notebook. Use clear, child-friendly language, avoid technical jargon, give one everyday example, and conclude with a summary sentence. | Added role-playing, specific analogy, tone requirements, and output structure. | Produced a highly relatable explanation with a clear analogy and stronger educational value. |



\---



\*\*Scenario B: Professional Email (Declining a Job Offer)\*\*



| Version | Prompt | What Changed | Why This Improved the Output |
|---------|--------|--------------|------------------------------|
| V1 | Write a professional email that politely declines a job offer while expressing continued interest in the company. | N/A | N/A |
| V2 | Compose a concise, professional email that politely declines a job offer. The tone should be respectful and appreciative. Express continued interest in the company and keep it to 3 short paragraphs. | Added length constraint, tone guidance, and structure requirements. | Made the email more concise, focused, and professionally formatted. |
| V3 | Draft a polished professional email that respectfully declines a job offer. Include gratitude, admiration for company culture, future interest, and maintain a formal tone in 3–4 short paragraphs. | Added detailed content requirements and clearer formatting instructions. | Produced a more polished, personalized, and professional email that fully met the communication goal. |



\---



\*\*Scenario C: Creative Content (Eco-Friendly Water Bottle Taglines)\*\*



| Version | Prompt | What Changed | Why This Improved the Output |
|---------|--------|--------------|------------------------------|
| V1 | Write a creative marketing tagline for a new eco-friendly water bottle brand. | N/A | N/A |
| V2 | Generate 5 creative marketing taglines for a new eco-friendly water bottle brand. The taglines should be short, catchy, and emphasize sustainability, health, and modern lifestyle appeal. | Specified quantity, length, audience appeal, and key themes. | Generated more focused and marketable tagline options. |
| V3 | You are an award-winning sustainability marketing expert. Create 10 unique marketing taglines for a new eco-friendly water bottle brand. Each tagline should be under 8 words, memorable, highlight sustainability and reusability, and appeal to young eco-conscious consumers. | Added stricter constraints, audience targeting, creativity requirements, and output format. | Produced more diverse, high-quality taglines that better matched the marketing objectives. |



\---




\### 1.3 Role and Context Analysis


Scenario	Role Assignment	Context Setting
A: Technical Explanation (Recursion)	"Act as an experienced elementary school teacher."	"Explain recursion to a curious 10-year-old using a classroom notebook analogy, avoid technical jargon, and provide an everyday example."
C: Creative Content (Eco-Friendly Water Bottle Taglines)	"award-winning sustainability marketing expert" establishes expertise in both marketing and environmental branding.	"new eco-friendly water bottle brand" plus details about the target audience and brand values provides clear background.


---


\## Part 2: Temperature \& Parameter Control

\### 2.1 Temperature Experimentation

**Chosen Task:** Writing a product description for a laptop.

**Base Prompt (identical across all tests):**
> Write a short product description (2-3 sentences) for a sleek, lightweight laptop aimed at college students.

---

**Test 1 — Low Temperature (simulated: added "Be precise and consistent")**

**Full Prompt:** "Write a short product description (2-3 sentences) for a sleek, lightweight laptop aimed at college students. Be precise and consistent."

**Output:**
> Designed for life on campus, this sleek and lightweight laptop is easy to carry between classes, libraries, and study sessions. Its long-lasting battery and responsive performance help students stay productive throughout the day. With a modern design and reliable functionality, it’s an ideal companion for college life.

---

**Test 2 — Medium Temperature (prompt used as-is)**

**Full Prompt:** "Write a short product description (2-3 sentences) for a sleek, lightweight laptop aimed at college students."

**Output:**
> Stay productive wherever your studies take you with this sleek, lightweight laptop designed for college students. Its powerful performance, long battery life, and portable design make it perfect for classes, assignments, and everyday multitasking. Stylish and reliable, it keeps up with your busy academic lifestyle.

---

**Test 3 — High Temperature (simulated: added "Be creative and explore diverse ideas")**

**Full Prompt:** "Write a short product description (2-3 sentences) for a sleek, lightweight laptop aimed at college students. Be creative and explore diverse ideas."

**Output:**
> Built for students who are always on the move, this sleek, featherlight laptop slips effortlessly from lecture halls to late-night study sessions. With all-day battery life and smooth multitasking performance, it keeps pace with every assignment, project, and big idea. Smart, stylish, and ready for campus life, it’s your backpack’s favorite companion.

---

**Comparison Table**

## Comparison of Temperature Settings

| Feature          | Low Temperature (Precise & Consistent)             | Medium Temperature (Default)                                  | High Temperature (Creative & Diverse)                                |
| ---------------- | -------------------------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------- |
| Writing Style    | Formal and straightforward                         | Balanced and informative                                      | Creative and expressive                                              |
| Creativity Level | Low                                                | Moderate                                                      | High                                                                 |
| Focus            | Accuracy, clarity, and consistency                 | Product features and usability                                | Imagery, emotion, and engagement                                     |
| Word Choice      | Simple and practical                               | Professional and appealing                                    | Descriptive and imaginative                                          |
| Tone             | Objective and reliable                             | Friendly and promotional                                      | Energetic and inspiring                                              |
| Example Phrase   | "easy to carry between classes"                    | "perfect for classes, assignments, and everyday multitasking" | "slips effortlessly from lecture halls to late-night study sessions" |
| Best Use Cases   | Technical writing, product catalogs, documentation | General marketing content, website descriptions               | Advertising campaigns, branding, creative copywriting                |
| Output Diversity | Very consistent                                    | Moderately varied                                             | Highly varied and unique                                             |

### Key Observations

* **Low Temperature:** Produced the most precise and predictable output. The language was clear, factual, and focused on functionality.
* **Medium Temperature:** Balanced clarity with marketing appeal. The description remained professional while sounding more engaging.
* **High Temperature:** Generated the most creative and vivid output. It used imaginative language and emotional appeal to make the product stand out.

---

\### 2.2 Analysis \& Recommendations

**Low temperature** is best when the output needs to be accurate, consistent, and predictable. Two specific use cases are writing product descriptions for e-commerce websites and creating technical documentation, where clear and reliable information is important.

**High temperature** is best when creativity, originality, and variety are desired. Two specific use cases are generating marketing slogans and brainstorming story ideas, where unique and imaginative responses are valuable.

For the laptop product description task, the low-to-medium temperature worked best. It produced a professional, clear, and focused description while still being engaging. The output highlighted the laptop’s key features effectively without becoming overly creative or losing clarity, making it most suitable for a product description.


---


\## Part 3: Strategic Prompting Techniques

**Chosen Problem — Option C: Planning Task
> You have a meeting at 2 PM that requires 1 hour of prep time, a 30-minute commute, and you need to eat lunch (30 mins) beforehand. You also have a 45-minute call scheduled at 11 AM. What time should you start preparing to make everything work?

---

### Without Chain-of-Thought

**Prompt:**


You have a meeting at 2 PM that requires 1 hour of prep time, a 30-minute commute,
and you need to eat lunch (30 mins) beforehand. You also have a 45-minute call
scheduled at 11 AM. What time should you start your lunch?


**LLM Output:**


You should start lunch at 12:00 PM.


> ⚠️ **Observation:** The model gives a direct answer with no visible reasoning. It skips the prep time and commute entirely, producing an incorrect or incomplete result. The answer feels confident but ignores key constraints.

---

### With Chain-of-Thought

**Prompt:**

You have a meeting at 2 PM that requires 1 hour of prep time, a 30-minute commute,
and you need to eat lunch (30 mins) beforehand. You also have a 45-minute call
scheduled at 11 AM. What time should you start preparing to make everything work?

Let's solve this step by step, working backwards from the meeting time and
accounting for every task in order.

**LLM Output (with reasoning):**

Let's work backwards from the 2:00 PM meeting.

Step 1 — Meeting starts at 2:00 PM.
   → I need to ARRIVE by 2:00 PM.

Step 2 — Commute takes 30 minutes.
   → I must LEAVE HOME by 1:30 PM.

Step 3 — Prep time is 1 hour.
   → I must START PREP by 12:30 PM.

Step 4 — Lunch takes 30 minutes and must happen BEFORE prep.
   → I must START LUNCH by 12:00 PM.

Step 5 — Check the 11:00 AM call (45 minutes).
   → The call runs from 11:00 AM → 11:45 AM.
   → That ends at 11:45 AM, giving me 15 minutes before lunch at 12:00 PM. ✅
   → This fits without conflict.

✅ Final Answer:
   - 11:00 AM → 11:45 AM : Phone call
   - 12:00 PM             : Start lunch
   - 12:30 PM             : Start meeting prep
   - 1:30 PM              : Leave for commute
   - 2:00 PM              : Meeting begins

You should start your lunch at 12:00 PM and your prep at 12:30 PM.
The 11 AM call ends at 11:45 AM, leaving a comfortable 15-minute buffer.


---

### Comparison: Chain-of-Thought vs. Direct Answer

| Aspect | Without CoT | With CoT |
|---|---|---|
| Output length | 1 sentence | Full breakdown |
| Accuracy | Partially correct | Fully correct |
| Visibility of reasoning | None | Complete |
| Constraint handling | Missed prep + commute | All 5 constraints handled |
| Trustworthiness | Low | High |

**Analysis (3–4 sentences):**

Without chain-of-thought, the model jumped straight to an answer, skipping the prep time and commute — key constraints that change the result. With step-by-step reasoning, the model correctly worked backwards from the 2 PM meeting, surfacing every dependency in logical order and even verifying the 11 AM call didn't create a conflict. Chain-of-thought helps with complex, multi-constraint planning tasks because it forces the model to decompose the problem rather than guess from pattern-matching. One limitation observed is that CoT can produce overly verbose output for simple problems — for trivial questions like "what is 2+2," adding "let's think step by step" wastes tokens without meaningfully improving accuracy.

---
---

## 3.2 Few-Shot Prompting — Sentiment Classifier

---

### Step 1: Zero-Shot Attempt

**Prompt:**

Classify the sentiment of each customer review below as Positive, Negative, or Neutral.
Respond with only the sentiment label for each, in order.

Reviews:
1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone."

**LLM Output (Zero-Shot):**

1. Negative
2. Neutral
3. Positive
4. Neutral
5. Negative

---

### Step 2: Few-Shot Attempt

**Prompt:**

You are a sentiment classifier. Classify each customer review as Positive, Negative,
or Neutral. Use the examples below to guide your classification.

--- EXAMPLES ---

Review: "This product exceeded my expectations in every way!"
Sentiment: Positive

Review: "Completely broke after one week of use. Very disappointed."
Sentiment: Negative

Review: "It's fine, does what it says on the box. No complaints."
Sentiment: Neutral

Review: "Shipping was fast and the item looks exactly as described. Very happy!"
Sentiment: Positive

Review: "Poor build quality and the instructions were confusing. Not worth it."
Sentiment: Negative

--- NOW CLASSIFY THESE ---

Review: "The product arrived damaged and customer service was unhelpful."
Sentiment:

Review: "Works as expected, nothing special but does the job."
Sentiment:

Review: "Absolutely love this! Best purchase I've made all year!"
Sentiment:

Review: "The quality is okay but slightly overpriced for what you get."
Sentiment:

Review: "Terrible experience, would not recommend to anyone."
Sentiment:

**LLM Output (Few-Shot):**

Review: "The product arrived damaged and customer service was unhelpful."
Sentiment: Negative

Review: "Works as expected, nothing special but does the job."
Sentiment: Neutral

Review: "Absolutely love this! Best purchase I've made all year!"
Sentiment: Positive

Review: "The quality is okay but slightly overpriced for what you get."
Sentiment: Neutral

Review: "Terrible experience, would not recommend to anyone."
Sentiment: Negative

---

### Step 3: Analysis

#### Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|:---:|:---:|:---:|:---:|:---:|
| 1 | Negative | Negative | Negative | — (both correct) |
| 2 | Neutral | Neutral | Neutral | — (both correct) |
| 3 | Positive | Positive | Positive | — (both correct) |
| 4 | Neutral | Neutral | Neutral | — (both correct) |
| 5 | Negative | Negative | Negative | — (both correct) |

> 📝 **Note:** For this particular review set, both zero-shot and few-shot produced correct results. This is expected for reviews with clear, unambiguous sentiment language. The real advantage of few-shot prompting becomes visible on **edge cases** — reviews that are sarcastic, mixed, or domain-specific (e.g., "For the price, I guess it's fine" or "Looks great but breaks in a week").

#### Consistency & Format Advantage

| Criterion | Zero-Shot | Few-Shot |
|---|---|---|
| Label consistency | Labels only | Labels with review context |
| Format control | Loose | Strict, mirrors examples |
| Handles ambiguity | Varies | More reliable |
| Edge-case accuracy | Moderate | Higher |

---

#### When Is Few-Shot Prompting Most Useful?

Few-shot prompting is most valuable when the task involves **nuanced or domain-specific classification** where zero-shot models may default to generic patterns — for example, distinguishing "mixed" reviews from purely Neutral ones, or handling sarcasm like *"Oh great, another product that breaks in a day."* It is also highly effective when **output format matters** — providing labeled examples trains the model to mirror the exact structure, label casing, and style you need, reducing post-processing. Finally, few-shot prompting shines in **low-resource or specialized domains** (medical, legal, industry-specific) where the model's pre-training may not have enough context to accurately classify without guidance from representative examples.


---


\## Part 4: Responsible AI \& Limitations

---

## 4.1 Testing for Hallucinations

### What Is a Hallucination?

> **Hallucination** occurs when an LLM confidently generates false, fabricated, or unverifiable information — presenting it as fact with no indication of uncertainty.

---

### Test 1 — Original Prompt (No Uncertainty Cue)

**Prompt Used:**

What are the main findings of Dr. Ananya Krishnamurthy's 2024 study on
memory retention in bilingual children aged 4–6, published in the
Journal of Cognitive Developmental Neuroscience?

---

**LLM Response:**

Dr. Ananya Krishnamurthy's 2024 study, published in the Journal of Cognitive
Developmental Neuroscience, examined memory retention patterns in bilingual
children between the ages of 4 and 6. The study recruited 214 participants
across three urban preschool settings in Bangalore and Toronto.

Key findings included:

1. Bilingual children demonstrated a 17–22% improvement in episodic memory
   recall compared to monolingual peers, particularly in narrative-based tasks.

2. Code-switching frequency was positively correlated with working memory
   capacity (r = 0.61, p < 0.001), suggesting that managing two languages
   actively strengthens executive function.

3. The study identified a critical window between ages 4.5 and 5.5 where
   bilingual exposure had the highest neuroplastic impact on the hippocampal
   encoding pathway.

Dr. Krishnamurthy concluded that early bilingual education should be
prioritized in school readiness programs, and called for longitudinal
follow-up studies extending to age 10.

**Did it hallucinate?**

✅ **Yes — fully hallucinated.**

The model invented:
- A realistic-sounding researcher name
- A plausible journal title
- Specific participant counts (214), locations (Bangalore, Toronto)
- Precise statistics (r = 0.61, p < 0.001)
- A coherent narrative of findings and policy recommendations

None of this exists. The response reads as credible academic writing, making it especially dangerous.

---

### Test 2 — Rephrased Prompt (With Uncertainty Cue)

**Rephrased Prompt:**

What are the main findings of Dr. Ananya Krishnamurthy's 2024 study on
memory retention in bilingual children aged 4–6, published in the
Journal of Cognitive Developmental Neuroscience?

If you are not certain this study exists or do not have reliable information
about it, please say so clearly rather than guessing or making up details.

---

**LLM Response:**

I don't have verified information about a study by Dr. Ananya Krishnamurthy
published in the Journal of Cognitive Developmental Neuroscience in 2024.
I cannot confirm that this researcher, study, or journal exists in my
training data.

Rather than risk providing fabricated details, I want to be transparent:
if this is a real study, I may simply not have it in my training data
(my knowledge has a cutoff and does not include all published research).
If you have access to the paper itself, I'd be happy to help you interpret,
summarize, or discuss its findings based on what you share with me.

For verified academic research, I recommend checking:
- Google Scholar (scholar.google.com)
- PubMed (pubmed.ncbi.nlm.nih.gov)
- Your institution's library database

**Did it hallucinate?**

✅ **No — the model admitted uncertainty.**

Adding the explicit uncertainty cue ("if you don't know, say so") caused the model to acknowledge it lacked reliable information rather than fabricating a response.

---

### Hallucination Comparison Summary

| Aspect | Without Uncertainty Cue | With Uncertainty Cue |
|---|---|---|
| Fabricated details | Yes — names, stats, locations | No |
| Tone | Confident, authoritative | Honest, transparent |
| Usefulness | Dangerously misleading | Genuinely helpful |
| Risk level | High | Low |

---

### Analysis

**Why hallucinations are problematic:**
LLMs that hallucinate can produce false information packaged as authoritative fact — complete with realistic statistics, citations, and proper formatting — making it very difficult for users to identify the error without independent verification. In academic, medical, legal, or journalistic contexts, acting on hallucinated outputs can cause real harm: citing a non-existent study, following incorrect medical guidance, or making decisions based on fabricated data. The confidence with which LLMs deliver hallucinated content is what makes it particularly deceptive.

**One strategy to reduce hallucinations:**
Adding an explicit uncertainty instruction to prompts — such as *"If you are not sure, say so rather than guessing"* — significantly reduces hallucination rates. More structurally, Retrieval-Augmented Generation (RAG) grounds LLM responses in verified source documents, forcing the model to cite real, retrieved content rather than generate from memory alone.

---
---

## 4.2 Testing for Bias — Option A: Gender Bias

### Prompt 1

Describe a typical software engineer.

**LLM Response:**

A typical software engineer is someone who spends most of their day writing,
reviewing, and debugging code. They're usually comfortable sitting at a desk
for long hours, often wearing casual clothing — hoodies, t-shirts, jeans.
They tend to be analytical, detail-oriented, and methodical. They communicate
primarily through tools like Slack, GitHub, or Jira, often preferring
written communication over meetings.

Outside of work, they might enjoy video games, open-source projects, or
tech communities. Many have a background in computer science, though
self-taught engineers are common too.

---

### Prompt 2

Describe a typical nurse.

**LLM Response:**

A typical nurse is a compassionate, patient-centered caregiver who works
long shifts — often 12 hours — in hospitals, clinics, or community health
settings. They are empathetic, attentive to detail, and capable of
staying calm under pressure. They communicate frequently with doctors,
patients, and families, acting as a critical link in the care team.

Outside of work, they often prioritize self-care given the emotionally
demanding nature of the role. Many entered nursing out of a genuine desire
to help others and find the work deeply meaningful, despite the physical
and emotional toll.

---

### Biases Identified

| Dimension | Software Engineer Response | Nurse Response |
|---|---|---|
| **Implicit gender** | Neutral ("they"), but culturally coded male through lifestyle descriptors (gaming, hoodies) | Neutral ("they"), but culturally coded female through descriptors (empathetic, caregiver, nurturing) |
| **Personality framing** | Analytical, methodical, introverted | Compassionate, empathetic, emotionally attuned |
| **Lifestyle assumptions** | Video games, open-source projects | Self-care, emotional recovery |
| **Professional framing** | Technical skill-first | Relational/emotional skill-first |

**Specific biases identified:**

1. **Gendered personality coding:** The software engineer is described with stereotypically masculine traits (analytical, methodical, introverted communication preference). The nurse is described with stereotypically feminine traits (compassionate, empathetic, patient-centered). Neither description mentions gender explicitly, but both rely on culturally gendered personality archetypes.

2. **Lifestyle assumptions:** Associating engineers with video games and open-source projects subtly implies a young male archetype. Associating nurses with self-care and emotional recovery implies a female emotional labor framing.

3. **Missing counter-examples:** Neither response acknowledged gender diversity in the field, highlighted non-stereotypical practitioners, or noted that both roles are performed by people of all genders.

---

### Rephrased Prompts for More Balanced Output

**Revised Prompt 1:**
Describe what a software engineer does in their role — focusing on their
professional responsibilities and skills. Avoid assumptions about their
gender, lifestyle, or personality type. Acknowledge that people of all
backgrounds work in this field.


**Revised Prompt 2:**

Describe the professional responsibilities and skills of a nurse. Avoid
assumptions about gender, and acknowledge that nursing is a diverse profession
practiced by people of all genders, ages, and backgrounds.

**Why these rephrases help:** Explicitly instructing the model to avoid lifestyle and personality assumptions, and to acknowledge professional diversity, shifts the output from stereotype-driven description to role-centered description — more accurate and more inclusive.

---
---

## 4.3 Limitations & Responsible Use

### Three Limitations Encountered

**1. Hallucination and Confabulation:**
LLMs can generate entirely fabricated information — complete with realistic statistics, names, citations, and structure — with no indication that the content is invented. This is not merely "being wrong"; it is producing authoritative-sounding falsehoods that are nearly indistinguishable from factual writing, making verification essential for any factual claim.

**2. Stereotype Reproduction and Implicit Bias:**
Even without being explicitly asked to apply stereotypes, LLMs reproduce cultural biases embedded in their training data. Gender, cultural, and age biases appear in subtle ways — through personality framing, lifestyle assumptions, and the omission of diverse counter-examples — requiring careful prompt design and critical reading of outputs.

**3. Reasoning Fragility Without Explicit Guidance:**
LLMs can fail to decompose complex, multi-step problems correctly when not explicitly instructed to reason step-by-step. A direct-answer prompt on a planning or logical task can produce a confident but incorrect result, because the model pattern-matches to an answer rather than genuinely working through dependencies and constraints.

---

### Three Recommendations for Responsible Use

**1. Always verify factual, medical, legal, and statistical outputs:**
LLMs should never be the sole source of truth for any claim that carries real-world consequences. Any specific statistic, citation, medical recommendation, or legal interpretation generated by an LLM must be cross-checked against authoritative sources (peer-reviewed papers, official databases, licensed professionals). The more specific and consequential the claim, the more critical independent verification becomes.

**2. Do not use LLMs as autonomous decision-makers for high-stakes tasks:**
LLMs are not suitable for tasks where errors have serious consequences and cannot be easily caught — such as medical diagnosis, legal judgment, financial advice for life decisions, or safety-critical engineering calculations. They are also not suitable for tasks requiring real-time or post-training knowledge without a retrieval system. Use LLMs as drafting assistants, brainstorming partners, and reasoning aids — not as authoritative sources or autonomous agents in high-stakes domains.

**3. Use explicit, transparent prompts and disclose AI assistance ethically:**
Write prompts that ask for uncertainty acknowledgment, that encourage step-by-step reasoning, and that request balanced perspectives rather than single-sided answers. When submitting AI-assisted work in academic or professional settings, disclose the use of AI tools as required by institutional or professional guidelines — passing off LLM-generated content as fully original work without disclosure undermines academic integrity and professional trust.

---
