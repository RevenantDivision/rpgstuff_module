# RPG extension for MyBB ACP
This module extends the MyBB Admin Control Panel (ACP) by adding an "RPG Extension" tab. It provides the same hooks as other modules and facilitates the future management of plugins directly from within the ACP. Additionally, the module includes two features:</br>
<br>
- Update Stylesheets: In the event that stylesheets are lost following a MyBB update, those belonging to registered plugins can be restored with a single click.
- Update Plugins: Allows for the integration of update scripts via hooks, enabling plugin updates to be performed conveniently with a single click.

# Setting User Group Permissions
To ensure that all admin accounts have access to the module within the ACP, you must adjust the permissions under the tab Users & Groups » Administrator Permissions » User Group Permissions. The permissions for this module can be found under the 'RPG Extensions' tab; all available options there should be set to 'Yes'.
