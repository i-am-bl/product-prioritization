# product-prioritization

## Table of Contents

- [product-prioritization](#product-prioritization)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
    - [Purpose](#purpose)
    - [What is a prioritization framework?](#what-is-a-prioritization-framework)
    - [Why is a prioritization framework important?](#why-is-a-prioritization-framework-important)
    - [What are some examples of a prioritization framework?](#what-are-some-examples-of-a-prioritization-framework)
  - [Products](#products)
    - [🏷️ Enterprise Banking Software](#️-enterprise-banking-software)
    - [🏷️ Loan Application Software](#️-loan-application-software)

## Introduction

One of the greatest challenges in product management is prioritization. What is the biggest priority? The role of a product leader is like managing a traffic jam. Each side is a force that includes customers, design, engineering, and stakeholders. Everything is a top priority, and each group has a different opinion on what should be a top priority.

### Purpose

The intent of this document is to share my experiences with prioritizing features, the problems faced, and the lesson I learned from my experiences.

---

### What is a prioritization framework?

A prioritization framework is a tool to identify and assign priority to a feature or idea. These frameworks are intended to help justify the assigned priority when communicating to stakeholders. A great framework will make communication or negotiating with stakeholders much easier.

---

### Why is a prioritization framework important?

Product teams and stakeholders rarely share a comprehensive product vision. Establishing alignment to gain agreement is a daunting task. It is even harder to maintain alignment. Priorities for stakeholders can shift easily, making the job of a product leader extremely difficult.

---

### What are some examples of a prioritization framework?

There are numerous prioritization frameworks. Below are some of the more popular frameworks. It is common for frameworks to be expanded to fit the needs of specific use cases. There is no perfect solution for prioritization. The frameworks have pros and cons. To pick a framework, factors like product maturity and industry should be considered.

- ✨ **ICE (Impact Confidence Ease)**\
  **This is best for smaller teams in industries where speed is crucial.**\
  Invented by Sean Ellis as a tool for growth teams. It considers three factors of impact, confidence, and ease.
  - **Impact**: How much will this feature impact the target KPI?
  - **Confidence**: What is the confidence level this will have impact?
  - **Ease**: How much effort is required to implement?
- ✨ **RICE (Reach Impact Confidence Effort)**\
  This is a more in-depth framework than ICE, factoring in reach. The scoring process is more detailed and can be best suited for larger product teams with a larger customer base.
  - **Reach**: The estimate of how many users this feature will reach.
- ✨ **Cost of Delay**:\
  **This is best for teams using SAFe (Scaled Agile Framework).**\
  In highly competitive industries, a "first-mover advantage" can help out perform the competition. Essentially, this helps calculate the opportunity cost when there are longer periods of development.
- ✨ **Value vs. Effort Matrix**:\
  **This simple framework is best for teams operating in lean agile.**\
  This is one of the most well-known frameworks due to its simplicity. Plotting features on graph with value as the x-axis and effort on the y-axis. It helps teams to focus on features that offer the highest return with the least amount of input.
- ✨ **Kano Model**:\
  **This is best for large product teams with a large customer base.**\
  This framework sorts features into five categories: must-have, performance, attractive, indifferent, and reverse. Focusing on the customer, it requires detailed surveys.
- ✨ **MoSCoW (Must have, Should have, Could have, Won't have)**:\
  **This is best for products early in the development stages.**\
  By organizing features into these categories, it helps to conceptualize the product, focusing on the product vision.
- ✨ **Opportunity Scoring**
  **Most suitable for companies in highly competitive industries.**\
  This framework is rooted in the ODI (Outcome-Driven Innovation) method. Through customer research, simple questions are asked, providing a score. These scores are used to map the opportunity landscape based on customer satisfaction and importance.
- ✨ **PIE (Potential Importance Ease)**
  **Best for simple yet effective prioritization.**\
  This approach simplifies decision-making to ensure efforts are directed at what will have the most impact.
- ✨ **ABCDE**
  **Best for quick prioritization, focusing on high impact.**\
  Following the alphabet, this prioritizes features in the following categories: A - very important, B - important, C - nice to have, D - delegate, and E - eliminate. It is intended to prioritize the most critical tasks first.
- ✨ **Weighted Scoring**
  **Best for data-driven decisions.**\
  This is a robust decision model. The framework calculates priority by assigning weights and different criteria.

In conclusion, there are many great frameworks for prioritization. Some are a better fit than others considering industry, product maturity, and team size. While each framework has some subjectiveness, it can still be a great tool for making an informed decision.

---

## Products

Below is a summary of the products managed.

| Product                                                          | Description                                                                                 |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| 🏷️ [Enterprise Banking Software](#️-enterprise-banking-software) | Software consisted of many modules to effectively manage the loan lifecycle.                |
| 🏷️ [Loan Application Software](#️-loan-application-software)     | Application software was a data collection tool to streamline the loan application process. |

### 🏷️ Enterprise Banking Software

Product is B2B banking software offering a multi-module application designed to facilitate the loan life cycle. The primary value added was decreasing the time to fund. Product delivered the ultimate support strategy to financial institutions. Product strategy empowered institutions to process all loans or offload the processing to an experienced support staff. Support staff did not consist of third-party service providers. This amazing support team lived in-house, sharing the company vision and passion for clients. This package delivered a one a kind customer experience.

The system offered a customizable ELT data pipeline through secure FTP, compatible with an institution’s banking core solution.

🔎 **Industry**:

- 52211 - Commercial Banking
- 52213 - Credit Unions

> **Tip**: [NAICS] - [Industry]

📰 **Background**:

The product organization was small, I was the sole product manager. There was an established vision for what the product was expected to do. The expectation was defined with a list of features. These features averaged 3-9 months in development effort. This does not include ideation and design time. The feature list could be translated into four years of development.

⚙️ **Challenges**:

I was presented with numerous challenges while managing the feature backlog.

- ✨ **Unexpected changes in priority.**\
  There were unexpected changes in priority due to internal or external factors. There were times a promise was made for a sell or a business relationship that shifted the priority. Other times, the senior team had a new idea, they felt it was important enough it had to happen then.
- ✨ **Too many priorities.**\
  The company was highly dependent upon the product. Not only did we sell it, but we also used it internally to service our clients. This could be understood as software enabled services. Stakeholders consisted of senior leaders from each department. Each department had different needs, and each felt their need was more important to help their teams perform and meet revenue goals.
- ✨ **Stakeholders were misaligned.**\
  The business was a people first company, and the senior team did a great job at meeting often. Product development was an exciting topic at all meetings, and I did not attend all these meetings. As they were excited about new ideas, they were shared without context and stakeholders misinterpreted what had been prioritized. As I met with stakeholders, they all were excited to discuss what we were currently working on. I was always surprised to hear what we were working on because it was not ever what we were actually working on.

💡 **Solutions**:

- ✨ **Data-Driven Decisions**\
  The business was a people first company, focusing on their employees and their customers. The product had internal customers and external customers. These many voices easily disrupted our roadmap, creating chaos. I did not have the resources to create a formal process for surveys or data collection. As the voice of the customer, I had to find a way to create a message they could relate to. This industry was highly regulated, focused on risk and compliance. To become more effective, I performed a risk analysis to change the perspective of leadership. This shift in perspective quickly identified the "must haves" from the "nice to haves."
- ✨ **Stakeholder Alignment**\
  As the owner of the roadmap, I would analyze, justify, and gain buy-in from stakeholders. This was not enough. I continued to be informed rather than the informer as things changed often. I had a similar problem that I solved by forming a committee. I gained buy-in from my boss and a product committee was formed. The committee included me and three executives. I led a strategy call every two weeks to gain alignment. Approvals were documented and accountability was established.
- ✨ **Product Goals**\
  The roadmap was a list of features, enough for years of work. This presented a difficult challenge for prioritizing the backlog with stakeholders. I found a way to change our perspective of what we were prioritizing. Rather than prioritizing features, we prioritized outcomes. I did this by creating a roadmap theme and product goals that were directly related to corporate goals. By focusing on what we wanted to achieve, we were more effective in identifying the features that created our desired outcomes.
- ✨ **Opportunity Cost**\
  Stakeholders were reactive and priorities shifted often. I felt the problem was they did not have enough information to make an informed decision. To mitigate this, I used project plans to estimate the opportunity cost to delivery if resources were reallocated. Projects consisted of months of work. The visual shift on a timeline helped to visualize the opportunity cost, effectively creating accountability for the team.
- ✨ **Prioritization Framework**\
  Stakeholders struggled to know if we were delivering the right thing. We attempted to do some analysis using different frameworks. As we were maturing, we kept things simple by using a variation of the Value vs. Effort framework, Value vs Competitiveness.

🚀 **Outcome**:

The outcome was successful.

This took time and strategic planning to achieve. I was not able to fully resolve all the problems, but I significantly decreased the severity. The senior leaders held the final decision; sometimes the final decision disrupted our plan. I navigated disruptions the best I could, reprioritizing the roadmap.

In conclusion, the disruptions did occur, but we successfully established alignment. The team agreed to self-accountability and held themselves accountable if a change was made. With the solutions described, I did the best I could to give the senior team the best information possible to make an informed decision.

🚀 **Key Takeaways and Lessons Learned**:

Executive presence is an amazing opportunity to effectively develop leadership skills.

This was a difficult situation to navigate. I was receiving great feedback on my efforts; I was exceeding expectations, but the ground kept moving. The teams were frustrated; we were struggling to decide if we were delivering the right thing.

The teams were doing their best with what they had. I quickly realized the senior team was doing the same thing. They were accustomed to making decisions without data and we were still working on collecting data. Once I had perspective rather than perception, I began developing a plan to help us prioritize.

In conclusion, it is important to have perspective over perception. When there is not enough information or good communication, people create their own perception. The senior team was creating their own perception and needed help putting things in perspective. I learned it takes patience and time to change minds.

---

### 🏷️ Loan Application Software

B2B loan application software is a white labeled customer facing product, facilitating the loan application process through an online presence, designed to decrease the time to fund and provide a method for secure file transfer.

🔎 **Industry**:

- 52211 - Commercial Banking
- 52213 - Credit Unions

> **Tip**: [NAICS] - [Industry]

📰 **Background**:

The product organization was very small, I was the sole product manager in the organization. I inherited this product while it was in the design phase. It took approximately two years to take this product to market.

This was one of two products I managed at this organization.

⚙️ **Challenges**:

I was presented with numerous challenges while managing the feature backlog.

- ✨ **Features were too large.**\
  As the launch date was approaching, I was sent a list of features. Stakeholders were excited for the launch but were ready for the next iteration. To make the launch date, we deprioritized items, launching a leaner product. The list of features I received included what we deprioritized but bigger.
- ✨ **Prioritizing features for two products.**\
  We now had two products and stakeholders wanted to look at one of list priorities. This made prioritization much more difficult. Both products had a long list of features in the backlog and the list was unmanageable.
- ✨ **Product Vision**\
  Stakeholders had varying opinions on the product vision. Without a clear vision, the product had no identity. Examples include data collection tool, sales lead generation, borrower application, etc.

💡 **Solution**:

- ✨ **Product Separation**\
  One roadmap was not the solution. It felt like we were trying to prioritize and allocate resources at the same time. I established separate roadmaps for each product. The separation of concerns simplified the exercise by focusing on identifying what was most important for each product.
- ✨ **Smaller Features**\
  Large features resulted in bigger commitments, longer development periods, and realized value was delayed. This problem was less severe for our other product line. It was more mature and had a clear vision. This product had yet to launch, and we were still unclear on the vision. To mitigate this risk. I began breaking features down into smaller deliverables to make prioritization easier.
- ✨ **Prioritization Framework**\
  We struggled to prioritize features for the product. Every stakeholder seemed to have a different vision for the product. The product needed a clear identity that we could all agree on. Like the MoSCoW framework, I developed a method for us to identify what the product needed to be. The team needed to align before we could find success. Once aligned, we were able to focus on what was most important.

🚀 **Outcome**:

The stakeholders were aligned, establishing a vision for the product. The product was to be branded as a data collection tool that would evolve into a borrower application for commercial loans.

A roadmap was created based on product goals. Features were identified that would generate the expected outcome.

🚀 **Key Takeaways and Lessons Learned**:

This was a difficult situation to navigate. While taking this product to market, the definition of the product changed multiple times. I made the mistake of assuming we were aligned in the product vision. This taught me the importance of formal documentation, even in an informal atmosphere.

I played a pivotal role in leading the team to a decision.

Large features were a common problem in both product lines. This was a great opportunity to begin introducing the idea of smaller deliverables. Smaller deliverables mitigated the risk of overcommitting to a feature that was not as impactful as originally projected. Research and analysis are helpful, but impact is still subjective, even with data.

In conclusion, it was an exceptional experience to lead the team through these difficult problems. The team had been accustomed to making decisions in a certain way. Their willingness to change made this a success story.

---
