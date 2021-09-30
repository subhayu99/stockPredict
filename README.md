# FINAnce preDICT

A simple and easy to use Stocks / Cryptocurreny / Foreign Exchange prices predictor.

## Live website : [finadict.tech](https://finadict.tech/)


## Install locally

### On Linux 

> **Ubuntu / Debian**

```shell
sudo apt-get update && apt-get upgrade
sudo apt-get install python3-pip
git clone https://github.com/subhayu99/finadict.git
cd finadict
sudo pip3 install -r requirements.txt
streamlit run app.py
```

### On a docker container

> **Using docker image**

```shell
sudo docker run -d -i --name finadict -h finadict -p 80:80 -e STREAMLIT_SERVER_PORT=80 subhayu99/finadict:latest
```

> **Using Dockerfile**

```shell
mkdir finadict && cd finadict
wget https://raw.githubusercontent.com/subhayu99/finadict/main/Dockerfile
sudo docker build -t subhayu99/finadict:latest .
sudo docker run -d -i --name finadict -h finadict -p 80:80 -e STREAMLIT_SERVER_PORT=80 subhayu99/finadict:latest
```

> **Using docker-compose**

```shell
mkdir finadict && cd finadict
wget https://raw.githubusercontent.com/subhayu99/finadict/main/compose.yaml
sudo docker-compose up -d
```

---

# Program Screenshot

### Stock's Raw Data
<br>
<p align="center"><img src="Screenshot/1.png" align="center" alt="screenshot"></p>
<br>

### Raw Data Graph
<br>
<p align="center"><img src="Screenshot/2.png" align="center" alt="screenshot"></p>
<br>

### Stock's Predicted Data
<br>
<p align="center"><img src="Screenshot/3.png" align="center" alt="screenshot"></p>
<br>

### Predicted Data Graph
<br>
<p align="center"><img src="Screenshot/4.png" align="center" alt="screenshot"></p>
<br>

---

