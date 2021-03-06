Integrated apps
===============

drf-saas-starter ships with some apps.

User
----

A custom user with some special features:

* E-Mail required for sign up / sign in

Fore more information read :doc:`users`.

Tenants
-------

Handling for multi-tenancy. It takes care, that a user belongs to one or many tenants.

* A registration for users within a tenant
* The possibility for invites by a tenant
* Tenant Middleware for accessing tenant resources

For more information read :doc:`users`.


Mails
-----

Handling of mails. It has some features:

* It uses django-anymail for sending with Sendgrid
* Saving mails to the database
* Use of dynamic mail templates

Fore more information read :doc:`email`.


Comments
--------

The functionality to add comments of objects in any model, e.g. an individual user:

* Can be used for any model.
* Doesn't change the commented model.
* Fast setup for ViewSets.

Fore more information read :doc:`comments`.


Activities
----------

Connection between Django Activity Stream and Django REST Framework.

Fore more information read :doc:`activities`.
