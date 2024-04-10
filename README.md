# paypal-payment-integration

<img src="paypal.webp" align="right" width="300px"/>

Integrate Paypal Advanced Payment API (this is not available to all countries) please see the list of supported currency & countries

## Getting started
- Fork the repository  <br>
  https://github.com/mrepol742/paypal-payment-integration/fork
- Clone fork the repository
  ```sh
  # using https
  git clone https://github.com/<your-username>/paypal-payment-integration
  
  # using ssh
  git clone git@github.com:<your-username>/paypal-payment-integration
  ```
- Install dependencies
  ```sh
  cd paypal-payment-integration/server && npm i
  ```
- Configure .env
  ```sh
  cp .env.example .env
  nano .env
  # configure the CLIENT_ID and CLIENT_SECRET
  ```
- Run the project
  ```sh
  npm run start
  ```
- Now run the frontend
  ```sh
  cd .. && cd client
  nano script.js
  # Line 54 add your CLIENT_ID

  # u can use python http
  python3 -m http.server
  # or vscode live server extension 
  # it's up to you
  # you can open the index.html in browser too
  ```

## Card testing
Please head to the following link to generate card details used for sandbox testing
https://developer.paypal.com/api/rest/sandbox/card-testing/#link-creditcardgeneratorfortesting


## Contribute
Code contributions are welcome! Please commit any pull requests against the master branch. Security audits and feedback are welcome. Please open an issue or email us privately if the report is sensitive in nature.