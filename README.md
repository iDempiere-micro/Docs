# iDempire micro - highly modularized Java + Kotlin OSGi back-end compatible with iDempiere

When building a new business system there is a lot of stuff you can reuse. Most of the well-known libraries give you reuse on the technological level: logging, users, access control etc.

We decided to raise the bar a little bit higher and give software developers a possibility to reuse business entities from one of the most advanced open source Enterprise Resource Planning (ERP) software - [iDempiere](http://www.idempiere.org/).

So instead of building everything from scratch you simply:

- **choose the iDempiere modules** you need and include them in your Java or Kotlin OSGi code (you can start with our [empty Scaffold project](https://github.com/iDempiere-micro/Scaffold))
- enhance the database with your **custom tables and views**
- **extend the standard iDempiere code** if needed
- use the resulting application as a **REST server** with builtin authentication, users & roles etc., all the functionality from iDempiere modules included plus your custom code

Note: this is not an end-user application. This is a LEGO-style back-end building kit.

[Start here in the Wiki](https://github.com/iDempiere-micro/Docs/wiki)
