# RED-EYE-Flight-NAPZ-
SDSS 2026 Datathon 

The goal of our analysis was for individual customers to be able to predict the average market fare for a trip they wish to perform. Becuase of this, we included largest market average fare and lowest market average fare as target variables, since we assumed passengers only knew the origin, destination and time of their trip, and that we had the data related to each city present in the file. Additionally, individual customers may find this information useful, for example because the largest carrier will probably have the more frequent flights, which would give the customer more flexibility in erms of dates when using their service. Following this assumnption of information possesed by the customers, we did not consider Total Fare-Paying Passengers for either city, since this is not information custoemrs have at the time of purchasing tickets. 
In summary, we wanted to answer the following questions: **"I see a ticket at a specific price, do I buy it?", "Am I paying above or below the average?", "How confident am I of this?"**

To do so we focused on **model interpretability** and **uncertainty quantification for individual data points**.

Assumptions:
- Customers only know their origin and destination
- We have information about cities
- Current trends in ticket prices will continue in the future
- Samples are (mostly) i.i.d.
