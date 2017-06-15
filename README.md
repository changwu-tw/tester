# 安裝開發環境

## python dev env

```bash
$ pyenv virtualenv py3eth
$ pyenv activate py3eth
```

## serpent

```bash
$ git clone https://github.com/ethereum/serpent.git
$ cd serpent
$ python setup.py install
```

## secp256k1

```bash
$ pip install secp256k1
```

## viper

```bash
$ git clone https://github.com/ethereum/viper.git
$ cd viper
$ python setup.py install
```

## pyethereum

```bash
$ git clone https://github.com/ethereum/pyethereum.git
$ cd pyethereum
$ git checlout state_revamp
$ git submodule update --init --recursive
$ python setup.py develop
```

## pytest

```bash
$ pip install pytest
```

## run test in pyethereum

```bash
$ cd ethereum/tests
$ pytest --ignore=todo
```

> pytest 很多測試沒過，目前是正常的
