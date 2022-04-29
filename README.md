First deploy your token.

Deploy the mock oracle, you will need to define a price in eth that the mock oracle will return.

Deploy the lending pool

In the lending pool whitelist your token -
  i - This is done by calling the set allowed token function in the lending contract.
  ii - for calling this function you will need the address in which your token and the mock oracle were deployed.
