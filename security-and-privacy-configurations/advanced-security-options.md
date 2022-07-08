# Additional Security Options

Wasabi Wallet offers several advanced options that will greatly improve the security of your funds and your privacy.

### Discreet Mode

When enabled, sensitive transaction and wallet information are hidden from physical observers. You can activate or deactivate by clicking the Discreet Mode button in the bottom left corner.&#x20;

* The wallet remains usable.
* Any information that you expand in the wallet will be revealed, Privacy Mode only offers surface level protection.

### Connect to your own full node

Connecting to your own node enables you to fetch information from it that Wasabi would otherwise fetch from external sources. Using Wasabi this way should give you more confidence about your privacy, because it simplifies some otherwise complex mechanisms. This is also your means of transacting without restrictions and for avoiding being defrauded. It's important to note that Wasabi's full node integration is still in experimental status.

#### Click on `Settings` (left-hand side), then select `Bitcoin` from the top menu.

There are three different ways of using your Bitcoin full node with Wasabi:

1. If you already have a full node on your computer, Wasabi will detect it.
2. You can connect to a remote node by specifying the local network IP address.
   * Enter the node IP address beside `Bitcoin P2P Endpoint`
3. You can start Bitcoin Knots in Wasabi wallet to begin downloading and running your own node on your computer. While previous alternatives only fetch blocks from your full node, this mode goes well beyond that, it utilizes the full node for various other services, like fetching network fees and using its mempool as source of truth for receiving unconfirmed transactions and detecting double spends.
