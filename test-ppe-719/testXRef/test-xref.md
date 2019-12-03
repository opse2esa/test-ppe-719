# Test xref 


## cross-reference within repository

Reference UIDs in same docset:

1 Inline Xref exists: <xref:b> and Inline Xref not exists: <xref:non-existence>

2 [Inline Xref exists](xref:b) and [Inline Xref not exists](xref:non-existence)

3 Inline Xref exists: @b and Inline Xref not exists: @non-existence

4 Inline Xref exists: <xref href="b"/> and Inline Xref not exists: <xref href="non-existence"/> 


## cross-reference in other repository with query tag ppe-provision-test

All usages with [referenced file](https://github.com/v-pegao/ppe-provision-test/blob/master/ppe-provision-test/index.md):

1 Inline Xref exists: <xref:cross reference index.md in repository ppe-provision-test> and Inline Xref not exists: <xref:non-existence>

2 [Inline Xref exists](xref:"cross reference index.md in repository ppe-provision-test") and [Inline Xref not exists](xref:non-existence)

3 Inline Xref exists: @"cross reference index.md in repository ppe-provision-test" and Inline Xref not exists: @"non-existence"

4 Inline Xref exists: <xref href="cross reference index.md in repository ppe-provision-test"/> and Inline Xref not exists: <xref href="non-existence"/> 
