# Regional ontology for standard residential leases in British Columbia 

## Parties 
Participants in the rental agreement 

### Landlord

A person who conveys the possession of a real estate under a lease.

Data properties: 
- First name: exactly 1
- Last name: exactly 1

### Tenant 

Data properties: 
- First name: exactly 1
- Last name: exactly 1
- Tenant's phone: some 

## Rental Unit 
Rental unit means a dwelling unit that is not owner-occupied and is rented or available to rent.

Data properties: 

- Address: 1
    - The address of the rental unit

## Service information 

- Service provider: 1
    - Usually service provider is "landlord" themself or "landlord's agent"
- Address for service: 1 
- Daytime phone: 1 
    - Service provider's phone number for contacting in daytime 
- Other phone: 1 
    - Other phone number of service provider 
- Service fax: 1 
    - fax number for service 


## Term 
This section regulate the start date of leases, and how long the lease will be effective. 

Data properties: 
- Start date: 1 
### Fixed term 
In fixed-term leases, the tenancy relationship is intended to last for only a specific and definite length of time.

Data properties: 
- End date: 1 

### Periodic term 
A periodic-term leases continue on a perdiodic basis without a specified end date. 

Data properties: 
- Periodic length: 1
    - periodic length indicates the periodic basis, like "weekly", "bi-weekly", "monthly", etc. 


## Rent 

Data properties: 

- Total rent: 1 
    - the sum of all fees: including "Base rent", "service fee", etc. 
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent
- Included in rent: some
    - this attributes contains all service/utilities/furniture covered in rent, like "heat", "water", "electricity", etc. 

## Security/damage deposit 
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

## Additional Terms 
Additional terms agreed by landlord and tenant should be listed in the standard lease form

Data properties: 
- Attached document: 1
- Number of pages: 1
    - Number of pages of the Addendum
- Number of additional terms: 1 
    
