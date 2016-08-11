(Lots of this data is from wikipedia, summarized by me.)

# PKI (Public Key Infrastructure).

A set of roles, policies, and procedures needed to create, manage, distribute, use, store, and revoke digital certificates.

An arrangement that binds public keys with the respective identities of entities (like persons and organizations). This binding is established by registration and issuance of certificates at and by a certificate authority.

Entities must be uniquely identifiable within each CA domain on the basis of information about that entity.

Consists of
- A certificate authority.
- A registration authority.
- A central directory.
- A certificate management system.
- A certificate policy.

A large corporation may have its own **internal** PKI infrastructure that issues certificates and deploys them.

## CA (Certificate Authority).

AKA *certification authority*

An entity that issues digital certificates.

In the predominant model, a CA is a **trusted third party**, trusted by the *subject* (owner) of the certificate and by the party relying on the certificate.

Any site using self-signed certificates acts as its own CA.

## Certificates

Digital certificates certifies the ownership of a public key by the named subject of the certificate. This allows *relying parties* to rely upon the signatures or assertions made about the private key that corresponds to the certified public key.

Use of certificates defends against the **man-in-the-middle** attack.

Usually client software includes a set of trusted CA certificates.

### Structure

A certificate contains a public key and the identity of the owner. The matching private key is not public, but kept secret by the end user who generated the key. 

### Self-signed certificates.

A self-signed certificate is one that is signed by the same entity whose identity it certifies. Technically it is **signed with its own private key**.

They can be created by a wide variety of tools (e.g. OpenSSL) and are easier to customize than those issued by a CA.

# PKI example.

Log into a website -> receive a public key along with the webpage
data.  The public key could be used to encrypt data from the client to
the server. Usually a safe procedure is to use this public key in a
protocal that generates a temporary shared symmetric key; this key
exchange protocol uses the public key.

The rest of the communication uses the disposable symmetric key.

This only works if the client can be sure the server they are talking
to is who they say they are. When the client receives the public key,
it also receives a digital signature of the key (X.509
Certificate). With the public key, it can verify the digital signature
and trust the certificate and the public key to use in the exchage
protocol. Any "fake" server cannot know the private key and so can't
create the digital signature.

