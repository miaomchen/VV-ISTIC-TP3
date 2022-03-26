# Detecting test smells with PMD

In folder [`pmd-documentation`](../pmd-documentation) you will find the documentation of a selection of PMD rules designed to catch test smells.
Identify which of the test smells discussed in classes are implemented by these rules.

Use one of the rules to detect a test smell in one of the following projects:

- [Apache Commons Collections](https://github.com/apache/commons-collections)
- [Apache Commons CLI](https://github.com/apache/commons-cli)
- [Apache Commons Math](https://github.com/apache/commons-math)
- [Apache Commons Lang](https://github.com/apache/commons-lang)

Discuss the test smell you found with the help of PMD and propose here an improvement.
Include the improved test code in this file.

## Answer

*DetachedTestCase* : permet de détecter les cas de test d'une classe de test qui ne sont pas précédés par l'annotation @Test

*JUnit4SuitesShouldUseSuiteAnnotation*, *JUnit4SuitesShouldUseSuiteAnnotation* , *JUnit4TestShouldUseAfterAnnotation*, *JUnit4TestShouldUseBeforeAnnotation*, *JUnit4TestShouldUseTestAnnotation*, *JUnitAssertionsShouldIncludeMessage*, *JUnitSpelling*, *JUnitStaticSuite* : permet de vérifier que les bonnes annotations et fonctions  ont été utilisées pour effectuer les tests.

*JUnitTestContainsTooManyAsserts*, *JUnitTestsShouldIncludeAssert*, *UnnecessaryBooleanAssertion*, *UseAssertEqualsInsteadOfAssertTrue*, *UseAssertEqualsInsteadOfAssertTrue* , *UseAssertNullInsteadOfAssertTrue*, *UseAssertSameInsteadOfAssertTrue*, *UseAssertTrueInsteadOfAssertEquals* : présente les meilleures manières d'utiliser les Assert dans les classes de tests

*JUnitUseExpectedJUnitUseExpected* : gestion des exceptions dans les cas de test





































