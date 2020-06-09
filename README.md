> Forked from https://github.com/sjwhitworth/proposal-template
> - For the most part I am going to leave his template intact, as in, not editing the questions of the template too much. I will...
>    - Add sections I deem relevant
>    - Remove sections I deem irrelevant

# Engineering Proposal Template
The intention for this template is an attempt to formalize thought and approach to a given problem. Each section should encourage thought and questioning behind motives for approaches - with focus on encouraging diversity of thought.  

---

### What problem are you trying to solve?
* _Introduce the problem statement here. This might be well-defined ('we need to tweak the parameter of a rule from X to Y to help reduce a certain type of abuse'), or more fuzzy ('we need to invest more in paying back technical debt')._
* _Focus on the underlying problem that needs to be solved, as opposed to jumping to how you will solve it._
* _I like to use the thought patterns brought about by [Rubber Duck Debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging) here - explain the problem as if you're doing so to an inanimate object - therefore having no underlying understanding to rely upon. This should encourage you to think about the problem on a wider scale, hopefully avoiding the pitfalls of opting for a 'quick fix'_

### Why should we solve it?
* _Why is this an important problem for us to solve?_  
* _Is it a big enough problem to solve?_
* _Should we solve it now, or later?_
* _Provide specific data (quantitative or qualitative) wherever possible._

### What is the current behaviour?
* _If the proposal is for an entirely new solution, feel free to delete this section_
* _I ask this for two reasons:_ 
    1. _It elicits whether or not you understand the current behaviour_
    2. _Understanding the current behaviour should dictate the **proposed solution**_
* _Ideally this section will elicit a high and low level description_
    >"If you can't explain something simply, you simply don't understand it yourself"
    * _Using this rationale, explain the current behaviour as simply as you deem necessary. This could be pseudocode, a simple box->box diagram, whatever it takes to elicit the current behaviour in a simple manner._
    * _Likewise, documenting the low level behaviour should aid in considering multiple approaches. See the section on [What other approaches did you consider?] on why that's important._

### How do you propose to solve it?
* _Add details of your proposed change. This can be high-level as pseudocode and sketches of the architecture, or as low-level as Protocol Buffer and interface definitions. Decide what the context of the proposal is, and write appropriately._
* _Be explicit about what you are optimising for in this proposed solution — for example, 'we need to hit this deadline, so we'll accept the tech debt this entails'._

### What other approaches did you consider?
* _In general, it's a red-flag if you haven't thought of a couple of different ways that you could approach the problem._
* _What does your proposed solution give you that these approaches don't?_
* _What are they optimising for that isn't appropriate in this case?_

### What could go wrong?
* _What risks does your proposed change entail?_
* _How will you mitigate them?_
* _How could this system fail, and what would be the impact if it did?_

---

## Jira-Friendly Version:
What problem are you trying to solve?
- Introduce the problem statement here. This might be well-defined ('we need to tweak the parameter of a rule from X to Y to help reduce a certain type of abuse'), or more fuzzy ('we need to invest more in paying back technical debt').
- Focus on the underlying problem that needs to be solved, as opposed to jumping to how you will solve it.
- I like to use the thought patterns brought about by Rubber Duck Debugging here - explain the problem as if you're doing so to an inanimate object - therefore having no underlying understanding to rely upon. This should encourage you to think about the problem on a wider scale, hopefully avoiding the pitfalls of opting for a 'quick fix'

Why should we solve it?
- Why is this an important problem for us to solve?
- Is it a big enough problem to solve?
- Should we solve it now, or later?
- Provide specific data (quantitative or qualitative) wherever possible.

What is the current behaviour?
- If the proposal is for an entirely new solution, feel free to delete this section
- I ask this for two reasons:
1. It elicits whether or not you understand the current behaviour
2. Understanding the current behaviour should dictate the proposed solution
- Ideally this section will elicit a high and low level description...
"If you can't explain something simply, you simply don't understand it yourself"
    - Using this rationale, explain the current behaviour as simply as you deem necessary. This could be pseudocode, a simple box->box diagram, whatever it takes to elicit the current behaviour in a simple manner.
    - Likewise, documenting the low level behaviour should aid in considering multiple approaches. See the section on [What other approaches did you consider?] on why that's important.

How do you propose to solve it?
- Add details of your proposed change. This can be high-level as pseudocode and sketches of the architecture, or as low-level as Protocol Buffer and interface definitions. Decide what the context of the proposal is, and write appropriately.
- Be explicit about what you are optimising for in this proposed solution — for example, 'we need to hit this deadline, so we'll accept the tech debt this entails'.

What other approaches did you consider?
- In general, it's a red-flag if you haven't thought of a couple of different ways that you could approach the problem.
- What does your proposed solution give you that these approaches don't?
- What are they optimising for that isn't appropriate in this case?

What could go wrong?
- What risks does your proposed change entail?
- How will you mitigate them?
- How could this system fail, and what would be the impact if it did?