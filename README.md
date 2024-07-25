# ethtool

```
$credential = Credential::fromWallet('123','./keystore/22cfeaa4523c1bf85b9ee6a5c1b86f97832630f7.json');
echo $credential->getPrivateKey() . PHP_EOL;
echo $credential->getPublicKey() . PHP_EOL;
echo $credential->getAddress() . PHP_EOL;
```