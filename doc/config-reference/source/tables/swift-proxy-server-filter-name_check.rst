..
  Warning: Do not edit this file. It is automatically generated and your
  changes will be overwritten. The tool to do so lives in the
  openstack-doc-tools repository.

.. list-table:: Description of configuration options for ``[filter-name_check]`` in ``proxy-server.conf``
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - ``forbidden_chars`` = ``'"`<>``
     - Characters that are not allowed in a name
   * - ``forbidden_regexp`` = ``/\./|/\.\./|/\.$|/\.\.$``
     - Substrings to forbid, using regular expression syntax
   * - ``maximum_length`` = ``255``
     - Maximum length of a name
   * - ``use`` = ``egg:swift#name_check``
     - Entry point of paste.deploy in the server
