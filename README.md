# Full Stack LLM

## Python 가상환경 설정

### Python 컴파일 필수 도구

```bash
sudo apt update
sudo apt install -y make build-essential libssl-dev zlib1g-dev libbz2-dev \
    libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev \
    xz-utils tk-dev libffi-dev liblzma-dev python-openssl git
```

### `pyenv` 설치

```bash
curl https://pyenv.run | bash
```

#### `pyenv` 환경변수 설정

`~/.bashrc` or `~/.zshrc` 등에 입력 후 `source ~/.bashrc` or `source ~/.zshrc`

```shell
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"
```

## Pyenv로 Python 버전관리

```bash
pyenv install 3.11.6
pyenv global 3.11.6
```

