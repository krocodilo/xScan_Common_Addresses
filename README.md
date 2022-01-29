# xScan_Duplicate_Finder

Piece of software to help analyse the history of a certain blockchain address using the APIs of online platforms such as etherscan.com, bscscan.com and others in the same family.

It finds addresses used more than once, for transactions going both In and Out. 

## Usage
```
Usage:  <executable> <address> [options]
Options:
        -h              ->      Print this help menu
        --hostname      ->      Specify the hostname of the API server (default: "api.etherscan.io")
        --last          ->      Request the last X transactions (default: 10000)
        --token         ->      Specify your API token (default: "YourApiKeyToken")
        --top           ->      Show the top X most used addresses (default: 10)

You can also use the config.ini file, but keep in mind that CLI arguments have higher priority.
```