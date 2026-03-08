## Third-Party Packages

_For a broader catalog of Django packages, see [Django Packages](https://djangopackages.org/). This list focuses on tools that are especially useful, actively maintained, or broadly adopted in modern Django projects._

### Admin

#### User Impersonation
- [django-hijack](https://github.com/django-hijack/django-hijack) - Securely sign in as another user for support, debugging, and customer success workflows, with clear auditability and permission controls.
- [django-loginas](https://github.com/skorokithakis/django-loginas) - Simple “log in as user” functionality for Django admin, useful for troubleshooting account-specific issues.
- [impostor](https://github.com/avallbona/Impostor) - Let staff members impersonate users using their own credentials instead of sharing passwords or resetting accounts.
- [django-impersonate](https://pypi.org/project/django-impersonate/) - Allow superusers to impersonate other accounts for debugging, support, or account review flows.

#### Data & Display
- [django-import-export](https://github.com/django-import-export/django-import-export) - Import and export structured data through Django admin, making bulk edits, migrations, and CSV/Excel-based workflows much easier.
- [django-admin-inline-paginator-plus](https://github.com/DmytroLitvinov/django-admin-inline-paginator-plus) - Add pagination to admin inlines so large related datasets stay usable and don’t overwhelm the page.
- [django-related-admin](https://github.com/PetrDlouhy/django-related-admin) - Makes it easier to display related model fields in admin lists without writing repetitive boilerplate.
- [django-admin-sortable2](https://github.com/jrief/django-admin-sortable2) - Drag-and-drop ordering for models in the Django admin, useful for menus, content blocks, ordered lists, and curated collections.

#### UX, Collaboration & Operations
- [django-admin-env-notice](https://github.com/dizballanze/django-admin-env-notice) - Clearly label environments like development, staging, and production so teams are less likely to make dangerous mistakes in the wrong admin.
- [django-admin-collaborator](https://github.com/brktrlw/django-admin-collaborator) - Adds real-time presence, edit locks, and chat to Django admin so teams can collaborate more safely on shared content.
- [dj-control-room](https://github.com/yassi/dj-control-room) - Turns Django admin into an operational control panel with tools for cache, Celery, Redis, URL inspection, and other day-to-day maintenance tasks.
### Admin Themes
- [django-grappelli](https://github.com/sehmaschine/django-grappelli) - A long-running alternative admin skin that improves the visual experience and adds useful interface refinements.
- [django-jazzmin](https://github.com/farridav/django-jazzmin) - A popular drop-in admin theme that modernizes Django admin with a polished dashboard-style interface.
- [django-admin-interface](https://github.com/fabiocaccamo/django-admin-interface) - Customize branding, colors, logos, titles, and modal behavior directly from the admin without hand-editing templates.
- [django-semantic-admin](https://github.com/globophobe/django-semantic-admin) - A Semantic UI-based admin theme for teams that want a different design system from Django’s default.
- [django-jet-reboot](https://github.com/assem-ch/django-jet-reboot) - A modernized admin interface with enhanced layout, navigation, and dashboard-like functionality.
- [django-baton](https://github.com/otto-torino/django-baton) - Responsive Bootstrap 5-based admin replacement designed for cleaner navigation and a more app-like experience.
- [django-unfold](https://github.com/unfoldadmin/django-unfold) - A modern admin theme geared toward building polished internal tools and client-facing back-office interfaces.
- [django-daisy](https://github.com/hypy13/django-daisy) - Dashboard-oriented Django admin styling built with DaisyUI for teams that want a more contemporary frontend feel.
- [django-admin-dracula](https://github.com/sjbitcode/django-admin-dracula) - A Dracula-inspired theme for developers who want a darker, more distinctive admin UI.
- [django-smartbase-admin](https://github.com/SmartBase-SK/django-smartbase-admin) - Performance-focused admin theme built for speed, usability, and more end-user-friendly administration experiences.

### APIs

#### REST Frameworks
- [django-rest-framework](https://github.com/encode/django-rest-framework) - The standard toolkit for building REST APIs in Django, with serializers, viewsets, authentication hooks, permissions, and a large ecosystem.
- [django-ninja](https://django-ninja.rest-framework.com/) - A fast API framework for Django built around Python type hints, great for developers who want OpenAPI-first ergonomics with less boilerplate.
- [django-tastypie](https://github.com/django-tastypie/django-tastypie) - One of the original API frameworks for Django, still useful in some legacy or established codebases.
- [djaq](https://github.com/paul-wolf/djaq) - Exposes Django models through a flexible query API, useful for dynamic data access patterns and internal tooling.

#### Authentication
- [dj-rest-auth](https://github.com/iMerica/dj-rest-auth) - Ready-made authentication endpoints for login, logout, password reset, and registration in Django REST Framework projects.
- [django-rest-knox](https://github.com/jazzband/django-rest-knox) - Token-based authentication for DRF with security-focused features like token expiry and multiple tokens per user.
- [djoser](https://github.com/sunscrapers/djoser) - Provides REST endpoints for common auth flows such as registration, activation, password reset, and user management.
- [django-rest-framework-simplejwt](https://github.com/jazzband/djangorestframework-simplejwt) - JWT authentication for DRF, commonly used in SPA, mobile, and distributed API architectures.

#### GraphQL
- [graphene-django](https://github.com/graphql-python/graphene-django) - GraphQL integration for Django, enabling schema-driven APIs on top of your models and business logic.
- [graphene-django-filter](https://github.com/devind-team/graphene-django-filter) - Adds more expressive filtering support to Graphene-Django, including advanced operator-based queries.
- [strawberry-django](https://github.com/strawberry-graphql/strawberry-django) - Django integration for Strawberry GraphQL, offering a more modern type-driven GraphQL developer experience.

#### Schema & Documentation
- [drf-spectacular](https://github.com/tfranzel/drf-spectacular) - Flexible and well-regarded OpenAPI 3 schema generation for DRF, especially useful for API docs and codegen workflows.
- [drf-yasg](https://github.com/axnsan12/drf-yasg) - Swagger/OpenAPI schema generation for DRF, often used in older DRF projects that still rely on its tooling.

#### Utilities
- [django-cors-headers](https://github.com/adamchainz/django-cors-headers) - Add and manage Cross-Origin Resource Sharing headers when your frontend and backend run on different domains or ports.
- [django-webpack-loader](https://github.com/django-webpack/django-webpack-loader) - Bridges Django templates with Webpack-generated bundles so frontend assets can be managed more cleanly.
- [django-webhook](https://github.com/danihodovic/django-webhook) - Send outgoing webhooks on model changes so external systems can react automatically to events in your application.
### Async
- [channels](https://github.com/django/channels/) - Adds async patterns like WebSockets, background consumers, and real-time communication to Django applications.

### Caching
- [django-cachalot](https://github.com/noripyt/django-cachalot) - Automatically caches ORM queries and invalidates them when data changes, helping reduce repeated database work.
- [django-cacheops](https://github.com/Suor/django-cacheops) - Redis-backed ORM caching with fine-grained invalidation and control over what gets cached.

### Commands

#### CLI Authoring
- [django-extensions](https://github.com/django-extensions/django-extensions/) - A grab bag of useful management commands and developer utilities, including `shell_plus`, `runserver_plus`, and model graphing tools.
- [django-click](https://github.com/django-commons/django-click) - Write Django management commands using Click for better CLI ergonomics and richer command interfaces.
- [django-typer](https://github.com/django-commons/django-typer) - Build Django management commands with Typer for modern typing-based CLIs and a smoother developer experience.

#### Database & Migrations
- [django-dbbackup](https://github.com/Archmonger/django-dbbackup) - Add straightforward database and media backup/restore workflows to your Django project.
- [django-liquidb](https://github.com/Gusakovskiy/django-liquidb) - Helps manage schema state and migration workflows in more controlled or complex database environments.
- [django-migration-zero](https://github.com/ambient-innovation/django-migration-zero/) - Implements the “migration zero” pattern for teams that want cleaner long-term migration maintenance.
### Configuration

#### Environment & Secrets
- [confidential](https://github.com/candidco/confidential) - Manage settings and secrets with tooling that supports more structured configuration workflows.
- [django-environ](https://github.com/joke2k/django-environ) - One of the most popular ways to load Django settings from environment variables and `.env` files.
- [dynaconf](https://www.dynaconf.com/django/) - Load settings from multiple sources such as files, environment variables, Redis, Vault, and more.
- [environs](https://github.com/sloria/environs) - Lightweight environment variable parsing with a clean API and Django-friendly usage.

#### Settings Structure
- [django-split-settings](https://github.com/wemake-services/django-split-settings) - Break a large settings file into smaller, easier-to-reason-about modules.
- [django-configurations](https://github.com/jazzband/django-configurations) - Organize Django settings using class-based configuration patterns.
- [django-classy-settings](https://github.com/funkybob/django-classy-settings) - Class-based settings with typed environment access and cleaner structure for multi-environment projects.
- [django-removals](https://github.com/ambient-innovation/django-removals/) - Detect deprecated settings and outdated config patterns through Django's system checks framework.

#### Dynamic / Runtime Settings
- [django-constance](https://github.com/jazzband/django-constance) - Store dynamic settings in Redis or the database and edit them through Django admin.
- [django-extra-settings](https://github.com/fabiocaccamo/django-extra-settings) - Define and manage typed extra settings directly from Django admin.
- [django-content-settings](https://django-content-settings.readthedocs.io/en/latest/) - Create editable, typed content/config variables that non-developers can manage through admin.

### Content Management Systems
- [wagtail](https://github.com/wagtail/wagtail) - A powerful and popular Django CMS known for strong editor experience, flexible content modeling, and excellent developer ergonomics.
- [mezzanine](https://github.com/stephenmcd/mezzanine) - CMS framework for Django that combines content management with a more traditional website-builder feel.
- [django-cms](https://github.com/django-cms/django-cms) - Enterprise-friendly CMS for Django with plugin-based page composition and multilingual support.
- [feincms](https://github.com/feincms/feincms) - An extensible CMS framework for developers who want to assemble content systems from reusable building blocks.
- [puput](https://github.com/APSL/puput) - A blog application for Wagtail that helps teams add publishing workflows quickly.

### Dependency Injection
- [Wireup](https://github.com/maldoinc/wireup) - Add dependency injection patterns to Django for more explicit service wiring and testable application architecture.

### ECommerce
- [saleor](https://github.com/saleor/saleor) - A headless, GraphQL-first e-commerce platform built with Django, suited for modern storefront architectures.
- [django-oscar](https://github.com/django-oscar/django-oscar) - A mature, highly customizable e-commerce framework for Django with strong domain modeling.

### Editors

#### Rich Text & WYSIWYG
- [django-summernote](https://github.com/lqez/django-summernote) - Integrates the Summernote WYSIWYG editor into Django forms and admin.
- [django-tinymce](https://github.com/jazzband/django-tinymce) - TinyMCE integration for rich text editing in Django.
- [django-prose](https://github.com/withlogicco/django-prose) - A lightweight content editor focused on simplicity and ease of use.

#### Markdown
- [django-markdownx](https://github.com/neutronX/django-markdownx) - Markdown editor and upload support for teams that want a lightweight writing workflow in Django.
- [django-markdown-editor](https://github.com/agusmakmun/django-markdown-editor) - Markdown editor with UI integrations for Bootstrap and Semantic UI projects.

#### Code & Logic
- [django-ace](https://github.com/django-ace/django-ace) - Embed the ACE code editor in Django for editing code, templates, or structured text.
- [django-business-logic](https://github.com/dgk/django-business-logic) - A visual DSL-style framework for defining business rules and logic flows in Django.
### Files/Images
- [django-cleanup](https://github.com/un1t/django-cleanup) - Automatically delete old files when model file fields change, helping keep local and remote storage clean.
- [django-imagekit](https://github.com/matthewwithanm/django-imagekit) - Process, transform, and generate thumbnails for uploaded images.
- [django-pictures](https://github.com/codingjoe/django-pictures) - Responsive image handling for modern formats like AVIF and WebP, with browser-friendly output.
- [sorl-thumbnail](https://github.com/jazzband/sorl-thumbnail) - A widely used thumbnail generation library for Django projects.

### Forms
- [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms/) - Flexible, DRY form rendering with support for multiple frontend frameworks.
- [django-formtools](https://github.com/jazzband/django-formtools) - Useful for multi-step forms, wizards, and other workflows that need state across several pages.
- [django-widget-tweaks](https://github.com/jazzband/django-widget-tweaks) - Modify form field rendering directly in templates without needing custom widgets everywhere.
- [django-autocomplete-light](https://github.com/yourlabs/django-autocomplete-light) - Add autocompletion and richer selection widgets to Django forms.

### Full-stack frameworks

#### Server-Driven UI
- [Django LiveView](https://github.com/Django-LiveView/liveview) - Build reactive, server-rendered interfaces with Django templates and WebSocket-powered interactivity.
- [Reactor](https://github.com/edelvalle/reactor/) - LiveView-style development model for Django, focused on real-time server-driven UI.
- [Sockpuppet](https://sockpuppet.argpar.se/) - Reactive UI patterns for Django without abandoning familiar templates and server-side architecture.
- [Unicorn](https://www.django-unicorn.com/) - A component framework for progressively enhancing traditional Django views with AJAX-style interactivity.

#### React & Python Components
- [Django-Bridge](https://github.com/kaedroho/django-bridge) - Connect Django backends to React frontends with a more integrated full-stack workflow.
- [ReactPy](https://github.com/reactive-python/reactpy) - Bring Python-driven reactive UI components into Django applications.
### General

#### Data Browsing & Querying
- [django-data-browser](https://github.com/tolomea/django-data-browser) - Browse model data in a more user-friendly way than raw admin screens.
- [django-filter](https://github.com/carltongibson/django-filter) - Declarative filtering for QuerySets, commonly used in both HTML views and APIs.
- [django-sql-explorer](https://github.com/explorerhq/sql-explorer) - Run, save, and share SQL queries from your Django application.
- [django-tables2](https://github.com/jieter/django-tables2) - Render HTML tables with sorting, pagination, and reusable table definitions.

#### Site Utilities
- [django-maintenance-mode](https://github.com/fabiocaccamo/django-maintenance-mode) - Put your site into maintenance mode and serve a friendly temporary outage page.
- [django-freeze](https://github.com/fabiocaccamo/django-freeze) - Generate a static version of a dynamic Django site for simpler hosting or archival purposes.
- [django-nh3](https://github.com/marksweb/django-nh3) - Integrates Django with `nh3` for modern HTML sanitization.

#### Developer Tooling
- [iommi](https://github.com/iommirocks/iommi) - A higher-level toolkit for CRUD-style apps that reduces the amount of HTML and JavaScript you have to write.
- [Django-Classy-Doc](https://github.com/nanuxbe/django-classy-doc) - Helps document your own code in a style similar to CCBV and CDRF.
- [Weblate](https://github.com/WeblateOrg/weblate) - A web-based continuous localization system used by many open source and commercial projects.
### Internationalisation (i18n)
- [django-localflavor](https://github.com/django/django-localflavor) - Country- and region-specific form fields, validators, and other utilities.
- [django-modeltrans](https://github.com/zostera/django-modeltrans) - Translate model fields using JSONField-based storage without duplicating schema.
- [django-modeltranslations](https://github.com/deschler/django-modeltranslation) - Add translated model fields using a registration-based approach.
- [django-rosetta](https://github.com/mbi/django-rosetta) - Edit gettext translation catalogs from a convenient web UI inside Django admin.