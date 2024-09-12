# wiki

## Hugo deployment stuff

- create pages:

    ```bash
    hugo new content dir/<page-name>.md
    ```

- update modules:

    ```bash
    hugo mod get -u
    ```

- run local server:

    ```bash
    hugo server -D --disableFastRender
    ```
