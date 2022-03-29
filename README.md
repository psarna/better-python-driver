## How to run the smoke test

1. Run scylla
2. Set up virtualenv, e.g. in `~/local/venv` directory
3. Enter the virtual env via `. ~/local/venv/bin/activate`
4. Run:
 ```bash
  pip install --user maturin
  mkdir -p ~/local/venv
  VIRTUALENV=~/local/venv maturin develop
 ```
5. Run the example python code - it works!
```bash
  python example.py
```

