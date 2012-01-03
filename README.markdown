Base Applicaton for [Yii](http://www.yiiframework.com/ "Yii Framework")-Applications [![Project status](http://stillmaintained.com/cebe/yii-base-application.png)](http://stillmaintained.com/cebe/yii-base-application)
====================================================================================

This is a base application to start a new project on.

I started developing just now, so it's not yet ready to use.

It aims to be a bit more prepared than the application created by yiic webapp.

Installation
------------

* fork/clone this repository.
* Download latest [yii-framework](http://www.yiiframework.com/download/ "Yii-Framework Download") and extract it somewhere on your disk.
* create a symlink `yii` in the the root directory of this application that points to your extracted yii-folder. The framework will be accessed through `./yii/framework/`
 `ln -s <path-to-yii>/ yii`
* create a application runtime directory that is writeable for the webserver
 `mkdir application/runtime`
 `chmod go+rwx application/runtime` <- this is only quick and dirty, on a production system you should find a user/group-based access control, not a world-writeable directory
* ...
* done.
