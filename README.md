# Bank Deposite
It's a Classifaication Project that the client subscribed a term deposit or not
The columns Description is :
Client Data:

    age: (numeric)

    job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

    marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

    education: (categorical: primary, secondary, tertiary and unknown)

    default: has credit in default? (categorical: 'no','yes','unknown')

    housing: has housing loan? (categorical: 'no','yes','unknown')

    loan: has personal loan? (categorical: 'no','yes','unknown')

    balance: Balance of the individual.

Related with the last contact of the current campaign:

    contact: contact communication type (categorical: 'cellular','telephone')

    month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

    day: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

    duration: last contact duration, in seconds (numeric).

Other attributes:

    campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

    pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted)

    previous: number of contacts performed before this campaign and for this client (numeric)

    poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

Dependent Feature

    deposit: has the client subscribed a term deposit? (binary: 'yes','no')


First thing we do Exploration and Cleaning the Data and it's apper in the First part in the Notebook 

Then I done some Data Analysis and do a Dashboard using Tableau 
(To review the Story and have a Dynamic view please visit that link https://public.tableau.com/app/profile/mustafa.aly/viz/BankDepositeAgreement/Story1)

![Story 1](https://github.com/Mustafa-Aly/Bank_Deposite/assets/129996921/83e30479-eb9b-4851-9b96-4ed708d58f2a)

![Story 2](https://github.com/Mustafa-Aly/Bank_Deposite/assets/129996921/c1edb065-bf83-4708-9acb-8b1d1c352b5c)

After Analysis we go to Modeling 

I try first Machine learning to find the Best Algorithm and then Try Random Grid Search Using Pipeline 

I found the best Accuracy was 81% using Random Forrest and here the Pipeline and snapshot of the accuracy

![Screenshot 2024-03-09 at 19-27-50 Google Colaboratory](https://github.com/Mustafa-Aly/Bank_Deposite/assets/129996921/2bc70932-b021-458e-a7f1-95fac8181107)

![Screenshot 2024-03-09 at 19-28-57 Google Colaboratory](https://github.com/Mustafa-Aly/Bank_Deposite/assets/129996921/e08fad79-5609-4fcf-b2e2-97e7a88e69e5)

Then I used Deep learning and used ANN to try a better accuracy I reach 84% used ANN and here the Pipeline and the classification report


![Screenshot 2024-03-09 at 19-26-23 Google Colaboratory](https://github.com/Mustafa-Aly/Bank_Deposite/assets/129996921/4db81a36-4718-486d-aa61-ad8a76f60cbb)

![Screenshot 2024-03-09 at 19-29-17 Google Colaboratory](https://github.com/Mustafa-Aly/Bank_Deposite/assets/129996921/de8cc7ff-3b28-475e-acfa-ca914be2c4f4)
