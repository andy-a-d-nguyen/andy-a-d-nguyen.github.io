---
layout: page
title: "Class 28"
permalink: /reading-notes/class-28/
---

## Django Forms

According to <https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms#in_this_module>, an HTML form consists of one or more text fields or widgets that are used to collect user input to be sent to a server.

Django forms provide a convenient way to handle form interactions by generating HTML forms that can handle input validation and submission.

Django's `Form` class is used to validate data submitted by a user and it contains many different kinds of forms fields and associated validations for those fields.

Django's `ModelForms` class is, instead, used to produce form fields for properties of a Django model.

Django also provides views classes specific to CRUD operations. For create, there is `CreateView`. For Update, there is `UpdateView`. For Delete, there is `DeleteView`.

## Bookmark and Review

<https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page>

<https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views>

## Things I want to know more about

- How Django differentiates between `PATCH` and `PUT` in UpdateView
