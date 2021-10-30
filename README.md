# DEPRECATED

Please use [azurectx-go](https://github.com/drewstinnett/azurectx-go) instead

# azurectx

Script for switching Azure Contexts (Default subscription).  Inspired by the
awesomeness of [kubectx](https://github.com/ahmetb/kubectx)

## Installation

```
pip3 install azurectx
```

## Usage

Run without any arguments to bring up a prompt

```
azurectx
```

Set the context non interactively with `-s`

```
azurectx -s 'Subscription name'
```

List existing subscriptions with `-l`

```
azurectx -l
```
