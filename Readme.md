# Kube Cluster Setup

## Prerequistes

- Running VM's (minimum 2) to setup kube cluster on.
- ansible collection - `community.general`
    ```shell
        ansible-galaxy collection install community.general
    ```
- Generate a token. This token must have the form `<6 character string>.<16 character string>`. More formally, it must match the regex: 
    ```regex
        [a-z0-9]{6}\.[a-z0-9]{16}
    ```
- You can use this online [tool](https://onlinerandomtools.com/generate-random-data-from-regexp) to generate a token using the regex above.