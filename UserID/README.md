ここでは、userが、botuserではないかの検証を行う。

今回は、Worldcoinのapiを用いて、実装する予定ある。


How it works
In broad strokes, this is how World ID works.

User gets their World ID in a compatible wallet (e.g. the World App).

User receives credentials in their World ID. The flagship credential is biometric verification, currently available by using the Orb. The user can also verify their phone number to obtain the respective credential.

Project integrates with World ID.

User connects their World ID to authenticate, and optionally prove they are a unique human doing something only once. The user's wallet will generate a Zero-Knowledge Proof to accomplish this.

Project verifies the Zero-knowledge Proof, either by using the API or by verifying on-chain.