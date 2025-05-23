# Invoice Analyzer

A FlowiseAI invoice analyzer workflow that processes invoice PDFs and returns a structured output containing all the relevant information found inside the invoice.

## Workflow

Below is the visual representation of the Invoice Analyzer workflow:

![Workflow of the Invoice Analyzer](WorkFlow%20of%20the%20Agent.png)

## Examples

### When No Invoice is Provided

The system returns "None" for all fields when no invoice content is available:

![No Invoice Provided](All%20None.png)

### Invoice Information Before Parsing

Raw JSON data extracted from the invoice:

![Invoice Information Raw](Invoice%20information.png)

### Invoice Information After Parsing

Structured and formatted information from the invoice:

![Invoice Information After Parsing](Invoice%20information%20after%20parser.png)

## How it Works

The workflow uses a combination of ChatDeepseek LLM, a Prompt Template, an LLM Chain, and a Structured Output Parser to:

1. Accept PDF invoice inputs
2. Extract relevant information from the invoice content
3. Parse the data into a structured format with specific fields
4. Return a clean, organized view of the invoice data

This agent handles various invoice formats and provides a consistent output structure regardless of the input invoice layout.
