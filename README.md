# Open Data DiscoTech - Privacy
**Primary Topics of Considerations**
- Individual and Group Privacy
- Right to be Forgotten and Privacy Bots
- Privacy concerns of Related Data Sets (Function Creep)

**Relational aspects of privacy**
So far privacy is thought of as an individual-based concept: what does this data reveal about this individual, what risks ensue when the `wrong' entities access it, etc.
But some aspects of privacy are communal: data about one individual reveals something about other individuals or communities. Examples include genetic data, location data, and immigration status. We call this communal privacy.
Moreover, it may be that data X is shareable because. But when combined with data Y, it constitutes an undue invasion of privacy for the individual. 
Examples include multi-modal transit data, which allows to reconstruct entire tripts to doctors' offices, businesses, etc. We call this disaggregative privacy.

So when the city is considering how to set access levels and sensitivity-of-data ratings for the data that it curates or collects or stores, it ought to consider the above two relational aspects.

**Privacy Challenge**
In the context of the privacy challenge question 3 ("a laptop gets stolen"), this means that a network analysis ought to be done to understand who else's privacy is now vulnerable, and who has been the victim of a previous data breach. 
This is a tall order, technologically, and seems to require city tracking of data events (e.g., breaches) beyond what it currently does or perhaps it is equipped to do; and of course, once one entity (the City, say) has obtained such a profile about data breaches affecting one individual, then that information itself needs protection. But this is not necessarily all-or-nothing: there may be incremental steps that can be taken which considerably enhance protection at little increased risk.

Implementing remote wiping of data is possible today. So is the implementation of restricted APIs for accessing data (with a caveat to the fact that every software can hide bugs). A practical issue is the maintenance of that software, making sure it functions correctly, ability to do (light) troubleshooting, etc. Some of us felt that the city ought to have a resident security expert(s) who is responsible for it - whether they be a developer or someone who knows who to hire and maintain the code base or the third-party software. Such a person (or persons) ought to have minimally conflicting charters, so privacy and security are not made subordinate to other considerations like economic development (important as those other considerations might be).
