## Getting started


### 1. fork한 후 git clone 받기   
```shell
git clone https://github.com/<your-github-username>/jupyterlab.git
cd jupyterlab
pip install -e .
jlpm install
```
+) 필수 
- node 설치
- ```export PATH="$HOME/.local/bin:$PATH"```
- mac만 ```brew install pkg-config cairo pango libpng jpeg giflib librsvg```
   
### 2. 실행 
```shell
jupyter lab --dev-mode
```

### 3. notebook directory 변경 
```shell
vi /Users/ksl2950/.jupyter/jupyter_lab_config.py
c.NotebookApp.notebook_dir = '원하는 디렉토리 위치'

```
