

# 论文： Microservices and Their Design Trade-Offs: A Self-Adaptive Roadmap
           （微服务及其设计权衡：自适应路线图）

## 摘要
- the state of the art still lacks consensus on the definition of microservices, their properties and their modelling techniques. 
  
  （现有的技术仍然缺乏对微服务的定义，性质，以及建模技术的共识）
  
- One of the motivations of this paper is to bridge this gap by digesting the various informal views from industry on defining microservices to aid in understanding the design problems faced by software architects when migrating to microservices.
  
  （本文的动机就是消化业界关于定义微服务的各种非正式观点来弥合这一差距，以帮助理解软件架构师在迁移到微服务时所面临的设计问题）
  
-  This paper summarises views of microservices from informal literature to reflect on the foundational context of this paradigm shift.
  
  (本文总结了非正式文献中对微服务的观点，来反映转换到微服务的基础背景, 这些背景帮助架构师解决其设计问题)

-  Related design trade-offs include: 

    （由设计问题，引出了下面两个设计权衡）
	
   1. balancing the size and number of microservices in an architecture 

   （平衡架构中微服务的大小和数量）
	  
   2. balancing the nonfunctional requirement satisfaction levels of the individual microservices as well as their satisfaction for the overall system. 

    (平衡各个微服务的非功能需求满意度以及对整个系统的满意度）

- We propose how self-adaptivity can assist in addressing these design trade-offs and discuss some of the challenges such a selfadaptive solution. 

    (我们提出自适应是如何解决这些设计权衡的，并讨论了一些自适应解决方案所面临的挑战)
	
	  
####  RQ

Among the crucial and non-trivial decision problems (DPs) that constitute addressing the
 size/number and the local/global NFRs satisfaction trade-offs are the following:
 
 (在解决微服务规模/数量， 以及各个微服务的非功能性满意度以及对整体系统的满意度权衡的关键决策问题有以下几点：)
 

> （关键决策问题DP：）

- DP 1: A solution which manages these trade-offs has to determine (given the current environment scenario and the stakeholders' definition of “optimality” regarding the trade-offs of concern):
        （管理这些权衡的解决方案，必须确定）
    
	（1） When does decomposing amicroservice into more fine-grained ones achieve the required optimality for both trade-offs?
	      （什么时候将微服务分解成更细粒度的产品才能实现两种权衡所需的最优化？）
     
	（2) When does merging several fine-grained microservices into a coarse-grained one achieve the required optimality for both trade-offs?
	       (什么时候将几个细粒度的微服务合并成粗粒度的微服务，实现两种权衡所需的最优化)
		   
    (3)  When should the current level of granularity be kept without further merging or decomposition?
	      (应该何时保持当前的粒度级别而不进一步合并或分解？)
		  
-  DP 2: The chosen architecture still has to guarantee the functional requirements ofthe system, regardless the level of 
          granularity of the microservices in that architecture.
		  (无论体系结构中微服务的粒度级别如何，所选择的体系结构仍然必须保证系统的功能要求)
	
-   DP3: Much of the uncertainties that relate to the choice of the optimal architecture and the knowledge that relates to the 
           expected behaviour of the system, can not be fully captured at design time.
		 (最优架构的选择和系统预期行为相关的知识在设计的时候是无法完全捕获的，需要运行时支持以不断更新设计时的知识)



####  method
  We propose a solution based on the MAPE-K loop to render a systematic solution that improves over the system lifetime through accumulating knowledge.
  (我们提出了一种基于MAPE-K 的环路的解决方案，通过积累知识来改善系统的寿命)
 
   proposes and discusses the suitability of techniques in the literature to each phase of the MAPE-K loop.
   （提出并讨论了文献中的技术对MAPE-K 循环的每个阶段的适用性）
   
> MAPE-K 循环的每个阶段:
   
- Input to Mape-k Loop
  （输入架构建模知识）
  
- Monitoring
   （监视系统运行时相关的变量， 如客户端请求率 和 系统响应时间）

-  Analysis
   (分析监测变量的值，转化为对当前系统的感知)

-  Planning
  （由分析的结果，采取触发（和计划）适应的决定）

-  Execution
  （将精细的抽象体系结构映射到具体的服务）

- Knowledge
   （捕获系统运行时的动态不确定性，以更新获得的知识）


#### conclusion， 

   Our contribution has reflected on the informal literature about microservices, their properties and their modelling techniques. 
   We have then formulated the problem of finding the optimal level of granularity during microservitization.
   （我们的贡献是反映了非正式文献中关于微服务的属性 和建模技术， 以及我们制定的在微服务化期间找到最佳粒度水平的问题）


####  contributions

1. We review and reflect on the definition, properties, and modelling techniques of microservices as presented in informal literature
   (回顾并反思了非正式文献中提出的微服务的定义，属性和 建模技术)

2. we formulate the problem of addressing the design trade-offs and introduce our solution proposal.
   (提出了解决设计权衡问题并介绍了我们的解决方案 )
   