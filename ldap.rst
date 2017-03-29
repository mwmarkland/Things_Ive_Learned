LDAP Notes
----------

.. _Wikipedia: https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol
.. _here: http://stackoverflow.com/questions/18756688/what-are-cn-ou-dc-in-an-ldap-search

The basics are coming from Wikipedia_.

Really, I think at its most basic the issues with LDAP are understanding its vocabulary for describing things.

Working from the example in Wikipedia, typing stuff out to try and understand

``dn:  cn=John Doe,dc=example,dc=com``

DN
    **Distinguished Name.** Not an attribute or part of the entry.

RDN
    **Relative Distinguished Name**. In this case ``cn=John Doe``.

DC
    **Domain Component**.

Entries are trees and a server holds a subtree starting at a specific
entry, ``dc=example,dc=com`` for example. Servers also hold references
to other servers.

The StackOverflow entry here_ is very informative also.

Operations
==========

The one I'm most interested in is **Bind (authenticate)**. This sets
the authentication state for the session. Sessions always start as
*anonymous* until this operation occurs.

URI Scheme
==========

``ldap://host:port/DN?attributes?scope?filter?extensions``

DN is the distinguished name to use as the search base.
attributes is a comma-separated list of attributes to retrieve.
scope specifies the search scope and can be ``base``, ``one``, or ``sub``.

Example: ``ldap//ldap.example.com/cn=John%20Doe,dc=example,dc=com``
yields all user attributes in John Doe's entry on that LDAP server.


