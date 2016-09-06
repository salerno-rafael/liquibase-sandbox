#Liquibase Sandbox
- IDs cannot be repeated, otherwise they will not run
- Scripts should be smalls
- Should be added script Rollback whenever possible
- Must be added new scripts on the changelog.xml
- Everything that was executed is registered on table DATABASECHANGELOG
- Documentation http://www.liquibase.org/documentation/index.html
- To execute:
	* <b>gradle task dev update</b>
	* <b>gradle task qa update</b>
	* <b>gradle task prod update</b>	
