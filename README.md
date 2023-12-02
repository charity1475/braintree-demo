# Braintree Payment Gateway Demo

A simple Node.js application demonstrating the integration with the Braintree payment processing gateway using express. Follow the steps below to set up the demo on your local machine.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/charity1475/braintree-demo.git
   cd braintree-demo
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Create a Braintree Sandbox Account:**
   - Go to [Braintree Sandbox](https://sandbox.braintreegateway.com/).
   - Log in or create a new account.
   - In the sandbox Control Panel, click on the gear icon in the top right corner.
   - Select API from the drop-down menu.
   - Scroll to the Tokenization Keys section.
   - Obtain your Tokenization Key. If no key appears, click the "Generate New Tokenization Key" button.
   - Note down your Sandbox Merchant ID, Public Key, and Private Key.

4. **Set Up Environment Variables:**
   - Duplicate the `.env.example` file and rename it to `.env`.
   - Open the `.env` file and fill in the following details:
     ```env
     BRAINTREE_ENV=sandbox
     BRAINTREE_MERCHANT_ID=your_sandbox_merchant_id
     BRAINTREE_PUBLIC_KEY=your_sandbox_public_key
     BRAINTREE_PRIVATE_KEY=your_sandbox_private_key
     ```

5. **Run the Application:**
   ```bash
   npm start
   ```

6. **View the Demo:**
   Open your web browser and go to [http://localhost:3000](http://localhost:3000).

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to modify the sections or add more information based on the specific details of your project. Make sure to replace placeholders like `your_sandbox_merchant_id` with the actual values obtained from your Braintree Sandbox account.
