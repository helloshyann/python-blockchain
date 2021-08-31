# python-blockchain
 Python & React / Blockchain + Cryptocurreny Project

**ACTIVATE VIRTUAL ENVIRONMENT**
```
source blockchain-env/scripts/activate
```

**INSTALL ALL PACKAGES**
```
pip3 install -r requirements.txt
```

**RUN THE TESTS**
Make sure to activate the virtual environment
```
python -m pytest backend/tests
```

**RUN THE APPLICATION AND API**
Make sure to activate the virtual environment
```
python -m pytest backend.app
```

**RUNNING A PEER INSTANCE**
Activate virtual environment
```
export PEER=True && python -m backend.app
```