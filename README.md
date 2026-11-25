## Project Structure

- manage.py -> Command-line helper script used to run the development server, apply database migrations, and create apps.

- config/__init__.py -> An empty file that tells Python to treat config as an importable package.

- config/settings.py -> Central settings file for installed apps, database connections, templates, stsatic files and security keys.

- config/urls.py -> The main URL(Unform Resource Locator) router that maps web paths to specific apps or views.

- config/wsgi.py -> The entry point used by traditional web servers to serve the project in production.

- config/asgi.py -> The entry point used by asynchronous web servers(such as for WebSockets or async features).

