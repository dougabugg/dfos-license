# Commercial Use
Generally, the following conditional chain can be used to determine if a particular use is considered "commercial" or not.

`def is_commercial:`
- if use involves copying, modifying or creating a derived work as some product: 
  - if there is only one party, the user themself:
    - return false; for private use, this license is not designed to restrict the user.
- else
  - if the use is just providing a mirror to help distribute a copy of the original:
    - return false; mirroring a copy for redistribution is non-commercial.
      one of the goals of this license is to encourage forking,
      and avoid restrictions on making the ecosystem more open and welcoming.
    - TODO finish me
