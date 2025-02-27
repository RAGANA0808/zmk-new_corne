# Corne Bluetooth無線分割キーボード　ZMK

![睫毛外设 Corne 的照片](https://ae01.alicdn.com/kf/Sa797fee25edd44248fbfdb0e13d44e00B.jpg)

## 使用方法

1. [このレポジトリをフォークします](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository)。
2. [Actionタブを押して、ワークフローを有効化させます](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/disabling-and-enabling-a-workflow#enabling-a-workflow)。
3. [Actionタブ内Build ZMK firmware→Run workflow→Run workflow緑ボタンを押して実行]
4. Keymap Editorからキーマップを変更し、編集が終わったらSaveを押す。Gitアクションが自動的に起動するので、終わり次第新しいファームウェアをダウンロードすることができます。
5. USBをキーボードに挿入し、リセットボタンを2回押すことでUSBドライブがPCにマウントされる。左右のファームウェアを左右のキーボードそれぞれに投入することで自動的に再起動されペアリングされます。

## Corneのデフォルトキーマップ

![Diagram of config/eyelash_corne.keymap](keymap-drawer/eyelash_corne.svg "generated by @caksoylar's Keymap Drawer")
