🏢 ACME Customer Support AI Agent
🤖 Powered by Google ADK + Gemini | Built for Kaggle Notebooks

This project is an AI-powered customer support agent for the fictional ACME Company, built using:

Google AI Agent Development Kit (ADK)

Gemini 1.5 Flash / Pro

In-Memory Agent Runner

Custom Tool Calling (search, product lookup, list products)

The agent provides conversational support, answers queries about ACME products, and automatically uses tools to fetch relevant product info.

🚀 Features
✔ AI-driven Customer Support

The agent communicates like a friendly human support representative.

✔ Custom Tools Integrated

The agent uses three backend tools:

search_products(query) – Searches across all ACME products

get_product_details(product_name/id) – Fetches full product details

list_all_products() – Shows complete catalog

✔ Google Gemini Model

You can choose:

gemini-1.5-flash (fast & cheap)

gemini-1.5-pro (high accuracy)

✔ Interactive Chat Loop

The notebook runs a live chat interface where the user can talk to the agent.

📦 Product Catalog

A built-in fictional ACME database with 5 products:

Product	Category	Price
1)ACME Smart Refrigerator	Kitchen	$2,499
2)AC2ME Smart LED Bulb	Smart Home	$29.99
3)ACME Professional Umbrella	Outdoor	$49.99
4)ACME Extension Ladder	Tools	$159.99
5)ACME Electric Leaf Blower	Garden	$89.99

🛠️ Tech Stack

1)Python 3
2)Google ADK
3)Google Gemini
4)InMemoryRunner
5)Pydantic
6)Kaggle Secrets API
