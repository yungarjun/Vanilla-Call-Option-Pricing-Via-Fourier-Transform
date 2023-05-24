# Vanilla-Option-Pricing-Via-Fourier-Transform
A python function to price vanilla call or put options using the fourier transform method

Given pre-defined variables, this function will return the value of a European call option by Fourier inversion, with inputs  𝑆 (the time zero value of the underlying asset), 𝐾(the strike), sgm (the volatility of the underlying asset),  𝑟 (the riskless interest rate), 𝑇 (the maturity of the option) and phi (the characteristic function of the distribution of the logarithmic asset price at time  𝑇  under the risk-neutral measure associated with taking the domestic savings account as the numeraire).
  
Additionally, the function phi(omega,mubar,sgmbar), the characteristic function in the Black/Scholes model, as defined above, is implemented.
