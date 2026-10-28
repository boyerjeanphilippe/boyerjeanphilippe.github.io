# boyerjeanphilippe.github.io

GitHub Pages site for a Tesla Fleet API public key used by the Home Assistant Tesla Fleet integration.

Tesla fetches the key at:

https://boyerjeanphilippe.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

The key file is not in this repository yet. When you have it, add it as `.well-known/appspecific/com.tesla.3p.public-key.pem`. Do not commit the private key.

An empty `.nojekyll` file at the repository root disables Jekyll, which would otherwise skip the `.well-known` directory.
