The GraphicZero folder contains the following:

## Origonal project deliverable:

ProjectIntroductionVideo:
https://www.youtube.com/watch?v=FqSzCCxxdVY&t=9s

**.** AbridgedMathsofQuadraticAddition.pdf is an abridged introduction to the math.

**.** TwoPolynomial092319.csv data for populating graphdb.

**.** Four cypher script text files.  
CreateDB loads the .csv.
Arithmetic will add two ^2 integers as pattern comprehension or otherwise return the quadratic polynomial representation of ^2.
UpdateWithQuartetNodes will extend graphDB with available quartet polynomial comprenension.  
ViewOfEvaluateQuartet inspects the new quartet.

**.** TwoPolynomialGeneratorJarZip contains Java Jar file.
Run with two arguments:
.FileName.csv
.Index argument (An integer, the independent variable of a quadratic. So far, tested up to 1000).

## Subsequent project work:

Zeppelin notbooks:

GraphicFirstML.json           - Cypher scripts implementing Neo4j ML algorithms. 

GraphicScrips.json            - Primary cypher scrips used for manipulating integer representing polynomials.

GraphicZero.json              - Spark Scala notebook exibiting algebraic properties of generated polynomials.     

GraphiZeroTheQuadratics.json  - Spark Scala notebook exibitiing properties of generated quadratics.

KafkaStreamsTopics.json       - neo4j .conf scrips integrating kafka and neo4j.

SingleVariableCritticalPoint.json    -  Spark Scala analysis of single variable P.

MultiVariableNMGradientDescent.json  -  Spark Scala mulit varaible Gradient Descent, Newtons Method applied to selected p's.


Java Jars:

ZADScripts.jar            - Generate arbitrary degreed polynomial starting with generated quadratics (uses Kafka).

ZeroAndDifferences.jar    - Implement Newton's difference algorithm along with jdbc methods for populating graphDB.


Video of Differences Graph generator:
https://www.youtube.com/watch?v=H4dBkofVA4A

Link to encoding root sets as rational numbers.
https://www.quora.com/How-are-rational-numbers-constructed-from-the-axioms-of-set-theory?q=how%20are%20the%20rationals%20constructed%20from%20the%20axioms%20of%20set

## Graph Machine learning:

CubicNewtonDifferences.csv is dumped graph of ZerosAndDifferences.jar output for cubic 1^3 input.  

The Zeppelin notebook GraphicDetermined implements neo4j gds.alpha.ml.nodeClassification algorithm for predicting determined polynomials represented on graph. 


