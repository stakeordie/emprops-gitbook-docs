# Wallets FAQ

##

### Kukai doesn’t work, what’s going on?

There is a bug in Beacon that prevents us from telling Kukai what link. So we can’t predict if it will send users to mainnet or testnet. The solution is to update the URL when you go to Kukai if it is sending you to the wrong site.

\---



You may find that when you switch that the change doesn’t take effect on EmProps and you see and error. The reason for this is that you are signed in to Kukai in the “wrong” mode. To fix, sign out of Kukai in the it it defaulting to, Switching should now work\
\
\---\
\
Why does my wallet say the wrong network? / Why might I be getting wallet failures when I try to publish?

This is most like an issue with Temple wallet for XTZ but also effects Metamask. Lets take them one at a time.

Temple

When you connect temple to the site it connects with main or testnet. Once this connection is made, temple seems to ignore when we tell it to move to the other when you switch. So, the best bet is to disconnect and reconnect after switching networks.\
\
\
Similar to Temple there is no way to switch networks automatically. To switch you need to disconnect and reconnect. The catch is, as is shown in the Kukai Doesn’t work answer, you need to log out of ghostnet Kukai before try to connect to mainnet, or vice versa depending on the way your wallet connected to to Kukai originally.\
\
\---
