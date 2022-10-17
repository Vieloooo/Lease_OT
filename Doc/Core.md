# Core ontology for residential leases

## Lessor

A person who conveys the possession of a real estate under a lease.

Data properties: 
- First name: exactly 1
- Last name: exactly 1
- Address: exactly 1
    - lessor's address for notice and communication 
- Email: some
- Tele No: some
    - phone number which includes telephone number and cellular
- Fax: some 

## Lessee

A lessee is a person who takes temporary possession of a lessor's property (dwelling) through a lease 

Data properties: 
- First name: exactly 1
- Last name: exactly 1
- Email: some
- Tele No: some
    - phone number which includes telephone number and cellular

## Rental Unit 
Rental unit means a dwelling unit that is not owner-occupied and is rented or available to rent.

Data properties: 
- Type: max 1 
    - the type of the rental unit, like "condo", "townhouse", "detached house", etc. 
- Applicance and furniture: some
    - applicance and furniture contained in the leases, which are covered in the rent 
- Accessory: some 
    - accessory to the rental unit, like "locker", "indoor parking space", "outdoor parking space", etc. 
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

## Rent 

Data properties: 
- Base rent: max 1 
    - the base rent for this tenancy
- Total rent: 1 
    - The actual amount of money that lessee(s) need to pay the lessor. Total rent = the sum of all fees: including "Base rent", "service fee", etc, while sub the discount amount. 
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent
- Payment method: some
    - this defines the method that lessor accepted: like "cash", "check", "wire-transfer", etc. 
- Service covered: some
    - this attributes contains all service covered in rent, like "heat", "water", "electricity", etc. 

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

## Deposit 
Deposit refers to the money paid by a tenant to a landlord who have entered into a rental agreement. 

### Key deposit 
A key deposit is a sum of money a tenant gives a landlord to hold until the safe return of the key(s) to a rented space. Usually the key deposit should not be more than the cost of replacing the key(s). 

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 

### Rent deposit 
A rent deposit is a deposit of a sum of money that the tenant puts down to hold the rental unit for them.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 

### Security/damage deposit 
A security deposit is money that a landlord collects at the start of the tenancy and holds until the end of the tenancy to cover the costs of repairing or cleaning and other costs agreed to by the lessee(s) in the residential tenancy agreement, such as legal fees, utilities, late fees, etc.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 

### Pet damage deposit 
A landlord may also request a pet damage deposit at the start of a tenancy or during a tenancy if a tenant gets a pet with the landlord’s permission.

Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
- Due date: 
    - lessee(s) must pay the deposit before the due date. 