# Tesla Fleet API public key

This directory is where the Tesla Fleet API public key for the Home Assistant Tesla Fleet integration will live.

Add the key later as:

`com.tesla.3p.public-key.pem`

That is the only file Tesla fetches, at:

https://boyerjeanphilippe.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

Put the public key Home Assistant shows during Tesla Fleet setup into that file. Do not generate a substitute key here, and do not commit the private key.

The empty `.nojekyll` file at the repository root turns off Jekyll so this `.well-known` directory is published with the rest of the site.
