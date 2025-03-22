## AI_TERMINAL_ASSISTANT

### A simple AI terminal command line assistant

#### Installation

1. Clone the repository
2. Install the requirements
3. `pyinstaller --onefile --name ai main.py`
4. OR YOU CAN JUST DOWNLOAD THE [ai.exe](https://github.com/mengqinlol/ai_terminal_assistant/releases) FROM release
5. Add path to the ai.exe to your PATH
6. First, run `ai` in your terminal for initialization.
7. Then, follow the instuction given by `ai` to fill in your configration

##### If you want to use Ollama
- `base_url` should be `http://127.0.0.1:11434/v1`
- 'api_key' is not needed
- 'model' can be any model you`ve pulled from ollama
- IT SHOULD BE noted that Ollama may take a long time to process your request if it hasn't received any requests for a while, due to the initialization of the model.


#### Usage

``` bash
ai <Your need>
```

Examples:

``` bash
(ollama) PS D:\ai_terminal> ai 查看当前目录下所有文件大小
dir /a-d /o-s
Copy(c)/ Execute(e)/ Quit(q):
```


```
(ollama) PS D:\ai_terminal> ai 根据这个目录创建一个叫abc的docker
docker build -t abc .
Copy(c)/ Execute(e)/ Quit(q):
```
