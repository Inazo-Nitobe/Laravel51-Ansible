Laravel5.1の練習のための仮想環境です。
php, composer, apache, mysqlを用意しています。
### セットアップ手順

#### vagrantを起動する
`$ vagrant up`

#### playbookを実行する
`$ ansible-playbook -i hosts bootstrap.yml`

#### Laravel5.1のセットアップ
`$ composer create-project laravel/laravel:5.1 /vagrant_data`

#### 注意点
ホストのIPアドレスは192.168.33.10としているが、
変更したい場合は最初にVagrantfileとhostsに記載している内容を変更しておくこと。


