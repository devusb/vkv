<div align="center">
<img src="www/static/images/logo.png" alt="drawing" width="200"/>
<br>
<img src="https://github.com/FalcoSuessgott/vkv/actions/workflows/test.yml/badge.svg" alt="drawing"/>
<img src="https://github.com/FalcoSuessgott/vkv/actions/workflows/lint.yml/badge.svg" alt="drawing"/>
<img src="https://codecov.io/gh/FalcoSuessgott/vkv/branch/master/graph/badge.svg" alt="drawing"/>
<img src="https://img.shields.io/github/downloads/FalcoSuessgott/vkv/total.svg" alt="drawing"/>
<img src="https://img.shields.io/github/v/release/FalcoSuessgott/vkv" alt="drawing"/>

`vkv` is a highly tested, little CLI tool written in Go, which lets you export and import 
secrets from a [HashiCorp Vault KV-v2 engine](https://developer.hashicorp.com/vault/docs/secrets/kv/kv-v2):
<br>
<br>
<img src="www/static/images/demo.gif" alt="drawing" width="800" />

`vkv` allows you to recursively list secrets from any KV-v2 engine in various useful [output formats](https://falcosuessgott.github.io/vkv/export/formats/). Meanwhile `vkv import` takes `vkv`'s `JSON` or `YAML` output and writes its secrets to the specified KV-v2 engine. You can even copy KV sub-paths into already existing secret engines.
<br>
<br>
Checkout the [Docs](https://falcosuessgott.github.io/vkv/) to learn more about `vkv`
</div>