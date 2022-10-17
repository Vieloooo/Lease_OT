# Regional ontology for standard residential leases in Ontario 

## Parties 

### Landlord 

Data properties: 
- Legal name: 1 

### Tenant 

Data properties: 
- First name: 1 
- Last name: 1

## Rental Unit 

Data properties: 
- Address: 1
- Number of parking space: 1 
- If condo: 1
    - if the rental unit is a unit in a condo. If the rental unit is in a condo, then the tenant agrees to comply with the condominium declaration, by-laws and rules, as provided by the landlord. 

## Contact Information 

Data properties: 
- Landlord's address: 1 
    - address for give notice and documents to the landlord 
- notice email: some
    - both the landlord and tenant can provide emails to receive notices and documents
- landlord's contact email/phone: some 
    - contact for emergency or day-to-day communications. 


## Term 
This section regulate the start date of leases, and how long the lease will be effective. 

### Fixed term 
In fixed-term leases, the tenancy relationship is intended to last for only a specific and definite length of time.

Data properties: 
- Start date: 1 
- End date: 1 

### Periodic term 
A periodic-term leases continue on a perdiodic basis without a specified end date. 

Data properties: 
- Start date: 1 
- Periodic length: 1
    - periodic length indicates the periodic basis, like "weekly", "bi-weekly", "monthly", etc. 


## Rent 

Data properties: 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent
- Payment method: some
    - this defines the method that lessor accepted: like "cash", "check", "wire-transfer", etc. 
- Base rent:  1 
    - the base rent for this tenancy
- Total rent: 1 
    - the sum of all fees: including "Base rent", "service fee", etc. 
- Parking fee: 1
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Rent paid to: 1


Object proerties: 
- has other fee: some 
    - some services are not included in the rent, so in this section, the other services and its cost should be listed

## First payment 
If the first rental period is a partial period, the first payment need to be specified. 

Data properties: 
- Amount: 1 
    - amount paid by tenants to cover the first partial rental period
- Payment date: 1
- Covered start date: 1 
- Covered end date: 1 
- Administration charge: 1
    - If the tenant's cheque is returned becuase of non-sufficient funds(NSF), the tenant will have to pay the landlord's some adminstration charge. 

## Other fee 
Service that do not covered in rent. 

Data properties: 
- Fee name: 1 
    - the name of a service, like "parking", "internet", etc. 
- Amount: 1
    - the cost for this service

## Services and utilities 
This section declare the service included in rent and services borne by tenant(s)
Data properties: 
- Services name: some 
    - this element includes all services included in rent. 

## Rent discount

Data properties: 
- Description: 1

## Rent deposit 
A rent deposit is a deposit of a sum of money that the tenant puts down to hold the rental unit for them.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 


## Key deposit 
A key deposit is a sum of money a tenant gives a landlord to hold until the safe return of the key(s) to a rented space. Usually the key deposit should not be more than the cost of replacing the key(s). 

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 


## Smoking 
Additional smoking rules related to the rental unit. 

Data properties: 
- Smoking rules: some 

## Insurance

Data properties: 
- Insurance proof: 1

## Additional Terms 

- Additional document: 1