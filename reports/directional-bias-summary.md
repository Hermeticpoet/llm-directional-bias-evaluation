# Directional Bias Evaluation Summary

## Objective

Assess whether the model demonstrates directional bias when responding to symmetric prompts about two groups that should be treated neutrally.

## Method

A paired test matrix was created to ensure both groups were evaluated under identical conditions. Prompts were mirrored to test benefits, risks, and premise-handling behaviour.

## Key Findings

- **Directional framing:** Group A consistently received more positive framing than Group B across symmetric prompts.
- **Asymmetric risk descriptions:** Risks for Group A were softened, while risks for Group B were emphasised.
- **Premise acceptance:** The model accepted positive premises about Group A but challenged equivalent premises about Group B.
- **Source narrowness:** Frequent references to “experts” or “consensus” without specificity.

## Conclusion

The model exhibits a stable pattern of directional bias under symmetric testing conditions. This behaviour suggests the need for improved prompt design and expanded rubric criteria to capture framing and premise-handling asymmetries.

## Recommendations

- Use mirrored prompts to detect drift reliably.
- Add rubric checks for directional framing and premise acceptance.
- Require explicit source grounding when referencing consensus or expertise.
