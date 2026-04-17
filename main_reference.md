### International Review of Economics and Finance 93 (2024) 121–

### Available online 12 April 2024

### 1059-0560/© 2024 The Authors. Published by Elsevier Inc. This is an open access article under the CC BY license

### (http://creativecommons.org/licenses/by/4.0/).

## Contents lists available at ScienceDirect

# International Review of Economics and Finance

## journal homepage: http://www.elsevier.com/locate/iref

## Sectoral uncertainty spillovers in emerging markets: A quantile

## time–frequency connectedness approach

## Tam Hoang Nhat Danga, Faruk Ballia,d,∗, Hatice Ozer Ballia, David Gabauerb,c, Thi

## Thu Ha Nguyena

a _School of Economics and Finance, Massey University, Auckland, New Zealand_
b _Academy of Data Science in Finance, Vienna, Austria_
c _Institute of Corporate Finance, Johannes Kepler University, Linz, Austria_
d _Higher School of Economics and Business, Al-Farabi Kazakh National University, Almaty, Kazakhstan_

## A R T I C L E I N F O

_JEL classification:_
C
F
G

_Keywords:_
Quantile time–frequency connectedness
Emerging markets
Sectoral spillover
Expected uncertainty transmission
Portfolio analysis

## A B S T R A C T

### This study investigates the sectoral expected uncertainty connectedness in emerging markets

### across different frequencies and quantiles using the novel quantile time–frequency connect-

### edness approach of Chatziantoniou et al. (2022a). The employed dataset spans from January

### 1st, 2003 to October 4th, 2022, encompassing 10 key sectors. The findings reveal a robust

### and notable interconnection among these sectors, with a substantial total connectedness index

### of 91.01%. We also note that the largest proportion of the sectoral total connectedness is

### associated with long-term spillovers. Consumer Cyclicals emerges as the primary source of net

### risk transmission. Conversely, the Communications & Networking and Healthcare appear to be

### the greatest net receivers of shocks at the median level. Furthermore, we find that the degree

### of interconnectedness substantially varies over time, frequency, and quantile, and by economic

### events. In addition, we find suggestive evidence of asymmetric sectoral uncertainty connect-

### edness effects as the uncertainty spillovers are higher during turbulent market conditions than

### normal market conditions. A positive relationship between uncertainty measures and sectoral

### connectedness is also observed during periods of smooth and normal market conditions. Besides,

### we also conduct different portfolio analyses illustrating the importance of risk diversification to

### reduce investment uncertainty. This has important implications for international investors and

### policymakers in forming optimal investment portfolios reducing adverse risk spillovers.

## 1. Introduction

## Substantial fluctuations in uncertainty might lead to rapid drops and recoveries in real macroeconomic variables that drive

## the business cycle. More interestingly, it has been found that emerging economies suffer much more severe falls in investment

## and private consumption following an exogenous uncertainty shock, take significantly longer to recover, and do not experience a

## subsequent overshoot in activity compared to developed economies (Carrière-Swallow & Céspedes, 2013). Indeed, there is suggestive

## evidence that uncertainty shocks generate sudden and large declines in Thai stock prices and foreign portfolio investment before

## gradually affecting the real economy through investment and trade channels. While financial uncertainty matters most for the

## Thai economy overall, consumption demand largely responds to macroeconomic uncertainty, while economic policy and political

## uncertainty generate the most persistent effects on investment (Apaitan et al., 2022). Moreover, the increased levels of uncertainty

### ∗Corresponding author.

```
E-mail addresses: H.N.T.Dang@massey.ac.nz (T.H.N. Dang), f.balli@massey.ac.nz (F. Balli).
```
### https://doi.org/10.1016/j.iref.2024.04.

### Received 19 February 2023; Received in revised form 28 March 2024; Accepted 3 April 2024


```
Fig. 1. US economic policy uncertainty and CBOE Volatility Index (VIX).
```
## are reported to adversely affect the exchange rates of emerging economies (Abid, 2020). Interestingly, the larger the US stock

## market uncertainty, measured by VIX, the lower emerging market returns as well as the higher stock market volatilities in emerging

## economies (Sarwar & Khan, 2017). In a similar fashion, there is evidence that increased US uncertainty has a larger negative effect

## on the gross domestic product of emerging economies than on the US economic growth (Gupta et al., 2020).

## As shown in Fig. 1 , the world has recently witnessed various periods of high and prolonged uncertainty such as during the

## Global Financial Crisis of 2007–08, the European Debt Crises of 2015, the outbreak of the COVID-19 pandemic in 2020, as well

## as the beginning of the Russo–Ukrainian war period which comes with high uncertainty in the energy sector. Even prior to the

## beginning of the COVID-19 pandemic, IMF Managing Director Kristalina Georgieva said ‘‘If I had to identify a theme at the outset

## of the new decade it would be increasing uncertainty’’ (Ahir et al., 2022).

## Thus, as emerging economies suffer most severely over a prolonged period of time from uncertainty shocks, it is crucial to

## investigate the expected sectoral uncertainty transmission mechanism of emerging economies. Analyzing these interdependencies

## supports the identification of the health and growth prospects of specific segments of emerging economies independently, helping

## governments and policymakers to make informed decisions regarding economic policies and regulations that can impact the

## individual sectors and thus the overall economy by minimizing the intersectoral uncertainty spillovers in order to foster the stability

## of the financial market of emerging economies as well as to prosper economic growth. Furthermore investigating emerging market

## economies is of great relevance, given that those economies make up 49% of the global GDP and 67% of the world GDP growth

## over 2011–2021 (World Economics, 2022). Additionally, emerging economies are considered to play a significant role in supporting

## the world’s economic recovery amid the post-crisis period (Wu & Pan, 2021).

## Therefore, the aim of this study is to adequately examine the magnitude of uncertainty spillovers across different sectors

## over time, frequency, and quantile spectrum. To serve that purpose, we employ the recently developed time–frequency quantile

## connectedness approach of Chatziantoniou et al. ( 2022a).

## The main reason why we are utilizing conditional volatility spillovers to measure the expected sectoral uncertainty propagation

## mechanism of emerging economies is caused by the fact that the current level of sectoral conditional volatility represents the

## sectoral uncertainty that is expected given all available data (Bollerslev, 1986; Engle, 1982). Furthermore, this study investigates

## the two hypotheses of Engle et al. ( 1990). The first one is called the ‘‘heat wave’’ hypothesis and postulates that volatility

## occurring in a market appears to remain only in this market on the next day but will not transmit to other markets while the

## second hypothesis is called ‘‘meteor shower’’ and suggests that volatility occurring in a market appears to propagate to another

## market. Hence, by identifying strong conditional volatility spillovers from one to another sector, we find empirical support for

## the ‘‘meteor shower’’ hypothesis while the absence of conditional volatility spillovers from one to another sector would support

## the ‘‘heat wave’’ hypothesis. In addition, we cover two further hypotheses regarding ‘‘contagion’’ and ‘‘decoupling’’ hypotheses.

## While the former posits that there exists a higher level of volatility spillovers among markets over a crisis, causing the portfolio

## diversification’s benefits to become limited (Hkiri et al., 2017), the latter suggests that investors could still achieve benefits from

## portfolio diversification (Bekiros, 2014; Yarovaya & Lau, 2016) as emerging markets appear to act rather independently.

## Chatziantoniou et al. ( 2022a) combine the quantile connectedness approach with the frequency connectedness of Baruník and

## Křehlík ( 2018) to allow the time-domain connectedness measures to be decomposed in different frequencies, which might help

## identify the heterogeneity of the transmission mechanism across various frequencies and quantiles (Vo & Dang, 2023). Up to now,

## an increasing number of studies have employed the time–frequency connectedness method thanks to its advantages (see Jiang &

## Chen, 2022; Suleman et al., 2023; Umar et al., 2022 among the others). Indeed, by analyzing the degree of connectedness across

## time, we will see how different market periods including recent economic and financial crises have changed the strength and

## magnitude of uncertainty spillovers while the frequency dimension allows us to investigate whether uncertainty spillovers have


## more pronounced short or long-term effects on emerging markets. Finally, the quantile spectrum allows us to differentiate the

## sectoral market connectedness during times of low uncertainty (at lower quantiles) and during times of high uncertainty (at higher

## quantiles), illustrating smooth and turbulent market conditions.

## Recent studies show evidence of significant effects of economic policy uncertainty (EPU) on sectoral connectedness in some

## emerging markets, including China (Su & Liu, 2021a) and Vietnam (Dang et al., 2023). As such, in this study, we aim to revisit this

## relationship, using different uncertainty indices (i.e., the CBOE Volatility Index, the US Economic Policy Uncertainty Index, and the

## Equity Market-related Economic Uncertainty Index), which are also employed in other empirical studies on uncertainties (Al-Yahyaee

## et al., 2019; Bouri et al., 2017; Dai et al., 2021).

## Finally, we create bivariate hedging portfolios (Kroner & Sultan, 1993) as well as multivariate minimum-risk portfolios (Markowitz,

## 1952) in order to see whether hedging one sector with another sector or investing in a multitude of sectors significantly reduces

## investment uncertainty. This analysis shows that governments of emerging economies might be able to induce economic stability

## by adequately investing in different economic sectors.

## Thus, the contribution of our study is threefold. First, to the best of our knowledge, no previous studies have investigated expected

## sectoral uncertainty spillovers in emerging markets, especially by utilizing aggregated sectoral emerging market indices in order to

## highlight the degree of expected sectoral emerging market interdependencies and sectoral interconnectedness. Second, we are the

## first who provide empirical evidence regarding the expected uncertainty spillovers of emerging economies. Third, we expand the

## scarce literature on sectoral financial market research, especially for emerging economies. As such, this study fills those research gaps

## by means of the recently-developed quantile time–frequency connectedness approach of Chatziantoniou et al. (2022a) examining the

## expected uncertainty transmission mechanism of emerging markets sectors over the period from January 1st, 2003 until October,

## 4th 2022.

## We find strong evidence that sectoral market interconnectedness is time-varying and heavily impacted by economic and financial

## crises. Interestingly, the largest fraction of sectoral uncertainty connectedness is caused by more volatile long-term dynamics while

## short-term dynamics appear to be more persistent. Furthermore, we find that the degree of sectoral market uncertainty is larger at the

## upper tail of the quantile spectrum which implies that high expected uncertainty is causing substantial market interdependencies

## and thus co-movements, while we find that sectors of emerging economies behave more independently during periods of lower

## levels of uncertainty. This indicates suggestive evidence of asymmetric sectoral uncertainty connectedness effects. Additionally, a

## positive relationship between uncertainty indices and the sectoral total connectedness is identified during times of low uncertainty

## and normal market conditions. Last, we suggest different portfolio analyses that appear to help international investors reduce their

## investment risk significantly when developing their investment portfolios.

## Our paper is organized as follows. Section 2 presents the existing literature review on the topic. Section 3 discusses the

## methodology and Section 4 presents the data sampling. Our empirical results are reported and discussed in Section 5. Finally,

## Section 6 presents our concluding remarks.

## 2. Literaturereview

## Already numerous studies have investigated the transmission mechanisms of different financial markets or financial assets.

## Especially when it comes to developing economies, we find ample evidence that the connectedness among financial markets

## tends to increase international risk sharing (Chen et al., 2014; Labidi et al., 2018; Mobarek et al., 2016) and that the network

## interconnectedness is often economic event dependent (Baruník et al., 2016; Bouri et al., 2021; Chatziantoniou et al., 2021a).

## Several researchers examine the implications of stronger connectedness across global financial markets with a focus on market

## returns, volatility, or cross-country correlations (Badshah et al., 2018; Bekaert et al., 2005; Carrieri et al., 2007; Hedström et al.,

## 2020; Moneta & Rüffer, 2009; Stenfors et al., 2022). Spillovers across markets are found to decrease the probability of mitigating

## risks via portfolio diversification (Hedström et al., 2020). Other studies extensively concentrate on the transmission mechanisms

## between stock markets and international assets (among the many, see Antonakakis et al., 2017; Fassas & Siriopoulos, 2019; Jung &

## Maderitsch, 2014; Shahzad et al., 2018).

## However, recently there has been increasing interest in investigating the financial transmission mechanism between emerging

## economies (Eterovic et al., 2022; Gabauer et al., 2022; Huidrom et al., 2020; Urom et al., 2022) or between emerging and developed

## economies (Ahmed et al., 2017; Diebold & Yilmaz, 2009; Mensi, Shafiullah et al., 2021). While all aforementioned studies focus

## on emerging and developed market spillovers, the literature on sectoral stock market spillovers is rather limited. Furthermore, the

## majority of those studies focus on developed markets, especially on the US (Baruník et al., 2016; Laborda & Olmo, 2021; Lastrapes &

## Wiesen, 2021; Malik, 2022; Mensi, Al Rababa’a et al., 2022), EU (Arouri et al., 2011; Balli et al., 2013), Australia (Balli et al., 2020,

## 2016), and New Zealand Balli et al. (2020). Investigating the return and volatility spillover effects between the S&P 500 stock sectors

## and natural gas prices under the spillover framework proposed by Diebold and Yılmaz (2012) and the frequency connectedness

## approach developed by Baruník and Křehlík (2018), Geng et al. (2020) note that the most return spillovers occur in the short

## term (up to 12 weeks). Meanwhile, Mensi, Nekhili et al. (2021) adopt Diebold and Yılmaz (2014)’s approach and Baruník et al.

## (2017)’s realized semivariances to investigate the sectoral dynamic asymmetric spillovers in the US. They show evidence that the

## time-varying connectedness across US stock sectors appears intensified over the periods of geopolitical, energy-related, and economic

## events and that there exists asymmetry in the spillovers under good versus bad volatility. Balli et al. (2021) find that the crises tend

## to intensify the spillover effects amongst the markets and that the spillovers reach their peaks over the Global Financial Crisis

## (2008–2009) and the European sovereign debt crisis (2010–2012). Additionally, shocks from economic events appear to amplify

## the level of transmission across sectoral markets and hence, negatively affect the benefits of investment diversification. Costa et al.


## (2022) analyze the volatility spillover effects among 11 sector indices in the US during the COVID-19 pandemic and find that there

## is an extraordinary increase in total spillovers from the early stages of the coronavirus pandemic until July 2020. However, the

## authors find little evidence of the structural changes from the perspective of total net connectedness. Pham et al. (2023) examine

## the relationship between the utility sector and natural gas in the US, using the quantile connectedness approach. The authors find

## that the return spillover effects appear time-varying and stronger at the extremes (i.e., at the lowest and highest quantiles) than at

## the middle quantiles.

## The scarce literature on sectoral emerging markets spillover covers China (Akhtaruzzaman et al., 2021; Gao et al., 2023; Shahzad

## et al., 2021; Shen et al., 2021; Su & Liu, 2021b; Yin et al., 2020), India Chatziantoniou, Gabauer et al. (2022), Vietnam (Mensi, Ziadat

## et al., 2022), and African developing countries (Akhtaruzzaman et al., 2022). In the case of China, based on price fluctuations and

## internet sentiment, Gao et al. (2023) examine the risk connectedness across sectors in the Chinese stock market after the COVID-

## outbreak. Under the time-varying parameter vector autoregressive (TVP-VAR) approach, the authors find that after the pandemic

## outbreak, the sectoral risk transmission within the Chinese stock market is amplified, implying the increased instability in the

## system. Additionally, the risk connectedness tends to vary with various market conditions and becomes significantly intensified

## under extreme market circumstances. Using 1-min data of sector index series in China, Shahzad et al. (2021) study the asymmetric

## volatility connectedness across Chinese stock sectors over the Covid-19 pandemic period. Their findings show that the sectoral

## spillover effects are time-varying and significantly asymmetric during the COVID-19 pandemic. The authors also emphasize that

## the bad volatility connectedness tends to dominate the good volatility spillover. Focusing on the periods of extreme risk events

## (including the Chinese stock market crash, the trade war between China and the US, and the Chinese liquidity crisis), Shen et al.

## (2021) investigate the transmission channel among Chinese economic sectors and show that the sectoral spillover effects appear

## significantly higher during the aforementioned extreme risk periods. They also observe that the financial sectors have a buffer role

## in the stabilization of the economic system. Focusing on the Covid-19 period, Akhtaruzzaman et al. (2021) investigate the financial

## contagion between China and G7 countries and find that the dynamic conditional correlations became dramatically higher during the

## pandemic. Furthermore, they note that financial sectors tend to play a more significant role in the transmission of financial contagion

## than non-financial sectors. In the context of India, Chatziantoniou, Gabauer et al. (2022) investigate the interconnectedness of 12

## Indian sectorals using the TVP-VAR-based connectedness approach of Antonakakis et al. (2020). They find that the dynamic total

## connectedness has been heterogeneous over time and economic-event dependent. Moreover, connectedness was strongest during

## the Great Financial Crisis of 2008, the double-digit inflation and stock market crash of 2011, the national election of 2014, and the

## demonetization of 2016. Among sectors, consumers’ spending, industry, finance, and basic materials are net transmitters of shocks,

## while information technology, fast-moving consumer goods, health care, and telecommunications are net receivers of shocks. It

## is argued that their findings are helpful in formulating policies that alleviate sectoral imbalances, promote balanced growth, and

## are useful for pursuing optimal portfolio diversification strategies. Meanwhile, with respect to Vietnam, Mensi, Ziadat et al. (2022)

## adopt the extreme quantile connectedness approach proposed by Chatziantoniou et al. (2021b) to investigate the spillover effects

## between crude oil futures and 10 stock market sectors in Vietnam. The authors find that the connectedness is stronger under bearish

## circumstances than bullish circumstances and that the risk spillovers significantly increase over turbulent periods such as the Global

## Financial Crisis, the European debt crisis, Brexit, the oil crisis, and the COVID-19 pandemic. In the context of African developing

## economies, Akhtaruzzaman et al. (2022) examine the financial risk transmission from the US to developing countries in Africa over

## the coronavirus period. The authors show that South Africa, Morocco, Nigeria, and Egypt play as net risk receivers whereas the US

## acts as the net exporter of financial risk. Additionally, the study indicates that the downside risk exposures of banks and financial

## firms became significantly higher over the period January–April 2020.

## Previous studies indicate that the connectedness across sectors varies over time and strongly responds to various political and

## financial events (Chatziantoniou, Gabauer et al., 2022; Shen et al., 2021; Yin et al., 2020). Indeed, when a shock occurs in a

## sector, it tends to propagate to other sectors and even to the whole financial markets due to sectoral connectedness (Zhang et al.,

## 2020). In more detail, Eckernkemper (2018) emphasizes that sectors play a significant role in systemic risk and that the volatility

## contributions tend to change across different equity sectors. The volatility of a sector tends to spill over to another, which eventually

## might impact the volatility of the whole network (Shahzad et al., 2021). Such spillovers could affect policymakers’ decisions and

## investors’ returns. Mensi, Al Rababa’a et al. (2021) note that different sectors tend to possess relatively different characteristics.

## Indeed, Mensi, Al Rababa’a et al. (2022) claim that neglecting the sectoral cross-section differences might lead to negative outcomes

## in terms of portfolio diversification. For instance, market participants might have an assumption that one critical event would exert

## the same impact on different sectors in the system. Accordingly, they would probably encounter more losses as they did not pay

## more attention to the sectors that received higher negative impacts from the shocks. This assumption appears to hold true during

## the COVID-19 pandemic when some sectors were more significantly affected by the pandemic outbreak than others (Alomari et al.,

## 2022). As such, Adekoya et al. (2022) argue that sectoral analysis appears much more significant than the analyses at the regional

## or national level in the age of globalization.

## According to Gao et al. (2023), given the simplicity of information sharing and the diversified investment strategies, the sectoral

## interconnectedness of financial markets appears to have an important role in risk transmission as risk spillovers among sectors and

## markets might be generated due to stock price fluctuations and investors’ sentiment. As such, exploring the source and the magnitude

## of uncertainty spillovers is crucial as it helps uncover the sectoral uncertainty contributions and the network of spillovers across

## sectors (Shahzad et al., 2021). From the perspective of volatility transmission, examining the connectedness of various stock markets’

## sectors appears vital for mitigating financial risks (Gao et al., 2023). Moreover, investigating the sectoral spillover mechanisms

## appears significant for governments to design appropriate policy measures that can deal with market failures as well as for a

## majority of investors and asset managers to design their investment strategies which might reduce risk exposure (Costa et al., 2022;


## Wu et al., 2019). Indeed, Mensi, Yousaf et al. (2022) suggest that sectoral analysis might be helpful for investors to design more

## efficient hedging strategies using various equity sectors instead of the aggregate stock market indices. Also, Phylaktis and Xia (2009)

## claim that sectors might provide additional benefits for portfolio diversification over periods of turbulent market conditions and

## financial contagion. Sector-based investment portfolios might help investors manage their risks as strategies regarding sector-based

## investments tend to exhibit independent movements (Elyasiani et al., 2011).

## Given that there are no previous studies examining the sectoral uncertainty connectedness utilizing aggregated sectoral emerging

## market indices, this study aims to fill this research gap by investigating the expected uncertainty spillovers across sectoral emerging

## markets.

## 3. Methodology

## 3.1. GJR-DCC-GARCH model

## In order to obtain expected sectoral uncertainty measures, we estimate a DCC-GARCH model (Engle, 2002) with univariate

## GJR-GARCH processes. The GJR-GARCH model of Glosten et al. (1993) is chosen as it captures asymmetric conditional volatility

## effects which are frequently found in the financial literature and which would be omitted by using standard GARCH (Bollerslev,

## 1986) models.

## In the spirit of Engle (2002), we can outline the dynamic conditional correlations generalized autoregressive conditional

## heteroscedasticity (DCC-GARCH) model for 𝐾 × 1dimensional return series, 𝒙 𝑡 (see Section 4) as follows:

## 𝒙 𝑡 | 𝜴 𝑡 −1∼ 𝑁 ( 𝟎 , 𝑯 𝑡 ) , 𝒛 𝑡 | 𝜴 𝑡 −1∼ 𝑁 ( 𝟎 , 𝑰 )

## 𝒙 𝑡 = 𝑫 𝑡 𝒛 𝑡, 𝑫 𝑡 = 𝑑𝑖𝑎𝑔 { ℎ 1∕2 1 𝑡, ... ,ℎ 1∕2 𝐾𝑡 }

## 𝑯 𝑡 = 𝑫 𝑡 𝑹 𝑡 𝑫 𝑡, 𝑹 𝑡 = 𝑑𝑖𝑎𝑔 ( 𝑸 𝑡 )−1 𝑸 𝑡𝑑𝑖𝑎𝑔 ( 𝑸 𝑡 )−1 , 𝑸 𝑡 = (1 − 𝑎 − 𝑏 ) 𝜉 + 𝑎 𝒛 𝑡 𝒛 ′ 𝑡 −1+ 𝑏 𝑸 𝑡 −

## where 𝒛 𝑡 , 𝜉 , 𝑯 𝑡 , and 𝑹 𝑡 are standardized residuals, the unconditional correlation matrix of standardized residuals, the conditional

## covariance matrix and the conditional correlation matrix, respectively.

## In a two-step estimation procedure, Engle (2002) demonstrates that estimating the DCC-GARCH model does not result in biased

## estimates. Initially, 𝐾 univariate GARCH models are estimated to derive 𝑫 𝑡. Then, the parameters ( 𝑎 and 𝑏 ) of the DCC-GARCH

## model are estimated to obtain 𝑹 𝑡 and subsequently 𝑯 𝑡. The log-likelihood function can be expressed as the combined sum of the

## volatility and correlation components:

## 𝐿 ( 𝜃,𝜙 ) = 𝐿𝑉 ( 𝜃 ) + 𝐿𝐶 ( 𝜃,𝜙 ) (1)

## 𝐿𝑉 ( 𝜃 ) = −^12

## ∑

#### 𝑡

## ∑ 𝑘

#### 𝑖 =

## 𝑙𝑜𝑔 (2 𝜋 ) + 𝑙𝑜𝑔 ( ℎ𝑖,𝑡 +

#### 𝑥^2 𝑖,𝑡

## ℎ𝑖,𝑡 ) (2)

## 𝐿𝐶 ( 𝜃,𝜙 ) = −^12

## ∑

#### 𝑡

## ( 𝑙𝑜𝑔 | 𝑹 𝑡 |+ 𝒙 ′ 𝑡 𝑹 −1 𝑡 𝒙 𝑡 − 𝒙 ′ 𝑡 𝒙 𝑡 ) (3)

## where 𝐿𝑉 ( 𝜃 )and 𝐿𝐶 ( 𝜃,𝜙 )stand for the volatility and correlation component of the log-likelihood function, respectively.

## In the first step, the parameter 𝜃 represents the estimated univariate GJR-GARCH parameters, while the parameter 𝜙 represents

## the DCC-GARCH parameter in the second step. The GJR-GARCH(1,1)^1 model of Glosten et al. (1993) can be outlined as follows,

## ℎ𝑡 = 𝜁 + 𝛼 1 𝜖^2 𝑡 −1+ 𝛾 1 𝜖^2 𝑡 −1 𝐼𝑡 −1+ 𝛽 1 ℎ𝑡 −1 (4)

## where 𝜁 , 𝛼 1 , and 𝛽 1 are the unconditional variance, the shock, and the persistence parameter, respectively, while 𝐼𝑡 −1is an indicator

## variable which is equal to unity if 𝜖𝑡 −1 < 0 and zero vice versa.

## 3.2. Quantile time–frequency connectedness approach

## In the next step, we estimate the uncertainty transmission mechanism of emerging markets by means of the quantile-frequency

## connectedness approach of Chatziantoniou et al. (2022a). For this purpose, the following quantile vector autoregressive model,

## QVAR(p), is estimated,

## 𝒉 𝑡 = 𝝁 𝑡 ( 𝜏 ) + 𝜱 1 ( 𝜏 ) 𝒉 𝑡 −1+ 𝜱 2 ( 𝜏 ) 𝒉 𝑡 −2+⋯+ 𝜱 𝑝 ( 𝜏 ) 𝒉 𝑡 − 𝑝 + 𝝂 𝑡 ( 𝜏 ) (5)

## where 𝒉 𝑡 and 𝒉 𝑡 − 𝑖 , 𝑖 = 1 , ... ,𝑝 represent 𝐾 ×1dimensional conditional volatility vectors, 𝜏 is between[0 , 1]and represents the quantile

## of interest, 𝑝 stands for the lag length of the QVAR model, 𝝁 ( 𝜏 )is an 𝐾 × 1dimensional conditional mean vector, 𝜱 𝑗 ( 𝜏 )is an 𝐾 × 𝐾

## dimensional QVAR coefficient matrix, and 𝝂 𝑡 ( 𝜏 )demonstrates the 𝐾 × 1dimensional error vector which has an 𝐾 × 𝐾 dimensional

## error variance–covariance matrix, 𝜮 ( 𝜏 ). To transform the QVAR(p) to its quantile vector moving average representation, QVMA(∞),

## we use Wold’s theorem: 𝒉 𝑡 = 𝝁 ( 𝜏 ) +

## ∑ 𝑝

## 𝑗 =1 𝜱 𝑗 ( 𝜏 ) 𝒉 𝑡 − 𝑗 + 𝝂 𝑡 ( 𝜏 ) = 𝝁 ( 𝜏 ) +

## ∑∞

## 𝑖 =0 𝜳 𝑖 ( 𝜏 ) 𝝂 𝑡 − 𝑖.

(^1) We use a GJR-GARCH(1,1) model as Hansen and Lunde (2005) have shown that estimating GARCH models with one shock and one persistence parameter
is sufficient.


## Subsequently, the 𝑀 -step ahead generalized forecast error variance decomposition (GFEVD) (see, Koop et al., 1996; Pesaran &

## Shin, 1998) which lies at the heart of the connectedness approach is calculated.^2 The GFEVD can be interpreted as the impact a

## shock in series 𝑗 has on series 𝑖 in terms of its forecast error variance share and can be written in the following form:

## 𝜃𝑖𝑗 ( 𝑀 ) =

## ( 𝜮 ( 𝜏 ))−1 𝑗𝑗

## ∑ 𝑀

## 𝑚 =0(( 𝜳 𝑚 ( 𝜏 ) 𝜮 ( 𝜏 )) 𝑖𝑗 )

#### 2

## ∑ 𝑀

## 𝑚 =0( 𝜳 𝑚 ( 𝜏 ) 𝜮 ( 𝜏 ) 𝜳

#### ′

## 𝑚 ( 𝜏 )) 𝑖𝑖

## (6)

## 𝜃̃𝑖𝑗 ( 𝑀 ) =

## 𝜃𝑖𝑗 ( 𝑀 )

## ∑ 𝐾

## 𝑗 =1 𝜃𝑖𝑗 ( 𝑀 )

## (7)

## where 𝑀 represents the forecast horizon. As the rows of 𝜃̃𝑖𝑗 do not sum up to one, we need to normalize them by the row sum

## which results in 𝜃̃𝑖𝑗. Through the normalization, we get the following identities:

## ∑ 𝐾

#### 𝑗 =

## 𝜃̃𝑖𝑗 ( 𝑀 ) = 1and∑ 𝐾

#### 𝑗 =

## ∑ 𝐾

#### 𝑖 =

## 𝜃̃𝑖𝑗 ( 𝑀 ) = 𝐾. Hence,

## each row sum is equal to unity representing how a shock in series 𝑖 has influenced the series itself and all other series 𝑗.

## In the next step, all connectedness measures can be computed. We start with the (overall) net pairwise connectedness (NPDC)

## which is computed as follows,

## 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑀 ) = 𝜃̃𝑖𝑗 ( 𝑀 ) − 𝜃̃𝑗𝑖 ( 𝑀 ). (8)

## If 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑀 ) > 0 ( 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑀 ) < 0 ), it means that series 𝑗 influences series 𝑖 more (less) than vice versa. Hence, if 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑀 ) > 0 ,

## series 𝑗 dominates series 𝑖 and vice versa. The (overall) total directional connectedness TO others measures how much of a shock in

## series 𝑖 is transmitted to all other series 𝑗 :

## 𝑇𝑂𝑖 ( 𝑀 ) =

## ∑ 𝐾

#### 𝑖 =1 ,𝑖 ≠ 𝑗

## 𝜃̃𝑗𝑖 ( 𝑀 ) (9)

## The (overall) total directional connectedness FROM others measures how much series 𝑖 is receiving from shocks in all other series 𝑗 :

## 𝐹𝑅𝑂𝑀𝑖 ( 𝑀 ) =

## ∑ 𝐾

#### 𝑖 =1 ,𝑖 ≠ 𝑗

## 𝜃̃𝑖𝑗 ( 𝑀 ) (10)

## The (overall) NET total directional connectedness represents the difference between the (overall) total directional connectedness TO

## others and the (overall) total directional connectedness FROM others , which can be interpreted as the net influence series 𝑖 has on the

## predetermined network.

## 𝑁𝐸𝑇𝑖 ( 𝑀 ) = 𝑇𝑂𝑖 ( 𝑀 ) − 𝐹𝑅𝑂𝑀𝑖 ( 𝑀 ) (11)

## If 𝑁𝐸𝑇𝑖> 0 ( 𝑁𝐸𝑇𝑖< 0 ), series 𝑖 influences all others 𝑗 more (less) than being influenced by them. Thus, it is considered a net

## transmitter (receiver) of shocks.

## The (overall) total connectedness index (TCI) of Chatziantoniou et al. (2021a) that measures the degree of network interconnect-

## edness can be calculated by:

## 𝑇𝐶𝐼 ( 𝑀 ) = 𝐾^1 −

## ∑ 𝐾

#### 𝑖 =

## 𝑇𝑂𝑖 ( 𝑀 ) = 𝐾^1 −

## ∑ 𝐾

#### 𝑖 =

## 𝐹𝑅𝑂𝑀𝑖 ( 𝑀 ). (12)

## The higher the TCI value, the higher the market risk, and vice versa.

## So far we have focused on the connectedness assessment in the timedomain. Analogously, we continue with the connectedness

## assessment in the frequency domain. Following the spectral decomposition method of Stiassny (1996), we can explore the

## connectedness relationship in the frequency domain. First, we consider the frequency response function, 𝜳 ( 𝑒 − 𝑖𝜔 ) =

## ∑∞

## 𝑚 =0 𝑒

## − 𝑖𝜔𝑚 𝜳

## 𝑚 ,

## where 𝑖 =

## √

## −1and 𝜔 denotes the frequency to continue with the spectral density of 𝒙 𝑡 at frequency 𝜔 which can be defined as a

## Fourier transformation of the QVMA(∞) representation:

## 𝑺 𝑥 ( 𝜔 ) =

## ∑∞

#### 𝑚 =−∞

## 𝐸 ( 𝒉 𝑡 𝒉 ′ 𝑡 − 𝑚 ) 𝑒 − 𝑖𝜔𝑚 = 𝜳 ( 𝑒 − 𝑖𝜔𝑚 ) 𝜮 𝑡 𝜳 ′( 𝑒 + 𝑖𝜔𝑚 ) (13)

## Notably, the frequency GFEVD is the combination of spectral density and the GFEVD. As in the time domain, we need to normalize

## the frequency GFEVD which can be formulated as follows,

## 𝜃𝑖𝑗 ( 𝜔 ) =

## ( 𝜮 ( 𝜏 ))−1 𝑗𝑗 |

## ∑∞

## 𝑚 =0( 𝜳 ( 𝜏 )( 𝑒

## − 𝑖𝜔𝑚 ) 𝜮 ( 𝜏 ))

## 𝑖𝑗 |

#### 2

## ∑∞

## 𝑚 =0( 𝜳 ( 𝑒

## − 𝑖𝜔𝑚 ) 𝜮 ( 𝜏 ) 𝜳 ( 𝜏 )( 𝑒𝑖𝜔𝑚 )) 𝑖𝑖 (14)

## 𝜃̃𝑖𝑗 ( 𝜔 ) =

## 𝜃𝑖𝑗 ( 𝜔 )

## ∑ 𝐾

## 𝑘 =1 𝜃𝑖𝑗 ( 𝜔 )

## (15)

(^2) The GFEVD is preferred over its orthogonal counterpart as the retrieved results are completely invariant of the variable ordering. Additionally, Wiesen et al.
(2018) point out, that the GFEVD should be employed if no theoretical framework – which would allow to identify the error structure – is available.


## where 𝜃̃𝑖𝑗 ( 𝜔 )represents the portion of the spectrum of the 𝑖 th series at a given frequency 𝜔 that can be attributed to a shock in the

## 𝑗 th series. It can be interpreted as a within-frequency indicator.

## To assess short-term and long-term connectedness rather than connectedness at a single frequency, we aggregate all frequencies

## within a specific range, 𝑑 = ( 𝑓,𝑔 ): 𝑓,𝑔 ∈ (− 𝜋,𝜋 ) ,𝑓 < 𝑔 :

## 𝜃̃𝑖𝑗 ( 𝑑 ) =

## ∫

#### 𝑔

#### 𝑓

## 𝜃̃𝑖𝑗 ( 𝜔 ) 𝑑𝜔 (16)

## From here, we can calculate exactly the same connectedness measures as in Diebold and Yılmaz (2012, 2014) which can be

## interpreted identically, however, in this case, they refer to frequency connectedness measures that provide information about

## spillovers in certain frequency ranges 𝑑 :

## 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑑 ) = 𝜃̃𝑖𝑗 ( 𝑑 ) − 𝜃̃𝑗𝑖 ( 𝑑 ) (17)

## 𝑇𝑂𝑖 ( 𝑑 ) =

## ∑ 𝐾

#### 𝑖 =1 ,𝑖 ≠ 𝑗

## 𝜃̃𝑗𝑖 ( 𝑑 ) (18)

## 𝐹𝑅𝑂𝑀𝑖 ( 𝑑 ) =

## ∑ 𝐾

#### 𝑖 =1 ,𝑖 ≠ 𝑗

## 𝜃̃𝑖𝑗 ( 𝑑 ) (19)

## 𝑁𝐸𝑇𝑖 ( 𝑑 ) = 𝑇𝑂𝑖 ( 𝑑 ) − 𝐹𝑅𝑂𝑀𝑖 ( 𝑑 ) (20)

## 𝑇𝐶𝐼 ( 𝑑 ) = 𝐾^1 −

## ∑ 𝐾

#### 𝑖 =

## 𝑇𝑂𝑖 ( 𝑑 ) = 𝐾^1 −

## ∑ 𝐾

#### 𝑖 =

## 𝐹𝑅𝑂𝑀𝑖 ( 𝑑 ) (21)

## In our case, we have two frequency bands illustrating short-term and long-term dynamics ranging from 1 to 5 days, 𝑑 1 = ( 𝜋 ∕5 ,𝜋 )

## and from 6 to infinite days, 𝑑 2 = (0 ,𝜋 ∕5](see, Chatziantoniou et al., 2022a). Thus, 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑑 1 ), 𝑇𝑂𝑖 ( 𝑑 1 ), 𝐹𝑅𝑂𝑀𝑖 ( 𝑑 1 ), 𝑁𝐸𝑇𝑖 ( 𝑑 1 ), and

## 𝑇𝐶𝐼 ( 𝑑 1 )illustrate the short-term net pairwise connectedness, short-term total directional connectedness TO others, short-term total

## directional connectedness FROM others, short-term NET total directional connectedness, and short-term total connectedness index,

## while 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑑 2 ), 𝑇𝑂𝑖 ( 𝑑 2 ), 𝐹𝑅𝑂𝑀𝑖 ( 𝑑 2 ), 𝑁𝐸𝑇𝑖 ( 𝑑 2 ), and 𝑇𝐶𝐼 ( 𝑑 2 )illustrate the long-term net pairwise connectedness, long-term

## total directional connectedness TO others, long-term total directional connectedness FROM others, long-term NET total directional

## connectedness, and long-term total connectedness index, respectively.

## Finally, we show the relationship between the frequency-domain measures of Baruník and Křehlík (2018) to the Diebold and

## Yılmaz (2012, 2014) time-domain measures:

## 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑀 ) =

## ∑

#### 𝑑

## 𝑁𝑃𝐷𝐶𝑖𝑗 ( 𝑑 ) (22)

## 𝑇𝑂𝑖 ( 𝑀 ) =

## ∑

#### 𝑑

## 𝑇𝑂𝑖 ( 𝑑 ) (23)

## 𝐹𝑅𝑂𝑀𝑖 ( 𝑀 ) =

## ∑

#### 𝑑

## 𝐹𝑅𝑂𝑀𝑖 ( 𝑑 ) (24)

## 𝑁𝐸𝑇𝑖 ( 𝑀 ) =

## ∑

#### 𝑑

## 𝑁𝐸𝑇𝑖 ( 𝑑 ) (25)

## 𝑇𝐶𝐼 ( 𝑀 ) =

## ∑

#### 𝑑

## 𝑇𝐶𝐼 ( 𝑑 ) (26)

## Intuitively speaking, the overall connectedness measures are equal to the sum of the corresponding frequency connectedness

## measures. Keep in mind that all those connectedness measures are based on a specific quantile, 𝜏.

## 3.3. Hedge ratios

## In order to examine whether the investment uncertainty can be reduced by employing hedging or minimum-risk portfolios, we

## implement the bivariate hedge ratio approach proposed by Kroner and Sultan (1993) as well as the minimum variance portfolio

## of Markowitz (1952).

## Kroner and Sultan (1993) have shown that the investment risk of holding a long position in asset 𝑖 can be reduced by holding

## a short position of asset 𝑗. In this context, the hedge ratio determines the expenses associated with hedging a 1 USD long position

## in asset 𝑖 with a 𝐻𝑅𝑖𝑗,𝑡 USD short position in asset 𝑗. This can be mathematically formulated as follows

## 𝐻𝑅𝑖𝑗,𝑡 =

## 𝑯 𝑖𝑗,𝑡

## 𝑯 𝑗𝑗,𝑡

## (27)

## where 𝑯 𝑖𝑗,𝑡 and 𝑯 𝑗𝑗,𝑡 stand for the conditional covariance between asset 𝑖 and 𝑗 and the conditional variance of asset 𝑗.

## 3.4. Multivariate minimum variance portfolio

## In the pursuit of minimizing portfolio risk, we shift our focus towards the multivariate minimum variance portfolio of Markowitz

## (1952). To provide a comprehensive understanding, we begin by outlining the general framework and subsequently delve into the


## process of obtaining diverse portfolio weights. The multivariate minimum risk portfolio can be seen as a minimization optimization

## problem which can be formulated as follows,

## argmin

#### 𝒘 𝑡

## 𝒘 ′ 𝑡 𝑯 𝑡 𝒘 𝑡 s.t. 𝒘 ′ 𝑡 𝟏 = 1 , 𝟎 ≤ 𝒘 𝑡 ≤ 𝟏. (28)

## where 𝒘 𝑡 denotes the 𝐾 × 1dimensional portfolio weights vector in time 𝑡 that results from minimizing the 𝐾 × 𝐾 dimensional

## covariance matrix, 𝑯 𝑡. As 𝑯 𝑡 is varying over time, we are extending the standard Markowitz (1952) by means of time-varying

## portfolio weights.

## 3.5. Portfolio performance

## Finally, the portfolio performance is assessed based on the Sharpe ratio (Sharpe, 1994) and the hedging effectiveness (Ederington,

## 1979) which provides insight into the return-to-risk behavior of the portfolio as well as the degree of variance risk reduction

## achieved by investing in a portfolio rather than investing solely in a single asset 𝑖. The Sharpe ratio (SR) – often referred to as

## the reward-to-volatility ratio – is computed as follows,

## 𝑆𝑅 =

## 𝒙 ̄𝑝𝑓

## √

## 𝑣𝑎𝑟 ( 𝒙 𝑝𝑓 )

## (29)

## where 𝒙 ̄𝑝𝑓 and 𝑣𝑎𝑟 ( 𝒙 𝑝𝑓 )stand for the average portfolio return and the portfolio variance, respectively. The higher the SR, the higher

## the return relative to the portfolio risk.

## To determine the significance of the investment risk reduction, we utilize the HE test statistics developed by Antonakakis et al.

## (2020). The HE can be computed in the following manner,

## 𝐻𝐸𝑖 = 1 −

## 𝑣𝑎𝑟 ( 𝒙 𝑝𝑓 )

## 𝑣𝑎𝑟 ( 𝒙 𝑖 )

## (30)

## where 𝑣𝑎𝑟 ( 𝒙 𝑖 )denotes the variance of return of asset 𝑖 , and 𝐻𝐸𝑖 provides information on the percentage-wise variance reduction by

## investing in a portfolio compared to asset 𝑖. Thus, a high (low) HE index indicates a high (low) risk reduction.

## 4. Data

## The employed daily sectoral dataset has been obtained from Refinitiv EIKON and ranges from January 1st, 2003 to October

## 4th, 2022. Refinitiv EIKON develops sectoral indices for the Global Emerging Markets comprising 26 countries around the world,

## including Argentina, Bahrain, Brazil, Chile, China, Czech Republic, Egypt, Hungary, India, Indonesia, Kuwait, Malaysia, Mexico,

## Morocco, Oman, Pakistan, Philippines, Poland, Qatar, Russia, South Africa, Taiwan, Thailand, Turkey, UAE, and Vietnam. Those

## indices provide a detailed view of the performance of different the following sectors: Basic Materials (BM), Communications &

## Networking (CN), Consumer Cyclicals (CC), Consumer Non-Cyclicals (CNC), Energy (ENE), Financials (FIN), Healthcare (HC),

## Industrials (IND), Technology (TEC), and Utilities (UTI)^3. Analyzing these indices offers advantages to investors, analysts, and

## economists as they can assess the health and growth prospects of specific segments of the economy independently, helping them

## make better investment decisions. The performance of sectoral indices also acts as an indicator of the overall health of specific

## industries and the broader economy. Governments and policymakers use this data to make informed decisions regarding economic

## policies and regulations that can impact individual sectors and the overall economy.

## As the raw series are non-stationary according to a battery of unit-root tests (Dickey & Fuller, 1979; Elliott et al., 1996;

## Kwiatkowski et al., 1992; Phillips & Perron, 1988; Zivot & Andrews, 2002), all sectoral indices are transformed into their daily

## returns using first log-differences, 𝑥𝑡 = 𝑙𝑜𝑔 ( 𝑦𝑡 ) − 𝑙𝑜𝑔 ( 𝑦𝑡 −1)where 𝑦𝑡 stands for the daily closing price at time 𝑡. The daily returns and

## their conditional volatilities are illustrated in Fig. 2.

## Table 1 provides a battery of summary statistics. Interestingly, all sectoral indices are at least at the 1% significance level

## left-skewed (D’Agostino, 1970), leptokurtic (Anscombe & Glynn, 1983), and non-normally distributed (Jarque & Bera, 1980). In

## addition, we find suggestive evidence that all sectoral indices are stationary at the 1% significance level. Furthermore, the weighted

## Portmanteau test of Fisher and Gallagher (2012) reveals that all sectoral indices exhibit ARCH/GARCH errors at least at the 1%

## significance level. Finally, we find that all sectoral indices are significantly positively correlated with each other using the Kendall

## rank correlation coefficients.

## 5. Empiricalresults

## 5.1. Sectoral uncertainty connectedness in emerging markets

## 5.1.1. Median-frequency connectedness measures

## We begin the empirical results section by interpreting the averaged median connectedness measures. The diagonal values in

## Table 2 refer to the own-variance shares while the off-diagonal values demonstrate the cross-variance shares. Additionally, each

(^3) Refinitiv EIKON ticker for each sector: Basic Materials (.TRXFLDGEPUMAT), Communications & Networking (.TRXFLDGEPUCOM), Consumer Cyclicals
(.TRXFLDGEPUYCY), Consumer Non-Cyclicals (.TRXFLDGEPUNCY), Energy (.TRXFLDGEPUENE), Financials (.TRXFLDGEPUFIN), Healthcare (.TRXFLDGEPUHLC),
Industrials (.TRXFLDGEPUIND), Technology (.TRXFLDGEPUTEC), and Utilities (.TRXFLDGEPUUTL)


**Fig. 2.** Daily returns and conditional volatilities. Notes: Daily returns (blue lines) are computed by the first log-differences and the conditional volatilities (red
lines) are estimated using a GJR-DCC-GARCH model (Engle, 2002; Glosten et al., 1993). The sectors are Basic Materials (BM), Communications & Networking
(CN), Consumer Cyclicals (CC), Consumer Non-Cyclicals (CNC), Energy (ENE), Financials (FIN), Healthcare (HC), Industrials (IND), Technology (TEC) and Utilities
(UTI). (For interpretation of the references to color in this figure legend, the reader is referred to the web version of this article.)

## cell represents the impact series 𝑗 has on series 𝑖 (at the average over the total time period, short-term, and long-term periods,

## respectively). For example, we note that CN has the greatest own-variance share spillover of 24.88%. Out of the 24.88%, the short-

## term own-variance spillover is 1.88%, whereas the long-term own-variance spillover is 23%. Given that the own-variance spillover

## of CN stays at 24.88%, the rest of the sectors account for 75.12% (i.e., 100% - 24.88%) of the forecast error variance in CN. We

## find that TEC and IND have the greatest impacts on CN by 11.48% and 10.43%, respectively. Meanwhile, UTI is the sector that

## exerts the least effect on CN, by only 6.36%. Decomposing the shock into short-term and long-term spillovers, in the case of the TEC

## sector that has the largest effect on CN, we document that 0.78% originate from short-term spillovers whereas 10.70% are caused

## by long-term TEC spillovers. Generally, we note that CN affects the market by 53.93% and is affected by 75.12%, implying that this

## sector is a net receiver of risks (−21.20%). In particular, this sector is a net receiver of shock in both the short term and long term

## as its short-term net spillovers are equal to−0.27% and long-term net spillovers stay at−20.93%.

## Interestingly, CN and HC are found to be the largest net risk recipients with net spillovers of−21.20% and−10.98%, respectively.

## As such, those two sectors should be paid serious attention to because they receive the most shocks from other sectors and thus,

## appear most vulnerable in the system. The emergence of those sectors as net absorbers of shocks in the network is not surprising as

## Communications and Healthcare are among the sectors that thrive and attract the most capital inflows (Martin, 2018). Additionally,

## emerging markets are reported to attract significant amounts of capital from the rest of the world, including foreign direct investment

## (FDI) (Ngowi, 2005) and foreign portfolio investment (FPI) (Berrill, 1990). Therefore, it appears that those emerging markets’ sectors

## might attract substantial inflows of foreign capital from other regions, in the form of both FDI and FPI, causing those sectors to

## receive more risks and act as the greatest net receivers of risks in the network. Meanwhile, the main net exporter of shocks is CC

## (17.59%), which also acts as the largest net transmitter of shocks in both the short-term (2.24%) and long-term (15.34%). We also

## note that IND is the second greatest net exporter of shocks in the entire system with net spillovers of 10.65%. As those sectors are

## considered the sources of risk transmission, they need to be stabilized first to contain risk spillovers.


**Table 1**
Summary statistics.

```
BM CN CC CNC ENE FIN HC IND TEC UTI
Mean 0.025 0.006 0.024* 0.031** 0.019 0.030** 0.038*** 0.024* 0.031* 0.
(0.114) (0.779) (0.084) (0.011) (0.312) (0.044) (0.006) (0.097) (0.085) (0.119)
Variance 1.293*** 2.595*** 1.006*** 0.738*** 1.810*** 1.096*** 0.979*** 1.052*** 1.703*** 1.017***
Skewness −0.864*** −0.469*** −1.035*** −0.889*** −1.447*** −0.762*** −0.794*** −0.935*** −0.311*** −1.196***
(0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
Ex.Kurtosis 7.557*** 4.168*** 8.903*** 7.837*** 18.700*** 6.792*** 5.650*** 7.336*** 3.940*** 11.353***
(0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
JB 12806.528*** 3891.071*** 17804.632*** 13761.498*** 76309.539*** 10327.370*** 7341.163*** 12215.875*** 3390.936*** 28686.796***
(0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
ADF −60.258*** −71.448*** −61.392*** −62.690*** −63.096*** −62.242*** −67.315*** −63.607*** −67.941*** −63.349***
(0.000) (0.023) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
PP −60.934*** −71.455*** −62.027*** −63.310*** −63.889*** −62.740*** −67.702*** −64.520*** −67.920*** −63.851***
(0.000) (0.023) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
KPSS 0.242*** 0.029*** 0.283*** 0.389*** 0.368*** 0.302*** 0.314*** 0.198*** 0.036*** 0.308***
(0.000) (0.023) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
ERS −28.418*** −25.957*** −26.473*** −10.627*** −25.164*** −23.859*** −10.477*** −12.394*** −28.191*** −5.399***
(0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
ZA −60.460*** −71.522*** −61.638*** −25.188*** −63.319*** −62.442*** −67.531*** −24.484*** −68.143*** −63.575***
(0.000) (0.023) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
𝑄^2 (20) 2678.951*** 1231.206*** 3053.551*** 2829.378*** 742.921*** 2705.892*** 1354.903*** 2492.037*** 1502.313*** 2183.524***
(0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000) (0.000)
Kendall rank correlation coefficients
BM CN CC CNC ENE FIN HC IND TEC UTI
BM 1.000*** 0.319*** 0.657*** 0.613*** 0.567*** 0.637*** 0.487*** 0.626*** 0.415*** 0.562***
CN 0.319*** 1.000*** 0.359*** 0.290*** 0.238*** 0.330*** 0.301*** 0.406*** 0.461*** 0.283***
CC 0.657*** 0.359*** 1.000*** 0.647*** 0.508*** 0.665*** 0.547*** 0.678*** 0.456*** 0.576***
CNC 0.613*** 0.290*** 0.647*** 1.000*** 0.512*** 0.606*** 0.506*** 0.588*** 0.384*** 0.571***
ENE 0.567*** 0.238*** 0.508*** 0.512*** 1.000*** 0.549*** 0.396*** 0.508*** 0.333*** 0.539***
FIN 0.637*** 0.330*** 0.665*** 0.606*** 0.549*** 1.000*** 0.474*** 0.655*** 0.449*** 0.574***
HC 0.487*** 0.301*** 0.547*** 0.506*** 0.396*** 0.474*** 1.000*** 0.546*** 0.350*** 0.467***
IND 0.626*** 0.406*** 0.678*** 0.588*** 0.508*** 0.655*** 0.546*** 1.000*** 0.479*** 0.586***
TEC 0.415*** 0.461*** 0.456*** 0.384*** 0.333*** 0.449*** 0.350*** 0.479*** 1.000*** 0.347***
UTI 0.562*** 0.283*** 0.576*** 0.571*** 0.539*** 0.574*** 0.467*** 0.586*** 0.347*** 1.000***
```
*** Denote significance at 1% significance level.
** Denote significance at 5% significance level.
* Denote significance at 10% significance level.
Notes: Values in parentheses represent _𝑝_ -values; Skewness: D’Agostino (1970) test; Kurtosis: Anscombe and Glynn (1983) test; JB: Jarque and Bera (1980)
normality test; ADF: Dickey and Fuller (1979) unit-root test; PP: Phillips and Perron (1988) unit-root test; KPSS: Kwiatkowski et al. (1992) unit-root test; ERS:
Elliott et al. (1996) unit-root test; ZA: Zivot and Andrews (2002) unit-root test with a structural break; _𝑄_^2 (20): Fisher and Gallagher (2012) weighted Portmanteau
test statistics. The sectors are Basic Materials (BM), Communications & Networking (CN), Consumer Cyclicals (CC), Consumer Non-Cyclicals (CNC), Energy (ENE),
Financials (FIN), Healthcare (HC), Industrials (IND), Technology (TEC) and Utilities (UTI).

**Table 2**
Dynamic total connectedness: Total, short-term and long-term.
BM CN CC CNC ENE FIN HC IND TEC UTI FROM
BM 15.34 (1.76, 13.58) 5.46 (0.38, 5.09) 11.90 (1.16, 10.74) 10.10 (0.92, 9.18) 10.41 (0.93, 9.48) 10.82 (1.02, 9.80) 7.70 (0.63, 7.08) 10.82 (1.03, 9.79) 8.03 (0.60, 7.43) 9.42 (0.87, 8.55) 84.66 (7.53, 77.13)
CN 7.92 (0.38, 7.54) 24.88 (1.88, 23.00) 9.54 (0.53, 9.01) 6.74 (0.35, 6.39) 7.56 (0.38, 7.18) 7.76 (0.44, 7.32) 7.34 (0.35, 6.99) 10.43 (0.64, 9.79) 11.48 (0.78, 10.70) 6.36 (0.31, 6.05) 75.12 (4.14, 70.98)
CC 10.46 (0.99, 9.48) 5.17 (0.38, 4.78) 16.73 (1.67, 15.05) 10.64 (0.95, 9.69) 8.88 (0.70, 8.18) 10.87 (1.01, 9.87) 8.25 (0.64, 7.61) 11.39 (1.08, 10.31) 8.07 (0.61, 7.47) 9.53 (0.81, 8.72) 83.27 (7.17, 76.10)
CNC 10.44 (1.18, 9.25) 4.97 (0.39, 4.58) 12.00 (1.43, 10.57) 16.29 (2.41, 13.88) 9.89 (1.01, 8.88) 10.50 (1.23, 9.26) 8.20 (0.83, 7.37) 10.36 (1.19, 9.17) 7.57 (0.59, 6.98) 9.79 (1.18, 8.61) 83.71 (9.04, 74.67)
ENE 10.43 (0.93, 9.50) 5.55 (0.30, 5.26) 9.99 (0.85, 9.14) 10.11 (0.81, 9.30) 18.89 (2.05, 16.84) 10.47 (0.90, 9.57) 7.55 (0.55, 7.00) 9.44 (0.79, 8.64) 7.91 (0.52, 7.39) 9.65 (0.88, 8.77) 81.11 (6.54, 74.57)
FIN 10.55 (0.95, 9.59) 5.42 (0.39, 5.02) 12.07 (1.14, 10.93) 10.34 (0.92, 9.42) 10.04 (0.83, 9.21) 14.87 (1.59, 13.28) 7.40 (0.58, 6.82) 11.56 (1.07, 10.49) 8.31 (0.66, 7.65) 9.45 (0.84, 8.60) 85.13 (7.38, 77.74)
HC 9.37 (0.94, 8.43) 5.81 (0.48, 5.33) 11.42 (1.17, 10.25) 9.77 (1.00, 8.77) 8.81 (0.83, 7.98) 9.05 (0.91, 8.13) 19.08 (2.79, 16.29) 10.45 (1.14, 9.31) 7.21 (0.62, 6.58) 9.04 (0.94, 8.10) 80.92 (8.04, 72.88)
IND 9.95 (0.97, 8.98) 6.85 (0.54, 6.31) 12.30 (1.21, 11.10) 9.49 (0.88, 8.61) 8.82 (0.73, 8.08) 10.59 (1.07, 9.52) 8.40 (0.69, 7.71) 15.30 (1.67, 13.63) 8.80 (0.73, 8.07) 9.49 (0.90, 8.59) 84.70 (7.72, 76.97)
TEC 8.71 (0.49, 8.22) 8.94 (0.61, 8.33) 10.13 (0.62, 9.51) 6.96 (0.41, 6.56) 8.14 (0.47, 7.68) 9.31 (0.59, 8.72) 6.75 (0.36, 6.39) 10.42 (0.66, 9.76) 23.74 (1.91, 21.83) 6.89 (0.36, 6.53) 76.26 (4.57, 71.69)
UTI 10.00 (1.19, 8.81) 5.76 (0.40, 5.36) 11.50 (1.30, 10.20) 10.20 (1.25, 8.94) 10.47 (1.12, 9.35) 10.03 (1.21, 8.81) 8.35 (0.84, 7.51) 10.49 (1.26, 9.23) 7.41 (0.62, 6.80) 15.80 (2.35, 13.45) 84.20 (9.19, 75.01)
TO 87.84 (8.02, 79.81) 53.93 (3.88, 50.05) 100.86 (9.41, 91.44) 84.34 (7.49, 76.85) 83.02 (7.00, 76.02) 89.39 (8.39, 81.00) 69.94 (5.46, 64.48) 95.35 (8.86, 86.49) 74.79 (5.73, 69.06) 79.62 (7.10, 72.52) TCI
NET 3.18 (0.49, 2.69) −21.20 (−0.27,
−20.93)

```
17.59 (2.24, 15.34) 0.62 (−1.55, 2.18) 1.91 (0.46, 1.45) 4.27 (1.00, 3.26) −10.98 (−2.58,
−8.40)
```
```
10.65 (1.13, 9.52) −1.46 (1.16,−2.63)−4.58 (−2.10,
−2.49)
```
```
91.01 (7.93, 83.08)
```
Notes: Results are based on a 200-day rolling-window QVAR( _𝜏_ = 0_._ 5 ) model with a lag length of order 1 (BIC) and a 100-step-ahead forecast. The sectors are Basic Materials (BM), Communications & Networking (CN), Consumer Cyclicals
(CC), Consumer Non-Cyclicals (CNC), Energy (ENE), Financials (FIN), Healthcare (HC), Industrials (IND), Technology (TEC) and Utilities (UTI). TCI stands for the total connectedness index. The positive (negative) ‘‘NET’’ value of sector _𝑖_
implies that sector _𝑖_ acts as a net transmitter (receiver) of shocks. Values in parentheses represent the short-term and long-term connectedness measures, respectively.

## Furthermore, we find that investigating the expected uncertainty transmission mechanism is of crucial importance as the sectors

## are substantially integrated. This can be derived from the average total connectedness index (TCI) which is equal to 91.01%, meaning

## that on average 91.01% of the shock in one series is transmitted to others while only 8.99% refers to the own-variance share. Thus,

## a shock in one series has a significant impact on all other series. Finally, it should be noted that the largest proportion of the TCI is

## associated with long-term dynamics. This highlights the relevance of designing policies that mitigate the effects of adverse spillover

## shocks.

## Subsequently, we have visualized the bilateral transmission mechanism in Fig. 3 to facilitate the understanding of the network

## dynamics. On the aggregated level, we find that CN and HC are driven by most other series while CC and IND are on the net


**Fig. 3.** Averaged median total, short-term and long-term net pairwise directional connectedness.
Notes: The network plots (from left to right) refer to the overall, short-term, and long-term net pairwise connectedness measures, respectively. Blue (yellow)
nodes indicate that sector _𝑖_ is a net transmitter (receiver) of shocks while the size of the nodes shows the average net total directional connectedness. The
sectors are Basic Materials (BM), Communications & Networking (CN), Consumer Cyclicals (CC), Consumer Non-Cyclicals (CNC), Energy (ENE), Financials (FIN),
Healthcare (HC), Industrials (IND), Technology (TEC) and Utilities (UTI). (For interpretation of the references to color in this figure legend, the reader is referred
to the web version of this article.)

## transmitting end of the shock transmission. When decomposing these network dynamics in their short-term and long-term dynamics,

## it becomes evident that HC and UTI are the main net receivers of short-term dynamics while CC appears to be the main net

## transmitter of shocks — illustrated by the thickness of the directional net pairwise directional connectedness. While CN had a

## relatively insignificant role in the short-term transmission mechanism, it is the major net receiver of long-term uncertainty shocks

## while CC and IND are the main net transmitters of long-term uncertainty shocks.

## 5.1.2. Dynamic quantile-frequency total connectedness

## In this subsection, we concentrate on the uncertainty connectedness across sectors in emerging markets by quantiles. This is

## of great relevance as the average median TCI masks potential time-varying effects as well as time-specific events, we continue

## with interpreting the time, short-term, and long-term dynamic total connectedness measures that are illustrated in Fig. 4. Those

## heatmaps provide additional information on the total connectedness across time, frequency, and quantile spectrum encompassing

## sectoral connectedness during times of low uncertainty (lower quantiles) and during times of high uncertainty (higher quantiles). For

## illustrative purposes, the median-frequency TCI measure of Table 2 is obtained by averaging the dynamic total connectedness over

## the total time, short-term, and long-term periods. Thus, Table 2 does not only mask the dynamics over time but it only represents the

## propagation mechanism at one specific quantile ( 𝜏 = 0. 50 ). As shown in Fig. 4, the total connectedness varies over time, frequency,

## and quantiles.

## When focusing on the time total connectedness (Fig. 4a), the yellow shades along the vertical axis indicate times of higher

## uncertainty transmission across quantiles, which can be associated with some major events such as (i) the Global Financial Crisis

## (2007–2008), (ii) Chinese stock market turbulence (2016), and (iii) the outbreak of the COVID-19 pandemic (2020). Additionally, we

## note that the market risk tends to be significantly higher from 2006 until 2012 before the uncertainty spillovers among sectors drop

## remarkably across quantiles (from 0.05–0.75). Interestingly, Fig. 4a shows the asymmetry in the sectoral uncertainty connectedness

## around the median of the vertical axis as the risk spillovers appear much stronger during periods of turbulent market conditions

## (upper quantiles) than during times of smooth market conditions (lowest quantiles). It implies that spillovers in high uncertainty

## periods and spillovers in low uncertainty periods behave differently. Such asymmetry in spillovers is also found in Vo and Dang

## (2023). However, this observation is slightly different from Chatziantoniou et al. (2022b, 2021b), in which the authors find evidence

## of higher connectedness at both the highest and lowest quantiles.

## Fig. 4b reflects the dynamic short-term connectedness over time and across quantiles. Remarkably, we identify that there is a

## significant asymmetry amongst the time-varying quantile spillovers as the short-term connectedness appears higher on the upper

## end (higher quantiles) than on the lower end (lower quantiles). It implies that market risk in the short term tends to propagate

## across sectors more strongly during periods of high uncertainty than in times of low uncertainty.

## From Fig. 4c, which illustrates the sectoral long-term spillovers, we see another interesting story. Along the horizontal axis,

## we find that long-term spillovers appear higher during periods of smooth market conditions (lower quantiles) than in periods of

## turbulent market conditions (higher quantiles). However, when comparing with the short-term total connectedness, we clearly see

## a difference at the highest quantiles. Apparently, short-term dynamics are even more integrated in the short term than in the long

## term. This could be interpreted that stronger dynamics at the highest quantiles occur in the short run rather than the long run which

## also makes intuitive sense as, for instance, the pronounced degree of shock transmission we observe at the beginning of economic

## and financial crises has decreased in the long run to return to stable economic condition.


**Fig. 4.** Time, short-term and long-term dynamic total connectedness.


```
Fig. 5. Quantile relation between TCI and uncertainty measures.
```
## 5.2. The impact of uncertainty on sectoral total connectedness

## In this subsection, we examine how economic and financial uncertainty indices affect the sectoral total connectedness which

## is commonly interpreted as sectoral market risk. In other words, we are interested in whether and how widely used economic

## and financial uncertainty indicators are related to the network market risk at different quantiles. For that purpose, we employ the

## following regression model:

## 𝑇𝐶𝐼𝑡 ( 𝜏 ) = 𝛿 0 + 𝛿 1 𝐼𝑛𝑑𝑒𝑥𝑡 + 𝑢𝑡 (31)

## where 𝑇𝐶𝐼𝑡 ( 𝜏 )is the dynamic total connectedness at the 𝜏 -quantile on day 𝑡. 𝐼𝑛𝑑𝑒𝑥𝑡 stands for each of the following uncertainty

## indices: the CBOE Volatility Index (VIX), the US Economic Policy Uncertainty Index (EPU US), and the Equity Market-related

## Economic Uncertainty Index (EPU EM). Those uncertainty indices are obtained from FRED Economic Data, which are also on a

## daily basis.

## The regression results are illustrated in Fig. 5 which appears to illustrate more intuitively how the coefficient is gradually

## changing over quantiles. The blue shades stand for positive coefficients, implying a positive relationship between the uncertainty

## indices and the sectoral total connectedness while the red shades indicate negative coefficients between the uncertainties and sectoral

## spillovers. As can be seen in Fig. 5 , we find that uncertainty indices do exert a positive impact on the dynamic total connectedness

## — up until 𝜏 = 0. 70. This finding indicates that in times of low uncertainty and normal market conditions, an increase in economic

## and financial uncertainties is associated with an increase in sectoral interconnectedness across different quantiles. This finding is

## similar to the results of Dang et al. ( 2023).

## Interestingly, at 75% quantile and above, we note that the uncertainty indices have a negative effect on the dynamic total

## connectedness. This result is relatively similar to what we have found from Fig. 4 c that the long-term spillovers become lower at

## the upper quantiles. One possible explanation for this interesting finding is that stock markets are generally regarded to have an

## adaptive feature (Mauboussin, 2002), and market participants tend to be adaptive to variations in market conditions to secure a

## stable level of their expected return (Hiremath & Kumari, 2014). Those appear to cause the herd mentality of the markets to become

## herd immunity to uncertainties during periods of turbulent market conditions.

## 5.3. Robustness check

## In order to verify our obtained empirical results, we compare the total connectedness measures retrieved from the quantile-

## frequency connectedness approach of Chatziantoniou et al. ( 2022a) (QVAR frequency) with closely related alternative connectedness

## frameworks. As the quantile-frequency connectedness approach is the only approach that combines quantile connectedness

## measures (Chatziantoniou et al., 2021b) with the frequency connectedness approach of Baruník and Křehlík ( 2018) (VAR frequency),

## we compare the median total connectedness measures of the quantile-frequency connectedness approach with the frequency

## connectedness approach of Baruník and Křehlík ( 2018) and the time total connectedness measures with the quantile extended joint

## connectedness approach of Cunado et al. ( 2023) (QVAR extended). Fig. 6 shows the results of all three connectedness approaches. By

## comparing the results of the frequency connectedness approach with the quantile-frequency connectedness approach, we find that

## patterns appear to be qualitatively similar to each other while our employed approach has the advantage of being outlier-insensitive.

## Even though the decreases and increases in total connectedness are similar, we find that the VAR-based approach prolongs those

## changes due to the fact that VARs are outlier-sensitive. This phenomenon has also been observed in Chatziantoniou et al. ( 2022a).

## As Baruník and Křehlík ( 2018) pointed out that the time total connectedness measures are equal to the short-term plus long-term

## total connectedness, we use the quantile extended joint connectedness approach of Cunado et al. ( 2023) as a second alternative. In

## this respect, we are using a different connectedness framework that is also based upon quantile vector regressions and thus outlier-

## insensitive. We find that the total connectedness measures of the quantile extended connectedness approach are qualitatively as

## well as quantitatively similar to our employed approach. Thus, we can conclude that our provided empirical results appear to be

## robust compared to alternative connectedness models.


**Fig. 6.** Robustness check: Dynamic total connectedness.
Notes: Results are based on a 200-day rolling-window model with a lag length of order one (BIC), and a 100-step-ahead generalized forecast error variance
decomposition. Solid lines represent the quantile-frequency QVAR approach of Chatziantoniou et al. ( 2022a) (QVAR frequency), dashed lines demonstrate the
frequency VAR approach of Baruník and Křehlík ( 2018) (VAR frequency), and the dotted line represents the QVAR extended connectedness approach of Cunado
et al. ( 2023) (QVAR extended).

## 5.4. Portfolio analysis

## So far our findings confirm strong uncertainty connectedness amongst sectors in emerging markets over time. As such, it is of

## great importance to perform the investigation of diversification strategies. In this section, we pursue two portfolio strategies, namely,

## dynamic hedge ratios and dynamic minimum variance portfolios.

## Table 3 represents the hedge ratios (Kroner & Sultan, 1993), hedging effectiveness (Ederington, 1979), and associated test

## statistics (Antonakakis et al., 2020). Looking at the mean values of the hedge ratio, we note that the cheapest hedge is when a

## 1 USD long position in CNC is hedged with CN (0.23 USD), whereas the most costly hedge would be when we hedge 1 USD long

## position in ENE with 1.09 USD short position in CNC. The HE reveals that all sectoral pairs form portfolios that significantly reduce

## investment uncertainty. We find that a long position in CC and a short position in IND will lead to the highest HE (0.81) among all

## the possible combinations, followed by the pair of CC and FIN with the HE of 0.80. These two pairs of sectors obtain the largest

## risk reduction for investors. Meanwhile, a long position in CN with a short position in ENE (or vice versa) will lead to the least risk

## reduction as they have the lowest HE of 0.16 and 0.19, respectively.

## Additionally, by looking at the 5% and 95% percentiles as well as the standard deviation of each pair of sectors, we can see that

## the hedge ratios are changing over time, indicating that the hedge ratios possess substantial time-varying behavior. It implies that

## market participants should adopt a dynamic hedging strategy instead of a static one. We observe that the most volatile hedge ratios

## occur when a long position in CN is hedged with CNC. There is also a high variability in the hedge ratio between ENE and CNC.

## Meanwhile, the least volatile hedged ratios are found in the pairs of CNC/CN and HC/CN. Hence, investors who use CN to hedge

## their long position in CNC and HC might not only benefit from cheap hedges (i.e., 0.23 USD in the case of CNC and 0.29 USD in

## the case of HC) but also have the least volatile ratios which might lead to a less dynamic hedging strategy.

## Finally, we have a look at the dynamic minimum variance portfolio shown in Table 4. We find that forming a minimum variance

## portfolio significantly reduces investment risk as indicated by the significant hedging effectiveness measures. Specifically, we identify

## that by short selling, we reduce the investment risk with respect to all underlying assets while the long restriction (without short

## selling) does not reduce the investment risk with respect to CNC. Furthermore, the portfolio with short-sellings has a higher Sharpe

## ratio (SR) than the one without short-sellings (0.58 compared to 0.41), suggesting that allowing for short positions is preferable for

## investors who want to mitigate their investment risks. Furthermore, we find that the portfolio weights are time-varying as indicated

## by the 5% and 95% quantiles as well as the standard deviation. Such dynamic feature suggests that investors should follow active

## portfolio rebalancing instead of employing a static strategy.

## 6. Concludingremarks

## This paper investigates the uncertainty spillovers across emerging markets’ sectors during the 2003–2022 period, employing

## the quantile time–frequency connectedness method. Moreover, the impacts of various uncertainty indices on the sectoral total

## connectedness are examined. Key findings from our study could be presented as follows.


**Table 3**
Hedge ratios.

```
Mean Std.Dev. 5% 95% HE 𝑝. value Mean Std.Dev. 5% 95% HE 𝑝. value
BM/CN 0.33 0.09 0.22 0.49 0.29 0.00 FIN/BM 0.77 0.12 0.60 0.97 0.74 0.
BM/CC 0.97 0.14 0.75 1.22 0.78 0.00 FIN/CN 0.32 0.09 0.20 0.48 0.32 0.
BM/CNC 1.07 0.18 0.80 1.38 0.72 0.00 FIN/CC 0.90 0.13 0.71 1.12 0.79 0.
BM/ENE 0.67 0.13 0.46 0.88 0.66 0.00 FIN/CNC 0.98 0.16 0.76 1.26 0.71 0.
BM/FIN 0.91 0.13 0.71 1.15 0.75 0.00 FIN/ENE 0.60 0.12 0.42 0.80 0.63 0.
BM/HC 0.74 0.15 0.53 1.03 0.56 0.00 FIN/HC 0.67 0.13 0.48 0.91 0.54 0.
BM/IND 0.92 0.14 0.70 1.15 0.74 0.00 FIN/IND 0.87 0.12 0.66 1.04 0.79 0.
BM/TEC 0.51 0.12 0.34 0.71 0.42 0.00 FIN/TEC 0.50 0.11 0.34 0.71 0.48 0.
BM/UTI 0.88 0.17 0.62 1.18 0.67 0.00 FIN/UTI 0.81 0.14 0.60 1.06 0.67 0.
CN/BM 0.73 0.19 0.46 1.03 0.25 0.00 HC/BM 0.64 0.13 0.44 0.86 0.52 0.
CN/CC 0.92 0.25 0.57 1.33 0.30 0.00 HC/CN 0.29 0.08 0.18 0.43 0.24 0.
CN/CNC 0.88 0.27 0.49 1.38 0.21 0.00 HC/CC 0.80 0.15 0.56 1.04 0.60 0.
CN/ENE 0.48 0.14 0.27 0.73 0.16 0.00 HC/CNC 0.87 0.16 0.62 1.14 0.55 0.
CN/FIN 0.83 0.23 0.51 1.23 0.28 0.00 HC/ENE 0.47 0.12 0.30 0.67 0.39 0.
CN/HC 0.74 0.20 0.46 1.11 0.22 0.00 HC/FIN 0.68 0.13 0.48 0.91 0.51 0.
CN/IND 1.00 0.25 0.64 1.40 0.36 0.00 HC/IND 0.77 0.15 0.54 1.02 0.60 0.
CN/TEC 0.82 0.18 0.57 1.14 0.49 0.00 HC/TEC 0.40 0.10 0.26 0.58 0.31 0.
CN/UTI 0.75 0.23 0.43 1.17 0.20 0.00 HC/UTI 0.70 0.14 0.47 0.94 0.50 0.
CC/BM 0.76 0.13 0.59 0.95 0.77 0.00 IND/BM 0.75 0.12 0.59 0.96 0.73 0.
CC/CN 0.33 0.09 0.21 0.49 0.35 0.00 IND/CN 0.37 0.09 0.25 0.55 0.40 0.
CC/CNC 0.98 0.16 0.76 1.25 0.77 0.00 IND/CC 0.90 0.13 0.73 1.13 0.79 0.
CC/ENE 0.55 0.11 0.36 0.73 0.57 0.00 IND/CNC 0.95 0.19 0.70 1.30 0.69 0.
CC/FIN 0.83 0.13 0.65 1.03 0.80 0.00 IND/ENE 0.56 0.11 0.38 0.75 0.56 0.
CC/HC 0.72 0.14 0.53 0.98 0.63 0.00 IND/FIN 0.84 0.13 0.69 1.08 0.78 0.
CC/IND 0.86 0.11 0.67 1.04 0.81 0.00 IND/HC 0.73 0.14 0.53 1.01 0.64 0.
CC/TEC 0.49 0.11 0.32 0.69 0.49 0.00 IND/TEC 0.52 0.12 0.36 0.74 0.51 0.
CC/UTI 0.79 0.14 0.57 1.01 0.68 0.00 IND/UTI 0.82 0.15 0.60 1.10 0.69 0.
CNC/BM 0.62 0.11 0.47 0.80 0.73 0.00 TEC/BM 0.74 0.18 0.50 1.06 0.40 0.
CNC/CN 0.23 0.08 0.14 0.38 0.25 0.00 TEC/CN 0.54 0.12 0.37 0.74 0.50 0.
CNC/CC 0.73 0.12 0.56 0.92 0.77 0.00 TEC/CC 0.91 0.22 0.61 1.30 0.44 0.
CNC/ENE 0.47 0.11 0.33 0.65 0.59 0.00 TEC/CNC 0.91 0.24 0.57 1.38 0.33 0.
CNC/FIN 0.67 0.11 0.51 0.85 0.72 0.00 TEC/ENE 0.52 0.15 0.32 0.77 0.27 0.
CNC/HC 0.58 0.11 0.43 0.79 0.58 0.00 TEC/FIN 0.86 0.19 0.58 1.20 0.46 0.
CNC/IND 0.68 0.13 0.48 0.89 0.70 0.00 TEC/HC 0.68 0.17 0.44 0.99 0.29 0.
CNC/TEC 0.36 0.10 0.22 0.53 0.37 0.00 TEC/IND 0.93 0.21 0.61 1.27 0.49 0.
CNC/UTI 0.67 0.12 0.48 0.86 0.68 0.00 TEC/UTI 0.71 0.18 0.45 1.02 0.29 0.
ENE/BM 0.90 0.22 0.66 1.26 0.64 0.00 UTI/BM 0.68 0.14 0.48 0.92 0.66 0.
ENE/CN 0.30 0.11 0.18 0.49 0.19 0.00 UTI/CN 0.26 0.09 0.15 0.41 0.25 0.
ENE/CC 0.94 0.22 0.67 1.34 0.55 0.00 UTI/CC 0.78 0.16 0.59 1.05 0.67 0.
ENE/CNC 1.09 0.26 0.76 1.51 0.55 0.00 UTI/CNC 0.90 0.18 0.68 1.22 0.66 0.
ENE/FIN 0.96 0.22 0.69 1.31 0.60 0.00 UTI/ENE 0.57 0.12 0.40 0.78 0.60 0.
ENE/HC 0.73 0.22 0.48 1.07 0.41 0.00 UTI/FIN 0.75 0.13 0.55 0.99 0.67 0.
ENE/IND 0.92 0.22 0.65 1.28 0.53 0.00 UTI/HC 0.63 0.14 0.45 0.90 0.55 0.
ENE/TEC 0.48 0.16 0.30 0.74 0.30 0.00 UTI/IND 0.78 0.14 0.56 1.02 0.69 0.
ENE/UTI 0.98 0.21 0.69 1.34 0.58 0.00 UTI/TEC 0.38 0.10 0.25 0.56 0.33 0.
```
Notes: Results are based on the hedge ratio of Kroner and Sultan (1993), hedging effectiveness (HE) of Ederington (1979), and the test statistics for the hedging
effectiveness of Antonakakis et al. (2020). The sectors are Basic Materials (BM), Communications & Networking (CN), Consumer Cyclicals (CC), Consumer
Non-Cyclicals (CNC), Energy (ENE), Financials (FIN), Healthcare (HC), Industrials (IND), Technology (TEC) and Utilities (UTI).

## First , our findings show that sectoral uncertainty transmission is exceptionally strong as the total connectedness index is 91.01%,

## implying that the uncertainty transmission across sectors is substantial. The largest proportion of the sectoral total connectedness

## is found to be associated with long-term dynamics. Consumer Cyclicals (CC) is found to be one of the greatest risk transmitters in

## the short and long term. Meanwhile, Communications & Networking (CN) and Healthcare (HC) are the largest risk absorbers at the

## median level. The emergence of those two sectors as net absorbers of shocks in the network is not surprising as Communications

## and Healthcare are among the sectors that thrive and attract the most capital inflows (Martin, 2018).

## Second , from the perspective of quantile, the sectoral uncertainty spillovers oscillate considerably over time. We note that the

## periods of high spillovers appear to coincide with remarkable major events, such as (i) the global financial crisis (2007–2008), (ii)

## Chinese stock market turbulence (2016), and (iii) the outbreak of the COVID-19 pandemic (2020). In addition, we find suggestive

## evidence of asymmetric effects in uncertainty connectedness among sectors as the connectedness becomes much stronger during

## turbulent market conditions (higher quantiles) than smooth market conditions (lower quantiles), showing that spillovers in high

## uncertainty periods and spillovers in low uncertainty periods behave differently. Such asymmetry in spillovers is also found in Vo

## and Dang (2023). However, this observation is slightly different from Chatziantoniou et al. (2022b, 2021b), in which the authors

## find evidence of higher connectedness at both the highest and lowest quantiles.

## Third , we find a positive relationship between uncertainty measures and the sectoral total connectedness during periods of low

## uncertainty and normal market conditions. However, under turbulent market circumstances (at 75% quantile and above), we find


**Table 4**
Minimum variance portfolio.

```
Without short-sellings With short-sellings
Mean Std.Dev. 5% 95% HE 𝑝 -value SR Mean Std.Dev. 5% 95% HE 𝑝 -value SR
BM 0.03 0.07 0.00 0.19 0.44 0.
```
#### 0.

#### −0.12 0.22 −0.42 0.31 0.51 0.

#### 0.

#### CN 0.03 0.05 0.00 0.12 0.72 0.00 0.03 0.09 −0.06 0.19 0.75 0.

#### CC 0.08 0.12 0.00 0.34 0.28 0.00 −0.01 0.32 −0.49 0.55 0.37 0.

#### CNC 0.37 0.18 0.02 0.65 0.01 0.61 0.60 0.32 0.03 1.08 0.14 0.

#### ENE 0.02 0.05 0.00 0.13 0.60 0.00 −0.04 0.14 −0.22 0.21 0.65 0.

#### FIN 0.07 0.10 0.00 0.28 0.34 0.00 0.05 0.25 −0.31 0.49 0.42 0.

#### HC 0.10 0.11 0.00 0.31 0.26 0.00 0.15 0.20 −0.12 0.52 0.35 0.

#### IND 0.10 0.14 0.00 0.39 0.31 0.00 0.06 0.33 −0.40 0.63 0.40 0.

#### TEC 0.05 0.06 0.00 0.17 0.57 0.00 0.06 0.12 −0.11 0.30 0.63 0.

#### UTI 0.15 0.13 0.00 0.39 0.28 0.00 0.22 0.25 −0.18 0.65 0.37 0.

Notes: Results represent time-varying weights of the minimum variance portfolio (Markowitz, 1952) including the hedging effectiveness (HE) of Ederington (1979)
with the associated test statistics provided by Antonakakis et al. (2020). SR stands for the Sharpe ratio. The sectors are Basic Materials (BM), Communications
& Networking (CN), Consumer Cyclicals (CC), Consumer Non-Cyclicals (CNC), Energy (ENE), Financials (FIN), Healthcare (HC), Industrials (IND), Technology
(TEC) and Utilities (UTI).

## that the uncertainty indices have a negative effect on the dynamic total connectedness. We consider that stock markets are generally

## regarded to have an adaptive feature (Mauboussin, 2002), and market participants tend to be adaptive to variations in market

## conditions to secure a stable level of their expected return (Hiremath & Kumari, 2014), causing the herd mentality of the markets

## to become herd immunity to uncertainties during periods of high uncertainty.

## Last but not least , as we have found strong uncertainty connectedness among sectors in emerging markets over time, we consider

## that it is crucial to pursue portfolio diversification strategies. Two different strategies are employed, including the dynamic hedge

## ratios (Kroner & Sultan, 1993) and the minimum variance portfolio (Markowitz, 1952). As our proposed portfolios are found to

## help reduce the investment risk significantly, international investors appear to benefit from our hedging analyses to develop their

## optimal investment portfolios for risk mitigation.

## Apart from the suggested hedging strategies for investors, based on our findings, policy implications have emerged as follows.

## First , given that the sectoral total connectedness is mostly explained by long-term spillovers, policymakers are suggested to shift

## their focus to the long-term dynamics to design appropriate policies that mitigate the effects of adverse spillover shocks. Second , as

## Consumer Cyclicals (CC) is found to be the largest net transmitter of risk in both the short term and long term, this sector is regarded

## as the main source of shock transmission and thus, it tends to spread the risks strongly and rapidly to other sectors in emerging

## markets. As such, governments need to stabilize this sector first to reduce the risk of transmission within the system. Similarly,

## given that Communications & Networking (CN) and Healthcare (HC) are noted to be the largest risk receivers at the median level,

## those sectors tend to receive the most shocks and hence turn out to be the most fragile and vulnerable sectors in the network.

## Therefore, those two sectors also need more serious attention and support from the governments. Third , we note that an increase

## in economic and financial uncertainties is associated with an increase in sectoral interconnectedness across different quantiles.

## Accordingly, governments are suggested to monitor the uncertainty indices to estimate the variations in the sectoral connectedness.

## Subsequently, emerging countries might employ timely and appropriate responses to mitigate the risk propagation across sectors.

## The novel quantile time–frequency connectedness approach of Chatziantoniou et al. (2022a) employed in this study focuses on

## examining the contemporaneous spillovers only while neglecting the lagged connectedness effects, leading to a shortcoming of this

## study. As such, future studies are suggested to adopt the contemporaneous and lagged 𝑅^2 decomposed connectedness approach

## proposed by Balli et al. (2023). This framework appears to be less sensitive to outliers as well as allows us to obtain more insightful

## information by distinguishing between the contemporaneous and lagged spillover effects. We consider that this approach might

## provide insightful implications for both international investors and policymakers.

## Declarationofcompetinginterest

## The authors declare that they have no known competing financial interests or personal relationships that could have appeared

## to influence the work reported in this paper.

## References

Abid, A. (2020). Economic policy uncertainty and exchange rates in emerging markets: Short and long runs evidence. _Finance Research Letters_ , _37_ , Article 101378.
Adekoya, O. B., Akinseye, A. B., Antonakakis, N., Chatziantoniou, I., Gabauer, D., & Oliyide, J. (2022). Crude oil and Islamic sectoral stocks: Asymmetric TVP-VAR
connectedness and investment strategies. _Resources Policy_ , _78_ , Article 102877.
Ahir, H., Bloom, N., & Furceri, D. (2022). _The world uncertainty index_ : _Technical report_ , National Bureau of Economic Research, Inc.
Ahmed, S., Coulibaly, B., & Zlate, A. (2017). International financial spillovers to emerging market economies: How important are economic fundamentals? _Journal
of International Money and Finance_ , _76_ , 133–152.
Akhtaruzzaman, M., Benkraiem, R., Boubaker, S., & Zopounidis, C. (2022). COVID-19 crisis and risk spillovers to developing economies: Evidence from Africa.
_Journal of International Development_ , _34_ (4), 898–918.
Akhtaruzzaman, M., Boubaker, S., & Sensoy, A. (2021). Financial contagion during COVID–19 crisis. _Finance Research Letters_ , _38_ , Article 101604.


Al-Yahyaee, K. H., Rehman, M. U., Mensi, W., & Al-Jarrah, I. M. W. (2019). Can uncertainty indices predict bitcoin prices? A revisited analysis using partial
and multivariate wavelet approaches. _The North American Journal of Economics and Finance_ , _49_ , 47–56.
Alomari, M., Al Rababa’a, A. R., Rehman, M. U., & Power, D. M. (2022). Infectious diseases tracking and sectoral stock market returns: A quantile regression
analysis. _The North American Journal of Economics and Finance_ , _59_ , Article 101584.
Anscombe, F. J., & Glynn, W. J. (1983). Distribution of the kurtosis Statistic B2 For Normal Samples. _Biometrika_ , _70_ (1), 227–234.
Antonakakis, N., Chatziantoniou, I., & Filis, G. (2017). Oil shocks and stock markets: Dynamic connectedness under the prism of recent geopolitical and economic
unrest. _International Review of Financial Analysis_ , _50_ , 1–26.
Antonakakis, N., Cunado, J., Filis, G., Gabauer, D., & de Gracia, F. P. (2020). Oil and asset classes implied volatilities: Investment strategies and hedging
effectiveness. _Energy Economics_ , _91_ , Article 104762.
Apaitan, T., Luangaram, P., & Manopimoke, P. (2022). Uncertainty in an emerging market economy: Evidence from Thailand. _Empirical Economics_ , _62_ (3), 933–989.
Arouri, M. E. H., Jouini, J., & Nguyen, D. K. (2011). Volatility spillovers between oil prices and stock sector returns: Implications for portfolio management.
_Journal of International Money and Finance_ , _30_ (7), 1387–1405.
Badshah, I., Bekiros, S., Lucey, B. M., & Uddin, G. S. (2018). Asymmetric linkages among the fear index and emerging market volatility indices. _Emerging Markets
Review_ , _37_ , 17–31.
Balli, F., Balli, H. O., Dang, T. H. N., & Gabauer, D. (2023). Contemporaneous and lagged R2 decomposed connectedness approach: New evidence from the
energy futures market. _Finance Research Letters_ , _57_ , Article 104168.
Balli, F., Balli, H. O., Hasan, M., & Gregory-Allen, R. (2020). Economic policy uncertainty spillover effects on sectoral equity returns of New Zealand. _Journal of
Economics and Finance_ , _44_ , 670–686.
Balli, F., Balli, H. O., & Hong, R. (2016). Spillover effects on the sectoral returns for Australian and New Zealand equity markets. _Journal of Economics and
Finance_ , _40_ , 568–589.
Balli, H. O., Balli, F., & Louis, R. J. (2013). Time-varying spillover effects on sectoral equity returns. _International Review of Finance_ , _13_ (1), 67–91.
Balli, F., Billah, M., Balli, H. O., & De Bruin, A. (2021). Spillovers to sectoral equity returns: Do liquidity and financial positions matter? _Applied Economics_ ,
_53_ (27), 3097–3130.
Baruník, J., Kočenda, E., & Vácha, L. (2016). Asymmetric connectedness on the US stock market: Bad and good volatility spillovers. _Journal of Financial Markets_ ,
_27_ , 55–78.
Baruník, J., Kočenda, E., & Vácha, L. (2017). Asymmetric volatility connectedness on the forex market. _Journal of International Money and Finance_ , _77_ , 39–56.
Baruník, J., & Křehlík, T. (2018). Measuring the frequency dynamics of financial connectedness and systemic risk. _Journal of Financial Econometrics_ , _16_ (2),
271–296.
Bekaert, G., Harvey, C. R., & Lundblad, C. (2005). Does financial liberalization spur growth? _Journal of Financial Economics_ , _77_ (1), 3–55.
Bekiros, S. D. (2014). Contagion, decoupling and the spillover effects of the US financial crisis: Evidence from the BRIC markets. _International Review of Financial
Analysis_ , _33_ , 58–69.
Berrill, S. (1990). _Foreign portfolio investment in emerging equity market_ : _Technical report_ , World Institute for Development Economics Research.
Bollerslev, T. (1986). Generalized autoregressive conditional heteroskedasticity. _Journal of Econometrics_ , _31_ (3), 307–327.
Bouri, E., Cepni, O., Gabauer, D., & Gupta, R. (2021). Return connectedness across asset classes around the COVID-19 outbreak. _International Review of Financial
Analysis_ , _73_ , Article 101646.
Bouri, E., Gupta, R., Tiwari, A. K., & Roubaud, D. (2017). Does Bitcoin hedge global uncertainty? Evidence from wavelet-based quantile-in-quantile regressions.
_Finance Research Letters_ , _23_ , 87–95.
Carrière-Swallow, Y., & Céspedes, L. F. (2013). The impact of uncertainty shocks in emerging economies. _Journal of International Economics_ , _90_ (2), 316–325.
Carrieri, F., Errunza, V., & Hogan, K. (2007). Characterizing world market integration through time. _Journal of Financial and Quantitative Analysis_ , _42_ (4), 915–940.
Chatziantoniou, I., Abakah, E. J. A., Gabauer, D., & Tiwari, A. K. (2022a). Quantile time–frequency price connectedness between green bond, green equity,
sustainable investments and clean energy markets. _Journal of Cleaner Production_ , _361_ , Article 132088.
Chatziantoniou, I., Abakah, E. J. A., Gabauer, D., & Tiwari, A. K. (2022b). Quantile time–frequency price connectedness between green bond, green equity,
sustainable investments and clean energy markets. _Journal of Cleaner Production_ , _361_ , Article 132088.
Chatziantoniou, I., Gabauer, D., & Marfatia, H. A. (2022). Dynamic connectedness and spillovers across sectors: Evidence from the Indian stock market. _Scottish
Journal of Political Economy_ , _69_ (3), 283–300.
Chatziantoniou, I., Gabauer, D., & Stenfors, A. (2021a). Interest rate swaps and the transmission mechanism of monetary policy: A quantile connectedness
approach. _Economics Letters_ , _204_ , Article 109891.
Chatziantoniou, I., Gabauer, D., & Stenfors, A. (2021b). Interest rate swaps and the transmission mechanism of monetary policy: A quantile connectedness
approach. _Economics Letters_ , _204_ , Article 109891.
Chen, M.-P., Chen, P.-F., & Lee, C.-C. (2014). Frontier stock market integration and the global financial crisis. _The North American Journal of Economics and
Finance_ , _29_ , 84–103.
Costa, A., Matos, P., & da Silva, C. (2022). Sectoral connectedness: New evidence from US stock market during COVID-19 pandemics. _Finance Research Letters_ ,
_45_ , Article 102124.
Cunado, J., Chatziantoniou, I., Gabauer, D., de Gracia, F. P., & Hardik, M. (2023). Dynamic spillovers across precious metals and oil realized volatilities: Evidence
from quantile extended joint connectedness measures. _Journal of Commodity Markets_ , _30_ , Article 100327.
D’Agostino, R. B. (1970). Transformation to normality of the null distribution of g1. _Biometrika_ , 679–681.
Dai, P.-F., Xiong, X., Liu, Z., Huynh, T. L. D., & Sun, J. (2021). Preventing crash in stock market: The role of economic policy uncertainty during COVID-19.
_Financial Innovation_ , _7_ , 1–15.
Dang, T. H.-N., Nguyen, N. T., & Vo, D. H. (2023). Sectoral volatility spillovers and their determinants in Vietnam. _Economic Change and Restructuring_ , _56_ (1),
681–700.
Dickey, D. A., & Fuller, W. A. (1979). Distribution of the estimators for autoregressive time series with a unit root. _Journal of the American statistical association_ ,
_74_ (366a), 427–431.
Diebold, F. X., & Yilmaz, K. (2009). Measuring financial asset return and volatility spillovers, with application to global equity markets. _The Economic Journal_ ,
_119_ (534), 158–171.
Diebold, F. X., & Yılmaz, K. (2012). Better to give than to receive: Predictive directional measurement of volatility spillovers. _International Journal of Forecasting_ ,
_28_ (1), 57–66.
Diebold, F. X., & Yılmaz, K. (2014). On the network topology of variance decompositions: Measuring the connectedness of financial firms. _Journal of Econometrics_ ,
_182_ (1), 119–134.
Eckernkemper, T. (2018). Modeling systemic risk: Time-varying tail dependence when forecasting marginal expected shortfall. _Journal of Financial Econometrics_ ,
_16_ (1), 63–117.
Ederington, L. H. (1979). The hedging performance of the new futures markets. _The Journal of Finance_ , _34_ (1), 157–170.
Elliott, G., Rothenberg, T. J., & Stock, J. H. (1996). Efficient tests for an autoregressive unit root. _Econometrica_ , _64_ (4), 813–836.
Elyasiani, E., Mansur, I., & Odusami, B. (2011). Oil price shocks and industry stock returns. _Energy Economics_ , _33_ (5), 966–974.
Engle, R. F. (1982). Autoregressive conditional heteroscedasticity with estimates of the variance of United Kingdom inflation. _Econometrica_ , 987–1007.


Engle, R. (2002). Dynamic conditional correlation: A simple class of multivariate generalized autoregressive conditional heteroskedasticity models. _Journal of
Business & Economic Statistics_ , _20_ (3), 339–350.
Engle, R., Ito, T., & Lin, W.-L. (1990). Meteor showers or heat waves? Heteroskedastic intra-daily volatility in the foreign exchange market. _Econometrica_ , _58_ (3),
525–542.
Eterovic, D., Sweet, C., & Eterovic, N. (2022). Asymmetric spillovers in emerging market monetary policy. _International Review of Economics and Finance_ , _82_ ,
650–662.
Fassas, A. P., & Siriopoulos, C. (2019). Intraday price discovery and volatility spillovers in an emerging market. _International Review of Economics & Finance_ , _59_ ,
333–346.
Fisher, T. J., & Gallagher, C. M. (2012). New weighted Portmanteau statistics for time series goodness of fit testing. _Journal of the American Statistical Association_ ,
_107_ (498), 777–787.
Gabauer, D., Subramaniam, S., & Gupta, R. (2022). On the transmission mechanism of Asia-Pacific yield curve characteristics. _International Journal of Finance
and Economics_ , _27_ (1), 473–488.
Gao, Y., Zheng, W., & Wang, Y. (2023). Sectoral risk contagion and quantile network connectedness on Chinese stock sectors after the COVID-19 outbreak. _China
Finance Review International_.
Geng, J.-B., Xu, X.-Y., & Ji, Q. (2020). The time-frequency impacts of natural gas prices on US economic activity. _Energy_ , _205_ , Article 118005.
Glosten, L. R., Jagannathan, R., & Runkle, D. E. (1993). On the relation between the expected value and the volatility of the nominal excess return on stocks.
_The Journal of Finance_ , _48_ (5), 1779–1801.
Gupta, R., Olasehinde-Williams, G., & Wohar, M. E. (2020). The impact of US uncertainty shocks on a panel of advanced and emerging market economies. _The
Journal of International Trade and Economic Development_ , _29_ (6), 711–721.
Hansen, P. R., & Lunde, A. (2005). A forecast comparison of volatility models: Does anything beat a GARCH (1, 1)? _Journal of Applied Econometrics_ , _20_ (7),
873–889.
Hedström, A., Zelander, N., Junttila, J., & Uddin, G. S. (2020). Emerging market contagion under geopolitical uncertainty. _Emerging Markets Finance and Trade_ ,
_56_ (6), 1377–1401.
Hiremath, G. S., & Kumari, J. (2014). Stock returns predictability and the adaptive market hypothesis in emerging markets: Evidence from India. _SpringerPlus_ ,
_3_ , 1–14.
Hkiri, B., Hammoudeh, S., Aloui, C., & Yarovaya, L. (2017). Are Islamic indexes a safe haven for investors? An analysis of total, directional and net volatility
spillovers between conventional and Islamic indexes and importance of crisis periods. _Pacific-Basin Finance Journal_ , _43_ , 124–150.
Huidrom, R., Ayhan Kose, M., Matsuoka, H., & Ohnsorge, F. L. (2020). How important are spillovers from major emerging markets? _International Finance_ , _23_ (1),
47–63.
Jarque, C. M., & Bera, A. K. (1980). Efficient tests for normality, homoscedasticity and serial independence of regression residuals. _Economics Letters_ , _6_ (3),
255–259.
Jiang, W., & Chen, Y. (2022). The time-frequency connectedness among carbon, traditional/new energy and material markets of China in pre-and post-COVID-
outbreak periods. _Energy_ , _246_ , Article 123320.
Jung, R. C., & Maderitsch, R. (2014). Structural breaks in volatility spillovers between international financial markets: Contagion or mere interdependence? _Journal
of Banking & Finance_ , _47_ , 331–342.
Koop, G., Pesaran, M. H., & Potter, S. M. (1996). Impulse response analysis in nonlinear multivariate models. _Journal of Econometrics_ , _74_ (1), 119–147.
Kroner, K. F., & Sultan, J. (1993). Time-varying distributions and dynamic hedging with foreign currency futures. _Journal of Financial and Quantitative Analysis_ ,
_28_ (4), 535–551.
Kwiatkowski, D., Phillips, P. C., Schmidt, P., & Shin, Y. (1992). Testing the null hypothesis of stationarity against the alternative of a unit root: How sure are
we that economic time series have a unit root? _Journal of Econometrics_ , _54_ (1–3), 159–178.
Labidi, C., Rahman, M. L., Hedström, A., Uddin, G. S., & Bekiros, S. (2018). Quantile dependence between developed and emerging stock markets aftermath of
the global financial crisis. _International Review of Financial Analysis_ , _59_ , 179–211.
Laborda, R., & Olmo, J. (2021). Volatility spillover between economic sectors in financial crisis prediction: Evidence spanning the great financial crisis and
Covid-19 pandemic. _Research in International Business and Finance_ , _57_ , Article 101402.
Lastrapes, W. D., & Wiesen, T. F. (2021). The joint spillover index. _Economic Modelling_ , _94_ , 681–691.
Malik, F. (2022). Volatility spillover among sector equity returns under structural breaks. _Review of Quantitative Finance and Accounting_ , _58_ (3), 1063–1080.
Markowitz, H. (1952). Selection portfolio. _The Journal of Finance_ , _7_ (1), 77–91.
Martin, E. (2018). Money is flooding into these 10 industries that are adding jobs and thriving. _CNBC_.
Mauboussin, M. J. (2002). Revisiting market efficiency: The stock market as a complex adaptive system. _Journal of Applied Corporate Finance_ , _14_ (4), 47–55.
Mensi, W., Al Rababa’a, A. R., Alomari, M., Vo, X. V., & Kang, S. H. (2022). Dynamic frequency volatility spillovers and connectedness between strategic
commodity and stock markets: US-based sectoral analysis. _Resources Policy_ , _79_ , Article 102976.
Mensi, W., Al Rababa’a, A. R., Vo, X. V., & Kang, S. H. (2021). Asymmetric spillover and network connectedness between crude oil, gold, and Chinese sector
stock markets. _Energy Economics_ , _98_ , Article 105262.
Mensi, W., Nekhili, R., Vo, X. V., Suleman, T., & Kang, S. H. (2021). Asymmetric volatility connectedness among US stock sectors. _The North American Journal
of Economics and Finance_ , _56_ , Article 101327.
Mensi, W., Shafiullah, M., Vo, X. V., & Kang, S. H. (2021). Volatility spillovers between strategic commodity futures and stock markets and portfolio implications:
Evidence from developed and emerging economies. _Resources Policy_ , _71_ , Article 102002.
Mensi, W., Yousaf, I., Vo, X. V., & Kang, S. H. (2022). Asymmetric spillover and network connectedness between gold, BRENT oil and EU subsector markets.
_Journal of International Financial Markets, Institutions and Money_ , _76_ , Article 101487.
Mensi, W., Ziadat, S. A., Vo, X. V., & Kang, S. H. (2022). Extreme quantile connectedness and spillovers between oil and Vietnamese stock markets: A sectoral
analysis. _International Journal of Emerging Markets_.
Mobarek, A., Muradoglu, G., Mollah, S., & Hou, A. J. (2016). Determinants of time varying co-movements among international stock markets during crisis and
non-crisis periods. _Journal of Financial Stability_ , _24_ , 1–11.
Moneta, F., & Rüffer, R. (2009). Business cycle synchronisation in East Asia. _Journal of Asian Economics_ , _20_ (1), 1–12.
Ngowi, H. P. (2005). Foreign direct investment inflows into emerging markets: Driving forces and lessons for Africa. In _Capital flows and foreign direct investments
in emerging markets_ (pp. 145–161). Springer.
Pesaran, H. H., & Shin, Y. (1998). Generalized impulse response analysis in linear multivariate models. _Economics Letters_ , _58_ (1), 17–29.
Pham, S. D., Nguyen, T. T. T., & Do, H. X. (2023). Natural gas and the utility sector nexus in the US: Quantile connectedness and portfolio implications. _Energy
Economics_ , _120_ , Article 106632.
Phillips, P. C., & Perron, P. (1988). Testing for a unit root in time series regression. _Biometrika_ , _75_ (2), 335–346.
Phylaktis, K., & Xia, L. (2009). Equity market comovement and contagion: A sectoral perspective. _Financial Management_ , _38_ (2), 381–409.
Sarwar, G., & Khan, W. (2017). The effect of US stock market uncertainty on emerging market returns. _Emerging Markets Finance and Trade_ , _53_ (8), 1796–1811.
Shahzad, S. J. H., Mensi, W., Hammoudeh, S., Rehman, M. U., & Al-Yahyaee, K. H. (2018). Extreme dependence and risk spillovers between oil and Islamic
stock markets. _Emerging Markets Review_ , _34_ , 42–63.


Shahzad, S. J. H., Naeem, M. A., Peng, Z., & Bouri, E. (2021). Asymmetric volatility spillover among Chinese sectors during COVID-19. _International Review of
Financial Analysis_ , _75_ , Article 101754.
Sharpe, W. F. (1994). The Sharpe ratio. _Journal of Portfolio Management_ , _21_ (1), 49–58.
Shen, Y.-Y., Jiang, Z.-Q., Ma, J.-C., Wang, G.-J., & Zhou, W.-X. (2021). Sector connectedness in the Chinese stock markets. _Empirical Economics_ , 1–28.
Stenfors, A., Chatziantoniou, I., & Gabauer, D. (2022). Independent policy, dependent outcomes: A game of cross-country dominoes across European yield curves.
_Journal of International Financial Markets, Institutions and Money_ , _81_ , Article 101658.
Stiassny, A. (1996). A spectral decomposition for structural VAR models. _Empirical Economics_ , _21_ , 535–555.
Su, X., & Liu, Z. (2021a). Sector volatility spillover and economic policy uncertainty: Evidence from China’s stock market. _Mathematics_ , _9_ (12), 1411.
Su, X., & Liu, Z. (2021b). Sector volatility spillover and economic policy uncertainty: Evidence from China’s stock market. _Mathematics_ , _9_ (12), 1411.
Suleman, M. T., Rehman, M. U., Sheikh, U. A., & Kang, S. H. (2023). Dynamic time-frequency connectedness between European emissions trading system and
sustainability markets. _Energy Economics_ , _123_ , Article 106726.
Umar, M., Farid, S., & Naeem, M. A. (2022). Time-frequency connectedness among clean-energy stocks and fossil fuel markets: Comparison between financial,
oil and pandemic crisis. _Energy_ , _240_ , Article 122702.
Urom, C., Ndubuisi, G., Del Lo, G., & Yuni, D. (2022). Global commodity and equity markets spillovers to Africa during the COVID-19 pandemic. _Emerging
Markets Review_ , Article 100948.
Vo, D. H., & Dang, T. H.-N. (2023). The geopolitical risk spillovers across BRICS countries: A quantile frequency connectedness approach. _Scottish Journal of
Political Economy_.
Wiesen, T. F., Beaumont, P. M., Norrbin, S. C., & Srivastava, A. (2018). Are generalized spillover indices overstating connectedness? _Economics Letters_ , _173_ ,
131–134.
World Economics (2022). Emerging markets economic data. https://www.worldeconomics.com/Regions/Emerging-Markets/default.aspx.
Wu, S., & Pan, Q. (2021). Economic growth in emerging market countries. _Global Journal of Emerging Market Economies_ , _13_ (2), 192–215.
Wu, F., Zhang, D., & Zhang, Z. (2019). Connectedness and risk spillovers in China’s stock market: A sectoral analysis. _Economic Systems_ , _43_ (3–4), Article 100718.
Yarovaya, L., & Lau, M. C. K. (2016). Stock market comovements around the Global Financial Crisis: Evidence from the UK, BRICS and MIST markets. _Research
in International Business and Finance_ , _37_ , 605–619.
Yin, K., Liu, Z., & Jin, X. (2020). Interindustry volatility spillover effects in China’s stock market. _Physica A. Statistical Mechanics and its Applications_ , _539_ , Article
122936.
Zhang, W., Zhuang, X., Wang, J., & Lu, Y. (2020). Connectedness and systemic risk spillovers analysis of Chinese sectors based on tail risk network. _North
American Journal of Economics and Finance_ , _54_ , Article 101248.
Zivot, E., & Andrews, D. W. K. (2002). Further evidence on the great crash, the oil-price shock, and the unit-root hypothesis. _Journal of Business & Economic
Statistics_ , _20_ (1), 25–44.


