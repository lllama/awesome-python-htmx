# PyHAT: Awesome Python htmx [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

**THIS IS A WIP, BUT WE ARE VERY OPEN TO CONTRIBUTIONS**

## Table of Contents

- [PyHAT: Awesome Python htmx ](#pyhat-awesome-python-htmx-)
  - [Table of Contents](#table-of-contents)
  - [What is PyHAT 🧐 ](#what-is-pyhat--)
    - [Our Goal](#our-goal)
    - [Why Should I Care](#why-should-i-care)
    - [But Will it Work in Production](#but-will-it-work-in-production)
  - [Usage ✏️ ](#usage-️-)
  - [Official Resources 📚](#official-resources-)
  - [Introductory Resources 🔰](#introductory-resources-)
  - [Introductory Courses 🏫](#introductory-courses-)
  - [Design, Theory, and Patterns 🧠](#design-theory-and-patterns-)
  - [Third Party Packages 📦](#third-party-packages-)
    - [Demos](#demos)
    - [Templates](#templates)
    - [Helper Libraries](#helper-libraries)
    - [Frameworks](#frameworks)
    - [Components](#components)
    - [Tools](#tools)
  - [Projects Using PyHAT (or similar) 🏗️](#projects-using-pyhat-or-similar-️)
  - [Further Reading 📖](#further-reading-)


## What is PyHAT 🧐 <a name = "about"></a>

PyHAT is more than just a snake with a hat 🐍🤠. It stands for Python htmx ASGI Tailwind&mdash;a web stack that allows you to build powerful web applications using nothing more than... drumroll... Python, htmx, and Tailwind.

### Our Goal

We want to promote hypermedia driven applications. That's it. That's the goal.

Okay, well, more specifically, we want to promote htmx within the Python ecosystem.

### Why Should I Care

Does any of this sound like you:
- I want to stick with just Python and HTML/CSS, [but not sacrifice front-end functionality](https://htmx.org/essays/when-to-use-hypermedia/).
- I don't want to have to use a [complicated front end framework](https://htmx.org/essays/a-response-to-rich-harris/).
- I don't enjoy [agonizing over CSS class names](https://tailwindcss.com/docs/utility-first#:~:text=You%20aren%E2%80%99t%20wasting%20energy%20inventing%20class%20names.).
- I want to maintain a consistent design without any bikeshedding.

If the above sounds like you then you are in the right place!

### But Will it Work in Production

Yes! [Here is a very good example](https://htmx.org/essays/a-real-world-react-to-htmx-port/) of a project a company underwent using HTMX with Django in production. Some highlights from the article:
> - The effort took about 2 months (with a 21K LOC code base, mostly JavaScript)
> - No reduction in the application’s user experience (UX)
> - They reduced the code base size by 67% (21,500 LOC to 7200 LOC)
> - They increased python code by 140% (500 LOC to 1200 LOC), a good thing if you prefer python to JS
> - They reduced their total JS dependencies by 96% (255 to 9)
> - They reduced their web build time by 88% (40 seconds to 5)
> - First load time-to-interactive was reduced by 50-60% (from 2 to 6 seconds to 1 to 2 seconds)
> - Much larger data sets were possible when using htmx, because react simply couldn’t handle the data
> - Web application memory usage was reduced by 46% (75MB to 45MB)


## Usage ✏️ <a name = "usage"></a>

Htmx can be used with any backend framework. Currently, there is a lot of experimentation in the Python space, which is exciting! But that also means that there are a lot of disparate approaches.

The best advice here is to get familiar with some of the core packages (htmx, tailwind). Then feel free to check out any of the packages below.


## Official Resources 📚

-   [htmx](https://htmx.org/) - htmx gives you access to AJAX, CSS Transitions, WebSockets and Server Sent Events directly in HTML, using attributes, so you can build modern user interfaces with the simplicity and power of hypertext. Htmx has no outside dependencies outside of a vanilla JavaScript file referenced in your HTML `<head>` section.
-   [tailwindcss](https://tailwindcss.com/docs/installation) - Rapidly build modern websites without ever leaving your HTML. Tailwind provides a standalone CLI tool that _does not_ require npm or any other JavaScript dependencies. (You can install it through `pip` using the [pytailwindcss](https://pypi.org/project/pytailwindcss/) library)


## Introductory Resources 🔰

-   **[simple site](https://github.com/tataraba/simplesite)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> - Provides thorough documentation on building a site from the ground up with FastAPI, Jinja, htmx, and Tailwind.
-   **[Rapid Prototyping with Flask, htmx, and Tailwind CSS](https://testdriven.io/blog/flask-htmx-tailwind/)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> - In this tutorial, you'll learn how to set up Flask with htmx and Tailwind CSS. (testdriven.io)


## Introductory Courses 🏫

-   **[HTMX + Flask: Modern Python Web Apps, Hold the JavaScript Course](https://training.talkpython.fm/courses/htmx-flask-modern-python-web-apps-hold-the-javascript)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> - htmx is one of the hottest properties 🔥 in web development today, and for good reason. This framework, along with the libraries and techniques introduced in this course, will have you writing the best Python web apps you've ever written: clean, fast, and interactive without all that frontend overhead. (TalkPython Training)
-   **[Bugbytes Django & HTMX](https://www.youtube.com/watch?v=Ula0c_rZ6gk&list=PL-2EBeDYMIbRByZ8GXhcnQSuv2dog4JxY)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> - A phenomenal tutorial series on using Django with htmx.

## Design, Theory, and Patterns 🧠
- **[Django + htmx patterns](https://github.com/spookylukey/django-htmx-patterns)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a><br/>
A compilation of patterns for writing Django projects that use htmx, with complete example code.
- **[htmx Essays](https://htmx.org/essays/)**<br/>
A collection of essays by Carson Gross, the creator of htmx. Some specific essays of note for those not familiar with his teachings:
    - **[Hypermedia-Driven Applications](https://htmx.org/essays/hypermedia-driven-applications/)** - This web stack could have been called PyHDA, this essay gives a great primer on how a PyHAT application should look, architecturally.
    - **[Locality of Behaviour (LoB)](https://htmx.org/essays/locality-of-behaviour/)** - A concept you will see referred to a lot around here. "The behaviour of a unit of code should be as obvious as possible by looking only at that unit of code"
    - **[Splitting Your Data & Application APIs: Going Further](https://htmx.org/essays/splitting-your-apis/)** - A great essay (responding to a [great article](https://max.engineer/server-informed-ui)).
    > If you split your API into Data and Application APIs...you should consider changing your Application API from JSON to Hypermedia (HTML) & using a hypermedia-oriented library like htmx to reap the benefits of the hypermedia model (simplicity, reliability, flexibility, etc.)



## Third Party Packages 📦

### Demos

-   **[Music Binder](https://github.com/tataraba/musicbinder)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> - More advanced version of [Simple Site repo](https://github.com/tataraba/simplesite) showcasing features like active search and infinite scroll. You can open with a Codespace in GitHub without having to install anything locally.
-   **[Bulldoggy: The Reminders App](https://github.com/AutomationPanda/bulldoggy-reminders-app)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> Bulldoggy is a small demo web app for tracking reminders. Uses htmx to handle `GET`, `POST`, `PATCH` requests in a fully-functioning to-do frontend.

### Templates

- **[fuzzy-couscous](https://tobi-de.github.io/fuzzy-couscous/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
A cli tool based on django's `startproject --template` to bootstrap your django projects with a PyHAT stack.

### Helper Libraries

<!--
 STARLETTE   <a href="https://www.starlette.io/" target="_blank"><img src="https://img.shields.io/badge/-Starlette-a9bbcc?style=flat&logo=starlette&logoColor=black" alt="Starlette"></a>
 FASTAPI   <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a>
FLASK   <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a>
JINJA   <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a>
DJANGO   <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a>
TAILWIND   <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a>
SANIC <a href="https://sanic.dev/" target="_blank"><img src="https://img.shields.io/badge/-Sanic-ea366a" alt="Sanic"></a>
-->
- **[Jinja2 fragments](https://github.com/sponsfreixes/jinja2-fragments)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a> <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> <a href="https://sanic.dev/" target="_blank"><img src="https://img.shields.io/badge/-Sanic-ea366a" alt="Sanic"></a> <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a><br/>
Allows rendering individual blocks from Jinja2 templates. This library was created to enable the pattern of [template fragments](https://htmx.org/essays/template-fragments/) with Jinja2. Extremely helpful when using HTMX to enable [Locality of Behavior](https://htmx.org/essays/locality-of-behaviour/)
- **[Django Render Block](https://github.com/clokep/django-render-block)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Allows rendering individual blocks from Django templates. This library was created to enable the pattern of [template fragments](https://htmx.org/essays/template-fragments/) with Django (using Django or Jinja2 templates). Extremely helpful when using HTMX to enable [Locality of Behavior](https://htmx.org/essays/locality-of-behaviour/)
- **[Flask-HTMX](https://github.com/edmondchuc/flask-htmx)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a><br/>
A Flask extension to work with HTMX.
- **[htmx-Flask](https://github.com/sponsfreixes/htmx-flask)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a> <br/>
An extension for Flask that adds support for htmx to your application. It simplifies using htmx with Flask by enhancing the global 'request' object and providing a new 'make_response' function.
- **[FastAPI-HTMX](https://github.com/maces/fastapi-htmx)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br>
An opinionated extension for FastAPI to speed up development of lightly interactive web applications.
- **[asgi-htmx](https://github.com/florimondmanca/asgi-htmx)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br>
HTMX integration for ASGI applications. Works with Starlette, FastAPI, Quart -- or any other web framework supporting ASGI that exposes the ASGI `scope`. Inspired by `django-htmx`.
- **[django-htmx](https://github.com/adamchainz/django-htmx)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Extensions for using Django with htmx.
- **[django-siteajax](https://github.com/idlesign/django-siteajax)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Streamline your server and client interaction using declarative techniques in your HTML and helpful abstractions from siteajax in your Python code. Powered by htmx.
- **[hx-requests](https://github.com/yaakovLowenstein/hx-requests)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
A package to simplify the usage of HTMX with Django. Easily add HTMX requests witout needing additional urls, and reduce clutter in views by offloading all responsibility to an hx_request.
- **[django-cbv-htmx](https://github.com/mixmash11/django-cbv-htmx)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Helps connect Django Class-Based-Views with htmx.
- **[Starlette_htmx](https://github.com/lllama/starlette-htmx)** <a href="https://www.starlette.io/" target="_blank"><img src="https://img.shields.io/badge/-Starlette-a9bbcc?style=flat&logo=starlette&logoColor=black" alt="Starlette"></a><br/>
A set of extensions for using htmx with Starlette, based on `django-htmx`.

### Frameworks

- **[Forge Packages](https://www.forgepackages.com/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Forge is a set of Django packages that work well together, but can also be used independently. These include some htmx/tailwind specific packages highlighted below. Note that these are opinionated approaches, but they provide a robust set of features to enhance your developer experience.
    -   **[forge-htmx](https://www.forgepackages.com/docs/forge-htmx/)** -  The forge-htmx Django package adds a couple of unique features for working with HTMX. One is template fragments and the other is view actions.
    -   **[forge-tailwind](https://www.forgepackages.com/docs/forge-tailwind/)** <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a> - Use Tailwind CSS with Django without requiring JavaScript or npm.
- **[django_htmx_ui](https://github.com/nikalexis/django_htmx_ui)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://palletsprojects.com/p/jinja/" target="_blank"><img src="https://img.shields.io/badge/-Jinja2-a9bbcc?style=flat&logo=jinja&logoColor=black" alt="Jinja2"></a><br/>
A django app that combines and helps leverage the full-stack django framework, the frontend htmx framework, the django-htmx library, and the jinja template engine. It provides extended django Views with htmx build-in functionality, CRUD Views for django models, extra Mixins to use with your Views to make life easier, a ready-to-use jinja environment, Middlewares for automations, and extra utils and decorators for common use cases.

### Components

- **[Django Dashboards](https://github.com/wildfish/django-dashboards)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <br/>
Tools to help you build data dashboards in Django.
- **[django-htmx-autocomplete](https://github.com/PHACDataHub/django-htmx-autocomplete)** <br/>
A client-side autocomplete component powered by htmx featuring multiselect, search and is completely extensible.

### Tools

- **[django-tailwind-cli](https://oliverandrich.github.io/django-tailwind-cli/)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a> <a href="https://tailwindcss.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailwind_CSS-a9bbcc?style=flat&logo=tailwindcss&logoColor=black" alt="Tailwind CSS"></a><br/>
An integration of Tailwind CSS for Django that is based on the precompiled versions of the Tailwind CSS CLI (No JS required!)
- **[HTML Form to Dict](https://github.com/guettli/html_form_to_dict)**<br/>
Do simple end-to-end testing of form handling without a real browser (like selenium/puppeteer/playwright). Supports the "action" and "method" attributes of forms and additionaly the htmx attributes hx-get, hx-post.

## Projects Using PyHAT (or similar) 🏗️

- **[Django Requests Tracker](https://github.com/bensi94/Django-Requests-Tracker)** <a href="https://docs.djangoproject.com/en/" target="_blank"><img src="https://img.shields.io/badge/-Django-a9bbcc?style=flat&logo=django&logoColor=black" alt="Django"></a><br/>
A Django development tool which collects and displays information on requests, responses, SQL queries, headers, Django settings and more. The Front-end uses HTMX.
- **[IDP-Z3](https://gitlab.com/krr/IDP-Z3)** <a href="https://flask.palletsprojects.com/en" target="_blank"><img src="https://img.shields.io/badge/-Flask-a9bbcc?style=flat&logo=flask&logoColor=black" alt="Flask"></a><br/>
A software collection implementing the Knowledge Base paradigm using the FO(.) language. Uses htmx for the front end.
- **[JupySpace](https://github.com/davidbrochart/jupyspace)** <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/-FastAPI-a9bbcc?style=flat&logo=fastapi&logoColor=black" alt="FastAPI"></a><br/>
A web server and client to manage conda-forge environments from the browser and access them through JupyterLab. Uses htmx on the front-end.

## Further Reading 📖

- [Awesome Htmx](https://github.com/rajasegar/awesome-htmx)
- [htmx support in pycharm](https://oluwatobi.dev/blog/posts/htmx-support-in-pycharm)
