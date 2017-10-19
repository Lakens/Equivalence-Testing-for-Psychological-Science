Psychologists should be able to falsify predictions. A common prediction
in psychological research is that an effect exists in the population
that differs from zero. For example, we might predict that priming
American Asian women with their Asian identify will increase their
performence on a math test compared to women in the control condition
who are primed with their female identity. To be able to falsify this
hypothesies, and design a study that allows for strong inferences
([**???** ]{}), it is important to specify which test result would
*disprove* the hypothesis.

An equivalence test can be used to test whether the observed effect is
surprisingly close to zero, assuming a meaningful effect exists in the
population. The test is a simple variation on the widely used null
hypothesis significance tests, with the small difference that instead of
testing the observed effect against zero, it is tested against a
smallest effect size of interest (SESOI). For example, if a difference
on a math test of 5% or more is considered meaningful, one could test
against a SESOI of 5%. If the observed effect is suprisingly closer to
0, assuming a true effect of 5% or larger existed, one can declare
statistical equivalence, or reject the presence of effects that are
large enough to be considered meaningful. An equivalence test can be
used to falsify hypotheses.

One can conclude statistical equivalence whenever a 90% confidence
interval around the effect size estimate does not contain the SESOI, or
when two one-sided tests (i.e., examining whether the difference on the
math test is more than -5%, but less than 5%) are statistically
significant. By combining null-hypothesis tests and equivalence tests,
four combinations of results can be observed (see Figure 1). Two
outcomes are straightforward to interpret, namely when the effect is
equivalent to zero, and not different from zero (an effect that is not
meaningful), and when the effect is not equivalent, and different from
zero (a meaningful effect). In addition, the effect can be different
from zero and too small to be considered meaningful (an effect which is
not meaningful) or the effect can neither differ from zero, not be
equivalent to zero (an undetermined result, where more data is needed).

Even though equivalence tests are just a small variation of traditional
Frequentist tests (testing against the SESOI, instead of 0), their use
was limited until the availability of user-friendly software to perform
the calculations (Lakens, 2017). In this article, we discuss different
approaches to determining the SESOI for psychological research, and
provide detailed reproducible examples of how to perform power analyses
when designing equivalence tests, and statistical re-analyses of
published psychology experiments.