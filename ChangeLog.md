# Version 1.9.4 Nov 15th, 2019

- Fixes a bug in the search (closes #263)

# Version 1.9.3 Novc 15th, 2019

- Upgrade ecstatic to a safer version
- Fixes a bug rendering for bracket tags (closes #261)

# Version 1.9.0, 1.9.1 Dec 15th, 2018

- Sanitize HTML by default, escaping it while rendering Markdown. Esplicitely enable html rendering again with the `allowHtml` option set to `true`. Remember that this will also enable rendering of <script> though, so beware (Jingo session cookie is http only)

# Version 1.8.5, Feb 25th, 2018

- Merges #236

# Version 1.8.4, Feb 25th, 2018

- Closes #234 (Conflicts created by auto-generated HTML ids)
- Updates ecstatic module to newer and safer version

# Version 1.8.3, May 28th, 2017

- Updates to LDAP authentication (#212 by @ScreamingHawk)

# Version 1.8.2, May 20th, 2017

- Closes #152 (You can now disable Gravatar)
- Closes #129 (Adds logo support)
- Fixes #216 ()
- Always uses local jQuery and not Google's
- Adds favicon support

# Version 1.8.1, May 17th, 2017

This is just a small fix release

- Fix #211 (pug migration regression bug)
- Merge #209 (pug migration regression bug)
- Adds @ScreamingHawk to contributors

# Version 1.8.0, March 11th, 2017

- Upgrade from Jade to Pug 2 (needed for copyright reasons)
- Removes support for Markitup
- Upgrade to jQuery 2.x
- Upgrades of various npm modules
- Removes the need of installing mocha globally (for testing)
- Removes obsolete script directory

# Version 1.7.3, January 8th, 2017

- Small set of fixed: merges #189, #190 and #191

# Version 1.7.2, December 4th, 2016

- Closes #183 (accessible document list)
- Closes #182 (case insensitive test on SHA-1 passwords)
- Reads Jingo version from packages.json (no manual edit for version bump)

# Version 1.7.1, November 5th, 2016

- Merges #179
- Refines README
- Adopts Standardjs as the formatting standard for the project

# Version 1.7.0, September 18th, 2016

- Fixes #164 (ProxyPath not used on /login)
- Adds LDAP authentication support (@everpcpc). Requires manual installation of `passport-ldapauth`

# Version 1.6.1, January 27th, 2016

- Fixes #132 (crash on empty repos)
- Renames an img so to not have problems with AdBlock

# Version 1.6.0, December 28th, 2015

- Ability to work behind a proxy directory #124 (@creynold, @claudioc)
- Enables CORS for /wiki pages (poor man read only API to pages) (@kaiserfro, @claudioc)
- Started the Github wiki with some "recipes" for common tasks and configurations
- Better documentation for the configuration options
- Adds a linter configuration (eslint) and fixes a lot of style issues
- Adds the CONTRIBUTING file
- Adds more tests
- Fixes a TOC bug (@creynold)
- Fixes #118
- Fixes a crash on a certain git configuration

Requires `npm install`

# Version 1.5.3, December 14th, 2015

- Adds the `redirectURL` to the configuration (#121)

# Version 1.5.2, December 14th, 2015

- Fixes an authentication bug on 1.5.1 (#120)

# Version 1.5.1, December 12th, 2015

DO NOT USE THIS VERSION

# Version 1.5.0, December 12th, 2015

- Adds the ability to revert to a specific revision from the history page (@brad7928)
- Adds support for directives (see PR #115) (@creynold)
- Adds support for Table of Contents (@creynold and @brad7928)
- Adds a new `emptyEmailMatches` configuration parameter (see README)
- Added the /etc configuration directory (for useful configurations we may need)
- Fixes #110 (@brad7928)
- Fixes #109
- Fixes #10

- Merged #115, #113, #110

# Version 1.4.1, October 17th, 2015

- Fixes #68, CSS support for markdown tables
- Removes deprecated `licenses` object in packages.json

# Version 1.4.0, October 11th, 2015

- Fixes a bug on header rendering (closes #93)
- Removes iconv and uses the transliteration module (finally!)

The version is coded 1.4.0 because removing iconv may create some regression of old installations.

# Version 1.3.1, October 4th, 2015

- Upgrades CodeMirror to 5.7
- Uses _github flavoured markdown_ as the default CodeMirror mode (Closes #99)
- Uses github username if the displayName is empty (Closes #95)

# Version 1.3.0, July 19th, 2015

- Fixes #80 – Crash when a title starts with /
- Fixes #87 – Better management of slashes in titles (replaced by "+")
- Adds the search form to the search pages, so that we could...
- ...show the login option on mobile (removes the search field) because we...
- ...added the search icon to the toolbox
- Merges #88 and #89

# Version 1.2.12, June 28th, 2015

- Fixes #85 – Jingo crash on search
- Fixes #45 – Jingo now works on mobile too

# Version 1.2.11, May 22th, 2015

- Merge PR #78 (Local authentication support, by @vschoettke)
- Merge PR #75 (Gfm line breaks, by @apskim)
- Deprecated the Alone authentication method

# Version 1.2.9, January 26th, 2015

- Fixes #64 (crash serving favicon)
- Fixes #62 (missing titles on new and edit)
- Fixes #60 (no sidebar on login page)

# Version 1.2.8, December 15th, 2014

- Fixes a bug on the pull git pull (Jon Richter, @almereyda)
- Updates README (Jon Richter, @almereyda)
- Re-enable the baseUrl config option (Jon Richter, @almereyda)
- Upgrade some modules to a newest version

# Version 1.2.7, November 16th, 2014

- Merges #59 (add a validation for Github parameters)

# Version 1.2.6, November 4th, 2014

- Fixes #57 (removes the backdrop from modal)
- Better accessibility for modal boxes
- Better layout and typography for modal boxes

# Version 1.2.5, October 28st, 2014

- Fixes a z-index bug

# Version 1.2.4, October 28st, 2014

- Fixes #56 (unrecognized git version)

# Version 1.2.3, October 27st, 2014

- Fixes #55 (footer links not clickable)

# Version 1.2.2, October 21st, 2014

- Fixes #54 (broken customizations)
- Adds the jingo version to the meta generator
- Better README
- Fixes a potential crash
- Adds missing page titles (regression bug)

# Version 1.2.1, October 13, 2014

- Fixes #41 (inverted diff)

# Version 1.2.0, October 9, 2014

- Adds support for the GitHub logins
- Adds support to be able to serve images and other assets from the repo

# Version 1.1.0, September 23, 2014

The markdown module we use (Marked) tries to overcome some "obscure" problems with the original Perl markdown parser by default. These produces some problems when rendering HTML embedded in a markdown document see also issue #48. By default we now want to use the original parser and not the modified one (pedantic: true).

There is a new option to override this behaviour (application.pedanticMarkdown).

# Version 1.0.0, July 31, 2014

This version introduces a LOT of changes, but it is still compatible with the 0.6.1

To upgrade, just run `npm install`. Please note that you will need `npm` version 1.3 or newer to install the dependencies or we will get the _Error: No compatible version found_ errors. To upgrade npm just run `npm update npm -g` (sudo may be required).

- Upgraded to Bootstrap 3.2
- Upgraded to Express 4
- Upgraded to Codemirror 3.24
- Code refactoring, now easier to maintain and to contribute
- Added some shortcut on the session message ("edit again?")
- New code tag renderer
- Fixed an issue where the sidebar and footer were not rendered
- Code refactoring using another level of abstraction (aka models)
- More mobile friendly
- New look for custom sidebar and footer
- Provides a new `pages` configuration options
- New YAML parser (js-yaml)
- Upgraded markdown parser
- It is now possible to specify a custom binary for git
- The list of documents is now paginated (configurable amount of items)
- Names of the components are now configurable
- Don't show the avatar if there is no email
- Better tests for the validity of the configuration options
- Fixes #39
- Fixes #37
- Fixes #32
- Fixes #27
- Fixes #22

# Version 0.6.1, June 24th, 2014

- Due to an incompatibility with latest versions of Express 3.x (and Connect),
  the Express version in package.json has been frozen
- Removed some deprecation warnings
- Fixed some problems on the welcome page

# Version 0.6.0, May 28th, 2014

- Uses the OAuth 2 authentication instead of the OpenID 2.0
  (see also https://developers.google.com/accounts/docs/OpenID)
  This will require to edit the config file and request Google for
  a client id and client secret (see the README on how to do that)

  The update requires to issue a `npm install`

# Version 0.5.2, May 26th, 2014

- Version bump for the npm package glitch

# Version 0.5.1, December 6th, 2013

- Use of icons (ionicons) instead of the ugly texts for buttons
- Add the quick diff option on the list of pages
- Fixes a bug on the compare button

# Version 0.5.0, December 4th, 2013

- Use of Codemirror (select it from the new config key `features`)
- Adds the last commit comment on the document list

# Version 0.4.4, July 23th, 2013

- Better typography

# Version 0.4.3, July 10th, 2013

- Closes #19
- Better line height for LI
- Refines PR #20

# Version 0.4.2, June 29th, 2013

- Fixed a compatibility issue with node 0.10.12, see #17

# Version 0.4.1, June 25th, 2013

- Fixed a bug on the document list sort

# Version 0.4.0, June 11th, 2013

- The main content is now centered
- Better typography
- Added WideArea support
- Added the ability to specify the branch within the remote

# Version 0.3.5, 0.3.6, June 5th, 2013

- Bug fixes

# Version 0.3.4, June 5th, 2013

- Support for search word highlight
- Makes the "tools" drawer fixed positioned

Version 0.3.3, June 4th, 2013
Version 0.3.2, June 4th, 2013
=============================

- Adds the baseUrl configuration key
- Fixes a bug on the renderer

# Version 0.3.1, May 26th, 2013

- Closes #11

# Version 0.3.0, May 24th, 2013

- Added the alone authorization option
- Added the --local server option
- Added ChangeLog
- Removed yaml module, added yaml-js
- Added connect-flash module
