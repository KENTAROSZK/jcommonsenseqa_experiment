# JcommonsenseQAをローカルLLMで動かすためのコード

JcommonsenseQAという日本に関する知識を4択で答えさせるデータセットをローカルLLMで動かしてみるコードを作成してテストさせました。

- notebook内の1番上のセルに記載している`model_name`を書き替えることでhugging face上にある各種テキスト生成LLMでJcommonsenseQAを解かせられると思います。


- データソース：https://github.com/yahoojapan/JGLUE/tree/main/datasets/jcommonsenseqa-v1.1
- プロンプト等を参考にしたリポジトリ：https://github.com/llm-jp/llm-jp-eval