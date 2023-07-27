# blog

**blog** is a blockchain application built using Cosmos SDK and Tendermint and generated with Starport

## To start please run command

```
starport serve
```
## Configure
Initialization parameters of your app are stored in `config.yml`.

### `accounts`
A list of user accounts created during genesis of your application.

| Key   | Required | Type            | Description                                       |
| ----- | -------- | --------------- | ------------------------------------------------- |
| name  | Y        | String          | Local name of the key pair                        |
| coins | Y        | List of Strings | Initial coins with denominations (e.g. "100coin") |
