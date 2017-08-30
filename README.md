# Nuntium Facebook Webhook

This project is an example server for Messenger Platform built in Node.js. With this app, you can create a questionnaire in Surveda and make it availble in Facebook messenger. Here is what this looks like:

![Nuntium Webhook](https://github.com/ICTatRTI/nuntium-fb-webhook/wiki/images/webhook.png)

To see this in action click here: http://m.me/ecigarettestudy

## Setup

The easiest way to get this thing going is to run it on heroku. You'll need to define these variables:

* MESSENGER_APP_SECRET
* MESSENGER_PAGE_ACCESS_TOKEN
* MESSENGER_VALIDATION_TOKEN
* NUNTIUM_PASSWORD
* NUNTIUM_URL
* NUNTIUM_USERNAME
* NUNTIUM_APPLICATION
* SERVER_URL

## Run

Read more about setting up SSL for a [Webhook](https://developers.facebook.com/docs/graph-api/webhooks#setup).

## Webhook

All webhook code is in `app.js`. It is routed to `/webhook`. This project handles callbacks for authentication, messages, delivery confirmation and postbacks. More details are available at the [reference docs](https://developers.facebook.com/docs/messenger-platform/webhook-reference).


## License

See the LICENSE file in the root directory of this source tree. Feel free to use and modify the code.
