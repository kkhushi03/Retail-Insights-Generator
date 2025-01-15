# AtliQ Tees: Talk to a Database  

This is an end-to-end LLM project based on Google Palm and Langchain. It is a system that can talk to the MySQL database. 
The user asks questions in a natural language and the system generates answers by converting those questions to an SQL query and
then executing that query on MySQL database. 
AtliQ Tees is a T-shirt store where they maintain their inventory, sales and discounts data in MySQL database. A store manager 
will ask questions such as,
- How many white colour Adidas t-shirts do we have left in stock?
- How much sales our store will generate if we can sell all extra-small size t-shirts after applying discounts?
The system is intelligent enough to generate accurate queries for given questions and execute them on the MySQL database
- Natural Language to SQL: Translates user queries in plain language into SQL commands using Hugging Face models and Google PaLM 2 to fetch insights from retail data.
- Actionable Insights: Processes data to deliver insights on sales trends, inventory, and customer behaviour, presented through intuitive visualizations.
- Enhanced Decision-Making: Empowers non-technical users to explore complex data effortlessly, improving strategy and operational efficiency.

- AtliQ Tees is a t-shirt store that sells Adidas, Nike, Van Heusen and Levi's t-shirts 
- Their inventory, sales and discounts data is stored in a MySQL database
- The code is an LLM-based question-and-answer system that will use the following,
  - Google Palm LLM
  - Hugging face embeddings
  - Streamlit for UI
  - Langchain framework
  - Chromadb as a vector store
  - Few shot learning
- In the UI, the store manager will ask questions in a natural language and it will produce the answers
