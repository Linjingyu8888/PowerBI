## Exemplar: Data storage and management
### Introduction
In the exercise Data storage and management, you evaluated the data sources and types the data analytics team uses in the Extract, Transform, Load (ETL) process at Adventure Works and data storage solutions. You then answered questions addressing key aspects related to data storage at Adventure Works, including the suitability of a specific storage solution, factors to consider in data storage planning, the advantages of hybrid storage, and the importance of data governance.

You can use the example answers in this reading as a guide to assess your answers to the questions in the exercise. Your answers may differ from the ones in this reading and still be correct.

### Exemplar: Data storage and management
For each data source, list the data type (structured and/or unstructured) and storage needs, for security, access, and storage capacity in relation to data volume and storage duration (short-term and/or long-term).

### Sales data

Data type

Structured

Data storage needs

Moderate to high scalability to handle the increasing volume of sales data over time, secure access for sensitive data, collaboration and sharing for less sensitive data, short-term storage for recent transactions and immediate customer service, and long-term storage for historical or archived sales data and sales performance analysis.

### Manufacturing data

Data type

Structured

Data storage needs

Moderate to high scalability to accommodate changing levels of manufacturing data related to production and inventory levels, secure access and high security levels for sensitive data, for example, intellectual property, controlled collaboration within the department, short-term storage for immediate operational needs during manufacturing, and long-term storage for analyzing historical data to identify trends and areas for improvement in manufacturing and production.

### Financial data

Data type

Structured

Data storage needs

Secure access (primarily highly sensitive data, so high security is required), strict controls and compliance with legal regulations, low to moderate scalability to accommodate the increase in financial records as Adventure Works grows, short-term storage for current financial management, and long-term storage for financial trend analysis and audits.

### Market research data

Data type

Structured and unstructured

Data storage needs

Moderate to high scalability depending on how often and to what degree market research is conducted, collaboration and sharing, short-term storage for ongoing market research and campaigns, and long-term storage for historical data and conducting market trends analyses.

### Social media and online reviews data

Data type

Mostly unstructured

Data storage needs

High scalability (high volumes of mostly non-sensitive data), collaboration and sharing, short-term storage for real-time social media and website monitoring and responding to customers, and customer perception analysis, and long-term storage for tracking long-term trends.

Based on the data sources mentioned, which storage solution(s) (on-premises, cloud-based, or hybrid) would be most suitable for storing data from each source? Explain your reasoning. 

### Sales data
A hybrid storage solution is ideal for storing sales data. The structured nature of this data makes it suitable for on-premises storage, which can offer better security and control for sensitive information, such as specific transaction details, personally identifiable customer information, payment information, or any other data that could potentially be exploited if unauthorized individuals accessed it. At the same time, cloud-based storage can be utilized for less sensitive data, enabling easier access and collaboration among different departments. This data may include information such as descriptions of the products and pricing information. 

### Manufacturing data
On-premises storage would be suitable for manufacturing data since it is structured and may involve sensitive information related to production processes and supply chain management. Ensuring high levels of security and control is crucial for protecting intellectual property and maintaining a competitive edge in the market.

### Financial data
On-premises storage is recommended for financial data due to its structured format and the sensitive nature of the information. Strict security and compliance requirements, as well as the need for full control over data, make on-premises storage the best choice for safeguarding financial records.

### Market research data
A hybrid storage solution is appropriate for market research data. Structured data, such as survey results, can be stored on-premises for increased security and control. Unstructured data, like focus group recordings or competitor analysis documents, can be stored on the cloud to facilitate easier access and collaboration among team members.

### Social media and online reviews data
Cloud-based storage is ideal for social media and online reviews data, as this information is primarily unstructured and requires extensive processing for analysis. Storing this data on the cloud allows for easier scalability, efficient data processing, and simplified access for teams working on sentiment analysis or brand perception.

Discuss four key factors to consider when selecting a data storage solution for Adventure Works.

### Accessibility and collaboration
With different departments at Adventure Works needing access to various data types, the storage solution should facilitate easy access and collaboration. Cloud-based storage is particularly beneficial for less sensitive data that requires frequent collaboration, such as aggregate sales data or market research data. The ability to access data from anywhere and share it among different departments can also facilitate more efficient workflows and decision-making processes.

### Scalability
Given the rapid growth at Adventure Works, it's generating increasing volumes of data, especially from sales and market research efforts. It is crucial to select storage solutions that can scale along with the company's growth. Cloud-based storage solutions are particularly advantageous in this context because they can be easily scaled up or down depending on the company's current needs, without the need for significant hardware investments.

### Data sensitivity and security
Adventure Works handles a variety of sensitive data types, including sales data that involves customer personal details, financial data containing the company's financial records, and manufacturing data that can include proprietary information about production processes. Due to the sensitive nature of these data sets, it is crucial to prioritize security measures. For instance, on-premises storage could be used for highly sensitive data that requires strict access controls, such as financial data and proprietary manufacturing information. This ensures that data is less vulnerable to external breaches and the company retains full control over it.

### Data type
Adventure Works uses both structured and unstructured data. The sales, manufacturing, and financial data are generally structured, while market research data and social media data can be both structured and unstructured. Therefore, the chosen storage solution should be capable of handling both types of data efficiently. For structured data, the company can use traditional databases on-premises or in the cloud, while for unstructured data, storage solutions that can handle large volumes of non-relational data, such as cloud-based data lakes, are beneficial.

What are the main advantages of hybrid storage for Adventure Works, and how can it help the company optimize its data storage solutions?

### Flexibility
Adventure Works deals with both structured and unstructured data. Structured data, such as sales transactions, customer information, and inventory levels, is typically organized and easy to analyze. Unstructured data, such as customer reviews and social media engagements, is harder to manage and analyze because it doesn't fit neatly into a predefined format. Hybrid storage provides the flexibility to store these diverse types of data in the most suitable environment based on its sensitivity and usage. For example, Adventure Works could store sensitive structured data like sales transactions or customer information on-premises while storing unstructured data like customer reviews and social media engagements in the cloud where it can be more easily accessed and analyzed.

### Scalability
As Adventure Works continues to grow, its data volume will increase. This is especially evident in areas such as sales data, manufacturing data, market research data, and social media data. A hybrid storage solution will allow Adventure Works to scale up their storage resources quickly and cost-effectively. This can be particularly helpful when dealing with high volumes of unstructured data from social media and online reviews, which can be stored and scaled up in the cloud, while more sensitive structured data can be maintained on-premises.

### Security and control
Adventure Works handles sensitive data, especially in areas such as sales, manufacturing, and financials. Hybrid storage provides a balance between the security and control of on-premises storage and the scalability and accessibility of cloud storage. Sensitive data such as sales, manufacturing, and financial data can be securely stored on-premises, while less sensitive data can benefit from the easy accessibility of cloud storage.

### Improved data management
Hybrid storage allows Adventure Works to manage and organize its data more efficiently by storing it in the most suitable environment based on its type, sensitivity, and usage requirements. For example, structured data like sales transactions and customer information can be stored on-premises for secure, efficient analysis, while unstructured data like social media posts can be stored in the cloud for easier access and analysis. This improved data management can enhance data analysis, decision-making, and overall business performance.

Given Adventure Works’ rapid growth and expanding data volumes, what aspects of data management should the company consider?

### Data governance
As Adventure Works grows, it is essential to establish a comprehensive framework of data governance. This includes defining clear policies and procedures for data collection, storage, access, and usage throughout the organization. A clear governance policy will ensure that Adventure Works has a holistic view of its data and it can be accessed and used by all relevant parties in a consistent and efficient manner.

### Data quality
To support its growth trajectory, Adventure Works must maintain high-quality data. Data quality is important as accurate, complete, up-to-date, and relevant data is foundational to reliable analytics and decision-making. The company must implement and continually refine processes for checking, cleaning, and enriching data.

### Data integration
Data integration is a key priority because Adventure Works has a variety of data sources, including sales, manufacturing, financials, human resources, market research, and social media. As the company grows, so does the complexity of the data and the need to consolidate this data into a unified view. This facilitates comprehensive data analysis and deeper insights into business operations and performance.

Data security and privacy
As data volume increases, it's important to prioritize data security and privacy measures to protect sensitive information, such as customer information and financial data. Adventure Works must implement strong access controls and monitoring activities, and comply with data protection regulations to ensure data integrity and maintain customer trust.

Data retention and archiving
Adventure Works must develop and implement a data retention policy to retain data for the appropriate time based on legal requirements and business needs. A system to archive data that is no longer in active use is also critical, as this can help Adventure Works manage data storage costs, improve system performance, and ensure that this data can be accessed when needed.

Conclusion
By completing this exercise, you learned about data storage solutions and the role different data types and sources play in the selection of these solutions. You gained hands-on experience evaluating data sources and types, as well as determining an appropriate storage solution, in a business context. As data continues to play an increasingly important role in businesses like Adventure Works, having the right data storage solutions in place is essential.