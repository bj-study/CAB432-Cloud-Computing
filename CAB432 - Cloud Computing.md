# CAB432 Study Guide | 2022 Semester 2

Associate Professor Jim Hogan | Notes for CAB432 at the Queensland University of Technology 

<hr />

<h1>Table of Contents</h1>
<ul>
	<li><a href="#CAB432">CAB432: Cloud Computing</a></li>
	<ul>
		<li><a href="#week1">Week 1</a>: Introduction</li>
		<li><a href="#week2">Week 2</a>: </li>
		<li><a href="#week3">Week 3</a>: </li>
		<li><a href="#week4">Week 4</a>: </li>
		<li><a href="#week5">Week 5</a>: </li>
		<li><a href="#week6">Week 6</a>: </li>
		<li><a href="#week7">Week 7</a>: </li>
		<li><a href="#week8">Week 8</a>: </li>
		<li><a href="#week9">Week 9</a>: </li>
		<li><a href="#week10">Week 10</a>: </li>
		<li><a href="#week11">Week 11</a>: </li>
		<li><a href="#week12">Week 12</a>: </li>
		<li><a href="#week13">Week 13</a>: </li>
	</ul>
</ul>

<hr /> 

<h1 id="CAB432">CAB432: Cloud Computing</h1>
<p>Cloud Computing is among the most important developments in the IT industry in recent years, and one which has received enormous attention. Cloud is a natural progression from earlier trends in service and infrastructure outsourcing and virtualisation, but is distinguished by its elasticity and scale: service and infrastructure provisioning may change rapidly in response to variations in demand, allowing clients to cater for unexpected spikes in load without tying up capital in expensive and potentially underutilised assets. Cloud services and technologies are becoming increasingly diverse and sophisticated, moving rapidly from the original 'bare metal' offerings and providing a rich set of options and APIs. This unit provides a technically oriented introduction to Cloud Computing, giving you experience in developing modern cloud applications and deploying them to the public clouds of the major vendors.</p>

<hr /> 

<h2 id="week1">Week 1: Introduction</h2>

### What is Cloud Computing?
Cloud computing is, at its core, IT infrastructures and services that can be turned on when needed and are payed only when being used. These services can be scaled as needed and automatically adjust themselves based on the current load. Modern cloud computing operates as a global scale providing access to everyone, everywhere at anytime.

So what business case would there be for cloud computing? 
1. Only pay for what you use
2. Don't have to spend the money, time and resources to build server rooms and run them
3. Capacity is managed through elastic provisioning
4. Most major vendors provide unlimited capacity based on how much you pay

### Public, Private, and Hybrid Clouds

| Public Cloud | Private Cloud | Hybrid Cloud |
|--|--|--|
| Services offered by the major vendors | Services hosted and managed by large companies or government | Services based on a mix of public and private clouds |
| Available globally on a commercial basis | Same elastic service model but on a smaller scale | Often used to manage regulatory requirements and client concerns over location of sensitive data sets| 
| "Limited only by the size of your credit card" | Usually more limited service offerings | Government services, Major corporate's | 

### Cloud Pre-requisites

| Virtualisation | Elasticity | Scale |
|--|--|--|
| Costly to maintain lots of small machines | Measure load and automatically scale as needed | Cloud data centres are huge |
| Better to maintain lots of virtual machines (VM) in the one place | Scale out when people are waiting. Scale in when we have too many machines | Major vendors have nodes around the world and their own undersea cables |

### Virtualisation

| Virtualisation Layers |
|--|
| Application(s) |
| Guest OS (many) |
| Hypervisor |
| Host Operating System - Linux, Windows, UNIX... |
| Physical Hardware |

### Types of Cloud Services

| Infrastructure as a Service (IaaS) | Platform as a Service (PaaS) | Software as a Service (SaaS) |
|--|--|--|
| Virtual Machine + OS | Not just the OS | Application hosting in the cloud |
| Pick your size | Pre-configured software stack on each VM | Subscription-based |
| Storage - entity storage, SQL, NoSQL, archive | Managed provisioning and scaling | All hosting and management is done for you at a fee |
| Pick your DB | | Salesforce is usually used |

### Major Providers

#### Microsoft Azure
- Provide a mix of XaaS services but mainly provide IaaS and PaaS
- Their focus areas consist of big data and machine learning
- Azure SQL and SQL Server are two instances of services
- Cognitive Services and Azure ML are key offerings

#### Google Cloud Platform
- Provide a mix of IaaS and PaaS
- Their focus area is IaaS at a large scale
- PaaS remains through Servlet based AppEngine
- Have application areas in search tech, data and machine learning

#### Amazon Web Services
- Provide a mix of XaaS services 
- Huge range of elastic application services
- Have made major improvement in machine learning services in recent years
- Developing a focus on IoT
