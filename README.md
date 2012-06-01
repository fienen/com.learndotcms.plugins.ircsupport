IRC Support Portlet Plugin for dotCMS
==================================
Installation
==================================
* Download and extract the plugin package to your {DOTCMS_ROOT}/plugins directory
* Shut down your server ({DOTCMS_ROOT}/bin/shutdown.[sh|bat])
* On your server, run 'ant clean-plugins deploy-plugins'
* Start your server back up ({DOTCMS_ROOT}/bin/startup.[sh|bat])
* Log in to your backend (http://yourhost.com/admin) and go to CMS Admin > Roles, Tabs & Tools
* Select the role that you want to have access to the portlet, then click on the 'CMS Tabs' tab
* Click on the tab name where you'd like the portlet to appear, then in the ensuing popup, select it from the 'tools' dropdown (it will probably be the last one in the list)
* Click 'add', then 'save', the popup will close, then click save on the 'CMS Tabs' page