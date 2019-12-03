# Test xref 


## cross-reference within repository

Reference UIDs in same docset:

1 Inline Xref exists: <xref:b> and Inline Xref not exists: <xref:non-existence>

2 [Inline Xref exists](xref:b) and [Inline Xref not exists](xref:non-existence)

3 Inline Xref exists: @b and Inline Xref not exists: @non-existence

4 Inline Xref exists: <xref href="b"/> and Inline Xref not exists: <xref href="non-existence"/> 


## cross-reference in other repository with query tag ppe-provision-test

Reference UID from different repository: [referenced file](https://github.com/v-pegao/ppe-provision-test/blob/master/ppe-provision-test/another.md):

1 Inline Xref exists: <xref:cross-repo-xref> and Inline Xref not exists: <xref:non-existence>

2 [Inline Xref exists](xref:cross-repo-xref) and [Inline Xref not exists](xref:non-existence)

3 Inline Xref exists: @cross-repo-xref and Inline Xref not exists: @"non-existence"

4 Inline Xref exists: <xref href="cross-repo-xref"/> and Inline Xref not exists: <xref href="non-existence"/> 
