The repository holds the xapi test package.

You an view the adapt module at https://xapi-test.learndata.info

The standalone build (basically this repository), with XAPI endpoint, key etc configured, is available as a zip in build-standalone.zip

The build for inclusion in a LMS, without XAPI endpoint configured, is available as a zip in build-stream.zip

The src-export that can be imported into an authoring tool is available in src-export.zip

Note that this build requires the ODI's version of the adapt-contrib-xapi plugin, based upon 0.8.3. It should be included in the zip file, however if you have a newer version of the xapi plugin installed you will need to manually overwrite this with the version avaiable here:

https://github.com/theodi/adapt-contrib-xapi/tree/odi-guid-0.8.3
