## Exercise: Data storage and management
### Introduction
Previously, you learned about planning for data storage and management. In this exercise, you’ll evaluate storage solutions for different data sources and formats using a case study about Adventure Works. You’ll also learn the differences between structured and unstructured data, as well as on-premises, cloud-based, and hybrid storage. 

### Case study
Adio, the data analyst at Adventure Works, states that the current data storage and management systems are outdated and unable to handle the increasing data volume from sources like sales, manufacturing, and social media. This affects the data analytics team’s ability to analyze and use this information to improve departmental performance. Adio asks you to review the different data sources and select appropriate storage solutions.

### Data types
Adventure Works collects and stores structured and unstructured data. Differentiating between structured and unstructured data is essential for choosing an appropriate storage solution, as some systems are more suitable for specific data types. Let’s begin by defining these terms.

Structured data: Structured data is organized in a specific format making it easily searchable and analyzable. It includes data types that can be neatly arranged in rows and columns, like numbers, dates, and text strings. Examples include sales transactions, customer information, and inventory levels.

Unstructured data: Unstructured data is not organized in a predefined format and is harder to analyze and manage. It includes data types that do not fit neatly into rows and columns, such as images, videos, and audio files. Examples of unstructured data include customer reviews, social media posts and engagements, and multimedia content.

### Storage solutions 
Now that you understand structured and unstructured data, let's explore the available storage solutions for Adventure Works and evaluate their advantages and disadvantages.

On-premises storage: On-premises storage involves storing data on physical hardware, such as storage devices, within the company's premises. It’s suitable for businesses with strict security and compliance needs, requiring full control over their data and infrastructure, or storing sensitive or core operational data. On-premises storage can be more expensive, due to the costs involved in purchasing, managing, and maintaining the hardware and software infrastructure.

Cloud-based storage: With cloud-based storage, you store data on remote servers managed by a third-party provider. It offers convenient access and management from anywhere through the Internet. Cloud-based storage is suitable for businesses that need scalability, to reduce IT infrastructure management or to store less sensitive or more collaborative data.

Hybrid storage: Hybrid storage combines on-premises and cloud-based storage solutions. Companies can store sensitive or mission-critical data on-premises while using cloud storage for less sensitive or more collaborative data. Hybrid storage offers the flexibility and scalability of cloud-based storage, while still allowing for control over sensitive information. It optimizes storage by storing different types of data in the most suitable environment.

### Data sources
Adventure Works’ current Extract, Transform, Load (ETL) process involves extracting data from sources, including sales, manufacturing, financials, human resources, market research, and social media. The data analytics team transforms the data by cleaning, aggregating, and formatting it as required. The processed data is then loaded into Microsoft Power BI for analysis. The data sources used include:

Sales data: Adventure Works collects sales data, including customer information and purchase history. This data is sensitive and structured, crucial for business operations and used to analyze customer behavior, product performance, and sales trends. The storage solution needs to allow for scalability due to growth in sales and collaboration between sales, marketing, and customer service teams. 

Manufacturing data: Adventure Works generates data through manufacturing processes, including production schedules, inventory levels, and quality control metrics. This sensitive, structured data is used to optimize manufacturing operations and supply chain management. Storage needs include scalability to handle production increases, and collaboration among manufacturing teams. 

Financial data: Adventure Works maintains structured financial data, like revenue, expenses, and profit margins for budgeting, forecasting, and monitoring financial health. As this data is highly sensitive, it needs strict access controls. Storage needs also include some scalability for growing financial records. 

Market research data: Adventure Works conducts market research to understand customer needs, preferences, and market trends. This data, from sources like surveys, focus groups, and competitor analysis, is structured and unstructured. Marketing, sales and product development teams share and use this data collaboratively. Scalability is required to accommodate growing market research efforts.

Social media and online reviews data: Adventure Works monitors social media platforms and online review sites to gather customer and public feedback and opinions. This generates high volumes of unstructured data with high scalability needs. This data provides insights into brand and customer perceptions and areas for growth and improvement. 

### Instructions
Create a new Word document called Data storage and management. In this document, answer the questions below to complete the exercise.

For each data source, list the data type (structured and/or unstructured) and storage needs, for example, security, access and storage capacity in relation to data volume and storage duration (short- and or long-term).

Based on the data sources at Adventure Works, which storage solution(s) (on-premises, cloud-based, or hybrid) are most suitable for storing data from each source? Explain your reasoning.

Discuss four key factors to consider when selecting a data storage solution for Adventure Works.

What are the main advantages of hybrid storage for Adventure Works, and how can it help the company optimize its data storage solutions?

Given Adventure Works' rapid growth and expanding data volumes, which aspects of data management should the company prioritize?

### Conclusion
In this exercise, you analyzed the data sources Adventure Works uses and their storage requirements to determine the appropriate storage solution for the company. You learned about different data types and storage solutions and gained insight into data storage planning. 