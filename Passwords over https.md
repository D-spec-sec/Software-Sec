Submitting the raw password over HTTPS is the most practical approach for the browser. HTTPS encrypts the communication between the browser and the webserver, ensuring that the password is securely transmitted without being exposed to potential attackers during transit.

In the browser, hashed passwords are computed using a custom JavaScript module. However, this method becomes ineffective if customers disable JavaScript or if antivirus software interferes with its operation. Such an occurrence would have adverse effects on market share, customer satisfaction, and the costs associated with customer services.

If an attacker manages to breach the HTTPS connection, there is no significant difference between sending a raw password or a hashed password. In either case, the attacker can potentially steal the access token and hijack the session, resulting in almost identical residual risks.

Additionally, sending a hashed password implies that the user's password must be hashed or salted, making it irreversible. However, certain websites may require support for a "retrieve password" feature where passwords are encrypted, and customers can inquire about their forgotten passwords.
