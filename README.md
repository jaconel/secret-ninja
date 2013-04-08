# Secret Ninja

A Collection of Markdown files containing useful links and information related to web development with a strong focus on php.

## Frontend Performance

* http://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers/

## Ubuntu Security

* http://plusbryan.com/my-first-5-minutes-on-a-server-or-essential-security-for-linux-servers

## Logstash

* http://semicomplete.com/presentations/logstash-scale11x/#/1 - Scaling Logging
* http://kibana.org/intro.html - Kibana UI for logstash

## Custom Terminal Prompt
* http://mediadoneright.com/content/ultimate-git-ps1-bash-prompt

## PHP, Apache2 and PHP-FPM

Running php with apache over fastcgi using php-fpm
* http://stackoverflow.com/questions/10678542/php5-fpm-children-and-requests
* https://alexcabal.com/installing-apache-mod_fastcgi-php-fpm-on-ubuntu-server-maverick/
* http://whocares.de/fastcgiexternalserver-demystified/all/1/
* http://articles.slicehost.com/2010/5/19/configuring-the-apache-mpm-on-ubuntu Configuring the apache mpm on ubuntu
* http://articles.slicehost.com/2010/5/19/apache-configuration-on-ubuntu-part-1
* http://articles.slicehost.com/2010/5/19/apache-configuration-on-ubuntu-part-2

# Apache

* http://www.debian-administration.org/articles/188 - Basic tweaking

## Python

* http://www.diveintopython.net/toc/index.html

## Montoring and Metrics

* http://codeascraft.etsy.com/2011/02/15/measure-anything-measure-everything/
* http://codeascraft.etsy.com/2010/12/08/track-every-release/
* http://www.slideshare.net/postwait/monitoring-and-observability

## Chef

* http://wiki.opscode.com/display/chef/Installing+Chef+Server+on+Debian+or+Ubuntu+using+Packages Installing chef via apt-get
* http://vagrantup.com/v1/docs/provisioners/chef_solo.html Testing Chef recipes with vagrant
* http://acrmp.github.com/foodcritic/ A lint tool for your Opscode Chef cookbooks.

## Git

* http://git-scm.com/book/en/Git-on-the-Server-Setting-Up-the-Server - Setting up a basic git server with ssh access

## Ruby

* http://guides.rubygems.org/make-your-own-gem/ - Creating a Ruby gem

## MySQL

* http://www.tokutek.com/ - High Performance, Scalable alternative to Innodb engine.
* http://komlenic.com/244/8-reasons-why-mysqls-enum-data-type-is-evil/ - 8 Reasons Why mysql enum data type is evil

## MySQL and NoSql alternatives

* http://www.memsql.com/

## Mobile Web

### Frameworks

* http://www.sencha.com/products/touch/features/ - Sencha Touch
* http://jquerymobile.com/ - jQuery Mobile

## Databas Versioning

* http://www.liquibase.org/ - Liquibase

## Hubot

* http://chanux.posterous.com/installing-githubs-hubot-on-ubuntu - Installing hubot on ubuntu 

## Node js

 * https://github.com/joyent/node/wiki/Installation - How to install

## Samba Share On Linux

* http://www.howtogeek.com/howto/ubuntu/install-samba-server-on-ubuntu/ - Install a samba server on Ubuntu

## Amazon EC2

* http://docs.amazonwebservices.com/AWSEC2/latest/GettingStartedGuide/Welcome.html?r=3947 - Getting Started
* http://aws.amazon.com/free/ - Free EC2 tier
* http://docs.amazonwebservices.com/gettingstarted/latest/awsgsg-freetier/deploy-sample-app.html - Sample application and deployment

## CI and PHP

* http://jenkins-php.org/ - Jenkins PHP Template
* http://travis-ci.org/ - For opensource projects on github
* http://www.devopsy.com/blog/2012/01/20/continuous-deployment-to-heroku-with-jenkins/ - Jenkins with heroku deployment
* http://about.travis-ci.org/blog/announcing-pull-request-support/ - Travisbot supports PRs
* https://github.com/github/janky - Github, Hubot and Jenkins integration opensourced by Github.
* http://markunsworth.com/2012/02/11/setting-up-a-jenkins-build-server-on-ec2/ - Running Jenkins on Amazon EC2 
* http://abhirama.wordpress.com/2008/11/03/apache-mod_proxy-in-ubuntu/
* https://wiki.jenkins-ci.org/display/JENKINS/Installing+Jenkins+on+Ubuntu

## Heroku

### Php on Heroku

* http://hakre.wordpress.com/2012/05/20/php-on-heroku-again/
* https://github.com/winglian/Heroku-PHP/tree/master/conf

## Php Benchmarking

* http://www.phpbench.com/

### Composer support

Using Composer in heroku ing custom build packs:

* https://devcenter.heroku.com/articles/buildpacks
* https://devcenter.heroku.com/articles/buildpack-api
* http://bergie.iki.fi/blog/using_composer_to_manage_dependencies_in_heroku_php_apps/

Might be able to use custom build pack to set the webroot directory to */public for zf2 applications: 
Fork https://github.com/heroku/heroku-buildpack-php and change settings. (Would be awesome to have composer support as well.)

Composer code for buildpack: 
* https://github.com/bergie/heroku-buildpack-php/blob/master/bin/compile#L49

Build pack to compile classmaps at update?

---

## Nginx

* http://arstechnica.com/business/2011/11/a-faster-web-server-ripping-out-apache-for-nginx/ (be sure to note the over friendly php error)
* http://wiki.nginx.org/Pitfalls#Pass_Non-PHP_Requests_to_PHP.

---

## Capistrano

### Introduction and Tutorials

* http://guides.beanstalkapp.com/deployments/deploy-with-capistrano.html
* https://help.github.com/articles/deploying-with-capistrano

### Cleaning Logs and Strucuture

* http://jondavidjohn.com/blog/2012/04/cleaning-up-capistrano-deployment-output
* http://guides.beanstalkapp.com/deployments/deploy-with-capistrano.html

### Excepting parameters

* http://archives.ryandaigle.com/articles/2007/6/22/using-command-line-parameters-w-rake-and-capistrano
* https://groups.google.com/forum/?fromgroups#!topic/capistrano/BYklL6-QMOc%5B1-25%5D

### Usefull Reading
* http://www.claytonlz.com/2008/08/php-deployment-with-capistrano/
* http://capitate.rubyforge.org/recipes/deploy.html
* Wiki page https://github.com/capistrano/capistrano/wiki
* Release paths https://groups.google.com/forum/?fromgroups=#!topic/capistrano/TKoy4it9w-c
* http://brighternet.com/articles/deploying-static-sites-with-capistrano/

## Github stuff

* https://github.com/blog/470-deployment-script-spring-cleaning
* http://scottchacon.com/2011/08/31/github-flow.html Github Workflow.

---

## ZF 2 

* http://framework.zend.com/zf2
* http://akrabat.com/
* http://blog.evan.pro/
* http://mwop.net/blog.html
* http://ralphschindler.com/
* http://modules.zendframework.com/

### Configuration

* http://www.spiffyjr.me/2012/06/17/how-does-configuration-work-in-zf2/
 
### JSON ViewStrategy

* http://akrabat.com/zend-framework-2/returning-json-from-a-zf2-controller-action/

### Example Applications

* https://github.com/akrabat
* https://github.com/akrabat/ZF2TestApp

### Event Manager 

* http://akrabat.com/zend-framework-2/an-introduction-to-zendeventmanager/
* http://mwop.net/blog/266-Using-the-ZF2-EventManager.html
 
### DIC

* http://ocramius.github.com/blog/zend-framework-2-controllers-and-dependency-injection-with-zend-di/

---

## Exception- and Errors handling in Php

* http://framework.zend.com/wiki/display/ZFDEV2/Proposal+for+Exceptions+in+ZF2
* http://www.php.net/manual/en/spl.exceptions.php
* http://mwop.net/blog/on-error-handling-and-closures.html

---

## Mocking and PHPUnit

* http://www.slideshare.net/sebastian_bergmann/phpunit-best-practices

### Stubbing/Mocking Hardcoded Dependancies

* http://stackoverflow.com/questions/2031385/phpunit-stub-methods-undefined
* http://sebastian-bergmann.de/archives/885-Stubbing-Hard-Coded-Dependencies.html

---

## GWT

* http://code.google.com/p/gwt-platform/wiki/GettingStarted#Browsing_the_Javadoc
* http://www.summa-tech.com/blog/2012/06/11/7-tips-for-exception-handling-in-gwt/ Exception Handling.


### Compiling

* https://developers.google.com/web-toolkit/doc/latest/DevGuideCompilingAndDebugging#DevGuideCompilerOptions - Compiling from command line

---

## How to handle sessions in GWT(P)

* http://zawoad.blogspot.com/2009/12/session-management-set-and-get-data.html
* http://code.google.com/p/google-web-toolkit-incubator/wiki/LoginSecurityFAQ
* http://code.google.com/p/gwtsecurity/wiki/designConsideration
* http://varuntayur.wordpress.com/2012/01/25/session-management-in-gwt/

## RESTful Service in GWT

* http://blog.furiousbob.com/2011/03/27/putting-your-gwt-service-to-rest/
* http://restygwt.fusesource.org/documentation/restygwt-user-guide.html

---
 
## Cross Browser Testing Tools

* https://browserlab.adobe.com/en-us/index.html
* https://browserlab.adobe.com/
* http://www.browserstack.com/

---

## Apache

### Ant

* http://ant.apache.org/
* http://ant.apache.org/manual/tutorial-writing-tasks.html
* http://ant.apache.org/manual/develop.html
* http://ant.apache.org/manual/tutorial-tasks-filesets-properties.html
* http://ant.apache.org/manual/tutorial-tasks-filesets-properties.html

### Modules

* http://httpd.apache.org/docs/2.2/mod/mod_cache.html
* http://code.google.com/speed/page-speed/docs/module.html
* http://httpd.apache.org/docs/2.0/mod/mod_expires.html

### Apache as a Proxy

* http://www.serverwatch.com/tutorials/article.php/10825_3092521_3/Configuring-Apache-20-as-a-Forward-Proxy-Server.htm

---

## PHP Tools

* http://www.smashingmagazine.com/2009/01/20/50-extremely-useful-php-tools/
* http://manual.phpdoc.org/HTMLframesConverter/default/phpDocumentor/tutorial_phpDocumentor.howto.pkg.html#basics.docblock
* http://devzone.zend.com/article/2803-Introducing-xdebug
* http://www.phpsrc.org/projects/pti-php-codesniffer/wiki/
* http://phpmd.org/download/index.html
 
---

## Mongo db

* http://www.mongodb.org/display/DOCS/Replica+Sets+-+Voting
* http://www.mongodb.org/display/DOCS/Replica+Set+Commands
* http://www.mongodb.org/display/DOCS/Replica+Sets+-+Oplog
* http://www.mongodb.org/display/DOCS/Capped+Collections
* http://www.mongodb.org/display/DOCS/Replica+Set+Tutorial
* http://www.mongodb.org/display/DOCS/Replica+Sets+-+Basics
* http://www.mongodb.org/display/DOCS/Replica+Sets+-+Priority
* http://www.mongodb.org/display/DOCS/Adding+an+Arbiter
* http://blog.engineering.kiip.me/post/20988881092/a-year-with-mongodb
* http://devzone.zend.com/1730/getting-started-with-mongodb-and-php/
* http://framework.zend.com/wiki/display/ZFPROP/Zend_Nosql_Mongo+-+Valentin+Golev

### Schema Design

* http://blog.mongodb.org/post/29140593886/designing-mongodb-schemas-with-embedded-non-embedded
* http://www.mongodb.org/display/DOCS/Schema+Design

---

## Automated/Continuous Deployment

* https://github.com/leehambley/railsless-deploy/
* http://hivelogic.com/articles/deploying-expressionengine-github-capistrano/
* http://mathew-davies.co.uk/2009/10/28/php-deployment.html
* https://github.com/capistrano/capistrano/wiki
* https://github.com/namics/capistrano-php/blob/master/lib/capistrano/php.rb
* http://www.davegardner.me.uk/blog/2012/02/13/php-deployment-with-capistrano/
* http://tfountain.co.uk/blog/2009/5/11/zend-framework-capistrano-deployment
* http://www.davegardner.me.uk/blog/2012/02/13/php-deployment-with-capistrano/
* https://github.com/capistrano/capistrano/wiki/
* https://github.com/holman/feedback/issues/38
* https://github.com/blog/470-deployment-script-spring-cleaning

---

## Database migration

* https://github.com/ruckus/ruckusing-migrations
* https://github.com/nickinuse/php-migrations
* http://stackoverflow.com/questions/3324571/is-there-a-php-equivalent-of-rails-migrations

---

## Feature branches

* http://martinfowler.com/bliki/FeatureBranch.html

---

## Restful Webservices

* http://www.ibm.com/developerworks/webservices/library/ws-restful/
* http://stackoverflow.com/questions/630453/put-vs-post-in-rest
* http://jacwright.com/250/simple-rest-server-in-php-supports-json-amf/
* http://devzone.zend.com/1590/create-restful-server-application-using-the-zend-framework/
* http://stackoverflow.com/questions/2081894/handling-put-delete-arguments-in-php
* http://www.recessframework.org/page/towards-restful-php-5-basic-tips
* http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.htm
* http://developer.github.com/v3/
* http://www.packetizer.com/ws/rest.html
* http://mwop.net/blog/233-Responding-to-Different-Content-Types-in-RESTful-ZF-Apps.html
* http://odino.org/rest-better-http-cache/
* http://restpatterns.org/HTTP_Status_Codes
* http://stackoverflow.com/questions/2342579/http-status-code-for-update-and-delete
* http://www.springsource.org/spring-data/mongodb

---

## Installing PHP 5.4 on Ubuntu

* http://chemicaloliver.net/internet/installing-php-5-4-in-ubuntu/

---

## PHPCS pre-commit hooke on git for PSR standards in PHP

* http://pear.php.net/package/PHP_CodeSniffer/redirected
* https://github.com/klaussilveira/phpcs-psr
* https://github.com/s0enke/git-hooks/tree/master/phpcs-pre-commit

---

## ZF2 and Restful Webservices

Introduction to proper rest full implementation:

http://www.ibm.com/developerworks/webservices/library/ws-restful/

ZF2 Restfull Controller Documentation:

http://packages.zendframework.com/docs/latest/manual/en/zend.mvc.controllers.html#zend.mvc.controllers.interfaces 

Routing will be VERY important, ZF2 routing documentation:

http://packages.zendframework.com/docs/latest/manual/en/zend.mvc.routing.html

Some thoughts on exposing web services via ZF1 :

http://mwop.net/blog/227-Exposing-Service-APIs-via-Zend-Framework

Building Rest services using ZF1:

http://mwop.net/blog/228-Building-RESTful-Services-with-Zend-Framework

Using Zend to handle and respond in different contexts:

http://mwop.net/blog/233-Responding-to-Different-Content-Types-in-RESTful-ZF-Apps

Link to ZF1 XML RPC Server, might be usefull:

http://framework.zend.com/manual/en/zend.xmlrpc.server.html

Link to ZF1 JSON RPC Server, might be usefull:

http://framework.zend.com/manual/en/zend.json.server.html

Reading of Accept Content type and setting headers for response:

http://packages.zendframework.com/docs/latest/manual/en/zend.http.html#zend.http.overview.request-response-and-headers

Look at overriding of verbs on:

http://dev.agilezen.com/concepts/overview.html

## Programatically creating Word Documents

* http://www.joelonsoftware.com/items/2008/02/19.html
* http://stackoverflow.com/questions/124959/create-word-document-using-php-in-linux
