# Merge Conflict Demonstration and Resolution

## Objective

The objective was to demonstrate how Git detects conflicting changes when two branches modify the same line in a file.

## Steps Performed

1. Created `feature/conflict-version-a` from `main`.
2. Created `feature/conflict-version-b` from `main`.
3. Modified the same sentence in `README.md` differently on both branches.
4. Merged Branch B into `main`.
5. Attempted to merge Branch A into `main`, which produced a content conflict.
6. Opened `README.md` and examined Git's conflict markers.
7. Combined the two versions into one sentence, removed the conflict markers, staged the file, and committed the resolution.

## Conflict Resolution

The conflicting versions described how Git tracks project history and how GitHub supports online collaboration. The final sentence combined both ideas:

"Git records and preserves project history, while GitHub hosts repositories and supports online collaboration."

## Result

The conflict was resolved manually, and the merge was completed with a commit. This exercise demonstrated how Git identifies incompatible changes and how a developer resolves them before completing a merge.

## Lessons Learned

- Conflicts can occur when branches modify the same lines differently.
- Git uses conflict markers to identify competing changes.
- Developers must review and resolve conflicts before committing the merge.
- Testing and checking the repository status helps verify the resolution.