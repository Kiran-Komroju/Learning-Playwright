Steps for instaling Playwright
- update and upgarde the packages

      sudo apt update -y
      sudo apt upgrade -y
      pip install --upgrade pip

- Create a python Virtual env for this project

      python -m venv venv
      source venv/bin/activate
          
- To install Playwright with python and its dependencies
  
      pip install playwright
- To install browser binaries

      playwright install
- To upgrade playwright

      pip install playwright -U
- To install playwright with pytest
  
      pip install pytest-playwright
