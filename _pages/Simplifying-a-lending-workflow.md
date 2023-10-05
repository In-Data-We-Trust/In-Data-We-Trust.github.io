---
layout: page
title: Simplifying a fintech bank’s lending workflow
description: The problem – A surge in mortgage applications stresses a bank’s lending workflow
permalink: /case-studies/simplifying-a-lending-workflow/
---

A newly launched fintech challenger bank is fast becoming the ‘go to’ bank for SMEs. In May 2020, commercial mortgage applications surge as the global Covid-19 pandemic causes larger banks to withdraw their products. 

But the bank’s workflow management system isn’t effectively supporting the operations, underwriting and finance departments, leaving teams struggling to manage dramatically increased workflow volumes. The bank needs an improved mortgage application workflow overview, and fast.   

## Building a reputation as the ‘go to’ bank for SMEs

A new fintech challenger bank has been launched to fill a gap in the UK banking sector: supporting SMEs – small and medium-sized businesses with 10-250 employees.

The bank has grown steadily since its launch in 2019. In early 2020, the Covid-19 pandemic knocks the world off its axis, forcing changes in the banking landscape. A team lead at the bank explains:

> When we launched, we weren’t known to a lot of business owners. When Covid struck a lot of the big lenders retreated. <br> <br>
Very quickly being less well known wasn’t as important to SMEs. Being prepared to support them mattered now. <br> <br>
Which we did. Our volume of commercial mortgage applications started to grow.

In fact, the volume of applications grew at a fantastic rate. The bank’s lending teams were simultaneously managing unprecedented workloads whilst adapting to new Covid-compliant ways of working.

The combination started to reveal any weak spots. In this case, the workflow management system wasn’t supporting the operations, finance and underwriting teams in the way they needed.

> At the time, there was a linear workflow, but there wasn’t an aggregated view of the workflows. <br> <br>
Teams were working from spreadsheets that didn’t allow them to see the status of each application. <br> <br>
Managers couldn't see how many offer letters needed to be issued or how many KYCs (Know Your Customer) were pending, for example.

Unable to triage the applications and enquiries, teams were becoming reactive rather than proactive. 

Aware of the risk to the SLA (service level agreement) in speed of turning around mortgage applications, and with it the bank’s hard-earned reputation for excellent customer service, something needed to be done. It was time to get Pratik back. 

## Why Pratik?

Pratik had already played a key role in building the bank – you can find out more in our [How a data engineer helped to build a new fintech challenger bank case study](https://www.indatawetrust.co.uk/case-studies/build-a-bank/). The team lead explains:

> Pratik had left, but we called him back in because we needed his expertise in the business. <br> <br>
>
> The phase two roadmap had just been rapidly brought forward and we needed to bring someone in who: (a) understands the domain and (b) really understands banking. <br> <br>
> 
> It wasn’t just that Pratik has worked here and knows the ins and outs of the bank. It was more than that.  <br> <br>
> 
> His knowledge of banking as a whole is incredibly important. <br> <br>
>
> As well as understanding the domain, Pratik understands the underwriting process, the reporting requirements, what’s needed from our proprietary software for our regulatory reporting. He can provide a different structure and view of the world.

Now Pratik needed to improve a workflow management system that was groaning under the volume of work, while the users were relying on it to deliver on the bank’s promise to support SMEs in a time of real need.

## The strategic solution isn’t always the best solution

In this case, there was neither the time nor resources available to build an end-state solution – the strategic solution.

Instead, Pratik set to work creating the solution for the immediate need, based on the existing data infrastructure and systems. 

Pratik explains the situation:

> The teams needed an easy way to identify which were the most urgent applications to review and what next steps needed to be carried out. Making changes to correct this within the existing systems would have taken a considerable amount of time, losing the bank its competitive edge and running the risk of creating unhappy customers. 

Instead, Pratik worked with the existing system and technology to build a suite of dashboards that would provide an oversight of the data in the workflows. The team lead commented:

> You can never underestimate how hard it is to build something from scratch, particularly banks. They're very, very hard. Pratik had the joy of building a bank, and he brought that experience back.

## How we fixed the bank’s workflow problem  

### 1. Understand the problem

With any project, the first course of action for Pratik and his team is to gain a thorough understanding of the problem and the wider business context. 

To do this, they conduct a discovery exercise, which in this case enabled them to:  
- Understand the business process and workflow across operations, finance and underwriting teams.
- Match the business process and workflow against the back-end systems.
- Investigate how data is generated from every single action a user takes, and understand exactly where this information is stored.   

Pratik notes:
> This is where working in data becomes a bit like being a detective, blending both business analysis with development tools.

Working together, Pratik and the team lead interrogated the process, noting every step along the workflow, identifying the pinch-points to be fixed and opportunities for improvement. They made sure they were seeing what the teams were seeing – in this case a far from user-friendly spreadsheet that was cumbersome to use.

Once the entire process was understood across both front end and back end, Pratik and team could make a start on delivering meaningful data. 

### 2. Build a solution

A firm believer in never adding unnecessary complexity, Pratik outlines what happened next:

> Based on our understanding of the problem, the existing workflow, areas of challenge and best ways forwards, we chose the simplest, most relevant technology tools to resolve the challenge.  <br> <br>
> 
> In this scenario, this meant tools such as Azure Data Factory, Power BI and the existing data lake in Azure.

Pratik went into the Core Banking System and data lake, checking to see that they had all the information necessary, where it was stored and how it was accessed. This was then backed up by testing the process with a real case and team member. Pratik recalls:

> Where we couldn’t get clear answers, we tested the systems with the relevant team. Gaining quick feedback enabled us to validate our understanding, which allowed us to move quickly.

The team lead adding:

> We needed to build something that shows visibility of queues and workflow activity. But achieving this is very, very complex and complicated. <br> <br>
>
> What Pratik was doing was huge.

As the bank was using a third-party system, nothing could be changed, everything was ‘Read Only’. To work around this, a replica was created of the critical data tables, which were engineered into the data lake and modelled in Power BI to create a purely visual resource. 

With the necessary access to the information, Pratik could look at how the information could be presented in a more systematic and visual way. 

### 3. Test, iterate, refine the solution

Within a few weeks, working closely with the in-house teams, many of whom were now working from home, Pratik had created a dashboard – the MVP (minimum viable product) for testing and further refinement.  

Soon he was able to give everyone greater visibility of the work distribution, with quick and easy access to information on the application status the teams needed, which was regularly updated every few hours to be as ‘real time’ as possible.

## Outcome

The end result was a dashboard that presented the data in a simpler yet still detailed way that was now searchable – by customer number, company name and stage within the process. Next steps could be seen. Work could be prioritised. 

The process enabled work to flow and the bank to support the SMEs in the way they needed. The team lead notes:

> Before people couldn’t see what they needed to do next. These dashboards told them exactly what they needed to do. If there was an action to be done, it showed them, which is exactly what we needed. <br> <br>
> 
> Pratik built the first view or version of this, which is great.

Pratik adds:  
> We were able to provide a daily report for each team that shows which applications need to be actioned and the length of time any outstanding tasks. <br> <br>
>
> This meant every customer application could be acted upon in a timely way. Suppliers were happy. The bank’s users saw quick turnaround times.

Over time, the world settled down and the bank could look further into the future, on an even stronger footing than before. It was time to consider building the ideal solution: a bespoke workflow management system. 

> Pratik was brought in specifically to lead the engineering team and build the data model needed to meet our lending data requirements and drive business outcomes, while adhering to regulatory compliance.  In effect, the data strategic direction for the next phase of the bank’s growth.

But that’s another case study. 

**If you’d like to talk to Pratik or the team about simplifying a bank’s lending workflow, building a bank, gaining regulatory approval or improving your bank’s management systems and processes, please** <!-- Calendly link widget begin --> <link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet"> <script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script> <a href="" onclick="Calendly.initPopupWidget({url: 'https://calendly.com/pratik-idwt/30min'});return false;"> book a call</a> <!-- Calendly link widget end --> 

<!-- Calendly badge widget begin -->
<link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
<script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
<script type="text/javascript">window.onload = function() { Calendly.initBadgeWidget({ url: 'https://calendly.com/pratik-idwt/30min', text: 'Arrange a call', color: '#0069ff', textColor: '#ffffff', branding: true }); }</script>
<!-- Calendly badge widget end -->
