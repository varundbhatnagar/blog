---
title: "Privacy, data governance, and machine learning- the regulatory perspective"
date: "2020-02-25 17:25 -0500"
feature: false
published: false
author: "Varun"
---

### Why does privacy and governance matter?

Data privacy has been a common conversation topic among the general public since the Cambridge Analytica scandal of 2018. The data "breach," where user information was hoovered up through a Facebook quiz and subsequently misrepresented as being used for academic purposes, resulted in over $5bn in fines for Facebook. However, users may be surprised to learn that Facebook's infringements were, in fact, relatively narrow in scope (but nonetheless egregious) compared to the growing remit of privacy law. Enterprises with wide-spanning data practices should be wary when establishing data-gathering practices, particularly those practices which are covered by the California Consumer Protection Act and EU General Data Protection Act.

Companies have already begun complying with these regulations, primarily in the form of updated privacy notices. **However, precedence has yet to be set around how data governance (oversight of data flows both within and outside the company) is treated in this process. This article will deal with this intersection, and how it pertains to machine learning operations.** 

### What laws are actually on the books? What are their implications to my business?

There are a couple new laws that directly pertain to company data usage, most prominently GDPR and CCPA. Let's talk about each of them at a high level.

GDPR requires companies that "process" (a purposefully broad term that covers just about anything you can do with data: collection, storage, transmission, analysis, etc.) any personal data of EU citizens must comply with a <a href=https://gdpr.eu/checklist/>{{ 19-point checklist. }}</a> One point on this checklist states: "it's easy for customers to request and receive all the information you have about them." 

The CCPA mandate covers any for-profit entity that collects consumers' personal data, which does business in California, and satisfies at least one of the following thresholds: a) Has annual gross revenues in excess of $25 million; b) Buys or sells the personal information of 50,000 or more consumers or households; or c) Earns more than half of its annual revenue from selling consumers' personal information. This law stipulates, among other requirements, that consumers have the "right to know what personal information a business holds about a consumer and whether the business sells or discloses personal information to third parties."

One way to facilitate compliance would be to build a comprehensive data model, which lists viewing, editing, and administrative rights over data repositories. This data model would necessarily extend to all data-collecting and data-maintaining operations that the enterprise is pursuing.

### Does my machine learning algorithm fall under this law?

In a word, yes. Each of the regulations approach the topic differently:

GDPR is much more exacting when it comes to setting standards for machine learning. Not only does it require companies to divulge all instances in which a customer's data is sold and processed, but it also states the consumers' "right to an explanation." This notion of an explanation has yet to be determined; it is currently being <a href = https://www.kdnuggets.com/2018/03/gdpr-machine-learning-illegal.html>hotly debated</a> by legal scholars. At the very least, it grants individuals "information about the existence of automated decision-making and about 'system functionality,' but no explanation about the rationale of a decision." In other words, consumers will be informed if their, say, credit decision was the result of an algorithm, but not the individual variables that contributed most to the decision.

CCPR mostly focuses on consumer sovereignty around their data, whether that includes the sale, deletion, or correction of their personal data. One potential machine learning-related highlight of the legislation (full text <a href = https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=201720180AB375>here</a>) includes the ban of any sort of price discrimination based on data: "A business shall not discriminate against a consumer because the consumer exercised any of the consumer’s rights under this title, including by charging different prices or rates for goods or services, including through the use of discounts or other benefits or imposing penalties." This sort of outcome could potentially be fostered unintentionally through a pricing model or inventory optimization algorithm. Lawyers are still debating the finer implications of the legislation, which was <a href = https://blog.ericgoldman.org/archives/2019/12/some-lessons-learned-from-the-california-consumer-privacy-act-ccpa-18-months-in-part-2-of-3.htm> written with the goal of being modified in the future. </a> Still, companies are still pursuing compliance activity regardless.

Compliance, in terms of data governance, starts with a well-built data model. This model should ideally cover not just the "golden record," but should also include how the golden record is being applied within business operations. For example, a manufacturing company may rely on   




### Privacy, past and present

Privacy law and ethics stretches back to the 1600s in the United States, when Governor William Bradford opened up mail flowing between the US colonies and England to monitor insurrectionary forces in the Massachusetts Bay Colony. The Townshend Acts of 1768 allowed British tax agents to search colonist homes, and served as the motivation behind the Fourth Amendment within the Bill of Rights, which laid out the definition of a lawful search. Since then, innovations within the postal services, telegraph, and photography have provoked conversations over what level of government snooping ought be considered an overreach. However, these days, private institutions (as opposed to governments) are coming under the popular/regulatory microscope. 

The laws above have pressing implications upon data governance practices, as well as the activities peripheral to the governance function. (AI & machine learning, automation, data 

### Will the government actually enforce this rule?

<a href = https://www.oag.ca.gov/privacy/privacy-enforcement-actions> Yes</a>, and <a href = https://www.enforcementtracker.com/?> yes. </a>
