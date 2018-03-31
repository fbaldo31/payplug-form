# payplug-form

Official Payplug form.js file

## Install

`npm i payplug-form`

## Usage

`import * as Payplug from 'payplug-form/index';`

```js
// First manage on server side the payment_url generation:
// https://docs.payplug.com/api/apiref.html#create-a-payment

// Once you get it from your server:
Payplug.showPayment(data.hosted_payment_url);

```