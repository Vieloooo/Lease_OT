# Regional ontology for standard residential leases in Manitoba 


## Landlord 

Data properties: 
- Legal name: 1 
- Address: 1
- Tele NO: 1 
    - telephone number 

## Tenant 

Data properties: 
- First name: exactly 1
- Last name: exactly 1

## Rental Unit 
Rental unit means a dwelling unit that is not owner-occupied and is rented or available to rent.

Data properties: 
- If condo: 1 
    - if the unit is registered as a condominium 
- Address: 1
    - The address of the rental unit

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

## Security deposit 
A security deposit is money that a landlord collects at the start of the tenancy and holds until the end of the tenancy to cover the costs of repairing or cleaning and other costs agreed to by the lessee(s) in the residential tenancy agreement, such as legal fees, utilities, late fees, etc.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 

## Pet damage deposit 
A landlord may also request a pet damage deposit at the start of a tenancy or during a tenancy if a tenant gets a pet with the landlord’s permission.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 

## Rent 

Data properties: 
- Base rent: 1
    - the base rent for this tenancy
- Rent payable: 1 
    - the sum of all fees: including "Base rent", "service fee", etc. 
- Discount amount: 1 
- Actual amount must pay: 1
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent


Object proerties: 
- has "Parking fee": max 1
- has "Other fee": some 
    - some services are not included in the rent, so in this section, the other services and its cost should be listed

## Parking fee 
Specified cost for parking 

Data properties: 
- Number of parking spaces: 1 
- Amount: 1
    - the cost of the these parking spaces per payment cycle. 

## Other fee 
Service that do not covered in rent. 

Data properties: 
- Cost detail: 1 
    - the name of a service, like "parking", "internet", etc. 
- Amount: 1
    - the cost for this service

## Service and Facilities 

Data properties: 
- Services tenants to pay: some 
    - services need to be paid by tenants themselves. 
- Services included in rent: some 
    - services covered in payable rent 

## Occupants of Rental Unit 

Data properties: 
- Name: some 
    - the names of people who can occupy the rental unit. 

## Furniture 
Furniture provided by the landlord.

Data properties: 
- Furniture item list: 1 
    - an itemized list of the furniture should be attached. 