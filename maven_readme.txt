Ensure the repositories inside maven_settings.xml exist within your Maven's settings.xml file.

Your Maven's settings.xml file can be located at either of the following two locations:
	$M2_HOME/conf/settings.xml
	${user.home}/.m2/settings.xml
	
If you do not have a settings.xml file at either of those two locations, you can rename maven_settings.xml
to settings.xml and place it in either location.

For more information see http://maven.apache.org/settings.html