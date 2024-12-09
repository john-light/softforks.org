---
name: New soft fork use case content
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

Want to add new content to softforks.org? There are only two rules:

1. It must be relevant to an active bitcoin soft fork proposal.
2. It should only **add** content, it should not **delete** content. Some exceptions may be made for editing or if the factual accuracy of existing content is in question. Feel free to create an issue to discuss.

Also feel free to add or remove anything below that you do or do not need. If you want to add content for more than one soft fork or use case, please open a different issue for each so they can be evaluated independently.

## New use case content

Add any new content for a soft fork use case, either editing one of the existing pages or adding a new page for a use case that isn't listed yet. If you are adding a new use case that is not listed yet, the use case must have at least one documented user (an individual, company, or project who has made a credible claim that they will leverage this use case if the soft fork is activated). Theoretical use cases that are clearly documented, such as in a research paper that makes use of a soft fork, are also acceptable.

- Soft forks: List of soft forks that enable the given use case  
- Enables new MEVil: Boolean value of "0" for "Does not enable new MEVil" or "1" for "Does enable new MEVil". This is an admittedly coarse ranking, but any nuances such as how severe the MEVil may theoretically be in the worst case are intended to be captured in the "New MEVil details" (see below).  
- Throughput multiple: The theoretical maximum throughput multiple over existing L1 transactions enabled by the given soft fork. This should only be given for use cases that have trust assumptions no worse than the Lightning Network i.e. users retain self-custody and unilateral exit capabilities as long as they can get a transaction confirmed on L1 within some reasonable amount of time.  
- Users: List of individuals, companies, or projects that have publicly stated their intent to use a soft fork for the given use case.  
- Description: A description of the use case and how it makes use of the soft forks referenced. Usually these descriptions are pulled from external sources, which are then cited below the quoted description. If no good description exists, you are encouraged to publish it yourself then cite it here, or you can publish the description directly in this issue.  
- New MEVil details: A description of how the given use case enables new [MEVil](https://bluematt.bitcoin.ninja/2024/04/16/stop-calling-it-mev/). The more details and nuance the better.  
- Throughput multiple details: An explanation of how the given theoretical maximum throughput multiple for the given use case is obtained. Show your work, or link to an external source that shows the work.
