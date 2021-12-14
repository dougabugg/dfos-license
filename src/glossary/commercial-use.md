# Commercial Use
Generally, the following conditional chain can be used to determine if a particular use
is considered "commercial" or not.

`def is_commercial:`
- if use involves copying, modifying or creating a derived work as some product: 
  - if the use of the product results in financial gain of a small group of private entities,
    - return true; if private entities are profitting (gaining finances) as a result of
      the product, then the use is not "non-profit", and the use is considered "commercial".
  - if there is only one party, the user themself:
    - return false; for private use, this license is not designed to restrict the user.
  - else if the number of parties exceeds 10_000 who interact with the product:
    - return true; above the arbitrarily chosen size of 10_000 parties/users, the usage
      is considered "commercial". 
- else
  - if the use is just providing a mirror to help distribute a copy of the original:
    - return false; mirroring a copy for redistribution is non-commercial.
      one of the goals of this license is to encourage forking,
      and avoid restrictions on making the ecosystem more open and welcoming.

NOTE: this definition is still under development.
