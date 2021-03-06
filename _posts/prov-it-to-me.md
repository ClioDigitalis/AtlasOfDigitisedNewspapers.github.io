---
layout: post
title: PROV It to Me
subtitle: Incorporating Provenance  and Crowdsourced Metadata into Digitised Newspaper Collections
authors: Maud Ehrmann, Marie Léger-St-Jean, Abigail Rieley, Valeria Vitale and Ivo Zandhuis
---

Collections come together over time; digital collections come out of physical collections. It would therefore be useful for metadata to include an archaeology of the document’s existence—in this case, that of the newspaper. The W3C’s provenance ontology PROV-O could be a starting point.

### Metadata can come from both professionals and machines

Let’s start by taking a wide view of metadata: it can be both about the documents—such as a newspaper title, in which case metadata will correspond to document-item information—or about its contents, information obtained through content analysis, including natural language processing or NLP.

In both cases, information and the way it was produced will be different. For example, document-item information is typically gathered manually while content-related metadata is usually obtained automatically, affecting the style in which it is recorded. While metadata produced by humans and machines can be equally perfect or imperfect, the processes undertaken are established by different people and communities. Nonetheless, in both cases, the need for documenting provenance remains.

### Metadata tells us about more than just the item it describes

<img src="https://cdn.pixabay.com/photo/2017/06/28/10/23/binary-2450188_1280.jpg" style="float: left; padding: 7px 10px 0px 0px;" width="33%">  
Provenance data are not simply about the collection to which newspapers belong or who has donated them. Metadata can also carry contextual information about themselves, which can help shed further light on the related item or enable more meaningful research questions on digital interfaces. For example, attributes that distinguish between human- and machine-generated metadata of a similar nature—such as manual annotations and Named Entity Recognition or NER—should be transparent and easily accessible. As usual, the persistence, sustainability and interoperability—syntactic and semantic—of these attributes are key.

### The provenance of the metadata itself must be documented

No data is a given; it always needs a source. This can be the physical object being catalogued itself or inferences made by someone at a certain time and place. That’s why it’s important to record the meta information about the metadata, with the date and background of the person who created that specific metadata, to give a sense of where they were coming from. It could help contextualize inherited, pre-standardization metadata.

If an algorithm has been used to create metadata (at any level), the algorithm itself should be documented, so that it could be retro-engineered or corrected. Creators of metadata, humans or computers performing an analysis, affect the data. Human experience (time, culture, field of study, whims and attitude of the moment) will always color the work that is being done, such as the focus or style. In contrast, computer algorithms do what they are programmed to do, by humans with their own experiences. Which is more useful? Human insight or gathered, supported knowledge?

### What to do with metadata generated by individual scholars and crowd-sourcing

Scholars often create provenance or other types of metadata that provides a new perspective or is better for a given task within the subject they are investigating. This metadata could be given to the library, stored and made accessible within the interface.

If the library is unable to insert this metadata in their system, a scholar can publish the data—for instance on figshare. In order for it to be usable, a durable relation (such as a DOI or other permanent URI) must be instituted with the original object. Users of this data could then combine data sources based on this link. As we move towards a more collaborative approach, we may see in the future libraries and cultural institutions leverage volunteers or academics to produce semantic annotations on web resources that can be fed to the catalogue.

So, our first appeal to the libraries would be: please publish URIs for the entities in your system.

*This blog is the product of a 40-minute collaborative writing session held via Zoom as part of the Exploring the Atlas of Digitised Newspapers and Metadata Workshop, held 19 August 2020. The editors of this site would like to thank the authors for their contribution to our ongoing conversation around the future of digitised newspaper collections.*
 
 
