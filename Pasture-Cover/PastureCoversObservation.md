 - <b id="#/properties/category">category</b>
	 - **Description:** Type of Observation recorded - Block, Paddock, Field or Grazing
	 - **Type:** `string`
 - <b id="#/properties/date">date</b>
	 - **Description:** Date (and depending on Observation, time) at which the Observation was made. For some events, the time component of the Observation is critical (for instance, a Milk Yield Observation). For others, (such as condition score), the rate of change is slow enough that time is irrelevant.
	 - **Type:** `string`
 - <b id="#/properties/blockId">blockId</b>
	 - **Description:** Identifier for the block being assessed.Usuually recorded as a block number or code used by the farm
	 - **Type:** `string`
 - <b id="#/properties/identifiers">identifiers</b>
	 - **Description:** A code used by the source system to identify the farm, such as an internally meaningful identifier
	 - **Type:** `array`
 - <b id="#/properties/items">items</b>
	 - **Description:** Reference to access details of the Observation Items recorded
	 - **Type:** `array`
	 - <b id="observationitemobservationitem.md">Link to schema: [ObservationItem](ObservationItem.md)</b>

_Generated with [json-schema-md-doc](https://brianwendt.github.io/json-schema-md-doc/)_