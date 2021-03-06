[![Build Status](https://travis-ci.org/Anephenix/dashku.png)](https://travis-ci.org/Anephenix/dashku)
[![Coverage Status](https://coveralls.io/repos/Anephenix/dashku/badge.png?branch=master)](https://coveralls.io/r/Anephenix/dashku?branch=master)
[![Dependency Status](https://david-dm.org/anephenix/dashku.png)](https://david-dm.org/anephenix/dashku)
[![Dev Dependency Status](https://david-dm.org/anephenix/dashku/dev-status.png)](https://david-dm.org/anephenix/dashku#info=devDependencies)
[![Code Climate](https://codeclimate.com/github/Anephenix/dashku.png)](https://codeclimate.com/github/Anephenix/dashku)
[![Gitter chat](https://badges.gitter.im/Anephenix/dashku.png)](https://gitter.im/Anephenix/dashku)
[![Issue Stats](http://issuestats.com/github/Anephenix/dashku/badge/pr)](http://issuestats.com/github/Anephenix/dashku)
[![Issue Stats](http://issuestats.com/github/Anephenix/dashku/badge/issue)](http://issuestats.com/github/Anephenix/dashku)

Dashku
===

![Dashku Screenshot](https://raw.github.com/Anephenix/dashku/master/dashku-screenshot.png)

Introduction
---

Dashku is a web application for creating dashboards and widgets in HTML, CSS, and JavaScript. It is open source, and available to download from Github. There is also a [hosted edition at Dashku.com](https://dashku.com).

<a href="https://flattr.com/submit/auto?user_id=paulbjensen&url=https%3A%2F%2Fgithub.com%2FAnephenix%2Fdashku" target="_blank"><img src="http://api.flattr.com/button/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0"></a>

Dependencies
---

- Node.js (0.10)
- MongoDB
- Redis

Installation
---

    git clone git://github.com/Anephenix/dashku.git
    cd dashku
    npm install

Booting the application
---

    mongod &
    redis-server &
    npm start

Seeding the database with widget templates
---

You can seed Dashku's database with widget templates by running this command:

    npm run populateWidgetTemplates

Using Dashku to create dashboards and widgets
---

Documentation will be coming soon.

Testing
---

To run unit and functional tests:

    npm test

To run the integration tests:

    npm run cuke

License & Credits
---

&copy; 2014 Anephenix Ltd. The Nike swoosh is a registered trademark of Nike Inc. Dashku is a trademark of Anephenix Ltd, and dashku is licenced under the LGPLv3 license. See LICENSE for details.
