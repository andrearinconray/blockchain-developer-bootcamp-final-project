# Trainings and Certifications
## General description
 
**Problem:** It's common for organizations to award certificates upon completion of trainings (or bootcamps!), but often there is no formal way to assess the authenticity of the certification or even the trustworthiness of the certificating company. In the education sector specific companies can endorse certificates or curriculums at a significant cost for each student, and typically won't be able to endorse certifications from smaller companies. This project aims to render education and technical certifications easy to award, verify, and to introduce a shared trust model that eliminates the need for external certification companies.
 
**Solution:** 
1. A service that allows the creation of digital training certificates on the blockchain. The server would allow any address ( owned by a training entity ) to create an entry on the blockchain representing a single unit of training or certificate. Additional metadata can be added to the certificate, including an expiration date for the same or any prerequisite certificate. The certificate can be awarded to an address (owned by the student ), be transferred, or be revoked.
2. A service that allows one address to declare a class of certificates created by an address owned by a training facility as trusted, as well as specify other entities able to assign an additional trust value and decay value on a trust graph. Every entity will be able to revoke trust affecting the trust graph.
 
As a result each actor will be able to verify a certification and to specify or create a trust provider or model that will provide a weighted endorsement for the certification.
 
## Use Cases ##
 
A company would be able to create digital certification about proprietary technologies and issue digital certificates to people attending it's courses. The company could declare a source address for the certifications and third parties could verify them on the blockchain.
 
A set of companies, each one issuing its own certifications, could be declared as trusted by a third party. Any entity would be able to verify a certificate against the trust three created by the third party.
 
A set of institutions could create a trust ( directed, weighted ) graph allowing the verification of certifications against a common model.
