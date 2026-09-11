# Intermind — Round B Residual Search Prompt
**Purpose:** reduce prompt-induced convergence after the structured first-pass review.

Give this prompt to each reviewer **without the original checklist repeated**:

> You have already reviewed the Intermind seed packet using a structured checklist.
>
> Now ignore every test, category, principle, and failure mode named in that checklist and in the first convergence synthesis.
>
> **What important failure mode, hidden assumption, competing objective, missing stakeholder, or fundamentally different architecture did those documents make you less likely to notice?**
>
> Do not repeat prior objections unless necessary to explain a genuinely new one.
>
> Also answer:
> 1. What existing tool/process might already make Intermind unnecessary?
> 2. What part of Intermind would you delete first if forced to reduce it by 50%?
> 3. What observation would make you conclude the entire framework should not continue?
> 4. What is one critique you expect other frontier AI models are unlikely to produce because of shared training/alignment assumptions?
>
> Preserve uncertainty. Do not optimize for agreement.

This round is not proof of independence. It is only a residual search for blind spots created by the common first-pass frame.
