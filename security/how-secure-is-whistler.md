# \[Out-of-date] Security & Privacy

## THIS PAGE IS OUT OF DATE AND WILL BE UPDATED IN MAY 2022

## Security

Tella integrates various security measures in place to achieve an acceptable level of security:

1. All data is encrypted at rest, on the user's device. This means that unless the app is unlocked (by entering the user's pattern), the data it contains cannot be accessed at all. Even if someone seizes the phone and extracts all the data using a computer, the data will remain unreadable. The encryption library we use is [SQLCipher](https://www.zetetic.net/sqlcipher/).&#x20;
2. All data being transferred between Tella and the servers we install for our partner organizations is encrypted through [Transport Layer Security (TLS)](https://en.wikipedia.org/wiki/Transport\_Layer\_Security) and certified by [Let's Encrypt](https://letsencrypt.org).&#x20;

## Privacy

We only collect the minimum amount of data that is necessary to fulfill the purpose of Tella. **We never collect personally identifiable information. We never disclose, share, or sell any of your data to third parties**. Through using our app, users may send data to servers managed by individuals or organizations they're working with (see [Choosing the right documentation method](../deploying-tella/choosing-the-right-documentation-method.md)). We encourage users to ask these individuals or organizations about their data privacy policies, as they may differ from ours. We provide the same standard of privacy protection to all our users no matter where you are in the world.&#x20;

You can read [Tella's full Privacy Policy here](../legal/privacy-policy.md).
