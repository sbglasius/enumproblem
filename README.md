# enumproblem

If https://github.com/sbglasius/enumproblem/blob/master/grails-app/domain/enumproblem/Relation.groovy#L5 has a `static belongsTo = [test: Test]` 
then Grails 3.0.11 fails to start the application with an (unrelated?) Hibernate error, if the domain class `Test` has a defined `Enum` 

