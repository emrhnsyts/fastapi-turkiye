# İlerleyiş

<!--
{% macro url_for_pr(number="0") -%}
    https://github.com/tiangolo/fastapi/pull/{{number}}
{%- endmacro %}
-->

## Emoji Haritası

| Emoji | Durum            | Açıklama                    |
| ----- | ---------------- | --------------------------- |
| 🤓     | İnceleme         | PR açıldı, Review ediliyor. |
| 🚧     | Yapım Aşamasında | Çalışma devam ediyor.       |
| 🔳     | Yapılacak        | Çevirmenini bekliyor.       |
| ✅     | Onaylandı        | Onaylandı.                  |

## İlerleyiş

| Sayfa                                              | Bağlantı | Durum                 | Sebep       | Atanan             | Çeviren            | Gözden Geçiren                                             |
| -------------------------------------------------- | -------- | --------------------- | ----------- | ------------------ | ------------------ | ---------------------------------------------------------- |
| [/index.md]({{url_for_pr(10444)}})                 |          | :white_check_mark:    | Zaman Aşımı | [@hasansezertasan] | [@hasansezertasan] | [@alperiox], [@esrefzeki], [@bilalalpaslan], @mertssmnoglu |
| [/python-types.md]({{url_for_pr(10445)}})          |          | :nerd:                | Zaman Aşımı | [@esrefzeki]       | [@esrefzeki]       | [@hasansezertasan], [@bilalalpaslan]                       |
| [/features.md]({{url_for_pr(10492)}})              |          | :nerd:                | Zaman Aşımı | [@bilalalpaslan]   | [@bilalalpaslan]   | [@hasansezertasan]                                         |
| [/alternatives.md]({{url_for_pr(10502)}})          |          | :nerd:                | Yeni        | [@alperiox]        | [@alperiox]        | [@hasansezertasan]                                         |
| [/fastapi-people.md]({{url_for_pr(10547)}})        |          | :nerd:                | Zaman Aşımı | [@alperiox]        | [@alperiox]        |                                                            |
| [/external-links.md]({{url_for_pr(10549)}})        |          | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/newsletter.md]({{url_for_pr(10550)}})            |          | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] | [@alperiox]                                                |
| [/benchmarks.md]({{url_for_pr(11005)}})            |          | :white_check_mark:    | Zaman Aşımı | [@bilalalpaslan]   | [@hasansezertasan] |                                                            |
| [/about/index.md]({{url_for_pr(11006)}})           |          | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/history-design-future.md]({{url_for_pr(11012)}}) |          | :nerd:                | Yeni        | [@esrefzeki]       | [@hasansezertasan] |                                                            |
| [/help/index.md]({{url_for_pr(11013)}})            |          | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/learn/index.md]({{url_for_pr(11014)}})           |          | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/resources/index.md]({{url_for_pr(11020)}})       |          | :white_square_button: | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/how-to/index.md]({{url_for_pr(11021)}})          |          | :white_square_button: | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/project-generation.md`                           |          | :construction:        | Yeni        | [@bilalalpaslan]   |                    |                                                            |
| `/async.md`                                        |          | :construction:        | Yeni        | [@bilalalpaslan]   |                    |                                                            |
| `/contributing.md`                                 |          | :construction:        | Yeni        | [@hasansezertasan] |                    |                                                            |
| `/help-fastapi.md`                                 |          | :white_square_button: | Yeni        | [@hasansezertasan] |                    |                                                            |

## Durum

| Sayfa                                                                 | Durum              |
| --------------------------------------------------------------------- | ------------------ |
| `/index.md`                                                           | Zaman Aşımı        |
| `/features.md`                                                        | Gözden Geçiriliyor |
| `/fastapi-people.md`                                                  | Gözden Geçiriliyor |
| `/python-types.md`                                                    | Gözden Geçiriliyor |
| `/alternatives.md`                                                    | Gözden Geçiriliyor |
| `/external-links.md`                                                  | Güncel             |
| `/benchmarks.md`                                                      | Güncel             |
| `/newsletter.md`                                                      | Güncel             |
| `/project-generation.md`                                              | Zaman Aşımı        |
| `/async.md`                                                           | Zaman Aşımı        |
| `/contributing.md`                                                    | Çevirilmedi        |
| `/help-fastapi.md`                                                    | Çevirilmedi        |
| `/history-design-future.md`                                           | Gözden Geçiriliyor |
| `/release-notes.md`                                                   | Çevirilmedi        |
| `/about/index.md`                                                     | Güncel             |
| `/help/index.md`                                                      | Güncel             |
| `/learn/index.md`                                                     | Güncel             |
| `/tutorial/index.md`                                                  | Çevirilmedi        |
| `/tutorial/first-steps.md`                                            | Zaman Aşımı        |
| `/tutorial/path-params.md`                                            | Çevirilmedi        |
| `/tutorial/query-params.md`                                           | Çevirilmedi        |
| `/tutorial/body.md`                                                   | Çevirilmedi        |
| `/tutorial/query-params-str-validations.md`                           | Çevirilmedi        |
| `/tutorial/path-params-numeric-validations.md`                        | Çevirilmedi        |
| `/tutorial/body-multiple-params.md`                                   | Çevirilmedi        |
| `/tutorial/body-fields.md`                                            | Çevirilmedi        |
| `/tutorial/body-nested-models.md`                                     | Çevirilmedi        |
| `/tutorial/schema-extra-example.md`                                   | Çevirilmedi        |
| `/tutorial/extra-data-types.md`                                       | Çevirilmedi        |
| `/tutorial/cookie-params.md`                                          | Çevirilmedi        |
| `/tutorial/header-params.md`                                          | Çevirilmedi        |
| `/tutorial/response-model.md`                                         | Çevirilmedi        |
| `/tutorial/extra-models.md`                                           | Çevirilmedi        |
| `/tutorial/response-status-code.md`                                   | Çevirilmedi        |
| `/tutorial/request-forms.md`                                          | Çevirilmedi        |
| `/tutorial/request-files.md`                                          | Çevirilmedi        |
| `/tutorial/request-forms-and-files.md`                                | Çevirilmedi        |
| `/tutorial/handling-errors.md`                                        | Çevirilmedi        |
| `/tutorial/path-operation-configuration.md`                           | Çevirilmedi        |
| `/tutorial/encoder.md`                                                | Çevirilmedi        |
| `/tutorial/body-updates.md`                                           | Çevirilmedi        |
| `/tutorial/dependencies/index.md`                                     | Çevirilmedi        |
| `/tutorial/dependencies/classes-as-dependencies.md`                   | Çevirilmedi        |
| `/tutorial/dependencies/sub-dependencies.md`                          | Çevirilmedi        |
| `/tutorial/dependencies/dependencies-in-path-operation-decorators.md` | Çevirilmedi        |
| `/tutorial/dependencies/global-dependencies.md`                       | Çevirilmedi        |
| `/tutorial/dependencies/dependencies-with-yield.md`                   | Çevirilmedi        |
| `/tutorial/security/index.md`                                         | Çevirilmedi        |
| `/tutorial/security/first-steps.md`                                   | Çevirilmedi        |
| `/tutorial/security/get-current-user.md`                              | Çevirilmedi        |
| `/tutorial/security/simple-oauth2.md`                                 | Çevirilmedi        |
| `/tutorial/security/oauth2-jwt.md`                                    | Çevirilmedi        |
| `/tutorial/middleware.md`                                             | Çevirilmedi        |
| `/tutorial/cors.md`                                                   | Çevirilmedi        |
| `/tutorial/sql-databases.md`                                          | Çevirilmedi        |
| `/tutorial/bigger-applications.md`                                    | Çevirilmedi        |
| `/tutorial/background-tasks.md`                                       | Çevirilmedi        |
| `/tutorial/metadata.md`                                               | Çevirilmedi        |
| `/tutorial/static-files.md`                                           | Çevirilmedi        |
| `/tutorial/testing.md`                                                | Çevirilmedi        |
| `/tutorial/debugging.md`                                              | Çevirilmedi        |
| `/advanced/index.md`                                                  | Çevirilmedi        |
| `/advanced/path-operation-advanced-configuration.md`                  | Çevirilmedi        |
| `/advanced/additional-status-codes.md`                                | Çevirilmedi        |
| `/advanced/response-directly.md`                                      | Çevirilmedi        |
| `/advanced/custom-response.md`                                        | Çevirilmedi        |
| `/advanced/additional-responses.md`                                   | Çevirilmedi        |
| `/advanced/response-cookies.md`                                       | Çevirilmedi        |
| `/advanced/response-headers.md`                                       | Çevirilmedi        |
| `/advanced/response-change-status-code.md`                            | Çevirilmedi        |
| `/advanced/advanced-dependencies.md`                                  | Çevirilmedi        |
| `/advanced/security/index.md`                                         | Çevirilmedi        |
| `/advanced/security/oauth2-scopes.md`                                 | Çevirilmedi        |
| `/advanced/security/http-basic-auth.md`                               | Çevirilmedi        |
| `/advanced/using-request-directly.md`                                 | Çevirilmedi        |
| `/advanced/dataclasses.md`                                            | Çevirilmedi        |
| `/advanced/middleware.md`                                             | Çevirilmedi        |
| `/advanced/sub-applications.md`                                       | Çevirilmedi        |
| `/advanced/behind-a-proxy.md`                                         | Çevirilmedi        |
| `/advanced/templates.md`                                              | Çevirilmedi        |
| `/advanced/websockets.md`                                             | Çevirilmedi        |
| `/advanced/events.md`                                                 | Çevirilmedi        |
| `/advanced/testing-websockets.md`                                     | Çevirilmedi        |
| `/advanced/testing-events.md`                                         | Çevirilmedi        |
| `/advanced/testing-dependencies.md`                                   | Çevirilmedi        |
| `/advanced/testing-database.md`                                       | Çevirilmedi        |
| `/advanced/async-tests.md`                                            | Çevirilmedi        |
| `/advanced/settings.md`                                               | Çevirilmedi        |
| `/advanced/openapi-callbacks.md`                                      | Çevirilmedi        |
| `/advanced/openapi-webhooks.md`                                       | Çevirilmedi        |
| `/advanced/wsgi.md`                                                   | Çevirilmedi        |
| `/advanced/generate-clients.md`                                       | Çevirilmedi        |
| `/deployment/index.md`                                                | Çevirilmedi        |
| `/deployment/versions.md`                                             | Çevirilmedi        |
| `/deployment/https.md`                                                | Çevirilmedi        |
| `/deployment/manually.md`                                             | Çevirilmedi        |
| `/deployment/concepts.md`                                             | Çevirilmedi        |
| `/deployment/cloud.md`                                                | Çevirilmedi        |
| `/deployment/server-workers.md`                                       | Çevirilmedi        |
| `/deployment/docker.md`                                               | Çevirilmedi        |
| `/how-to/index.md`                                                    | Gözden Geçiriliyor |
| `/how-to/general.md`                                                  | Çevirilmedi        |
| `/how-to/sql-databases-peewee.md`                                     | Çevirilmedi        |
| `/how-to/async-sql-encode-databases.md`                               | Çevirilmedi        |
| `/how-to/nosql-databases-couchbase.md`                                | Çevirilmedi        |
| `/how-to/graphql.md`                                                  | Çevirilmedi        |
| `/how-to/custom-request-and-route.md`                                 | Çevirilmedi        |
| `/how-to/conditional-openapi.md`                                      | Çevirilmedi        |
| `/how-to/extending-openapi.md`                                        | Çevirilmedi        |
| `/how-to/separate-openapi-schemas.md`                                 | Çevirilmedi        |
| `/how-to/custom-docs-ui-assets.md`                                    | Çevirilmedi        |
| `/how-to/configure-swagger-ui.md`                                     | Çevirilmedi        |
| `/reference/index.md`                                                 | Çevirilmedi        |
| `/reference/fastapi.md`                                               | Çevirilmedi        |
| `/reference/parameters.md`                                            | Çevirilmedi        |
| `/reference/status.md`                                                | Çevirilmedi        |
| `/reference/uploadfile.md`                                            | Çevirilmedi        |
| `/reference/exceptions.md`                                            | Çevirilmedi        |
| `/reference/dependencies.md`                                          | Çevirilmedi        |
| `/reference/apirouter.md`                                             | Çevirilmedi        |
| `/reference/background.md`                                            | Çevirilmedi        |
| `/reference/request.md`                                               | Çevirilmedi        |
| `/reference/websockets.md`                                            | Çevirilmedi        |
| `/reference/httpconnection.md`                                        | Çevirilmedi        |
| `/reference/response.md`                                              | Çevirilmedi        |
| `/reference/responses.md`                                             | Çevirilmedi        |
| `/reference/middleware.md`                                            | Çevirilmedi        |
| `/reference/openapi/index.md`                                         | Çevirilmedi        |
| `/reference/openapi/docs.md`                                          | Çevirilmedi        |
| `/reference/openapi/models.md`                                        | Çevirilmedi        |
| `/reference/security/index.md`                                        | Çevirilmedi        |
| `/reference/encoders.md`                                              | Çevirilmedi        |
| `/reference/staticfiles.md`                                           | Çevirilmedi        |
| `/reference/templating.md`                                            | Çevirilmedi        |
| `/reference/testclient.md`                                            | Çevirilmedi        |
| `/resources/index.md`                                                 | Gözden Geçiriliyor |
