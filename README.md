# Supranodes Latency Tester (Windows version)

>To test the latency of a node, a simple ping is not accurate.
>
>This tester is sending web3 requests to the node to test the latency. 


# Windows .exe Version:
download these 2 files

https://github.com/supranodes/Supranodes-latency-tester-windows/blob/main/supranodes-latency-tester.exe

https://github.com/supranodes/Supranodes-latency-tester-windows/blob/main/settings.json

## Edit settings.json (example):
{

"endpoints": ["https://bsc-dataseed1.binance.org/","http://127.0.0.1:8000","ws://127.0.0.1:8546"]

}
## launch exe file
## Enter the amount of request you want to send
(Public nodes: 100-150 // Private Node, 800-1000)


# Windows Python Version:
you need python - pip - web3

## Install python pip
apt install python3-pip -y

## Install web3
pip install web3

## Edit settings.json (example):
{

"endpoints": ["https://bsc-dataseed1.binance.org/","http://127.0.0.1:8000","ws://127.0.0.1:8546"]

}

## Run script:
python3 supranodes-latency-tester.py

## Enter the amount of request you want to send
(Public nodes: 100-150 // Private Node, 800-1000)
