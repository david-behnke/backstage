---
'@backstage/plugin-search-react': minor
---

- Add `noTrack` property to `DefaultResultListItem` component, this new property is optional and it disables event tracking;
- Create the search results extensions, for more details see the documentation [here](https://backstage.io/docs/features/search/how-to-guides#how-to-render-search-results-using-extensions);
- Update the `SearchResult`, `SearchResultList` and `SearchResultGroup` components to use extensions and default their props to optionally accept a query, when the query is not passed, the component tries to get it from the search context.
