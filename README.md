# AB-test
 We will discuss different topics of A/B testing -- how to choose the metrics, design the experiments and analyze the results after running the experiments. We also cover some statistical background required for A/B testing. We build an interactive ecommerce example to learn how to analyze results from A/B testing.
The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product after a free trial. The goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision. We will use statistical techniques to answer questions about the data and report conclusions and recommendations in a report.
 
 The project included choosing a metric, building intuition, defining hypothesis and comparing two samples for hypothesis testing.
 
# Metric Definition
Two use cases of metrics:

Invariant checking (sanity checking): Metrics that shouldn’t change between your test and control
Do you have the same number of users across the two?
Is the distribution the same?
Evaluation:
High level business metrics: how much revenue you make, what your market share is, how many users you have
Detailed metrics: user experience with the product

# Metric Choice
Click-Through Rate: 𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑐𝑙𝑖𝑐𝑘𝑠/𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑝𝑎𝑔𝑒𝑣𝑖𝑒𝑤𝑠

Use a rate when you want to measure the usability (how often do they actually find that button.)
Click-Through Probability 𝑈𝑛𝑖𝑞𝑢𝑒 𝑣𝑖𝑠𝑖𝑡𝑜𝑟𝑠 𝑤ℎ𝑜 𝑐𝑙𝑖𝑐𝑘/𝑈𝑛𝑖𝑞𝑢𝑒 𝑣𝑖𝑠𝑖𝑡𝑜𝑟𝑠 𝑡𝑜 𝑝𝑎𝑔𝑒

Use a probability when you want to measure the total impact (how often users went to the second level page on your site)
We're interested in whether users are progressing to the second level of the funnel, which is why we picked a probability.

 # Resources
 Udacity free course on A/B Testing
Introduction to bayes theorem https://www.youtube.com/watch?v=HZGCoVF3YvM
