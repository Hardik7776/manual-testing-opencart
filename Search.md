# Search Test Cases

| Test Case ID | Test Case | Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|
| TC_SEARCH_001 | Exact search | Search exact product name | MacBook | Relevant product should appear | Medium | Not Run |
| TC_SEARCH_002 | Partial search | Search partial product name | Mac | Relevant products should appear | Medium | Not Run |
| TC_SEARCH_003 | No results | Search nonexistent term | ZZZ-NO-PRODUCT | No-results message should appear | Medium | Not Run |
| TC_SEARCH_004 | Case variation | Search upper/lower case | MACBOOK | Results should follow search rules | Low | Not Run |
| TC_SEARCH_005 | Leading/trailing spaces | Search with extra spaces |   MacBook   | System should handle whitespace appropriately | Low | Not Run |
| TC_SEARCH_006 | Special characters | Search with symbols | @@@ | System should handle input without error | Medium | Not Run |
| TC_SEARCH_007 | Sorting | Search and change sort order | MacBook; price | Results should reorder correctly | Medium | Not Run |
| TC_SEARCH_008 | Pagination | Open next results page | Common keyword | Next page should load correctly | Medium | Not Run |
| TC_SEARCH_009 | Result count | Compare result count with displayed products | Common keyword | Count/pagination should be consistent | Low | Not Run |
| TC_SEARCH_010 | Category search | Search from category context where supported | Category/product keyword | Relevant results should display | Medium | Not Run |
