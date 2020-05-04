### Project for "Python, JS, & React| Build a Blockchain and Crytpocurrency"

![image info](./frontend/src/assets/Squiggle.png)

**To Activate the Virtual Environment**
```
source blockchain-env/bin/activate
```

**Install all packages**
```
pip3 install -r requirements.txt
```

**Run Tests**

Note: Make sure you are running the virtual environment

```
python3 -m pytest
```

**Run the Application and API**

Note: Make sure you are running the virtual environment

```
python3 -m backend.app
```

**Run a peer instance**

Note: Make sure you are running the virtual environment

```
export PEER=True && python3 -m backend.app
```

**Run the frontend***

In the frontend directory:
```
npm run start
```

**Seed the backend with data**
Note: Make sure you are running the virtual environment

```
export SEED_DATA=True && python3 -m backend.app
```
