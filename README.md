## Introduction

I am getting too many fraudulent emails these days. So, to help me annoy the spammers, I've written this script to submit fake credit card details to annoy spammers and polute their database of victims, making it difficult to impossible to distinguish between real and fake data.

## Usage

This script is written for a specific fraudulent website (which, as of the time of writing, has been taken down). This website had two pages. The first page is a login page, requiring the input of an email address and password. After clicking on login, a new form is asking for credit card information. Once this is submitted, data will be send directly to the spammer.

I am using a combination of selenium (to automatically open a webbrowser, populate form fields with things like names, email addresses, and credit card data), as well as clicking buttons automatically. The module Faker is used to generate fake data that immitates people but whose personal details are all fake. I use Beautiful soup here as well to get a list of valid proxies directly from the internet to hide my IP address before connecting to the fraudulent website.

This is for educational purposes only, i.e. this example won't run as the website has been taken down (success!). Use and adapt it for your own scambaiting activities.
