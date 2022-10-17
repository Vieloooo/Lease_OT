# Regional ontology for standard residential leases in Nova Scotia 

## Parties 
Participants in the rental agreement 

### Landlord

A person who conveys the possession of a real estate under a lease.

Data properties: 
- Name: 1 
- Address: 1
- Phone(home): 1
- Phone(other): 1

### Tenant 

Data properties: 
- First name: exactly 1
- Last name: exactly 1

## Other occupants 
Other adults or children will occupy premises 

Data properties: 
- Name: some 

## Premises 

Data properties: 
- Type: 1 
    - the type of the rental unit, like "condo", "townhouse", "detached house", etc. 
- Address: 1
    - The address of the rental unit
- Tenant's mailing address: 1 
- Tenant's phone(home): 1
- Tenant's phone(other): 1

## Emergency contact 
The tenant should provide an emergency contact. It is ideal if the emergency contact is local, but this is not required.

Data properties: 
- Name: 1 
- Address: 1
- Phone(home): 1
- Phone(other): 1

## Landlord agent 

Data properties: 
- Name: 1 
- Address: 1
- Phone(home): 1
- Phone(other): 1

## Building Superintendent
current superintendent of the rental unit 
Data properties: 
- Name: 1 
- Address: 1
- Phone(home): 1
- Phone(other): 1

## Tenant's E-address 
Landlords and tenants may agree to provide electronic addresses to receive service of documents.

Data properties: 
- E-address: some 

## Landlord's E-address 
Landlords and tenants may agree to provide electronic addresses to receive service of documents.

Data properties: 
- E-address: max 1 


## Lease Type  
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
- Payment method: some
    - this defines the method that lessor accepted: like "cash", "check", "wire-transfer", etc. 
- Payable to: 1 

## Rent include 

Data properties: 
- Rent includes: some 
    - services included in rent 
- Services for tenant: some 
    - costs that tenant need to take responsbility

## Security deposit 
A security deposit is money that a landlord collects at the start of the tenancy and holds until the end of the tenancy to cover the costs of repairing or cleaning and other costs agreed to by the lessee(s) in the residential tenancy agreement, such as legal fees, utilities, late fees, etc.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 