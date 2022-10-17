# Regional ontology for standard residential leases in Prince Edward 

## Parties 


Data properties: 
- Agreement date: 1 
- Lessor name: 1 
- Lessor address: 1
- Lessor teleNO: 1 
    - lessor's telephone number(s)
- Lessee name: min 1

## Premises 

Data properties: 
- Unit type: 1 
    - the type of the rental unit, like "condo", "townhouse", "detached house", etc. 
- Max number of occupants: 1 
- Address: 1
    - The address of the rental unit

Ojbect properties: 
- has "Superintendent of the Residential Premises": max 1 

## Superintendent of the Residential Premises

Data properties: 
- Name: 1 
- Address: 1
- Telephone number: min 1

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
- Payment reciever: 1
    - name of the rent reciever 
- Payment address: 1
    - Payment shall be delivered/mailed to this address

## Services and Facilities 

Data properties: 
- Services included in rent: some 
    - services included in rent 
- Services borne by lessee: some 
    - costs that tenant need to take responsbility

## Security deposit 


Data properties: 
- Deposit amount: 1
    - the amount should be paied by lessee(s). 
