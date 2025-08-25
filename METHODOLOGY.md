# SAPITS Methodology

## 🔒 Values and Principles

### 1. Security
Your data security is the MOST important aspect of SAPITS, and we want to explain how we achieve it.

- **Encrypted Hard Drives**: We use LUKS1/LUKS2 for full disk encryption, ensuring that even if someone gains physical access to the drives, they cannot access the data stored on computers dedicated exclusively to SAPITS.

- **Secure Operating System**: QubesOS is our default operating system, offering private and secure isolation for each stage of the process, ensuring maximum possible security for your data.

- **Password Model**: [Not Implemented] We are developing a decentralized system for managing hard drive and login passwords, preventing access centralization and reducing risks of corruption or security threats.

- **E2E Encrypted Messaging**: We use cutting-edge technologies to always provide security between SAPITS and its users. SimpleX Chat is one of the most revolutionary messaging apps at the moment, requiring no phone number or email for use, featuring end-to-end encryption (E2E) to protect your conversations, as well as E2E decentralized servers and the possibility to use incognito profiles for your anonymity.

### 2. Anonymity

#### 2.1 Philosophical Foundations
Anonymity in SAPITS is not just a technical feature but a fundamental philosophical principle. We recognize that in an increasingly surveilled world, the right to privacy has become a basic necessity.

#### 2.2 Freedom of Expression and Identity Protection

##### Core Principles

- **Absence of Direct Human Interaction**:
  - The SAPITS model eliminates the possibility of interpersonal discrimination by removing human-to-human contact at all service points.
  - Automated systems are designed to be completely neutral, without the capacity to judge or discriminate based on personal characteristics.

- **Right to Anonymity**:
  - Users have the absolute right to protect their identity through any means of their choice.
  - Clothing, including items that cover the face or body, cannot be grounds for service denial.

- **Use of TOR**:
  - Users can always use the [Tor protocol](https://orbot.app/en/) to hide their IP while interacting in SimpleX Chat.
  - The use of Tor is highly recommended to enhance online privacy and anonymity.
  - It is also possible to use a private, secure, and transparent VPN like [Mullvad VPN](https://mullvad.net/en/vpn) or [Proton VPN](https://protonvpn.com/free-vpn/server).
  - .onion links: [Mullvad VPN](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion/en/vpn).

##### Surveillance Considerations

1. **Use of Cameras**:
   - **Legal Compliance**: In jurisdictions where surveillance cameras are mandatory:
     - Only the minimum necessary cameras will be installed.
     - Their presence will be clearly indicated.
     - Recordings will be handled with the highest privacy standards.
   
   - **Data Protection**:
     - Recordings will be stored encrypted.
     - Access restricted to authorized personnel only.
     - Minimum retention period required by law.

2. **User Rights**:
   - **In the presence of cameras**:
     - Users retain their right to cover their face and body.
     - Service cannot be denied for exercising this right.
     - Recordings cannot be used to identify users without a court order.

   - **In the absence of cameras**:
     - The same privacy and anonymity rights are maintained.
     - Clothing cannot be grounds for suspicion or denial of service.

3. **Non-Discrimination**:
   - **Express prohibition** of service denial based on:
     - Choice of clothing or face coverings.
     - Physical appearance.
     - Any perceived personal characteristic.

   - **Protection against profiling**:
     - SAPITS systems do not create appearance-based profiles.
     - No facial recognition or biometric systems are used.
     - No personally identifiable data is stored.

#### 2.3 Anonymous Identification System [In Development]

##### Design Considerations

- **Implementation dilemmas**:
  - Balance between utility and privacy.
  - User experience vs. Security.
  - Censorship resistance.

#### 2.4 Future Roadmap

##### Next Steps

1. **Research phase**
2. **Prototype development**
3. **Bug bounty program**

#### 🔐 Technical Proposal

#### 1️⃣ Main Identification System

**ID and Base PIN Generation**

- Each user receives:
  - A unique and anonymous identifier (ID)
  - An 8-digit base PIN
  
**Per-Establishment Features**

- Local generation: Each SAPITS establishment generates its own IDs and PINs
- Independence: A new ID and PIN required for each SAPITS establishment
- Guest mode: Catalog browsing without ID/PIN requirement

**Usage Process**

1. User receives their ID and PIN at start
2. No linking to personal information
3. Valid ID and PIN required for service access

> 📝 **Security Note**: We recommend storing ID and PIN securely:
>
> - On physical paper
> - In a trusted password manager

#### 2️⃣ Temporary PIN System

**Main Features**

- Generation: A unique PIN for each session
- Purpose: Authentication for specific transactions
- Protection: Does not compromise the base password

**Linking and Security**

- Direct association with requested service
- Secure connection between client ID and service
- Prevention of fraud and identity theft

**Operational Benefits**

- Efficiency: Allows technicians to work without user's physical interaction
- Speed: Streamlines service/product delivery
- Security: Minimizes time spent at establishment

**Protection Measures**

- Prevention of:
  - Vulnerabilities
  - Theft
  - Terrorist acts
  - Kidnapping
  - Other associated risks

> ⚠️ **Important Note**: Temporary PINs:
>
> - Have limited duration
> - Are automatically invalidated after use
> - Cannot be reused

### 3. Privacy

#### 3.1 Privacy Principles

1. **What is privacy?**
   - Privacy is the fundamental right of individuals to control their personal information and decide how it is collected, used, and shared.
   - Privacy is often confused with anonymity, but although they are closely related concepts, it's important to differentiate them. Privacy refers to control over personal information, while anonymity refers to the ability to hide one's identity.

2. **Data Minimization**:
   - Only strictly necessary data will be collected to provide the service.
   - Collection of sensitive data will be avoided unless absolutely necessary.

3. **Transparency**:
   - Users will be informed about what data is collected and for what purpose.
   - Options will be provided for users to manage their privacy preferences.

4. **User Control**:
   - Users will have the ability to access, modify, or delete their personal data.
   - Mechanisms will be implemented for users to effectively exercise their privacy rights.

## 🔍 Process

### Initial Phase

#### User

1. **Need**: The user will require an IT service which could consist of many available services (depending on the SAPITS establishment) such as repair, computer equipment maintenance, buying and selling of different products, etc.

2. **Options**: The user will obviously have multiple options from different establishments including those not in the SAPITS protocol. Those users who are more maximalist regarding the privacy and security of their data might consider acquiring a service from a SAPITS establishment instead of a regular one.

3. **Contact**: Contact methods may vary depending on each SAPITS establishment but ALL must use at least [SimpleX Chat](https://simplex.chat/) ([SimpleX Chat .onion](http://isdb4l77sjqoy2qq7ipum6x3at6hyn3jmxfx4zdhc72ufbmuq4ilwkqd.onion/)) as the main contact method.

#### Establishment

1. **Preparation**: By this point, the establishment must already have a physical location and a technical team trained to provide the service. In addition to having already defined the Contact tools to be able to start communication with the client.

  - Must have:

    - One or more computers with QubesOS installed.
    - Communication channels ready and advertised to allow the user to consult the establishment in question.
    - Technical team with sufficient level to be able to provide quality IT services, more specialized services will require deeper knowledge of specific tools and technologies.
    - Have as a basic rule to follow the SAPITS protocol (original or modified) to the letter to guarantee the human and essential rights of clients.

2. **Attention**: The establishment must be prepared to serve the user efficiently and effectively, guaranteeing the privacy and security of their data at all times.

###### Working...

### Intermediate Phase

###### Working...

#### 2.4 Future Roadmap

##### Next Steps

1. **Research phase**
2. **Prototype development**
3. **Bug bounty program**

##### Call to Community
We invite security experts, cryptographers, and privacy enthusiasts to contribute their knowledge and experience.

## 🔄 Continuous Improvement

We welcome suggestions for improving the SAPITS methodology while maintaining our core principles. Please submit your suggestions through our secure channels.

---
*See latest version in commit history*
