# Time Staking :

1.Deploy Memories.sol Token contract.
2.Deploy Time.sol token contract.
3.Deploy staking Contract.sol (timetokenaddress,memorytokenaddress,epochlength,firstepochnumber,firstepochtime)
Epochlength-28800
Firstepochnumber-284
Firstepochtime-1636812000
4.Deploy stakinghelper.sol contract
5.Deploy stakingwarmupcontract.sol (stakingaddress,memoryaddress)
6.Deploy uniswapv2factory contract set feetosetter with u r address(can be changed later)
7.Deploy ethtoken contract Name:Ether,Symbol:ETH
8.Deploy the anyswapv4router.sol(factory,wnative,mpc)
Factory-uniswapfactory address
Wnative-ethtoken address
Mpc-admin address
9.Deploy mim contract(name,symbol,decimals,undelying,vault)
Name-Magic Internet Memory
Symbol-MIM
Decimals-18
Underlying-0x0000000000000000000000000000000000000000
Vault-give u r address and then change it to anyswapv4router address
10.Deploy Time treasury contract (timetokenaddress,mim address)
11.Delpoy dao.sol -Multisigwalletwithdailylimit – change in dropdown (addressof owners,required)
Addressofowners – [“ur address”]
Required-1
12.Deploy timebonding calculator (timetokenaddress)
13.Deploy distributorcontract-(treasuryaddress,ohmaddress,epochlength,nextepochtime)
Ohmaddress-timetokenaddress
Epochlength-28800
Nextepochtime-1636812000

## Function changes-Timestaking.sol

setContract(\_contract,contract address):
0,distributor address
1,warmupcontract address
Memotoken contract:
Initialize(timestakingcontract address)
