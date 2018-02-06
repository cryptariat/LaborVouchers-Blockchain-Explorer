# LaborVouchers-Blockchain-Explorer
Block explorer for LaborVouchers CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon laborvouchersd. It should be accessible from the Internet. Run laborvouchersd with open port as follows:
```bash
./laborvouchersd --rpc-bind-ip=0.0.0.0 --rpc-bind-port=12023
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
