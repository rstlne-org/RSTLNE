###### Fields

| subject  | predicate        | object           |
|:---------|:-----------------|:-----------------|
| GUTS/IRI | GUTS/IRI/literal | GUTS/IRI/literal |

###### Functionality

| read   | write         | execute        |
|:-------|:--------------|:---------------|
| SELECT | INSERT/UPDATE | START...COMMIT |

###### Q&A

| questions | answers    |
|:----------|:-----------|
| who       | people     |
| where     | places     |
| when      | times      |
| why       | tasks      |
| what      | hard wares |
| how       | soft wares |
| did       | true/false |

###### AuthNZ

| store  | shared with     |
|:-------|:----------------|
| red    | mallory         |
| orange | everyone        |
| yellow | guests          |
| green  | friends/members |
| blue   | family/admins   |
| indigo | daemons         |
| violet | self            |

###### Operations

1. initialize store
2. create a (non-literal) subject
3. create a (non-literal) predicate
4. this predicate+object combination describes that subject
5. this predicate+object combination no longer describes that subject
6. select all subjects
7. select subject(s) for one predicate+object combination
8. select predicate+object combinations for one subject
9. select all predicates (for one subject)
10. select object(s) for one subject+predicate combination
11. select objects for one predicate
12. consolidate subjects

* * *

> 20210225
