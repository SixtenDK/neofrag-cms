# NeoFrag CMS Change Log

## [Alpha 0.1.2](https://github.com/NeoFragCMS/neofrag-cms/tree/alpha0.1.2) (2015-10-04)
[Change Log](https://github.com/NeoFragCMS/neofrag-cms/compare/alpha0.1.1...alpha0.1.2)

**Features**

- Adding ajax popover mini user profile
- Permissions management

**Core**

- [Config][Fixes #3] Remove getallheaders function (was useless)
- [Group] Fix group url
- [Session] Crawlers detection
- [Session] Improving __destruct for always save user_data
- [Template] Adding loader arg for callbacks

**Helpers**

- [Assets] Adding fa-fw class for Font Awesome icons
- [Buttons] Standardization of adding buttons and changing color to btn-primary
- [File] Move is_asset function from Assets
- [Output] Improving output function
- [String] Improving links detection and adding @Username format support
- [String] Improving url_title function
- [Time] Fix time_span function

**Libraries**

- [Form] Fix &nbsp; in text editor
- [Form] Fix some comparison bugs
- [Form][Fixes #4][Fixes #5] Trim and htmlentities all post entries before the validity check
- [Table] Add number of results
- [Table] Adding td option to return td tags in content
- [Table] Global improving

**LiveEditor**

- Fix widget selectors

**Modules**

- [Forum] Responsive improving
- [Page] Remove link when unpublished and add check page path unicity
- [Teams] Adding the sorting of teams and roles

**Themes**

- [Admin] Global improvement
- [Default] Removing container:'body' for tooltips (and forcing to data-container="body" when needed)
- Removing @import url in css to increase downloading and files caching

**Security**

- Remove templating for security and performances
- XSS vulnerabilities

**Plugins updates**

- Font Awesome v4.4

## [Alpha 0.1.1](https://github.com/NeoFragCMS/neofrag-cms/tree/alpha0.1.1) (2015-07-23)
[Change Log](https://github.com/NeoFragCMS/neofrag-cms/compare/alpha0.1...alpha0.1.1)

**Features**

- Themes management and customization

**Classes**

- [Library] Add copy method
- [Widget_View] Fix error empty settings
- [Zone] Display profiler after row containing the module

**Core**

- [Assets] Force download only for .zip files
- [Config] Adding type argument to update settings
- [Config] Fix config in .css .js files
- [Config] Global improving for ajax requests
- [Config] Insert setting in database if not exists
- [Groups] Fix bugs
- [Database] Add HAVING clause
- [Output] Add .module .module-admin .module-... classes to back-office
- [Session] Fix history url bug

**Helpers**

- [Color] New helper
- [File] Add rmdir_all function to remove non empty directories
- [File] Improving image_resize function: keeping the aspect ratio and transparency for .gif pictures

**Libraries**

- [Editor] BBcode update
- [File] Code improvement
- [Form] Color-picker improvement
- [Form] Fix color selector bug
- [Form] Fix file deletion returned value
- [Form] Fix file input required
- [Form] Global improvement of library and update icon-picker plugin

**Modules**

- [Contact] Fix icon envelope
- [Forum] Adding subforums and url forums
- [Forum] Fix bug is_authorized
- [Gallery] New module
- [Members] Add back button
- [Teams] Fix check_team sql
- [Teams] Fix players list
- [User] Add checking of birthday
- [User] Fix delete session bug

**Themes**

- [Admin] Fix toggle button to hide sidebar
- [Admin] Remove div end tag not opened
- [Default] Adding internal customisation
- [Default] Default popover container is body and default trigger is hover

**Widgets**

- [Forum][Statistics] Fix announces counter
- [Gallery] New widgets
- [Header] Adding alignment, colors and titles configuration
- [Members][Online] Fix counting online users bug
- [Navigation] Accept https url and fix delete button bug
- [Teams] New widget

**Plugins updates**

- Bootstrap v3.3.5
- Bootstrap-Iconpicker v1.7.0 (https://github.com/NeoFragCMS/bootstrap-iconpicker)
- Bootstrap-Colorpicker v2.2 (https://github.com/NeoFragCMS/bootstrap-colorpicker)
- WysiBB v1.5.1 (https://github.com/NeoFragCMS/wysibb)

## [Alpha 0.1](https://github.com/NeoFragCMS/neofrag-cms/tree/alpha0.1) (2015-05-31)