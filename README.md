# notes-of-scripts
初回設定時に使うけど、1回設定したら内容を忘れてしまうかもしれないスクリプト。
簡単な説明も記載。

<ul>
<li>vm_startstop_snippet.cmd<br />
  VirtualBoxの仮想マシンを起動したり停止したりするスクリプトの元。
  VM名を変更し、必要なところのREMを消してタスクスケジューラに組み込んで利用。
  シャットダウン時の実行は、ログ:System、ソース:Microsoft-Windows-Kernel-General、イベントID:13 をトリガーとして実行。</li>
