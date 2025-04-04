# LazySql

***LazySql is an open-source tool designed for SQL injection testing. It offers robust functionality and is built to work effectively against 2 mode time based mode and Error based mode***
## FrameWork Mode
![image](https://github.com/user-attachments/assets/4f1e99e9-0cff-4424-a682-191593d9f334)
```
 lazysql
[*] StartinG the LazySQL Framework console... -
[*] LazySQL Framework Loaded!

Call trans opt: received. 2-19-98 13:24:18 REC:Loc

     Trace program: running

           wake up, Neo...
        the matrix has you
      follow the white rabbit.

          knock, knock, Neo.


                        (`.         ,-,
                        ` `.    ,;' /
                         `.  ,'/ .'
                          `. X /.'
                .-;--''--.._` ` (
              .'            /   `
             ,           ` '   Q '
             ,         ,   `._    \
          ,.|         '     `-.;_'
          :  . `  ;    `  ` --,.._;
           ' `    ,   )   .'
              `._ ,  '   /_
                 ; ,''-,;' ``-
                  ``-..__``--`

                             https://lazysql.example.com

       =[ LazySQL v1.0-dev                          ]
+ -- --=[ 2 Modes - Error & Time Payloads    ]
+ -- --=[ File mode - URL mode - Pipeline    ]
+ -- --=[ SQL Injection Scanner              ]

LazySQL Documentation: https://docs.lazysql.example.com/

sql6 >

```
## Command Line Mode

```
 lazysql -h
╔══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║                                              ██╗      █████╗ ███████╗██╗   ██╗    ███████╗ ██████╗ ██╗                                                   ║
║                                              ██║     ██╔══██╗╚══███╔╝╚██╗ ██╔╝    ██╔════╝██╔═══██╗██║                                                   ║
║                                              ██║     ███████║  ███╔╝  ╚████╔╝     ███████╗██║   ██║██║                                                   ║
║                                              ██║     ██╔══██║ ███╔╝    ╚██╔╝      ╚════██║██║▄▄ ██║██║                                                   ║
║                                              ███████╗██║  ██║███████╗   ██║       ███████║╚██████╔╝███████╗                                              ║
║                                              ╚══════╝╚═╝  ╚═╝╚══════╝   ╚═╝       ╚══════╝ ╚══▀▀═╝ ╚══════╝                                              ║
║                                                                      v1.0 By Iamunixtz                                                                   ║
╚══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╝
usage: lazysql [-h] [-u URL] [-r URLS_FILE] [-p] [-o OUTPUT_FILE] [--proxy PROXY] [--error-payload ERROR_PAYLOAD] [--time-payload TIME_PAYLOAD]
               [--single-error-payload SINGLE_ERROR_PAYLOAD] [--single-time-payload SINGLE_TIME_PAYLOAD] [--discord DISCORD] [--headers HEADERS]
               [--threads THREADS] [-X {BOTH}] [-T] [-E]

Detect error-based and time-based SQL injection

options:
  -h, --help            show this help message and exit
  -u, --url URL         Single URL for the target
  -r, --urls_file URLS_FILE
                        File containing a list of URLs
  -p, --pipeline        Read from pipeline
  -o, --output OUTPUT_FILE
                        Output file for logs
  --proxy PROXY         Proxy (e.g., http://127.0.0.1:8080)
  --error-payload ERROR_PAYLOAD
                        File with error-based payloads (default: errorbased.txt)
  --time-payload TIME_PAYLOAD
                        File with time-based payloads (default: payloads.txt)
  --single-error-payload SINGLE_ERROR_PAYLOAD
                        Single error-based payload
  --single-time-payload SINGLE_TIME_PAYLOAD
                        Single time-based payload
  --discord DISCORD     Discord Webhook URL
  --headers HEADERS     File with headers (default: headers.txt)
  --threads THREADS     Number of threads
  -X {BOTH}             Test both error-based and time-based SQL injection
  -T, --time            Test only time-based SQL injection on headers
  -E, --error           Test only error-based SQL injection on URL and parameters
```


## Usage
```
sql6 > help

LazySQL Usage Manual:
Commands:
SET TARGET_URLS <url>          - Set a single target URL
SET URLS_FILE <file>           - Set a file containing URLs
SET PIPELINE                   - Read URLs from pipeline (stdin)
SET PROXY <proxy>              - Set proxy (e.g., http://127.0.0.1:8080)
SET ERROR_PAYLOAD <file>       - Set error payload file
SET TIME_PAYLOAD <file>        - Set time payload file
SET SINGLE_ERROR <payload>     - Set single error payload
SET SINGLE_TIME <payload>      - Set single time payload
SET WEBHOOK <url>              - Set Discord webhook URL
SET HEADERS <file>             - Set headers file
SET THREADS <number>           - Set number of threads
SET OUTPUT <file>              - Set output log file
SET MODE <ERROR|TIME|BOTH>     - Set testing mode
OPTIONS                        - Show current settings
RUN | EXPLOIT                  - Start the scanning process
HELP                           - Show this manual
EXIT                           - Exit LazySQL
sql6 >
```

## Installation
```
apt update && apt upgrade
git clone https://github.com/iamunixtz/LazySql/
cd LazySql
pip install -r requirement.txt 
sudo mv lazysql /usr/local/bin
chmod +x /usr/local/bin/lazysql
lazysql
```


**NB:Tool under development mode Happy Hunting**








