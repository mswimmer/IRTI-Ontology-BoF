## Welcome to The FIRST Incident Response and Threat Intelligence Ontology BoF page ##

> How to express facts in the threat intelligence and incident response domain.

### Mission

The mission of the Birds of a Feather group, founded at the [29th FIRST Conference](https://www.first.org/conference/2017/) in San Juan, Puerto Rico held in June 2017, is to flesh out the idea of an industry standard ontology for Threat Intelligence and Incidence Response data. While the initiative is spearheaded by Martin Eian and Morton Swimmer, we welcome all contributors to the discussion and possible coding. After an initial discussion and fleshing out of use-cases, etc., we will need to decide how to move forward to make it a standard.

Our aim is to elevate the current practice from mere data exchange to actionable knowledge exchange. While we have a number of file formats with which to exchange data, these formats do not define the semantics well enough to ensure that the data producer understands how to properly express his/her data and the consumer therefore needs to re-interpret all incoming data, often forced to guess how it has been produced.

The aim is to produce an ontology for Threat Intelligence and Incident Response information that can be used in multiple ways. An ontology can be used to specify how labels are being used in an existing information exchange document or database. Threat information can also be specified 'natively', independent of any format, by reusing [W3C RDF](https://www.w3.org/RDF/) as a data model, which is a set of subject-predicate-object triple relationship, and one of the serialization formats (RDF-XML, N3, Turtle) to express the information. For the ontology itself, [W3C's OWL](https://www.w3.org/OWL/) ontology language will be used. Lastly, given the ontology and the data expressed in RDF, Description Logics reasoning can be used to infer new information, or check for consistency.

The triple form of semantic information lends itself to implementation in graph databases, which is becoming popular now, and this ontology can leed to better and more consistent implementations of such graph databases.

Furthermore, using reification of individual triples or subgraphs of the semantic data model, the tactical information can be mapped to strategic goals.

We will not be addressing data quality or confidence issues. We also don't need to address data format issues as we intend to reuse the W3C RDF model or map the ontology to data or database fields.

### Prior Art

This project is inspired by the ongoing [TOSCA](http://www.mn.uio.no/ifi/english/research/projects/tocsa/) project and we anticipate working closely with that team.

## Over the years, there have been a number of papers and projects on security (or related) ontologies:

* Stefan Fenz, Andreas Ekelhart, Thomas Neubauer, et al 2009: [Ontology-based Decision Support for Information Security Risk Management](http://www.sba-research.org/wp-content/uploads/publications/2009%20-%20Ekelhart%20-%20Ontology-based%20Decision%20Support%20for%20Information%20Security%20Risk%20Management.pdf).

* Wang et al 2009: [Security Data Mining in an Ontology for Vulnerability Management](http://www.inf.furb.br/~paulofernando/downloads/ontologia-security/ontology%20vulnerability%20management.pdf).

* Bromander et al 2016: [Semantic Cyberthreat Modelling](http://stids.c4i.gmu.edu/papers/STIDSPapers/STIDS2016_A2_BromanderJosangEian.pdf) (AKA TOSCA)

* Zareen Syed, Ankur Padia, Tim Finin, Lisa Mathews and Anupam Joshi, [UCO: Unified Cybersecurity Ontology](http://ebiq.org/p/722), AAAI Workshop on Artificial Intelligence for Cyber Security, February 2016, <https://github.com/Ebiquity/Unified-Cybersecurity-Ontology>, Ontology URI: <http://ffrdc.ebiquity.umbc.edu/ns/ontology/> (AKA the Unified Cybersecurity Ontology (UCO))

* Eoghan Casey, Greg Back, Sean Barnum, [Leveraging CybOX to Standardize Representation and Exchange of Digital Forensic Information](https://www.dfrws.org/sites/default/files/session-files/pres-leveraging_cybox_to_standardize_representation_and_exchange_of_digital_forensic_information.pdf), 2015, (AKA the Unified Cyber Ontology.)

* Kim, A., Luo, J., Kang, M.: [Security Ontology for Annotating Resources](https://pdfs.semanticscholar.org/52d4/8a132aa6f0a5169d5a6422c7d8335a47ee90.pdf). Naval Research Laboratory, Report No. NRL/MR/5542-05-8903 ( 2005) 3 (AKA the NRL Security Ontology)

* Daniel L. Costa, Michael J. Albrethsen, Matthew L. Collins, Samuel J. Perl, George J. Silowash, Derrick L. Spooner, [An Insider Threat Indicator Ontology](https://resources.sei.cmu.edu/asset_files/TechnicalReport/2016_005_001_454627.pdf), May 2016, CMU/SEI-2016-TR-007 

* Asgarli, E. and Burger, E., [Symantic Ontologies for Cyber Threat Sharing Standards](https://georgetown.box.com/s/o36u2pkejvuijicji5g7fkuobpyrvv1t), 2016 IEEE International Symposium on Technologies for Homeland Security (HST 2016), 10 May 2016.

* Burger, E., Goodman, M., Kampanakis, P., and Zhu, K., [Taxonomy Model for Cyber Threat Intelligence Information Exchange Technologies](https://georgetown.box.com/s/cfap21dxmsgr4k9hnipu), First ACM Workshop on Information Sharing and Collaborative Security (WISCS 2014), 3 November 2014.

* Burger, Eric, [A Taxonomy for CyberISE Technology Evaluation](https://s2erc.georgetown.edu/sites/s2erc/files/CyberISE%20Taxonomy.pdf), 17 February 2014.

* Swimmer, IRTI, 2017 <https://github.com/mswimmer/IRTI-Ontology> (An experimental ontology being built for working with infrastructure and threat data.)

* Swimmer, HTTP, 2013 <https://github.com/mswimmer/HTTP-Ontology> (An experimental ontology for describing HTTP entities.)

* Swimmer, Malware, 2004 <http://www.purl.org/malware> (An old taxonomy for describing Malware properties.)


## Ontology-like documents and other resources:

* MITRE, Common Attack Pattern Enumeration and Classification (CAPEC), https://capec.mitre.org/

* S. Barnum, Standardizing cyber threat intelligence information with the Structured Threat Information eXpression (STIX), MITRE Corporation, vol. 11, 2012.

* MITRE, Adversarial Tactics, Techniques and Common Knowledge (ATT&CK), <https://attack.mitre.org/>.

* Ryan Stillions, Detection Maturity Model, <http://ryanstillions.blogspot.de/2014/04/the-dml-model_21.html>

* Mandiant, Open Framework for Sharing Threat Intelligence, <http://openioc.org>

* OMG, Threat Modeling, <http://www.omg.org/hot-topics/threat-modeling.htm>

* IETF SACM Terminology, <https://datatracker.ietf.org/doc/draft-ietf-sacm-terminology/>

## Useful conferences

http://dfrws.org

ACM WISC (part of SIGSAC)

### Use cases

### Planned events

Vocamps, etc

Ontology engineering workshops

PoC


### Who to interface with

Vendors, tools, etc.


### Next steps

