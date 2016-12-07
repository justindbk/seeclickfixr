## Release notes seeclickfixr version 1.1.0

This new version provides one fix and one minor update

First, documentation now explains that the city field must now be entered as iut is specified in the "url_name" field returned by list_places().

Second, requests for more than 100 results now correctly return the full number of results by checking against the metadata for ewach request in the SeeClickFix API.

