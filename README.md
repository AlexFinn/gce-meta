## gce-metadata

Small and very simple utility to get some metadata for instance on Google Cloud Engine.

Example:

	→ gce-metadata

	NAME:
	   gce-metadata - Small and simple utility to get some metadata of project or instance on Google Cloud Engine.

	USAGE:
	   gce-metadata [global options] command [command options] [arguments...]

	VERSION:
	   0.2

	COMMANDS:
	     help, h  Shows a list of commands or help for one command

	   instance:
	     desc                 The free-text description of an instance, assigned using the --description flag, or set in the API.
	     hostname             The full host name of the instance.
	     instance-name, name  The short host name of the instance.
	     instance-id, id      The ID of the instance. This is a unique, numerical ID that is generated by Google Compute Engine.
	     machine-type, mt     The fully-qualified machine type name of the instance's host machine.
	     zone                 The instance's zone.
	     internal-ip, iip     Internal IP of instance.
	     external-ip, eip     External IP of instance.
	     tags, t              Any tags associated with the instance.
	     attr, a              Attributes passed to the instance during startup or shutdown.

	   project:
	     project-id, p           The project ID.
	     numeric-project-id, np  The numeric project ID of the instance.

	GLOBAL OPTIONS:
	   --help, -h     show help
	   --version, -v  print the version

