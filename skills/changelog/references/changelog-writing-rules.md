# Changelog writing rules

## Release status comes first

- **Released:** the change is available to the stated audience, on the supplied date.
- **Partially released:** availability is limited by audience, region, plan, platform, percentage, or another supplied condition.
- **Planned:** work is intended but not yet available. Keep it separate from released entries.
- **Unknown:** the notes do not prove availability. Treat it as a publication blocker.

Do not infer release status from words such as complete, merged, approved, staged, or ready.

## Entry categories

- **New:** a capability or experience that did not exist for the stated audience.
- **Improved:** an existing experience changed without correcting a stated defect.
- **Fixed:** an observed defect or regression was corrected.
- **Removed or changed behavior:** something no longer exists or requires a person to work differently.

One release may contain all four. Do not force an item into a positive category when it creates required action.

## From work note to entry

For each item, answer:

1. What changed for the audience?
2. Who has it?
3. When did they receive it?
4. Why does it matter, based on supplied evidence?
5. What must a person do, if anything?
6. What limitation or support path must they know?

Implementation details belong only when they change an answer. Internal task IDs, branches, code paths, and private discussion do not belong in customer-facing copy.

## Completeness without noise

Completeness means covering every user-relevant new feature, improvement, fix, removal, and required action in the release boundary. It does not mean copying every internal task. Combine several internal notes when they produced one observable change.

## Publication check

- Every released claim has supplied status and availability.
- Dates use one clear format and refer to user availability.
- Benefits and affected groups have support.
- Breaking behavior and limitations are visible.
- Links and support routes are supplied, not guessed.
- Planned items are separate and labeled.

