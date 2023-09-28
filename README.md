# CIRA Digital Trust

![Large](https://github.com/Northern-Block/CIRA-Digital-Trust/assets/67612904/8485cdad-0b8e-40bb-aab8-55affdaf63ec)

DNS brought trust to the internet by enabling the mapping of human typable/readable/friendly domain names to IP addresses. But in this model, there are a lot of trust assumptions that we make in typing in a domain name into a browser:

1. Correct Mapping: We trust that the Domain Name System (DNS) correctly maps the domain name to the correct IP address. This means that when we type in a domain name, we trust that we are being directed to the correct server and not being redirected to a malicious site.
2. Security of the DNS: We trust that the DNS itself is secure and has not been compromised. DNS hijacking, where an attacker redirects queries to a different domain, is a known threat. We assume that protections are in place to prevent this.
3. Authenticity of the Website: We trust that the website we reach is the authentic one that it claims to be, and not a phishing site or a site created for malicious purposes.
4. Privacy: We trust that our interactions with the website are private and not being monitored or intercepted by third parties.
5. Data Integrity: We trust that the data we send and receive has not been tampered with during transmission.
6. Secure Transactions: If we're conducting transactions, we trust that our financial and personal information is being securely handled and stored.
7. Certificate Authorities: We trust that the Certificate Authorities (CAs) that issue SSL/TLS certificates to the website have properly validated the website's identity before issuing the certificate.
8. Browser Security: We trust that our web browser correctly implements security protocols and will warn us if we're trying to visit a potentially dangerous site.
9. Up-to-date Information: We trust that the information we're accessing is up-to-date and accurate.

Based on this list, to interact directly with a website, we as consumers place trust in intermediaries such as DNS server operators, CAs and browser developers.

While DNSSEC provides a model to create integrity on data transmitted between a user and a website ensuring the “pathway” has not been compromised and messages are relayed with integrity, it does not provide a model where the end point participants themselves are authentic, validated and are who they say they are.
