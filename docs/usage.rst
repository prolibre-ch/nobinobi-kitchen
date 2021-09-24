=====
Usage
=====

To use Nobinobi Kitchen in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'nobinobi_kitchen.apps.NobinobiKitchenConfig',
        ...
    )

Add Nobinobi Kitchen's URL patterns:

.. code-block:: python

    from nobinobi_kitchen import urls as nobinobi_kitchen_urls


    urlpatterns = [
        ...
        url(r'^', include(nobinobi_kitchen_urls)),
        ...
    ]
