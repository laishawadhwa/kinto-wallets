
Simple application demonstrating the integration of the [Kinto Wallet SDK](https://www.npmjs.com/package/kinto-web-sdk). The Kinto Wallet SDK provides a seamless way to interact with Kinto's Ethereum Layer 2 solution, enabling fast and secure transactions.


## Installation

To get started with the sample app, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

```bash
git clone https://github.com/KintoXYZ/wallet-transfer-sample
```

2. **Navigate to the Project Directory**: Change into the project directory.

```bash
cd wallet-transfer-sample
```

3. **Install Dependencies**: Use Yarn to install the necessary dependencies.

```bash
yarn install
```

4. **Set up a local certificate**: Needed to run the app on https.

```bash
brew install mkcert
mkcert -install
mkcert dev.kinto.xyz localhost 127.0.0.1 ::1

// You should see something like this
The certificate is at "./dev.kinto.xyz+3.pem" and the key at "./dev.kinto.xyz+3-key.pem" ✅
```

5. **Set up a local DNS**: Change the `etc/hosts` file to run the app locally on dev.kinto.xyz.

```bash
sudo nano /etc/hosts

// Add the following line and save the file
127.0.0.1       dev.kinto.xyz
```

Update your package.json accordingly

6. **Start the Application**: Run the app using Yarn.

```bash
yarn start
```

