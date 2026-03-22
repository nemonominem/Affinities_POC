# Genetic and Choice-Based Affinities in Human Relationships

---
header-includes:
	- |
		\usepackage[hyphens]{url}
		\usepackage{hyperref}
		\usepackage{microtype}
		\usepackage{fancyhdr}
		\pagestyle{fancy}
		\fancyhf{}
		\fancyfoot[L]{Page\ \thepage}
		\fancyfoot[R]{Generated:\ \today}
		\renewcommand{\headrulewidth}{0pt}
		\renewcommand{\footrulewidth}{0.4pt}
		\sloppy
		\urlstyle{same}
geometry: margin=2.5cm
---

*A framework for understanding the statistical likelihood of personality compatibility across relationship types*

**Author:** Gilles DEMANEUF (conception, editorial role) — ORCID: 0000-0001-7277-9533

**Date:** March 2026

---

### Disclaimer

This essay is based on an idea and initial analysis by the author, which was then refined using GenAI models via the Cline extension in VS Code[^disclaimer]. Editorial clean-up and final shaping was by the author. This essay was also used as a test-bench for optimal deployment of GenAI tools.

[^disclaimer]: Models used: mimo-v2-pro and trinity-large-preview on Cline (both free); final sub-agent peer-review and adjustments by Claude Sonnet 4.6 (cost: NZD 2.67).

---

## Introduction

How much compatibility should we reasonably expect from different relationships in our lives? This question matters for setting realistic expectations, allocating emotional energy, and understanding why some relationships feel more naturally harmonious than others.

This essay focuses on two measurable factors of character affinity: **genetic-based relatedness** (the biological baseline for potential similarity in personality and temperament) and **agency** (the personal choice we exercise in selecting and shaping some relationships but not others). By examining how these factors interact, we can develop more nuanced *predictions* about personality compatibility—though translating those predictions into normative expectations requires additional steps that are discussed in the Implications section.

It is important to be clear about the conceptual chain this essay relies on. Three links must hold for the framework to work:

1. **Genetic similarity → personality similarity**: Relatives share some personality traits due to shared genes, but phenotypic correlations between first-degree relatives are modest (~0.15–0.25) **[4][10]**, far below the 50% shared DNA would naively suggest.
2. **Personality similarity → compatibility**: Similarity on personality traits predicts relationship quality, but only modestly. Meta-analyses (e.g., Montoya & Horton, 2013 **[11]**) find similarity-attraction correlations that are real but context-dependent and typically small-to-moderate.
3. **Compatibility prediction → fair expectation**: Even where compatibility is more likely, it does not automatically follow that we are *owed* more of it from a given relationship type, or that we are more justified in dissolving bonds that disappoint. This normative step requires ethical reasoning beyond the statistics.

These links are acknowledged throughout the essay. The framework is therefore best understood as describing statistical *tendencies*—not obligations or entitlements—and readers should bear all three links in mind when interpreting the ranking.

A third empirical factor—**nurture and social conventions**—also shapes compatibility. This includes shared upbringing, cultural norms, and community expectations that bind people together regardless of genetic or choice-based factors. However, this aspect is more difficult to evaluate quantitatively, and its importance varies dramatically across societies. In many Western, individualist cultures, nurture conventions play a relatively modest role in adult personality compatibility. In contrast, in highly cohesive cultures—such as Māori society with its emphasis on *manaakitanga* (hospitality, generosity, mutual care)—social conventions and collective identity can be powerful drivers of interpersonal harmony, sometimes rivaling or exceeding the influence of genetic relatedness or personal choice. This essay deliberately sets aside this third factor to focus on the two that are more readily measured, but its significance should not be forgotten.

The focus here is on personality traits that drive day-to-day harmony—particularly the Big Five dimensions (extraversion, agreeableness, conscientiousness, neuroticism, and openness)—rather than on deeper bonds of loyalty or obligation, which follow different dynamics.

*Note: The estimates and framework presented here draw on behavioral genetics, but this remains an active field with ongoing debates about the relative importance of additive vs. non-additive genetic effects, gene-environment interactions, and the limits of heritability estimates. Readers should treat the specific numbers as indicative approximations rather than precise measurements.*

## Genetic Compatibility Potential: The Numbers

Personality traits are highly polygenic, influenced by thousands of genetic variants each with tiny effects. The **standard additive model** assumes relatedness *r = 0.5* for parents, children, and full siblings (sharing 50% of DNA on average). However, non-additive effects—dominance and especially epistasis (gene–gene interactions)—introduce randomness, particularly visible in siblings **[3]**. This means the *effective* genetic similarity for expressed personality is somewhat lower than 0.5, though the exact reduction varies by trait and remains imprecisely estimated.

*A note on precision: The estimates below are derived indirectly from observed phenotypic correlations and additive genetic models. In particular, the "adjusted personality relatedness" column attempts to capture the fact that non-additive genetic effects reduce the effective genetic signal below the nominal 50% DNA sharing. As a back-calculation: if phenotypic correlations between relatives are r ≈ 0.20 and narrow-sense heritability is h² ≈ 0.40, then the implied additive genetic correlation is r/h² ≈ 0.50—consistent with the additive model. Evidence for reductions below 0.50 comes from twin-plus-sibling designs that detect non-additive variance **[3]**. These should be treated as rough guides rather than precise measurements. The relationship between genetic similarity and phenotypic correlation is not perfectly linear, and the exact values depend on trait-specific architecture, measurement quality, and population. "Effective genetic personality relatedness" as used here is a shorthand, not a standard behavioral-genetics term; it refers loosely to the degree to which shared genes are expected to translate into shared personality traits after accounting for non-additive effects.*

| Relationship | Additive DNA Relatedness | Approx. Personality-Trait Relatedness (adjusted) | Chosen by Us? | Predicted Compatibility Tendency |
|--------------|--------------------------|-------------------------------|:--------------:|------------------|
| Partner | ~0 | ~0 | Yes (fully) | **Very High** — choice is the primary signal (plus modest assortative mating) |
| Chosen Friends | ~0 | ~0 | Yes (fully) | **Very High** — choice is the only signal |
| Children | 0.5 | ~0.40–0.50 (small mate-choice boost) | Indirect (via partner choice) | **High** — significant genetic baseline plus indirect filtering |
| Parents | 0.5 | ~0.40–0.50 | No (your parents chose partners) | **Moderate** — decent genetic baseline, but no agency on your part |
| Siblings | 0.5 | ~0.35–0.45 | No | **Moderate-Low** — same genetic baseline, greater non-additive randomness |

**Observed data supports this picture**: parent–child and sibling correlations for personality are typically only ~0.15–0.25 (sometimes approaching ~0.25 with better measurement) **[4][10]**, far below what a pure 50% additive model would predict without non-additive drag.

### Friends and Partners: Chosen Similarity

We select partners and friends deliberately for matching values, humor, lifestyle, interests, and worldview, with zero genetic relatedness. Compatibility rests entirely on this choice and deliberate alignment. Partners also benefit from a modest additional signal: people tend to mate assortatively on personality dimensions (partner correlations typically r ≈ 0.10–0.20 on Big Five traits **[12][13]**), giving chosen partnerships a small genetic-similarity boost over random pairing. Research also suggests friends cluster on some behavioral and genetic characteristics **[14]**. Note, however, that the assortative-mating effect is modest; it should not be overstated as a major "compatibility boost."

### Children: Indirect Agency

Relatedness is strong (~0.40–0.50 adjusted for non-additive effects, though some estimates suggest as low as ~0.35 for traits with more epistasis) **[1][3]**. Critically, the parent chose the other parent, indirectly shaping half the genetic package transmitted to the child. This creates a directional asymmetry in agency: from the *parent's* vantage point, the child's genotype partly reflects a choice they made; from the *child's* vantage point, both parents were equally unchosen. This asymmetry in agency does not translate directly into differential relational obligations, but it does mean the statistical signal for parent→child compatibility is slightly stronger (by the assortative-mating boost) than for child→parent. See the Appendix for a formal derivation showing this effect is numerically small: with observed partner personality correlations of r_parents ≈ 0.10–0.15, the additive regression coefficient of child on parent rises only from β = 0.50 to approximately β = 0.505–0.575—a marginal increment that likely disappears under non-additive effects and environmental noise. The asymmetry is real in principle but modest in practice.

### Parents and Siblings: No Agency

Both have the same ~0.5 additive DNA relatedness as children, but neither was chosen. Siblings may have a marginally lower effective personality relatedness (~0.35–0.45) than parent–child pairs because siblings draw their gene combinations independently from each parent, potentially amplifying non-additive (dominance and epistatic) randomness **[3]**. Note that the available evidence on the epistasis/dominance split is limited: twin-plus-sibling designs detect non-additive variance broadly, but cleanly separating dominance from epistasis in these designs is notoriously difficult, so "epistatic lottery" should be understood as shorthand for "non-additive randomness" rather than a precise mechanistic claim.

## Validity and Limits of the Additive Model

The pure additive model (*r = 0.5*, everything sums linearly) is a **very good first approximation** and explains most of the genetic signal for personality. Narrow-sense heritability (additive genetic variance as a proportion of phenotypic variance) is estimated at approximately 40–60% in the best modern designs, with variation across traits: some traits (e.g., openness, neuroticism) tend toward the higher end **[4][10]**. A commonly cited working figure is ~40% for well-measured adult personality, though estimates up to ~60% appear in comprehensive meta-analyses **[10]**. It works well because the vast majority of genetic effects on complex traits like personality are additive—small, independent contributions from thousands of variants.

However, it is **not perfect**. Twin and family studies (especially those including siblings) consistently detect non-additive variance (dominance + epistasis), often 10–30% of total genetic variance for some traits (e.g., openness, extraversion facets) **[1][3]**. Note that Keller et al. (2005) **[3]** studied Cloninger's and Eysenck's personality dimensions rather than the Big Five specifically; the mapping between these frameworks is imperfect. Nonetheless, non-additive effects are widely considered real and meaningful for personality more broadly. This non-additivity is more prominent in siblings than in parent–child pairs because siblings independently draw their gene combinations from each parent, creating greater randomness in how gene interactions play out **[3]**.

Large modern genomic studies (using common SNPs) typically find SNP-based heritability for personality of approximately 15–21% **[2]**—substantially lower than twin-based estimates (~40–60%). This gap is mainly attributed to *missing heritability* (rare variants, structural variants, gene-environment interactions not captured by common SNPs) rather than being direct evidence for non-additive genetic effects. Separate evidence from twin-plus-sibling designs **[3]** supports the existence of non-additive effects; the two lines of evidence address different questions.

The net result: **effective personality relatedness for first-degree relatives is somewhat below the additive 0.5**—roughly 0.40–0.50 for parent–child pairs, potentially somewhat lower for siblings (~0.35–0.45) **[3]**. These estimates are approximate; the exact adjustment varies by trait and measurement precision.

This adjustment has practical implications: family compatibility is less reliable and more variable than textbooks suggest, reinforcing that we should not over-rely on "50% shared genes" as a guarantee of harmony.

## Nature vs. Nurture: Complementary Forces, Not Rivals

Personality heritability is approximately 40–60% in well-measured designs (narrow-sense, mostly additive) **[4][10]**, leaving a substantial proportion to environment. But the environmental portion is dominated by **non-shared environment** (unique experiences, peers, personal interpretations)—not the shared family home. Shared family culture provides only a thin, early-life baseline (<10% for adult personality in most studies) **[7][15]**.

This explains several patterns:

- **Chosen friends and partners often show higher personality compatibility with us than biological relatives**: We select them precisely for cultural match (values, humor, worldview), while family gets whatever mix of genes and imposed culture we draw. People also tend to assort with somewhat genetically similar partners and friends **[9][14]**, giving chosen relationships a modest additional signal.

- **Siblings and parent–adult-child pairs frequently diverge**: Even with identical genetics (as in monozygotic twins raised together), generational gaps, life-stage differences, and non-shared experiences create divergence **[7]**.

- **Modern life amplifies choice-based bonds**: Mobility and individualism mean we spend far more time with chosen people than blood relatives. Biology (kin selection) still pulls us toward family, but deliberate choice and non-shared environments increasingly shape day-to-day affinity.

**The interaction matters**: Genes set potentials and biases; nurture—especially chosen nurture—does the heavy lifting for real compatibility. The two forces are complementary, not competing.

## A Ranking of Predicted Compatibility Tendencies

Based on the evidence reviewed above, personality compatibility tendencies rank roughly as follows, from highest to lowest predicted likelihood:

**Partners and Chosen Friends** > **Children** > **Parents** > **Siblings**

- **Partners and chosen friends** rank first because compatibility rests entirely on active selection, which is the strongest available signal.
- **Children** rank second because the parent contributed indirect genetic agency via partner choice. In practice, the numerical boost over parents is modest (see Appendix), but the directional logic holds.
- **Parents** rank third: same genetic baseline as children, but no agency was exercised by the person doing the evaluating.
- **Siblings** rank fourth: same nominal genetic baseline, but with greater non-additive randomness reducing the effective personality signal.

This ranking describes statistical tendencies in personality overlap and compatibility likelihood. It does not prescribe how to treat people, does not imply that family bonds matter less (they operate through very different channels—attachment, loyalty, shared history), and does not justify treating any relationship as disposable. Individual variation is vast, and averages obscure many exceptional cases.

## Implications and Caveats

### What This Framework Suggests

1. **It is statistically reasonable to predict higher day-to-day personality compatibility with chosen friends and partners than with family members.** This does not mean family is less important—its importance stems more from attachment, loyalty, shared history, and obligation than from natural personality affinity.

2. **There is a directional asymmetry in parent–child compatibility predictions.** From the parent's vantage point, the child's genotype partly reflects their mate choice; from the child's vantage point, both parents were unchosen. In practice, this asymmetry is quantitatively small (see Appendix) but theoretically present.

3. **Prioritizing chosen relationships is not irrational.** The statistics support the observation that relationships where both parties actively selected for compatibility tend to show higher personality overlap.

### Important Limitations

- **This framework addresses personality compatibility, not all forms of closeness.** Attachment, loyalty, duty, shared history, and love operate through different channels and may favor family bonds.

- **Culture matters enormously.** In collectivist societies, family obligations may override compatibility concerns more strongly, and the framework's implications may feel less relevant. The emphasis on choice-based relationships reflects individualist cultural assumptions that may not translate universally. In highly cohesive cultures—such as Māori society with its emphasis on *manaakitanga* (hospitality, generosity, mutual care)—social conventions and collective identity can be powerful drivers of interpersonal harmony, sometimes rivaling or exceeding the influence of genetic relatedness or personal choice. This essay's focus on measurable factors (genetics and agency) should not obscure the importance of this third dimension.

- **Individual variation is vast.** Statistical tendencies obscure the fact that some siblings are deeply compatible and some friendships fail despite deliberate selection. The framework describes probabilities, not certainties.

- **Personality is not destiny.** People grow, change, and adapt. Relationships can become more compatible over time through deliberate effort, regardless of their starting point.

- **The adjusted personality relatedness estimates (~0.40–0.50, lower for siblings) are approximations** derived indirectly from the gap between observed correlations and additive predictions. They vary by trait, measurement quality, and population, and should be treated as indicative rather than precise. "Effective relatedness" is not standard behavioral-genetics terminology; what is meant is the degree to which shared genes translate into shared personality traits, approximately, after adjusting for non-additive effects.

- **Ongoing scientific debates**: The relative importance of additive vs. non-additive genetic effects, the role of gene-environment correlations, and the limits of heritability estimates remain active areas of research. The framework represents a reasonable synthesis but not a settled consensus **[10]**.

- **The normative step carries its own complexity.** Even granting all the statistical claims, the inference that we are *owed* more compatibility from chosen relationships, or that disappointing relationships should be "released," requires ethical reasoning that goes beyond the behavioral genetics. Readers should draw their own conclusions about what follows normatively from the descriptive picture.

## Bottom Line

Personality compatibility is most likely with chosen partners and friends (where selection is the entire signal), quite likely with children (where a meaningful genetic baseline exists plus a modest indirect filtering effect), and rests on a moderate genetic baseline with parents and siblings (where no agency was involved and non-additive randomness reduces the signal further). Genetics provides a nudge; personal agency and deliberate alignment decide how far that nudge goes.

This is a descriptive and probabilistic framework, not a prescription for how to treat people. It offers a lens for understanding why some relationships feel more naturally harmonious than others, and for setting expectations that are biologically informed—while recognizing that attachment, loyalty, and shared history follow their own logic, independent of personality overlap.

---

## Appendix: Quantitative Assessment of the Assortative Mating Boost

Write parental additive genetic values as $G_m$ (mother) and $G_f$ (father). The child's additive value is approximately

$$G_c \approx \tfrac{1}{2}G_m + \tfrac{1}{2}G_f.$$

The covariance between child and mother is

$$\mathrm{Cov}(G_c,G_m)=\mathrm{Cov}\big(\tfrac{1}{2}G_m+\tfrac{1}{2}G_f,\;G_m\big)=\tfrac{1}{2}\mathrm{Var}(G_m)+\tfrac{1}{2}\mathrm{Cov}(G_f,G_m).$$

Let $r_{\mathrm{parents}}=\mathrm{Corr}(G_f,G_m)$ and $\mathrm{Var}(G_m)=\sigma_G^2$. Then

$$\mathrm{Cov}(G_c,G_m)=\sigma_G^2\cdot\tfrac{1}{2}(1+r_{\mathrm{parents}}),$$

so the expected additive regression of child on that parent is

$$\beta_{c:\!m}=\frac{\mathrm{Cov}(G_c,G_m)}{\mathrm{Var}(G_m)}=\tfrac{1}{2}(1+r_{\mathrm{parents}}).$$

Empirically, partner personality correlations on Big Five traits are typically $r_{\mathrm{parents}} \approx 0.10$–$0.15$ **[12][13]**. Substituting:

$$\beta_{c:\!m} \approx \tfrac{1}{2}(1+0.10) \approx 0.55 \quad \text{to} \quad \tfrac{1}{2}(1+0.15) \approx 0.575.$$

This is only marginally above the baseline of 0.50. When environmental and non-additive variance are considered, phenotypic correlations between parent and child are typically 0.15–0.25, with essentially no practically detectable difference attributable to assortative mating alone. The asymmetry is therefore **real in principle but difficult to detect in practice**.

---

## Sources

[1] Jang, K. L., Livesley, W. J., & Vernon, P. A. (1996). Heritability of the big five personality dimensions and their facets: A twin study. *Journal of Personality*, 64(3), 577–592. https://pubmed.ncbi.nlm.nih.gov/8776880/

[2] Power, R. A., & Pluess, M. (2015). Heritability estimates of the Big Five personality traits based on common genetic variants. *Translational Psychiatry*, 5(7), e604. [Note: This paper reports SNP-based heritability (~15–21%), which is lower than twin-based estimates (~40–60%) due to missing heritability from rare variants and other sources not captured by common SNPs. It should not be compared directly with twin-study heritability figures.] https://pmc.ncbi.nlm.nih.gov/articles/PMC5068715/

[3] Keller, M. C., et al. (2005). Widespread evidence for non-additive genetic variation in Cloninger's and Eysenck's personality dimensions using a twin plus sibling design. *Behavior Genetics*, 35(6), 707–721. [Note: Uses Cloninger's TCI and Eysenck's EPQ instruments, not the Big Five directly. The mapping to Big Five dimensions is imperfect.] https://pubmed.ncbi.nlm.nih.gov/16273321/

[4] Vukasović, T., & Bratko, D. (2015). Heritability of personality: A meta-analysis of behavior genetic studies. *Psychological Bulletin*, 141(4), 769–785. https://psycnet.apa.org/record/2015-20360-001

[5] Loehlin, J. C. (1998). Heritabilities of common and measure-specific components of the Big Five personality factors. *Journal of Research in Personality*, 32(4), 431–453. https://www.sciencedirect.com/science/article/pii/S0092656698922255

[6] Weinschenk, A., et al. (2022). The five factor model of personality and heritability: Evidence from Denmark. *Personality and Individual Differences*, 192, 111605. https://www.sciencedirect.com/science/article/pii/S019188692200109X

[7] Plomin, R., Asbury, K., & Dunn, J. (2001). Why are children in the same family so different? Non-shared environment a decade later. *The Canadian Journal of Psychiatry*, 46(3), 225–233. https://pubmed.ncbi.nlm.nih.gov/11320676/

[8] Beam, C. R., et al. (2020). How nonshared environmental factors come to correlate with behavioral genetic factors. *Development and Psychopathology*, 32(5), 1645–1659. https://pmc.ncbi.nlm.nih.gov/articles/PMC8081739/

[9] Versluys, T. M. M., et al. (2021). Why do we pick similar mates, or do we? *Evolutionary Psychology*, 19(3). [Note: Findings on genetic and phenotypic assortative mating for personality are mixed and modest; the title's question mark reflects genuine uncertainty. Claims of a "compatibility boost" from assortative mating should be read with this caveat in mind.] https://pmc.ncbi.nlm.nih.gov/articles/PMC8610703/

[10] Polderman, T. J. C., et al. (2015). Meta-analysis of the heritability of human traits based on fifty years of twin studies. *Nature Genetics*, 47(7), 702–709. https://www.nature.com/articles/ng.3285

[11] Montoya, R. M., & Horton, R. S. (2013). A meta-analytic investigation of the processes underlying the similarity-attraction effect. *Journal of Social and Personal Relationships*, 30(1), 64–94. https://doi.org/10.1177/0265407512452989

[12] Luo, S., & Klohnen, E. C. (2005). Assortative mating and marital quality in newlyweds: A couple-centered approach. *Journal of Personality and Social Psychology*, 88(2), 304–326. https://doi.org/10.1037/0022-3514.88.2.304

[13] Watson, D., et al. (2004). Match makers and deal breakers: Analyses of assortative mating in newlywed couples. *Journal of Personality*, 72(5), 1029–1068. https://doi.org/10.1111/j.0022-3506.2004.00289.x

[14] Christakis, N. A., & Fowler, J. H. (2014). Friendship and natural selection. *Proceedings of the National Academy of Sciences*, 111(Suppl. 3), 10796–10801. https://doi.org/10.1073/pnas.1400825111

[15] Turkheimer, E. (2000). Three laws of behavior genetics and what they mean. *Current Directions in Psychological Science*, 9(5), 160–164. https://doi.org/10.1111/1467-8721.00084
