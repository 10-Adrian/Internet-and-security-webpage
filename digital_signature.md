<header class="definition-header">
<h1 class="definition-title">Digital signature</h1>
</header>
<div id="content-center" class="content-center">
<section id="content-body" class="section definition-section" data-menu-title="Definition">
<p style="text-align: justify;"><img src="https://www.smartdatacollective.com/wp-content/uploads/2019/05/digital-signature-data.jpg" alt="How Big Data Offers Better Electronic Signature Solutions" /></p>
<p style="text-align: justify;">A digital signature is a mathematical technique used to validate the authenticity and integrity of a message, software or digital document. It's the digital equivalent of a handwritten signature or stamped seal, but it offers far more inherent security. A digital signature is intended to solve the problem of tampering and impersonation in digital communications.</p>
<p style="text-align: justify;">Digital signatures can provide evidence of origin, identity and status of electronic documents, transactions or digital messages. Signers can also use them to acknowledge informed consent.</p>
<p style="text-align: justify;">In many countries, including the United States, digital signatures are considered legally binding in the same way as traditional handwritten document signatures.</p>
<section class="section main-article-chapter" data-menu-title="How do digital signatures work?">
<h3 class="section-title">1. How do digital signatures work?</h3>
<p style="text-align: justify;">Digital signatures are based on public key cryptography, also known as asymmetric cryptography. Using a public key algorithm, such as RSA (Rivest-Shamir-Adleman), two keys are generated, creating a mathematically linked pair of keys, one private and one public.</p>
<p style="text-align: justify;">Digital signatures work through public key cryptography's two mutually authenticating cryptographic keys. The individual who creates the digital signature uses a private key&nbsp;to encrypt signature-related data, while the only way to decrypt that data is with the signer's public key.</p>
<p style="text-align: justify;">If the recipient can't open the document with the signer's public key, that's a sign there's a problem with the document or the signature. This is how digital signatures are authenticated.</p>
<p style="text-align: justify;">Digital signature technology requires all parties trust that the individual creating the signature has kept the private key secret. If someone else has access to the private signing key, that party could create fraudulent digital signatures in the name of the private key holder.</p>
</section>
</section>
</div>
<section class="section main-article-chapter" data-menu-title="What are the benefits of digital signatures?">
<h3 class="section-title">2. What are the benefits of digital signatures?</h3>
<p style="text-align: justify;">Security is the main benefit of digital signatures. Security capabilities embedded in digital signatures ensure a document is not altered and signatures are legitimate. Security features and methods used in digital signatures include the following:</p>
<ul class="default-list">
<li style="text-align: justify;"><strong>Personal identification numbers (PINs), passwords and codes.</strong>&nbsp;Used to authenticate and verify a signer's identity and approve their signature. Email, username and password are the most common methods used.</li>
<li style="text-align: justify;"><strong>Asymmetric cryptography.</strong> Employs a public key algorithm that includes private and public key encryption and authentication.&nbsp;</li>
<li style="text-align: justify;"><strong>Checksum.</strong> A long string of letters and numbers that represents the sum of the correct digits in a piece of digital data, against which comparisons can be made to detect errors or changes. A checksum acts as a data fingerprint.</li>
<li style="text-align: justify;"><strong>Cyclic redundancy check (CRC</strong><strong>).</strong>&nbsp;An error-detecting code and verification feature used in digital networks and storage devices to detect changes to raw data.</li>
<li style="text-align: justify;"><strong>Certificate authority (CA</strong><strong>) validation.</strong> CAs issue digital signatures and act as trusted third parties by accepting, authenticating, issuing and maintaining digital certificates. The use of CAs helps avoid the creation of fake digital certificates.</li>
<li style="text-align: justify;"><strong>Trust service provider (TSP) validation.</strong>&nbsp;A TSP is a person or legal entity that performs validation of a digital signature on a company's behalf and offers signature validation reports.</li>
</ul>
<p style="text-align: justify;">Other benefits to using digital signatures include the following:</p>
<ul class="default-list">
<li style="text-align: justify;"><strong>Timestamping.</strong>&nbsp;By providing the data and time of a digital signature, timestamping is useful when timing is critical, such as for stock trades, lottery ticket issuance and legal proceedings.</li>
<li style="text-align: justify;"><strong>Globally accepted and legally compliant.</strong> The public key infrastructure (PKI) standard ensures vendor-generated keys are made and stored securely. Because of the international standard, a growing number of countries are accepting digital signatures as legally binding.</li>
<li style="text-align: justify;"><strong>Time savings.</strong>&nbsp;Digital signatures simplify the time-consuming processes of physical document signing, storage and exchange, enabling businesses to quickly access and sign documents.</li>
<li style="text-align: justify;"><strong>Cost savings.</strong>&nbsp;Organizations can go paperless and save money previously spent on the physical resources and on the time, personnel and office space used to manage and transport them.</li>
<li style="text-align: justify;"><strong>Positive environmental impact. </strong>Reducing paper use also cuts down on the physical waste generated by paper and the negative environmental impact of transporting paper documents.</li>
<li style="text-align: justify;"><strong>Traceability.</strong>&nbsp;Digital signatures create an audit trail that makes internal record-keeping easier for business. With everything recorded and stored digitally, there are fewer opportunities for a manual signee or record-keeper to make a mistake or misplace something.</li>
</ul>
</section>
<section class="section main-article-chapter" data-menu-title="How do you create a digital signature?">
<h3 class="section-title">3. How do you create a digital signature?</h3>
  <h3>3.1 Tutorial video</h3>
<p>Create your own signature in an electronic format very quickly and easily using a pen, paper, your mobile phone, your email, a snipping tool, onlinepngtools (png transparency creator) and that is it!</p>
 <iframe width="560" height="315" src="https://www.youtube.com/embed/qKQT5HW4kxY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 

<p style="text-align: justify;">To create a digital signature, signing software, such as an email program, is used to provide a one-way hash of the electronic data to be signed.</p>
<p style="text-align: justify;">A hash is a fixed-length string of letters and numbers generated by an algorithm. The digital signature creator's private key is then used to encrypt the hash. The encrypted hash -- along with other information, such as the hashing algorithm -- is the digital signature.</p>
<p style="text-align: justify;">The reason for encrypting the hash instead of the entire message or document is a hash function can convert an arbitrary input into a fixed-length value, which is usually much shorter. This saves time as hashing is much faster than signing.</p>
<p style="text-align: justify;">The value of a hash is unique to the hashed data. Any change in the data, even a change in a single character, will result in a different value. This attribute enables others to use the signer's public key to decrypt the hash to validate the integrity of the data.</p>
<p style="text-align: justify;">If the decrypted hash matches a second computed hash of the same data, it proves that the data hasn't changed since it was signed. If the two hashes don't match, the data has either been tampered with in some way and is compromised or the signature was created with a private key that doesn't correspond to the public key presented by the signer -- an issue with authentication.</p>
<figure class="main-article-image full-col" style="text-align: justify;" data-img-fullsize="https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f.png"><img class="" src="https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f_mobile.png" srcset="https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f_mobile.png 960w,https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f_desktop.png 1280w" alt="How digital signatures work" data-src="https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f_mobile.png" data-srcset="https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f_mobile.png 960w,https://cdn.ttgtmedia.com/rms/onlineimages/security-digital_signature_process-f_desktop.png 1280w" />
<figcaption>A person creates a digital signature using a private key to encrypt the signature. At the same time, hash data is created and encrypted. The recipient uses the signer's public key to decrypt the signature.</figcaption>
<div class="main-article-image-enlarge">&nbsp;</div>
</figure>
<p style="text-align: justify;">A digital signature can be used with any kind of message, whether it is encrypted or not, simply so the receiver can be sure of the sender's identity and the message arrived intact. Digital signatures make it difficult for the signer to deny having signed something as the digital signature is unique to both the document and the signer and it binds them together. This property is called nonrepudation.</p>
<p style="text-align: justify;">Digital signatures are not to be confused with digital certificates. A digital certificate is an electronic document that contains the digital signature of the issuing CA. It binds together a public key with an identity and can be used to verify that a public key belongs to a particular person or entity.</p>
<p style="text-align: justify;">Most modern email programs support the use of digital signatures and digital certificates, making it easy to sign any outgoing emails and validate digitally signed incoming messages. Digital signatures are also used extensively to provide proof of authenticity, data integrity and nonrepudiation of communications and transactions conducted over the internet.</p>
</section>

<p><strong>Internet security:</strong></p>
<h3><a href="https://10-adrian.github.io/Internet-and-security-webpage/internet_security.html"><span style="background-color: #ffff00;">Internet_security</span></a></h3>
<p><strong>Accesibility standards:</strong></p>
<h3><span style="background-color: #ff9900;"><a style="background-color: #ff9900;" href="https://10-adrian.github.io/Internet-and-security-webpage/accesibility_standards.html">Accesibility_standards</a></span></h3>
<p><strong>Object oriented programming VS Structured programming:</strong></p>
<h3><a href="https://10-adrian.github.io/Internet-and-security-webpage/object_oriented_programming_vs_structured_programming.html"><span style="background-color: #00ffff;">Object_oriented_programming_VS_Structured_programming</span></a></h3>






