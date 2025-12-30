# 5. Conflicts, Ambiguity, and Failure States

This section defines how Panzlian handles ambiguity, contradictions, and reading failures.
It establishes safe limits for skimming, recursion, and modifier placement.

## 5.1 Ambiguity in Nucleos

- Some nucleos may be inherently ambiguous, especially when composed of merged attributes.
- Context is required to fully interpret ambiguous nucleos.
- Ambiguity does not invalidate identity; it only affects behavioral interpretation.

## 5.2 Weak Orbitals (Bottom-Left and Bottom-Right)

- Weak orbitals alter behavior and context only.
- Weak orbitals cannot contradict strong links (internal defining attributes).
- Misplaced or incorrectly interpreted weak orbitals are considered bad writing.

## 5.3 Prefixes and Suffixes

- Prefixes and suffixes encode relational context (ownership, gender, number, known/unknown articles).
- Skipping prefixes or suffixes may create contextual ambiguity but does not create internal contradictions.
- Placement relative to the root ensures proper hierarchy and influence.

## 5.4 Identity Preservation

- Identity is guaranteed as long as root and strong nucleos attributes are read.
- Readers may skip:
  - Attribute stack (bottom-right orbitals)
  - Prefixes and suffixes (if relational context is known)
- Readers should avoid skipping strong nucleos attributes unless the text is already familiar or contextually obvious.

## 5.5 Hierarchy

- Proximity to the root determines influence.
- Left orbital children only affect their parent orbital; they cannot influence the main nucleos.
- Placement guarantees safety and prevents conflict between layers.
- Hud or transformation markers obey the same hierarchy rules.

## 5.6 Recursive Orbitals

- Recursion is allowed but rare.
- Sub-orbitals only affect their immediate parent orbital.
- Recursive structures cannot override nucleos identity.
- Reading order of recursive orbitals follows the same right→left, top→bottom priority.

## 5.7 Summary

- Nucleos can be naturally ambiguous; context resolves uncertainty.
- Weak orbitals, prefixes, and suffixes modify but do not contradict core identity.
- Skimming is safe when respecting proximity hierarchy.
- Placement guarantees that conflicts are avoided.
- Recursive orbitals follow the same influence rules and cannot corrupt identity.
