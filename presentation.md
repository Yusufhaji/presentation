Name: Yusuf Hassan Haji   ANR:180541


Empirical equations for the Solow Model
=================


###Introduction
-------------------------------------------
I attempt to explain long run economic growth by looking at:

* capital accumulation
* labor or population growth 
* and increases in productivity (technological progress)
* Check my assignment 2 for further explanation:
[http://yusufhaji.github.io/assignment2/](http://yusufhaji.github.io/assignment2/ "Assignment 2 link")

--------------------------------------------------


###Motivation
------------------------------------------------------------
* How to incorporate technological progress in the Solow model
* About policies to promote growth
* About growth empirics:  confronting the theory with facts
* Two simple models in which the rate of technological progress is endogenous
* * So, poor countries grow faster than richer countries and can be seen from the below figure:

![Figure 1: Conditional convergence](http://www.puertorico-herald.org/images/Convergence/image1.gif)

------------------------------------------------------------


###Growth empirics: Balanced growth
-----------------------------------------------------------------------
* Solow model’s steady state equilibrium exhibits balanced growth
* Many variables grow at the same rate
* Solow model predicts Y/L and K/L grow at the same rate (g), so K/Y should be constant
* Solow model predicts real wage grows at same rate as Y/L, while real rental price is constant.  
* And so the steady state capital per effective worker is : 

$k^*=(s/(δ+n+g))^{1/(1-∝)}$

See the figure below to see the steady state of capital:

![Figue 2](http://cruel.org/econthought/essays/growth/neoclass/image/solowconv1.gif)


----------------------------------------------------------------------------

###Growth empirics:  Convergence
-------------------------------------------------------------
* Solow model predicts that, other things equal, “poor” countries (with lower Y/L  and K/L) should grow faster than “rich” ones
* If true, then the income gap between rich & poor countries would shrink over time, causing living standards to “converge.”  
* In real world, many poor countries do NOT grow faster than rich ones.  Does this mean the Solow model fails?  


-------------------------------------------------------------------------------------

###Growth empirics:  Convergence
--------------------------------------------------------------
* Convergence in the Solow model is arrived at by taking a first order Taylor expansion of output around the steady state level gives : 

$(d[lny(t)-lny^*])/dt=-λ[lny(t)-lny^*]$

* The Solow model suggests a natural regression to study the rate of convergence;
	
$lny(t)= (1-e^{-λt} )  lny^*+ e^{-λt}  lny(0)$

---------------------------------------------------------------------------------------

###Growth empirics:  Convergence
---------------------------------------------
* Equation (E.2) can also be derived as above by subtracting lny(t-T) from both sides. T is an arbitrary log in order to get income per effective worker at some initial year

* Equation (E.1) can therefore become:

$lny(t)- lny(t-T) = lny^* - (e^{-λt} )  lny^*- lny(t-T)+ e^(-λt)  lny(t-T)$

$lny(t)- lny(t-T)=(1-e^{-λt} )  lny^* - (1-e^{-λt}) lny(t-T)$

* We consider a time span of just one year which is technically feasible given that the underlying dataset provides annual data.
* Thus the growth of income is a function of the determinants of ultimate steady state and the initial level of income
* I present the Solow model in a graphical form and study how it explains how a country can be trapped when it cannot converge and this is the case in many African countries. See the figure below

![Figure 3](http://cruel.org/econthought/essays/growth/neoclass/image/solowtrap4.gif)




----------------------------------------------------------------------------------------------

###Growth empirics:  Derive the regression equation
--------------------------------------------------------------
* The Solow model takes the rates of savings, population growth and technological progress as exogenous
* A Cobb-Douglas production function is assumed , so production at time t is given by:

$Y(t) = K(t)^α (A(t)L(t))^{1-α}  ,0<α<1$

L and A are assumed to be exogenous at rates n and g∶ $L(t) = L(0)  e^{nt}$

$A(t)= A(0)  e^{gt}$

* But the central-predictions of the Solow model concern the impact of saving and population growth on real income and so we can derive the steady state output per effective worker : y*
Since :                   
y = k^α
And so : 
$y^* = (s/(δ+n+g))^{∝/(1-∝)}$

* Mankiw Romer and Weil (1992) assume that:
lnA(0) = a + ε  where a is a constant and ε  is a country-specific shock (e.g., climate, social capital and property rights). The constant a is assumed to be identical across countries
* Using  lnA(0) = a + ε   and normalizing t=0 and thus taking log of income per capita we get the basic regression equation: 

$ln(Y/L) = lnA(0) + gt+∝/(1-∝) lns-  ∝/(1-∝)  ln(n+g+δ) + ε$

* The production function in intensive form is :

$y= k^∝ h^β$ 

Savings: 

 $s ≡ s_K+s_H$
* In steady state k ̇= 0 and k ̇= h= 0 and so 

$k^* = ((s_K^(1-β) s_H^β)/(δ+n+g))^{1/(1-∝-β)}$      and     

$h^* = ((s_K^∝ s_H^{(1-∝)})/(δ+n+g))^{1/(1-∝-β)}$

So    $y = k^∝ h^β$  becomes;    $y^*=((s_K^(1-β) s_H^β)/(δ+n+g))^{∝/(1-∝-β)} ((s_K^∝ s_H^{1-∝})/(δ+n+g))^{β/(1-∝-β)}$
* And simplifies to be:

$((Y(t))/(L(t)))^*=A(0).e^gt=A_0 e^gt  (((s_K^α s_H^β ))/(δ+n+g)^{1/(∝+β)} )^{(α+β)/(1-∝-β)}$

* Taking logs on both sides of the equation gives the linear specification:
$ln(Y/L)^*=lnA(0) + gt-(∝+β)/(1-∝-β) ln(n+g+δ) +  ∝/(1-∝-β)  lns_K + β/(1-∝-β)  lns_H $

------------------------------------------------------------------------------------------------------
###Growth empirics:  Conclusion
-----------------------------------------------------
* steady state growth rate of income per person depends solely on the exogenous rate of tech progress
* Ways to increase the saving rate
    * increase public saving (reduce budget deficit)
    * tax incentives for private saving
* Empirical studies
    * Solow model explains balanced growth, conditional convergence
    * Cross-country variation in living standards is due to differences in cap. accumulation and in production efficiency

------------------------------------------------------------------------------------------------



