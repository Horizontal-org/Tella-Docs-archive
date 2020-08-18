# Security

Tella integrates various security measures in place to achieve an acceptable level of security:

1. All data is encrypted at rest, on the user's device. This means that unless the app is unlocked \(by entering the user's pattern\), the data it contains cannot be accessed at all. Even if someone seizes the phone and extracts all the data using a computer, the data will remain unreadable. The encryption library we use is [SQLCipher](https://www.zetetic.net/sqlcipher/). 
2. All data being transferred between Tella and the servers we install for our partner organizations is encrypted through [Transport Layer Security \(TLS\)](https://en.wikipedia.org/wiki/Transport_Layer_Security) and certified by [Let's Encrypt](https://letsencrypt.org/). 

