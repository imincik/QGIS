ADD_SUBDIRECTORY(qgis_topoview)

PLUGIN_INSTALL(db_manager db_plugins/postgis/plugins __init__.py)
