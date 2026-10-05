# AI visibility baseline template

A measurement-first template for recording whether AI answer systems correctly identify, mention, cite, or recommend a person or business.

Prepared by [Japhet Cordova](https://www.japhetcordova.com/about), an independent search and website specialist based in the Philippines and working with clients internationally.

## Principles

- Freeze the prompt set and test conditions before changing the website.
- Keep branded recognition separate from unbranded discovery.
- Keep mentions, citations, recommendations, search indexing, and referral traffic separate.
- Record `unavailable` when access or evidence is missing. Never silently convert it to zero.
- Treat a wrong-person response as an entity-collision incident, not positive visibility.
- Preserve raw evidence privately when it contains account or personal information.
- Report observations and limitations; do not claim that one website change caused an external AI result.

## Environment record

| Field | Value |
| --- | --- |
| Test window | `YYYY-MM-DD` through `YYYY-MM-DD` |
| Reviewer |  |
| Market/location |  |
| Language |  |
| Product |  |
| Visible model or mode |  |
| Account state | Signed out / signed in / temporary context |
| Clean-context method | New conversation per run |
| Runs per prompt |  |
| Evidence location |  |

## Prompt register

| Prompt ID | Group | Exact prompt | Buyer intent | Target entity or page |
| --- | --- | --- | --- | --- |
| BRAND-01 | Branded identity |  | Recognition |  |
| BRAND-02 | Branded capability |  | Verification |  |
| DISC-01 | Unbranded discovery |  | Selection |  |
| PROB-01 | Problem-led |  | Evaluation |  |
| PROOF-01 | Evidence |  | Trust |  |

Do not include the brand name in an unbranded discovery prompt.

## Response log

| Date | Product/mode | Prompt ID | Run | Entity result | Presence | Recommendation position | Canonical citation | Independent citation | Evidence ID | Limitation |
| --- | --- | --- | ---: | --- | --- | ---: | --- | --- | --- | --- |
|  |  |  | 1 | correct / wrong / mixed / absent / unavailable | mentioned / not mentioned / unavailable |  | URL / none / unavailable | URL / none / unavailable |  |  |

## Outcome definitions

- `correct`: the intended entity and approved canonical domain are resolved.
- `wrong`: the response describes another person or business.
- `mixed`: correct and unrelated claims or sources are combined.
- `absent`: the completed answer contains no target mention.
- `unavailable`: the run or supporting evidence could not be obtained.

Presence is not the same as recommendation. A mention inside a caveat or citation list should not be scored as a direct recommendation.

## Summary

| Measure | Numerator | Denominator | Rate | Unavailable | Notes |
| --- | ---: | ---: | ---: | ---: | --- |
| Correct branded entity resolution |  |  |  |  |  |
| Unbranded mention rate |  |  |  |  |  |
| Unbranded recommendation rate |  |  |  |  |  |
| Canonical-domain citation rate |  |  |  |  |  |
| Independent corroboration citation rate |  |  |  |  |  |
| Wrong or mixed entity rate |  |  |  |  |  |

Only completed, comparable runs belong in the denominator. Disclose every exclusion.

## Change log

| Date deployed | Page/source | Change | Prompt gap addressed | Evidence |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

## Remeasurement

Repeat the unchanged stable prompt subset after a documented recrawl or provider-refresh interval. Keep the original baseline, denominators, raw results, and unfavorable findings.

For an example of the method and its limits, see [AI search visibility measurement](https://www.japhetcordova.com/ai-search-visibility).
