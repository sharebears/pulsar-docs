Forums
======

.. qrefflask:: app:create_app('config.py')
   :undoc-static:
   :blueprints: forums.routes
   :order: path

Categories
----------

.. autoflask:: app:create_app('config.py')
   :undoc-static:
   :modules: forums.routes.categories
   :groupby: view
   :order: path

Forums
------

.. autoflask:: app:create_app('config.py')
   :undoc-static:
   :modules: forums.routes.forums
   :groupby: view
   :order: path

Threads
-------

.. autoflask:: app:create_app('config.py')
   :undoc-static:
   :modules: forums.routes.threads
   :groupby: view
   :order: path

Posts
-----

.. autoflask:: app:create_app('config.py')
   :undoc-static:
   :modules: forums.routes.posts
   :groupby: view
   :order: path

Polls
-----

.. autoflask:: app:create_app('config.py')
   :undoc-static:
   :modules: forums.routes.polls
   :groupby: view
   :order: path
