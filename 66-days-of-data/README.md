# Journey of 66 Days of Data

<br/>
<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 1 - The Importance of Data Governance in Organizations </summary>



> 🗓️ &nbsp;  Date: 2023-02-20  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Learning Data Governance](https://www.linkedin.com/learning-login/share?account=57118729&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Flearning-data-governance-14224082%3Ftrk%3Dshare_ent_url%26shareId%3Dcohrv0OvTo6yI5CniLW7DQ%253D%253D)



<p align="justify">
In this course on data governance, I learned about the importance of managing data effectively within organizations.
As someone who has taken a course on data governance, I now understand that it involves creating policies, procedures, and standards for managing an organization's data assets. These policies cover a wide range of areas, including data privacy, data quality, data security, and data access.
</p>
<p align="justify">
One key takeaway from the course was the importance of data governance in ensuring the accuracy and reliability of an organization's data. Data governance policies help to ensure that the data is of high quality and can be trusted to support decision-making processes. Additionally, data governance can help organizations comply with regulatory requirements related to data privacy and security.
</p>
<p align="justify">
Overall, this course on data governance has helped me to appreciate the importance of managing data effectively within organizations. By implementing robust data governance policies, organizations can ensure that their data is accurate, secure, and reliable, and that it can be used effectively to support their goals.
</p>

___

</details>

<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 2 - Advanced Statistical Techniques </summary>

>  🗓️ &nbsp; Date: 2023-02-21  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Statistics Foundations 4: Advanced Topics](https://www.linkedin.com/learning-login/share?account=57118729&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fstatistics-foundations-4-advanced-topics%3Ftrk%3Dshare_ent_url%26shareId%3DbgrLh5ABQXy0gFkJrRmHGA%253D%253D)	

<p align="justify">
In this advanced statistics course, I gained a deeper understanding of various statistical concepts and techniques that are crucial. One of the most significant takeaways from this course was the importance of experimental design in ensuring the validity of statistical inferences. I learned about different types of experimental designs, such as completely randomized, randomized block, and factorial designs, and how to analyze the data obtained from them using analysis of variance (ANOVA). This knowledge is particularly useful in A/B testing. 
</p>

<p align="justify">
Furthermore, the course covered two-population comparisons, where I learned how to compare means and variances of two populations using different statistical tests, such as t-tests and F-tests. Additionally, the course covered advanced topics such as small sample sizes, t-distribution, degrees of freedom, and statistical power.
</p>

---
</details>


<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 3 - Exploring Analytics Engineering, ETL vs ELT, and dbt for Data Transformation </summary>

>  🗓️ &nbsp; Date: 2023-02-22  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Fundamentals of Dbt](https://courses.getdbt.com/courses/fundamentals)	

<p align="justify">
Today, I learned a bit about analytical engineers, ETL vs ELT and dbt for data transformation. I understood the difference between data engineer and analytical engineer. Data Engineers are responsible for designing and maintaining the infrastructure that enables the storage, processing, and analysis of large volumes of data whereas Analytics Engineers focus on building the analytical infrastructure that enables data-driven decision making. 
</p>
  
<p align="justify">
ETL and ELT are two different approaches to building data pipelines. ELT has become more popular in recent years due to the increasing availability of powerful cloud-based data warehouses, such as Amazon Redshift, Google BigQuery, and Snowflake. The main difference between the two approaches is the order in which the transformations are performed. ETL performs transformations on the data before it is loaded into the target system, while ELT loads the data into the target system first and then performs transformations on the data as needed.
</p>

<p align="justify">
dbt (data build tool) is a popular open-source tool that is used to manage data transformation pipelines. It is specifically designed for ELT workflows and provides features such as version control, testing, and documentation for data transformation code. dbt allows analytics engineers to manage the data transformation process in a more scalable and efficient way.
</p>
  
<p align="justify">
Next, I will dive deeper into dbt and explore this powerful too. 
</p>
  
---

</details>


<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 4 - Diving into dbt fundamentals: A technical overview </summary>

>  🗓️ &nbsp; Date: 2023-02-23  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Fundamentals of Dbt](https://courses.getdbt.com/courses/fundamentals)	

<p align="justify">
Today, I learned about data orchestration, fact models, dimension models, and DAG. I also explored the history of data modeling, including the Star schema, Kimball, and Data Vault. I learned that denormalized modeling, agile analytics, and ad hoc analytics are the latest trends in data modeling. I also learned why marts are called marts, and the differences between materialized tables and views.
</p>
  
<p align="justify">
In addition, I learned that models are .sql files that live in the models folder and that modularity is the degree to which a system's components may be separated and recombined. I also explored the concept of Sources, Staging, Intermediate, Fact, and Dimension models. I learned about upstream and downstream dependencies and the importance of data freshness in dbt.
</p>

<p align="justify">
I learned about the importance of modularity in dbt and how it allows for easy separation and recombination of system components. I also learned about the ref macro, which allows for easy reference to other models in the project. Testing is an essential aspect of data transformation, and dbt has features that allow for testing at multiple levels. There are two types of tests in dbt: singular tests and generic tests. Singular tests are specific queries that run on an entire model, while generic tests are written in YAML and run on specific columns in a model.
</p>

<details>
  <summary>Some of the Terminology</summary>
  
| Term | Description |
| --- | --- |
| Analytics Engineering | The process of creating and managing a data pipeline that transforms raw data into actionable insights. |
| ETL | Extract, Transform, Load - a data integration process that extracts data from source systems, transforms it into a format suitable for analysis, and loads it into a data warehouse. |
| ELT | Extract, Load, Transform - a data integration process that extracts data from source systems and loads it into a data warehouse, where it is transformed for analysis. |
| dbt | Data Build Tool - a tool for managing data transformations and orchestrating the data pipeline. |
| Fact Model | A data model that represents a fact or event, such as a sale or a customer interaction. |
| Dimension Model | A data model that represents a person, place, or thing, such as a customer or a product. |
| DAG | Directed Acyclic Graph - a visual representation of the dependencies between data pipeline tasks. |
| Data Vault | A data modeling technique that focuses on auditability, flexibility, and scalability. |
| Materialized Table | A table that is pre-calculated and stored in a database, improving query performance. |
| View | A virtual table that is a result of a query, allowing users to see a specific subset of data without altering the underlying data. |
| Modularity | The degree to which a system's components may be separated and recombined, often with the benefit of flexibility and variety in use. |
| ref Macro | A dbt macro that creates a reference to a model, allowing users to reuse the code and maintain consistency. |
| Source (src) | Raw table data that have been built in the warehouse through a loading process. |
| Staging (stg) | Models that are built directly on top of sources, used for light transformations that shape the data into what you want it to be. |
| Intermediate (int) | Models that exist between final fact and dimension tables, built on staging models rather than directly on sources to leverage the data cleaning that was done in staging. |
| Upstream | Refers to the models that are required to build a specific model. |
| Downstream | Refers to the models that are built on top of a specific model. |
| Freshness | The time since the last time data was refreshed or updated. |
| Singular Tests | Specific queries that are run against a model. |
| Generic Tests | Tests written in YAML that return the number of records that do not meet your assertions. |
| dbt test | A command that runs tests against a model. |
| dbt build | A command that builds the models and prepares them for the data pipeline. |
| Documentation | Information about a model or data pipeline, often in the form of comments or doc blocks. |
| Doc Block | A comment block in dbt that allows users to provide additional context and information about a model or data pipeline. |

  </details>

---

</details>


