---
'@keystonejs/server-side-graphql-client': minor
---

Enhanced the `getItems` functionality by adding: 
- `sortBy`
- `first`
- `skip`

These variable are part of the public interface, and allow users to achieve some advance use cases like sorting and skipping.

**Note**: We are still keeping the internal pagination behaviour as it is, but now prioritising `first` over the `pageSize`.

