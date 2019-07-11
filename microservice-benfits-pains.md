

# 论文题目：Microservice Architecture in Reality: An Industrial Inquiry 
（https://ieeexplore.ieee.org/document/8703917） （南京大学张贺老师）


研究了几个维度的微服务的收益和痛点


##  A  Componentization Via Services （通过服务进行组件化）

#### 收益:
 1) Practice 1: Independence by Separation  
- (the benefit of componentization are the independence or the autonomy of microservices)
- (shorten the lead time of products in practice)

#### 痛点:
  2)  Chaotic Independence
- (For instance, inappropriate boundary among services may decrease the testability, especially when the mi-croservices are over fine-grained)
- (increases the complexity of joint debugging among different versions)
- (the developers may face the requests of joint debugging from different developers at the same time. Some remote microservices are not always connectable in this process, which exacerbates the pain of testing)

 > All these problems may seriously influence the speed of debugging and the efficiency of developments…


## Organized Around Business Capabilities  (围绕业务能力组织)

#### 收益:
1)  Organizational Transformation
- （reduces the dependency and the communication among teams, and consequently lowers the cost of management. ）

#### 痛点:
2） Unguided Organizational Transformation
- （organizations in this study still achieve the transformation mainly based on experience，
The mismatching between the organization structure and the architecture may cause the low 
 efficiency of internal development or the massive communication among teams.  不当的组织转型可能会带来效率低下）

- （ lack the guide on how to do it， Most importantly, we need the approval of the decision makers… ）


 
##  Smart Endpoints and Dumb Pipes (智能端点和哑通道)

#### 收益:
1）  Choosing Communication Protocol

- （Four main factors concerned by practitioners are the maturity of the technology's ecosystem (8/13), the activity of the community (8/13),
   the supporting documents (6/13), and technology stacks with previous experience (6/13)）

- （这个收益主要指框架选择很多，基于RESTful的 Spring Cloud, 基于RPC的Apache Dubbo, 他们提供了很多组件，）

#### 痛点:
2） Complexity of API Management
- （the communications among mi-croservices is the complexity of the implementation and management of API）
 


##   Decentralized Governance （分散治理）

#### 收益:
1） Controlling Technology Diversity (控制技术多样性)
- (microservices support a mix of multiple languages, development frameworks and data-storage technologies, i.e. technology diversity
    但是从业者不会鼓励技术多样性，这会带来问题，如版本控制等)

 #### 痛点:
 2） Excessive Technology Diversity

- （The diversity of technology stacks also raises the requirements on developers' ability and increases the complexity of the learning and construction.）


## Decentralized Data Management （分散数据管理）

#### 收益:
 1） Compromise with Database Decomposition
> (由于以下原因未考虑分解数据库：)
- （Memory database in use）
- （Databases partitioned in legacy systems.）
- （Benefit analysis of decomposition）

#### 痛点:

 2）Data Inconsistence
- （practitioners are usually pained with the complexity of addressing the distributed transactions while ensuring the data consistency.）
- （messaging-based or event-based, the design and implementation are very complicated）
- （The real process of addressing the data consistency is far more complicated than the description）



## Infrastructure Automation （基础设施自动化）

#### 收益:
1） CI&CD
- (applying infrastructure automation technology)
- （service mesh technology to facilitate the upgrade and the version management of microservices. 通过Service Mesh 方便升级和管理）


#### 痛点:
2） Inadequate Automation
- （many existing infrastructure-related technical frameworks are unsatisfying to meet their requirements. 许多基础设施不能满足现有的需求)


## Design for Failure 


#### 收益:

1） Monitoring and Logging
- （Monitoring Metrics）
- （Monitoring Strategies）

#### 痛点:

2) Unsatisfying Monitoring and Logging
- (Insufficiency of Automated Operation)
-  (Difficulty in Troubleshooting)
- (Difficulty in Threshold Setting)
-  (No Well-Rounded Monitoring System)


## Evolutionary Design (进化设计)

#### 收益:
1） Stepwise Evolution

#### 痛点:
2）  Missing of an Effective Decomposition Guide （缺少有效的分解指南）
- （DDD is a relatively abstract thing to us, without a specific process. Since different people had different consensus of views about it）








# 论文题目：Microservices Maturity Model 

#### 收益：
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
（企业采用微服务架构的主要驱动力）
11. Enterprise primary business revolves around extremely high volume transactions 
12. Rapid development and enhanced operational support, reduce implementation and release cycle time and enables continuous delivery 
13. Enterprises migrating from Monolithic and Legacy Processes to Microservices 
14. Scalability and flexibility of Cloud service help in handling more customers simultaneously without interrupting service 
15. For the solutions that require the integration of business capability from disparate systems and programming models 
16. For aligning business and IT functionality 
17. For business and technology agility 
18. Better ROI 
19. For incremental development (Agile) and continuous deployment of business software 



#### 痛点:
1. Miss knowledge and lack of qualified people.


# 论文题目：GLOBAL MICROSERVICES TRENDS A SURVEY OF DEVELOPMENT PROFESSIONALS 


#### 收益：
1. By breaking applications down into lightweight and decoupled services that each serve a specific business need, development teams could deploy more frequently, scale more effectively, and avoid many of the problems of software monoliths.
2. Agility (82%) and scalability (78%) are the top motivators for microservices adoption 



#### 痛点：
1. 56% say each additional microservice increases operational challenges 
2. 73% find troubleshooting is harder in a microservices environment 
3. 98% of those that face issues identifying the root cause of issues in microservices environments report it has a direct business impact 
4. 87% of those in production report microservices generate more application data 



# 论文题目：Migrating towards Microservice Architectures: an Industrial Survey 

####  收益：
1. agility
2. scalability
3. have flexible and evolvable architectures 
4. Resolving existing issues(Typical issues of legacy systems are technical (e.g., the system becomes highly coupled, hard to maintain, presents side effects) or business-related (e.g., long time to release new features, low productivity of developers)).
5. Improving the system maintainability and the frequency of product releases.

#### 痛点：
1. infrastructure automation 
2. distributed debugging
3. Creation of cross-functional teams



# 论文题目： Supporting Microservice Evolution


#### 收益：
1. scale-out application
2.  loose coupling
3. agile and rapid evolution


#### 痛点：
1. Checking for upgrade consistency  

 （developers manually identify micro service dependencies and either engage with other developers who own that
 micro service or evaluate the dependency through code inspection）
 
2. Identifying architectural improvements  (架构的确定困难)

   （An evolving μApp will experience software architectural corrosion, such as a decrease in cohesion and increase in coupling between related services. ）
   
   
3. Evaluating changing deployment trade-offs

   （Today developers evaluate changing deployment trade-offs through trial and error without a systematic strategy nor much tool support.）
   
   
   
#  论文题目： Microservices The Journey So Far and Challenges Ahead

#### 收益：
1. faster  delivery
2. scalability
3. greater autonomy


#### 痛点：
1. Service Modularization and Refactoring

   （With any approach to modularization, finding the right modules, with the right size, 
   the right assignment of responsibilities, and well-designed interfaces, is a challenge. ）
   
   
2. Service Granuiarity

   （Another issue is the lack of agreement on the right size of microservices. Although the name 
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
   On the other hand, it increases the risk of teams failing to see the big picture—that is,
   to understand whether their local decisions are justifiable and coherent in the context
   of the system's overall architecture and business goals.)
   

# 收益统计
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
- Increased traceability （企业采用微服务架构的主要驱动力）
- Improving the system maintainability and the frequency of product releases.


# 痛点统计
- miss knowledge and lack of qualified people.   
- increases operational challenges
- troubleshooting is harder （distributed debugging, decrease the testability ,  joint debugging among different versions） 
- microservices generate more application data
- creation of cross-functional teams ， Organization Culture and Coordination ( lack the guide on how to do it) 
- lack infrastructure automation （Inadequate Automation）
- checking for upgrade consistency
- identifying architectural improvements （Service Modularization and Refactoring, Missing of an Effective Decomposition Guide）
- evaluating changing deployment trade-offs
- resource Monitoring and Management  （unsatisfying Monitoring and Logging）
- failure recovery, and Self-Repair
- chaotic Independence (when the mi-croservices are over fine-grained)
- complexity of API Management 
- excessive Technology Diversity (increases the complexity of the learning and construction)
- data Inconsistence （implementation are very complicated）
  
