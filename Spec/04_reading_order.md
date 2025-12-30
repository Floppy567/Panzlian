# 4. Reading Order and Skimming

This section defines how word groups are read, which layers are mandatory, and which layers may be skipped without breaking meaning.
Reading order in Panzlian is spatially and hierarchically defined.

## 4.1 Absolute Reading Order

Panzlian word groups are read in the following order:

1. Attribute stack (bottom-right orbitals), top to bottom
2. Prefixes (all located to the right of the root)
3. Nucleos attributes (strong links), read from right to left
4. Root (central)
5. Continuation orbital (bottom-left)
6. Suffixes (bottom-left of last orbital, may have children)
7. ‘Y bridge, if present (relational marker)

- Placement dictates influence. Elements closer to the root carry more weight.
- The reading order may be partially skipped without breaking identity.
- Bridges like ‘Y are treated as relational overlays and read last.

## 4.2 Mandatory Layers

- Nucleos attributes (strong links)
- Root
- Continuation orbital (bottom-left)

## 4.2 Optional Layers

- Attribute stack (bottom-right orbitals)
- Prefixes (if identity is known)
- Suffixes (if relational context is known)

## 4.3 Prefixes

- Located to the right of the root
- May be multiple
- Read immediately after the attribute stack

## 4.3 Suffixes

- Located to the bottom-left of the last bottom-left orbital
- May have children
- Influence decreases with distance from the root
- Read last among positional elements

## 4.4 Skimming Tiers

1. **Full resolution**
   - Read all layers in absolute order
   - Provides complete identity, behavior, and context

2. **Intermediate scan**
   - Skip attribute stack (bottom-right orbitals)
   - Optionally skip prefixes and suffixes if context is clear

3. **Identity scan**
   - Read only root and nucleos attributes
   - Skip leftmost nucleos attributes first if necessary
   - Guarantees identity preservation, behavior may be partially lost

- Skimming is supported by spatial placement
- Reader intuitively infers missing layers based on position
- Contradictions rarely occur; weak orbitals and Hud-like markers encode contextual changes without breaking identity

## 4.5 Conflict Resolution

- Strong links define identity and cannot be overridden by orbitals or prefixes/suffixes
- Weak orbitals and Hud-type modifiers may alter interpretation but do not contradict identity
- Placement determines which element has greater influence

## 4.6 Summary

- Reading order is spatial: right-to-left horizontally, top-to-bottom vertically
- Root + strong links + bottom-left orbital are mandatory
- Attribute stack, prefixes, and suffixes are optional for identity
- Skimming tiers allow controlled omission without losing core meaning
- ‘Y bridges and relational markers are read last
