# Global Electronics Retail Analytics Platform

## Business Problem

A global electronics retailer operates across multiple countries, product categories, and store formats. The objective was to analyze sales performance, customer purchasing behavior, product profitability, and store-level efficiency to support data-driven business decisions.

## Dataset

The project combines multiple business datasets:

* Customers
* Products
* Sales Transactions
* Stores
* Exchange Rates

## Tools Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Data Cleaning
* Exploratory Data Analysis (EDA)

## Project Workflow

### Data Preparation

* Imported and validated multiple datasets
* Cleaned missing and inconsistent values
* Standardized formats and data types
* Merged datasets using common keys

### Exploratory Analysis

* Revenue trend analysis
* Product category performance
* Store performance comparison
* Customer purchasing behavior
* Revenue normalization using exchange rates

### Business KPIs

* Revenue by Category
* Revenue by Store
* Revenue per Square Meter
* Month-over-Month Growth
* Store Age Performance

## Key Insights

* Identified highest-performing product categories
* Determined top revenue-generating stores
* Evaluated store efficiency using revenue-per-area metrics
* Analyzed customer purchase patterns across regions

## Business Impact

The analysis demonstrates how retail organizations can leverage data analytics to optimize store operations, improve inventory planning, and support strategic business decisions.

# Generative AI Assisted Analytics

## Objective

As part of this project, Large Language Models (LLMs) were used to accelerate data preparation, exploratory analysis, KPI development, and business insight generation.

The objective was not to replace analytical thinking, but to evaluate how Generative AI can improve productivity during the analytics workflow while maintaining human validation of outputs.

---

## Use Case 1: Store Revenue Efficiency Analysis

### Prompt

You are a retail business analyst.

Using a dataset containing store revenue, store size, location, and product information, calculate a store efficiency metric that measures revenue generated per unit of store area.

Requirements:

* Handle missing values appropriately.
* Convert invalid data types where necessary.
* Calculate revenue per square meter.
* Rank high-performing and low-performing stores.
* Generate business recommendations.
* Provide Python Pandas code.

### LLM Output Evaluation

| Evaluation Criteria     | Assessment |
| ----------------------- | ---------- |
| Business Understanding  | High       |
| KPI Recommendation      | High       |
| Python Code Quality     | High       |
| Data Validation         | Moderate   |
| Business Interpretation | Moderate   |

### Outcome

The LLM correctly suggested Revenue per Square Meter as a suitable operational efficiency metric and generated reusable Pandas code for implementation.

Human validation was performed before finalizing recommendations.

---

## Use Case 2: Revenue Growth Analysis

### Prompt Type

Chain-of-Thought Prompting

### Prompt

Analyze monthly revenue trends and calculate Month-over-Month growth.

Provide:

* Monthly revenue calculations
* Growth percentages
* Trend interpretation
* Business recommendations

Explain each analytical step before generating the final output.

### Outcome

The LLM successfully generated:

* Monthly revenue aggregation logic
* Percentage growth calculations
* Trend explanations
* Business-focused recommendations

The step-by-step reasoning helped validate calculations and improve transparency.

---

## Generative AI Applications Used

The LLM assisted in:

* Data cleaning recommendations
* Datatype conversion
* Missing value analysis
* Feature engineering
* KPI design
* Revenue normalization
* Business insight generation
* Code debugging
* Exploratory Data Analysis (EDA)

---

## Human Validation

All generated outputs were manually reviewed and validated before implementation.

While the LLM accelerated development, business assumptions and analytical conclusions were verified using domain knowledge and data-driven validation techniques.

---

## Key Learning

This project demonstrates how Generative AI can act as an analytics copilot, significantly reducing time spent on repetitive preprocessing and debugging tasks while allowing analysts to focus on business problem solving and decision making.

