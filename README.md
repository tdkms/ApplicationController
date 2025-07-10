# ApplicationController
This repo is designed to forcefully shut down applications when necessary.

I use this as a safety handler for some of my apps, where clients need to review the functionality before making a payment. When shut_down is set to true in the JSON configuration file, the entire server/application is terminated immediately.

This implementation serves as a development backdoor for certain projects, ensuring that clients must test and verify the application before proceeding further.
