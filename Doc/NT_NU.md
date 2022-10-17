# Regional ontology for standard residential leases in North territory and Nuvaut

## Landlord 

A person who conveys the possession of a real estate under a lease.

Data properties: 
- Name: 1
- Phone number: 1

## Tenant 

A tenant is a person who takes temporary possession of a lessor's property (dwelling) through a lease 

Data properties: 
- Name: min 1
- Phone number: min 1

## Premises 

Data properties: 
- Address: 1 


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
- Total rent: 1 
    - The actual amount of money that lessee(s) need to pay the lessor. Total rent = the sum of all fees: including "Base rent", "service fee", etc, while sub the discount amount. 
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent


Object proerties: 
- has other fee: some 
    - some services are not included in the rent, so in this section, the other services and its cost should be listed

## Other fee 
Service that do not covered in rent. 

Data properties: 
- Fee name: 1 
    - the name of a service, like "parking", "internet", etc. 
- Amount: 1
    - the cost for this service


## Services and Facilities 

Data properties: 
- Included in rent: some 
    - services included in rent 
- Paid by the tenant: some 
    - costs that tenant need to take responsbility

## Security deposit 
A security deposit is money that a landlord collects at the start of the tenancy and holds until the end of the tenancy to cover the costs of repairing or cleaning and other costs agreed to by the lessee(s) in the residential tenancy agreement, such as legal fees, utilities, late fees, etc.

Data properties: 
- Total Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Prepaid amount: 1
- Prepaid percentage: 1
- Prepaid date: 1 
- Remained amount: 1
- Remained percentage: 1
- Remained date: 1 

## Pet security deposit 
A landlord may also request a pet security deposit at the start of a tenancy or during a tenancy if a tenant gets a pet with the landlord’s permission.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 

## Landlord's obligations to maintain premises

Data proerties: 
- Clauses of obligation: some 

## Additional obligations 
Additional obligations for 2 parties

Data properties: 
- Tenant's obligations: some 
- Landlord's obligations: some  
## Occupants 

Data properties: 
- Max number of occupants: 1 

## Serive of Documents and Notices

Data properties: 
- Landlord's address: 1 
- Landlord's email: some 
- Landlord's phone: some 
- Tenant's address: 1 
- Tenant's email: some 
- Tenant's phone: some 