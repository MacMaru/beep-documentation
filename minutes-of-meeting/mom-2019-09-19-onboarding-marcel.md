Notes 19 sept - Introduction of domain model with Marcel

* Currently, an Inspection has a relation to both a Hive and a Colony. It needs both relations, since the relationship between the inspected Colony and its Hive may change over time. In the same way, the Apiary might also change over time e.g. when a Hive is being moved from location X to Y. for instance when entire orchards are being pollinated. We need to see if this use case is relevant, and if we accept that such usecases indeed are represented by the Apiary itself moving.
* Cardinality of Queen -> Colony: Can a colony have more than one queen, and if so, should we model this?
* SliderInput could be removed from the tree, and represented by a different visualization of a NumericInput.
* Why do InspetionComponents have a component type
* ADR: Why JSON files are used for inspection list visualisation
* Apiaries may be moved. We should maintain a log of Places that an Apiary has been.
* Collaborator: Distinguish between grantor and grantee

