1) A landlord can rent out a separate apartment, the whole building or several apartments to another party. 
    while the apartment has id, flat number, has 1:M relationship 
2) A landlord can sign a rental contract with one or multiple tenants.
3) One tenant can rent multiple apartments from the same landlord.
4) One tenant can rent multiple apartments simultaneously.
5) A landlord can also be a tenant of another landlord.


The landlord has attributes like name, id.

The Tenant has attributes like id, name, family status

The Apartment has attributes like id, size, flat number, furnished typed

The Building has attributes like name, address

A landlord can own multiple apartments. 
Each of these apartment belong to either the same building or different building.
Hence a building consists of multiple apartment which is shown by 1:M relationship.

The landlord can have multiple contract with different tenants 
and a tenant can sign a contract with multiple
landlords. Hence there is a M:M relationship between them.

Lastly, as the landlord can themselves be a landlord, this is depicted by a self relation.
 