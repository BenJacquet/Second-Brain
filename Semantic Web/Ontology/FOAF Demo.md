First of all, we need to create our RDF file:
```sh
touch benjaminjacquet.rdf
```

We add the metadata:
```XML
<?xml version="1.0" encoding="UTF-8"?>
```

Now we need to import our ontologies:
```XML
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
    xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
    xmlns:foaf="http://xmlns.com/foaf/0.1/"
    xmlns:bio="http://purl.org/vocab/bio/0.1/"
    xmlns:dc="http://purl.org/dc/terms/"
    xmlns:lang="http://purl.org/net/inkel/rdf/schemas/lang/1.1#"
    xmlns:geo="http://www.w3.org/2003/01/geo/wgs84_pos#"
    xmlns:doac="http://ramonantonio.net/doac/0.1/"
    xmlns:menow="http://schema.peoplesdns.com/menow/"
    xmlns:sioc="http://rdfs.org/sioc/ns#"
    xmlns:owl="http://www.w3.org/2002/07/owl#"
    xmlns:admin="http://webns.net/mvcb/"
    xmlns:rel="http://purl.org/vocab/relationship/">
```

**Note that even though we don't use all the ontologies, we still need to import all of them as they use each other**.

We can now describe our Person element:
``` XML
<foaf:Person rdf:ID="me">
<foaf:name>Benjamin Jacquet</foaf:name>
<foaf:title>Mr</foaf:title>
<foaf:givenname>Benjamin</foaf:givenname>
<foaf:family_name>Jacquet</foaf:family_name>
<foaf:nick>ben</foaf:nick>
<foaf:gender>male</foaf:gender>
<foaf:mbox rdf:resource="mailto:benjamin.jacquet@keiken-digital.com"/>
<foaf:homepage rdf:resource="https://benjacquet.com"/>
<foaf:phone rdf:resource="tel:0602264530"/>
<foaf:knows>
	<foaf:Person>
		<foaf:name>Hamza</foaf:name>
		<foaf:mbox rdf:resource="mailto:hamza@keiken-digital.com"/>
	</foaf:Person>
</foaf:knows>
<foaf:knows>
	<foaf:Person>
		<foaf:name>Ismail</foaf:name>
		<foaf:mbox rdf:resource="mailto:Ismail@keiken-digital.com"/>
	</foaf:Person>
</foaf:knows>
<foaf:interest rdf:resource="http://dbpedia.org/page/Video_game"/>
</foaf:Person>
```

Here it is, our RDF self !

We can then use SPARQL queries to find specific data in this RDF data.
I recommend this tutorial to find more information on this subject:
https://web-semantique.developpez.com/tutoriels/jena/arq/introduction-sparql/