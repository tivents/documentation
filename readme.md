# BookStack

![GitHub release](https://img.shields.io/github/release/BookStackApp/BookStack.svg)
![license](https://img.shields.io/badge/License-MIT-yellow.svg)
![Crowdin](https://badges.crowdin.net/bookstack/localized.svg)
![Build Status](https://github.com/BookStackApp/BookStack/workflows/test-php/badge.svg)
![Lint Status](https://github.com/BookStackApp/BookStack/workflows/lint-php/badge.svg)
![Maintainability](https://api.codeclimate.com/v1/badges/5551731994dd22fa1f4f/maintainability)

![Repo Stats](https://img.shields.io/static/v1?label=GitHub+project&message=stats&color=f27e3f)
![Discord](https://img.shields.io/static/v1?label=Discord&message=chat&color=738adb&logo=discord)
![Mastodon](https://img.shields.io/static/v1?label=Mastodon&message=@bookstack&color=595aff&logo=mastodon)
![X - Formerly Twitter](https://img.shields.io/static/v1?label=Follow&message=@bookstack_app&color=1d9bf0&logo=x)

![PeerTube](https://img.shields.io/static/v1?label=PeerTube&message=bookstack@foss.video&color=f2690d&logo=peertube)
![YouTube](https://img.shields.io/static/v1?label=YouTube&message=bookstackapp&color=ff0000&logo=youtube)

A platform for storing and organising information and documentation. Details for BookStack can be found on the official website at https://www.bookstackapp.com/.

* [Installation Instructions](https://www.bookstackapp.com/docs/admin/installation)
* [Documentation](https://www.bookstackapp.com/docs)
* [Demo Instance](https://demo.bookstackapp.com) 
  * [Admin Login](https://demo.bookstackapp.com/login?email=admin@example.com&password=password)
* [Screenshots](https://www.bookstackapp.com/#screenshots)
* [BookStack Blog](https://www.bookstackapp.com/blog)
* [Issue List](https://github.com/BookStackApp/BookStack/issues)
* [Discord Chat](https://discord.gg/ztkBqR2)
* [Support Options](https://www.bookstackapp.com/support/)

## 📚 Project Definition

BookStack is an opinionated wiki system that provides a pleasant and simple out-of-the-box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

BookStack is not designed as an extensible platform to be used for purposes that differ to the statement above.

In regard to development philosophy, BookStack has a relaxed, open & positive approach. At the end of the day this is free software developed and maintained by people donating their own free time.

## 🌟 Project Sponsors

Shown below are our bronze, silver and gold project sponsors.
Big thanks to these companies for supporting the project.
*Note: The listed services are not tested, vetted nor supported by the official BookStack project in any manner.*

[Project donation details](https://www.bookstackapp.com/donate/) - [GitHub Sponsors Page](https://github.com/sponsors/ssddanbrown) - [Ko-fi Page](https://ko-fi.com/ssddanbrown)

#### Gold Sponsor

<table><tbody><tr>
<td align="center"><a href="https://www.federated.computer/bookstack/" target="\_blank">
<img width="240" src="https://media.githubusercontent.com/media/BookStackApp/website/main/static/images/sponsors/federated-computer.png" alt="Diagrams.net">
</a></td>
</tr></tbody></table>

#### Bronze Sponsors

<table><tbody><tr>
<td align="center"><a href="https://www.diagrams.net/" target="\_blank">
<img width="240" src="https://media.githubusercontent.com/media/BookStackApp/website/main/static/images/sponsors/diagramsnet.png" alt="Diagrams.net">
</a></td>
<td align="center"><a href="https://cloudabove.com/hosting" target="\_blank">
<img width="200" src="https://media.githubusercontent.com/media/BookStackApp/website/main/static/images/sponsors/cloudabove.png" alt="Cloudabove">
</a></td>
</tr><tr>
<td align="center"><a href="https://www.practicali.be" target="\_blank">
<img width="240" src="https://media.githubusercontent.com/media/BookStackApp/website/main/static/images/sponsors/practicali.png" alt="Practicali">
</a></td>
<td align="center"><a href="https://www.stellarhosted.com/bookstack/" target="\_blank">
<img width="240" src="https://media.githubusercontent.com/media/BookStackApp/website/main/static/images/sponsors/stellarhosted.png" alt="Stellar Hosted">
</a></td>
</tr>
<tr>
<td colspan="2" align="center" style="text-align: center"><a href="https://nws.netways.de/apps/bookstack/" target="\_blank">
<img width="240" src="https://media.githubusercontent.com/media/BookStackApp/website/main/static/images/sponsors/netways.png" alt="NETWAYS Web Services">
</a></td>
</tr></tbody></table>

## 🛣️ Road Map

Below is a high-level road map view for BookStack to provide a sense of direction of where the project is going. This can change at any point and does not reflect many features and improvements that will also be included as part of the journey along this road map. For more granular detail of what will be included in upcoming releases you can review the project milestones as defined in our [Release Process](dev/docs/release-process.md) documentation.

- **Platform REST API** - *(Most actions implemented, maturing)* 
  - *A REST API covering, at minimum, control of core content models (Books, Chapters, Pages) for automation and platform extension.*
- **Permission System Review** - *(In Progress)* 
  - *Improvement in how permissions are applied and a review of the efficiency of the permission & roles system.*

## 🛠️ Development & Testing

Please see our [development docs](dev/docs/development.md) for full details regarding work on the BookStack source code.

If you're just looking to customize or extend your own BookStack instance, take a look at our [Hacking BookStack documentation page](https://www.bookstackapp.com/docs/admin/hacking-bookstack/) for details on various options to achieve this without altering the BookStack source code.

Details about BookStack's versioning scheme and the general release process [can be found here](dev/docs/release-process.md).

## 🌎 Translations

Translations for text within BookStack is managed through the [BookStack project on Crowdin](https://crowdin.com/project/bookstack). Some strings have colon-prefixed variables such as `:userName`. Leave these values as they are as they will be replaced at run-time.

Please use [Crowdin](https://crowdin.com/project/bookstack) to contribute translations instead of opening a pull request. The translations within the working codebase can be out-of-date, and merging via code can cause conflicts & sync issues. If for some reason you can't use Crowdin feel free to open an issue to discuss alternative options.

If you'd like a new language to be added to Crowdin, for you to be able to provide translations for, please [open a new issue here](https://github.com/BookStackApp/BookStack/issues/new?template=language_request.yml).

Please note, translations in BookStack are provided to the "Crowdin Global Translation Memory" which helps BookStack and other projects with finding translations. If you are not happy with contributing to this then providing translations to BookStack, even manually via GitHub, is not advised.

## 🎁 Contributing, Issues & Pull Requests

Feel free to [create issues](https://github.com/BookStackApp/BookStack/issues/new/choose) to request new features or to report bugs & problems. Just please follow the template given when creating the issue.

Pull requests are welcome but, unless it's a small tweak, it may be best to open the pull request early or create an issue for your intended change to discuss how it will fit into the project and plan out the merge. Just because a feature request exists, or is tagged, does not mean that feature would be accepted into the core project.

Pull requests should be created from the `development` branch since they will be merged back into `development` once done. Please do not build from or request a merge into the `release` branch as this is only for publishing releases. If you are looking to alter CSS or JavaScript content please edit the source files found in `resources/`. Any CSS or JS files within `public` are built from these source files and therefore should not be edited directly.

The project's code of conduct [can be found here](https://github.com/BookStackApp/BookStack/blob/development/.github/CODE_OF_CONDUCT.md).

## 🔒 Security

Security information for administering a BookStack instance can be found on the [documentation site here](https://www.bookstackapp.com/docs/admin/security/).

If you'd like to be notified of new potential security concerns you can [sign-up to the BookStack security mailing list](https://updates.bookstackapp.com/signup/bookstack-security-updates).

If you would like to report a security concern, details of doing so [can be found here](https://github.com/BookStackApp/BookStack/blob/development/.github/SECURITY.md).

## ♿ Accessibility

We want BookStack to remain accessible to as many people as possible. We aim for at least WCAG 2.1 Level A standards where possible although we do not strictly test this upon each release. If you come across any accessibility issues please feel free to open an issue.

## 🖥️ Website, Docs & Blog

The website which contains the project docs & blog can be found in the [BookStackApp/website](https://github.com/BookStackApp/website) repo.

## ⚖️ License

The BookStack source is provided under the [MIT License](https://github.com/BookStackApp/BookStack/blob/development/LICENSE).

The libraries used by, and included with, BookStack are provided under their own licenses and copyright.
The licenses for many of our core dependencies can be found in the attribution list below but this is not an exhaustive list of all projects used within BookStack.

## 👪 Attribution

The great people that have worked to build and improve BookStack can [be seen here](https://github.com/BookStackApp/BookStack/graphs/contributors). The wonderful people that have provided translations, either through GitHub or via Crowdin [can be seen here](https://github.com/BookStackApp/BookStack/blob/development/.github/translators.txt).

Below are the great open-source projects used to help build BookStack.
Note: This is not an exhaustive list of all libraries and projects that would be used in an active BookStack instance.

* [Laravel](http://laravel.com/) - [*MIT*](https://github.com/laravel/framework/blob/v8.82.0/LICENSE.md)
* [TinyMCE](https://www.tinymce.com/) - [*MIT*](https://github.com/tinymce/tinymce/blob/develop/LICENSE.TXT)
* [CodeMirror](https://codemirror.net) - [*MIT*](https://github.com/codemirror/CodeMirror/blob/master/LICENSE)
* [Sortable](https://github.com/SortableJS/Sortable) - [*MIT*](https://github.com/SortableJS/Sortable/blob/master/LICENSE)
* [Google Material Icons](https://github.com/google/material-design-icons) - [*Apache-2.0*](https://github.com/google/material-design-icons/blob/master/LICENSE)
* [markdown-it](https://github.com/markdown-it/markdown-it) and [markdown-it-task-lists](https://github.com/revin/markdown-it-task-lists) - [*MIT*](https://github.com/markdown-it/markdown-it/blob/master/LICENSE)* and [ISC](https://github.com/revin/markdown-it-task-lists/blob/master/LICENSE)*
* [Dompdf](https://github.com/dompdf/dompdf) - [*LGPL v2.1*](https://github.com/dompdf/dompdf/blob/master/LICENSE.LGPL)
* [BarryVD/Dompdf](https://github.com/barryvdh/laravel-dompdf) - [*MIT*](https://github.com/barryvdh/laravel-dompdf/blob/master/LICENSE)
* [BarryVD/Snappy (WKHTML2PDF)](https://github.com/barryvdh/laravel-snappy) - [*MIT*](https://github.com/barryvdh/laravel-snappy/blob/master/LICENSE)
* [WKHTMLtoPDF](http://wkhtmltopdf.org/index.html) - [*LGPL v3.0*](https://github.com/wkhtmltopdf/wkhtmltopdf/blob/master/LICENSE)
* [diagrams.net](https://github.com/jgraph/drawio) - [*Embedded Version Terms*](https://www.diagrams.net/trust/)* / [Source Project - Apache-2.0](https://github.com/jgraph/drawio/blob/dev/LICENSE)*
* [OneLogin's SAML PHP Toolkit](https://github.com/onelogin/php-saml) - [*MIT*](https://github.com/onelogin/php-saml/blob/master/LICENSE)
* [League/CommonMark](https://commonmark.thephpleague.com/) - [*BSD-3-Clause*](https://github.com/thephpleague/commonmark/blob/2.2/LICENSE)
* [League/Flysystem](https://flysystem.thephpleague.com) - [*MIT*](https://github.com/thephpleague/flysystem/blob/3.x/LICENSE)
* [League/html-to-markdown](https://github.com/thephpleague/html-to-markdown) - [*MIT*](https://github.com/thephpleague/html-to-markdown/blob/master/LICENSE)
* [League/oauth2-client](https://oauth2-client.thephpleague.com/) - [*MIT*](https://github.com/thephpleague/oauth2-client/blob/master/LICENSE)
* [pragmarx/google2fa](https://github.com/antonioribeiro/google2fa) - [*MIT*](https://github.com/antonioribeiro/google2fa/blob/8.x/LICENSE.md)
* [Bacon/BaconQrCode](https://github.com/Bacon/BaconQrCode) - [*BSD-2-Clause*](https://github.com/Bacon/BaconQrCode/blob/master/LICENSE)
* [phpseclib](https://github.com/phpseclib/phpseclib) - [*MIT*](https://github.com/phpseclib/phpseclib/blob/master/LICENSE)
* [Clockwork](https://github.com/itsgoingd/clockwork) - [*MIT*](https://github.com/itsgoingd/clockwork/blob/master/LICENSE)
* [PHPStan](https://phpstan.org/) & [Larastan](https://github.com/nunomaduro/larastan) - [*MIT*](https://github.com/phpstan/phpstan/blob/master/LICENSE)* and [MIT](https://github.com/nunomaduro/larastan/blob/master/LICENSE.md)*
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - [*BSD 3-Clause*](https://github.com/squizlabs/PHP_CodeSniffer/blob/master/licence.txt)
* [JakeArchibald/IDB-Keyval](https://github.com/jakearchibald/idb-keyval) - [*Apache-2.0*](https://github.com/jakearchibald/idb-keyval/blob/main/LICENCE)