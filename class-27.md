---
layout: page
title: "Class 27"
permalink: /reading-notes/class-27/
---

## Django Models

According to <https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models>, models are used to represent the structure of data, constraints that exist for those data and relationship between those data. Models represent the database tables in a database. In Django, a class is used to represent a model. a field/property in a class is used to represent a column of data in a database table. By extending the `Models` base class in Django, a class also gains access to methods that can be used to query the database Django is connected to.

## Django Admin

According to <https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site>, Django admin is a special application of a Django project that allows a developer to easily perform CRUD operations on the models they have created during development as well as manage data in production using a web interface at the `admin` endpoint. In order for the Django admin application to be aware of the models that were created, they only need to be registered with the Django admin application. By extending the `ModelAdmin` base class in Django, a developer is able to change how a model is displayed in the admin web interface.

## Bookmark and Review

<https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html>

## Things I want to know more about

- Similar full-stack frameworks like Django that abstracts away a lot of complexities when trying to create a web application
