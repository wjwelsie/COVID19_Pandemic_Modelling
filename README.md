# COVID19 Pandemic Modelling
In this repository, two new pandemic models are introduced to describe and predict the trend of COVID-19 (SARS-CoV-2) pandemic outbreak. Both models are *Deterministic pandemic models*.

#### SEIDiQRD Model
This model is proposed with 7 infection states: Susceptible (S), Exposed (E), Infected (I), Diagnosed (Di), Quarantined (Q), Recovered (R), and Death (D), represented with respective parameters in parentheses.
The SEIDiQRD model is a general COVID-19 model which is able to describe the trend of infected and death cases in most of the countries. It was simulated with data from three countires: the United Kingdom, France and Italy. 
Qualitatively, the model predicts the results with a better-fitted curve comparing to the experimental data. Quantitatively, there is a 95.24% decrease in discrepancy when comparing the exact number of infections within 5-day time interval comparing to the SEIR model.

#### SEQPIRD Model
It is a pandemic model designed by considering the Chinese lock-down policy. Therefore, it is a pandemic model that is specialised for China.
