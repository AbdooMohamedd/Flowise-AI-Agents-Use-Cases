# Customer Support Agent

A FlowiseAI customer support agent workflow that answers questions about a business by retrieving information from a knowledge base of documents. This agent provides accurate customer service responses based on company documentation.

## Workflow

Below is the visual representation of the Customer Support Agent workflow:

![Workflow of the Customer Support Agent](1-%20Workflow%20of%20the%20Agent.png)

## Components

The Customer Support Agent utilizes several key components:

1. **Document Store Configuration**: Setting up the vector database with company information.

   ![Document Store Configuration](3-%20document%20store%20configration.png)

2. **Document Data**: Loading documents into the vector store for retrieval.

   ![Document Store Added Data](2-%20document%20store%20added%20data.png)

3. **Retrieval Process**: The agent retrieving relevant content from the knowledge base.

   ![Retrieved Content from Database](5-%20Retrevied%20content%20from%20the%20database.png)

4. **Customer Interaction**: The agent answering customer questions with retrieved information.

   ![Retrieved Answer](4-%20Retrevied%20answer.png)

## How it Works

The Customer Support Agent combines several technologies to provide accurate customer service:

1. **ChatDeepseek LLM**: Powers the conversational capabilities of the agent

2. **Buffer Window Memory**: Maintains conversation context for coherent responses

3. **Tool Agent (AgentExecutor)**: Coordinates the use of retrieval tools

4. **Retriever Tool**: Fetches relevant information from the document store

5. **Document Store (Vector Database)**: Stores and indexes company documentation for efficient retrieval

When a customer asks a question, the agent:

1. Analyzes the query
2. Retrieves relevant information from the document store
3. Formulates a helpful response based on the retrieved information
4. Maintains conversation context for follow-up questions

## Use Cases

- Answering FAQ questions about products or services
- Providing information about business policies
- Assisting with menu items and specials (for restaurant businesses)
- Handling reservation inquiries and information requests
- Responding to questions about business hours, location, and accessibility
