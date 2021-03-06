Getting Started with MetaRelate
********************************

MetaRelate is a project to relate definitions within metadata schemes: it provides guidance on how to interpret a metadata definition from one scheme within another.

Getting started using the information requires the installation of some software, the project does not yet have a live web interface to the relationships.

The project is hosted on Github, at `MetaRelate <https://github.com/metarelate>`_

The metarelate project uses Python, Django, Jena and Fuseki to provide a repository of translation information, an application programming interface and a user interface.

Software
=========

Metarelate is a knowledge base support system, providing information management for metadata translations.

This project provides software to manage the knowledge base and the knowledge base content. The knowledge is stored as RDF Turtle datasets in data repository, referred to as StaticData.

To contribute to the project, the required static data should be used to populate a local triple store which the management software may access. 

See the README.md for installation instructions.

Use
===

The metarelate API provides programmatic access to the data in the local triple store.  This API enables valid and relevant information to be retrieved and converted to a form which can be used by other applications.

There is more information in the `exporting translations <../exporting/index.html>`_ pages.

For examples of this approach, see how Iris makes use of metarelate and the metOcean-mapping translation information in `iris-code-generators <https://github.com/SciTools/iris-code-generators>`_



Contribution
============

The project aims to collate and manage translation information from many sources.  Contributions to the knowledge base are crucial.

To contribute:

  * Create a branch in your git repository, linked to the main data project your are interested in, and check it out.
  * Load the static data into your local triple store.
  * Use the editor application to add information to the knowledge base.
  * Validate your changes against the information rules in the application.
  * Persist your changes to your local static data store.
  * Propose these changes to the relevant Metarelate github data project as a Pull Request.
