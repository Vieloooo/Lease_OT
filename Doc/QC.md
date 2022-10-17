# Regional ontology for standard residential leases in Quebec 

## Lessor

A person who conveys the possession of a real estate under a lease.

Data properties: 
- Name: 1 
- Address: 1
    - lessor's address for notice and communication 
- Email: some
- Phone: some
    - phone number which includes telephone number and cellular


## Lessee

A lessee is a person who takes temporary possession of a lessor's property (dwelling) through a lease 

Data properties: 
- Name: 1 
- Address: 1
    - lessor's address for notice and communication 
- Email: some
- Phone: some
    - phone number which includes telephone number and cellular

## Description of leased dwelling 

Data properties: 
- Address: 1
    - The address of the rental unit
- Unit purpose: min 1 
- If co-ownership: 1 
- Applicance and furniture: some
    - applicance and furniture contained in the leases, which are covered in the rent 
- Accessory: some 
    - accessory to the rental unit, like "locker", "indoor parking space", "outdoor parking space", etc. 


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
- Base rent: max 1 
    - the base rent for this tenancy
- Total cost of services: 1 
- Total rent: 1 
    - The actual amount of money that lessee(s) need to pay the lessor. Total rent = the sum of all fees: including "Base rent", "service fee", etc, while sub the discount amount. 
- First payment date: 1
- Payment cycle: 1 
    - defines the periodicity and frequency of tenant payments, like "weekly", "bi-weekly", "monthly", etc. 
- Exact date: 1 
    - this defines on which day of the payment period the lessees pay the rent
- Payment method: some
    - this defines the method that lessor accepted: like "cash", "check", "wire-transfer", etc. 
- Payment places: 1

## Services and Conditions 

Data properties: 
- Repairs before delivery: some
- Repairs during the lease

Object properties: 

- has "service responsibility": some 
- has "Janitorial service contact": max 1 

## Service responsibility

Data properties: 
- Service name: 1 
- Whose responsbility: 1 
    - who should be reponsible to this service, lessor or lessee

## Janitorial service contact 

Data properties: 
- Name: 1 
- Telephone No.: max 1 
- Cell phone: max 1 
- Email: max 1 