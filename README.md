# Ebay Smart Contract With Javascript Testing

### About Smart Contract
- This is a Solidity smart contract for an Ebay-like auction platform.

- The contract contains two struct types, Auction and Offer, which define the properties of an auction and an offer, respectively. The contract also includes four mapping variables to store auction and offer information: auctions, offers, auctionList, and offerList.

- The createAuction() function allows a user to create a new auction with a name, description, and minimum price.
- The createOffer() function allows a user to make an offer on an existing auction by sending ether to the contract. If the offer is greater than the current best offer, the best offer is updated to the new offer.
- The transaction() function allows the seller of an auction to withdraw the funds from the best offer and distribute them to the buyer and any other bidders.

- The contract also includes three getter functions: getAuctions(), getUserAuctions(), and getUserOffer(). getAuctions() returns an array of all auctions on the platform, getUserAuctions() returns an array of auctions created by a specific user, and getUserOffer() returns an array of offers made by a specific user.

- Finally, the contract includes a modifier called auctionExists() that checks whether an auction exists before executing a function that requires an auction ID as input.

### License
- This project is licensed under the MIT.

##### Note: 
- This contract is intended for educational and experimental purposes only and should not be used for any actual auction system without complete satisfaction.
