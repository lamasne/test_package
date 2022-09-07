to install package:
    in venv, use command:
        python -m pip install git+https://github.com/lamasne/test_package.git
    then in a python file, you can test
        from test_package.main import my_fct
        my_fct(['hey', 'ho'])
