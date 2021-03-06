
CHANGELOG
====

v1.1.0-rc.10
----
 * Released without any changes.

v1.1.0-rc.9
----
 * localkit: Return `frameworkVersion` when calling `Localkit.getProject()` function.
 * localkit: Now `Localkit` emits `live-reload` event when the file has changed.

v1.1.0-rc.8
----
 * localkit: Fixed bug when serving multiple projects.

v1.1.0-rc.7
----
 * monaca: Added `isBuildOnly` parameter to `Monaca.createProject()` API.
 * monaca: Rewrote `Monaca.getTemplates()` method to get templates from Monaca Cloud.
 * monaca: Added `Monaca.createFromTemplate()` method to create a project from a template in Monaca cloud.
 * monaca: Added `disableStatusUpdate` parameter to `Monaca.getLatestNews()`.
 * localkit: Added `Localkit.startWatchProject()`, `Localkit.stopWatchingProject()` and `Localkit.isWatchingProject()` for more granular control.
 * monaca: Added `options.language` parameter.
 * monaca: Added `options` object to `Monaca.relogin()`. Works exactly like the parameters for `Monaca.login()`.
 * localkit: Added `Localkit.initInspector()` method.
 * localkit: Fixed `Localkit.startWatch()` so it will always be resolved.
 * monaca: Return whole response body in `Monaca.login` instead of just the message.
 * monaca: Added `Monaca.download()` method.
 * localkit: Removed nw.js dependency.
 * localkit: `Localkit` object is now an event emitter.
 * localkit: Fixed `Localkit.stopHttpServer` so it will work even if clients are connected to SSE.
 * localkit: Kill adb processes on shutdown.
 * localkit: Add ability to override config.xml project name in `Localkit.addProject()` and `Localkit.setProjects()`.
 * monaca: Don't save cloud project id in `Monaca.cloneProject()`.
 * monaca: Return whole JSON response when making requests to Monaca Cloud.

v1.0.4
----
 * monaca: Added `Monaca.getLatestNews()` to fetch latest news and status on known issues from Monaca Cloud.
 * localkit: Added `options.clientId` to `Localkit.startProject()` method. Used to start a project on one device instead of sending the start signal to all connected devices.
 * localkit: Added `Localkit.startInspector()` to start an inspector when the computer is connected to Localkit.
 * monoaca: Added `Monaca.isMonacaProject()` to check if a directory is a Monaca project.

v1.0.3
----
 * monaca: Added `options` parameter to `Monaca.login()` to specify version.
 * monaca: Added `Monaca.isCordovaProject()` to check if a directory is a Cordova project.

v1.0.2
----
 * monaca: Fixed bug where .cordova directory was not created correctly when missing.

v1.0.1
----
 * monaca: Added configuration methods.
 * monaca: Added proxy support.

v1.0.0
------
 * Initial version.
