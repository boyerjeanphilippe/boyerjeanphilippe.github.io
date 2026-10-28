# Tesla Fleet API public key

This directory holds the Tesla Fleet API public key for the Home Assistant Tesla Fleet integration.

The public key file is `com.tesla.3p.public-key.pem`. Tesla fetches it at:

https://boyerjeanphilippe.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

Do not commit the private key.

The empty `.nojekyll` file at the repository root turns off Jekyll so this `.well-known` directory is published with the rest of the site.
