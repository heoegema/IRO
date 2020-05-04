### Mr. Squiggles' Blockchain

![image info](./frontend/src/assets/Squiggle.png)

This is the course project completed as a part of the  ["Python, JS & React | Build a Blockchain and Cryptocurrency"](https://www.udemy.com/course/python-js-react-blockchain) course on udemy. 

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
