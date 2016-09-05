Updates:
--------
- Source code updated to litecoin v0.8.x branch
- uses boilerplate diff retarget and block rewards -> this needs major updates
- DNS Seeds set to null; need to set up nodes for actual network
- No genesis block created in this update for either network
- Fix leveldb permissions so daemon compiles correctly on unix
- Quick fix for client version so wallet doesn't incorrectly attempt downgrade
- Moved 'To Do' to a seperate file
- Windows Test Client compiled and running correctly

To Do:
------
- Reseed testnet and verify new coin distribution
- Create test genesis block for mainnet to run tests
- Change difficulty retarget algorithm
