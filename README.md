# R2RML Parser

An R2RML implementation that can export relational database contents as RDF graphs, based on an [R2RML](http://www.w3.org/TR/r2rml/) mapping document. Contains an R2RML [mapping document](https://github.com/nkons/r2rml-parser/blob/master/dspace/dspace-mapping.rdf) for the [DSpace](http://www.dspace.org/) institutional repository solution.

For more information, please [visit the wiki](https://github.com/nkons/r2rml-parser/wiki).

Please send any feedback/questions by email to [nkons@live.com](mailto:nkons@live.com), by direct message (dm) via twitter to [@nkonstantinou](https://twitter.com/nkonstantinou), or ["open an issue"](https://github.com/nkons/r2rml-parser/issues). We'll be happy to discuss how to export your data into RDF.

## Implementation details

R2RML implementation written fully in Java 7, using Apache Jena 2.11, Spring 4.0, JUnit 4.9, and Maven 3.1. Tested against MySQL 5.6, PostgreSQL 9.2 and Oracle 11g.

## Licence

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 Unported License.

http://creativecommons.org/licenses/by-nc/4.0/

You are free to use and distribute this work as long as you provide proper reference and respect the license terms.

## Publications

1. N. Konstantinou, D.E. Spanos: ["Creating Linked Data from Relational Databases"](http://dx.doi.org/10.1007/978-3-319-16074-0_4). In Book ["Materializing the Web of Linked Data"](http://www.springer.com/gp/book/9783319160733), Pages 73-102, Springer, 2015

1. N. Konstantinou, D.E. Spanos, D. Kouis, N. Mitrou: ["An Approach for the Incremental Export of Relational Databases into RDF Graphs"](https://www.researchgate.net/publication/275251864_An_Approach_for_the_Incremental_Export_of_Relational_Databases_into_RDF_Graphs), In International Journal on Artificial Intelligence Tools, 24 (2), 2015 [(doi:10.1142/S0218213015400138)](http://dx.doi.org/10.1142/S0218213015400138)

1. N. Konstantinou, D. Kouis, N. Mitrou: ["Incremental Export of Relational Database Contents into RDF Graphs"](https://www.researchgate.net/publication/262098563_Incremental_Export_of_Relational_Database_Contents_into_RDF_Graphs). In 4th International Conference on Web Intelligence, Mining and Semantics (WIMS'14), Thessaloniki, Greece, June 2014 [(doi:10.1145/2611040.2611082)](http://dx.doi.org/10.1145/2611040.2611082) [(fulltext)](http://people.cn.ntua.gr/nkons/papers/74-Konstantinou-updated.pdf) [(slides)](http://www.slideshare.net/nkons/wims14-v2)

1. N. Konstantinou, D.E. Spanos, N. Houssos, N. Mitrou: ["Exposing Scholarly Information as Linked Open Data: RDFizing DSpace contents"](https://www.researchgate.net/publication/236881378_Exposing_Scholarly_Information_as_Linked_Open_Data_RDFizing_DSpace_contents). In The Electronic Library, Vol. 32, No. 6, 2014 [(doi:10.1108/EL-12-2012-0156)](http://dx.doi.org/10.1108/EL-12-2012-0156) [(fulltext)](http://people.cn.ntua.gr/nkons/papers/r2rml_parser-2014_post_peer-review.pdf)

1. N. Konstantinou, D.E. Spanos, N. Mitrou: ["Transient and persistent RDF views over relational databases in the context of digital repositories"](https://www.researchgate.net/publication/258235039_Transient_and_persistent_RDF_views_over_relational_databases_in_the_context_of_digital_repositories). In 7th Metadata and Semantics Research Conference (MTSR'13), Thessaloniki, Greece, Springer, CCIS 390, pp. 342-354, November 2013 [(doi:10.1007/978-3-319-03437-9_33)](http://dx.doi.org/10.1007/978-3-319-03437-9_33) [(fulltext)](http://people.cn.ntua.gr/nkons/papers/mtsr13.pdf) [(slides)](http://www.slideshare.net/nkons/transient-and-persistent-rdf-views-over-relational-databases-in-the-context-of-digital-repositories) [(datasets)](http://people.cn.ntua.gr/nkons/13-mtsr/)

1. N. Konstantinou, N. Houssos, A. Manta: ["Exposing Bibliographic Information as Linked Open Data using Standards-based Mappings: Methodology and Results"](https://www.researchgate.net/publication/256691164_Exposing_Bibliographic_Information_as_Linked_Open_Data_using_Standards-based_Mappings_Methodology_and_Results). In 3rd International Conference on Integrated Information (IC-ININFO'13), Prague, Czech Republic, September 2013 [(fulltext)](http://people.cn.ntua.gr/nkons/papers/nkons-nhoussos-amanta-camera-ready.pdf) [(slides)](http://www.slideshare.net/nkons/exposing-bibliographic-information-as-linked-open-data-using-standardsbased-mappings-methodology-and-results)
