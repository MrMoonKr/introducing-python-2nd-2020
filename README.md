# 책 부록 소스 프로젝트 입니다

직무 교육( OJT, On the job Training )을 위해서 클론 하였습니다.  


## 책 관련 링크  

- [Introducing Python 2nd [ 원서 ]](https://www.oreilly.com/library/view/introducing-python-2nd/9781492051374/)  

- [처음 시작하는 파이썬 2판 [ 번역서 ]](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=249209763)  


## 개발 및 테스트 환경

- windows 10  
- Python 3.12.0
- pip 23.2.1
- venv  
- VS Code  
- ...  

  ```
  $ python -m venv .venv-local
  $ .venv-local/Scripts/Activate.ps1 
  $ (.venv-local) python --version
  $ (.venv-local) pip --version
  $ (.venv-local) pip install -r requirements.txt
  ```

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
