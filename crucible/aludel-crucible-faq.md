# FAQ 📖

{% embed url="https://youtu.be/8XJ1MSTEuU0" caption="Please watch this Video on Impermanent loss before subscribing LP" %}

## **How do I participate in the Aludel / How do I mint a Crucible NFT?**

To participate in the Aludel, you must mint a Crucible NFT and deposit some ⚗️$mist/ETH Uniswap LP tokens into it \(think of this as a virtual vault\). The Crucible then accrues rewards from the Aludel program proportional to the amount and duration of LP tokens that are Subscribed. The cost of minting a Crucible and Subscribing depends on the current gas prices of ethereum, you can expect it will be approx 0.1-0.2 ETH.

{% hint style="danger" %}
Crucible only supports the **Uniswap V2** Liquidity Pool. Adding liquidity to the **Uniswap V3** pool is not compatible with the Rewards Program.
{% endhint %}

{% hint style="warning" %}
**Precautions**

Do not use Brave browser as it is not compatible with the process at this time and you're transaction will fail resulting in lost fees.

We do not recommend using a hardware wallet at this time as many do not currently support EIP-712 signing. When they fix this, we can implement it.

Some users have reported issues with Trustwallet.

We do not recommend you do this on a mobile.
{% endhint %}

1. To mint a crucible go to the website, [alchemist.farm](https://alchemist.farm/)
2. Connect MetaMask wallet
3. Enter the amount of LP you wish you put into the Crucible. 
4. Hit “Mint Crucible and Subscribe LP to Aludel”. You will get 2 approvals via MetaMask pop up, sign these and wait for completion.
5. Next you will be asked to confirm the transaction, this normally costs around 0.1-0.2 Eth to create a Crucible, if you're happy with the gas price, press confirm and wait for the transaction to go through.
6. Once complete you will see your new Crucible in your Erc721 tokens tab on Etherscan.

**Why can’t I see my ⚗️Mist in my wallet?**

You can add the contract address **`0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`** to make them visible.

**Why can’t I see my LP in my wallet?**

You can add the contract address **`0xcd6bcca48069f8588780dfa274960f15685aee0e`** to make them visible.

**Why can’t I see my Crucible in my wallet?**

You can add the contract address **`0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`** to make your crucible\(s\) visible.

**What are the rewards for Subscribing in the Aludel?**

Rewards are distributed from the reward pool proportionally to the amount and duration of a Subscription. The more ⚗️$mist/ETH Uniswap LP tokens you Subscribe and the longer you leave it for, the more rewards it will accumulate. The Aludel reward program is designed to reward long term participants.

You can see the reward pool [here.](https://etherscan.io/address/0x04108d6e9a51bec5170f8fd953a156cf754ba541)

**How do I become an certified Alchemist in Discord?**

* Please use this [guide](how-to-become-a-certified-alchemist-on-discord.md)
* Join Discord
* Go to the Welcome channelType !join
* You will then get a message from the Collab.Land bot
* Connect Your wallet containing your ⚗️$mist
* The bot will then message you  ~ Updating roles, Please check assigned roles in Alchemist
* Close bot and return to the main alchemy channel and you will now be a certified Alchemist!

**How do I claim the rewards?**

All rewards are received when you "Claim Rewards and Unsubscribe LP". Be careful, this also resets your reward multiplier. You will need to use Taichi Network when doing this to prevent bots from front-running your rewards. See this [guide](guides-alchemist.farm/how-to-claim-rewards-and-unsubscribe-your-lp-from-the-aludel-using-the-taichi-network.md).

**Does it matter how many LP tokens go into the Crucible?**

The more LP tokens you get the higher amount of liquidity you provided therefore a larger percentage of the rewards pool you will receive. There is no minimum LP required, but we do suggest you be mindful of the ethereum gas cost when considering this.

**Is it more advantageous to have more Crucibles or a higher Subscription in one Crucible?**

It’s almost always better to accumulate LP in a single Crucible as it minimizes the gas costs.

The only time you would use multiple Crucibles is if you aim to transfer / sell a Crucible with some active Subscription on it.

**How does "Claim Rewards and Unsubscribe LP" impact the reward multiplier?**

Every time you put LP tokens in the Aludel reward program, it keeps track of how long those tokens are Subscribed. The Aludel applies a reward multiplier which starts at 1x and increases to 10x over 60 days. When you claim a partial amount, the Aludel first claims from the Subscription with the lowest multiplier \(Last In, First Out\).

**Can I somehow see how much rewards I have acquired in the meantime?**

You can see the accumulated reward for your crucible by using the UI at [alchemist.farm](https://alchemist.farm) and the accumulated Uniswap LP fees using [apy.vision](https://apy.vision/) or [croco.finance](https://croco.finance/)

**Can I add more LP to an existing Crucible?**

Yes. The gas for adding more LPs to your current Crucible will be much lower than when you initially minted a Crucible. Each Subscription event is independent, so any LP you add will start their own multiplier independently.

**Does “Claim Rewards and Unsubscribe LP” remove my LP & rewards from the Crucible?**

No. This only claims the rewards earned, your LP will remain in the Crucible until you “Withdraw Unsubscribed LP”.

**Does “Withdraw Unsubscribed LP” destroy the Crucible?**

No, it only empties it. You retain the empty Crucible.

**Can I transfer the Crucible NFT to another wallet?**

Yes, the ownership of the NFT \(and the Subscribed LP tokens\) can be transferred to any ERC721 compatible wallet. This can be done via the "Transfer Crucible" button on [alchemist.farm](https://alchemist.farm/)

**If I transfer my Crucible from one wallet to another will that reset the multiplier?**

No, as long as the rewards are not unsubscribed from the Aludel.

