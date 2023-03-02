Prepare xdebug
--------------
1. Install extension "Xdebug helper" for Chrome.
2. In settings PhpStorm:
   
   2.1) Build, Execution, Deployment -> Docker
    ```sh
    Connection sucessfull
    ```
   2.2) PHP -> CLI Interpreter -> Add
    ```sh
    From docker-compose.yml
    ```
   2.3) PHP -> Debug -> Servers -> Add:

   **Name** : phpServerName (from docker-compose.yml)

   **Host**: localhost

   **Port**: 80

   **Debugger**: Xdebug

   **Use path mappings**: /www -> /var/www/html
