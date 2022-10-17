# Regional ontology for standard residential leases in New Brunswick 

## Landlord 

A person who conveys the possession of a real estate under a lease.

Data properties: 
- First name:  1
- Last name:  1
- Address:  1
    - lessor's address for notice and communication 
- Email: some
- Tele No: some
    - phone number which includes telephone number and cellular
- Fax: some 

## Tenant 

A tenant is a person who takes temporary possession of a lessor's property (dwelling) through a lease 

Data properties: 
- First name:  1
- Last name:  1
- Email: some
- Tele No: some
    - phone number which includes telephone number and cellular
- Fax: some 

## Premises 

Data properties: 
- Type: 1 
    - the type of the rental unit, like "condo", "townhouse", "detached house", etc. 
- Address: 1
    - The address of the premises

- Smoking restrictions: some 
    - specify if some portions of premises are smoke-free 
- Pet restrictions: some 
    - restrictions related to pets. 

## Length of the tenancy  
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
    - The actual amount of money that lessee(s) need to pay the lessor. Total rent = the sum of all fees: including "Base rent", "service fee", etc, while sub the discount amount. 
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent
- Payment method: some
    - this defines the method that lessor accepted: like "cash", "check", "wire-transfer", etc. 
- First payment due date: 1 
- Paid to: 1 
    - if the rent is paid to landlord directly or landlord's agent. 
- Service covered: some
    - this attributes contains all service and frunitures covered in rent, like "heat", "water", "electricity", etc. 


## Security deposit 
A security deposit is money that a landlord collects at the start of the tenancy and holds until the end of the tenancy to cover the costs of repairing or cleaning and other costs agreed to by the lessee(s) in the residential tenancy agreement, such as legal fees, utilities, late fees, etc.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by tenant(s). 
