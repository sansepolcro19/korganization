@base <https://sansepolcro19.github.io/>.
@prefix dcterms: <http://purl.org/dc/terms/> .
@prefix schema: <https://schema.org/> .
@prefix dbp: <http://dbpedia.org/resource/> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix mus: <http://data.doremus.org/ontology>.
@prefix crm: <http://www.cidoc-crm.org/>.    
@prefix bibo: <http://purl.org/ontology/bibo/>.
@prefix agr: <https://promsns.org/def/agr/agr.html>.
@prefix mo:<http://musicontology.com/specification/>.
@prefix foaf:<http://xmlns.com/foaf/spec/>.
@prefix cwdm:<https://www.getty.edu/research/publications/electronic_publications/cdwa/categories.html#list/> .



# PERIOD
<period/Sansepolcrism> a <crm:E4_Period>;
            <dcterms:title> <event/Sansepolcrism> ;
            <crm:P7_took_place_at> <place/Milano> .
             
# PERSON
<person/Mussolini> a <foaf:Person> ;
<schema:subjectOf> <items/MussoliniSpeaks> .

# PLACE
<place/Milano> a <crm:E53_Place> .
	

# BOOK 
<items/ReflectionsOnViolence>  a <schema:book> ;
              <dcterms:title> <items/Reflections_on_Violence>;
              <dcterms:language>"en";              
              <schema:isbn><978-1-2754-6767-5> ;
              <schema:datePublished> "1915";
              <schema:subject> "Strikes and lockouts, Syndacalism, Social Conflict" ;
              <schema:author> <persons/Georges_Sorel>;
              <crm:P15_was_influenced_by> <period/Sansepolcrism> .



# SONG
<items/Giovinezza> a <mo:Track>;
            <mo:Genre> "Hymn";
            <mo:composer> <persons/Giuseppe_Blanc>;
            <mo:artist> <persons/Salvatore_Gotta>;
            <mo:duration> "3 min 57 s";
            <dcterms:title> "Giovinezza";
            <dcterms:language> "it";
            <schema:datePublished> "1909";
            <crm:P138_represents> <period/Sansepolcrism> . 

# MOVIE

<items/LaMarciaSuRoma> a <dbo:movie>;
            <schema:director> "Dino Risi";
            <schema:actor> "Vittorio Gassman";
            <schema:actor> "Ugo Tognazzi";
            <schema:actor> "Roger Hanin"; 
            <schema:contentLocation> "Milan Rome";
            <schema:datePublished> "December 20, 1962";
            <schema:genre> "Comedy"; 
            <schema:duration> "1 h 34 min";
            <dcterms:language> "it";
            <dcterms:title> "La Marcia su Roma" ;
            <schema:isBasedOn> <period/Sansepolcrism> .

# DOCUMENTARY

<items/MussoliniSpeaks> a <crm:E12_Production>;
            <schema:director> "Edgar G. Ulmer";
            <schema:actor> "Lowell Thomas";
            <schema:contentLocation> "Italy  Rome";
            <schema:datePublished> "March 10, 1933";
            <schema:genre> "Documentary Biography Historic";
            <schema:duration> "1 h 14 min";
            <dcterms:language> "en";
            <dcterms:title> "Mussolini Speaks" ;
            <schema:about> <period/Sansepolcrism> .

# PHOTOGRAPH1

<items/Photograph1> a <schema:Photograph>;
            <schema:creationDate> "1919";
            <schema:locationCreated> "Milan";
            <dcterms:title> "Piazza San Sepolcro 1919";
            <schema:about> "Start of San Sepolcrism" ;
            <schema:about> <period/Sansepolcrism> ;
            <schema:subject> <person/Mussolini> .

# PHOTOGRAPH2

<items/Photograph2> a <schema:Photograph>;
            <schema:author> "Porry Pastorel, Adolfo";
            <schema:locationCreated> "Rome";
            <schema:creationDate> "October, 1922";
            <dcterms:title> "Mussolini in camicia nera fra i quadriumviri";
            <schema:about> "March on Rome" ;
            <schema:about> <period/Sansepolcrism> ;
            <schema:subject> <person/Mussolini> .

# DOCUMENT

<items/Document> a <schema:text>;
            <schema:author> "Benito Mussolini";
            <schema:datePublished> "June 6, 1919";
            <schema:isPartOf> "Il Popolo d'Italia";
            <dcterms:title> "Programma di San Sepolcro";
            <dcterms:language> "it" ;
            <crm:P70_is_documented_in> <period/Sansepolcrism> ;
            <schema:isPartOf> <items/IlPopolod'Italia> .
            

# NEWSPAPER

<items/IlPopolod'Italia> a <frbroo:F19_Publication_work> ;
            <schema:creationDate> "November 15, 1914";
            <schema:genre> "Political";
            <dcterms:language> "it";
            <dcterms:title> "Il Popolo d'Italia" ;
            <frbroo:P69_is_associated_with> <period/Sansepolcrism> ;
            <crm:P108_was_produced_by> <person/Mussolini> .
			

# SCULPTURE

<items/Uniqueformsofcointinuityinspace> a <schema:CreativeWork>;
            <schema:author> "Umberto Boccioni";
            <schema:dateCreated> "1913";
            <schema:itemLocation> "Museu de arte contemporanea";
            <dcterms:title> "Unique forms of continuity in space";
            <schema:material> "Plaster";
            <schema:dimensions> "119,7 cm x89,9 cm x 39,9 cm" ;
            <crm:P138_represents> <items/Futurism> .

# ARTISTICANDSOCIALMOVEMENT

<items/Futurism> a <Style/Period/Group/Movement>;
            <schema:author> "Filippo Tommaso Marinetti";
            <schema:dateCreated> "1909";
            <schema:place> "Italy" ;
            <crm:P69_is_associated_with> <period/Sansepolcrism> .
