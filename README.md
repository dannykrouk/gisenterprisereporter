# arcgisenterprisereporter

The purpose of the tool to document the configuration and administrative settings of an ArcGIS Enterprise deployment.

You point it at the port 7443 endpoint of a Portal for ArcGIS machine, with a Portal administrative account. The tool then crawls through the REST admin api's of the Portal and federated ArcGIS Server Sites.

The outputs include a logical overview diagram, a services inventory (with workspaces and datasets), a Portal content inventory, lists of users and groups, information about TLS/SSL certificates, etc.

You can download "a release" (https://github.com/dannykrouk/arcgisenterprisereporter/releases), which is a zip file with the executables and documentation.  It is recommended that you download the most recent release.  
