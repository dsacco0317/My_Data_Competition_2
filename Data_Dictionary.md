## Data Dictionary ##


__Data Set Information:__

This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel Sorting Smoothing Method to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. Therefore, among the six data mining techniques, artificial neural network is the only one that can accurately estimate the real probability of default.

|   |   |   |
|---|---|---|
| __Feature ID__ | __Description__  | __Values__ |
| X1 | Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit. | INTEGER VALUE |
| X2 | Gender | Male=1 Female=2 |
| X3 | Education | 1=Graduate School 2=University 3=High School 4=Others |
| X4 | Marital Status | 1=Married 2=Single 3=Others |
| X5 | Age | INTEGER VALUE (Year) |
| X6 - X11 | History of past payment. We tracked the past monthly payment records (from April to September, 2005) (X6=September 2005 & X11=April 2005) | -1=pay duly; 1=payment delay for one month; 2=payment delay for two months |
| X12-X17 | Amount of bill statement (NT dollar). X12=amount of bill statement in September, 2005; X13=amount of bill statement in August, 2005 ... | INTEGER VALUE |
| X18-X23 | Amount of previous payment (NT dollar) | X18=amount paid in September, 2005; X19=amount paid in August, 2005; . . . |


__Source:__

Name: I-Cheng Yeh 
email addresses: (1) icyeh '@' chu.edu.tw (2) 140910 '@' mail.tku.edu.tw 
institutions: (1) Department of Information Management, Chung Hua University, Taiwan. (2) Department of Civil Engineering, Tamkang University, Taiwan. 
other contact information: 886-2-26215656 ext. 3181 