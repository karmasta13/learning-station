<!--- <details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day N - Something</summary>

>  🗓️ &nbsp; Date: 2023-02-N  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [ResourceNAME](Link) 

<p align="justify">
</p>
  
<pre><code>
</code></pre>

---

</details> ---> 


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


<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 5 - Measures of Spread in Python </summary>

>  🗓️ &nbsp; Date: 2023-02-24  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Introduction to Statistics in Python](https://app.datacamp.com/learn/courses/introduction-to-statistics-in-python)	

<p align="justify">
Today I learned about measures of spread such as variance, standard deviation, and mean absolute deviation in Python. These measures help to understand how much the data is spread out from the mean or central tendency.
</p>

<details> <br>
<summary> &nbsp; Variance and Standard Deviation</summary>
Variance is the average of the squared differences from the mean, while standard deviation is the square root of variance.

<pre><code>
import numpy as np

data = [2, 4, 6, 8, 10]

var = np.var(data)
std = np.std(data)

print("Variance:", var)
print("Standard Deviation:", std)

## output 
Variance: 8.0
Standard Deviation: 2.8284271247461903

</code></pre>

</details>

<details> <br>

 <summary> &nbsp; Mean Absolute Deviation </summary>
Mean absolute deviation (MAD) is the average of the absolute differences from the mean.

<pre><code>
import numpy as np

data = [2, 4, 6, 8, 10]

mean = np.mean(data)
mad = np.mean(np.abs(data - mean))

print("Mean Absolute Deviation:", mad)

## output 
Mean Absolute Deviation: 2.4

</code></pre>

</details>

<details>

<summary> &nbsp; Difference between SD and MSD </summary> <br>

The main difference between standard deviation and mean absolute deviation is that the former gives more weight to extreme values in the dataset, whereas the latter treats all deviations equally. Therefore, standard deviation is more sensitive to outliers than mean absolute deviation.

</details>

<details> <br>

<summary> &nbsp; Interquartile Range and Outliers </summary>
Interquartile range (IQR) is the range between the first and third quartiles of the dataset, and it can be used to identify outliers. Any value outside the range of 1.5 times the IQR below the first quartile or above the third quartile is considered an outlier.

<pre><code>
import numpy as np
import scipy.stats as stats

data = [2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40]

q1, q3 = np.percentile(data, [25, 75])
iqr = q3 - q1

lower_bound = q1 - (1.5 * iqr)
upper_bound = q3 + (1.5 * iqr)

outliers = [x for x in data if x < lower_bound or x > upper_bound]

print("Interquartile Range:", iqr)
print("Outliers:", outliers)


## output 
Interquartile Range: 18.0
Outliers: [2, 40]

</code></pre>
</details>

---
</details>


<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 6 - Discrete probability and sampling  </summary>

>  🗓️ &nbsp; Date: 2023-02-22  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Datacamp: Random Numbers and Probability](https://campus.datacamp.com/courses/introduction-to-statistics-in-python/random-numbers-and-probability-2?ex=1) , [Youtube playlist: Discrete Probability](https://www.youtube.com/watch?v=oHcrna8Fk18&list=PLvxOuBpazmsNIHP5cz37oOPZx0JKyNszN)

<p align="justify">
Today, I learned about probability distributions in Python, specifically discrete probability distributions such as the binomial, Poisson, and geometric distributions. I also learned about sampling using the sample() method in Python as sampling is the process of selecting a subset of data from a larger dataset, usually for the purpose of making inferences about the larger population.

</p>
  
<p align="justify">
In Python, we can use the NumPy library to generate random numbers from different probability distributions. For example, we can use the binomial distribution to simulate flipping a coin a certain number of times and counting the number of heads. The binomial distribution takes two parameters: the number of trials (n) and the probability of success (p). The following code generates 100 random numbers from a binomial distribution with n=10 and p=0.5:
</p>


<pre><code>
import numpy as np
binomial_dist = np.random.binomial(n=10, p=0.5, size=100)
</code></pre>

<p align="justify">
Similarly, we can use the Poisson distribution to model the number of events occurring in a fixed interval of time or space, given the average rate of occurrence. The Poisson distribution takes one parameter: the average rate of occurrence (λ). The following code generates 100 random numbers from a Poisson distribution with λ=5:
</p>

<pre><code>
import numpy as np
poisson_dist = np.random.poisson(lam=5, size=100)
</code></pre>

<p align="justify">
Lastly, the geometric distribution models the number of trials needed to achieve the first success in a series of independent trials, each with the same probability of success. The geometric distribution takes one parameter: the probability of success (p). The following code generates 100 random numbers from a geometric distribution with p=0.3:
</p>

<pre><code>
import numpy as np
geometric_dist = np.random.geometric(p=0.3, size=100)
</code></pre>
  
<p align="justify">
In addition to generating random numbers from probability distributions, we can use the sample() method in Python to randomly sample a subset of data from a larger dataset. The sample() method takes one parameter: the sample size. The following code randomly samples 10 values from a list of numbers:
</p>

<pre><code>
import numpy as np
data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]
sample = np.random.choice(data, size=10, replace=False)
</code></pre>
    
---

</details>

<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 7 - Continuous Distribution and Binomial Distribution in Python</summary>

>  🗓️ &nbsp; Date: 2023-02-27  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Datacamp: Random Numbers and Probability](https://campus.datacamp.com/courses/introduction-to-statistics-in-python/random-numbers-and-probability-2?ex=1)

<p align="justify">
Today, I continued my exploration of probability theory and practiced using the Uniform distribution and Binomial distribution in Python.
</p>

### Continuous Distribution
<p align="justify">
A continuous distribution is used to describe the probability of a continuous random variable taking on values within a specific range. One common example of a continuous distribution is the Uniform distribution, which describes a scenario where all values in a range are equally likely to occur. In Python, I used the scipy.stats module to work with continuous distributions, specifically the uniform function.
Here's an example of using uniform.cdf to calculate the cumulative distribution function of the Uniform distribution:
</p>
  
<pre><code>
from scipy.stats import uniform

# Define the range of the Uniform distribution (lower bound and upper bound)
lower = 0
upper = 10

# Calculate the cumulative distribution function (CDF) of the Uniform distribution at x = 5 
uniform.cdf(5, lower, upper)

##output 
0.5

</code></pre>

<p align="justify">
I also used the uniform.rvs function to generate random numbers from the Uniform distribution:
</p>

<pre><code>
from scipy.stats import uniform

# Define the range of the Uniform distribution (lower bound and upper bound)
lower = 0
upper = 10

# Generate 10 random numbers from the Uniform distribution
uniform.rvs(upper, lower, size=10)
</code></pre>
---

### Binomial Distribution

<p align="justify">
The Binomial distribution is used to describe the probability of a certain number of successes in a fixed number of independent trials. In Python, I used the scipy.stats.binom module to work with the Binomial distribution.

Here's an example of using binom.pmf to calculate the probability mass function of the Binomial distribution:
</p>
  
<pre><code>
from scipy.stats import binom

# Calculate the probability of getting exactly 2 heads in 5 coin flips
n = 5
p = 0.5
k = 2

binom.pmf(k, n, p)

</code></pre>

<p align="justify">
In this example, I calculated the probability of getting exactly 2 heads in 5 coin flips, where the probability of getting heads on any given flip is 0.5. The k parameter specifies the number of successes, the n parameter specifies the total number of trials, and the p parameter specifies the probability of success for each trial.</p>

<p align="justify">
Overall, it was an interesting day exploring continuous and Binomial distributions in Python. I look forward to continuing my learning and exploring other types of probability distributions.</p>

  ---
</details>
  
  
<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 8 - (Continued) Probability Distributions, Normal Distribution, Poisson Distribution, and the Central Limit Theorem</summary>

>  🗓️ &nbsp; Date: 2023-02-28  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Datacamp: More Distributions and the Central Limit Theorem](https://campus.datacamp.com/courses/introduction-to-statistics-in-python/more-distributions-and-the-central-limit-theorem-3?ex=1)

<p align="justify">
Today, I continued my exploration of probability theory and learned about the normal distribution in more depth, as well as the Poisson distribution and the central limit theorem.
</p>

### Normal Distribution:
  
<p align="justify">
I learned about the normal distribution, which is a continuous probability distribution that is commonly used to model real-world phenomena. Here's an example of using norm.cdf to calculate the cumulative distribution function of the Normal distribution:
  
<pre><code>
from scipy.stats import norm

# Calculate the probability that a random variable from a normal distribution with mean 0 and standard deviation 1 is less than 1
norm.cdf(1, 0, 1)

</code></pre>

<p align="justify">
I also used the norm.rvs function to generate random numbers from the Normal distribution:
</p>
  
<pre><code>
from scipy.stats import norm

# Generate 10 random numbers from a normal distribution with mean 0 and standard deviation 1
norm.rvs(0, 1, size=10)

</code></pre>
---

### Poisson Distribution

<p align="justify">
The Poisson distribution is a discrete probability distribution that is used to model the number of times an event occurs in a fixed time period. In Python, I used the scipy.stats.poisson module to work with the Poisson distribution. Here's an example of using poisson.pmf to calculate the probability mass function of the Poisson distribution:
</p>
  
<pre><code>
from scipy.stats import poisson

# Calculate the probability of seeing 3 cars passing by in 1 minute on average
mu = 2
poisson.pmf(3, mu)

</code></pre>

---

### Central Limit Theorem

<p align="justify">
The Central Limit Theorem states that the sum of a large number of independent and identically distributed random variables will be approximately normally distributed, regardless of the underlying distribution of the individual variables. In Python, I used numpy to simulate the Central Limit Theorem. Here's an example of generating 1000 samples of 100 uniformly distributed random variables and calculating the mean of each sample:
</p>
  
<pre><code>
import numpy as np
from scipy.stats import norm

# Generate 1000 samples of 100 uniformly distributed random variables
samples = np.random.uniform(0, 1, (1000, 100))

# Calculate the mean of each sample
sample_means = np.mean(samples, axis=1)

# Plot the distribution of sample means
import matplotlib.pyplot as plt

plt.hist(sample_means, bins=30, density=True)

# Calculate the parameters of the normal distribution that approximates the sample means
mean = np.mean(sample_means)
std = np.std(sample_means)

# Plot the normal distribution that approximates the sample means
x = np.linspace(mean - 3*std, mean + 3*std, 100)
plt.plot(x, norm.pdf(x, mean, std), 'r')

plt.show()

</code></pre>
  
  ---

</details>


<details> 
<br/>
<summary> &nbsp; 📖 &nbsp; Day 9 - (Continued) Exponential Distribution, t-Distribution, Log Normal Distribution </summary>

>  🗓️ &nbsp; Date: 2023-01-01  &nbsp; &nbsp;| &nbsp; &nbsp; 🔖 &nbsp; Resource: [Datacamp: More Distributions and the Central Limit Theorem](https://campus.datacamp.com/courses/introduction-to-statistics-in-python/more-distributions-and-the-central-limit-theorem-3?ex=1)

<p align="justify">
Today, I continued my exploration of probability theory and practiced using the Exponential distribution, t-Distribution, Log Normal distribution.
</p>

### Exponential Distribution:
  
<p align="justify">
The Exponential distribution is a continuous probability distribution that describes the time between events in a Poisson point process, where events occur independently and at a constant rate. The Exponential distribution has a parameter lambda (λ) which represents the rate of events. Here's an example of using expon.cdf to calculate the cumulative distribution function of the Exponential distribution:
  
<pre><code>
from scipy.stats import expon

# Calculate the probability of waiting less than 3 minutes between two events that occur on average every 4 minutes
lambda_ = 1/4
expon.cdf(3, scale=1/lambda_)

# Output: 0.3296799539643607
</code></pre>
---

### t-Distribution (Student's Distribution)

<p align="justify">
The t-Distribution is a continuous probability distribution that is used when the sample size is small and/or when the population variance is unknown. In Python, I used the scipy.stats.t module to work with the t-Distribution. The t-Distribution has a parameter called degrees of freedom (df) which determines the shape of the distribution. When the degrees of freedom are low, the t-Distribution has fatter tails and a lower peak than the normal distribution. Here's an example of using t.cdf to calculate the cumulative distribution function of the t-Distribution:
</p>
  
<pre><code>
from scipy.stats import t

# Calculate the cumulative distribution function (CDF) of the t-distribution at x = 2
t.cdf(2, df=5)

# Output: 0.9342621026418957

</code></pre>

---

### Log Normal Distribution

<p align="justify">
The log normal distribution is a continuous probability distribution that is used when the underlying data is positively skewed and can be transformed to a normal distribution by taking the logarithm of the data. In Python, I used the scipy.stats.lognorm module to work with the log normal distribution.
</p>
  
<pre><code>

from scipy.stats import lognorm

# Generate 10 random numbers from the log normal distribution with shape parameter = 0.25 and scale parameter = 1
lognorm.rvs(s=0.25, scale=1, size=10)

# Output: array([1.22673498, 0.60983203, 0.62700296, 1.10447058, 1.56578228,
#                0.87423138, 0.85463339, 1.09205123, 1.20236384, 1.12615535])

</code></pre>
  
  ---

</details>
