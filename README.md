
# ShwanSurksha - Pet Dog Insurance

ShwanSurksha is a decentralized insurance platform built using Solidity and React that allows users to manage insurance policies for their pets. The smart contract on the Ethereum blockchain handles the creation, premium calculation, and claim processing for pet insurance policies.

## Features

- Policy Creation: Users can create new insurance policies for their pets by providing details such as pet breed, age, health condition, region, and policy type (accident, illness, or wellness).
- Premium Calculation: The smart contract calculates the premium amount for each policy based on the provided details and stores it in the policy struct.
- Payout Calculation: The smart contract also calculates the payout amount for each policy based on the premium amount and a payout percentage, which can be customized for each policy type.
- Claim Processing: Users can claim their policy payout by calling the "fulfilThePolicyClaim" function, which transfers the payout amount to the policy holder's address if the claim is valid and not already claimed.
- Policy Management: Users can view and manage their insurance policies, including checking the policy details, premium amount, payout amount, and claim status.

## Usage

1. Install Dependencies: Install the necessary dependencies for the smart contract and frontend application using npm or yarn.
2. Deploy Smart Contract: Deploy the ShwanSurkshaClaimVerifier smart contract on the Ethereum blockchain using a compatible Ethereum client such as Ganache or a testnet like Rinkeby or Ropsten.
3. Connect to Smart Contract: Connect the frontend application to the deployed smart contract by providing the contract address and ABI.
4. Create Insurance Policy: Users can create a new insurance policy by providing the required details such as pet breed, age, health condition, region, and policy type using the frontend application.
5. Calculate Premium: The smart contract will calculate the premium amount based on the provided details and store it in the policy struct.
6. Calculate Payout: The smart contract will also calculate the payout amount based on the premium amount and a payout percentage, which can be customized for each policy type.
7. Claim Policy Payout: Users can claim their policy payout by calling the "fulfilThePolicyClaim" function using the frontend application. The smart contract will transfer the payout amount to the policy holder's address if the claim is valid and not already claimed.
8. Manage Policies: Users can view and manage their insurance policies, including checking the policy details, premium amount, payout amount, and claim status using the frontend application.

## Future Enhancements

- Implementing an oracle service to fetch real-time data for premium calculation, such as pet breed, age, and health condition, from external sources.
- Adding an admin role to manage policy types, payout percentages, and other contract parameters.
- Enhancing the frontend application with a user-friendly interface and additional features such as policy search and filtering.
- Implementing a dispute resolution mechanism for handling claim disputes between policy holders and the insurance company.
- Integrating with a payment gateway for premium payments and policy payouts in cryptocurrency or fiat currency.

## License

This project is open-source and released under the MIT License. Feel free to use, modify, and distribute the code as per the license terms.

## Acknowledgements

This project uses OpenZeppelin's Solidity library for contract development and follows best practices for smart contract security. Special thanks to the Solidity and React communities for their contributions to the blockchain ecosystem.

For any issues or inquiries, please contact!
