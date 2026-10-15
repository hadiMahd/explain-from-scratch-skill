---
name: explain-from-scratch-skill
description: Explain any concept from scratch by first teaching all the prerequisite concepts it relies on, starting from the very beginning, and explaining any sub-concepts or technical terms mentioned along the way. Use whenever the user asks to explain a concept, mechanism, formula, or topic from scratch, from zero, or step by step.
---
# Explain From Scratch

Explain any target concept by first identifying and teaching every prerequisite concept it depends on from the ground up, while also unpacking any secondary terms or sub-concepts mentioned along the way. Instead of jumping straight into high-level definitions or glossing over jargon, build understanding step by step from Concept 1 up to the target concept.

## When to Use

- The user asks to explain a concept, theory, mathematical operation, algorithm, system, or mechanism.
- The user asks to learn how something works "from scratch", "from zero", "from the beginning", or "step by step".
- Understanding the target topic requires understanding earlier building blocks first (Concepts 1 through N-1 before Concept N).

## Steps

1. **Map the Prerequisite Chain**
   Identify the target concept (Concept N) and trace backward to find the foundational concepts it relies on (Concept 1 -> Concept 2 -> ... -> Concept N). Show this path briefly at the start so the user can see how the ideas build on each other.

2. **Start at the Beginning (Concept 1)**
   Begin with the most basic concept in the chain. Explain it in plain, everyday language with a concrete example and zero unstated assumptions.

3. **Build Up Step by Step (Concepts 2 to N-1)**
   Introduce each new concept purely as the next logical step from the previous one. Show how and why it comes from the earlier step.

   - Example: When explaining multiplication (5 x 3), do not start with multiplication tables or rules. Start with counting and addition (Concept 1), then show how adding the same number repeatedly creates summation n times (5 + 5 + 5, Concept 2), which is what multiplication actually is.

4. **Explain Mentioned Sub-Concepts Along the Way**
   Whenever you mention a related sub-concept, component, or technical term during your explanation, explain it inline right when you introduce it rather than assuming the user already knows it.

   - Example: If you are explaining databases and mention "indexing", immediately explain what indexing is and how it works (such as comparing it to a book's index that points directly to the right page instead of scanning every row) before continuing.

5. **Explain the Target Concept (Concept N)**
   Once all prior concepts and inline sub-concepts are clear, explain the target concept as the natural result of the chain, and walk through a complete example that connects every step.

## Gotchas

- **Never skip a prerequisite step**: Do not use a technical term or rule unless you have already explained it earlier in the chain or unpack it immediately inline.
- **No drive-by jargon**: Never mention a secondary mechanism or term (like "indexing", "hashing", or "caching") in passing without briefly explaining what it does along the way.
- **Connect every step to the one before it**: Each step should flow directly from the previous one rather than reading like a list of separate definitions.
- **Pick a practical starting point**: Start Concept 1 at the core building block of that topic (for example, addition for multiplication, or memory addresses for pointers) so the explanation stays clear and focused.
