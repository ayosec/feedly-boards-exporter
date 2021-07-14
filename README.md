# feedly-boards-exporter

Export items in Feedly boards.

## Usage

1. Create an [access token](https://developer.feedly.com/v3/developer/) for your Feedly account.

2. Store the token in the environment variable `FEEDLY_TOKEN`.

    ```console
    $ export FEEDLY_TOKEN=$(cat ~/.config/feedly/access-token)
    ```

3. Execute the script in this repository in an empty directory.

A `.json` file will be created in the current directory for every board found in the account.
