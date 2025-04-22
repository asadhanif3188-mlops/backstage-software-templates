# Documents for ${{ values.app_name }}

Endpoints will be available at:

- GET `${{ values.app_name }}-${{ values.app_env }}.test.com/health`
- GET `${{ values.app_name }}-${{ values.app_env }}.test.com/info`
- GET `${{ values.app_name }}-${{ values.app_env }}.test.com/time`

More endpoints for app specific:

- GET `${{ values.app_name }}-${{ values.app_env }}.test.com/api/v1/details`

Here you could expand on what each of these endpoints do.

# How to access the app?

You can access the app by accessing this URL: `${{ values.app_name }}-${{ values.app_env }}.test.com/api/v1/healthz` 