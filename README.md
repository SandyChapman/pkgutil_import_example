To execute, add deps/dep_1 and deps/dep_2 to your PYTHONPATH and run main.py:

```fish
set -x PYTHONPATH (pwd)/deps/dep_1:(pwd)/deps/dep_2
python ./main.py
```

```bash
export PYTHONPATH=`pwd`/deps/dep_1:`pwd`/deps/dep_2
python ./main.py
```