# Проверка согласованности импортов онтологии
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>

# Этот запрос проверяет, что все импортируемые онтологии существуют в триплсторе
ASK {
    ?ontology rdf:type owl:Ontology ;
              owl:imports ?imported .
    ?imported rdf:type owl:Ontology .
}