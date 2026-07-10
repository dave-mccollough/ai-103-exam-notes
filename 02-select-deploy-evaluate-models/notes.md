# Select, deploy, and evaluate Microsoft Foundry models

- Model Catalog
  - Models billed directly in Azure
    - OpenAI models
    - Microsoft models
    - Etc..
  - Models from partners
    - Purchase from model provider
  - Search and filter models by
    - Curated collections
    - Model capabilities
      - Context window size
    - Model provider (Source)
    - Inference Tasks
    - Fine Tuning support
    - Industry

- Model Benchmarks
  - Quality
    - Usefulness of response coming back
      - Higher is better
  - Safety
    - Model attack success rate
      - Lower is better
  - Throughput
    - Token output per second
    - Smaller models typically respond better
      - Higher is better
  - Cost
    - USD per 1 million tokens
    - Input and output tokens
      - Lower is better

- Deploy models to endpoints

  - Global
    - Not tied to a single or specific region
    - Lots of options
    - Higher throughput
      - Global Standard
        - General workloads
        - Highest quota
      - Global Provisioned
        - Predictable high throughput
      - Global Batch
        - Large async jobs - not specifically fast
  
  
  - Data zone
    - Tied to specific countries or areas - EU/US
    - Data residency/sovereignty concerns
      - Data Zone Standard
        - EU/US data zone compliance
      - Data Zone Provisioned
        - Data zone + predictable throughput
      - Data Zone Batch
        - Data zone + large async jobs - not specifically fast

  - Regional
    - Tied to specific regions
    - East US 2
    - May see lower throughput if region is heavily used
      - Standard
        - Regional compliance
        - Low volume
      - Regional Provisioned
        - Regional compliance
        - Throughput
      - Developer 
        - Model evaluation only

- Evaluate model performance
  - Quality
    - Is the model response correct
    - Is the model response useful
  - Relevance
    - Is the response what we expected
  - Fluency
    - Is the language in a natural form
  - Grounded
    - Does it reflect the 'real world' 
      - Business data, etc
  - Manual evaluation
    - Test model responses in playground
    - Compare models side by side
  - Automated evaluation
    - Use synthetic datasets or your own data
    - Measure response based on standard metrics

- Use model leaderboard to compare models


