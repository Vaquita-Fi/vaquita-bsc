# Protocol Vaquita

![Texto alternativo](/vaquina.png)

Protocol Vaquinha is a community savings protocol inspired by the traditional Andean savings system known as Pasanaku. This protocol leverages blockchain technology to solve trust issues, allowing users to organize and participate in group savings systems with complete transparency and security. Vaquinha Protocol scales these traditional systems to the digital world, providing global access to communities that need reliable shared savings solutions.

## 🌐 Resources

- 🚀 **Demo:** Check out the live demo of the project [here](https://vaquita-fi-bsc.vercel.app/)
- 📂 **Repo:** Explore the project repository on [GitHub](https://github.com/Vaquita-Fi/vaquita-bsc).
- 🎥 **Pitch Deck:** This is the pitch deck for the project, providing a concise overview of its key elements. It helps to understand the problem, solution, business model, and overall impact more clearly. [Watch the Pitch Deck](https://www.loom.com/share/7eeb25ece45e45e084f13e8f811739fb?sid=8cba32ec-3d0e-4b07-b9e2-6b18b154a9a9)
- 💻 **Binance Smart Chain Testnet Contract:** `0xAe49A6520205fB223CAB1Fe17B1373ab979946e0` — View the [Vaquita Program](https://testnet.bscscan.com/address/0xAe49A6520205fB223CAB1Fe17B1373ab979946e0).

  **Methods:**

  - 🏁 `initializeRound`: Creates a new Round and adds collateral.
  - 🙋‍♂️ `addPlayer`: Adds a player to the round and their collateral.
  - 💰 `payTurn`: Pays the current turn in the round.

## Setup

To ensure all components work seamlessly, set the following environment variables in your `.env` file using `.env.local.example` as a reference.

You can find the API key on the [Coinbase Developer Portal's OnchainKit page](https://portal.cdp.coinbase.com/products/onchainkit). If you don't have an account, you will need to create one.

You can find your Wallet Connector project ID at [Wallet Connect](https://cloud.walletconnect.com).

```sh
# See https://portal.cdp.coinbase.com/products/onchainkit
NEXT_PUBLIC_CDP_API_KEY="GET_FROM_COINBASE_DEVELOPER_PLATFORM"

# See https://cloud.walletconnect.com
NEXT_PUBLIC_WC_PROJECT_ID="GET_FROM_WALLET_CONNECT"
```

<br />

## Locally run

```sh
# Install bun in case you don't have it
curl -fsSL https://bun.sh/install | bash

# Install packages
bun i

# Run Next app
bun run dev
```

<br />

## Resources

- [OnchainKit documentation](https://onchainkit.xyz)
- We use the [OnchainKit Early Adopter](https://github.com/neodaoist/onchainkit-early-adopter) contract written by neodaoist [[X]](https://x.com/neodaoist)

## Additional Resources for Binance Smart Chain Testnet

- 💵 **Faucet USDC:** [Access the USDC Faucet](https://testnet.bscscan.com/token/0x4b8eed87b61023f5beccebd2868c058fee6b7ac7?a=0x711ff445c1931a7899238b1626eba589195e1c3c#writeContract)
- 💰 **Faucet BNB Token:** [Get BNB Testnet Tokens](https://www.bnbchain.org/en/testnet-faucet)

<br />

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
