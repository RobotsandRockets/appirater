RnR version of Appirater
------------

1. Removed resources from podspec `  s.resources         = '*.lproj'`
	* This allows for custom Appirater resource strings in the client app by not automatically including the resources.
	* The client app must provide it's own copy of Appirater string resource strings.
