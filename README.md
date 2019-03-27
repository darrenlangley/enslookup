# enslookup

A command line utility to query the Ethereum Name Service

## Install

Clone this repository:
```shell
git clone https://github.com/darrenlangley/enslookup.git
```

Change into directory:
```shell
cd enslookup
```

Install dependencies:
```shell
npm install
```

If you are on Linux or macOS, make the `enslookup` executable:
```shell
chmod +x enslookup
```

## Usage

```shell
enslookup <ensname>
```

## Example

```shell
./enslookup ethereum.eth
Name:		ethereum.eth
Resolver:	0x1da022710dF5002339274AaDEe8D58218e9D6AB5
Address:	0xfB6916095ca1df60bB79Ce92cE3Ea74c37c5d359 (3295.179176904502385668 ether)
Public Key:
		x = 0x0000000000000000000000000000000000000000000000000000000000000000
		y = 0x0000000000000000000000000000000000000000000000000000000000000000
```

*Note on Windows you will have to run `node enslookup`*