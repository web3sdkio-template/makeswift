# Visually build with Web3sdkio components

In this example, you'll learn how to integrate web3sdkio components from your Next.js app into [Makeswift](https://www.makeswift.com) to make it visually editable.

## Demo

[https://makeswift-examples-web3sdkio.vercel.app/](https://makeswift-examples-web3sdkio.vercel.app/)

## Deploy your own

Deploy your own with [Vercel](https://vercel.com/new/git/external?repository-url=https://github.com/makeswift/makeswift/tree/main/examples/web3sdkio&project-name=makeswift-web3sdkio-template&repository-name=makeswift-web3sdkio-template&env=MAKESWIFT_SITE_API_KEY&envDescription=The%20API%20key%20for%20your%20Makeswift%20site&envLink=https%3A%2F%2Fwww.makeswift.com%2Fdocs%2Fguides%2Fgetting-started%23configure-the-makeswift-site-api-key) or preview live with [StackBlitz](https://stackblitz.com/github/makeswift/makeswift/tree/main/examples/web3sdkio)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/makeswift/makeswift/tree/main/examples/web3sdkio&project-name=makeswift-web3sdkio-template&repository-name=makeswift-web3sdkio-template&env=MAKESWIFT_SITE_API_KEY&envDescription=The%20API%20key%20for%20your%20Makeswift%20site&envLink=https%3A%2F%2Fwww.makeswift.com%2Fdocs%2Fguides%2Fgetting-started%23configure-the-makeswift-site-api-key)

## Tools

- [**React SDK**](https://docs.web3sdk.io/react): to enable users to connect their wallets with the [useMetamask](https://docs.web3sdk.io/react/react.usemetamask) hook, and access hooks such as [useNFTDrop](https://docs.web3sdk.io/react/react.usenftdrop) to interact with the NFT drop contract.
- [**TypeScript SDK**](https://docs.web3sdk.io/typescript): to view the claimed supply, total supply, and mint NFTs from the drop.
- [**Makeswift SDK**](https://www.makeswift.com/docs): to register components into Makeswift's visual builder.

## Using this repo

1. **Create a site on Makeswift**

   Head over to [Makeswift](https://app.makeswift.com) and sign up for a free account. Create a site using the option to "Integrate with Next.js".

2. **Clone this template**

   Instead of using `create-next-app`, run this command from the terminal:

   ```bash
   npx web3sdkio create --template makeswift
   ```

3. **Update environment variables**

   Rename `.env.local.example` to `.env.local` and add your site API key from Makeswift.

   ```diff
   - MAKESWIFT_SITE_API_KEY=
   + MAKESWIFT_SITE_API_KEY=<YOUR_MAKESWIFT_SITE_API_KEY>
   ```

4. **Start the dev server**

   Run this command from the terminal:

   ```bash
   yarn dev
   # or
   npm run dev
   ```

   Your host should be up and running on http://localhost:3000.

5. **Add the NFT Drop component into your Makeswift page**

   Look for the ellipsis menu in the left toolbar and drop the NFT Drop component into Makeswift.

   With the NFT drop component selected, paste your NFT drop contract address from Web3sdkio into the "Contract address" panel and select the correct chain.

   > If you don't have an NFT drop contract, [read this guide](https://docs.web3sdk.io/guides/release-an-nft-drop-with-no-code#create-a-drop-contract) to learn how to create one using Web3sdkio without any code.

---

## Next steps

With Makeswift, you can give your marketing team hand-crafted Web3sdkio building blocks to create custom Web3 websites.

To learn more about Makeswift, take a look at the following resources:

- [Makeswift Website](https://www.makeswift.com/)
- [Makeswift Documentation](https://www.makeswift.com/docs/)
- [Makeswift Discord Community](https://discord.gg/dGNdF3Uzfz)

You can check out [the Makeswift GitHub repository](https://github.com/makeswift/makeswift) - your feedback and contributions are welcome!
