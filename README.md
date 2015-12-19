# Automatic DNS prefetch

Modern browsers allow pages to prefetch DNS records of external libraries. This plugin looks through WordPress enqueued scripts and styles and adds DNS prefetch statements for scripts and stylesheets added by other plugins.

This means that when the browser comes to download an external script or stylesheet, it already has looked up the DNS record for the external domain, and can proceed immediately to downloading the script, saving latency during loading of external resources.

Plugin page : [Automatic DNS prefetch plugin @ mabujo](https://mabujo.com/)

## Installation

Installing "Automatic DNS prefetch" can be done either by searching for "Automatic DNS prefetch" via the "Plugins > Add New" screen in your WordPress dashboard, or by using the following steps:

1. Download the plugin via WordPress.org
2. Upload the ZIP file through the 'Plugins > Add New > Upload' screen in your WordPress dashboard
3. Activate the plugin through the 'Plugins' menu in WordPress

You can also download from GitHub : https://github.com/mabujo/Automatic-DNS-Prefetch/archive/master.zip or composer.