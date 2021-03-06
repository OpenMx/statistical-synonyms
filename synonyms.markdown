## Structural Modeling Terms

1. Classical [Structural Equation Model](https://en.wikipedia.org/wiki/Structural_equation_modeling)
 * A model in which (to use RAM notation), entries in `A` and `S` are numeric.
 * synonym: General structural equation models: Models with both observed and unobserved variables. (term used in sem package)
2.  Extended SEM
 *  Model in which the [RAM](http://onlinelibrary.wiley.com/doi/10.1111/j.2044-8317.1984.tb00802.x/abstract)-equivalent of `A` and `S` matrix entries may be arbitrary algebras.  These algebras may be a function of definition variables (see below).
3. [Definition variable](http://davidakenny.net/cm/basics.htm)
 * Any value in an SEM that is replaced with a person-specific value such that it can differ for each row or person.
4. [Multilevel model](https://en.wikipedia.org/wiki/Multilevel_model)
 * Relational SEM, by analogy to the way in which a relational database links values in different tables. 
5. [Item Response Theory](https://en.wikipedia.org/wiki/Item_response_theory)
 * Item factor analysis (IFA)

## Ordinal Data terms

1. Cumulative link (mixed) models
 * Regression models with ordinal data. Implemented in `R` in package [ordinal](https://cran.rstudio.com/web/packages/ordinal/)
 * Synonyms:
  * Ordered regression models
  * Proportional odds models
  * Proportional hazards models (for grouped survival times)
  * Ordered logit/probit/... models
