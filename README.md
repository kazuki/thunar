## What is it?

Thunar is a modern file manager for the Unix/Linux desktop, aiming to be easy-to-use and fast.


## Required packages

Thunar depends on the following packages:

 - perl 5.6 or above
 - GTK+ 3.22.0 or above
 - GLib 2.42.0 or above
 - exo 0.12.0 or above
 - intltool 0.30 or above

Thunar can optionally use the following packages:

 - D-Bus 0.34 or above (strongly suggested)
 - xfce4-panel 4.14.0 or above (for the trash applet)
 - xfconf-query


## Installation

The file [`INSTALL`](INSTALL) contains generic installation instructions. For more general information, check the [Thunar documentation](https://docs.xfce.org/xfce/thunar/start).


## Debugging Support

Thunar currently supports four different levels of debugging support, which can be setup using the configure flag `--enable-debug` (check the output of `configure --help`):

| Argument  | Description |
| -------   | ----------- |
| `full`    | Use this if you want to debug Thunar to locate a bug. The build will most probably be noticably slower. This is also recommended for people that want to develop Thunar stuff. |
| `yes`     | Adds all kinds of checks to the code, and is therefore likely to run slower. Use this if you want to develop for Thunar (e.g. writing Thunar extensions and such). |
| `minimum` | This is the default for release builds, and presents the recommended behaviour. |
| `no`      | Disables all sanity checks. Don't use this unless you know exactly what you do. |


## Standards compliance

Thunar supports the following standards/specifications:

  * [XDG Base Directory Specification](https://freedesktop.org/wiki/Specifications/basedir-spec)
  * [Shared MIME Database Specification](https://freedesktop.org/wiki/Specifications/shared-mime-info-spec)
  * [X Direct Save (XDS) Protocol for the X Window System](https://freedesktop.org/wiki/Specifications/direct-save)
  * [Icon Theme Specification](https://freedesktop.org/wiki/Specifications/icon-theme-spec)
  * [Thumbnail Managing Standard](https://freedesktop.org/wiki/Specifications/thumbnails)
  * [File URI Specification](https://freedesktop.org/wiki/Specifications/file-uri-spec)
  * [Desktop Trash Can Specification](https://freedesktop.org/wiki/Specifications/trash-spec)


## How to report bugs?

Bugs should be reported to [Xfce's GitLab](https://gitlab.xfce.org/xfce/thunar). You will need to create an account for yourself.

Please read [how to report bugs ](https://docs.xfce.org/contribute/start#bug_reporting_and_testing) for information on where to send changes or bugfixes.
