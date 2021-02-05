# Choosing the right documentation method

Tella can be used by individuals to protect themselves, but is often deployed by groups and organizations to collect data on a large scale. Because organizations have different documentation needs and varying levels of financial and technical capacity, Tella supports three different methods to collect data and document events. Before deploying Tella, it is important to identify which method best fits the organization's needs and capacity. If you are unsure, or if you need support deploying the different methods outlined below, contact us at contact@tella-app.org. 

Here is a summary of the three documentation methods available:

|  | Third-party app | Structured forms | Tella Reports |
| :--- | :--- | :--- | :--- |
| **Summary** | Users share files through Tella's "Share" feature The files are shared through a third-party, like WhatsApp, Signal, or an email app.  | Users fill their organization's forms, answering custom questions and attaching files. | Users create and send reports that include files and a short text description  |
| **Verification information** | Users can share verification information along with their files. Each file's verification information is shared as a separate spreadsheet. | Verification information is automatically attached to the form. It is displayed as a long string of text in the data table in a moderately usable format | Verification information is automatically sent along with the report. It is displayed in the back-office in a usable format, with location shown on a map.  |
| **Speed** | Quick: users simply need to select the files, select what app to share them through, and send. | Slow: users needs to select the form, answer all questions, manually attach the files they want to send, and submit. | Very quick: users select their files, optionally type in a description, and send. THey can also opt for "auto-upload": files are immediately sent as soon as recorded. |
| **Infrastructure** | No infrastructure required: users can download Tella and immediately start documentating and share their documentation. | Back-office server: organizations need to either install the data-collection software on their own server or use a public one. | Back-office server: organizations need to install the data-collection software on their own server. |

### Sharing files through third-party apps

Organizations can train their members on the use of Tella's core features for documentation purposes. Their members can then share their photo, video, and audio files through Tella's "Share" feature, which functions similarly to sharing files from the device's gallery. The files are shared through a third-party, like WhatsApp, Signal, or an email app. This presents the advantage of being accessible to any user and organization, as it requires no infrastructure at all beyond installing Tella on the users' devices. 

However, it does present risks, as the third-party app\(s\) used to share the files will have access to those files. These apps may save the files on the device's unencrypted storage or on their server. For example, sharing a photo through WhatsApp would immediately save a copy of the photo on the device's gallery, making it accessible to anyone searching the device. If using this feature, it is advisable to use trustable apps like Signal and to enable protection features like disappearing messages. 

### Collecting data through structured forms

Tella supports form-based data collection. This means that organizations can create their own forms, asking specific questions based on the data they want to collect. Users can download the forms and submit data directly from within Tella. 

Tella uses the [Open Data Kit \(ODK\)](http://opendatakit.org/) standard; as such it is compatible with a wide range of tools that are ODK-compliant. Those tools are used to create forms with custom questions, manage users, and aggregate the data submitted by users. You can pick any of the ODK-compliant data collection tools--y[ou can find some of those tools here](https://opendatakit.org/community/ecosystem/). We recommend [KoBoToolbox](http://kobotoolbox.org/), a free and open-source software that is very powerful yet accessible to new users. KoBoToolbox provides a hosted version their software accessible for free to anyone. 

{% hint style="info" %}
When using KoBoToolbox's free service, the data is hosted on their server and is therefore accessible to their staff and to government subponea, and potentially to hackers.
{% endhint %}

Organizations that need additional privacy and security can install the software on their own servers. This may provide extra protection for their server and full control over the data they collect. For organization that lack the technical capacity to install KoBoToolbox on their server, Horizontal can do it. We can also configure the servers to receive large attachments \(the free and hosted version of KoBoToolbox only supports attachments below 80MB\). 

This is a great solution for deployments that require the collection of large amounts of data, as all of the data submitted by users is aggregated into a database that can be exported as a spreadsheet. 

### Tella Reports \(to be released on June 1st, 2021\)

For some organizations, structured forms are too cumbersome: they take time to open, fill, and sent. Often, what is needed is to send documentation as quickly as possible, before anyone can try to delete it from the device. This is what Tella Reports is for.

With Tella Reports, all users have to do is select the files and send them. They can also add a short text description to add some information, but this is optional. 

Users also have the option to enable auto-upload: as soon as they take a photo or a video, or record audio, the file is immediately and automatically sent to the server. They can also enable auto-delete: as soon as the file is uploaded to the server, it is automatically deleted from their device. 

The back-office to manage users, view their reports, and download them is called Tella Web. Because organizations using Tella Web collect sensitive data, there is no public instance. The software must be installed on a server. You can either install it on your own server or Horizontal can help you do it. 



