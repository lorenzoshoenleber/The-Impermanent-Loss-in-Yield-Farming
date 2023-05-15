# The-Impermanent-Loss-in-Yield-Farming
Academic Project, The Impermanent Loss (IL) in Yield Farming; Continuous-time Stochastic Model, Hedging of the IL via tokens and derivatives

Motivation 

Yield farming is the practice of seeking rewards in the form of transaction fees by depositing tokens into a liquidity pool on a decentralized application (dApp). In contrast to traditional finance, yield farming is different from traditional liquidity provision because it occurs in the absence of a central market maker (intermediary). If a trader (the liquidity taker) enters the liquidity pool, he can buy and sell tokens by swapping them in the pool according to a known pricing rule governed by the Automated Market Maker (AMM). In exchange for providing liquidity, the yield farmer (liquidity provider) earns a share of the trading fees from the trades that occur in the liquidity pool. Liquidity is of critical importance to the stability and efficiency of financial markets. In yield farming, tokens are lent (to a protocol), and, most likely, the protocol will not return the same quantities of individual tokens to the lender, due to the so-called impermanent loss. 

Impermanent loss defines the opportunity-cost dynamic between offering assets for exchange and holding the underlying assets to potentially profit from the price movement. This occurs when the price of the deposited assets changes compared to when one deposited them. The bigger this change is, the more one is exposed to impermanent loss. It is important to mention that an impermanent loss does not necessarily mean that the LP experiences a negative return on the investment: It simply means that the gains from a buy-and-hold strategy outperformed the returns obtained for the liquidity provision.

Contribution

The academic literature on impermanent loss as the major risk driver in DeFi is not developed yet and especially little is known about how to hedge or minimize the impermanent loss for investors.

The main contributions we plan to achieve in this project are as follows:

i)	To shed light on the concrete mechanism of impermanent loss, we propose a continuous-time stochastic model which we calibrate to the data and then use to characterize the impermanent loss dynamics in the liquidity pool. The construction of our model starts with the mathematical formulation of the AMM governing prices in the liquidity pool. We then fully derive and characterize the impermanent loss as the major source of risk for the agent who has invested in the pool. For a single pool with a single pair of tokens, the first calculations show that the impermanent loss is a function of the respective token return volatilities and the correlation between them.

ii)	We then study the replication (hedging) of the impermanent loss: Therefore, we solve a portfolio problem using stochastic control theory with the goal to minimize the (one-step ahead) impermanent loss occurring to the yield farmer. The optimal portfolio strategy will then command the optimal holdings in either the underlying token pair (outside the pool) or derivatives (call or put options) written on the respective token individually. 
 
Benefits for your Foundation and Ecosystem

The stability and efficiency of financial markets heavily rely on the crucial significance of liquidity. You would sponsor a high-level academic research paper in DeFi and hence gain visibility among the academic community. Our current paper “Maneuvering and Investing in Yield Farms” (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4422213) got presented already at various conferences. Besides the visibility, the results which we provide in our paper can be useful for the enhancement and development of the current architecture of your dApp. For example, via a simulation study, one could provide corridors for the expected impermanent loss. Besides, the paper would guide and educate the investor on how to avoid or hedge impermanent loss. 

In addition, we just held a one-day conference by the Collegio Carlo Alberto and the University of Turin, called ToDeFi: Torino Decentralized Finance Conference 2023 (https://www.carloalberto.org/event/todefi-torino-decentralized-finance-conference/), which promoted the highest level and up-to-date research in DeFi within the academic community. Speakers and discussants were selected among the most innovative junior researchers and established scholars. We are planning to make the conference a yearly event. Beyond the research support, we are potentially open to discuss about a deeper cooperation. In particular, the Collegio Carlo Alberto hosts a postgraduate Master’s in finance, insurance, and risk management (Mafirm), which is a small high-quality program that exists for more than 20 years. The program appears in several international rankings (e.g., 1st in Italy, 6th in Europe, and 25th worldwide in the quantitative finance masters' ranking by Risk.net). The students attending our master lectures are excellent but more importantly, really motivated.

Funding Requirement: Data and Research Assistant

In order to implement our optimization framework, we have to model the underlying relevant stochastic processes: While current spot prices are publicly available, dedicated firms such as https://tardis.dev offer access to various cryptocurrency derivative trading platforms, which we need to acquire for this project. Pool data can be sourced for free via The Graph as done in our current project. On top of the data acquisition, we need to hire a Research Assistant, who helps us to access and analyze the relevant data. The optimization framework requires high-level hardware and computing capabilities which we need to acquire (or rent) for this project. The price for the Tardis API for 1 year is about 6.000€. Hiring a Research Assistant for about 1.5 years accumulates to approximately 8000€. Hardware can be acquired for less than 2000€. 

We want to emphasize that any amount of sponsorship or donation would be beneficial for us since we are trying to request funding from different funding sources to realize this project.

 
The Team:

Prof. Dr. Lorenzo Schoenleber is an Assistant Professor in Finance at the Collegio Carlo Alberto and the University of Turin. He obtained his PhD at the Frankfurt School of Finance. He is also associated with the Fintech & Digital Finance Chair at Paris Dauphine University. His area of specialization is empirical asset pricing (option-implied information) and DeFi (Yield Farming). 

Prof. Dr. Andrew Papanicolaou is an associate professor in the Department of Mathematics at North Carolina State University (NCSU). His PhD is in applied mathematics from Brown University. His research interests are computational finance and stochastic systems for control and optimization. The applications of this work include financial data analysis and the challenges associated with these highly complex data sets. My background is in probability theory and nonlinear filtering. 

Dr. Siddharth Naik is a quantitative portfolio manager and trader with over 7 years of experience at institutional hedge funds (systematic macro and low latency, respectively) with extensive experience in trading fx, futures, and crypto instruments. He has previously published multiple papers on non-convex optimization mechanism design and trading crypto since 2017. Previously he was a CEO at RadioLytics a startup, which aimed at making spectrum tradable.

Timetable - Project Roadmap & Milestones - Expected Timeline for the Grant Completion

Dates - Project stage 

06-08/2023 – Accessing, preparing, and processing spot and option data via the Tardis API 
08-09/2023 – Accessing liquidity pool data using The Graph
09-12/2023 – Developing the mathematical optimization framework 
01-02/2024 – Programming and numerically solving the optimization framework  
02-04/2024 – Calibrating the model output to the data (tokens and options) 
04-06/2024 – First paper draft 
07-08/2024 – Submission to a Journal 

Useful Links:

https://sites.google.com/view/lorenzo-schoenleber/menu
https://math.sciences.ncsu.edu/people/apapani/
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4422213
https://www.carloalberto.org/event/todefi-torino-decentralized-finance-conference/
https://www.carloalberto.org/education/master-in-finance/
