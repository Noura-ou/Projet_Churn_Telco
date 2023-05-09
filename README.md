# Projet_Churn_Telco
Telco est une entreprise de télécom. 
Elle rencontre actuellement un turnover important chez ses clients, elle vous sollicite pour 2 choses: 
    Expliquer quel est le profil de client qui “churn” le plus 
    Donner pour chaque client une probabilité qu’il churn afin de voir quelles actions elle peut mettre en œuvre pour garder ou non le client.




#### La Base de Données :

L'ensemble de données comprend des informations sur :

    * les clients qui ont quitté l'entreprise au cours du dernier mois - la colonne s'appelle "Churn
    * Les services auxquels chaque client a souscrit : téléphone, lignes multiples, internet, sécurité en ligne, 
    sauvegarde en ligne, protection des appareils, assistance technique, télévision et films en streaming.
    * Informations sur le compte du client : ancienneté, contrat, mode de paiement, facturation dématérialisée, 
    frais mensuels et total des frais.
    * Informations démographiques sur les clients : sexe, tranche d'âge, partenaires et personnes à charge.


- Customer ID
- gender : Whether the customer is a male or a female
- SeniorCitizen : Whether the customer is a senior citizen or not (1, 0)
- Partner : Whether the customer has a partner or not (Yes, No)
- Dependents : Whether the customer has dependents or not (Yes, No)
- tenure : Number of months the customer has stayed with the company
- PhoneService : Whether the customer has a phone service or not (Yes, No)
- MultipleLines : Whether the customer has multiple lines or not (Yes, No, No phone service)
- InternetService : Customer’s internet service provider (DSL, Fiber optic, No)
- OnlineSecurity : Whether the customer has online security or not (Yes, No, No internet service)
- OnlineBackup : Whether the customer has online backup or not (Yes, No, No internet service)
- DeviceProtection : Whether the customer has device protection or not (Yes, No, No internet service)
- TechSupport : Whether the customer has tech support or not (Yes, No, No internet service)
- StreamingTV : Whether the customer has streaming TV or not (Yes, No, No internet service)
- StreamingMovies : Whether the customer has streaming movies or not (Yes, No, No internet service)
- Contract : The contract term of the customer (Month-to-month, One year, Two year)
- PaperlessBilling : Whether the customer has paperless billing or not (Yes, No)
- PaymentMethod : The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- MonthlyCharges : The amount charged to the customer monthly
- TotalCharges : The total amount charged to the customer
- Churn : Whether the customer churned or not (Yes or No)


- [lien vers la base de données](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)



#### Les conversions effectuées sur les variables : 







Bonus :

    


## Features
 ⚠️ - IN Progress


## Run the project Locally

Clone the project

```bash
git clone https://github.com/Noura-ou/Projet_Churn_Telco.git
````

Go to the project directory :

```bash
  cd my-project
```


## App streamlit

![ screanshot application streamlit](capture.png)

## Useful Documentation

- [Learning Curves IN Python SKlearn](https://vitalflux.com/learning-curves-explained-python-sklearn-example/)
- [Encodage et Normalisation](https://www.youtube.com/watch?v=OGWwzm304Xs&list=PLO_fdPEVlfKqMDNmCFzQISI2H_nJcEDJq&index=25) 
- [Bonus Piplines](https://www.youtube.com/watch?v=41mnga4ptso&list=PLO_fdPEVlfKqMDNmCFzQISI2H_nJcEDJq&index=26)
- [Les métriques de régression](https://www.youtube.com/watch?v=_TE9fDgtOaE&list=PLO_fdPEVlfKqMDNmCFzQISI2H_nJcEDJq&index=24)



## Authors

- [@noura-ou](https://github.com/Noura-ou)