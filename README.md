## SNOMED CT Computable Languages

This repository contains the formal syntax, example parsers, and valid example files for each computable language in the SNOMED CT Family of Languages.

The SNOMED CT Family of Languages currently includes:
* **SNOMED CT Compositional Grammar** - used to represent SNOMED CT expressions. The SNOMED CT Compositional Grammar Specification and Guide is available at [snomed.org/scg](http://snomed.org/scg)
* **SNOMED CT Expression Constraint Language** - used to represent SNOMED CT expression constraints and simple queries. The SNOMED CT Expression Constraint Language Specification and Guide is available at [snomed.org/ecl](http://snomed.org/ecl)
* **SNOMED CT Expression Template Language** - allows slots to be added to expressions, that can be filled with specific values at a later time. The SNOMED CT Expression Template Syntax combines SNOMED CT Compositional Grammar with the SNOMED CT Template Syntax. Please refer to [snomed.org/etl](http://snomed.org/etl) and [snomed.org/sts](http://snomed.org/sts)

It is anticipated that the following languages will be added to this repository in the future:

* **SNOMED CT Query Language** - used to represent computable queries over SNOMED CT content
* **SNOMED CT Expression Constraint Template Syntax** - allows slots to be added to expression constraints, that can be filled with specific values at a later time
* **SNOMED CT Query Template Syntax** – allows slots to be added to SNOMED CT queries, that can be filled with specific values at a later time

The folders are organized as follows:
* *SnomedCTCompositionalGrammar* - contains files relating to SNOMED CT Compositional Grammar
  * *CG Examples* - contains a set of valid example files for SNOMED CT Compositional Grammar v2.3.1
  * *CG Parser* - contains an example parser for SNOMED CT Compositional Grammar v2.3.1 (as generated by the APG ABNF Parser Generator)
  	* For an example parser based on an ANTLR4 grammar, please refer to [github.com/IHTSDO/snomed-scg-parser](https://github.com/IHTSDO/snomed-scg-parser)
  * *CG Syntax* - contains the ABNF syntax for SNOMED CT Compositional Grammar v2.3.1
   	* For a corresponding ANTLR4 grammar, please refer to [github.com/IHTSDO/snomed-scg-parser/blob/master/parser-generation/SCG.txt](https://github.com/IHTSDO/snomed-scg-parser/blob/master/parser-generation/SCG.txt)
* *SnomedCTExpressionConstraintLanguage* - contains files relating to the SNOMED CT Expression Constraint Language
  * *ECL Examples* - contains a set of valid example files for the SNOMED CT Expression Constraint Language
  	* *ECL v1* - contains examples for v1 of the SNOMED CT Expression Constraint Language
  	* *ECL v1.2* - contains examples for v1.2 of the SNOMED CT Expression Constraint Language
  * *ECL Parser* - contains an example parser for the brief (normative) and long (informative) ABNF syntaxes of the SNOMED CT Expression Constraint Language v1.2 (as generated by the APG ABNF Parser Generator). For an example parser based on an ANTLR4 grammar, please refer to [github.com/IHTSDO/snomed-ecl-parser](https://github.com/IHTSDO/snomed-ecl-parser)
  * *ECL Syntax* - contains the brief (normative) and long (informative) ABNF syntaxes for the SNOMED CT Expression Constraint Language v1.2. For a corresponding ANTLR4 grammar, please refer to [github.com/IHTSDO/snomed-ecl-parser/blob/master/src/main/antlr4/org/snomed/langauges/ecl/generated/parser/ECL.g4](https://github.com/IHTSDO/snomed-ecl-parser/blob/master/src/main/antlr4/org/snomed/langauges/ecl/generated/parser/ECL.g4)
* *SNOMEDCTExpressionTemplateLanguage* - contains files relating to the SNOMED CT Expression Template Language
  * *ETL Examples* - contains examples for v1 of the SNOMED CT Expression Constraint Language
  * *ETL Parser* - contains an example parser for the normative ABNF syntax of the SNOMED CT Expression Template Language v1. For an Expression Template parser based on the corresponding ANTLR4 grammar, please refer to [github.com/IHTSDO/snomed-template-parser](https://github.com/IHTSDO/snomed-template-parser)
  * *ETL Syntax* - contains the normative ABNF syntax for the SNOMED CT Expression Template v1. For a corresponding ANTLR4 grammar, please refer to [github.com/IHTSDO/snomed-template-parser/blob/master/parser-generation/ExpressionTemplate.txt](https://github.com/IHTSDO/snomed-template-parser/blob/master/parser-generation/ExpressionTemplate.txt)

