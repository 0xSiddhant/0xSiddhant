Joined Github {{ ACCOUNT_AGE }} years ago.

Since then I pushed **{{ COMMITS }}** commits, opened **{{ ISSUES }}** issues, submitted **{{ PULL_REQUESTS }}** pull requests, received **{{ STARS }**} stars across **{{ REPOSITORIES }}** personal projects.

Most used languages across my projects:

{{ LANGUAGE_TEMPLATE_START:max=8 }}
![{{LANGUAGE_NAME}}](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor={{LANGUAGE_COLOR:uri}}&message={{LANGUAGE_NAME:uri}}%EF%B8%B1{{LANGUAGE_PERCENT:uri}}%25)
{{ LANGUAGE_TEMPLATE_END }}
