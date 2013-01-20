Details

	Automatically allocate units
	
	This allows unit pointers to be used rather than direct units
	
	Never allocate a unit (allocate(MEMORY_TYPE_UNIT))
	Never deallocate a unit (deallocate())
	
	Keep unitref settings for triggers at default, otherwise system will break
	
	Uses
	
		c_unitPropBountyCustom

Status

	Finished

Requirements

	Dynamic Memory Allocator
	
		https://github.com/HiveWorkshop/Galaxy-Code/tree/master/dynamic%20memory%20allocator

Initializer

	initializeUnitIndexer