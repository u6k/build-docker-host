# build-docker-host

Dockerホストを構築する手順を確立します。Ubuntuをベースとして、Ansibleを使用して自動構築して、動作確認はVagrantで行いますが最終的にはDigital Oceanで動作させます。

## 使い方

Vagrantを起動して、sshログインするだけ。

```
cd src/

# Vagrantを起動
vagrant up

# sshログイン
vagrant ssh
```

## 課題管理

https://myredmine-u6kapps.rhcloud.com/projects/build-docker-host
