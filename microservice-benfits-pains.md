

# ������Ŀ��Microservice Architecture in Reality: An Industrial Inquiry 
��https://ieeexplore.ieee.org/document/8703917�� ���Ͼ���ѧ�ź���ʦ��


�о��˼���ά�ȵ�΢����������ʹ��


##  A  Componentization Via Services ��ͨ����������������

#### ����:
 1) Practice 1: Independence by Separation  
- (the benefit of componentization are the independence or the autonomy of microservices)
- (shorten the lead time of products in practice)

#### ʹ��:
  2)  Chaotic Independence
- (For instance, inappropriate boundary among services may decrease the testability, especially when the mi-croservices are over fine-grained)
- (increases the complexity of joint debugging among different versions)
- (the developers may face the requests of joint debugging from different developers at the same time. Some remote microservices are not always connectable in this process, which exacerbates the pain of testing)

 > All these problems may seriously influence the speed of debugging and the efficiency of developments��


## Organized Around Business Capabilities  (Χ��ҵ��������֯)

#### ����:
1)  Organizational Transformation
- ��reduces the dependency and the communication among teams, and consequently lowers the cost of management. ��

#### ʹ��:
2�� Unguided Organizational Transformation
- ��organizations in this study still achieve the transformation mainly based on experience��
The mismatching between the organization structure and the architecture may cause the low 
 efficiency of internal development or the massive communication among teams.  ��������֯ת�Ϳ��ܻ����Ч�ʵ��£�

- �� lack the guide on how to do it�� Most importantly, we need the approval of the decision makers�� ��


 
##  Smart Endpoints and Dumb Pipes (���ܶ˵����ͨ��)

#### ����:
1��  Choosing Communication Protocol

- ��Four main factors concerned by practitioners are the maturity of the technology's ecosystem (8/13), the activity of the community (8/13),
   the supporting documents (6/13), and technology stacks with previous experience (6/13)��

- �����������Ҫָ���ѡ��ܶ࣬����RESTful�� Spring Cloud, ����RPC��Apache Dubbo, �����ṩ�˺ܶ��������

#### ʹ��:
2�� Complexity of API Management
- ��the communications among mi-croservices is the complexity of the implementation and management of API��
 


##   Decentralized Governance ����ɢ����

#### ����:
1�� Controlling Technology Diversity (���Ƽ���������)
- (microservices support a mix of multiple languages, development frameworks and data-storage technologies, i.e. technology diversity
    ���Ǵ�ҵ�߲���������������ԣ����������⣬��汾���Ƶ�)

 #### ʹ��:
 2�� Excessive Technology Diversity

- ��The diversity of technology stacks also raises the requirements on developers' ability and increases the complexity of the learning and construction.��


## Decentralized Data Management ����ɢ���ݹ���

#### ����:
 1�� Compromise with Database Decomposition
> (��������ԭ��δ���Ƿֽ����ݿ⣺)
- ��Memory database in use��
- ��Databases partitioned in legacy systems.��
- ��Benefit analysis of decomposition��

#### ʹ��:

 2��Data Inconsistence
- ��practitioners are usually pained with the complexity of addressing the distributed transactions while ensuring the data consistency.��
- ��messaging-based or event-based, the design and implementation are very complicated��
- ��The real process of addressing the data consistency is far more complicated than the description��



## Infrastructure Automation ��������ʩ�Զ�����

#### ����:
1�� CI&CD
- (applying infrastructure automation technology)
- ��service mesh technology to facilitate the upgrade and the version management of microservices. ͨ��Service Mesh ���������͹���


#### ʹ��:
2�� Inadequate Automation
- ��many existing infrastructure-related technical frameworks are unsatisfying to meet their requirements. ��������ʩ�����������е�����)


## Design for Failure 


#### ����:

1�� Monitoring and Logging
- ��Monitoring Metrics��
- ��Monitoring Strategies��

#### ʹ��:

2) Unsatisfying Monitoring and Logging
- (Insufficiency of Automated Operation)
-  (Difficulty in Troubleshooting)
- (Difficulty in Threshold Setting)
-  (No Well-Rounded Monitoring System)


## Evolutionary Design (�������)

#### ����:
1�� Stepwise Evolution

#### ʹ��:
2��  Missing of an Effective Decomposition Guide ��ȱ����Ч�ķֽ�ָ�ϣ�
- ��DDD is a relatively abstract thing to us, without a specific process. Since different people had different consensus of views about it��








# ������Ŀ��Microservices Maturity Model 

#### ���棺
1. predictability
2. Process controls
3. Effectiveness
4. Focus on business need
5. Agility, enterprises can introduce new products or enhancements into the market quickly 
6. Enhancing the customer experience 
7. Can be developed & deployed independently of other services 
8. Reduced dependency on key resources 
    1. Improved accuracy in scheduling software development/implementation
9. More efficient deployment of technology solutions development / implementation 
10. Increased traceability 
����ҵ����΢����ܹ�����Ҫ��������
11. Enterprise primary business revolves around extremely high volume transactions 
12. Rapid development and enhanced operational support, reduce implementation and release cycle time and enables continuous delivery 
13. Enterprises migrating from Monolithic and Legacy Processes to Microservices 
14. Scalability and flexibility of Cloud service help in handling more customers simultaneously without interrupting service 
15. For the solutions that require the integration of business capability from disparate systems and programming models 
16. For aligning business and IT functionality 
17. For business and technology agility 
18. Better ROI 
19. For incremental development (Agile) and continuous deployment of business software 



#### ʹ��:
1. Miss knowledge and lack of qualified people.


# ������Ŀ��GLOBAL MICROSERVICES TRENDS A SURVEY OF DEVELOPMENT PROFESSIONALS 


#### ���棺
1. By breaking applications down into lightweight and decoupled services that each serve a specific business need, development teams could deploy more frequently, scale more effectively, and avoid many of the problems of software monoliths.
2. Agility (82%) and scalability (78%) are the top motivators for microservices adoption 



#### ʹ�㣺
1. 56% say each additional microservice increases operational challenges 
2. 73% find troubleshooting is harder in a microservices environment 
3. 98% of those that face issues identifying the root cause of issues in microservices environments report it has a direct business impact 
4. 87% of those in production report microservices generate more application data 



# ������Ŀ��Migrating towards Microservice Architectures: an Industrial Survey 

####  ���棺
1. agility
2. scalability
3. have flexible and evolvable architectures 
4. Resolving existing issues(Typical issues of legacy systems are technical (e.g., the system becomes highly coupled, hard to maintain, presents side effects) or business-related (e.g., long time to release new features, low productivity of developers)).
5. Improving the system maintainability and the frequency of product releases.

#### ʹ�㣺
1. infrastructure automation 
2. distributed debugging
3. Creation of cross-functional teams



# ������Ŀ�� Supporting Microservice Evolution


#### ���棺
1. scale-out application
2.  loose coupling
3. agile and rapid evolution


#### ʹ�㣺
1. Checking for upgrade consistency  

 ��developers manually identify micro service dependencies and either engage with other developers who own that
 micro service or evaluate the dependency through code inspection��
 
2. Identifying architectural improvements  (�ܹ���ȷ������)

   ��An evolving ��App will experience software architectural corrosion, such as a decrease in cohesion and increase in coupling between related services. ��
   
   
3. Evaluating changing deployment trade-offs

   ��Today developers evaluate changing deployment trade-offs through trial and error without a systematic strategy nor much tool support.��
   
   
   
#  ������Ŀ�� Microservices The Journey So Far and Challenges Ahead

#### ���棺
1. faster  delivery
2. scalability
3. greater autonomy


#### ʹ�㣺
1. Service Modularization and Refactoring

   ��With any approach to modularization, finding the right modules, with the right size, 
   the right assignment of responsibilities, and well-designed interfaces, is a challenge. ��
   
   
2. Service Granuiarity

   ��Another issue is the lack of agreement on the right size of microservices. Although the name 
   itself seems to suggest that microservices should be as small as possible, project teams tend to interpret this tenet in drastically different ways. )

3. Resource Monitoring and Management
  
   (As microservice applications' size and complexity grow, the number and diversity of infrastructure resources 
   (for example, virtual machines, containers, services, messages, thread pools, and logs) that must be continuously 
   monitored and managed at runtime also increase.)
   
   
4. Failure, Recovery, and Self-Repair
  
    (Like any type of distributed system, microservices typically are fragile. For many reasons, 
	such as network, hardware, or application-level issues, they might become unavailable, become inaccessible, or simply fail. )
	
	
5. Organization Culture and Coordination
   
   (Having many autonomous teams developing independently deployed services might be a double-edged sword. One one hand, 
   each team can make local decisions without always having to negotiate with other teams. 
   On the other hand, it increases the risk of teams failing to see the big picture��that is,
   to understand whether their local decisions are justifiable and coherent in the context
   of the system's overall architecture and business goals.)
   

# ������Ŀ��Microservices: Architecting for Continuous Delivery and DevOps

#### ���棺
1. Deployment independency.(After the application has been moved to Microservices, there is no need to queue for merges; no need to resolve merge conflicts with other teams; and no need to coordinate with and wait for other teams�� changes. Finally, each team can deploy their changes independently)
2. Shorter deployment time.(Each service is significantly smaller than the corresponding former monolith. Deploying such a small service takes a shorter amount of time than that for the corresponding former monolith)
3. Simpler deployment procedures.(The procedures to deploy a large monolithic application are generally more complex than the procedures to deploy a microservice)
4. Zero downtime.(After the application has been moved to Microservices, we can choose the most suitable database for each individual service. It turned out only a small portion of the services actually required a relational database. Thus, all the other services use a NoSQL database, which is more amenable to schema evolution)
5. Shorter cycle time for small incremental functional changes(For most small incremental functional changes, we have reduced the cycle time from multiple months to two to five days. Although we cannot attribute all the cycle time reduction to the use of Microservices, the use of Microservices is a factor to achieve such short (two to five days) cycle time.)
6. Incremental quality attribute changes(We are not only able to make incremental functional changes but also to make incremental changes to quality attributes. )
7. Easier technology changes(Teams can choose different technologies for implementing their services)
8. Easier language and library upgrades(each team can upgrade independently because each service no longer shares the same code base, compilation process, and language runtime (e.g., Java virtual machine) with other parts of the system. )

#### ʹ�㣺
1. Increased number of services(The traditional approach is not able to handle the significantly increased number of services with frequent releases. The large number of deployment requests greatly exceeds what the operations engineers can handle. )
2. Evolving interactions/contracts among services.(With Microservices, some interactions that were formerly internal communications within an application became external communications among services. This led to more interactions among services and more contracts to manage. Not only did the number of interactions/contracts increase, but all the participants in these interactions also undergo frequent changes. )
3. Technology diversity(Using diverse technology stacks in an uncontrolled manner can lead to problems. For example, each team using a different technology stack creates knowledge silos that make moving individuals from overstaffed to under-staffed teams difficult. Moreover, each introduced technology stack requires operational overhead, which can outweigh the benefits of introducing a new technology stack)
4. Testing(Microservices introduces testing challenges, which mainly arise from changes that impact interactions among services)


# ������Ŀ��Microservices Architecture: Challenges and Proposed Conceptual Design

#### ���棺

1. Scalability �C With the instances of small sized microservices being easy to develop, implement and operate, scalability of large complex systems can be increased manifolds.

2. Continuous Delivery �C Implementation of new microservices and re-deployment of existing microservices with an upgraded functionality is a lot easy.

3. Development �C Microservices implementing single tasks / logic involves less efforts in development and deployment of individual microservices.

4. Independence �C Microservices are considered to be developed and implemented in a way that it should work independently hence removing various dependency issues like error cascading through other operations.

5. Maintainability �C Due to the small size it is prone to less bugs and is easy to maintain and upgrade.

6. Reusability �C Independent microservices with dedicated own databases can be re-used multiple times without understanding of the detailed internal working.

7. Technology Heterogeneity �C An opportunity to use the technology of own choice for implementation of independent microservices.



#### ʹ�㣺
1. Interactions between Microservices and Client

   (direct interactions between UI and microservices then it will be causing congestion by too many calls between both over public network)
   
2.  ACID Transactions in Databases per Microservices

    (Microservices are proposed to act as an independent working entity with its own dedicated data portion which presents an issue of ensuring ACID (Atomicity, Consistency, Isolation, Durability) transactions spanning over multiple databases per microservces. )
	
3. Fault Tolerance
   
   (with the single failure of one microservice, it can result a complete failure or ripple effect in operations of the complete software system. )
   

4. Monitoring (Performance / Analytics)
   
   (Software systems consisting of microservices present a challenge of handling the performance issues and analytics of microservices)
   
5. Security

   (Security is a major challenge in any software system however with multiple large number of microservices, preventing 
   unauthorized access to business operations is a serious challenge to implement at various layers of the system (application, deployment platforms etc).)
   

6.  Deployment and Integration

   (Deployment of a large complex system is always a problem however incase of microservices architecture integration between microservices
   and the deployment of microservices is a major challenge which needs to be catered for from the initial design phase. )



#   Microservices: Yesterday, Today, and Tomorrow

#### ���棺
1.  A microservice is a cohesive, independent process interacting via messages. 
    ��microservicesshouldbeindependentcomponents conceptuallydeployedinisolationandequippedwithdedicatedmemorypersistence tools (e.g. databases).��


2.  Microservices naturally lend themselves to containerisation 
   	��developers enjoy a high degree of freedom in the con?guration of the
	deployment environment that best suits their needs (both in terms of costs and quality of service). 
	
3.  Scaling a microservice architecture does not imply a duplication of all its components
    �� developers can conveniently deploy/dispose instances of services with respect to their load ��

4. 	developers can freely choose the optimal resources (languages, frameworks, etc.) for the implementationof each microservice
 
5. Size
   ��only a single business capability. This brings bene?ts in terms of service maintainability and extendability.�� 
   
6. Bounded context
   ��Related functionalities are combined into a single business capability, which is then implemented as a service��

7. Independency
    ����Each servicein microservicearchitectureis operationallyindependent from other services, 
	and the only form of communication between services is throughtheir publishedinterfaces��

8. Flexibility
   ��A system is able to keep up with the ever-changing business environment and is able to support all
   modi?cations that is necessary for an organisationto stay competitiveon the market��

9. Modularity
   ��A system is composed of isolated components where each component contributes to the overall 
   system behaviour rather than having a single componentthat offers full functionality��
   
10. Evolution
    ��A system should stay maintainable while constantly evolving and adding new features.��
	
	
#### ʹ�㣺

1. Dependability
   ��There are many pitfalls that we need to keep in mind when programming with microservices. 
   In particular, preventing programming errors is hard. Consequently, building dependablesystems is challenging.��
   
2. Trust and Security
   ��The microservice paradigm poses a number of trust and security challenges. These issues are certainly not new, as they apply to
   SOA and in general to distributed computing,but theybecomeevenmorechallengingin the contextof microservices. ��
   
   ��GreaterSurface Attack Area��
   
    ��Network Complexity��
	
3. 


# ����ͳ��
- independence or the autonomy of microservices (Scalability and flexibility, can be developed & deployed independently of other services, More efficient deployment of technology solutions)
- agility, for incremental development (Agile) and continuous deployment of business software
- scalability
- loose coupling
- faster delivery, shorten the lead time of products in practice  (Rapid development and enhanced operational support, reduce implementation and release cycle time and enables continuous delivery)
- greater autonomy
- have flexible and evolvable architectures
- reduces the dependency and the communication among teams, and consequently lowers the cost of management
- controlling Technology Diversity
- stepwise Evolution
- focus on business need
- enhancing the customer experience
- reduced dependency on key resources
- Increased traceability ����ҵ����΢����ܹ�����Ҫ��������
- Improving the system maintainability and the frequency of product releases.


# ʹ��ͳ��
- miss knowledge and lack of qualified people.   
- increases operational challenges
- troubleshooting is harder ��distributed debugging, decrease the testability ,  joint debugging among different versions�� 
- microservices generate more application data
- creation of cross-functional teams �� Organization Culture and Coordination ( lack the guide on how to do it) 
- lack infrastructure automation ��Inadequate Automation��
- checking for upgrade consistency
- identifying architectural improvements ��Service Modularization and Refactoring, Missing of an Effective Decomposition Guide��
- evaluating changing deployment trade-offs
- resource Monitoring and Management  ��unsatisfying Monitoring and Logging��
- failure recovery, and Self-Repair
- chaotic Independence (when the microservices are over fine-grained)
- complexity of API Management 
- excessive Technology Diversity (increases the complexity of the learning and construction)
- data Inconsistence ��implementation are very complicated��
  
