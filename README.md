# 책 부록 소스 프로젝트 입니다

직무 교육( OJT, On the job Training )을 위해서 클론 하였습니다.  


## 책 관련 링크  

- [Introducing Python 2nd [ 원서 ]](https://www.oreilly.com/library/view/introducing-python-2nd/9781492051374/)  

- [처음 시작하는 파이썬 2판 [ 번역서 ]](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=249209763)  


## 개발 및 테스트 환경

- 시스템 ( Computer System )  

  - AMD Ryzen 9 7900X 12-Core Processor
  - 32G RAM
  - NVIDIA Geforce RTX 3060 12GB
  - SSD 2TB
  - Windows 11 64bit Korean

- 파이썬 ( Python 3.12 )  

  - [Python Download](https://www.python.org/downloads/)  
    - [v3.12.0 for Windows](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)  
    - [v3.11.9 for Windows](https://www.python.org/ftp/python/3.11.9/python-3.11.9-amd64.exe)  

- 에디터 ( Editor, Intergrated Development Environment )  

  - [VS Code](https://visualstudio.microsoft.com/ko/free-developer-offers/)  
    - [Python Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python)  
      - Python Interpreter Chooser  
      - Pylance  
      - Python Debugger  
      -  
    - 

- 패키지 매니저 ( Package Manager )
  - [pypi](https://pypi.org/)  
    - [검색](https://pypi.org/search/)  
    - ...
    ```
    $ pip --version
    $ pip --help
    ```
    ```
    $ pip install ipykernel
    $ pip list
    ```
    ```
    $ pip freeze > requirements.txt
    $ pip install -r ./requirements.txt
    ```

- 소스관리  

  - [Install Git](https://git-scm.com/downloads)
    ```
    $ git --version
    ```
  - [Install Tortoisgit](https://tortoisegit.org/download/)


## 사용된 패키지 목록

- ipykernel
  - [pypi](https://pypi.org/project/ipykernel/)  
    ```
    $ (.venv) pip install ipykernel
    ```
  - [ipykernel](https://github.com/ipython/ipykernel)  
  - IPython Kernel for Jupyter

- ...
  - [pypi]()  
    ```
    $ (.venv) pip install ...
    ```
  - [...]()
  - ...  


## ...

---  
---  
---  




## 사전 지식

- Python  
- pip  
- venv  
- jypyter notebook  
- ...  

### MariaDB 

- [Install v11.32](https://mariadb.org/download) with MSI Package
- Edit the system environment variables
  - register system variable "MARIADB_HOME"
  - register "MARIADB_HOME\bin" variable "PATH"
```
$ mysql --version
```

### VS Code

- [Install Latest](https://code.visualstudio.com/)
- [Install python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

### python

- [Install v3.12.0](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)
-  
```
$ python --version
```

### git

- [Install Git](https://git-scm.com/downloads)
- [Install Tortoisgit](https://tortoisegit.org/download/)
```
$ git --version
```

---
---
---

# Introducing Python -- Second Edition
=================

This repository contains the programs featured in 
the second edition of the book _Introducing Python_.
