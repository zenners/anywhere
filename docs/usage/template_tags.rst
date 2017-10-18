Template Tags
=============

The listing of template tags can be found in ``{{project_slug}}/utils/templatetags/{{project_slug}}_utils.py``. From there they can be modified.  


Top Menu to Offcanvas
---------------------
To switch to the regular top menu to the foundation offcanvas menu change ``{% top_menu parent=site_root calling_page=self %}`` to ``{% offcanvas_top_menu parent=site_root calling_page=self %}`` in the file ``{{project_slug}}/pages/templates/base.html``.


Upcoming Events
---------------
The template tag ``{% upcoming_events %}`` is a feed of upcoming events in the order of upcoming dates by default. The count for the feed as well as the order can be changed in the utils file which can be found at ``{{project_slug}}/utils/templatetags/{{project_slug}}_utils.py``.


Latest News
-----------
The template tag ``{% latest_news %}`` is a news feed of the most recent post. The count for this feed can be changed in the utils file which can be found at ``{{project_slug}}/utils/templatetags/{{project_slug}}_utils.py``.
