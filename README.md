# centos-openstack-gnome
openstack勉強用の環境です。
GUI環境かつ、ネットワークの設定がすでに終わっています。
private_networkに設定してあるので、
他のホストからは触ることはできません。

ネットワークの理解がある人はpublicに書き換えてみましょう。

## 使い方
vagrant,virtualboxはインストール済みとします。
また、virtual boxでウィンドウの大きさを変えた時に
guest側のデスクトップの大きさが反映されるように設定するために
vagrant-vbguestをインストールしておきます。

[vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest)
