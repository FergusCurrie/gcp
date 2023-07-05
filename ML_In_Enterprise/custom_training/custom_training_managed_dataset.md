Setting up dataset + container

- Link Vertex AI dataset to BigQuery
  - What is structure is Vertex AI dataset? It has set goals (classifcation, regression) but can point back to storage in a different location.
- Vertex AI dataset: generate statistics, calculates summarys stats over cols
- creating python source dist aka dist package
  - folder structure:
    - package name
      - setup.py # how to build dist
      - trainer
        - **init**.py
        - task.py # entry point
- see cmd.sh for next steps

Training model:
Create training :

- training method
- model details
- training container
- hyper parameters
- compute and pricing
- prediction container
