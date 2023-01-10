---
layout: page
title: "Class 29"
permalink: /reading-notes/class-29/
---

## Django Custom User Model

According to <https://learndjango.com/tutorials/django-custom-user-model>, Django provides a default `User` model for authentication, but production Django projects should use a custom user model instead. `AbstractUser` and `AbstractBaseUser` are two classes that can be extended to create a custom user model; `AbstractUser` is more straightforward and simpler to use.

`UserCreationForm` and `UserChangeForm` are two classes that can be extended to work with any custom user models. The `UserAdmin` class can be extended to use these two form classes by using them as fields inside a class extended from the `UserAdmin` class, which is registered to the admin site.

## DjangoX

According to <https://github.com/wsvincent/djangox>, `DjangoX` is an opinionated view of Django with some things pre-configured for ease of use.

## Bookmark and Review

<https://docs.djangoproject.com/en/3.0/topics/auth/customizing/#auth-custom-user>

## Things I want to know more about

- How function-based views work
- How the `Form` class works
