# Caine9.0の環境構築
フォレンジックの学習を本格的に進めようと考え、一番の学習は実際に手を動かすことだと考えた。<br>
しかし、英語のサイトが多くて、いきなり言語と技術の両方を意識するのは自分には難しいと考えた。<br>
なので、日本語のサイトで技術にある程度触れてからにしようと考えた。<br>
その日本のセキュリティイベントのサイトでの学習でCaineの環境構築が必要なので行った。<br>
●情報セキュリティ技術のスキルアップ・イベント 仙台CTF 2017<br>
[http://sectanlab.sakura.ne.jp/sendaictf/fyi.html](http://sectanlab.sakura.ne.jp/sendaictf/fyi.html)<br>
![](https://github.com/shh11nn/How_to_install_Caine9.0/blob/main/sendai.png)
# Caineとは
フォレンジック用Linux。さまざまな調査ツールが入っている。ツールのインストールがうまくいかない場合、<br>
まとめてツールが入っているため役に立つ。<br>
今回はWindows OSにVirtual BoxでISO　イメージファイルを使って環境構築を行っていく。<br>
# VirtualBoxのインストール
略さず書くとOracle VM VirtualBoxという仮想化ソフトウェアパッケージの一つ現在の開発は米国オラクルが行っている。<br>
私と同様にWindowsにインストールする場合はインストーラをダウンロードして、インストーラを実行して<br>
VirtualBoxが起動できるようにする。<br>
●Oracle Virtual Box 公式サイト<br>
[https://www.oracle.com/jp/virtualization/technologies/vm/downloads/virtualbox-downloads.html](https://www.oracle.com/jp/virtualization/technologies/vm/downloads/virtualbox-downloads.html)<br>
![](https://github.com/shh11nn/How_to_install_Caine9.0/blob/main/oracle.png)<br>
<br>
VirtualBoxを起動すると下の画像の通りになる。既に私は「Caine9.0」という名前でCaineの環境構築を終えているが、<br>
別の名前で環境構築をして説明していく。
![](https://github.com/shh11nn/How_to_install_Caine9.0/blob/main/virtualbox1.png)
# Caine9.0のインストール
Caineの公式サイトのリンクにとび、DOWNLOADSをクリックする。<br>
●Caineの公式サイト<br>
[https://www.caine-live.net/](https://www.caine-live.net/)
![](https://github.com/shh11nn/How_to_install_Caine9.0/blob/main/caine_home.png)<br>
<br>
Caine9.0.iso (64 bit)をクリックしてISOイメージをダウンロードする。<br>
VirtualBoxで新規で名前：Caine・タイプ：Linux・バージョン：Oracle(64-bit)で、<br>
後はデフォルトで仮想マシンを作成する。
![](https://github.com/shh11nn/How_to_install_Caine9.0/blob/main/caine9.0.png)
<br>
VirtualBoxの設定のストレージでISOイメージに配置してDVDで焼く
![](https://github.com/shh11nn/How_to_install_Caine9.0/blob/main/storage.png)
