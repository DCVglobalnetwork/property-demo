# 🏠 SmartDee Demo – Chainlink x HTML

This is a simple front-end demo (`index.html`) for the **SmartDee** Chainlink Hackathon project. It simulates how a property oracle system would fetch, verify, and display property data using **Chainlink Functions**.

---

## 🌍 Live HTML Demo

📺 [Click to view the property demo page](https://dcvglobalnetwork.github.io/property-demo/)

This HTML demo page displays:
- Property ID
- Estimated Market Value
- Location

Used for simulating how Chainlink Functions would return verified external property data into your smart contract.


## 🚀 Live Demo

Check out the live demo of this project here:  
[https://property-demo-2025.netlify.app](https://property-demo-2025.netlify.app)

You can also scan the QR code in the project brochure or slides to open the demo directly on your device!

![image](https://github.com/user-attachments/assets/d6665569-7702-4c6e-9f5c-41a07b00dd5f)


---

## 🧱 Repo Structure

property-demo/ - index.html (HTML demo file with mock property data), README.md (You're reading it)


---

## 💼 Business & Money

### 💰 Real Use. Real Clients. Real Money.

This isn’t just a hack. It’s a **product**.

#### Revenue Potential:
- SaaS/API pricing per property check
- White-label version for mortgage firms & insurers
- Add fees, whitelist, and access control later

#### Clients:
✅ Momo Finance  
✅ Property lenders & credit scoring platforms  
✅ DeFi mortgage apps

### 🔖 Tagline:
> 💰 Turn property data into revenue — with Chainlink

---

## 🔮 Use Case Summary

- Chainlink Functions connects smart contracts to **external property data**.
- Property ID, estimated value, and geolocation are parsed and stored on-chain.
- This HTML page mocks the UI side of that process for the hackathon submission.

---

## 🚀 Future Development (Advanced Version)

| Feature                     | Status   | Description                                              |
|----------------------------|----------|----------------------------------------------------------|
| ✅ Whitelist Access        | Planned  | Only authorized users can call request function         |
| ✅ Access Control / Owner  | Planned  | Use Ownable or AccessControl for permissions             |
| ✅ Request Fee Logic       | Optional | Add LINK or ETH fee per request                          |
| ✅ Request Throttling      | Optional | Prevent spam/frequent re-calls                           |
| ✅ Dynamic JS Scripts      | Future   | Allow different scripts per property ID or source        |
| ✅ IPFS / External API     | Future   | Use real APIs instead of mock data                       |

---

## 🧪 Remix & Chainlink Functions: Technical Recap

While testing in Remix:

- Encountered **gas estimation errors** during simulation.
- Problem: Remix cannot simulate off-chain Chainlink Function calls correctly.
- Workaround: Clearly demonstrated contract logic and fallback UI using HTML.
- Plan: Switch to Hardhat + staging environment for full Chainlink E2E testing.

---

## 📸 What to Include in the Submission

- ✅ Screenshot of Remix IDE + successful request ID
- ✅ Screenshot of property data parsed (ID, value, location)
- ✅ QR Code to this GitHub repo or demo HTML page

---

https://dcvglobalnetwork.github.io/property-demo/


2. Open `index.html` in any browser.
3. Use the mock property data to simulate Chainlink output.

---

## 🔗 Project Links

- **Canva Design (Brochure/Slides):** [View on Canva](https://www.canva.com/design/DAGrqBWirLk/SAArdJnI_be1nVvHEw-1oQ/view?utm_content=DAGrqBWirLk&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h4229c9811c)

- **Live Demo:** [https://property-demo-2025.netlify.app/](https://property-demo-2025.netlify.app/)

- **GitHub Repository:** [https://github.com/DCVglobalnetwork/property-demo](https://github.com/DCVglobalnetwork/property-demo)


---

## 🙌 Acknowledgements

- Chainlink Functions Docs  
- Remix IDE  
- Ethereum Sepolia Faucet  
- Canvas for pitch design  
- Judges & real client feedback  

---

## 📜 License

MIT License

© 2025 DCV Global Network

---



