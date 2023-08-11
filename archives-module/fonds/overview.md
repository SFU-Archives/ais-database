###### [AIS Documentation](../../README.md) > [Archives Module](../overview.md)
###### [Accessions](../accession/overview.md) `|` [Block Reviews](../block-review/overview.md) `|` Fonds `|` [Informal Access Reviews](../informal-access-review/overview.md) `|` [Inquiries](../inquiry/overview.md) `|` [Processing Projects](../processing-project/overview.md) `|` [Research Products](../research-product/overview.md)
###### Overview `|` [Create new records](create-new-record.md) `|` [Edit records](edit-record.md) `|` [Reports and actions](reports-actions.md) `|` [DB structure](db-structure.md)

# Fonds: Overview
`Fonds` and `Collections` represent the highest level of arrangement and description in the Archives' holdings.
- A `Fonds` is the whole of the records that a person, family, or corporate body accumulated in the course of its activities.
- A `Collection` is an artificial assemblage of documents about a person, family, corporate body, or thematic subject.

The AIS `Fonds` table registers and tracks both fonds and collections, using a field (`identity__typeHoldings`) to distinguish the two. The table's main purposes are to:
- Generate unique identifiers (in the form "F-n").
- Support statistical reporting on the Archives' holdings and activities.

Fonds identifiers (`refCode` field) are used throughout the system to link various other entities (e.g. `Accessions`, `AIPs`, `Containers`) to the record aggregates to which they belong or otherwise relate.

Note that AIS `Fonds` record contains minimal descriptive data. The Archives uses [SFU AtoM](https://atom.archives.sfu.ca) as its platform for full archival description. AIS `Fonds` records are linked to their AtoM counterpart through AtoM's predictable urls based on the reference code, e.g. `https://atom.archives.sfu.ca/f-10` = Fonds F-10 (Kate Braid fonds).

In this section:
- [Create new records](create-new-record.md)
- [Edit records](edit-record.md)
- [Reports and actions](reports-actions.md)
- [Database table structure](db-structure.md)

###### Last updated: Aug 10, 2023
