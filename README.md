## Spend Desktop Wallet

The project is bootstraped using boostrap, crypto libaries, jquery and electron-forge

It is using spend-js libary to create, recover and sign spend crypto addresses and messages. 

## INSTALLING
### Requirements

#### Ubuntu
In Ubuntu the development files of `libudev` are necessary:
```
sudo apt-get install libudev-dev libusb-1.0-0-dev
```

#### Windows
- Python 2.7
- Visual Studio 2017

``` npm install windows-build-tools --global ```

#### Node 10
To download, head over to [here](https://nodejs.org/en/) and download Node 11.

If you already have npm installed, you can run
```
npm install -g n
sudo n 10
```

#### Yarn
Install the Yarn dependency manager
```
npm install -g yarn
```

### Commands

<details><summary>List of commands</summary>

``` bash
### Install dependencies
yarn install

### Execute the application. Making changes in the code, updates the application (hot reloading).
yarn start

### Build electron application for production (Current OS)
yarn make

## Security

If you discover a security vulnerability within this project, please send an e-mail to chain@spend.org. All security vulnerabilities will be promptly addressed.

s)

## License

[MIT](LICENSE) © [SPEND](https://spend.org)

