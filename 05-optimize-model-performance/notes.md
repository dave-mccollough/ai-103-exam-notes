# Optimize generative AI model performance with MicrosoftO Foundry

- Optimize Model Performance
  - Optimize for Context
    - If the model lacks contextual knowledge, and you want to maximize response accuracy
    - Examples
      - Prompt engineering
        - Cheapest and most straightforward
        - Should be used first
      - RAG
        - Use when you need to ground in specific data
  - Optimize the model
    - When you want to improve the response style, format, or speech by maximizing the consistency of the behavior
      - Examples
        - Fine-tuning
          - Can take time
          - Expensive
          - Ongoing process
        - Combining strategies

- Prompt Engineering
  - Use detailed, explicit system prompts
  - Use prompt patterns
    - Format template pattern
      - Output format
    - Chain of thought pattern
      - Have model explain reasoning
      - Already integrated into most models
    - Few shot learning patterns

- RAG (Retrivel Augmented Generation)
  - Gathers relevant data to include with a prompt for the LLM to use for grounding context
  - RAG Pattern
    - Architectural design for RAG
    - Includes retrieved relevant data in the prompt
    - Example
      - User input
      - Retrieve grounding data based on user input
      - Augment prompt with grounding data and send to model
      - Model generates a response

- Fine tuning a model
  - Additional training for a foundation model
    - Foundation mddel + training data = fine tuned model
  - Provides the model with example prompts and responses
  - Used to maximize the consistency of the models tone and style
  - Giving the model an example of the right response
  - Model must be fine-tunable
  - Model must be in region that supports fine tuning
  