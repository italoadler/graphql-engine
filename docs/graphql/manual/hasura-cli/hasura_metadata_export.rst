.. _hasura_metadata_export:

Hasura CLI: hasura metadata export
----------------------------------

Export Hasura GraphQL Engine metadata from the database

Synopsis
~~~~~~~~


Export Hasura metadata and save it in migrations/metadata.yaml file.
The output is a yaml file which captures all the metadata required 
by GraphQL Engine. This includes info about tables that are tracked,
permission rules, relationships and event triggers that are defined 
on those tables.

::

  hasura metadata export [flags]

Examples
~~~~~~~~

::

    # Export metadata and save it in migrations/metadata.yaml file:
    hasura metadata export

Options
~~~~~~~

::

      --access-key string   access key for Hasura GraphQL Engine
      --endpoint string     http(s) endpoint for Hasura GraphQL Engine
  -h, --help                help for export

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura metadata <hasura_metadata>` 	 - Manage Hasura GraphQL Engine metadata saved in the database

*Auto generated by spf13/cobra*
