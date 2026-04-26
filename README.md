## Running with Gunicorn

Gunicorn is included as the production WSGI server for deployment.

Note: Gunicorn is not supported on Windows environments due to its dependency on Unix-based modules (e.g., fcntl). As a result, it cannot be run locally on Windows.

However, the application is fully compatible with Gunicorn in Linux-based environments such as cloud deployment platforms.