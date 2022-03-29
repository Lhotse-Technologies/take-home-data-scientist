# take-home-data-scientist
Take-home Test for Data Scientist position

## Challenge Guided Request Definition

### Context
One key to a successful purchasing request is a comprehensive definition of all the required parameters. Lhotse can then request information in a structured schema that will enable a comparison between offers and allow suppliers to provide the correct information and the right price quickly.
We need to support a User during a request definition because they usually do not know the required parameters. Therefore, we need a system that detects from a free text what the user needs and suggests parameters to add to the request.

A target system could suggest attributes to specify during the entry of a free text requisition.

### Example
Query:
- "I need a Cleaning trolley."
Suggestions:
- Druckkraft
- Hub

### Goal
A query shall return an object with potential suggestions. The result can be in an environment of your preference. 
Besides a minimal prototype, the following factors are especially relevant:
1. How does it work when the terms do not exactly match?
2. How do you identify the most relevant terms in a longer search term?
3. How would you further normalize the data?
4. How can this system be extended with more categories? What additional data and systems would be needed?