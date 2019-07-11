

#������Ŀ�� ��ʵ�е�΢����ܹ�����ҵ̽�� ���Ͼ���ѧ�źأ�
��https://ieeexplore.ieee.org/document/8703917��


�о���9��ά�ȵ�΢����������ʹ��


##  A  Componentization Via Services ��ͨ����������������

#### ����
 1) Practice 1: Independence by Separation  
- (the benefit of componentization are the independence or the autonomy of microservices)
- (shorten the lead time of products in practice)

#### ʹ��
  2)  Chaotic Independence
- (For instance, inappropriate boundary among services may decrease the testability, especially when the mi-croservices are over fine-grained)
- (increases the complexity of joint debugging among different versions)
- (the developers may face the requests of joint debugging from different developers at the same time. Some remote microservices are not always connectable in this process, which exacerbates the pain of testing)

 > All these problems may seriously influence the speed of debugging and the efficiency of developments��


## Organized Around Business Capabilities  (Χ��ҵ��������֯)

#### ����
1)  Organizational Transformation
- ��reduces the dependency and the communication among teams, and consequently lowers the cost of management. ��

#### ʹ��
2�� Unguided Organizational Transformation
- ��organizations in this study still achieve the transformation mainly based on experience��
The mismatching between the organization structure and the architecture may cause the low 
 efficiency of internal development or the massive communication among teams.  ��������֯ת�Ϳ��ܻ����Ч�ʵ��£�

- �� lack the guide on how to do it�� Most importantly, we need the approval of the decision makers�� ��


 
##  Smart Endpoints and Dumb Pipes (���ܶ˵����ͨ��)

#### ����
1��  Choosing Communication Protocol
-��Four main factors concerned by practitioners are the maturity of the technology's ecosystem (8/13), the activity of the community (8/13),
   the supporting documents (6/13), and technology stacks with previous experience (6/13)��
-�����������Ҫָ���ѡ��ܶ࣬����RESTful�� Spring Cloud, ����RPC��Apache Dubbo, �����ṩ�˺ܶ��������

#### ʹ��
2�� Complexity of API Management
- ��the communications among mi-croservices is the complexity of the implementation and management of API��
 


##   Decentralized Governance ����ɢ����

#### ����
1�� Controlling Technology Diversity (���Ƽ���������)
- (microservices support a mix of multiple languages, development frameworks and data-storage technologies, i.e. technology diversity
    ���Ǵ�ҵ�߲���������������ԣ����������⣬��汾���Ƶ�)

 #### ʹ��
 2�� Excessive Technology Diversity
-��The diversity of technology stacks also raises the requirements on developers' ability and increases the complexity of the learning and construction.��


## Decentralized Data Management ����ɢ���ݹ���

#### ����
 1�� Compromise with Database Decomposition
     ����һ��ԭ��δ���Ƿֽ����ݿ⣺
- ��Memory database in use��
- ��Databases partitioned in legacy systems.��
- ��Benefit analysis of decomposition��

#### ʹ��

 2��Data Inconsistence
- ��practitioners are usually pained with the complexity of addressing the distributed transactions while ensuring the data consistency.��
- ��messaging-based or event-based, the design and implementation are very complicated��
- ��The real process of addressing the data consistency is far more complicated than the description��



## Infrastructure Automation ��������ʩ�Զ�����

#### ����
1�� CI&CD
- ��applying infrastructure automation technology��
- ��service mesh technology to facilitate the upgrade and the version management of microservices. ͨ��Service Mesh ���������͹���


#### ʹ��
2�� Inadequate Automation
- ��many existing infrastructure-related technical frameworks are unsatisfying to meet their requirements. ��������ʩ�����������е�����)


## Design for Failure 


#### ����

1�� Monitoring and Logging
- ��Monitoring Metrics��
- ��Monitoring Strategies��

#### ʹ��

2) Unsatisfying Monitoring and Logging
- (Insufficiency of Automated Operation)
-  (Difficulty in Troubleshooting)
- (Difficulty in Threshold Setting)
-  (No Well-Rounded Monitoring System)


## Evolutionary Design (�������)

#### ����
1�� Stepwise Evolution

#### ʹ��
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



#### ʹ��
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
2. Identifying architectural improvements  (�ܹ���ȷ������)
3. Evaluating changing deployment trade-offs


#  ������Ŀ�� Microservices The Journey So Far and Challenges Ahead

#### ���棺
1. faster  delivery
2. scalability
3. greater autonomy


#### ʹ�㣺
1. Service Modularization and Refactoring
2. Service Granuiarity
3. Front-End Integration
4. Resource Monitoring and Management
5. Failure, Recovery, and Seft-Repair
6. Organization Culture and Coordination


